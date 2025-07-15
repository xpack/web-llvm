---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/apfloat
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `APFloat` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::APFloat { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">llvm/ADT/APFloat.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase">APFloatBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A self-contained host- and target-independent arbitrary-precision floating-point software implementation. <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">detail::IEEEFloat</a> <a href="#a046ad3e7d995bcb705ba0a6b2ae31a59">IEEEFloat</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">detail::DoubleAPFloat</a> <a href="#a8fb3ee99500c25c79431c9c13b48c729">DoubleAPFloat</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec8b5b1495be8560aad61368e3a65264">hash_value</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See friend declarations above. <a href="#aec8b5b1495be8560aad61368e3a65264">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac80f9443595260c6f6cb446849521325">ilogb</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6f3e137b277266516df5fd9eb692719">scalbn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fccce07c15282e9fd964254f21d81c7">frexp</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a674fe76f94de32f3a20c21504f1a9cd8">APFloat</a> (const fltSemantics &amp;Semantics)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a271da21b4c6619b24fcdb30bc6c82ed1">APFloat</a> (const fltSemantics &amp;Semantics, StringRef S)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b80de807a1f0bcd41bfa0d76c64de39">APFloat</a> (const fltSemantics &amp;Semantics, integerPart I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a5f183f8fe94a7e0291b35ccaefd470c4">APFloat</a> (const fltSemantics &amp;Semantics, T V)=delete</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb93f57b514b59c063c125768c57771b">APFloat</a> (const fltSemantics &amp;Semantics, uninitializedTag)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd147a3ee2d7379f47b9197c2ce2f912">APFloat</a> (const fltSemantics &amp;Semantics, const APInt &amp;I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d01e127e68e5892e266e055d0e67094">APFloat</a> (double d)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf992210f35921e854458eb836175ba7">APFloat</a> (float f)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18cb545067209aacc017227371e346fa">APFloat</a> (const APFloat &amp;RHS)=default</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3be3be81acaf5d9fcb8d8bc41d7dbdc5">APFloat</a> (APFloat &amp;&amp;RHS)=default</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc1d610f53e483ee2697e6eebc5d86a8">APFloat</a> (IEEEFloat F, const fltSemantics &amp;S)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6f5f22d42991c783a527f785603a3aa">APFloat</a> (DoubleAPFloat F, const fltSemantics &amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bd571701cd25b64ebd51a90adfc6b5f">~APFloat</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98d55d6fc5c66837024b06bfc115ed4c">operator-</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Negate an <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a>. <a href="#a98d55d6fc5c66837024b06bfc115ed4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a302f4ab2cb810c2763fc7aef728145cf">operator+</a> (const APFloat &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add two APFloats, rounding ties to the nearest even. <a href="#a302f4ab2cb810c2763fc7aef728145cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a656998434061ad466f2177bf41173775">operator-</a> (const APFloat &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subtract two APFloats, rounding ties to the nearest even. <a href="#a656998434061ad466f2177bf41173775">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a662962ee7a570f3dcbb3b0826b9985e0">operator*</a> (const APFloat &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Multiply two APFloats, rounding ties to the nearest even. <a href="#a662962ee7a570f3dcbb3b0826b9985e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a931608d42edab0dd403d65dec89e95e8">operator/</a> (const APFloat &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Divide the first <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> by the second, rounding ties to the nearest even. <a href="#a931608d42edab0dd403d65dec89e95e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abde24e929388be14e369195541847ac7">operator==</a> (const APFloat &amp;RHS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ced4849b1d8bc242491248da1bf66c9">operator!=</a> (const APFloat &amp;RHS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70eee025af91f471b6e367b988fcd734">operator&lt;</a> (const APFloat &amp;RHS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e343b52f5d5006c7ee1f558e4650951">operator&gt;</a> (const APFloat &amp;RHS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afde15e39fbdaa60019f320862b1495b0">operator&lt;=</a> (const APFloat &amp;RHS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8d18be4722edccea943a9da193c1e7f">operator&gt;=</a> (const APFloat &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fcde202082bf523d879268e4bb2e119">operator=</a> (const APFloat &amp;RHS)=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14055236d585a1d62cfd702f81bde775">operator=</a> (APFloat &amp;&amp;RHS)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba402b558169083d42683af51ae36016">needsCleanup</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0215397085e3a37d4a6efd65ec877861">Profile</a> (FoldingSetNodeID &amp;NID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to insert <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> objects, or objects that contain <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> objects, into FoldingSets. <a href="#a0215397085e3a37d4a6efd65ec877861">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44602b2ea058f08b290a8fa0185909d1">add</a> (const APFloat &amp;RHS, roundingMode RM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27bc3a1b1f84258afe7e981fb707f646">subtract</a> (const APFloat &amp;RHS, roundingMode RM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82567bb6632fa71c7c727b9464368173">multiply</a> (const APFloat &amp;RHS, roundingMode RM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a107d394b970c9f03a486a15cdd08f0df">divide</a> (const APFloat &amp;RHS, roundingMode RM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95aaadfb3026e47b75223d2733df62f1">remainder</a> (const APFloat &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3126d0302ebe7754bf962fdaa25e286">mod</a> (const APFloat &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9180d9a8c1fc9693c4b0a50937e904e6">fusedMultiplyAdd</a> (const APFloat &amp;Multiplicand, const APFloat &amp;Addend, roundingMode RM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4eca54fe8b71670e3bd3a2b18469d73">roundToIntegral</a> (roundingMode RM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0fdc79bb75e8fe845f98e2199f9d451">next</a> (bool nextDown)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7fe7691e456e49addd866aa23896387">changeSign</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69cb669b1adc09cca90312d39ea3021a">clearSign</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cfd2be1063599384fd6e6172264a979">copySign</a> (const APFloat &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74b616ebc9fe99bb3d64e0f8181d8de7">makeQuiet</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assuming this is an IEEE-754 NaN value, quiet its signaling bit. <a href="#a74b616ebc9fe99bb3d64e0f8181d8de7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a257e3cb529defa79ad7a9f42072f339a">convert</a> (const fltSemantics &amp;ToSemantics, roundingMode RM, bool *losesInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae1f09de4bf1aab27149a7d328715e30">convertToInteger</a> (MutableArrayRef&lt; integerPart &gt; Input, unsigned int Width, bool IsSigned, roundingMode RM, bool *IsExact) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebaffb4b288b2508f99e75e0e8bd3ed9">convertToInteger</a> (APSInt &amp;Result, roundingMode RM, bool *IsExact) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a046fe3d1230e4804494ce18bae1175">convertFromAPInt</a> (const APInt &amp;Input, bool IsSigned, roundingMode RM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc309055edb782bba7bcb11b415dd17">convertFromSignExtendedInteger</a> (const integerPart *Input, unsigned int InputSize, bool IsSigned, roundingMode RM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8026384a9b6bfd57046298ab64b0ea1">convertFromZeroExtendedInteger</a> (const integerPart *Input, unsigned int InputSize, bool IsSigned, roundingMode RM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6a">opStatus</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac83df2fb4fcefd0a95deb09db83a0635">convertFromString</a> (StringRef, roundingMode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c5a2112c559ffbe2c7bbf5698b6482f">bitcastToAPInt</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37733c4c22afc6a48194783dbd25487c">convertToDouble</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Converts this <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> to host double value. <a href="#a37733c4c22afc6a48194783dbd25487c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8269fab998356ea27a76ad45bd6cc8fe">convertToFloat</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Converts this <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> to host float value. <a href="#a8269fab998356ea27a76ad45bd6cc8fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1373bb8e8796d3b0b642b42cf55296ec">cmpResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af739a28663314781780783f9741801a8">compare</a> (const APFloat &amp;RHS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28cbb0780286695406353e6a295e12c8">bitwiseIsEqual</a> (const APFloat &amp;RHS) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43efe9700a64d52fdf51d350923eef33">isExactlyValue</a> (double V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We don't rely on operator== working on double values, as it returns true for things that are clearly not equal, like -0.0 and 0.0. <a href="#a43efe9700a64d52fdf51d350923eef33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80fcf8584733a9b06176373b10e49b17">convertToHexString</a> (char *DST, unsigned int HexDigits, bool UpperCase, roundingMode RM) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aaed17970b55e9e1bfa906822ea7b71">isZero</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdbfe0ba27cece5e333f4a7ae68fa82e">isInfinity</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a763d4ccd87f2c21d2079796c0c9cd51a">isNaN</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b901c3a0625a7d7173e9bd4864e2775">isNegative</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43c6c871e61d6071a20a680aa2a08009">isDenormal</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a833f6b183e2adebde0fb463e6a6297fe">isSignaling</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43257671f610226d09cfb0ad8d5e7d6b">isNormal</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72c0ccd36e5b427a58262f9481c9c61c">isFinite</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#ada22bd638e0df004a3337fea421c4b44">fltCategory</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9818805994c902a893e9c4c86f50caf">getCategory</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a643f8cd038a6fa41604fe8e3df11f977">getSemantics</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67847bcacd8e684f0449be8f1ec90f29">isNonZero</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a152743f94b060fbc99d10736c1b430e5">isFiniteNonZero</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac37cd93f2c41a818a278e99de784ba1d">isPosZero</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad57f69ac4fa1d889dc657d52e8a51ef1">isNegZero</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b1180f8b5b3af0d2aa0876e590f8690">isPosInfinity</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1af637e15f22d5e9b99800a0fabe12c">isNegInfinity</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa34fa2837fa3f7355fe90cbca1555e0">isSmallest</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e937642977dd028fb0b5293f30ee47d">isLargest</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace4517dbbab7dbdefa0d31e29db55969">isInteger</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3bec23b6e372e677f17151bfd6af8fc">isIEEE</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8943302f831d2fc16d84eaf1f2740ed">isSmallestNormalized</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc7c5f3ebb11d0aaf551f3b37ab16437">classify</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a> which will return true for the value. <a href="#abc7c5f3ebb11d0aaf551f3b37ab16437">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a416dc650964ad640df99464a32aa49da">toString</a> (SmallVectorImpl&lt; char &gt; &amp;Str, unsigned FormatPrecision=0, unsigned FormatMaxPadding=3, bool TruncateZero=true) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad88e80162417db584dd417cc946c57b3">print</a> (raw_ostream &amp;) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4e64a2bbbacfa304679cbdd5db87098">dump</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a133fbd343970e5f7e689c3b94185a605">getExactInverse</a> (APFloat *inv) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ab8e0eab61769d9974aeed9345ce11baf">LLVM_READONLY</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a268f8980dd0cba08690326624d4c7235">getExactLog2Abs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ab8e0eab61769d9974aeed9345ce11baf">LLVM_READONLY</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44d70cf308906fa36b66a9796dc0b6e3">getExactLog2</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a6d0b44cf07432415ae0a82d57f337f">getIEEE</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0cc28ecab09e9e66a66b2e52f447f09">getIEEE</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53457f4042afc32d14e54842d3bd011a">makeZero</a> (bool Neg)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b5ae7111a5157e39f87525ab7e3bea0">makeInf</a> (bool Neg)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b55f121ce68f75060269c29f756e728">makeNaN</a> (bool SNaN, bool Neg, const APInt *fill)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c9263666a922badddc8d25eab235b9c">makeLargest</a> (bool Neg)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90010bf62ff62d8aad5de12ec1bb2252">makeSmallest</a> (bool Neg)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6017520ecdb4cfdcb8dff80040b7eeb5">makeSmallestNormalized</a> (bool Neg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1373bb8e8796d3b0b642b42cf55296ec">cmpResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e8f9674b7a3078ebb8ea18e2cb1d050">compareAbsoluteValue</a> (const APFloat &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2a27c01ab688eb9eb2e470de3676133">IEEEFloat</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a368919de899363c960656bee29bc6f69">DoubleAPFloat</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union llvm::APFloat::Storage</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5434e967269f6c816bebddc643f52681">U</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af591f8d18d0d9773192a0ffcca41796e">getZero</a> (const fltSemantics &amp;Sem, bool Negative=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Factory for Positive and Negative Zero. <a href="#af591f8d18d0d9773192a0ffcca41796e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f8802ce4f0a7839abb4c836cb52138a">getOne</a> (const fltSemantics &amp;Sem, bool Negative=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Factory for Positive and Negative One. <a href="#a7f8802ce4f0a7839abb4c836cb52138a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab35b08ed1345493af2c69fbb71e4d0c3">getInf</a> (const fltSemantics &amp;Sem, bool Negative=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Factory for Positive and Negative Infinity. <a href="#ab35b08ed1345493af2c69fbb71e4d0c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeecd5fa66870de83d235933a683b5952">getNaN</a> (const fltSemantics &amp;Sem, bool Negative=false, uint64_t payload=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Factory for NaN values. <a href="#aeecd5fa66870de83d235933a683b5952">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a010e22ea9432c4b7d5962406932ed27b">getQNaN</a> (const fltSemantics &amp;Sem, bool Negative=false, const APInt *payload=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Factory for QNaN values. <a href="#a010e22ea9432c4b7d5962406932ed27b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07d7341cdcfc7d01525ca04b10fce7a9">getSNaN</a> (const fltSemantics &amp;Sem, bool Negative=false, const APInt *payload=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Factory for SNaN values. <a href="#a07d7341cdcfc7d01525ca04b10fce7a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa67fe0741c2b3712630ae636f8c2c20">getLargest</a> (const fltSemantics &amp;Sem, bool Negative=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the largest finite number in the given semantics. <a href="#aaa67fe0741c2b3712630ae636f8c2c20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbed2fc7a4a18eea942e56d6b7583c1e">getSmallest</a> (const fltSemantics &amp;Sem, bool Negative=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the smallest (by magnitude) finite number in the given semantics. <a href="#abbed2fc7a4a18eea942e56d6b7583c1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c568ab8748aba5d37006d52618bbcfd">getSmallestNormalized</a> (const fltSemantics &amp;Sem, bool Negative=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the smallest (by magnitude) normalized finite number in the given semantics. <a href="#a9c568ab8748aba5d37006d52618bbcfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a581d4a580ff88de698682f78a554b2fa">getAllOnesValue</a> (const fltSemantics &amp;Semantics)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a float which is bitcasted from an all one value int. <a href="#a581d4a580ff88de698682f78a554b2fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0ef7731beb4deaba4d953f79e1731d1">hasSignificand</a> (const fltSemantics &amp;Sem)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the given semantics has actual significand. <a href="#af0ef7731beb4deaba4d953f79e1731d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada08ec10c9c11a30327565d8fc7f852e">copySign</a> (APFloat Value, const APFloat &amp;Sign)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A static helper to produce a copy of an <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> value with its sign copied from some other <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a>. <a href="#ada08ec10c9c11a30327565d8fc7f852e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa0e0afb05651563e72d0efb97fd93b4a">usesLayout</a> (const fltSemantics &amp;Semantics)</td>
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


<p>Definition at line 905 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### DoubleAPFloat {#a8fb3ee99500c25c79431c9c13b48c729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef detail::DoubleAPFloat llvm::APFloat::DoubleAPFloat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 907 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### IEEEFloat {#a046ad3e7d995bcb705ba0a6b2ae31a59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef detail::IEEEFloat llvm::APFloat::IEEEFloat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 906 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### frexp {#a9fccce07c15282e9fd964254f21d81c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; X, int &amp; Exp, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### hash\_value {#aec8b5b1495be8560aad61368e3a65264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Arg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See friend declarations above.</p>


<p>These additional declarations are required in order to compile LLVM with IBM xlC compiler.</p>


<p>Declaration at line 1499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5440 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#a643f8cd038a6fa41604fe8e3df11f977">getSemantics</a>, <a href="#aec8b5b1495be8560aad61368e3a65264">hash_value</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#aec8b5b1495be8560aad61368e3a65264">hash_value</a>.</p>

</div>
</div>

### ilogb {#ac80f9443595260c6f6cb446849521325}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend int <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Arg</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1500 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="#ac80f9443595260c6f6cb446849521325">ilogb</a>.</p>


<p>Referenced by <a href="#ac80f9443595260c6f6cb446849521325">ilogb</a>.</p>

</div>
</div>

### scalbn {#ab6f3e137b277266516df5fd9eb692719}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> X, int Exp, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### APFloat() {#a674fe76f94de32f3a20c21504f1a9cd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APFloat::APFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Semantics)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1060 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### APFloat() {#a271da21b4c6619b24fcdb30bc6c82ed1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APFloat::APFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Semantics, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1061 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5448 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="#ac83df2fb4fcefd0a95deb09db83a0635">convertFromString</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>.</p>

</div>
</div>

### APFloat() {#a5b80de807a1f0bcd41bfa0d76c64de39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APFloat::APFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Semantics, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a86aa96e22d365ebc7653372bed96a778">integerPart</a> I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1062 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### APFloat() {#a5f183f8fe94a7e0291b35ccaefd470c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = std::enable_if_t&lt;std::is_floating_point&lt;T&gt;::value&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APFloat::APFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Semantics, T V)</td>
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



<p>Definition at line 1065 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### APFloat() {#acb93f57b514b59c063c125768c57771b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APFloat::APFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Semantics, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a486e96424b2741b19c72dca18e17567f">uninitializedTag</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1067 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a486e96424b2741b19c72dca18e17567fa94fac5b2829fc1204d02e14326e2f479">llvm::APFloatBase::uninitialized</a>.</p>

</div>
</div>

### APFloat() {#afd147a3ee2d7379f47b9197c2ce2f912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APFloat::APFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Semantics, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1069 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### APFloat() {#a4d01e127e68e5892e266e055d0e67094}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APFloat::APFloat (double d)</td>
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



<p>Definition at line 1070 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>.</p>

</div>
</div>

### APFloat() {#adf992210f35921e854458eb836175ba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APFloat::APFloat (float f)</td>
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



<p>Definition at line 1071 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a0c5765e9acba977f6e462c2917276d8f">llvm::APFloatBase::IEEEsingle</a>.</p>

</div>
</div>

### APFloat() {#a18cb545067209aacc017227371e346fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APFloat::APFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS)</td>
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



<p>Definition at line 1072 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### APFloat() {#a3be3be81acaf5d9fcb8d8bc41d7dbdc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APFloat::APFloat (<a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp;&amp; RHS)</td>
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



<p>Definition at line 1073 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### APFloat() {#abc1d610f53e483ee2697e6eebc5d86a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APFloat::APFloat (<a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat">IEEEFloat</a> F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; S)</td>
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



<p>Definition at line 1045 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### APFloat() {#ad6f5f22d42991c783a527f785603a3aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APFloat::APFloat (<a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat">DoubleAPFloat</a> F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; S)</td>
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



<p>Definition at line 1046 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~APFloat() {#a2bd571701cd25b64ebd51a90adfc6b5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::APFloat::~APFloat ()</td>
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



<p>Definition at line 1075 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator-() {#a98d55d6fc5c66837024b06bfc115ed4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::APFloat::operator- ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Negate an <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a>.</p>

<p>Definition at line 1262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### operator-() {#a656998434061ad466f2177bf41173775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::APFloat::operator- (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Subtract two APFloats, rounding ties to the nearest even.</p>


<p>No error checking.</p>


<p>Definition at line 1278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>.</p>

</div>
</div>

### operator!=() {#a5ced4849b1d8bc242491248da1bf66c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1373bb8e8796d3b0b642b42cf55296eca95e6b9c1e27b4949da4c40f5afb842a6">llvm::APFloatBase::cmpEqual</a>, <a href="#af739a28663314781780783f9741801a8">compare</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator\*() {#a662962ee7a570f3dcbb3b0826b9985e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::APFloat::operator* (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Multiply two APFloats, rounding ties to the nearest even.</p>


<p>No error checking.</p>


<p>Definition at line 1286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>.</p>

</div>
</div>

### operator/() {#a931608d42edab0dd403d65dec89e95e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::APFloat::operator/ (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Divide the first <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> by the second, rounding ties to the nearest even.</p>


<p>No error checking.</p>


<p>Definition at line 1294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>.</p>

</div>
</div>

### operator+() {#a302f4ab2cb810c2763fc7aef728145cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::APFloat::operator+ (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add two APFloats, rounding ties to the nearest even.</p>


<p>No error checking.</p>


<p>Definition at line 1270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>.</p>

</div>
</div>

### operator&lt;() {#a70eee025af91f471b6e367b988fcd734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1373bb8e8796d3b0b642b42cf55296eca6bd5099a8de38cdb7b0a65bf451c4fa7">llvm::APFloatBase::cmpLessThan</a>, <a href="#af739a28663314781780783f9741801a8">compare</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt;=() {#afde15e39fbdaa60019f320862b1495b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::operator&lt;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1373bb8e8796d3b0b642b42cf55296eca95e6b9c1e27b4949da4c40f5afb842a6">llvm::APFloatBase::cmpEqual</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1373bb8e8796d3b0b642b42cf55296eca6bd5099a8de38cdb7b0a65bf451c4fa7">llvm::APFloatBase::cmpLessThan</a>, <a href="#af739a28663314781780783f9741801a8">compare</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator=() {#a4fcde202082bf523d879268e4bb2e119}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat &amp; llvm::APFloat::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS)</td>
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



<p>Definition at line 1473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator=() {#a14055236d585a1d62cfd702f81bde775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat &amp; llvm::APFloat::operator= (<a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp;&amp; RHS)</td>
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



<p>Definition at line 1474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#abde24e929388be14e369195541847ac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1373bb8e8796d3b0b642b42cf55296eca95e6b9c1e27b4949da4c40f5afb842a6">llvm::APFloatBase::cmpEqual</a>, <a href="#af739a28663314781780783f9741801a8">compare</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt;() {#a8e343b52f5d5006c7ee1f558e4650951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::operator&gt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1373bb8e8796d3b0b642b42cf55296eca9f45fb1a56fb0564ec5ede93dad96cc4">llvm::APFloatBase::cmpGreaterThan</a>, <a href="#af739a28663314781780783f9741801a8">compare</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt;=() {#ab8d18be4722edccea943a9da193c1e7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::operator&gt;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1373bb8e8796d3b0b642b42cf55296eca95e6b9c1e27b4949da4c40f5afb842a6">llvm::APFloatBase::cmpEqual</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a1373bb8e8796d3b0b642b42cf55296eca9f45fb1a56fb0564ec5ede93dad96cc4">llvm::APFloatBase::cmpGreaterThan</a>, <a href="#af739a28663314781780783f9741801a8">compare</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a44602b2ea058f08b290a8fa0185909d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">opStatus llvm::APFloat::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a643f8cd038a6fa41604fe8e3df11f977">getSemantics</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2664741ca8fa0d154ef9e738aef0db7b">llvm::ConstantFoldFPBinOp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae97ea168cb4b3418065ffd29f4217956">llvm::SelectionDAG::foldConstantFPMath</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae53e791e2762b79bf164fb1802e3292b">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#a314c190b5e7220bc1daa2c7fa271a63c">llvm::detail::DoubleAPFloat::multiply</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a>.</p>

</div>
</div>

### bitcastToAPInt() {#a9c5a2112c559ffbe2c7bbf5698b6482f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::APFloat::bitcastToAPInt ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#a9c5a2112c559ffbe2c7bbf5698b6482f">bitcastToAPInt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a7ed44f2251a99b3c609481e114ae9295">llvm::DwarfExpression::addConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acdbc6c6e847bf30e629b1de682424b8d">llvm::DwarfUnit::addConstantFPValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa952aa5bfb51a38178c0d47e0fc7aa7b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addLiteralImmOperand</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a2bc19898d48a85699db2ea0cdb8ec55f">anonymous{AArch64PreLegalizerCombiner.cpp}::applyFConstantToConstant</a>, <a href="#a9c5a2112c559ffbe2c7bbf5698b6482f">bitcastToAPInt</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#a477d9c111d2e0ae837de4f4efaf47058">llvm::detail::DoubleAPFloat::convertFromAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#ae4f54bf233710b1041d2a2218b3d9775">llvm::detail::DoubleAPFloat::convertFromSignExtendedInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#a5afdbe49400342f155b8076095f3e777">llvm::detail::DoubleAPFloat::convertFromString</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#a50b587c3ee7248d56ec0bb9aa8bc4dfd">llvm::detail::DoubleAPFloat::convertFromZeroExtendedInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#a2ee4399de3a7bdd9b93639642dee7a6c">convertIntToDoubleImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f470dbe853f135f9dc2cf67d6f2e8fe">llvm::convertToNonDenormSingle</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a830996c6ee01a4fc50c18055a48a02a8">anonymous{AArch64AsmParser.cpp}::AArch64Operand::CreateFPImm</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#aa4808fb08649caf3637752746bbc6bc2">llvm::detail::DoubleAPFloat::divide</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a42aed3ce098f4ba8b69e50e87e8146f6">emitGlobalConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa5f2de80c23c28bd1a3320e8369aab2">llvm::InstCombinerImpl::foldICmpAndConstConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a7134dae528abf2cf2ef1bd1d92f9ce39">foldLogOpOfMaskedICmps_NotAllZeros_BMask_Mixed</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#ae5a3c008b93df2ac020b72d934c4d4c2">llvm::detail::DoubleAPFloat::fusedMultiplyAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabf50e80c80c98fd130ff1cb70553742">llvm::generateSpecConstantInst</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-utils-cpp-/#a21c5d1a680afc10bd790c931150ac04f">anonymous{Utils.cpp}::getCImmOrFPImmAsAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#a58ab6474b8e70068a974fa56622abd14">llvm::detail::DoubleAPFloat::getExactInverse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c0a683d5c4984e6d58f5f3809ff6ec3">llvm::getExpressionForConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a8d99a67b80aa823579e6144312d2ab49">llvm::AArch64_AM::getFP16Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a175cfb35ded324792e79b99f0f26788b">llvm::ARM_AM::getFP16Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a802e2c223f77ddcaa043fdb8aea8f0db">llvm::ARM_AM::getFP32FP16Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#ae8c5e2948d1d2c86073df3e61ed55b6a">llvm::AArch64_AM::getFP32Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a7216473d5bb804df4df6141438c8c5ce">llvm::ARM_AM::getFP32Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a5ee61f3cdffeade9f24458631bc67052">llvm::AArch64_AM::getFP64Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a39c2a3666c56528f1a3dd717634f4bd4">llvm::ARM_AM::getFP64Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvloadfpimm/#a56787dd7342f7a3d1ba14262d29d1aab">llvm::RISCVLoadFPImm::getLoadFPImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#a2d298529e6e847055ce47f80d60576d1">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getMachineOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#af54e9ce01961e65d9b74fef2193a8d95">llvm::SPIRVGlobalRegistry::getOrCreateConstFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77ac85fa1d774b4d1f5a064e1b8ee8c3">llvm::HexagonLowerToMC</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#ab28800a685d06a879d56b4d178e85aa5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isInlinableImm</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a79ddea5769637d54074168769084f404">llvm::LegalizerHelper::lowerISFPCLASS</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ad593882fdec13fdc1832fa224050666e">llvm::CombinerHelper::matchCombineUnmergeConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#ab11bb851f15cc8f484d5ba9948e14411">llvm::detail::DoubleAPFloat::mod</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#a867d044bc3f3ac08e29e98aee30c3e58">llvm::detail::DoubleAPFloat::next</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a62ccca1cd262d040e8aee057ab0d22d5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a763e5d73a932a30d95c888b81f45a0c3">anonymous{AArch64AsmParser.cpp}::AArch64Operand::print</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxfloatmcexpr/#aaae727146c1ddb0a21babf63964848de">llvm::NVPTXFloatMCExpr::printImpl</a>, <a href="#a0215397085e3a37d4a6efd65ec877861">Profile</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#a2f8f5b97d182a63fa132a5169d82a1e9">llvm::detail::DoubleAPFloat::remainder</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#ae3b0430f59ff83e88ee055589e1c7387">llvm::detail::DoubleAPFloat::roundToIntegral</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a7d60a41c0d5e450f770042d3427928d0">llvm::RISCVDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinstructionselector-cpp-/riscvinstructionselector/#a285142054aed60907906550e49ed07e2">anonymous{RISCVInstructionSelector.cpp}::RISCVInstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a8414362458bfc0acef16b0440665faa1">llvm::RISCVDAGToDAGISel::selectScalarFPAsInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a>.</p>

</div>
</div>

### bitwiseIsEqual() {#a28cbb0780286695406353e6a295e12c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::bitwiseIsEqual (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#a643f8cd038a6fa41604fe8e3df11f977">getSemantics</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a4c44f70a31ae4f69f7676b9499ba117b">llvm::ConstantFPRange::getSingleElement</a>, <a href="#a43efe9700a64d52fdf51d350923eef33">isExactlyValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp/#a3c7836582438ab141883fb92f51a57c6">isInv2Pi</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#a3c7836582438ab141883fb92f51a57c6">isInv2Pi</a>.</p>

</div>
</div>

### changeSign() {#ae7fe7691e456e49addd866aa23896387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APFloat::changeSign ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#ae7fe7691e456e49addd866aa23896387">changeSign</a>.</p>


<p>Referenced by <a href="#ae7fe7691e456e49addd866aa23896387">changeSign</a>, <a href="#a69cb669b1adc09cca90312d39ea3021a">clearSign</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="#a1cfd2be1063599384fd6e6172264a979">copySign</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a274a99ee4eac8fbc5e112f80cd84c71e">llvm::PPCInstrInfo::finalizeInsInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c486f37283215012d84a486d6387ad2">llvm::SelectionDAG::getNeutralElement</a>, <a href="#a7f8802ce4f0a7839abb4c836cb52138a">getOne</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af2f8b153ed08786f54cf5e64aa404552">llvm::isNeutralConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a62ccca1cd262d040e8aee057ab0d22d5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a0ff7af77f414b9796ed948a2723f6199">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseFPImm</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae9e81fca4b22706c50ad62e3241b6286">llvm::X86TargetLowering::X86TargetLowering</a>.</p>

</div>
</div>

### classify() {#abc7c5f3ebb11d0aaf551f3b37ab16437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FPClassTest llvm::APFloat::classify ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a> which will return true for the value.</p>

<p>Declaration at line 1471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5455 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da3ab665df1666568d7eac3b1373106638">llvm::fcNegInf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dab003a118cd0b76a814ba4dfc7077034a">llvm::fcNegNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da023ad3d9b33a1af5eb90b8b543fb3ccb">llvm::fcNegSubnormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da1e8072411cd3959aa091c3cae8006dc0">llvm::fcNegZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dada0d259988860d7a2f882aa40b25fee1">llvm::fcPosInf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da052ace75708c251359ff22dd036417a6">llvm::fcPosNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dad0940edb5f5bf512669b72928b527d0c">llvm::fcPosSubnormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da7ace586671df3e62fa392d5144a8b3da">llvm::fcPosZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da05bb099c0a65e5b835ed8cd0b326df7c">llvm::fcQNan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da9d366dced7a639841b0ced40c82ccb28">llvm::fcSNan</a>, <a href="#a43c6c871e61d6071a20a680aa2a08009">isDenormal</a>, <a href="#afdbfe0ba27cece5e333f4a7ae68fa82e">isInfinity</a>, <a href="#a763d4ccd87f2c21d2079796c0c9cd51a">isNaN</a>, <a href="#a2b901c3a0625a7d7173e9bd4864e2775">isNegative</a>, <a href="#a43257671f610226d09cfb0ad8d5e7d6b">isNormal</a>, <a href="#a833f6b183e2adebde0fb463e6a6297fe">isSignaling</a> and <a href="#a9aaed17970b55e9e1bfa906822ea7b71">isZero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa56f37cb4a3ca6ae2017ac7c5e5b5d13">llvm::fcmpImpliesClass</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afbfe964338488078570fe14e7deb0551">llvm::InstCombinerImpl::foldICmpBitCast</a>.</p>

</div>
</div>

### clearSign() {#a69cb669b1adc09cca90312d39ea3021a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APFloat::clearSign ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#ae7fe7691e456e49addd866aa23896387">changeSign</a> and <a href="#a2b901c3a0625a7d7173e9bd4864e2775">isNegative</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abc7ab426f010b3402a1e9e6a9fef1327">LowerFCOPYSIGN</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a>.</p>

</div>
</div>

### compare() {#af739a28663314781780783f9741801a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cmpResult llvm::APFloat::compare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a643f8cd038a6fa41604fe8e3df11f977">getSemantics</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#aadf903de6f82a588de4eed4d082b5b8c">fmed3AMDGCN</a>, <a href="#a5ced4849b1d8bc242491248da1bf66c9">operator!=</a>, <a href="#a70eee025af91f471b6e367b988fcd734">operator&lt;</a>, <a href="#afde15e39fbdaa60019f320862b1495b0">operator&lt;=</a>, <a href="#abde24e929388be14e369195541847ac7">operator==</a>, <a href="#a8e343b52f5d5006c7ee1f558e4650951">operator&gt;</a> and <a href="#ab8d18be4722edccea943a9da193c1e7f">operator&gt;=</a>.</p>

</div>
</div>

### convert() {#a257e3cb529defa79ad7a9f42072f339a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::APFloat::convert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; ToSemantics, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM, bool * losesInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5468 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a643f8cd038a6fa41604fe8e3df11f977">getSemantics</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6aa8092c6b52c0412d8198a63bc995761e9">llvm::APFloatBase::opOK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a83b0af0afed8864c1437a6a032891333">llvm::semPPCDoubleDoubleLegacy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa952aa5bfb51a38178c0d47e0fc7aa7b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addLiteralImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a5c1af79d4ba400e89ab28d0586484fae">canLosslesslyConvertToFPType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ab787227a6a978f146fcb2b2ed651642e">canSafelyConvertTo16Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a12143601a4f0bcae30a2f017fbe6bbd7">llvm::checkConvertToNonDenormSingle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad797efb6c6fbbb2038d5ed8f8379561f">llvm::ConstantFoldCastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a>, <a href="#a37733c4c22afc6a48194783dbd25487c">convertToDouble</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a6f50fded9ec4a127a18b88ef2a61163e">llvm::APFixedPoint::convertToFloat</a>, <a href="#a8269fab998356ea27a76ad45bd6cc8fe">convertToFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a3b07116192b9d8ea90fb67b9bf755b">llvm::convertToNonDenormSingle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a0207059cc31ba2a73d1d7bc1ce62663f">emitDebugValueComment</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae97ea168cb4b3418065ffd29f4217956">llvm::SelectionDAG::foldConstantFPMath</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a5eb8f7a5d3cfdd127ad9db2e425e14eb">llvm::ConstantFP::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee5a9adb5b8a88c8913aed9c85e5a52">llvm::getAPFloatFromSize</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a58dab46907515eb8ebaa4a067bf5cf6a">anonymous{ConstantFolding.cpp}::GetConstantFoldFPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a354aae224911d4dab66e34bfa10cf5d6">llvm::SelectionDAG::getConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a67272093577b2c99e6138e38c647abe3">llvm::APFixedPoint::getFromFloatValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvloadfpimm/#a56787dd7342f7a3d1ba14262d29d1aab">llvm::RISCVLoadFPImm::getLoadFPImm</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#af490926429978952543839e7a62ffeb8">anonymous{ConstantFolding.cpp}::getValueAsDouble</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="#a43efe9700a64d52fdf51d350923eef33">isExactlyValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a69943c1bc81f3680f6f696b6565853e5">llvm::ConstantFP::isExactlyValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp/#a3cc2ef5101115495b8700d1e71834d9e">isFPExtFromF16OrConst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#ab28800a685d06a879d56b4d178e85aa5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isInlinableImm</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#adb514535d2905d3a9aeb570ab270c83f">llvm::ConstantFP::isValueValidForType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfpsdnode/#a032c3c529239728e58f7fccdbcdbc033">llvm::ConstantFPSDNode::isValueValidForType</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantscalar/#gab5d3d570a38c53cd67c5288df7d8fdd5">LLVMConstRealGetDouble</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab2731249115c18b6fbd58ad75ce431f9">LowerFROUND</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a452a31c9f24b147d72a14890d60d3894">llvm::ARMAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ae04610310004450abde7293643734104">matchFPExtFromF16</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a8cacbfce1f2eaebad939051128812350">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::matchFractPat</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxfloatmcexpr/#aaae727146c1ddb0a21babf63964848de">llvm::NVPTXFloatMCExpr::printImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a5d7cad0cfce679b9ebdf1fdf0eae6b1a">strictFPExtFromF16</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae9e81fca4b22706c50ad62e3241b6286">llvm::X86TargetLowering::X86TargetLowering</a>.</p>

</div>
</div>

### convertFromAPInt() {#a7a046fe3d1230e4804494ce18bae1175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">opStatus llvm::APFloat::convertFromAPInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Input, bool IsSigned, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#a7a046fe3d1230e4804494ce18bae1175">convertFromAPInt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad797efb6c6fbbb2038d5ed8f8379561f">llvm::ConstantFoldCastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1aef656147029ec93dabe8abf51806b6">llvm::ConstantFoldIntToFloat</a>, <a href="#a7a046fe3d1230e4804494ce18bae1175">convertFromAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#a477d9c111d2e0ae837de4f4efaf47058">llvm::detail::DoubleAPFloat::convertFromAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a3ee5abf8664d1ea66e6d93fd6cf61065">llvm::LegalizerHelper::lowerFPTOINT_SAT</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a64f47636eb4667460ea08f358d6d39da">llvm::LegalizerHelper::lowerFPTOUI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abec179193cc8369e33418e87154d7d04">lowerFTRUNC_FCEIL_FFLOOR_FROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abe950951aec4aa71b14f89b89d26eae0">lowerVectorFTRUNC_FCEIL_FFLOOR_FROUND</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#acc354c12306e08991c73849216e09f78">lowerVectorStrictFTRUNC_FCEIL_FFLOOR_FROUND</a>.</p>

</div>
</div>

### convertFromSignExtendedInteger() {#a6cc309055edb782bba7bcb11b415dd17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">opStatus llvm::APFloat::convertFromSignExtendedInteger (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a86aa96e22d365ebc7653372bed96a778">integerPart</a> * Input, unsigned int InputSize, bool IsSigned, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#a6cc309055edb782bba7bcb11b415dd17">convertFromSignExtendedInteger</a>.</p>


<p>Referenced by <a href="#a6cc309055edb782bba7bcb11b415dd17">convertFromSignExtendedInteger</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#ae4f54bf233710b1041d2a2218b3d9775">llvm::detail::DoubleAPFloat::convertFromSignExtendedInteger</a>.</p>

</div>
</div>

### convertFromString() {#ac83df2fb4fcefd0a95deb09db83a0635}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; APFloat::opStatus &gt; llvm::APFloat::convertFromString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5435 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#ac83df2fb4fcefd0a95deb09db83a0635">convertFromString</a>.</p>


<p>Referenced by <a href="#a271da21b4c6619b24fcdb30bc6c82ed1">APFloat</a>, <a href="#ac83df2fb4fcefd0a95deb09db83a0635">convertFromString</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#a5afdbe49400342f155b8076095f3e777">llvm::detail::DoubleAPFloat::convertFromString</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a21b5aaa8f0eba3c0ece98cdc86d90dec">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isExactFPImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a62ccca1cd262d040e8aee057ab0d22d5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseImm</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a0ff7af77f414b9796ed948a2723f6199">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseFPImm</a>.</p>

</div>
</div>

### convertFromZeroExtendedInteger() {#af8026384a9b6bfd57046298ab64b0ea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">opStatus llvm::APFloat::convertFromZeroExtendedInteger (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a86aa96e22d365ebc7653372bed96a778">integerPart</a> * Input, unsigned int InputSize, bool IsSigned, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#af8026384a9b6bfd57046298ab64b0ea1">convertFromZeroExtendedInteger</a>.</p>


<p>Referenced by <a href="#af8026384a9b6bfd57046298ab64b0ea1">convertFromZeroExtendedInteger</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#a50b587c3ee7248d56ec0bb9aa8bc4dfd">llvm::detail::DoubleAPFloat::convertFromZeroExtendedInteger</a>.</p>

</div>
</div>

### convertToDouble() {#a37733c4c22afc6a48194783dbd25487c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::APFloat::convertToDouble ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Converts this <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> to host double value.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> must be built using semantics, that can be represented by the host double type without loss of precision. It can be IEEEdouble and shorter semantics, like IEEEsingle and others.</p></dd>
</dl>


<p>Declaration at line 1361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5530 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a257e3cb529defa79ad7a9f42072f339a">convert</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a3d43c52f31748261cbdd0e2b0bbad94a">llvm::detail::IEEEFloat::convertToDouble</a>, <a href="#a643f8cd038a6fa41604fe8e3df11f977">getSemantics</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#abcbf7e10dae54479fd98a43302c14037">llvm::APFloatBase::isRepresentableBy</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6aaba98149aef517089f9868bde5b8c41bc">llvm::APFloatBase::opInexact</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a537c4619bcbfabf2035ffb5eca964f9b">llvm::semIEEEdouble</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a0207059cc31ba2a73d1d7bc1ce62663f">emitDebugValueComment</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#af490926429978952543839e7a62ffeb8">anonymous{ConstantFolding.cpp}::getValueAsDouble</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantscalar/#gab5d3d570a38c53cd67c5288df7d8fdd5">LLVMConstRealGetDouble</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a452a31c9f24b147d72a14890d60d3894">llvm::ARMAsmPrinter::lowerOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a>.</p>

</div>
</div>

### convertToFloat() {#a8269fab998356ea27a76ad45bd6cc8fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float llvm::APFloat::convertToFloat ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Converts this <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> to host float value.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> must be built using semantics, that can be represented by the host float type without loss of precision. It can be IEEEquad and shorter semantics, like IEEEdouble and others. Converts this <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> to host float value.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> must be built using semantics, that can be represented by the host float type without loss of precision. It can be IEEEsingle and shorter semantics, like IEEEhalf.</p></dd>
</dl>


<p>Declaration at line 1377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5558 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a257e3cb529defa79ad7a9f42072f339a">convert</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a3ee96d60e840c18bbd08398261142ad7">llvm::detail::IEEEFloat::convertToFloat</a>, <a href="#a643f8cd038a6fa41604fe8e3df11f977">getSemantics</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#abcbf7e10dae54479fd98a43302c14037">llvm::APFloatBase::isRepresentableBy</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#aee544c332088dbef348a0c1c97e21a6aaba98149aef517089f9868bde5b8c41bc">llvm::APFloatBase::opInexact</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7754dc9e65dfebb21bf7179fb690de9c">llvm::semIEEEsingle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#af50d863c0e5a39ec42b567a9ea58e351">llvm::FPMathOperator::getFPAccuracy</a> and <a href="/web-llvm/docs/api/classes/llvm/spirvmcinstlower/#a6d050903b1d4eb1403389e782f6cec1c">llvm::SPIRVMCInstLower::lower</a>.</p>

</div>
</div>

### convertToHexString() {#a80fcf8584733a9b06176373b10e49b17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::APFloat::convertToHexString (char * DST, unsigned int HexDigits, bool UpperCase, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#a80fcf8584733a9b06176373b10e49b17">convertToHexString</a>.</p>


<p>Referenced by <a href="#a80fcf8584733a9b06176373b10e49b17">convertToHexString</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#ae9bf262be438320cef2483bf01e7222c">llvm::detail::DoubleAPFloat::convertToHexString</a>.</p>

</div>
</div>

### convertToInteger() {#aae1f09de4bf1aab27149a7d328715e30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">opStatus llvm::APFloat::convertToInteger (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a86aa96e22d365ebc7653372bed96a778">integerPart</a> &gt; Input, unsigned int Width, bool IsSigned, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM, bool * IsExact)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#aae1f09de4bf1aab27149a7d328715e30">convertToInteger</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a69c84bdc36fee945e94d62b77e1558f1">checkCVTFixedPointOperandWithFBits</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a07d7324865c4b7d490acd0e24b361a97">anonymous{ConstantFolding.cpp}::ConstantFoldSSEConvertToInt</a>, <a href="#aebaffb4b288b2508f99e75e0e8bd3ed9">convertToInteger</a>, <a href="#aae1f09de4bf1aab27149a7d328715e30">convertToInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#a7d6416a03ebbfc3c8e49c43f65c5a84d">llvm::detail::DoubleAPFloat::convertToInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#af945460922a5750a0d075b6344608e27">ConvertToSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#aa5d7b750612b9a523ddd10c10c1faa4d">llvm::BuildVectorSDNode::getConstantFPSplatPow2ToLog2Int</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a174a77eb2d84ab20b1e3e58da247fd41">getExactInteger</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a30dc6de174502314903dfcbf8d176cea">PerformVMulVCTPCombine</a>.</p>

</div>
</div>

### convertToInteger() {#aebaffb4b288b2508f99e75e0e8bd3ed9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat::opStatus llvm::APFloat::convertToInteger (<a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> &amp; Result, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM, bool * IsExact)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5518 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#aae1f09de4bf1aab27149a7d328715e30">convertToInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a5fa938f247b20cccc87cc8a6e5d20aa6">llvm::APInt::getNumWords</a> and <a href="/web-llvm/docs/api/classes/llvm/apsint/#af482956db6e996054f48726dccc31686">llvm::APSInt::isSigned</a>.</p>

</div>
</div>

### copySign() {#a1cfd2be1063599384fd6e6172264a979}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APFloat::copySign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#ae7fe7691e456e49addd866aa23896387">changeSign</a>, <a href="#a2b901c3a0625a7d7173e9bd4864e2775">isNegative</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a2664741ca8fa0d154ef9e738aef0db7b">llvm::ConstantFoldFPBinOp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae97ea168cb4b3418065ffd29f4217956">llvm::SelectionDAG::foldConstantFPMath</a>.</p>

</div>
</div>

### divide() {#a107d394b970c9f03a486a15cdd08f0df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">opStatus llvm::APFloat::divide (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a643f8cd038a6fa41604fe8e3df11f977">getSemantics</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2664741ca8fa0d154ef9e738aef0db7b">llvm::ConstantFoldFPBinOp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#aa4808fb08649caf3637752746bbc6bc2">llvm::detail::DoubleAPFloat::divide</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae97ea168cb4b3418065ffd29f4217956">llvm::SelectionDAG::foldConstantFPMath</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a> and <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>.</p>

</div>
</div>

### dump() {#ad4e64a2bbbacfa304679cbdd5db87098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void llvm::APFloat::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5504 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#ad88e80162417db584dd417cc946c57b3">print</a>.</p>

</div>
</div>

### fusedMultiplyAdd() {#a9180d9a8c1fc9693c4b0a50937e904e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">opStatus llvm::APFloat::fusedMultiplyAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Multiplicand, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Addend, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a643f8cd038a6fa41604fe8e3df11f977">getSemantics</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a505a295564c761e2006b8e48647f6f7d">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall3</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#ae5a3c008b93df2ac020b72d934c4d4c2">llvm::detail::DoubleAPFloat::fusedMultiplyAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae53e791e2762b79bf164fb1802e3292b">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#add44d478a1c329e77659000039f6ae74">llvm::CombinerHelper::matchConstantFoldFMA</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#a314c190b5e7220bc1daa2c7fa271a63c">llvm::detail::DoubleAPFloat::multiply</a>.</p>

</div>
</div>

### getCategory() {#ac9818805994c902a893e9c4c86f50caf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">fltCategory llvm::APFloat::getCategory ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Referenced by <a href="#afdbfe0ba27cece5e333f4a7ae68fa82e">isInfinity</a>, <a href="#a763d4ccd87f2c21d2079796c0c9cd51a">isNaN</a> and <a href="#a9aaed17970b55e9e1bfa906822ea7b71">isZero</a>.</p>

</div>
</div>

### getExactInverse() {#a133fbd343970e5f7e689c3b94185a605}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::getExactInverse (<a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> * inv)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#a133fbd343970e5f7e689c3b94185a605">getExactInverse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a69c84bdc36fee945e94d62b77e1558f1">checkCVTFixedPointOperandWithFBits</a>, <a href="#a133fbd343970e5f7e689c3b94185a605">getExactInverse</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#a58ab6474b8e70068a974fa56622abd14">llvm::detail::DoubleAPFloat::getExactInverse</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a30dc6de174502314903dfcbf8d176cea">PerformVMulVCTPCombine</a>.</p>

</div>
</div>

### getExactLog2() {#a44d70cf308906fa36b66a9796dc0b6e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_READONLY int llvm::APFloat::getExactLog2 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#a44d70cf308906fa36b66a9796dc0b6e3">getExactLog2</a>.</p>


<p>Referenced by <a href="#a44d70cf308906fa36b66a9796dc0b6e3">getExactLog2</a>.</p>

</div>
</div>

### getExactLog2Abs() {#a268f8980dd0cba08690326624d4c7235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_READONLY int llvm::APFloat::getExactLog2Abs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#a268f8980dd0cba08690326624d4c7235">getExactLog2Abs</a>.</p>


<p>Referenced by <a href="#a268f8980dd0cba08690326624d4c7235">getExactLog2Abs</a>.</p>

</div>
</div>

### getSemantics() {#a643f8cd038a6fa41604fe8e3df11f977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloat::getSemantics ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Referenced by <a href="#a44602b2ea058f08b290a8fa0185909d1">add</a>, <a href="#a28cbb0780286695406353e6a295e12c8">bitwiseIsEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a81a7959d3e7f624343ecdf6905e251dd">llvm::MachineIRBuilder::buildFConstant</a>, <a href="#af739a28663314781780783f9741801a8">compare</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aeae4a07f0fe95525d21343b3139276bd">anonymous{ConstantFolding.cpp}::ConstantFoldAMDGCNCubeIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a6aa7059c451076ac90510ca8a30e5dad">constantFoldFpUnary</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#adc453b2dc648e45c35ae756cbe300cb8">llvm::ConstantFPRange::contains</a>, <a href="#a257e3cb529defa79ad7a9f42072f339a">convert</a>, <a href="#a37733c4c22afc6a48194783dbd25487c">convertToDouble</a>, <a href="#a8269fab998356ea27a76ad45bd6cc8fe">convertToFloat</a>, <a href="#a107d394b970c9f03a486a15cdd08f0df">divide</a>, <a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddend/#a2b3d6406d7e75f89f75afce4b23cc012">anonymous{InstCombineAddSub.cpp}::FAddend::drillValueDownOneStep</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp/#a2a2cd943c672fd604c2837f01a7db49f">flushDenormalConstant</a>, <a href="#a9180d9a8c1fc9693c4b0a50937e904e6">fusedMultiplyAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvloadfpimm/#a56787dd7342f7a3d1ba14262d29d1aab">llvm::RISCVLoadFPImm::getLoadFPImm</a>, <a href="#aec8b5b1495be8560aad61368e3a65264">hash_value</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="#a43efe9700a64d52fdf51d350923eef33">isExactlyValue</a>, <a href="#af3bec23b6e372e677f17151bfd6af8fc">isIEEE</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#adb514535d2905d3a9aeb570ab270c83f">llvm::ConstantFP::isValueValidForType</a>, <a href="#ac3126d0302ebe7754bf962fdaa25e286">mod</a>, <a href="#a82567bb6632fa71c7c727b9464368173">multiply</a>, <a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddendcoef/#a5ff268ddd74e086254b810bebd99174d">anonymous{InstCombineAddSub.cpp}::FAddendCoef::operator*=</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad9d34da62b4146ef6290977107ea7ead">llvm::AMDGPUTargetLowering::performRcpCombine</a>, <a href="#a95aaadfb3026e47b75223d2733df62f1">remainder</a>, <a href="#a27bc3a1b1f84258afe7e981fb707f646">subtract</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzvectorconstantinfo/#a62e5d01aa7e3692c19b8fedd0e6e2333">llvm::SystemZVectorConstantInfo::SystemZVectorConstantInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a>.</p>

</div>
</div>

### isDenormal() {#a43c6c871e61d6071a20a680aa2a08009}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isDenormal ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#a43c6c871e61d6071a20a680aa2a08009">isDenormal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a12143601a4f0bcae30a2f017fbe6bbd7">llvm::checkConvertToNonDenormSingle</a>, <a href="#abc7c5f3ebb11d0aaf551f3b37ab16437">classify</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a3b07116192b9d8ea90fb67b9bf755b">llvm::convertToNonDenormSingle</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp/#aacbd97f1443d5a400a39b1899b363812">flushDenormalConstantFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a69211e2fb3d1eed7ee14964bfc04e261">llvm::FlushFPConstant</a>, <a href="#a43c6c871e61d6071a20a680aa2a08009">isDenormal</a> and <a href="#a43257671f610226d09cfb0ad8d5e7d6b">isNormal</a>.</p>

</div>
</div>

### isExactlyValue() {#a43efe9700a64d52fdf51d350923eef33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isExactlyValue (double V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We don't rely on operator== working on double values, as it returns true for things that are clearly not equal, like -0.0 and 0.0.</p>


<p>As such, this method can be used to do an exact bit-for-bit comparison of two floating point values.</p>


<p>We leave the version with the double argument here because it's just so convenient to write "2.0" and the like. Without this function we'd have to duplicate its logic everywhere it's called.</p>


<p>Definition at line 1429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#a28cbb0780286695406353e6a295e12c8">bitwiseIsEqual</a>, <a href="#a257e3cb529defa79ad7a9f42072f339a">convert</a>, <a href="#a643f8cd038a6fa41604fe8e3df11f977">getSemantics</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adefe5a72d1e1691061658b46706bb306">llvm::SelectionDAG::simplifyFPBinop</a>.</p>

</div>
</div>

### isFinite() {#a72c0ccd36e5b427a58262f9481c9c61c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isFinite ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#afdbfe0ba27cece5e333f4a7ae68fa82e">isInfinity</a> and <a href="#a763d4ccd87f2c21d2079796c0c9cd51a">isNaN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a86456cb345c788177fa0b43a40519723">anonymous{ConstantFolding.cpp}::ConstantFoldScalarFrexpCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9bb4cbe0f2af3f9ba06c999baeb7736d">llvm::SelectionDAG::getNode</a>, <a href="#a152743f94b060fbc99d10736c1b430e5">isFiniteNonZero</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a4aa6c86468a25ae6ef47ec9b300990e0">matchFastFloatClamp</a>.</p>

</div>
</div>

### isFiniteNonZero() {#a152743f94b060fbc99d10736c1b430e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isFiniteNonZero ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#a72c0ccd36e5b427a58262f9481c9c61c">isFinite</a> and <a href="#a9aaed17970b55e9e1bfa906822ea7b71">isZero</a>.</p>


<p>Referenced by <a href="#a43257671f610226d09cfb0ad8d5e7d6b">isNormal</a>.</p>

</div>
</div>

### isIEEE() {#af3bec23b6e372e677f17151bfd6af8fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isIEEE ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="#a643f8cd038a6fa41604fe8e3df11f977">getSemantics</a>.</p>

</div>
</div>

### isInfinity() {#afdbfe0ba27cece5e333f4a7ae68fa82e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isInfinity ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#ada22bd638e0df004a3337fea421c4b44a6eb3128fd9350fb0e7095fd5109a2193">llvm::APFloatBase::fcInfinity</a> and <a href="#ac9818805994c902a893e9c4c86f50caf">getCategory</a>.</p>


<p>Referenced by <a href="#abc7c5f3ebb11d0aaf551f3b37ab16437">classify</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/constantproperties/#aea4b4c239b71e73a13e281c9b2b623e6">anonymous{HexagonConstPropagation.cpp}::ConstantProperties::deduce</a>, <a href="#a72c0ccd36e5b427a58262f9481c9c61c">isFinite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f579c2fbf1fda44d35d059d9799eddc">llvm::isMathLibCallNoop</a>, <a href="#ad1af637e15f22d5e9b99800a0fabe12c">isNegInfinity</a>, <a href="#a3b1180f8b5b3af0d2aa0876e590f8690">isPosInfinity</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a>.</p>

</div>
</div>

### isInteger() {#ace4517dbbab7dbdefa0d31e29db55969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isInteger ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#ace4517dbbab7dbdefa0d31e29db55969">isInteger</a>.</p>


<p>Referenced by <a href="#ace4517dbbab7dbdefa0d31e29db55969">isInteger</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp/#a035312f0450b07253231a7a9a7153b74">isKnownIntegral</a>.</p>

</div>
</div>

### isLargest() {#a9e937642977dd028fb0b5293f30ee47d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isLargest ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#a9e937642977dd028fb0b5293f30ee47d">isLargest</a>.</p>


<p>Referenced by <a href="#a9e937642977dd028fb0b5293f30ee47d">isLargest</a>.</p>

</div>
</div>

### isNaN() {#a763d4ccd87f2c21d2079796c0c9cd51a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isNaN ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#ada22bd638e0df004a3337fea421c4b44a44bde6e2840d9413a5a3334e66dd0e54">llvm::APFloatBase::fcNaN</a> and <a href="#ac9818805994c902a893e9c4c86f50caf">getCategory</a>.</p>


<p>Referenced by <a href="#abc7c5f3ebb11d0aaf551f3b37ab16437">classify</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aeae4a07f0fe95525d21343b3139276bd">anonymous{ConstantFolding.cpp}::ConstantFoldAMDGCNCubeIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#adc453b2dc648e45c35ae756cbe300cb8">llvm::ConstantFPRange::contains</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a438bfa60f8534d9b0e347dc50e46e079">anonymous{ConstantFolding.cpp}::evaluateCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="#a72c0ccd36e5b427a58262f9481c9c61c">isFinite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f579c2fbf1fda44d35d059d9799eddc">llvm::isMathLibCallNoop</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ac31ecf657d06f3e6f617cd4d6e035f1a">llvm::CombinerHelper::matchCombineFMinMaxNaN</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a>.</p>

</div>
</div>

### isNegative() {#a2b901c3a0625a7d7173e9bd4864e2775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isNegative ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Referenced by <a href="#abc7c5f3ebb11d0aaf551f3b37ab16437">classify</a>, <a href="#a69cb669b1adc09cca90312d39ea3021a">clearSign</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aeae4a07f0fe95525d21343b3139276bd">anonymous{ConstantFolding.cpp}::ConstantFoldAMDGCNCubeIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a>, <a href="#a1cfd2be1063599384fd6e6172264a979">copySign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa56f37cb4a3ca6ae2017ac7c5e5b5d13">llvm::fcmpImpliesClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp/#a2a2cd943c672fd604c2837f01a7db49f">flushDenormalConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvloadfpimm/#a56787dd7342f7a3d1ba14262d29d1aab">llvm::RISCVLoadFPImm::getLoadFPImm</a>, <a href="#ad1af637e15f22d5e9b99800a0fabe12c">isNegInfinity</a>, <a href="#ad57f69ac4fa1d889dc657d52e8a51ef1">isNegZero</a>, <a href="#a3b1180f8b5b3af0d2aa0876e590f8690">isPosInfinity</a>, <a href="#ac37cd93f2c41a818a278e99de784ba1d">isPosZero</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abf257c2c6dadfee6ee83fabb6ea77c4f">llvm::InstCombinerImpl::visitFMul</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a>.</p>

</div>
</div>

### isNegInfinity() {#ad1af637e15f22d5e9b99800a0fabe12c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isNegInfinity ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#afdbfe0ba27cece5e333f4a7ae68fa82e">isInfinity</a> and <a href="#a2b901c3a0625a7d7173e9bd4864e2775">isNegative</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>.</p>

</div>
</div>

### isNegZero() {#ad57f69ac4fa1d889dc657d52e8a51ef1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isNegZero ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#a2b901c3a0625a7d7173e9bd4864e2775">isNegative</a> and <a href="#a9aaed17970b55e9e1bfa906822ea7b71">isZero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a7d60a41c0d5e450f770042d3427928d0">llvm::RISCVDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a8414362458bfc0acef16b0440665faa1">llvm::RISCVDAGToDAGISel::selectScalarFPAsInt</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adefe5a72d1e1691061658b46706bb306">llvm::SelectionDAG::simplifyFPBinop</a>.</p>

</div>
</div>

### isNonZero() {#a67847bcacd8e684f0449be8f1ec90f29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isNonZero ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="#a9aaed17970b55e9e1bfa906822ea7b71">isZero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aeae4a07f0fe95525d21343b3139276bd">anonymous{ConstantFolding.cpp}::ConstantFoldAMDGCNCubeIntrinsic</a>.</p>

</div>
</div>

### isNormal() {#a43257671f610226d09cfb0ad8d5e7d6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isNormal ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#a43c6c871e61d6071a20a680aa2a08009">isDenormal</a> and <a href="#a152743f94b060fbc99d10736c1b430e5">isFiniteNonZero</a>.</p>


<p>Referenced by <a href="#abc7c5f3ebb11d0aaf551f3b37ab16437">classify</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>.</p>

</div>
</div>

### isPosInfinity() {#a3b1180f8b5b3af0d2aa0876e590f8690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isPosInfinity ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#afdbfe0ba27cece5e333f4a7ae68fa82e">isInfinity</a> and <a href="#a2b901c3a0625a7d7173e9bd4864e2775">isNegative</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>.</p>

</div>
</div>

### isPosZero() {#ac37cd93f2c41a818a278e99de784ba1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isPosZero ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="#a2b901c3a0625a7d7173e9bd4864e2775">isNegative</a> and <a href="#a9aaed17970b55e9e1bfa906822ea7b71">isZero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#af54e9ce01961e65d9b74fef2193a8d95">llvm::SPIRVGlobalRegistry::getOrCreateConstFP</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a7d60a41c0d5e450f770042d3427928d0">llvm::RISCVDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a8414362458bfc0acef16b0440665faa1">llvm::RISCVDAGToDAGISel::selectScalarFPAsInt</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adefe5a72d1e1691061658b46706bb306">llvm::SelectionDAG::simplifyFPBinop</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a0ff7af77f414b9796ed948a2723f6199">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseFPImm</a>.</p>

</div>
</div>

### isSignaling() {#a833f6b183e2adebde0fb463e6a6297fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isSignaling ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Referenced by <a href="#abc7c5f3ebb11d0aaf551f3b37ab16437">classify</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#adc453b2dc648e45c35ae756cbe300cb8">llvm::ConstantFPRange::contains</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a438bfa60f8534d9b0e347dc50e46e079">anonymous{ConstantFolding.cpp}::evaluateCompare</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a>.</p>

</div>
</div>

### isSmallest() {#aaa34fa2837fa3f7355fe90cbca1555e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isSmallest ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#aaa34fa2837fa3f7355fe90cbca1555e0">isSmallest</a>.</p>


<p>Referenced by <a href="#aaa34fa2837fa3f7355fe90cbca1555e0">isSmallest</a>.</p>

</div>
</div>

### isSmallestNormalized() {#af8943302f831d2fc16d84eaf1f2740ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isSmallestNormalized ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1466 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#af8943302f831d2fc16d84eaf1f2740ed">isSmallestNormalized</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa56f37cb4a3ca6ae2017ac7c5e5b5d13">llvm::fcmpImpliesClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvloadfpimm/#a56787dd7342f7a3d1ba14262d29d1aab">llvm::RISCVLoadFPImm::getLoadFPImm</a> and <a href="#af8943302f831d2fc16d84eaf1f2740ed">isSmallestNormalized</a>.</p>

</div>
</div>

### isZero() {#a9aaed17970b55e9e1bfa906822ea7b71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::isZero ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#ada22bd638e0df004a3337fea421c4b44a3a1240559e1e13a8f634da491cd89c43">llvm::APFloatBase::fcZero</a> and <a href="#ac9818805994c902a893e9c4c86f50caf">getCategory</a>.</p>


<p>Referenced by <a href="#abc7c5f3ebb11d0aaf551f3b37ab16437">classify</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#af8730ce5a51609308adda5bc1de4a859">anonymous{ConstantFolding.cpp}::ConstantFoldLibCall2</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a505a295564c761e2006b8e48647f6f7d">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a017debc0002d97577349af103f3bbe4d">expandNormalizeIntrinsic</a>, <a href="#a152743f94b060fbc99d10736c1b430e5">isFiniteNonZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f579c2fbf1fda44d35d059d9799eddc">llvm::isMathLibCallNoop</a>, <a href="#ad57f69ac4fa1d889dc657d52e8a51ef1">isNegZero</a>, <a href="#a67847bcacd8e684f0449be8f1ec90f29">isNonZero</a>, <a href="#ac37cd93f2c41a818a278e99de784ba1d">isPosZero</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a7d60a41c0d5e450f770042d3427928d0">llvm::RISCVDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adefe5a72d1e1691061658b46706bb306">llvm::SelectionDAG::simplifyFPBinop</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abf257c2c6dadfee6ee83fabb6ea77c4f">llvm::InstCombinerImpl::visitFMul</a>.</p>

</div>
</div>

### makeQuiet() {#a74b616ebc9fe99bb3d64e0f8181d8de7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::APFloat::makeQuiet ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assuming this is an IEEE-754 NaN value, quiet its signaling bit.</p>


<p>This preserves the sign and payload bits.</p>


<p>Definition at line 1319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>.</p>

</div>
</div>

### mod() {#ac3126d0302ebe7754bf962fdaa25e286}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">opStatus llvm::APFloat::mod (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a643f8cd038a6fa41604fe8e3df11f977">getSemantics</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2664741ca8fa0d154ef9e738aef0db7b">llvm::ConstantFoldFPBinOp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae97ea168cb4b3418065ffd29f4217956">llvm::SelectionDAG::foldConstantFPMath</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#ab11bb851f15cc8f484d5ba9948e14411">llvm::detail::DoubleAPFloat::mod</a>.</p>

</div>
</div>

### multiply() {#a82567bb6632fa71c7c727b9464368173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">opStatus llvm::APFloat::multiply (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a643f8cd038a6fa41604fe8e3df11f977">getSemantics</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2664741ca8fa0d154ef9e738aef0db7b">llvm::ConstantFoldFPBinOp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae97ea168cb4b3418065ffd29f4217956">llvm::SelectionDAG::foldConstantFPMath</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae53e791e2762b79bf164fb1802e3292b">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddendcoef/#a5ff268ddd74e086254b810bebd99174d">anonymous{InstCombineAddSub.cpp}::FAddendCoef::operator*=</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a>.</p>

</div>
</div>

### needsCleanup() {#aba402b558169083d42683af51ae36016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::needsCleanup ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1077 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#aba402b558169083d42683af51ae36016">needsCleanup</a>.</p>


<p>Referenced by <a href="#aba402b558169083d42683af51ae36016">needsCleanup</a>.</p>

</div>
</div>

### next() {#ab0fdc79bb75e8fe845f98e2199f9d451}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">opStatus llvm::APFloat::next (bool nextDown)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#ab0fdc79bb75e8fe845f98e2199f9d451">next</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab2731249115c18b6fbd58ad75ce431f9">LowerFROUND</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a8cacbfce1f2eaebad939051128812350">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::matchFractPat</a>, <a href="#ab0fdc79bb75e8fe845f98e2199f9d451">next</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#a867d044bc3f3ac08e29e98aee30c3e58">llvm::detail::DoubleAPFloat::next</a>.</p>

</div>
</div>

### print() {#ad88e80162417db584dd417cc946c57b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APFloat::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1482 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5497 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="#a416dc650964ad640df99464a32aa49da">toString</a>.</p>


<p>Referenced by <a href="#ad4e64a2bbbacfa304679cbdd5db87098">dump</a>.</p>

</div>
</div>

### Profile() {#a0215397085e3a37d4a6efd65ec877861}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APFloat::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; NID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to insert <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> objects, or objects that contain <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> objects, into FoldingSets.</p>

<p>Declaration at line 1182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5510 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid/#ae75832b6dfaefd06c8e1c2e7e4f4a3de">llvm::FoldingSetNodeID::Add</a> and <a href="#a9c5a2112c559ffbe2c7bbf5698b6482f">bitcastToAPInt</a>.</p>

</div>
</div>

### remainder() {#a95aaadfb3026e47b75223d2733df62f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">opStatus llvm::APFloat::remainder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a643f8cd038a6fa41604fe8e3df11f977">getSemantics</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#a2f8f5b97d182a63fa132a5169d82a1e9">llvm::detail::DoubleAPFloat::remainder</a>.</p>

</div>
</div>

### roundToIntegral() {#ae4eca54fe8b71670e3bd3a2b18469d73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">opStatus llvm::APFloat::roundToIntegral (<a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#ae4eca54fe8b71670e3bd3a2b18469d73">roundToIntegral</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a901cc1fd9cbb0ec57e3d7f53a70ecd09">llvm::InstCombinerImpl::foldFCmpIntToFPConst</a>, <a href="#ae4eca54fe8b71670e3bd3a2b18469d73">roundToIntegral</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#ae3b0430f59ff83e88ee055589e1c7387">llvm::detail::DoubleAPFloat::roundToIntegral</a>.</p>

</div>
</div>

### subtract() {#a27bc3a1b1f84258afe7e981fb707f646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">opStatus llvm::APFloat::subtract (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a> RM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a643f8cd038a6fa41604fe8e3df11f977">getSemantics</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2664741ca8fa0d154ef9e738aef0db7b">llvm::ConstantFoldFPBinOp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae97ea168cb4b3418065ffd29f4217956">llvm::SelectionDAG::foldConstantFPMath</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>.</p>

</div>
</div>

### toString() {#a416dc650964ad640df99464a32aa49da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APFloat::toString (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Str, unsigned FormatPrecision=0, unsigned FormatMaxPadding=3, bool TruncateZero=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h/#a91a6dbe6838c079cb3887485f4b1a965">APFLOAT_DISPATCH_ON_SEMANTICS</a> and <a href="#a416dc650964ad640df99464a32aa49da">toString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a42aed3ce098f4ba8b69e50e87e8146f6">emitGlobalConstantFP</a>, <a href="#ad88e80162417db584dd417cc946c57b3">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a1ae942149adacb516624bfb499d4d627">printConstant</a>, <a href="#a416dc650964ad640df99464a32aa49da">toString</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/doubleapfloat/#ab8a87407767d65bd07b00a21d614a74d">llvm::detail::DoubleAPFloat::toString</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### compareAbsoluteValue() {#a2e8f9674b7a3078ebb8ea18e2cb1d050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cmpResult llvm::APFloat::compareAbsoluteValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1049 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### getIEEE() {#a3a6d0b44cf07432415ae0a82d57f337f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IEEEFloat &amp; llvm::APFloat::getIEEE ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1009 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### getIEEE() {#ab0cc28ecab09e9e66a66b2e52f447f09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IEEEFloat &amp; llvm::APFloat::getIEEE ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1017 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### makeInf() {#a2b5ae7111a5157e39f87525ab7e3bea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APFloat::makeInf (bool Neg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1027 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### makeLargest() {#a5c9263666a922badddc8d25eab235b9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APFloat::makeLargest (bool Neg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1033 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### makeNaN() {#a2b55f121ce68f75060269c29f756e728}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APFloat::makeNaN (bool SNaN, bool Neg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> * fill)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1029 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### makeSmallest() {#a90010bf62ff62d8aad5de12ec1bb2252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APFloat::makeSmallest (bool Neg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1037 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### makeSmallestNormalized() {#a6017520ecdb4cfdcb8dff80040b7eeb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APFloat::makeSmallestNormalized (bool Neg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1041 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### makeZero() {#a53457f4042afc32d14e54842d3bd011a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::APFloat::makeZero (bool Neg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1025 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DoubleAPFloat {#a368919de899363c960656bee29bc6f69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::APFloat::DoubleAPFloat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1504 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### IEEEFloat {#ad2a27c01ab688eb9eb2e470de3676133}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::APFloat::IEEEFloat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### U {#a5434e967269f6c816bebddc643f52681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::APFloat::Storage llvm::APFloat::U</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 998 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### copySign() {#ada08ec10c9c11a30327565d8fc7f852e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::APFloat::copySign (<a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Sign)</td>
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

<p>A static helper to produce a copy of an <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> value with its sign copied from some other <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a>.</p>

<p>Definition at line 1312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### getAllOnesValue() {#a581d4a580ff88de698682f78a554b2fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::APFloat::getAllOnesValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Semantics)</td>
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

<p>Returns a float which is bitcasted from an all one value int.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#ae28d826c1042631ac188d8295949ff52"&gt;Semantics&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- type float semantics</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 5493 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a419747b6445cfb3e87ebb2905eb6ae3a">lowerShuffleAsBitMask</a>.</p>

</div>
</div>

### getInf() {#ab35b08ed1345493af2c69fbb71e4d0c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::APFloat::getInf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Sem, bool Negative=false)</td>
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

<p>Factory for Positive and Negative Infinity.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Negative</td>
<td class="doxyParamItemDescription"><p>True iff the number should be negative.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a486e96424b2741b19c72dca18e17567fa94fac5b2829fc1204d02e14326e2f479">llvm::APFloatBase::uninitialized</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#aa6e7cbf32894b4feb398e5ff39919ca1">canonicalizeRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa5f2de80c23c28bd1a3320e8369aab2">llvm::InstCombinerImpl::foldICmpAndConstConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a7134dae528abf2cf2ef1bd1d92f9ce39">foldLogOpOfMaskedICmps_NotAllZeros_BMask_Mixed</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a6f2864671b22c9f6135b6ae5d41bcf54">llvm::ConstantFP::getInfinity</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a8fd61f288d29d0a4114ca74f4befd17d">llvm::AMDGPUTargetLowering::getIsFinite</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a5cf82053f21c501b073d99bb18e73541">llvm::ConstantFPRange::getNaNOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c486f37283215012d84a486d6387ad2">llvm::SelectionDAG::getNeutralElement</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a340071757f3e0c6524e70a873212adee">llvm::ConstantFPRange::getNonNaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af2f8b153ed08786f54cf5e64aa404552">llvm::isNeutralConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5552c2fa1505412508e493149af31543">llvm::AMDGPULegalizerInfo::legalizeFExp</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2b530047260b0f52c4dd8823764acb2d">llvm::AMDGPULegalizerInfo::legalizeFFREXP</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a39adc1637ddc1df880ec4ab13529879e">llvm::AMDGPULegalizerInfo::legalizeFlogCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a8b4d189fb624411d2c3e6d460da3796f">llvm::AMDGPUTargetLowering::lowerFEXP</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a79ddea5769637d54074168769084f404">llvm::LegalizerHelper::lowerISFPCLASS</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a84ec432d02febd1b518e9453b1a0eba9">llvm::ConstantFPRange::makeAllowedFCmpRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a5172beb0382e24b2305c8bc0e46ee1f4">llvm::fuzzerop::makeConstantsWithType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#aac402a26d55b042a1350ed55c9fa2f36">makeGreaterThan</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#aa6196262129213645adfe2c1f4bfc562">makeLessThan</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#abdaa8ae9b3e01099946066f89a8e10ad">anonymous{AsmParser.cpp}::AsmParser::parseRealValue</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a1c3ac00eab4ed0328bc8c8942957c83b">anonymous{MasmParser.cpp}::MasmParser::parseRealValue</a>.</p>

</div>
</div>

### getLargest() {#aaa67fe0741c2b3712630ae636f8c2c20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::APFloat::getLargest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Sem, bool Negative=false)</td>
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

<p>Returns the largest finite number in the given semantics.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Negative</td>
<td class="doxyParamItemDescription"><p>- True iff the number should be negative</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a486e96424b2741b19c72dca18e17567fa94fac5b2829fc1204d02e14326e2f479">llvm::APFloatBase::uninitialized</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a901cc1fd9cbb0ec57e3d7f53a70ecd09">llvm::InstCombinerImpl::foldFCmpIntToFPConst</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a90400068a35c0781d02ecabdb296ddef">llvm::ConstantFPRange::getFinite</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c486f37283215012d84a486d6387ad2">llvm::SelectionDAG::getNeutralElement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a31bf36444fc26b97b06effa1d8536efb">llvm::getReductionIdentity</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af2f8b153ed08786f54cf5e64aa404552">llvm::isNeutralConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a68b29f4aff8a6db0040bc8e00a520116">llvm::AMDGPULegalizerInfo::legalizeRsqClampIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a79ddea5769637d54074168769084f404">llvm::LegalizerHelper::lowerISFPCLASS</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a84ec432d02febd1b518e9453b1a0eba9">llvm::ConstantFPRange::makeAllowedFCmpRegion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a5172beb0382e24b2305c8bc0e46ee1f4">llvm::fuzzerop::makeConstantsWithType</a>.</p>

</div>
</div>

### getNaN() {#aeecd5fa66870de83d235933a683b5952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::APFloat::getNaN (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Sem, bool Negative=false, uint64_t payload=0)</td>
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

<p>Factory for NaN values.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Negative</td>
<td class="doxyParamItemDescription"><p>- True iff the NaN generated should be negative.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">payload</td>
<td class="doxyParamItemDescription"><p>- The unspecified fill bits for creating the NaN, 0 by default. The value is truncated as necessary.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="#a010e22ea9432c4b7d5962406932ed27b">getQNaN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae97ea168cb4b3418065ffd29f4217956">llvm::SelectionDAG::foldConstantFPMath</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuatomicoptimizer-cpp/#a11bb0046d2dde7ed854e2515cbc6b191">getIdentityValueForAtomicOp</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#ab21342133676f10340dc3f541b128f24">llvm::ConstantFP::getNaN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a5172beb0382e24b2305c8bc0e46ee1f4">llvm::fuzzerop::makeConstantsWithType</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#abdaa8ae9b3e01099946066f89a8e10ad">anonymous{AsmParser.cpp}::AsmParser::parseRealValue</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a1c3ac00eab4ed0328bc8c8942957c83b">anonymous{MasmParser.cpp}::MasmParser::parseRealValue</a>.</p>

</div>
</div>

### getOne() {#a7f8802ce4f0a7839abb4c836cb52138a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::APFloat::getOne (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Sem, bool Negative=false)</td>
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

<p>Factory for Positive and Negative One.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Negative</td>
<td class="doxyParamItemDescription"><p>True iff the number should be negative.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1091 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="#ae7fe7691e456e49addd866aa23896387">changeSign</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a1d270f02c1f9186ea7961768be1269a7">getOneFP</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2f579c2fbf1fda44d35d059d9799eddc">llvm::isMathLibCallNoop</a>.</p>

</div>
</div>

### getQNaN() {#a010e22ea9432c4b7d5962406932ed27b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::APFloat::getQNaN (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Sem, bool Negative=false, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> * payload=nullptr)</td>
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

<p>Factory for QNaN values.</p>

<p>Definition at line 1123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a486e96424b2741b19c72dca18e17567fa94fac5b2829fc1204d02e14326e2f479">llvm::APFloatBase::uninitialized</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a>, <a href="#aeecd5fa66870de83d235933a683b5952">getNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c486f37283215012d84a486d6387ad2">llvm::SelectionDAG::getNeutralElement</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#ae1c0cea3240ade5ee715cdaadd6166ca">llvm::ConstantFP::getQNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af2f8b153ed08786f54cf5e64aa404552">llvm::isNeutralConstant</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblyinstprinter-cpp/#a63c3f91798717016cc0fbef3b4dc0b34">toString</a>.</p>

</div>
</div>

### getSmallest() {#abbed2fc7a4a18eea942e56d6b7583c1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::APFloat::getSmallest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Sem, bool Negative=false)</td>
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

<p>Returns the smallest (by magnitude) finite number in the given semantics.</p>


<p>Might be denormalized, which implies a relative loss of precision.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Negative</td>
<td class="doxyParamItemDescription"><p>- True iff the number should be negative</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a486e96424b2741b19c72dca18e17567fa94fac5b2829fc1204d02e14326e2f479">llvm::APFloatBase::uninitialized</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a5172beb0382e24b2305c8bc0e46ee1f4">llvm::fuzzerop::makeConstantsWithType</a>.</p>

</div>
</div>

### getSmallestNormalized() {#a9c568ab8748aba5d37006d52618bbcfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::APFloat::getSmallestNormalized (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Sem, bool Negative=false)</td>
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

<p>Returns the smallest (by magnitude) normalized finite number in the given semantics.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Negative</td>
<td class="doxyParamItemDescription"><p>- True iff the number should be negative</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a486e96424b2741b19c72dca18e17567fa94fac5b2829fc1204d02e14326e2f479">llvm::APFloatBase::uninitialized</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#ab8a7b154668a6d94ab02f1bac73e99e9">emitRsqIEEE1ULP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a33e5f96d603430d2b0ddffb1c06b8580">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::emitSqrtIEEE2ULP</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a8b9405405e3fd94cb6afc437af701f68">llvm::AMDGPUTargetLowering::getIsLtSmallestNormal</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a6cccbc4ab2203366175f55aba0035679">llvm::AMDGPULegalizerInfo::getScaledLogInput</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ac5177832b2a049a7c1dfe8181ba484fb">llvm::AMDGPUTargetLowering::getScaledLogInput</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a>.</p>

</div>
</div>

### getSNaN() {#a07d7341cdcfc7d01525ca04b10fce7a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::APFloat::getSNaN (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Sem, bool Negative=false, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> * payload=nullptr)</td>
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

<p>Factory for SNaN values.</p>

<p>Definition at line 1131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a486e96424b2741b19c72dca18e17567fa94fac5b2829fc1204d02e14326e2f479">llvm::APFloatBase::uninitialized</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a2d4899e7eb5175d079ff8523d226ded9">llvm::ConstantFP::getSNaN</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a>.</p>

</div>
</div>

### getZero() {#af591f8d18d0d9773192a0ffcca41796e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat llvm::APFloat::getZero (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Sem, bool Negative=false)</td>
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

<p>Factory for Positive and Negative Zero.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Negative</td>
<td class="doxyParamItemDescription"><p>True iff the number should be negative.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1082 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a486e96424b2741b19c72dca18e17567fa94fac5b2829fc1204d02e14326e2f479">llvm::APFloatBase::uninitialized</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a28ddcf99fafe235217356e423dcdd084">anonymous{ConstantFolding.cpp}::constantFoldCanonicalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#a0e9cfe70f7f772a846b632fd67a1b578">extendZeroIfEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a13254d395258a157ea8ce4a0e1a96050">fixFuncEntryCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp/#a2a2cd943c672fd604c2837f01a7db49f">flushDenormalConstant</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#acc6b975e547fa1ea148c5fb2aa0b93fd">anonymous{ConstantFolding.cpp}::FTZPreserveSign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuatomicoptimizer-cpp/#a11bb0046d2dde7ed854e2515cbc6b191">getIdentityValueForAtomicOp</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a75071440d60c24178371ca1299f4ef07">llvm::ConstantFP::getZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a3bdf014154b31cd5813672cbcd3af604">getZeroFP</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a5172beb0382e24b2305c8bc0e46ee1f4">llvm::fuzzerop::makeConstantsWithType</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a1c3ac00eab4ed0328bc8c8942957c83b">anonymous{MasmParser.cpp}::MasmParser::parseRealValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a1ae942149adacb516624bfb499d4d627">printConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/pdb/variant/#a49fdbd518da9e19748b74b4d4b91ce8d">llvm::pdb::Variant::toAPFloat</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae9e81fca4b22706c50ad62e3241b6286">llvm::X86TargetLowering::X86TargetLowering</a>.</p>

</div>
</div>

### hasSignificand() {#af0ef7731beb4deaba4d953f79e1731d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::hasSignificand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Sem)</td>
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

<p>Returns true if the given semantics has actual significand.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Sem</td>
<td class="doxyParamItemDescription"><p>- type float semantics</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a50923487cfa87ebdbff5d297e591a068">llvm::APFloatBase::Float8E8M0FNU</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a65ad336dde9a51ae13b2d854313a0693">llvm::detail::IEEEFloat::isLargest</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#abe7488323ce38642acc4938efe0bcc82">llvm::detail::IEEEFloat::next</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### usesLayout() {#aa0e0afb05651563e72d0efb97fd93b4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloat::usesLayout (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Semantics)</td>
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



<p>Definition at line 1000 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
