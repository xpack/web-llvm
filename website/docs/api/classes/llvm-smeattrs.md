---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/smeattrs
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SMEAttrs` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/smeattrs">SMEAttrs</a> is a utility class to parse the SME ACLE attributes on functions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SMEAttrs { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">Target/AArch64/Utils/AArch64SMEAttributes.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">StateValue { <a href="#a786805d9eb176b61475f63d699d6344e">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Mask { <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cfa8c181aa3fd059200b7f7f936e9fe">SMEAttrs</a> (unsigned Mask=Normal)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf9a475c8b485c367d66e5ea678850eb">SMEAttrs</a> (const Function &amp;F)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5e262aac758714fcbe1b579d3d37920">SMEAttrs</a> (const CallBase &amp;CB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6d7c918ff7f20fdc03905b056edd11e">SMEAttrs</a> (const AttributeList &amp;L)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac62a2489e88e4e05e640c4bf6b29082f">SMEAttrs</a> (StringRef FuncName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74b3e482c88651fdb789252fdb19b107">set</a> (unsigned M, bool Enable=true)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f4d6e0f808a8b16227fac1099bcbf1d">hasStreamingBody</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0631da4d405aecafd9a30ab19f6a6488">hasStreamingInterface</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74197613bcbc100772a3359ab5788a14">hasStreamingInterfaceOrBody</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f213ec4d32444fe6f73dca3f3690e7d">hasStreamingCompatibleInterface</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e09d6791578ea1cbbf431a2bc9b50c9">hasNonStreamingInterface</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1702889e841fef1eafacab6fd2860082">hasNonStreamingInterfaceAndBody</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53b5f403cb0929bd20ac860f699cda2a">requiresSMChange</a> (const SMEAttrs &amp;Callee) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5c76ddab5601ff5ead828edc802e912">isNewZA</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a044953a906f7fadb980d48bf095e20">isInZA</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a699089d13481fdacd943a6cd11781739">isOutZA</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadc9b29185f58ba6752a3c7c5e254e14">isInOutZA</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0f92885ea519bd5864c82b85067e6a3">isPreservesZA</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa15a533e07f6ac4720eeff0eff804c35">sharesZA</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52ba4f9b8290209e88febec35b239e78">hasAgnosticZAInterface</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc5529d6f2fb091f8f2a066d3f244526">hasSharedZAInterface</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abee68000498a270e17c4979e748d96b7">hasPrivateZAInterface</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad66eee3f9196f0a756ab985fdaebd171">hasZAState</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4e4ec7b663af703242f9039b1692edd">requiresLazySave</a> (const SMEAttrs &amp;Callee) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69746b44d6e2baf8fde71e2ec31d1b36">isNewZT0</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53c16e2a7dc92cb1d8aa8549174fb02d">isInZT0</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ed8a49d1d4f5d58e8b3ebeefbdaecdb">isOutZT0</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a7c8d26150da168c48f20e3ab5991c2">isInOutZT0</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00f3d906fae5d5f0163bc69c7219d51a">isPreservesZT0</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7acc77cacd6e1f08bfe29e55f6374b23">isUndefZT0</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05704200885efea3fc85cff92725e91d">sharesZT0</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad68c22513c48158743ae0c58b8638aed">hasZT0State</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d818ea00be5db5237397edb1ddad5bd">requiresPreservingZT0</a> (const SMEAttrs &amp;Callee) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a3118e33d31e320d165ff3d5f0d0d63">requiresDisablingZABeforeCall</a> (const SMEAttrs &amp;Callee) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f3e643c8ad7c96e3ea6c0fb389898c0">requiresEnablingZAAfterCall</a> (const SMEAttrs &amp;Callee) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a852ea409f16839e8072e7fb7fa77791d">requiresPreservingAllZAState</a> (const SMEAttrs &amp;Callee) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa909d6765da3f99943f92d067449a9b2">Bitmask</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a786805d9eb176b61475f63d699d6344e">StateValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7920f986bb7bb24d992e3ca7ee970f6f">decodeZAState</a> (unsigned Bitmask)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12e5d29860fe2c7589e171f9226ac72a">encodeZAState</a> (StateValue S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a786805d9eb176b61475f63d699d6344e">StateValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c1be7584b445978af402d11e6cce2fd">decodeZT0State</a> (unsigned Bitmask)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff781ae50114ed4d856994602a9d5406">encodeZT0State</a> (StateValue S)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/smeattrs">SMEAttrs</a> is a utility class to parse the SME ACLE attributes on functions.</p>


<p>It helps determine a function's requirements for PSTATE.ZA and PSTATE.SM. It has interfaces to query whether a streaming mode change or lazy-save mechanism is required when going from one function to another (e.g. through a call).</p>


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Mask {#ac3ddd43ec0706cb4af5f9f5b910b2161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::SMEAttrs::Mask </td>
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
<td class="doxyEnumItemName">Normal<a id="ac3ddd43ec0706cb4af5f9f5b910b2161ad16802716b90c1277a57db873e286dbe"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SM_Enabled<a id="ac3ddd43ec0706cb4af5f9f5b910b2161adc47f081f050b4bbfa660018a2f55efc"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SM_Compatible<a id="ac3ddd43ec0706cb4af5f9f5b910b2161ab2289c6755601ab4fda5bad77ca4f330"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SM_Body<a id="ac3ddd43ec0706cb4af5f9f5b910b2161a78a2a47d2f2af8aca07759839ae0b018"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SME_ABI_Routine<a id="ac3ddd43ec0706cb4af5f9f5b910b2161a7e18bb628f3d4add46ae5f0e8bc06ea1"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZA_State_Agnostic<a id="ac3ddd43ec0706cb4af5f9f5b910b2161ab7990779115cc548dc085610e81f4f3b"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZT0_Undef<a id="ac3ddd43ec0706cb4af5f9f5b910b2161a4b700f4ff7fed0fe466634c23670c371"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZA_Shift<a id="ac3ddd43ec0706cb4af5f9f5b910b2161a36369aeedd545c2a472d3061db63bc56"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZA_Mask<a id="ac3ddd43ec0706cb4af5f9f5b910b2161a48c5df039934edae90cfa029ef8e81dd"></a></td>
<td class="doxyEnumItemDescription"> (= 0b111 &lt;&lt; ZA_Shift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZT0_Shift<a id="ac3ddd43ec0706cb4af5f9f5b910b2161ae555bd5c5c3db5fa9459aa0cc10fe1c6"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZT0_Mask<a id="ac3ddd43ec0706cb4af5f9f5b910b2161a595791f58d5b560bc6eae857bfdbbfff"></a></td>
<td class="doxyEnumItemDescription"> (= 0b111 &lt;&lt; ZT0_Shift)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>

</div>
</div>

### StateValue {#a786805d9eb176b61475f63d699d6344e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::SMEAttrs::StateValue </td>
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
<td class="doxyEnumItemName">None<a id="a786805d9eb176b61475f63d699d6344ea6adf97f83acf6453d4a6a4b1070f3754"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">In<a id="a786805d9eb176b61475f63d699d6344eaefeb369cccbd560588a756610865664c"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Out<a id="a786805d9eb176b61475f63d699d6344ea7c147cda9e49590f6abe83d118b7353b"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InOut<a id="a786805d9eb176b61475f63d699d6344ea47a54d9da8952a3980d27488b00a21c1"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Preserved<a id="a786805d9eb176b61475f63d699d6344ea5e837ef81141bf040b588faa5a333683"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">New<a id="a786805d9eb176b61475f63d699d6344ea03c2e7e41ffc181a4e84080b4710e81e"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SMEAttrs() {#a1cfa8c181aa3fd059200b7f7f936e9fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SMEAttrs::SMEAttrs (unsigned Mask=<a href="#ac3ddd43ec0706cb4af5f9f5b910b2161ad16802716b90c1277a57db873e286dbe">Normal</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161ad16802716b90c1277a57db873e286dbe">Normal</a> and <a href="#a74b3e482c88651fdb789252fdb19b107">set</a>.</p>


<p>Referenced by <a href="#a7a3118e33d31e320d165ff3d5f0d0d63">requiresDisablingZABeforeCall</a>, <a href="#a3f3e643c8ad7c96e3ea6c0fb389898c0">requiresEnablingZAAfterCall</a>, <a href="#ac4e4ec7b663af703242f9039b1692edd">requiresLazySave</a>, <a href="#a852ea409f16839e8072e7fb7fa77791d">requiresPreservingAllZAState</a>, <a href="#a4d818ea00be5db5237397edb1ddad5bd">requiresPreservingZT0</a>, <a href="#a53b5f403cb0929bd20ac860f699cda2a">requiresSMChange</a>, <a href="#aa5e262aac758714fcbe1b579d3d37920">SMEAttrs</a> and <a href="#aaf9a475c8b485c367d66e5ea678850eb">SMEAttrs</a>.</p>

</div>
</div>

### SMEAttrs() {#aaf9a475c8b485c367d66e5ea678850eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SMEAttrs::SMEAttrs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a1cfa8c181aa3fd059200b7f7f936e9fe">SMEAttrs</a>.</p>

</div>
</div>

### SMEAttrs() {#aa5e262aac758714fcbe1b579d3d37920}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMEAttrs::SMEAttrs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-cpp">AArch64SMEAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ae0c55761fce39dd71617690b04385193">llvm::CallBase::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="#a74b3e482c88651fdb789252fdb19b107">set</a> and <a href="#a1cfa8c181aa3fd059200b7f7f936e9fe">SMEAttrs</a>.</p>

</div>
</div>

### SMEAttrs() {#aa6d7c918ff7f20fdc03905b056edd11e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMEAttrs::SMEAttrs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> AttributeList &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-cpp">AArch64SMEAttributes.cpp</a>.</p>


<p>References <a href="#a12e5d29860fe2c7589e171f9226ac72a">encodeZAState</a>, <a href="#aff781ae50114ed4d856994602a9d5406">encodeZT0State</a>, <a href="#a786805d9eb176b61475f63d699d6344eaefeb369cccbd560588a756610865664c">In</a>, <a href="#a786805d9eb176b61475f63d699d6344ea47a54d9da8952a3980d27488b00a21c1">InOut</a>, <a href="#a786805d9eb176b61475f63d699d6344ea03c2e7e41ffc181a4e84080b4710e81e">New</a>, <a href="#a786805d9eb176b61475f63d699d6344ea7c147cda9e49590f6abe83d118b7353b">Out</a>, <a href="#a786805d9eb176b61475f63d699d6344ea5e837ef81141bf040b588faa5a333683">Preserved</a>, <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161a78a2a47d2f2af8aca07759839ae0b018">SM_Body</a>, <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161ab2289c6755601ab4fda5bad77ca4f330">SM_Compatible</a>, <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161adc47f081f050b4bbfa660018a2f55efc">SM_Enabled</a>, <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161ab7990779115cc548dc085610e81f4f3b">ZA_State_Agnostic</a> and <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161a4b700f4ff7fed0fe466634c23670c371">ZT0_Undef</a>.</p>

</div>
</div>

### SMEAttrs() {#ac62a2489e88e4e05e640c4bf6b29082f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMEAttrs::SMEAttrs (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-cpp">AArch64SMEAttributes.cpp</a>.</p>


<p>References <a href="#a12e5d29860fe2c7589e171f9226ac72a">encodeZAState</a>, <a href="#a786805d9eb176b61475f63d699d6344eaefeb369cccbd560588a756610865664c">In</a>, <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161ab2289c6755601ab4fda5bad77ca4f330">SM_Compatible</a> and <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161a7e18bb628f3d4add46ae5f0e8bc06ea1">SME_ABI_Routine</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### hasAgnosticZAInterface() {#a52ba4f9b8290209e88febec35b239e78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::hasAgnosticZAInterface ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>Reference <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161ab7990779115cc548dc085610e81f4f3b">ZA_State_Agnostic</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#ad6a46b5fa0c0be4df0f957b751654025">llvm::AArch64::createFastISel</a>, <a href="#abee68000498a270e17c4979e748d96b7">hasPrivateZAInterface</a>, <a href="#a852ea409f16839e8072e7fb7fa77791d">requiresPreservingAllZAState</a> and <a href="#a74b3e482c88651fdb789252fdb19b107">set</a>.</p>

</div>
</div>

### hasNonStreamingInterface() {#a7e09d6791578ea1cbbf431a2bc9b50c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::hasNonStreamingInterface ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#a3f213ec4d32444fe6f73dca3f3690e7d">hasStreamingCompatibleInterface</a> and <a href="#a0631da4d405aecafd9a30ab19f6a6488">hasStreamingInterface</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#added54819e6c37b1fb2697343812e6de">getSMCondition</a> and <a href="#a1702889e841fef1eafacab6fd2860082">hasNonStreamingInterfaceAndBody</a>.</p>

</div>
</div>

### hasNonStreamingInterfaceAndBody() {#a1702889e841fef1eafacab6fd2860082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::hasNonStreamingInterfaceAndBody ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#a7e09d6791578ea1cbbf431a2bc9b50c9">hasNonStreamingInterface</a> and <a href="#a9f4d6e0f808a8b16227fac1099bcbf1d">hasStreamingBody</a>.</p>


<p>Referenced by <a href="#a53b5f403cb0929bd20ac860f699cda2a">requiresSMChange</a>.</p>

</div>
</div>

### hasPrivateZAInterface() {#abee68000498a270e17c4979e748d96b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::hasPrivateZAInterface ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#a52ba4f9b8290209e88febec35b239e78">hasAgnosticZAInterface</a> and <a href="#afc5529d6f2fb091f8f2a066d3f244526">hasSharedZAInterface</a>.</p>

</div>
</div>

### hasSharedZAInterface() {#afc5529d6f2fb091f8f2a066d3f244526}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::hasSharedZAInterface ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#aa15a533e07f6ac4720eeff0eff804c35">sharesZA</a> and <a href="#a05704200885efea3fc85cff92725e91d">sharesZT0</a>.</p>


<p>Referenced by <a href="#abee68000498a270e17c4979e748d96b7">hasPrivateZAInterface</a> and <a href="#a74b3e482c88651fdb789252fdb19b107">set</a>.</p>

</div>
</div>

### hasStreamingBody() {#a9f4d6e0f808a8b16227fac1099bcbf1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::hasStreamingBody ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>Reference <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161a78a2a47d2f2af8aca07759839ae0b018">SM_Body</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a78b4edb7f5a3d943e1e3b5a6bf0328c6">llvm::AArch64TTIImpl::areInlineCompatible</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#aa1ef43d8b6e30020194591f4e5a914ac">emitVGSaveRestore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a3e52e7f7caf22b1bab8a06cbe8c387bf">enableMultiVectorSpillFill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#added54819e6c37b1fb2697343812e6de">getSMCondition</a>, <a href="#a1702889e841fef1eafacab6fd2860082">hasNonStreamingInterfaceAndBody</a> and <a href="#a74197613bcbc100772a3359ab5788a14">hasStreamingInterfaceOrBody</a>.</p>

</div>
</div>

### hasStreamingCompatibleInterface() {#a3f213ec4d32444fe6f73dca3f3690e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::hasStreamingCompatibleInterface ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>Reference <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161ab2289c6755601ab4fda5bad77ca4f330">SM_Compatible</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#ad6a46b5fa0c0be4df0f957b751654025">llvm::AArch64::createFastISel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#added54819e6c37b1fb2697343812e6de">getSMCondition</a>, <a href="#a7e09d6791578ea1cbbf431a2bc9b50c9">hasNonStreamingInterface</a> and <a href="#a74b3e482c88651fdb789252fdb19b107">set</a>.</p>

</div>
</div>

### hasStreamingInterface() {#a0631da4d405aecafd9a30ab19f6a6488}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::hasStreamingInterface ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>Reference <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161adc47f081f050b4bbfa660018a2f55efc">SM_Enabled</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#aa1ef43d8b6e30020194591f4e5a914ac">emitVGSaveRestore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a3e52e7f7caf22b1bab8a06cbe8c387bf">enableMultiVectorSpillFill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#added54819e6c37b1fb2697343812e6de">getSMCondition</a>, <a href="#a7e09d6791578ea1cbbf431a2bc9b50c9">hasNonStreamingInterface</a>, <a href="#a74197613bcbc100772a3359ab5788a14">hasStreamingInterfaceOrBody</a> and <a href="#a74b3e482c88651fdb789252fdb19b107">set</a>.</p>

</div>
</div>

### hasStreamingInterfaceOrBody() {#a74197613bcbc100772a3359ab5788a14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::hasStreamingInterfaceOrBody ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#a9f4d6e0f808a8b16227fac1099bcbf1d">hasStreamingBody</a> and <a href="#a0631da4d405aecafd9a30ab19f6a6488">hasStreamingInterface</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#ad6a46b5fa0c0be4df0f957b751654025">llvm::AArch64::createFastISel</a> and <a href="#a53b5f403cb0929bd20ac860f699cda2a">requiresSMChange</a>.</p>

</div>
</div>

### hasZAState() {#ad66eee3f9196f0a756ab985fdaebd171}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::hasZAState ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#ac5c76ddab5601ff5ead828edc802e912">isNewZA</a> and <a href="#aa15a533e07f6ac4720eeff0eff804c35">sharesZA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#ad6a46b5fa0c0be4df0f957b751654025">llvm::AArch64::createFastISel</a>, <a href="#a7a3118e33d31e320d165ff3d5f0d0d63">requiresDisablingZABeforeCall</a> and <a href="#ac4e4ec7b663af703242f9039b1692edd">requiresLazySave</a>.</p>

</div>
</div>

### hasZT0State() {#ad68c22513c48158743ae0c58b8638aed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::hasZT0State ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#a69746b44d6e2baf8fde71e2ec31d1b36">isNewZT0</a> and <a href="#a05704200885efea3fc85cff92725e91d">sharesZT0</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#ad6a46b5fa0c0be4df0f957b751654025">llvm::AArch64::createFastISel</a>, <a href="#a7a3118e33d31e320d165ff3d5f0d0d63">requiresDisablingZABeforeCall</a> and <a href="#a4d818ea00be5db5237397edb1ddad5bd">requiresPreservingZT0</a>.</p>

</div>
</div>

### isInOutZA() {#aadc9b29185f58ba6752a3c7c5e254e14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::isInOutZA ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#a7920f986bb7bb24d992e3ca7ee970f6f">decodeZAState</a> and <a href="#a786805d9eb176b61475f63d699d6344ea47a54d9da8952a3980d27488b00a21c1">InOut</a>.</p>


<p>Referenced by <a href="#a74b3e482c88651fdb789252fdb19b107">set</a>.</p>

</div>
</div>

### isInOutZT0() {#a6a7c8d26150da168c48f20e3ab5991c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::isInOutZT0 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#a9c1be7584b445978af402d11e6cce2fd">decodeZT0State</a> and <a href="#a786805d9eb176b61475f63d699d6344ea47a54d9da8952a3980d27488b00a21c1">InOut</a>.</p>


<p>Referenced by <a href="#a74b3e482c88651fdb789252fdb19b107">set</a>.</p>

</div>
</div>

### isInZA() {#a2a044953a906f7fadb980d48bf095e20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::isInZA ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#a7920f986bb7bb24d992e3ca7ee970f6f">decodeZAState</a> and <a href="#a786805d9eb176b61475f63d699d6344eaefeb369cccbd560588a756610865664c">In</a>.</p>


<p>Referenced by <a href="#a74b3e482c88651fdb789252fdb19b107">set</a>.</p>

</div>
</div>

### isInZT0() {#a53c16e2a7dc92cb1d8aa8549174fb02d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::isInZT0 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#a9c1be7584b445978af402d11e6cce2fd">decodeZT0State</a> and <a href="#a786805d9eb176b61475f63d699d6344eaefeb369cccbd560588a756610865664c">In</a>.</p>


<p>Referenced by <a href="#a74b3e482c88651fdb789252fdb19b107">set</a>.</p>

</div>
</div>

### isNewZA() {#ac5c76ddab5601ff5ead828edc802e912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::isNewZA ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#a7920f986bb7bb24d992e3ca7ee970f6f">decodeZAState</a> and <a href="#a786805d9eb176b61475f63d699d6344ea03c2e7e41ffc181a4e84080b4710e81e">New</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a78b4edb7f5a3d943e1e3b5a6bf0328c6">llvm::AArch64TTIImpl::areInlineCompatible</a>, <a href="#ad66eee3f9196f0a756ab985fdaebd171">hasZAState</a>, <a href="/web-llvm/docs/api/structs/anonymous-smeabipass-cpp-/smeabi/#aa765a5fc788410699fd070df2aa20319">anonymous{SMEABIPass.cpp}::SMEABI::runOnFunction</a> and <a href="#a74b3e482c88651fdb789252fdb19b107">set</a>.</p>

</div>
</div>

### isNewZT0() {#a69746b44d6e2baf8fde71e2ec31d1b36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::isNewZT0 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#a9c1be7584b445978af402d11e6cce2fd">decodeZT0State</a> and <a href="#a786805d9eb176b61475f63d699d6344ea03c2e7e41ffc181a4e84080b4710e81e">New</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a78b4edb7f5a3d943e1e3b5a6bf0328c6">llvm::AArch64TTIImpl::areInlineCompatible</a>, <a href="#ad68c22513c48158743ae0c58b8638aed">hasZT0State</a>, <a href="/web-llvm/docs/api/structs/anonymous-smeabipass-cpp-/smeabi/#aa765a5fc788410699fd070df2aa20319">anonymous{SMEABIPass.cpp}::SMEABI::runOnFunction</a> and <a href="#a74b3e482c88651fdb789252fdb19b107">set</a>.</p>

</div>
</div>

### isOutZA() {#a699089d13481fdacd943a6cd11781739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::isOutZA ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#a7920f986bb7bb24d992e3ca7ee970f6f">decodeZAState</a> and <a href="#a786805d9eb176b61475f63d699d6344ea7c147cda9e49590f6abe83d118b7353b">Out</a>.</p>


<p>Referenced by <a href="#a74b3e482c88651fdb789252fdb19b107">set</a>.</p>

</div>
</div>

### isOutZT0() {#a5ed8a49d1d4f5d58e8b3ebeefbdaecdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::isOutZT0 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#a9c1be7584b445978af402d11e6cce2fd">decodeZT0State</a> and <a href="#a786805d9eb176b61475f63d699d6344ea7c147cda9e49590f6abe83d118b7353b">Out</a>.</p>


<p>Referenced by <a href="#a74b3e482c88651fdb789252fdb19b107">set</a>.</p>

</div>
</div>

### isPreservesZA() {#ab0f92885ea519bd5864c82b85067e6a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::isPreservesZA ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#a7920f986bb7bb24d992e3ca7ee970f6f">decodeZAState</a> and <a href="#a786805d9eb176b61475f63d699d6344ea5e837ef81141bf040b588faa5a333683">Preserved</a>.</p>


<p>Referenced by <a href="#a74b3e482c88651fdb789252fdb19b107">set</a>.</p>

</div>
</div>

### isPreservesZT0() {#a00f3d906fae5d5f0163bc69c7219d51a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::isPreservesZT0 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#a9c1be7584b445978af402d11e6cce2fd">decodeZT0State</a> and <a href="#a786805d9eb176b61475f63d699d6344ea5e837ef81141bf040b588faa5a333683">Preserved</a>.</p>


<p>Referenced by <a href="#a74b3e482c88651fdb789252fdb19b107">set</a>.</p>

</div>
</div>

### isUndefZT0() {#a7acc77cacd6e1f08bfe29e55f6374b23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::isUndefZT0 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>Reference <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161a4b700f4ff7fed0fe466634c23670c371">ZT0_Undef</a>.</p>

</div>
</div>

### requiresDisablingZABeforeCall() {#a7a3118e33d31e320d165ff3d5f0d0d63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::requiresDisablingZABeforeCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smeattrs">SMEAttrs</a> &amp; Callee)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#ad66eee3f9196f0a756ab985fdaebd171">hasZAState</a>, <a href="#ad68c22513c48158743ae0c58b8638aed">hasZT0State</a>, <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161a7e18bb628f3d4add46ae5f0e8bc06ea1">SME_ABI_Routine</a> and <a href="#a1cfa8c181aa3fd059200b7f7f936e9fe">SMEAttrs</a>.</p>


<p>Referenced by <a href="#a3f3e643c8ad7c96e3ea6c0fb389898c0">requiresEnablingZAAfterCall</a>.</p>

</div>
</div>

### requiresEnablingZAAfterCall() {#a3f3e643c8ad7c96e3ea6c0fb389898c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::requiresEnablingZAAfterCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smeattrs">SMEAttrs</a> &amp; Callee)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#a7a3118e33d31e320d165ff3d5f0d0d63">requiresDisablingZABeforeCall</a>, <a href="#ac4e4ec7b663af703242f9039b1692edd">requiresLazySave</a> and <a href="#a1cfa8c181aa3fd059200b7f7f936e9fe">SMEAttrs</a>.</p>

</div>
</div>

### requiresLazySave() {#ac4e4ec7b663af703242f9039b1692edd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::requiresLazySave (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smeattrs">SMEAttrs</a> &amp; Callee)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#ad66eee3f9196f0a756ab985fdaebd171">hasZAState</a>, <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161a7e18bb628f3d4add46ae5f0e8bc06ea1">SME_ABI_Routine</a> and <a href="#a1cfa8c181aa3fd059200b7f7f936e9fe">SMEAttrs</a>.</p>


<p>Referenced by <a href="#a3f3e643c8ad7c96e3ea6c0fb389898c0">requiresEnablingZAAfterCall</a>.</p>

</div>
</div>

### requiresPreservingAllZAState() {#a852ea409f16839e8072e7fb7fa77791d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::requiresPreservingAllZAState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smeattrs">SMEAttrs</a> &amp; Callee)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#a52ba4f9b8290209e88febec35b239e78">hasAgnosticZAInterface</a>, <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161a7e18bb628f3d4add46ae5f0e8bc06ea1">SME_ABI_Routine</a> and <a href="#a1cfa8c181aa3fd059200b7f7f936e9fe">SMEAttrs</a>.</p>

</div>
</div>

### requiresPreservingZT0() {#a4d818ea00be5db5237397edb1ddad5bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::requiresPreservingZT0 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smeattrs">SMEAttrs</a> &amp; Callee)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#ad68c22513c48158743ae0c58b8638aed">hasZT0State</a> and <a href="#a1cfa8c181aa3fd059200b7f7f936e9fe">SMEAttrs</a>.</p>

</div>
</div>

### requiresSMChange() {#a53b5f403cb0929bd20ac860f699cda2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SMEAttrs::requiresSMChange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smeattrs">SMEAttrs</a> &amp; Callee)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if a call from Caller -&gt; Callee requires a change in streaming mode.</p></dd>
</dl>


<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-cpp">AArch64SMEAttributes.cpp</a>.</p>


<p>References <a href="#a1702889e841fef1eafacab6fd2860082">hasNonStreamingInterfaceAndBody</a>, <a href="#a74197613bcbc100772a3359ab5788a14">hasStreamingInterfaceOrBody</a> and <a href="#a1cfa8c181aa3fd059200b7f7f936e9fe">SMEAttrs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a2fe24d660e9d8d98ce590a26cb40fe10">llvm::AArch64TTIImpl::getInlineCallPenalty</a>.</p>

</div>
</div>

### set() {#a74b3e482c88651fdb789252fdb19b107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SMEAttrs::set (unsigned M, bool Enable=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>, definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-cpp">AArch64SMEAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a2faec1f9f8cc7f8f40d521c4dd574f49">llvm::Enable</a>, <a href="#a52ba4f9b8290209e88febec35b239e78">hasAgnosticZAInterface</a>, <a href="#afc5529d6f2fb091f8f2a066d3f244526">hasSharedZAInterface</a>, <a href="#a3f213ec4d32444fe6f73dca3f3690e7d">hasStreamingCompatibleInterface</a>, <a href="#a0631da4d405aecafd9a30ab19f6a6488">hasStreamingInterface</a>, <a href="#aadc9b29185f58ba6752a3c7c5e254e14">isInOutZA</a>, <a href="#a6a7c8d26150da168c48f20e3ab5991c2">isInOutZT0</a>, <a href="#a2a044953a906f7fadb980d48bf095e20">isInZA</a>, <a href="#a53c16e2a7dc92cb1d8aa8549174fb02d">isInZT0</a>, <a href="#ac5c76ddab5601ff5ead828edc802e912">isNewZA</a>, <a href="#a69746b44d6e2baf8fde71e2ec31d1b36">isNewZT0</a>, <a href="#a699089d13481fdacd943a6cd11781739">isOutZA</a>, <a href="#a5ed8a49d1d4f5d58e8b3ebeefbdaecdb">isOutZT0</a>, <a href="#ab0f92885ea519bd5864c82b85067e6a3">isPreservesZA</a>, <a href="#a00f3d906fae5d5f0163bc69c7219d51a">isPreservesZT0</a>, <a href="#aa15a533e07f6ac4720eeff0eff804c35">sharesZA</a>, <a href="#a05704200885efea3fc85cff92725e91d">sharesZT0</a> and <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161a7e18bb628f3d4add46ae5f0e8bc06ea1">SME_ABI_Routine</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a78b4edb7f5a3d943e1e3b5a6bf0328c6">llvm::AArch64TTIImpl::areInlineCompatible</a>, <a href="#aa5e262aac758714fcbe1b579d3d37920">SMEAttrs</a> and <a href="#a1cfa8c181aa3fd059200b7f7f936e9fe">SMEAttrs</a>.</p>

</div>
</div>

### sharesZA() {#aa15a533e07f6ac4720eeff0eff804c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::sharesZA ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#a7920f986bb7bb24d992e3ca7ee970f6f">decodeZAState</a>, <a href="#a786805d9eb176b61475f63d699d6344eaefeb369cccbd560588a756610865664c">In</a>, <a href="#a786805d9eb176b61475f63d699d6344ea47a54d9da8952a3980d27488b00a21c1">InOut</a>, <a href="#a786805d9eb176b61475f63d699d6344ea7c147cda9e49590f6abe83d118b7353b">Out</a> and <a href="#a786805d9eb176b61475f63d699d6344ea5e837ef81141bf040b588faa5a333683">Preserved</a>.</p>


<p>Referenced by <a href="#afc5529d6f2fb091f8f2a066d3f244526">hasSharedZAInterface</a>, <a href="#ad66eee3f9196f0a756ab985fdaebd171">hasZAState</a> and <a href="#a74b3e482c88651fdb789252fdb19b107">set</a>.</p>

</div>
</div>

### sharesZT0() {#a05704200885efea3fc85cff92725e91d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMEAttrs::sharesZT0 ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#a9c1be7584b445978af402d11e6cce2fd">decodeZT0State</a>, <a href="#a786805d9eb176b61475f63d699d6344eaefeb369cccbd560588a756610865664c">In</a>, <a href="#a786805d9eb176b61475f63d699d6344ea47a54d9da8952a3980d27488b00a21c1">InOut</a>, <a href="#a786805d9eb176b61475f63d699d6344ea7c147cda9e49590f6abe83d118b7353b">Out</a> and <a href="#a786805d9eb176b61475f63d699d6344ea5e837ef81141bf040b588faa5a333683">Preserved</a>.</p>


<p>Referenced by <a href="#afc5529d6f2fb091f8f2a066d3f244526">hasSharedZAInterface</a>, <a href="#ad68c22513c48158743ae0c58b8638aed">hasZT0State</a> and <a href="#a74b3e482c88651fdb789252fdb19b107">set</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Bitmask {#aa909d6765da3f99943f92d067449a9b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SMEAttrs::Bitmask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### decodeZAState() {#a7920f986bb7bb24d992e3ca7ee970f6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StateValue llvm::SMEAttrs::decodeZAState (unsigned Bitmask)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161a48c5df039934edae90cfa029ef8e81dd">ZA_Mask</a> and <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161a36369aeedd545c2a472d3061db63bc56">ZA_Shift</a>.</p>


<p>Referenced by <a href="#aadc9b29185f58ba6752a3c7c5e254e14">isInOutZA</a>, <a href="#a2a044953a906f7fadb980d48bf095e20">isInZA</a>, <a href="#ac5c76ddab5601ff5ead828edc802e912">isNewZA</a>, <a href="#a699089d13481fdacd943a6cd11781739">isOutZA</a>, <a href="#ab0f92885ea519bd5864c82b85067e6a3">isPreservesZA</a> and <a href="#aa15a533e07f6ac4720eeff0eff804c35">sharesZA</a>.</p>

</div>
</div>

### decodeZT0State() {#a9c1be7584b445978af402d11e6cce2fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StateValue llvm::SMEAttrs::decodeZT0State (unsigned Bitmask)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>References <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161a595791f58d5b560bc6eae857bfdbbfff">ZT0_Mask</a> and <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161ae555bd5c5c3db5fa9459aa0cc10fe1c6">ZT0_Shift</a>.</p>


<p>Referenced by <a href="#a6a7c8d26150da168c48f20e3ab5991c2">isInOutZT0</a>, <a href="#a53c16e2a7dc92cb1d8aa8549174fb02d">isInZT0</a>, <a href="#a69746b44d6e2baf8fde71e2ec31d1b36">isNewZT0</a>, <a href="#a5ed8a49d1d4f5d58e8b3ebeefbdaecdb">isOutZT0</a>, <a href="#a00f3d906fae5d5f0163bc69c7219d51a">isPreservesZT0</a> and <a href="#a05704200885efea3fc85cff92725e91d">sharesZT0</a>.</p>

</div>
</div>

### encodeZAState() {#a12e5d29860fe2c7589e171f9226ac72a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SMEAttrs::encodeZAState (<a href="#a786805d9eb176b61475f63d699d6344e">StateValue</a> S)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>Reference <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161a36369aeedd545c2a472d3061db63bc56">ZA_Shift</a>.</p>


<p>Referenced by <a href="#aa6d7c918ff7f20fdc03905b056edd11e">SMEAttrs</a> and <a href="#ac62a2489e88e4e05e640c4bf6b29082f">SMEAttrs</a>.</p>

</div>
</div>

### encodeZT0State() {#aff781ae50114ed4d856994602a9d5406}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SMEAttrs::encodeZT0State (<a href="#a786805d9eb176b61475f63d699d6344e">StateValue</a> S)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a>.</p>


<p>Reference <a href="#ac3ddd43ec0706cb4af5f9f5b910b2161ae555bd5c5c3db5fa9459aa0cc10fe1c6">ZT0_Shift</a>.</p>


<p>Referenced by <a href="#aa6d7c918ff7f20fdc03905b056edd11e">SMEAttrs</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-cpp">AArch64SMEAttributes.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">AArch64SMEAttributes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
