---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dxilbindingmap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DXILBindingMap` Class



## Declaration

<div class="doxyDeclaration">
class llvm::DXILBindingMap { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">llvm/Analysis/DXILResource.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeda3608306b6cbfe5714a924813ecbfc">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo">dxil::ResourceBindingInfo</a> &gt;::iterator</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea789cde5885eba58b7f868bef857819">const_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo">dxil::ResourceBindingInfo</a> &gt;::const_iterator</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe395509f4d2fa957386dcae55733fe4">DXILResourceBindingAnalysis</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38a83403e9ec3cd77ffe71f32d2a3339">DXILResourceBindingWrapperPass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aeda3608306b6cbfe5714a924813ecbfc">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74e1b81ca73d8ed22f6ce0e77a966dc4">begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aea789cde5885eba58b7f868bef857819">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52aafbe0b0f293d85ad799b2fc56cb7d">begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aeda3608306b6cbfe5714a924813ecbfc">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec887fcb4679a05828b0500e44264bdf">end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aea789cde5885eba58b7f868bef857819">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bb36f1e6aeb28045321f9b42657d05f">end</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e54b766c239100a4742f07c8edf440a">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aeda3608306b6cbfe5714a924813ecbfc">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13e5e795eceff514135b36d6799d9e94">find</a> (const CallInst *Key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aea789cde5885eba58b7f868bef857819">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81a4625acf09575b1d7ab6a28e09cd1e">find</a> (const CallInst *Key) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aeda3608306b6cbfe5714a924813ecbfc">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeef3240163c06611e004433341e1707">srv_begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aea789cde5885eba58b7f868bef857819">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68a3ee7f0143522b89777bdc896f556f">srv_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aeda3608306b6cbfe5714a924813ecbfc">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb754a0b4bd6b996cd778d2df35cd3b">srv_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aea789cde5885eba58b7f868bef857819">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba92317a2e2bc9f934b851ffb0a522d2">srv_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#aeda3608306b6cbfe5714a924813ecbfc">iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7794c7fbe171e5c70d604343647e9436">srvs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#aea789cde5885eba58b7f868bef857819">const_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07ee02c28b670f15b85b55752a4a2a79">srvs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aeda3608306b6cbfe5714a924813ecbfc">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab50a778955892b5e13ee107b436416a2">uav_begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aea789cde5885eba58b7f868bef857819">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac292b36bac693233c8e00aa6297bf017">uav_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aeda3608306b6cbfe5714a924813ecbfc">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74949a6e6b937c54cca97fcc11df5afa">uav_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aea789cde5885eba58b7f868bef857819">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91bdd4a4bfaebbbff93374a41ab6089f">uav_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#aeda3608306b6cbfe5714a924813ecbfc">iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2aff0b0669895df82de56ea93641d40">uavs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#aea789cde5885eba58b7f868bef857819">const_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a17b2b196ce93a2e77262987f33191e">uavs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aeda3608306b6cbfe5714a924813ecbfc">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4abb4b5c8e3f82376c21fb99e11a8c8b">cbuffer_begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aea789cde5885eba58b7f868bef857819">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab723f905a2e222bc7ffc05584067c01e">cbuffer_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aeda3608306b6cbfe5714a924813ecbfc">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac78f861fa19f18f2178da4b3ca0f2bc0">cbuffer_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aea789cde5885eba58b7f868bef857819">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6526e95d090c0faef5e7531ef0134061">cbuffer_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#aeda3608306b6cbfe5714a924813ecbfc">iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09b441646cb8c12800c253403d6c5f21">cbuffers</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#aea789cde5885eba58b7f868bef857819">const_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b5f741d1bca86b6b6e07f46cd95c371">cbuffers</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aeda3608306b6cbfe5714a924813ecbfc">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9f209a11f26fc23d75201a6e4b2bf4f">sampler_begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aea789cde5885eba58b7f868bef857819">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a40786f6f379526c746d6d763ce112a">sampler_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aeda3608306b6cbfe5714a924813ecbfc">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f53e22e490fa9f8bb6cc5778f321a1d">sampler_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aea789cde5885eba58b7f868bef857819">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f1bdc78a6b2525e216b60610799d1f7">sampler_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#aeda3608306b6cbfe5714a924813ecbfc">iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a821ddc9c4832dcfc6c066490fc2400c9">samplers</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#aea789cde5885eba58b7f868bef857819">const_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a422e8af3dd8530c73476e75b04a49eb5">samplers</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42b1001c73526313afc7d8da2ccb937c">print</a> (raw_ostream &amp;OS, DXILResourceTypeMap &amp;DRTM, const DataLayout &amp;DL) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ad3949d6a40a442a9949b5a323d1459">populate</a> (Module &amp;M, DXILResourceTypeMap &amp;DRTM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populate the map given the resource binding calls in the given module. <a href="#a3ad3949d6a40a442a9949b5a323d1459">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo">dxil::ResourceBindingInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4efa8fe05e675fc02d52cda249fb50b">Infos</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54184cddf5afb65f1a3a96e53fd0bd7a">CallMap</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab6aa194ad5d8400cc0607ad5c5d0b57">FirstUAV</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec55d73c79f47f6bd12b2e17b41ed239">FirstCBuffer</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adec8cf9744fe84d22fcd511d770fb898">FirstSampler</a> = 0</td>
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


<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#aea789cde5885eba58b7f868bef857819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DXILBindingMap::const_iterator =  SmallVector&lt;dxil::ResourceBindingInfo&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

### iterator {#aeda3608306b6cbfe5714a924813ecbfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DXILBindingMap::iterator =  SmallVector&lt;dxil::ResourceBindingInfo&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DXILResourceBindingAnalysis {#abe395509f4d2fa957386dcae55733fe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/dxilresourcebindinganalysis">DXILResourceBindingAnalysis</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="#abe395509f4d2fa957386dcae55733fe4">DXILResourceBindingAnalysis</a>.</p>


<p>Referenced by <a href="#abe395509f4d2fa957386dcae55733fe4">DXILResourceBindingAnalysis</a>.</p>

</div>
</div>

### DXILResourceBindingWrapperPass {#a38a83403e9ec3cd77ffe71f32d2a3339}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/dxilresourcebindingwrapperpass">DXILResourceBindingWrapperPass</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="#a38a83403e9ec3cd77ffe71f32d2a3339">DXILResourceBindingWrapperPass</a>.</p>


<p>Referenced by <a href="#a38a83403e9ec3cd77ffe71f32d2a3339">DXILResourceBindingWrapperPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a74e1b81ca73d8ed22f6ce0e77a966dc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::DXILBindingMap::begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Referenced by <a href="#a4abb4b5c8e3f82376c21fb99e11a8c8b">cbuffer_begin</a>, <a href="#ab723f905a2e222bc7ffc05584067c01e">cbuffer_begin</a>, <a href="#ac78f861fa19f18f2178da4b3ca0f2bc0">cbuffer_end</a>, <a href="#a6526e95d090c0faef5e7531ef0134061">cbuffer_end</a>, <a href="#af9f209a11f26fc23d75201a6e4b2bf4f">sampler_begin</a>, <a href="#a4a40786f6f379526c746d6d763ce112a">sampler_begin</a>, <a href="#adeef3240163c06611e004433341e1707">srv_begin</a>, <a href="#a68a3ee7f0143522b89777bdc896f556f">srv_begin</a>, <a href="#abbb754a0b4bd6b996cd778d2df35cd3b">srv_end</a>, <a href="#aba92317a2e2bc9f934b851ffb0a522d2">srv_end</a>, <a href="#ab50a778955892b5e13ee107b436416a2">uav_begin</a>, <a href="#ac292b36bac693233c8e00aa6297bf017">uav_begin</a>, <a href="#a74949a6e6b937c54cca97fcc11df5afa">uav_end</a> and <a href="#a91bdd4a4bfaebbbff93374a41ab6089f">uav_end</a>.</p>

</div>
</div>

### begin() {#a52aafbe0b0f293d85ad799b2fc56cb7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::DXILBindingMap::begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

### cbuffer\_begin() {#a4abb4b5c8e3f82376c21fb99e11a8c8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::DXILBindingMap::cbuffer_begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="#a74e1b81ca73d8ed22f6ce0e77a966dc4">begin</a>.</p>


<p>Referenced by <a href="#a09b441646cb8c12800c253403d6c5f21">cbuffers</a> and <a href="#a8b5f741d1bca86b6b6e07f46cd95c371">cbuffers</a>.</p>

</div>
</div>

### cbuffer\_begin() {#ab723f905a2e222bc7ffc05584067c01e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::DXILBindingMap::cbuffer_begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="#a74e1b81ca73d8ed22f6ce0e77a966dc4">begin</a>.</p>

</div>
</div>

### cbuffer\_end() {#ac78f861fa19f18f2178da4b3ca0f2bc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::DXILBindingMap::cbuffer_end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="#a74e1b81ca73d8ed22f6ce0e77a966dc4">begin</a>.</p>


<p>Referenced by <a href="#a09b441646cb8c12800c253403d6c5f21">cbuffers</a> and <a href="#a8b5f741d1bca86b6b6e07f46cd95c371">cbuffers</a>.</p>

</div>
</div>

### cbuffer\_end() {#a6526e95d090c0faef5e7531ef0134061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::DXILBindingMap::cbuffer_end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="#a74e1b81ca73d8ed22f6ce0e77a966dc4">begin</a>.</p>

</div>
</div>

### cbuffers() {#a09b441646cb8c12800c253403d6c5f21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; iterator &gt; llvm::DXILBindingMap::cbuffers ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>References <a href="#a4abb4b5c8e3f82376c21fb99e11a8c8b">cbuffer_begin</a>, <a href="#ac78f861fa19f18f2178da4b3ca0f2bc0">cbuffer_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a75f9b9721a2718d692fd3805c713f2ff">emitResourceMetadata</a>.</p>

</div>
</div>

### cbuffers() {#a8b5f741d1bca86b6b6e07f46cd95c371}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_iterator &gt; llvm::DXILBindingMap::cbuffers ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>References <a href="#a4abb4b5c8e3f82376c21fb99e11a8c8b">cbuffer_begin</a>, <a href="#ac78f861fa19f18f2178da4b3ca0f2bc0">cbuffer_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### empty() {#a6e54b766c239100a4742f07c8edf440a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DXILBindingMap::empty ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a75f9b9721a2718d692fd3805c713f2ff">emitResourceMetadata</a>.</p>

</div>
</div>

### end() {#aec887fcb4679a05828b0500e44264bdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::DXILBindingMap::end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Referenced by <a href="#a7f53e22e490fa9f8bb6cc5778f321a1d">sampler_end</a> and <a href="#a2f1bdc78a6b2525e216b60610799d1f7">sampler_end</a>.</p>

</div>
</div>

### end() {#a8bb36f1e6aeb28045321f9b42657d05f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::DXILBindingMap::end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

### find() {#a13e5e795eceff514135b36d6799d9e94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::DXILBindingMap::find (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * Key)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### find() {#a81a4625acf09575b1d7ab6a28e09cd1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::DXILBindingMap::find (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * Key)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### print() {#a42b1001c73526313afc7d8da2ccb937c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBindingMap::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/dxilresourcetypemap">DXILResourceTypeMap</a> &amp; DRTM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 757 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a47f93450ef17fba62a5182c8070230ee">llvm::dxil::ResourceBindingInfo::getHandleTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#ae91cb2487ec1305b31571bb8187dbf68">llvm::dxil::ResourceBindingInfo::print</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dxilresourcebindingprinterpass/#a9c5f08a05826fa28ba48d255e06f1b97">llvm::DXILResourceBindingPrinterPass::run</a>.</p>

</div>
</div>

### sampler\_begin() {#af9f209a11f26fc23d75201a6e4b2bf4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::DXILBindingMap::sampler_begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="#a74e1b81ca73d8ed22f6ce0e77a966dc4">begin</a>.</p>


<p>Referenced by <a href="#a821ddc9c4832dcfc6c066490fc2400c9">samplers</a> and <a href="#a422e8af3dd8530c73476e75b04a49eb5">samplers</a>.</p>

</div>
</div>

### sampler\_begin() {#a4a40786f6f379526c746d6d763ce112a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::DXILBindingMap::sampler_begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="#a74e1b81ca73d8ed22f6ce0e77a966dc4">begin</a>.</p>

</div>
</div>

### sampler\_end() {#a7f53e22e490fa9f8bb6cc5778f321a1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::DXILBindingMap::sampler_end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="#aec887fcb4679a05828b0500e44264bdf">end</a>.</p>


<p>Referenced by <a href="#a821ddc9c4832dcfc6c066490fc2400c9">samplers</a> and <a href="#a422e8af3dd8530c73476e75b04a49eb5">samplers</a>.</p>

</div>
</div>

### sampler\_end() {#a2f1bdc78a6b2525e216b60610799d1f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::DXILBindingMap::sampler_end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="#aec887fcb4679a05828b0500e44264bdf">end</a>.</p>

</div>
</div>

### samplers() {#a821ddc9c4832dcfc6c066490fc2400c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; iterator &gt; llvm::DXILBindingMap::samplers ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#af9f209a11f26fc23d75201a6e4b2bf4f">sampler_begin</a> and <a href="#a7f53e22e490fa9f8bb6cc5778f321a1d">sampler_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a75f9b9721a2718d692fd3805c713f2ff">emitResourceMetadata</a>.</p>

</div>
</div>

### samplers() {#a422e8af3dd8530c73476e75b04a49eb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_iterator &gt; llvm::DXILBindingMap::samplers ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#af9f209a11f26fc23d75201a6e4b2bf4f">sampler_begin</a> and <a href="#a7f53e22e490fa9f8bb6cc5778f321a1d">sampler_end</a>.</p>

</div>
</div>

### srv\_begin() {#adeef3240163c06611e004433341e1707}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::DXILBindingMap::srv_begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="#a74e1b81ca73d8ed22f6ce0e77a966dc4">begin</a>.</p>


<p>Referenced by <a href="#a7794c7fbe171e5c70d604343647e9436">srvs</a> and <a href="#a07ee02c28b670f15b85b55752a4a2a79">srvs</a>.</p>

</div>
</div>

### srv\_begin() {#a68a3ee7f0143522b89777bdc896f556f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::DXILBindingMap::srv_begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="#a74e1b81ca73d8ed22f6ce0e77a966dc4">begin</a>.</p>

</div>
</div>

### srv\_end() {#abbb754a0b4bd6b996cd778d2df35cd3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::DXILBindingMap::srv_end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="#a74e1b81ca73d8ed22f6ce0e77a966dc4">begin</a>.</p>


<p>Referenced by <a href="#a7794c7fbe171e5c70d604343647e9436">srvs</a> and <a href="#a07ee02c28b670f15b85b55752a4a2a79">srvs</a>.</p>

</div>
</div>

### srv\_end() {#aba92317a2e2bc9f934b851ffb0a522d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::DXILBindingMap::srv_end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="#a74e1b81ca73d8ed22f6ce0e77a966dc4">begin</a>.</p>

</div>
</div>

### srvs() {#a7794c7fbe171e5c70d604343647e9436}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; iterator &gt; llvm::DXILBindingMap::srvs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#adeef3240163c06611e004433341e1707">srv_begin</a> and <a href="#abbb754a0b4bd6b996cd778d2df35cd3b">srv_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a75f9b9721a2718d692fd3805c713f2ff">emitResourceMetadata</a>.</p>

</div>
</div>

### srvs() {#a07ee02c28b670f15b85b55752a4a2a79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_iterator &gt; llvm::DXILBindingMap::srvs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#adeef3240163c06611e004433341e1707">srv_begin</a> and <a href="#abbb754a0b4bd6b996cd778d2df35cd3b">srv_end</a>.</p>

</div>
</div>

### uav\_begin() {#ab50a778955892b5e13ee107b436416a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::DXILBindingMap::uav_begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="#a74e1b81ca73d8ed22f6ce0e77a966dc4">begin</a>.</p>


<p>Referenced by <a href="#ad2aff0b0669895df82de56ea93641d40">uavs</a> and <a href="#a8a17b2b196ce93a2e77262987f33191e">uavs</a>.</p>

</div>
</div>

### uav\_begin() {#ac292b36bac693233c8e00aa6297bf017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::DXILBindingMap::uav_begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="#a74e1b81ca73d8ed22f6ce0e77a966dc4">begin</a>.</p>

</div>
</div>

### uav\_end() {#a74949a6e6b937c54cca97fcc11df5afa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::DXILBindingMap::uav_end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="#a74e1b81ca73d8ed22f6ce0e77a966dc4">begin</a>.</p>


<p>Referenced by <a href="#ad2aff0b0669895df82de56ea93641d40">uavs</a> and <a href="#a8a17b2b196ce93a2e77262987f33191e">uavs</a>.</p>

</div>
</div>

### uav\_end() {#a91bdd4a4bfaebbbff93374a41ab6089f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::DXILBindingMap::uav_end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>Reference <a href="#a74e1b81ca73d8ed22f6ce0e77a966dc4">begin</a>.</p>

</div>
</div>

### uavs() {#ad2aff0b0669895df82de56ea93641d40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; iterator &gt; llvm::DXILBindingMap::uavs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#ab50a778955892b5e13ee107b436416a2">uav_begin</a> and <a href="#a74949a6e6b937c54cca97fcc11df5afa">uav_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a75f9b9721a2718d692fd3805c713f2ff">emitResourceMetadata</a>.</p>

</div>
</div>

### uavs() {#a8a17b2b196ce93a2e77262987f33191e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_iterator &gt; llvm::DXILBindingMap::uavs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#ab50a778955892b5e13ee107b436416a2">uav_begin</a> and <a href="#a74949a6e6b937c54cca97fcc11df5afa">uav_end</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### populate() {#a3ad3949d6a40a442a9949b5a323d1459}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DXILBindingMap::populate (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/dxilresourcetypemap">DXILResourceTypeMap</a> &amp; DRTM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Populate the map given the resource binding calls in the given module.</p>

<p>Declaration at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>, definition at line 682 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CallMap {#a54184cddf5afb65f1a3a96e53fd0bd7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;CallInst *, unsigned&gt; llvm::DXILBindingMap::CallMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

### FirstCBuffer {#aec55d73c79f47f6bd12b2e17b41ed239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DXILBindingMap::FirstCBuffer = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

### FirstSampler {#adec8cf9744fe84d22fcd511d770fb898}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DXILBindingMap::FirstSampler = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

### FirstUAV {#aab6aa194ad5d8400cc0607ad5c5d0b57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DXILBindingMap::FirstUAV = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

### Infos {#ad4efa8fe05e675fc02d52cda249fb50b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;dxil::ResourceBindingInfo&gt; llvm::DXILBindingMap::Infos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dxilresource-h">DXILResource.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilresource-cpp">DXILResource.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
