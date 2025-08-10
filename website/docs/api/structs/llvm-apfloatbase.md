---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/apfloatbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `APFloatBase` Struct

<p>A self-contained host- and target-independent arbitrary-precision floating-point software implementation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::APFloatBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">llvm/ADT/APFloat.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint/#a5221357e5b7511cb0c90c94044ba35cf">APInt::WordType</a> <a href="#a86aa96e22d365ebc7653372bed96a778">integerPart</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">int32_t <a href="#afe80c9bd1684d47025d691a7eabcb656">ExponentType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A signed type to represent a floating point numbers unbiased exponent. <a href="#afe80c9bd1684d47025d691a7eabcb656">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ea536c95c40fca11948b01252554b2a">roundingMode</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">llvm::RoundingMode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IEEE-754R 4.3: Rounding-direction attributes. <a href="#a1ea536c95c40fca11948b01252554b2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">cmpResult { <a href="#a1373bb8e8796d3b0b642b42cf55296ec">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IEEE-754R 5.11: Floating Point Comparison Relations. <a href="#a1373bb8e8796d3b0b642b42cf55296ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">opStatus { <a href="#aee544c332088dbef348a0c1c97e21a6a">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IEEE-754R 7: Default exception handling. <a href="#aee544c332088dbef348a0c1c97e21a6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">fltCategory { <a href="#ada22bd638e0df004a3337fea421c4b44">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Category of internally-represented number. <a href="#ada22bd638e0df004a3337fea421c4b44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">uninitializedTag { <a href="#a486e96424b2741b19c72dca18e17567f">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience enum used to construct an uninitialized <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a>. <a href="#a486e96424b2741b19c72dca18e17567f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">IlogbErrorKinds { <a href="#aa78db24ff4e5fbe0c3013bd4b9edb7fc">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumeration of <span class="doxyComputerOutput">ilogb</span> error results. <a href="#aa78db24ff4e5fbe0c3013bd4b9edb7fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6530cd829b7e8d4df2c29d950039961e">semanticsPrecision</a> (const fltSemantics &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#afe80c9bd1684d47025d691a7eabcb656">ExponentType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cf388064ffacaf16fafb77dd41942d9">semanticsMinExponent</a> (const fltSemantics &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#afe80c9bd1684d47025d691a7eabcb656">ExponentType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a1d760444efbbc033928adb6f41f1f3">semanticsMaxExponent</a> (const fltSemantics &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27161c9f62ab8ae2d6ddaf10b8ccb937">semanticsSizeInBits</a> (const fltSemantics &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afede4bd63799684de5d737cd51519768">semanticsIntSizeInBits</a> (const fltSemantics &amp;, bool)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87a8ed21539b142b455c4f1a5383bb98">semanticsHasZero</a> (const fltSemantics &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2afd3520f710c5f50d07c871a9b85964">semanticsHasSignedRepr</a> (const fltSemantics &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e5060fa91243ed21569206b08ec5baf">semanticsHasInf</a> (const fltSemantics &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d013abdde58b73c8192909295fbdf85">semanticsHasNaN</a> (const fltSemantics &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdc65020fc921934882691e772269f0b">isIEEELikeFP</a> (const fltSemantics &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87bff5ee1b945c644ee36d4e43c4a596">isRepresentableAsNormalIn</a> (const fltSemantics &amp;Src, const fltSemantics &amp;Dst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3536ced38fb9e6404151cfa03b4531dc">getSizeInBits</a> (const fltSemantics &amp;Sem)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the size of the floating point number (in bits) in the given semantics. <a href="#a3536ced38fb9e6404151cfa03b4531dc">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81cd273998d8aef3f44da0550bc3ab4b">integerPartWidth</a> = <a href="/web-llvm/docs/api/classes/llvm/apint/#aaf70a90533b469062634730e27f6577d">APInt::APINT_BITS_PER_WORD</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22ed74f1ed33c4d33f524a650ea536a6">rmNearestTiesToEven</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8777e7a3e4355e29cc0993a935225db3">rmTowardPositive</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7ca9f5fca8e6c87d7107d7203b4c2ccd1af">RoundingMode::TowardPositive</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ba0fce5daa7f716936cabcf00373f0e">rmTowardNegative</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7cacd6fee581a325642b84f1af5c0be5140">RoundingMode::TowardNegative</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a482d9cf95b588eb05cefeaa5c05be9a3">rmTowardZero</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7ca2113e9520b32addb451df3b9fec51a96">RoundingMode::TowardZero</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7c">roundingMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1289beadf5d399fa4a2c64e18903ac90">rmNearestTiesToAway</a> = ...</td>
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

## Floating Point Semantics. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Semantics { <a href="#ae28d826c1042631ac188d8295949ff52">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">llvm::fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a> (Semantics S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ae28d826c1042631ac188d8295949ff52">Semantics</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a> (const llvm::fltSemantics &amp;Sem)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86415bb448a78ef1fed893f9eb0f5d06">IEEEhalf</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab46ff1a80ee89c9e22ca17c179a89ab1">BFloat</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c5765e9acba977f6e462c2917276d8f">IEEEsingle</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ba7c3d54a5a714f7a27861ee114cce3">IEEEdouble</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a494661a175e7785032f9a05d963fc0e9">IEEEquad</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b2fd910a2e9a7bfeb48751fe74f82ff">PPCDoubleDouble</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15c3f4cebec85cf6235d979f9b14ec2f">PPCDoubleDoubleLegacy</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a769a83016fc4f31b00ab0c3e823386cb">Float8E5M2</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4b6de8d206b2fda9f4c7b4e23fe12bb">Float8E5M2FNUZ</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32226e35444b7f652a4509459840f5c2">Float8E4M3</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3935f43144fba97ee25855776b990622">Float8E4M3FN</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa450b6d406b108024671a1915f7019cf">Float8E4M3FNUZ</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5440673d0ef22ecfc78aa1d2f5fa8c4a">Float8E4M3B11FNUZ</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae548654e5e1a44f5f48a145f70efc63f">Float8E3M4</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba7428d2844bcef2f285358764c7a807">FloatTF32</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50923487cfa87ebdbff5d297e591a068">Float8E8M0FNU</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12295a6a0a905b037b436d8c90e6b0c9">Float6E3M2FN</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7296b1aca108f2303a26c024084efa7">Float6E2M3FN</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f07c4873ae20a55da7aeb56d9f70ceb">Float4E2M1FN</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4830aff0741b3cd7a3920826ae6c0ece">x87DoubleExtended</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a545c6b0586eb03d972908b478f671950">Bogus</a> () LLVM_READNONE</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A Pseudo fltsemantic used to construct APFloats that cannot conflict with anything real. <a href="#a545c6b0586eb03d972908b478f671950">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcbf7e10dae54479fd98a43302c14037">isRepresentableBy</a> (const fltSemantics &amp;A, const fltSemantics &amp;B)</td>
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

<p>A self-contained host- and target-independent arbitrary-precision floating-point software implementation.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> uses bignum integer arithmetic as provided by static functions in the <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> class. The library will work with bignum integers whose parts are any unsigned type at least 16 bits wide, but 64 bits is recommended.</p>


<p>Written for clarity rather than speed, in particular with a view to use in the front-end of a cross compiler so that target arithmetic can be correctly performed on the host. Performance should nonetheless be reasonable, particularly for its intended use. It may be useful as a base implementation for a run-time library during development of a faster target-specific one.</p>


<p>All 5 rounding modes in the IEEE-754R draft are handled correctly for all implemented operations. Currently implemented operations are add, subtract, multiply, divide, fused-multiply-add, conversion-to-float, conversion-to-integer and conversion-from-integer. New rounding modes (e.g. away from zero) can be added with three or four lines of code.</p>


<p>Four formats are built-in: IEEE single precision, double precision, quadruple precision, and x87 80-bit extended double (when operating with full extended precision). Adding a new format that obeys IEEE semantics only requires adding two lines of code: a declaration and definition of the format.</p>


<p>All operations return the status of that operation as an exception bit-mask, so multiple operations can be done consecutively with their results or-ed together. The returned status can be useful for compiler diagnostics; e.g., inexact, underflow and overflow can be easily diagnosed on constant folding, and compiler optimizers can determine what exceptions would be raised by folding operations and optimize, or perhaps not optimize, accordingly.</p>


<p>At present, underflow tininess is detected after rounding; it should be straight forward to add support for the before-rounding case too.</p>


<p>The library reads hexadecimal floating point numbers as per C99, and correctly rounds if necessary according to the specified rounding mode. Syntax is required to have been validated by the caller. It also converts floating point numbers to hexadecimal text as per the C99 a and A conversions. The output precision (or alternatively the natural minimal precision) can be specified; if the requested precision is less than the natural precision the output is correctly rounded for the specified rounding mode.</p>


<p>It also reads decimal floating point numbers and correctly rounds according to the specified rounding mode.</p>


<p>Conversion to decimal text is not currently implemented.</p>


<p>Non-zero finite numbers are represented internally as a sign bit, a 16-bit signed exponent, and the significand as an array of integer parts. After normalization of a number of precision P the exponent is within the range of the format, and if the number is not denormal the P-th bit of the significand is set as an explicit integer bit. For denormals the most significant bit is shifted right so that the exponent is maintained at the format's minimum, so that the smallest denormal has just the least significant bit of the significand set. The sign of zeroes and infinities is significant; the exponent and significand of such numbers is not stored, but has a known implicit (deterministic) value: 0 for the significands, 0 for zero exponent, all 1 bits for infinity exponent. For NaNs the sign and significand are deterministic, although not really meaningful, and preserved in non-conversion operations. The exponent is implicitly all 1 bits.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> does not provide any exception handling beyond default exception handling. We represent Signaling NaNs via IEEE-754R 2008 6.2.1 should clause by encoding Signaling NaNs with the first bit of its trailing significand as 0.</p>


## TODO {#autotoc_md0}


<p>Some features that may or may not be worth adding:</p>


<p>Binary to decimal conversion (hard).</p>


<p>Optional ability to detect underflow tininess before rounding.</p>


<p>New formats: x87 in single and double precision mode (IEEE apart from extended exponent range) (hard).</p>


<p>New operations: sqrt, IEEE remainder, C90 fmod, nexttoward.</p>


<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ExponentType {#afe80c9bd1684d47025d691a7eabcb656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef int32_t llvm::APFloatBase::ExponentType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A signed type to represent a floating point numbers unbiased exponent.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### integerPart {#a86aa96e22d365ebc7653372bed96a778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef APInt::WordType llvm::APFloatBase::integerPart</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### roundingMode {#a1ea536c95c40fca11948b01252554b2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::APFloatBase::roundingMode =  llvm::RoundingMode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IEEE-754R 4.3: Rounding-direction attributes.</p>

<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### cmpResult {#a1373bb8e8796d3b0b642b42cf55296ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::APFloatBase::cmpResult </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IEEE-754R 5.11: Floating Point Comparison Relations.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">cmpLessThan<a id="a1373bb8e8796d3b0b642b42cf55296eca6bd5099a8de38cdb7b0a65bf451c4fa7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">cmpEqual<a id="a1373bb8e8796d3b0b642b42cf55296eca95e6b9c1e27b4949da4c40f5afb842a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">cmpGreaterThan<a id="a1373bb8e8796d3b0b642b42cf55296eca9f45fb1a56fb0564ec5ede93dad96cc4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">cmpUnordered<a id="a1373bb8e8796d3b0b642b42cf55296eca0976a38a3a3c7de732d9538999dc45d1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### fltCategory {#ada22bd638e0df004a3337fea421c4b44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::APFloatBase::fltCategory </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Category of internally-represented number.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fcInfinity<a id="ada22bd638e0df004a3337fea421c4b44a6eb3128fd9350fb0e7095fd5109a2193"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fcNaN<a id="ada22bd638e0df004a3337fea421c4b44a44bde6e2840d9413a5a3334e66dd0e54"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fcNormal<a id="ada22bd638e0df004a3337fea421c4b44adcfdb684c8105f35e04c61d5b8d8495b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fcZero<a id="ada22bd638e0df004a3337fea421c4b44a3a1240559e1e13a8f634da491cd89c43"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### IlogbErrorKinds {#aa78db24ff4e5fbe0c3013bd4b9edb7fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::APFloatBase::IlogbErrorKinds </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enumeration of <span class="doxyComputerOutput">ilogb</span> error results.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IEK_Zero<a id="aa78db24ff4e5fbe0c3013bd4b9edb7fca92ab3f7aab17e3be64ddf42a7fa88cd0"></a></td>
<td class="doxyEnumItemDescription"> (= INT_MIN + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IEK_NaN<a id="aa78db24ff4e5fbe0c3013bd4b9edb7fca23abe3c9be234401b670eed6856bc850"></a></td>
<td class="doxyEnumItemDescription"> (= INT_MIN)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IEK_Inf<a id="aa78db24ff4e5fbe0c3013bd4b9edb7fca4c1772918997b32aa846df0cf32ca5f1"></a></td>
<td class="doxyEnumItemDescription"> (= INT_MAX)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### opStatus {#aee544c332088dbef348a0c1c97e21a6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::APFloatBase::opStatus </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IEEE-754R 7: Default exception handling.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">opOK<a id="aee544c332088dbef348a0c1c97e21a6aa8092c6b52c0412d8198a63bc995761e9"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">opInvalidOp<a id="aee544c332088dbef348a0c1c97e21a6aabb85c4ca7e984a8fc43c9276a64cff10"></a></td>
<td class="doxyEnumItemDescription"> (= 0x01)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">opDivByZero<a id="aee544c332088dbef348a0c1c97e21a6aae31d0d7b55b711771fea6f5fd635eb00"></a></td>
<td class="doxyEnumItemDescription"> (= 0x02)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">opOverflow<a id="aee544c332088dbef348a0c1c97e21a6aa054516d40647594fd6e9e436a9aa308f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x04)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">opUnderflow<a id="aee544c332088dbef348a0c1c97e21a6aa48b9b8471355c94315b5c94c294ffe5e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x08)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">opInexact<a id="aee544c332088dbef348a0c1c97e21a6aaba98149aef517089f9868bde5b8c41bc"></a></td>
<td class="doxyEnumItemDescription"> (= 0x10)</td>
</tr>

</table>
</dd>
</dl>


<p>opUnderflow or opOverflow are always returned or-ed with opInexact.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> models this behavior specified by IEEE-754: "For operations producing results in floating-point format, the default
   result of an operation that signals the invalid operation exception
   shall be a quiet NaN."</p>


<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### uninitializedTag {#a486e96424b2741b19c72dca18e17567f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::APFloatBase::uninitializedTag </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convenience enum used to construct an uninitialized <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a>.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">uninitialized<a id="a486e96424b2741b19c72dca18e17567fa94fac5b2829fc1204d02e14326e2f479"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getSizeInBits() {#a3536ced38fb9e6404151cfa03b4531dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APFloatBase::getSizeInBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Sem)</td>
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

<p>Returns the size of the floating point number (in bits) in the given semantics.</p>

<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#a8bca650e08800ab5625649c4f991b909">llvm::fltSemantics::sizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a81a7959d3e7f624343ecdf6905e251dd">llvm::MachineIRBuilder::buildFConstant</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### isIEEELikeFP() {#acdc65020fc921934882691e772269f0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloatBase::isIEEELikeFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; semantics)</td>
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



<p>Declaration at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#ae28d826c1042631ac188d8295949ff52a905c1ddc4453cfcbc4365f95ca89a188">S_IEEEquad</a> and <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>.</p>

</div>
</div>

### isRepresentableAsNormalIn() {#a87bff5ee1b945c644ee36d4e43c4a596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloatBase::isRepresentableAsNormalIn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; Dst)</td>
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



<p>Declaration at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>.</p>

</div>
</div>

### semanticsHasInf() {#a0e5060fa91243ed21569206b08ec5baf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloatBase::semanticsHasInf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; semantics)</td>
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



<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab0b9d2d0eaa773cc9476c1cd7a728b3eaac6a6b8a25c5c9332dcd09a9ebd672ac">llvm::IEEE754</a> and <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#a627fc7f98b788a5ed6da4856a414736b">llvm::fltSemantics::nonFiniteBehavior</a>.</p>

</div>
</div>

### semanticsHasNaN() {#a6d013abdde58b73c8192909295fbdf85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloatBase::semanticsHasNaN (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; semantics)</td>
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



<p>Declaration at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab0b9d2d0eaa773cc9476c1cd7a728b3eae574ed55b8fdf720e808271239fec3cc">llvm::FiniteOnly</a> and <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#a627fc7f98b788a5ed6da4856a414736b">llvm::fltSemantics::nonFiniteBehavior</a>.</p>

</div>
</div>

### semanticsHasSignedRepr() {#a2afd3520f710c5f50d07c871a9b85964}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloatBase::semanticsHasSignedRepr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; semantics)</td>
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



<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#a82ebbe1ed81fa4ae7185176f7c8c3463">llvm::fltSemantics::hasSignedRepr</a>.</p>

</div>
</div>

### semanticsHasZero() {#a87a8ed21539b142b455c4f1a5383bb98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloatBase::semanticsHasZero (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; semantics)</td>
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



<p>Declaration at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#ab3820f5dd38e5f39bca385d6a39d1779">llvm::fltSemantics::hasZero</a>.</p>

</div>
</div>

### semanticsIntSizeInBits() {#afede4bd63799684de5d737cd51519768}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::APFloatBase::semanticsIntSizeInBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; semantics, bool isSigned)</td>
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



<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a> and <a href="#a5a1d760444efbbc033928adb6f41f1f3">semanticsMaxExponent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aefd6331c5fd6ec51f6a9e5558f885f28">canEvaluateTruncated</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#afbd068bf51a918cf4d30b127334f0656">isSaturatingMinMax</a>.</p>

</div>
</div>

### semanticsMaxExponent() {#a5a1d760444efbbc033928adb6f41f1f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloatBase::ExponentType llvm::APFloatBase::semanticsMaxExponent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; semantics)</td>
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



<p>Declaration at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#a259e56c00894bdd3606974a6e3a6464e">llvm::fltSemantics::maxExponent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a5a31319ba96ba0a68b6c30fed08f3dd2">llvm::FunctionComparator::cmpAPFloats</a> and <a href="#afede4bd63799684de5d737cd51519768">semanticsIntSizeInBits</a>.</p>

</div>
</div>

### semanticsMinExponent() {#a1cf388064ffacaf16fafb77dd41942d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloatBase::ExponentType llvm::APFloatBase::semanticsMinExponent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; semantics)</td>
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



<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#a775c20ec722ff6779370b64d2251d954">llvm::fltSemantics::minExponent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a5a31319ba96ba0a68b6c30fed08f3dd2">llvm::FunctionComparator::cmpAPFloats</a>.</p>

</div>
</div>

### semanticsPrecision() {#a6530cd829b7e8d4df2c29d950039961e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::APFloatBase::semanticsPrecision (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; semantics)</td>
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



<p>Declaration at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#aaec0dd351f93ebc840a6551422c2ad97">llvm::fltSemantics::precision</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2f6c6d734b9aae99aa476c3bf6c1cbf6">CastIntSETCCtoFP</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a5a31319ba96ba0a68b6c30fed08f3dd2">llvm::FunctionComparator::cmpAPFloats</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aff704e68e1a7f944f4a81ce9ef713ba4">computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a9940526e89938ffd29ad3135da3e2f7d">FoldIntToFPToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae07d5efbe94a4af292ffa12c5e9de0e5">getEstimate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abec179193cc8369e33418e87154d7d04">lowerFTRUNC_FCEIL_FFLOOR_FROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abe950951aec4aa71b14f89b89d26eae0">lowerVectorFTRUNC_FCEIL_FFLOOR_FROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#acc354c12306e08991c73849216e09f78">lowerVectorStrictFTRUNC_FCEIL_FFLOOR_FROUND</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a90425b7a8031ab778f7fbbdf07c1b948">llvm::detail::IEEEFloat::roundToIntegral</a>.</p>

</div>
</div>

### semanticsSizeInBits() {#a27161c9f62ab8ae2d6ddaf10b8ccb937}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::APFloatBase::semanticsSizeInBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; semantics)</td>
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



<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/fltsemantics/#a8bca650e08800ab5625649c4f991b909">llvm::fltSemantics::sizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a5a31319ba96ba0a68b6c30fed08f3dd2">llvm::FunctionComparator::cmpAPFloats</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### integerPartWidth {#a81cd273998d8aef3f44da0550bc3ab4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::APFloatBase::integerPartWidth = <a href="/web-llvm/docs/api/classes/llvm/apint/#aaf70a90533b469062634730e27f6577d">APInt::APINT_BITS_PER_WORD</a></td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acfc69dbf371d7d6d656538978ddb858a">llvm::lostFractionThroughTruncation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a006e3654b537d29fe0c6ec0da67eafa0">llvm::partAsHex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19ed009e0b27dab26887f6d10132a9cf">llvm::partCountForBits</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad222357287bec7df20542d5e06916737">llvm::ulpsFromBoundary</a>.</p>

</div>
</div>

### rmNearestTiesToAway {#a1289beadf5d399fa4a2c64e18903ac90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RoundingMode llvm::APFloatBase::rmNearestTiesToAway</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
                                                <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7cac88733f0acde4922deb25917d884f7bb">RoundingMode::NearestTiesToAway</a>
</div>
</dd>
</dl>

<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a> and <a href="/web-llvm/docs/api/classes/llvm/fixedpointsemantics/#ab30aaf95486d0b2aac87f3d9e1e450e3">llvm::FixedPointSemantics::fitsInFloatSemantics</a>.</p>

</div>
</div>

### rmNearestTiesToEven {#a22ed74f1ed33c4d33f524a650ea536a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RoundingMode llvm::APFloatBase::rmNearestTiesToEven</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
                                                <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7ca44467144e3b6bdac3e85ef6f90e7d832">RoundingMode::NearestTiesToEven</a>
</div>
</dd>
</dl>

<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa952aa5bfb51a38178c0d47e0fc7aa7b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addLiteralImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a271da21b4c6619b24fcdb30bc6c82ed1">llvm::APFloat::APFloat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a5c1af79d4ba400e89ab28d0586484fae">canLosslesslyConvertToFPType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a12143601a4f0bcae30a2f017fbe6bbd7">llvm::checkConvertToNonDenormSingle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad797efb6c6fbbb2038d5ed8f8379561f">llvm::ConstantFoldCastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2664741ca8fa0d154ef9e738aef0db7b">llvm::ConstantFoldFPBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a6aa7059c451076ac90510ca8a30e5dad">constantFoldFpUnary</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1aef656147029ec93dabe8abf51806b6">llvm::ConstantFoldIntToFloat</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a505a295564c761e2006b8e48647f6f7d">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall3</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a86456cb345c788177fa0b43a40519723">anonymous{ConstantFolding.cpp}::ConstantFoldScalarFrexpCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a07d7324865c4b7d490acd0e24b361a97">anonymous{ConstantFolding.cpp}::ConstantFoldSSEConvertToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a37733c4c22afc6a48194783dbd25487c">llvm::APFloat::convertToDouble</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a6f50fded9ec4a127a18b88ef2a61163e">llvm::APFixedPoint::convertToFloat</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a8269fab998356ea27a76ad45bd6cc8fe">llvm::APFloat::convertToFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a3b07116192b9d8ea90fb67b9bf755b">llvm::convertToNonDenormSingle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a0207059cc31ba2a73d1d7bc1ce62663f">emitDebugValueComment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a68d58b6cb8f56c90aa445f4857a8d430">fitsInFPType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a13254d395258a157ea8ce4a0e1a96050">fixFuncEntryCount</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae97ea168cb4b3418065ffd29f4217956">llvm::SelectionDAG::foldConstantFPMath</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a901cc1fd9cbb0ec57e3d7f53a70ecd09">llvm::InstCombinerImpl::foldFCmpIntToFPConst</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a5eb8f7a5d3cfdd127ad9db2e425e14eb">llvm::ConstantFP::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee5a9adb5b8a88c8913aed9c85e5a52">llvm::getAPFloatFromSize</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a23753c04a4ada14fc9c4891d30ed5cdc">llvm::StringRef::getAsDouble</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a58dab46907515eb8ebaa4a067bf5cf6a">anonymous{ConstantFolding.cpp}::GetConstantFoldFPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a354aae224911d4dab66e34bfa10cf5d6">llvm::SelectionDAG::getConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvvm/#a6aebf445d83116942f4b690d6d40a4f8">llvm::nvvm::GetFPToIntegerRoundingMode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvloadfpimm/#a56787dd7342f7a3d1ba14262d29d1aab">llvm::RISCVLoadFPImm::getLoadFPImm</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae53e791e2762b79bf164fb1802e3292b">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9bb4cbe0f2af3f9ba06c999baeb7736d">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#af490926429978952543839e7a62ffeb8">anonymous{ConstantFolding.cpp}::getValueAsDouble</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a835817b2c14c68ccbb8da31e459b4e96">llvm::detail::IEEEFloat::ilogb</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a43efe9700a64d52fdf51d350923eef33">llvm::APFloat::isExactlyValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a69943c1bc81f3680f6f696b6565853e5">llvm::ConstantFP::isExactlyValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp/#a3cc2ef5101115495b8700d1e71834d9e">isFPExtFromF16OrConst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#ab28800a685d06a879d56b4d178e85aa5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isInlinableImm</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#adb514535d2905d3a9aeb570ab270c83f">llvm::ConstantFP::isValueValidForType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfpsdnode/#a032c3c529239728e58f7fccdbcdbc033">llvm::ConstantFPSDNode::isValueValidForType</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantscalar/#gab5d3d570a38c53cd67c5288df7d8fdd5">LLVMConstRealGetDouble</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a64f47636eb4667460ea08f358d6d39da">llvm::LegalizerHelper::lowerFPTOUI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab2731249115c18b6fbd58ad75ce431f9">LowerFROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abec179193cc8369e33418e87154d7d04">lowerFTRUNC_FCEIL_FFLOOR_FROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abe950951aec4aa71b14f89b89d26eae0">lowerVectorFTRUNC_FCEIL_FFLOOR_FROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#acc354c12306e08991c73849216e09f78">lowerVectorStrictFTRUNC_FCEIL_FFLOOR_FROUND</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#add44d478a1c329e77659000039f6ae74">llvm::CombinerHelper::matchConstantFoldFMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ae04610310004450abde7293643734104">matchFPExtFromF16</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a8cacbfce1f2eaebad939051128812350">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::matchFractPat</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a662962ee7a570f3dcbb3b0826b9985e0">llvm::APFloat::operator*</a>, <a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddendcoef/#a5ff268ddd74e086254b810bebd99174d">anonymous{InstCombineAddSub.cpp}::FAddendCoef::operator*=</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a302f4ab2cb810c2763fc7aef728145cf">llvm::APFloat::operator+</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a656998434061ad466f2177bf41173775">llvm::APFloat::operator-</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a931608d42edab0dd403d65dec89e95e8">llvm::APFloat::operator/</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a62ccca1cd262d040e8aee057ab0d22d5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#abdaa8ae9b3e01099946066f89a8e10ad">anonymous{AsmParser.cpp}::AsmParser::parseRealValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a1c3ac00eab4ed0328bc8c8942957c83b">anonymous{MasmParser.cpp}::MasmParser::parseRealValue</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxfloatmcexpr/#aaae727146c1ddb0a21babf63964848de">llvm::NVPTXFloatMCExpr::printImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a5d7cad0cfce679b9ebdf1fdf0eae6b1a">strictFPExtFromF16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblyinstprinter-cpp/#a63c3f91798717016cc0fbef3b4dc0b34">toString</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a815e93bbea2fb7ef5a1c01f8d9de441f">valueHasFloatPrecision</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae9e81fca4b22706c50ad62e3241b6286">llvm::X86TargetLowering::X86TargetLowering</a>.</p>

</div>
</div>

### rmTowardNegative {#a1ba0fce5daa7f716936cabcf00373f0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RoundingMode llvm::APFloatBase::rmTowardNegative = <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7cacd6fee581a325642b84f1af5c0be5140">RoundingMode::TowardNegative</a></td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a> and <a href="/web-llvm/docs/api/namespaces/llvm/nvvm/#a6aebf445d83116942f4b690d6d40a4f8">llvm::nvvm::GetFPToIntegerRoundingMode</a>.</p>

</div>
</div>

### rmTowardPositive {#a8777e7a3e4355e29cc0993a935225db3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RoundingMode llvm::APFloatBase::rmTowardPositive = <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7ca9f5fca8e6c87d7107d7203b4c2ccd1af">RoundingMode::TowardPositive</a></td>
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



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a> and <a href="/web-llvm/docs/api/namespaces/llvm/nvvm/#a6aebf445d83116942f4b690d6d40a4f8">llvm::nvvm::GetFPToIntegerRoundingMode</a>.</p>

</div>
</div>

### rmTowardZero {#a482d9cf95b588eb05cefeaa5c05be9a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RoundingMode llvm::APFloatBase::rmTowardZero = <a href="/web-llvm/docs/api/namespaces/llvm/#ab7af0c09900daed62bbdb01dba180f7ca2113e9520b32addb451df3b9fec51a96">RoundingMode::TowardZero</a></td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ab787227a6a978f146fcb2b2ed651642e">canSafelyConvertTo16Bit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a69c84bdc36fee945e94d62b77e1558f1">checkCVTFixedPointOperandWithFBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad797efb6c6fbbb2038d5ed8f8379561f">llvm::ConstantFoldCastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a07d7324865c4b7d490acd0e24b361a97">anonymous{ConstantFolding.cpp}::ConstantFoldSSEConvertToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a6f50fded9ec4a127a18b88ef2a61163e">llvm::APFixedPoint::convertToFloat</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#af945460922a5750a0d075b6344608e27">ConvertToSInt</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a901cc1fd9cbb0ec57e3d7f53a70ecd09">llvm::InstCombinerImpl::foldFCmpIntToFPConst</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#aa5d7b750612b9a523ddd10c10c1faa4d">llvm::BuildVectorSDNode::getConstantFPSplatPow2ToLog2Int</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvvm/#a6aebf445d83116942f4b690d6d40a4f8">llvm::nvvm::GetFPToIntegerRoundingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a67272093577b2c99e6138e38c647abe3">llvm::APFixedPoint::getFromFloatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a21b5aaa8f0eba3c0ece98cdc86d90dec">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isExactFPImm</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a90186243528cfcd7b02837f130da5de2">llvm::PPCTargetLowering::isFPImmLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a3ee5abf8664d1ea66e6d93fd6cf61065">llvm::LegalizerHelper::lowerFPTOINT_SAT</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a452a31c9f24b147d72a14890d60d3894">llvm::ARMAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a30dc6de174502314903dfcbf8d176cea">PerformVMulVCTPCombine</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a0ff7af77f414b9796ed948a2723f6199">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseFPImm</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Floating Point Semantics.

### BFloat {#ab46ff1a80ee89c9e22ca17c179a89ab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::BFloat ()</td>
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



<p>Declaration at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ae0204614712901c08052fd64e0e6607c">llvm::semBFloat</a>.</p>


<p>Referenced by <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#afb55f797ff051b3fc29a0cf5f7465f12">llvm::ConstantDataSequential::getElementAsAPFloat</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a8eacadbf1dcf84e349dc5201f548eb96">llvm::MVT::getFltSemantics</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ae548c8a19a1775280fbea6ecd754363f">getOpFltSemantics</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#ab28800a685d06a879d56b4d178e85aa5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isInlinableImm</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#adb514535d2905d3a9aeb570ab270c83f">llvm::ConstantFP::isValueValidForType</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxfloatmcexpr/#aaae727146c1ddb0a21babf63964848de">llvm::NVPTXFloatMCExpr::printImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#aca508af3c3b25de78d97741420a9ff9e">llvm::APFixedPoint::promoteFloatSemantics</a>, <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a4b773c63bff7bbf9565edd03d7864966">shrinkFPConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae9e81fca4b22706c50ad62e3241b6286">llvm::X86TargetLowering::X86TargetLowering</a>.</p>

</div>
</div>

### Bogus {#a545c6b0586eb03d972908b478f671950}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::Bogus ()</td>
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

<p>A Pseudo fltsemantic used to construct APFloats that cannot conflict with anything real.</p>

<p>Declaration at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a081a32b758ca3c58f2a937b3d04ca218">llvm::semBogus</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-5607773d27be4d35012e29621f60e5ba/#ac3348a6df2d13b92529faba4d7344d70">llvm::DenseMapInfo&lt; APFloat &gt;::getEmptyKey</a> and <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-5607773d27be4d35012e29621f60e5ba/#a7679f40cf42384b86ad3cd2656c89adc">llvm::DenseMapInfo&lt; APFloat &gt;::getTombstoneKey</a>.</p>

</div>
</div>

### EnumToSemantics {#a08b077e94d6e9f21a63113d369da9b22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const llvm::fltSemantics &amp; llvm::APFloatBase::EnumToSemantics (<a href="#ae28d826c1042631ac188d8295949ff52">Semantics</a> S)</td>
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



<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#ab46ff1a80ee89c9e22ca17c179a89ab1">BFloat</a>, <a href="#a4f07c4873ae20a55da7aeb56d9f70ceb">Float4E2M1FN</a>, <a href="#ad7296b1aca108f2303a26c024084efa7">Float6E2M3FN</a>, <a href="#a12295a6a0a905b037b436d8c90e6b0c9">Float6E3M2FN</a>, <a href="#ae548654e5e1a44f5f48a145f70efc63f">Float8E3M4</a>, <a href="#a32226e35444b7f652a4509459840f5c2">Float8E4M3</a>, <a href="#a5440673d0ef22ecfc78aa1d2f5fa8c4a">Float8E4M3B11FNUZ</a>, <a href="#a3935f43144fba97ee25855776b990622">Float8E4M3FN</a>, <a href="#aa450b6d406b108024671a1915f7019cf">Float8E4M3FNUZ</a>, <a href="#a769a83016fc4f31b00ab0c3e823386cb">Float8E5M2</a>, <a href="#ac4b6de8d206b2fda9f4c7b4e23fe12bb">Float8E5M2FNUZ</a>, <a href="#a50923487cfa87ebdbff5d297e591a068">Float8E8M0FNU</a>, <a href="#aba7428d2844bcef2f285358764c7a807">FloatTF32</a>, <a href="#a6ba7c3d54a5a714f7a27861ee114cce3">IEEEdouble</a>, <a href="#a86415bb448a78ef1fed893f9eb0f5d06">IEEEhalf</a>, <a href="#a494661a175e7785032f9a05d963fc0e9">IEEEquad</a>, <a href="#a0c5765e9acba977f6e462c2917276d8f">IEEEsingle</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a3b2fd910a2e9a7bfeb48751fe74f82ff">PPCDoubleDouble</a>, <a href="#a15c3f4cebec85cf6235d979f9b14ec2f">PPCDoubleDoubleLegacy</a>, <a href="#ae28d826c1042631ac188d8295949ff52a4ac2c7646ad25f6198c3cbbc627c5b54">S_BFloat</a>, <a href="#ae28d826c1042631ac188d8295949ff52a8dd16c9eabbd4b03bad890b2bba3868c">S_Float4E2M1FN</a>, <a href="#ae28d826c1042631ac188d8295949ff52a17d727cd884fae7f7f3f1b3e029ac575">S_Float6E2M3FN</a>, <a href="#ae28d826c1042631ac188d8295949ff52a99773cadb5a3e21af5ad411ff0d56bcf">S_Float6E3M2FN</a>, <a href="#ae28d826c1042631ac188d8295949ff52acc6b5146d622a16b408c9fffbde9b934">S_Float8E3M4</a>, <a href="#ae28d826c1042631ac188d8295949ff52a6b22aebe60dd7c23142230f419cf4587">S_Float8E4M3</a>, <a href="#ae28d826c1042631ac188d8295949ff52ac66c5550fab7a97aa213b82f4ead8882">S_Float8E4M3B11FNUZ</a>, <a href="#ae28d826c1042631ac188d8295949ff52aa5355a964dc9ce6a38b183340262cc4b">S_Float8E4M3FN</a>, <a href="#ae28d826c1042631ac188d8295949ff52a3397bd1915e0cb2c7cb7b5e09c1d556c">S_Float8E4M3FNUZ</a>, <a href="#ae28d826c1042631ac188d8295949ff52a5360fa26ec11b4638e0ac1b1b4dbb30b">S_Float8E5M2</a>, <a href="#ae28d826c1042631ac188d8295949ff52ac6275c0290c28bf6d94af2651f0af108">S_Float8E5M2FNUZ</a>, <a href="#ae28d826c1042631ac188d8295949ff52af9c857c44bca65044d0582c1aa608f01">S_Float8E8M0FNU</a>, <a href="#ae28d826c1042631ac188d8295949ff52ab04e922575a47a53d1a406925985d5f2">S_FloatTF32</a>, <a href="#ae28d826c1042631ac188d8295949ff52addf4aea26776fa9ef6fbecdd9d4bd42f">S_IEEEdouble</a>, <a href="#ae28d826c1042631ac188d8295949ff52a34e6dc98e540680ba8a019c81ea26459">S_IEEEhalf</a>, <a href="#ae28d826c1042631ac188d8295949ff52a905c1ddc4453cfcbc4365f95ca89a188">S_IEEEquad</a>, <a href="#ae28d826c1042631ac188d8295949ff52a256aae058a9193e7a33e5c1e74487863">S_IEEEsingle</a>, <a href="#ae28d826c1042631ac188d8295949ff52a601f9d15fb988710f86c2481f0982cff">S_PPCDoubleDouble</a>, <a href="#ae28d826c1042631ac188d8295949ff52ae1a763752ce9783b8ed283af10e5dccb">S_PPCDoubleDoubleLegacy</a>, <a href="#ae28d826c1042631ac188d8295949ff52ac2304127435c8b9489c15b90cc9b1239">S_x87DoubleExtended</a> and <a href="#a4830aff0741b3cd7a3920826ae6c0ece">x87DoubleExtended</a>.</p>

</div>
</div>

### Float4E2M1FN {#a4f07c4873ae20a55da7aeb56d9f70ceb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::Float4E2M1FN ()</td>
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



<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a78e3dcad9f6b12186ad03ad5393c02ab">llvm::semFloat4E2M1FN</a>.</p>


<p>Referenced by <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a> and <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>.</p>

</div>
</div>

### Float6E2M3FN {#ad7296b1aca108f2303a26c024084efa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::Float6E2M3FN ()</td>
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



<p>Declaration at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a20739cd51291ceb86fb7a94b4279017a">llvm::semFloat6E2M3FN</a>.</p>


<p>Referenced by <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a> and <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>.</p>

</div>
</div>

### Float6E3M2FN {#a12295a6a0a905b037b436d8c90e6b0c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::Float6E3M2FN ()</td>
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



<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a47846115528d616ad9673e2703cf9374">llvm::semFloat6E3M2FN</a>.</p>


<p>Referenced by <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a> and <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>.</p>

</div>
</div>

### Float8E3M4 {#ae548654e5e1a44f5f48a145f70efc63f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::Float8E3M4 ()</td>
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



<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#af0c6473763345fc4fad9690798754a24">llvm::semFloat8E3M4</a>.</p>


<p>Referenced by <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a> and <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>.</p>

</div>
</div>

### Float8E4M3 {#a32226e35444b7f652a4509459840f5c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::Float8E4M3 ()</td>
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



<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#af8b943441d508a929d62ab9444d35dd6">llvm::semFloat8E4M3</a>.</p>


<p>Referenced by <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a> and <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>.</p>

</div>
</div>

### Float8E4M3B11FNUZ {#a5440673d0ef22ecfc78aa1d2f5fa8c4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::Float8E4M3B11FNUZ ()</td>
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



<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aaa215f65f2c225222d546711a5bad178">llvm::semFloat8E4M3B11FNUZ</a>.</p>


<p>Referenced by <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a> and <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>.</p>

</div>
</div>

### Float8E4M3FN {#a3935f43144fba97ee25855776b990622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::Float8E4M3FN ()</td>
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



<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a583afa2665e59069dfb9fc42c408723c">llvm::semFloat8E4M3FN</a>.</p>


<p>Referenced by <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a> and <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>.</p>

</div>
</div>

### Float8E4M3FNUZ {#aa450b6d406b108024671a1915f7019cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::Float8E4M3FNUZ ()</td>
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



<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a4ced5d9cf31beb3eb87c3ca575b1f8f9">llvm::semFloat8E4M3FNUZ</a>.</p>


<p>Referenced by <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a> and <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>.</p>

</div>
</div>

### Float8E5M2 {#a769a83016fc4f31b00ab0c3e823386cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::Float8E5M2 ()</td>
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



<p>Declaration at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9d0f43624747b09541310d90b6674144">llvm::semFloat8E5M2</a>.</p>


<p>Referenced by <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a> and <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>.</p>

</div>
</div>

### Float8E5M2FNUZ {#ac4b6de8d206b2fda9f4c7b4e23fe12bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::Float8E5M2FNUZ ()</td>
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



<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7440eebc93a0c37645a7c1ee67e4df1d">llvm::semFloat8E5M2FNUZ</a>.</p>


<p>Referenced by <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a> and <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>.</p>

</div>
</div>

### Float8E8M0FNU {#a50923487cfa87ebdbff5d297e591a068}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::Float8E8M0FNU ()</td>
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



<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1bceb2114f6460962c9e988f8dcf9246">llvm::semFloat8E8M0FNU</a>.</p>


<p>Referenced by <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af0ef7731beb4deaba4d953f79e1731d1">llvm::APFloat::hasSignificand</a> and <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>.</p>

</div>
</div>

### FloatTF32 {#aba7428d2844bcef2f285358764c7a807}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::FloatTF32 ()</td>
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



<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac072554936469e5afe54c3c48c529c76">llvm::semFloatTF32</a>.</p>


<p>Referenced by <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a> and <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>.</p>

</div>
</div>

### IEEEdouble {#a6ba7c3d54a5a714f7a27861ee114cce3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::IEEEdouble ()</td>
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



<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a537c4619bcbfabf2035ffb5eca964f9b">llvm::semIEEEdouble</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a72b37da283ebf9ecc9ef3b8468b9569d">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addFPImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa952aa5bfb51a38178c0d47e0fc7aa7b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addLiteralImmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a4d01e127e68e5892e266e055d0e67094">llvm::APFloat::APFloat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bca5f0c0254fc2b2707fe8b6e5677d3">combineBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a6aa7059c451076ac90510ca8a30e5dad">constantFoldFpUnary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#a2ee4399de3a7bdd9b93639642dee7a6c">convertIntToDoubleImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a0207059cc31ba2a73d1d7bc1ce62663f">emitDebugValueComment</a>, <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a13254d395258a157ea8ce4a0e1a96050">fixFuncEntryCount</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1abbecb57e09bf906ab1503722015802">getConstantVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abee99e97f96cb26e6b8208e4d6c98fec">getConstantVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afe7ad42a427fd0055f7f57f33b915252">getConstVector</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#afb55f797ff051b3fc29a0cf5f7465f12">llvm::ConstantDataSequential::getElementAsAPFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25ebf05ccdc20f3355715fb29ee82427">llvm::getFltSemanticForLLT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a27ccaa09df579488f23c8b968c4325c2">getFltSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a8eacadbf1dcf84e349dc5201f548eb96">llvm::MVT::getFltSemantics</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#abe43ce294e9f0705c6f51289b1057d16">anonymous{AArch64AsmParser.cpp}::AArch64Operand::getFPImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvloadfpimm/#a56787dd7342f7a3d1ba14262d29d1aab">llvm::RISCVLoadFPImm::getLoadFPImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a1d270f02c1f9186ea7961768be1269a7">getOneFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ae548c8a19a1775280fbea6ecd754363f">getOpFltSemantics</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#af490926429978952543839e7a62ffeb8">anonymous{ConstantFolding.cpp}::getValueAsDouble</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a3bdf014154b31cd5813672cbcd3af604">getZeroFP</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a21b5aaa8f0eba3c0ece98cdc86d90dec">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isExactFPImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#ab28800a685d06a879d56b4d178e85aa5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isInlinableImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp/#a3c7836582438ab141883fb92f51a57c6">isInv2Pi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#a3c7836582438ab141883fb92f51a57c6">isInv2Pi</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a55cada066d6192320d0ca6c3033e9faf">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isLiteralImm</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a65b07c2d3b33166b642509347647acee">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isLoadFPImm</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#adb514535d2905d3a9aeb570ab270c83f">llvm::ConstantFP::isValueValidForType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ab2bd62dca48651e04d811aff7bfc2aa6">llvm::AMDGPULegalizerInfo::legalizeFroundeven</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a68b29f4aff8a6db0040bc8e00a520116">llvm::AMDGPULegalizerInfo::legalizeRsqClampIntrinsic</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantscalar/#gab5d3d570a38c53cd67c5288df7d8fdd5">LLVMConstRealGetDouble</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a64f47636eb4667460ea08f358d6d39da">llvm::LegalizerHelper::lowerFPTOUI</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#acb08518735dd5a6add8a754124198fd3">llvm::AMDGPUTargetLowering::LowerFROUNDEVEN</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a452a31c9f24b147d72a14890d60d3894">llvm::ARMAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1d727a45696ad380a24b7fd8445182d8">LowerUINT_TO_FP_i64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adbf830c60a50ca49ef14e5cb8750244e">lowerUINT_TO_FP_vXi32</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a62ccca1cd262d040e8aee057ab0d22d5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a034b546ea133319ab2244f9bfa28ecae">anonymous{AsmParser.cpp}::AsmParser::parseStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ac351340ed4428a1b6d69d303bcba86d9">llvm::SDNode::print_details</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxfloatmcexpr/#aaae727146c1ddb0a21babf63964848de">llvm::NVPTXFloatMCExpr::printImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#aa43bb54e111c5b87edb58a368175a352">llvm::WebAssemblyInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#aca508af3c3b25de78d97741420a9ff9e">llvm::APFixedPoint::promoteFloatSemantics</a>, <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a4b773c63bff7bbf9565edd03d7864966">shrinkFPConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a0ff7af77f414b9796ed948a2723f6199">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseFPImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a>.</p>

</div>
</div>

### IEEEhalf {#a86415bb448a78ef1fed893f9eb0f5d06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::IEEEhalf ()</td>
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



<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a81a3dea1d2b584030458c05f0dd109b7">llvm::semIEEEhalf</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ab787227a6a978f146fcb2b2ed651642e">canSafelyConvertTo16Bit</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargettransforminfo-cpp/#a2efdcd5db2fb392d8ef38eca4bc0f570">convertNvvmIntrinsicToLlvm</a>, <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee5a9adb5b8a88c8913aed9c85e5a52">llvm::getAPFloatFromSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1abbecb57e09bf906ab1503722015802">getConstantVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abee99e97f96cb26e6b8208e4d6c98fec">getConstantVector</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#afb55f797ff051b3fc29a0cf5f7465f12">llvm::ConstantDataSequential::getElementAsAPFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25ebf05ccdc20f3355715fb29ee82427">llvm::getFltSemanticForLLT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a27ccaa09df579488f23c8b968c4325c2">getFltSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a8eacadbf1dcf84e349dc5201f548eb96">llvm::MVT::getFltSemantics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvloadfpimm/#a56787dd7342f7a3d1ba14262d29d1aab">llvm::RISCVLoadFPImm::getLoadFPImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a1d270f02c1f9186ea7961768be1269a7">getOneFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ae548c8a19a1775280fbea6ecd754363f">getOpFltSemantics</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a3bdf014154b31cd5813672cbcd3af604">getZeroFP</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp/#a3cc2ef5101115495b8700d1e71834d9e">isFPExtFromF16OrConst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#ab28800a685d06a879d56b4d178e85aa5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isInlinableImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp/#a3c7836582438ab141883fb92f51a57c6">isInv2Pi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#a3c7836582438ab141883fb92f51a57c6">isInv2Pi</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#adb514535d2905d3a9aeb570ab270c83f">llvm::ConstantFP::isValueValidForType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ae04610310004450abde7293643734104">matchFPExtFromF16</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxfloatmcexpr/#aaae727146c1ddb0a21babf63964848de">llvm::NVPTXFloatMCExpr::printImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#aca508af3c3b25de78d97741420a9ff9e">llvm::APFixedPoint::promoteFloatSemantics</a>, <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a4b773c63bff7bbf9565edd03d7864966">shrinkFPConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a5d7cad0cfce679b9ebdf1fdf0eae6b1a">strictFPExtFromF16</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae9e81fca4b22706c50ad62e3241b6286">llvm::X86TargetLowering::X86TargetLowering</a>.</p>

</div>
</div>

### IEEEquad {#a494661a175e7785032f9a05d963fc0e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::IEEEquad ()</td>
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



<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a425a13121bd69ca1416cc3d1da205d07">llvm::semIEEEquad</a>.</p>


<p>Referenced by <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25ebf05ccdc20f3355715fb29ee82427">llvm::getFltSemanticForLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a8eacadbf1dcf84e349dc5201f548eb96">llvm::MVT::getFltSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#adb514535d2905d3a9aeb570ab270c83f">llvm::ConstantFP::isValueValidForType</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#aca508af3c3b25de78d97741420a9ff9e">llvm::APFixedPoint::promoteFloatSemantics</a>, <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzvectorconstantinfo/#a62e5d01aa7e3692c19b8fedd0e6e2333">llvm::SystemZVectorConstantInfo::SystemZVectorConstantInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae9e81fca4b22706c50ad62e3241b6286">llvm::X86TargetLowering::X86TargetLowering</a>.</p>

</div>
</div>

### IEEEsingle {#a0c5765e9acba977f6e462c2917276d8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::IEEEsingle ()</td>
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



<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7754dc9e65dfebb21bf7179fb690de9c">llvm::semIEEEsingle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfloat/#adf992210f35921e854458eb836175ba7">llvm::APFloat::APFloat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a12143601a4f0bcae30a2f017fbe6bbd7">llvm::checkConvertToNonDenormSingle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargettransforminfo-cpp/#a2efdcd5db2fb392d8ef38eca4bc0f570">convertNvvmIntrinsicToLlvm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a3b07116192b9d8ea90fb67b9bf755b">llvm::convertToNonDenormSingle</a>, <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1abbecb57e09bf906ab1503722015802">getConstantVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abee99e97f96cb26e6b8208e4d6c98fec">getConstantVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afe7ad42a427fd0055f7f57f33b915252">getConstVector</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#afb55f797ff051b3fc29a0cf5f7465f12">llvm::ConstantDataSequential::getElementAsAPFloat</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a6c1c7a303df4926ba82dfd4ac4ef1deb">getF32Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25ebf05ccdc20f3355715fb29ee82427">llvm::getFltSemanticForLLT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a27ccaa09df579488f23c8b968c4325c2">getFltSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a8eacadbf1dcf84e349dc5201f548eb96">llvm::MVT::getFltSemantics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvloadfpimm/#a56787dd7342f7a3d1ba14262d29d1aab">llvm::RISCVLoadFPImm::getLoadFPImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a1d270f02c1f9186ea7961768be1269a7">getOneFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ae548c8a19a1775280fbea6ecd754363f">getOpFltSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a6cccbc4ab2203366175f55aba0035679">llvm::AMDGPULegalizerInfo::getScaledLogInput</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ac5177832b2a049a7c1dfe8181ba484fb">llvm::AMDGPUTargetLowering::getScaledLogInput</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a3bdf014154b31cd5813672cbcd3af604">getZeroFP</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#adab9b2e1a33cfbe6f0fa6443046dcaf8">llvm::Attributor::identifyDefaultAbstractAttributes</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#ab28800a685d06a879d56b4d178e85aa5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isInlinableImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp/#a3c7836582438ab141883fb92f51a57c6">isInv2Pi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#a3c7836582438ab141883fb92f51a57c6">isInv2Pi</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#adb514535d2905d3a9aeb570ab270c83f">llvm::ConstantFP::isValueValidForType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5552c2fa1505412508e493149af31543">llvm::AMDGPULegalizerInfo::legalizeFExp</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a39adc1637ddc1df880ec4ab13529879e">llvm::AMDGPULegalizerInfo::legalizeFlogCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a68b29f4aff8a6db0040bc8e00a520116">llvm::AMDGPULegalizerInfo::legalizeRsqClampIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a8b4d189fb624411d2c3e6d460da3796f">llvm::AMDGPUTargetLowering::lowerFEXP</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a64f47636eb4667460ea08f358d6d39da">llvm::LegalizerHelper::lowerFPTOUI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adbf830c60a50ca49ef14e5cb8750244e">lowerUINT_TO_FP_vXi32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a58970668183d813014f564e59eafbef6">llvm::AMDGPUTargetLowering::needsDenormHandlingF32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a092571cd6865fc5f86e2a594265ff717">needsDenormHandlingF32</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a034b546ea133319ab2244f9bfa28ecae">anonymous{AsmParser.cpp}::AsmParser::parseStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ac351340ed4428a1b6d69d303bcba86d9">llvm::SDNode::print_details</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxfloatmcexpr/#aaae727146c1ddb0a21babf63964848de">llvm::NVPTXFloatMCExpr::printImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#aa43bb54e111c5b87edb58a368175a352">llvm::WebAssemblyInstPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#aca508af3c3b25de78d97741420a9ff9e">llvm::APFixedPoint::promoteFloatSemantics</a>, <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a4b773c63bff7bbf9565edd03d7864966">shrinkFPConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/pdb/variant/#a49fdbd518da9e19748b74b4d4b91ce8d">llvm::pdb::Variant::toAPFloat</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a4aa31e8cd18083599550e7203bc275fd">llvm::NVPTXTargetLowering::useF32FTZ</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a815e93bbea2fb7ef5a1c01f8d9de441f">valueHasFloatPrecision</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a>.</p>

</div>
</div>

### isRepresentableBy {#abcbf7e10dae54479fd98a43302c14037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::APFloatBase::isRepresentableBy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">fltSemantics</a> &amp; B)</td>
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



<p>Declaration at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a37733c4c22afc6a48194783dbd25487c">llvm::APFloat::convertToDouble</a> and <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a8269fab998356ea27a76ad45bd6cc8fe">llvm::APFloat::convertToFloat</a>.</p>

</div>
</div>

### PPCDoubleDouble {#a3b2fd910a2e9a7bfeb48751fe74f82ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::PPCDoubleDouble ()</td>
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



<p>Declaration at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a67db0271a5f67c58b07394c80a961ece">llvm::semPPCDoubleDouble</a>.</p>


<p>Referenced by <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a8eacadbf1dcf84e349dc5201f548eb96">llvm::MVT::getFltSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#adb514535d2905d3a9aeb570ab270c83f">llvm::ConstantFP::isValueValidForType</a>, <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a>.</p>

</div>
</div>

### PPCDoubleDoubleLegacy {#a15c3f4cebec85cf6235d979f9b14ec2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::PPCDoubleDoubleLegacy ()</td>
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



<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a83b0af0afed8864c1437a6a032891333">llvm::semPPCDoubleDoubleLegacy</a>.</p>


<p>Referenced by <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a> and <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>.</p>

</div>
</div>

### Semantics {#ae28d826c1042631ac188d8295949ff52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::APFloatBase::Semantics </td>
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
<td class="doxyEnumItemName">S_IEEEhalf<a id="ae28d826c1042631ac188d8295949ff52a34e6dc98e540680ba8a019c81ea26459"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_BFloat<a id="ae28d826c1042631ac188d8295949ff52a4ac2c7646ad25f6198c3cbbc627c5b54"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_IEEEsingle<a id="ae28d826c1042631ac188d8295949ff52a256aae058a9193e7a33e5c1e74487863"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_IEEEdouble<a id="ae28d826c1042631ac188d8295949ff52addf4aea26776fa9ef6fbecdd9d4bd42f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_IEEEquad<a id="ae28d826c1042631ac188d8295949ff52a905c1ddc4453cfcbc4365f95ca89a188"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_PPCDoubleDouble<a id="ae28d826c1042631ac188d8295949ff52a601f9d15fb988710f86c2481f0982cff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_PPCDoubleDoubleLegacy<a id="ae28d826c1042631ac188d8295949ff52ae1a763752ce9783b8ed283af10e5dccb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_Float8E5M2<a id="ae28d826c1042631ac188d8295949ff52a5360fa26ec11b4638e0ac1b1b4dbb30b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_Float8E5M2FNUZ<a id="ae28d826c1042631ac188d8295949ff52ac6275c0290c28bf6d94af2651f0af108"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_Float8E4M3<a id="ae28d826c1042631ac188d8295949ff52a6b22aebe60dd7c23142230f419cf4587"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_Float8E4M3FN<a id="ae28d826c1042631ac188d8295949ff52aa5355a964dc9ce6a38b183340262cc4b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_Float8E4M3FNUZ<a id="ae28d826c1042631ac188d8295949ff52a3397bd1915e0cb2c7cb7b5e09c1d556c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_Float8E4M3B11FNUZ<a id="ae28d826c1042631ac188d8295949ff52ac66c5550fab7a97aa213b82f4ead8882"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_Float8E3M4<a id="ae28d826c1042631ac188d8295949ff52acc6b5146d622a16b408c9fffbde9b934"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_FloatTF32<a id="ae28d826c1042631ac188d8295949ff52ab04e922575a47a53d1a406925985d5f2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_Float8E8M0FNU<a id="ae28d826c1042631ac188d8295949ff52af9c857c44bca65044d0582c1aa608f01"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_Float6E3M2FN<a id="ae28d826c1042631ac188d8295949ff52a99773cadb5a3e21af5ad411ff0d56bcf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_Float6E2M3FN<a id="ae28d826c1042631ac188d8295949ff52a17d727cd884fae7f7f3f1b3e029ac575"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_Float4E2M1FN<a id="ae28d826c1042631ac188d8295949ff52a8dd16c9eabbd4b03bad890b2bba3868c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_x87DoubleExtended<a id="ae28d826c1042631ac188d8295949ff52ac2304127435c8b9489c15b90cc9b1239"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S_MaxSemantics<a id="ae28d826c1042631ac188d8295949ff52a0a10ccbbf040ec937bbfc491920e2e7d"></a></td>
<td class="doxyEnumItemDescription"> (= S_x87DoubleExtended)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>.</p>

</div>
</div>

### SemanticsToEnum {#a78aae6e86ca05443b019735012c7d73a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloatBase::Semantics llvm::APFloatBase::SemanticsToEnum (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/fltsemantics">llvm::fltSemantics</a> &amp; Sem)</td>
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



<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>References <a href="#ab46ff1a80ee89c9e22ca17c179a89ab1">BFloat</a>, <a href="#a4f07c4873ae20a55da7aeb56d9f70ceb">Float4E2M1FN</a>, <a href="#ad7296b1aca108f2303a26c024084efa7">Float6E2M3FN</a>, <a href="#a12295a6a0a905b037b436d8c90e6b0c9">Float6E3M2FN</a>, <a href="#ae548654e5e1a44f5f48a145f70efc63f">Float8E3M4</a>, <a href="#a32226e35444b7f652a4509459840f5c2">Float8E4M3</a>, <a href="#a5440673d0ef22ecfc78aa1d2f5fa8c4a">Float8E4M3B11FNUZ</a>, <a href="#a3935f43144fba97ee25855776b990622">Float8E4M3FN</a>, <a href="#aa450b6d406b108024671a1915f7019cf">Float8E4M3FNUZ</a>, <a href="#a769a83016fc4f31b00ab0c3e823386cb">Float8E5M2</a>, <a href="#ac4b6de8d206b2fda9f4c7b4e23fe12bb">Float8E5M2FNUZ</a>, <a href="#a50923487cfa87ebdbff5d297e591a068">Float8E8M0FNU</a>, <a href="#aba7428d2844bcef2f285358764c7a807">FloatTF32</a>, <a href="#a6ba7c3d54a5a714f7a27861ee114cce3">IEEEdouble</a>, <a href="#a86415bb448a78ef1fed893f9eb0f5d06">IEEEhalf</a>, <a href="#a494661a175e7785032f9a05d963fc0e9">IEEEquad</a>, <a href="#a0c5765e9acba977f6e462c2917276d8f">IEEEsingle</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a3b2fd910a2e9a7bfeb48751fe74f82ff">PPCDoubleDouble</a>, <a href="#a15c3f4cebec85cf6235d979f9b14ec2f">PPCDoubleDoubleLegacy</a>, <a href="#ae28d826c1042631ac188d8295949ff52a4ac2c7646ad25f6198c3cbbc627c5b54">S_BFloat</a>, <a href="#ae28d826c1042631ac188d8295949ff52a8dd16c9eabbd4b03bad890b2bba3868c">S_Float4E2M1FN</a>, <a href="#ae28d826c1042631ac188d8295949ff52a17d727cd884fae7f7f3f1b3e029ac575">S_Float6E2M3FN</a>, <a href="#ae28d826c1042631ac188d8295949ff52a99773cadb5a3e21af5ad411ff0d56bcf">S_Float6E3M2FN</a>, <a href="#ae28d826c1042631ac188d8295949ff52acc6b5146d622a16b408c9fffbde9b934">S_Float8E3M4</a>, <a href="#ae28d826c1042631ac188d8295949ff52a6b22aebe60dd7c23142230f419cf4587">S_Float8E4M3</a>, <a href="#ae28d826c1042631ac188d8295949ff52ac66c5550fab7a97aa213b82f4ead8882">S_Float8E4M3B11FNUZ</a>, <a href="#ae28d826c1042631ac188d8295949ff52aa5355a964dc9ce6a38b183340262cc4b">S_Float8E4M3FN</a>, <a href="#ae28d826c1042631ac188d8295949ff52a3397bd1915e0cb2c7cb7b5e09c1d556c">S_Float8E4M3FNUZ</a>, <a href="#ae28d826c1042631ac188d8295949ff52a5360fa26ec11b4638e0ac1b1b4dbb30b">S_Float8E5M2</a>, <a href="#ae28d826c1042631ac188d8295949ff52ac6275c0290c28bf6d94af2651f0af108">S_Float8E5M2FNUZ</a>, <a href="#ae28d826c1042631ac188d8295949ff52af9c857c44bca65044d0582c1aa608f01">S_Float8E8M0FNU</a>, <a href="#ae28d826c1042631ac188d8295949ff52ab04e922575a47a53d1a406925985d5f2">S_FloatTF32</a>, <a href="#ae28d826c1042631ac188d8295949ff52addf4aea26776fa9ef6fbecdd9d4bd42f">S_IEEEdouble</a>, <a href="#ae28d826c1042631ac188d8295949ff52a34e6dc98e540680ba8a019c81ea26459">S_IEEEhalf</a>, <a href="#ae28d826c1042631ac188d8295949ff52a905c1ddc4453cfcbc4365f95ca89a188">S_IEEEquad</a>, <a href="#ae28d826c1042631ac188d8295949ff52a256aae058a9193e7a33e5c1e74487863">S_IEEEsingle</a>, <a href="#ae28d826c1042631ac188d8295949ff52a601f9d15fb988710f86c2481f0982cff">S_PPCDoubleDouble</a>, <a href="#ae28d826c1042631ac188d8295949ff52ae1a763752ce9783b8ed283af10e5dccb">S_PPCDoubleDoubleLegacy</a>, <a href="#ae28d826c1042631ac188d8295949ff52ac2304127435c8b9489c15b90cc9b1239">S_x87DoubleExtended</a> and <a href="#a4830aff0741b3cd7a3920826ae6c0ece">x87DoubleExtended</a>.</p>


<p>Referenced by <a href="#acdc65020fc921934882691e772269f0b">isIEEELikeFP</a> and <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a6c9e39c1fc1cf514ffd33b75339b815e">llvm::SIInstrInfo::isInlineConstant</a>.</p>

</div>
</div>

### x87DoubleExtended {#a4830aff0741b3cd7a3920826ae6c0ece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const fltSemantics &amp; llvm::APFloatBase::x87DoubleExtended ()</td>
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



<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a>, definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abc695eee95f8cbb17f7bdfb60134704e">llvm::semX87DoubleExtended</a>.</p>


<p>Referenced by <a href="#a08b077e94d6e9f21a63113d369da9b22">EnumToSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a8eacadbf1dcf84e349dc5201f548eb96">llvm::MVT::getFltSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#adb514535d2905d3a9aeb570ab270c83f">llvm::ConstantFP::isValueValidForType</a>, <a href="#a78aae6e86ca05443b019735012c7d73a">SemanticsToEnum</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp/#abbfb15ef66003a1f34d28fa4fb90ac93">toStringAPFloat</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae9e81fca4b22706c50ad62e3241b6286">llvm::X86TargetLowering::X86TargetLowering</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">APFloat.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/apfloat-cpp">APFloat.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
