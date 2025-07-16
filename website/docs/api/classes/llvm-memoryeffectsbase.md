---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memoryeffectsbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MemoryEffectsBase` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename LocationEnum&gt;
class llvm::MemoryEffectsBase&lt;LocationEnum&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">llvm/Support/ModRef.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a802b3c8c587d808116e71ca648a3e868">Location</a> = LocationEnum</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a74997d7ce097d24d16694d10b48a9e5c">MemoryEffectsBase</a> (Location Loc, ModRefInfo MR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> that can access only the given location with the given <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a>. <a href="#a74997d7ce097d24d16694d10b48a9e5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a58c45934536d15a5b43f3b3df864958a">MemoryEffectsBase</a> (ModRefInfo MR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> that can access any location with the given <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a>. <a href="#a58c45934536d15a5b43f3b3df864958a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a847454057de73421174617ea9685e486">MemoryEffectsBase</a> (uint32_t Data)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0647b4ca7130ebfaeaf73e2e9ba90bb9">operator&amp;</a> (MemoryEffectsBase Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Intersect with other <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a>. <a href="#a0647b4ca7130ebfaeaf73e2e9ba90bb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7810e96fc95a23b4c5e3c9dfe4966467">operator&amp;=</a> (MemoryEffectsBase Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Intersect (in-place) with other <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a>. <a href="#a7810e96fc95a23b4c5e3c9dfe4966467">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aae7d83c089436d03366e5af1d477efc3">operator|</a> (MemoryEffectsBase Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Union with other <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a>. <a href="#aae7d83c089436d03366e5af1d477efc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a34935466bb869ed05156021faa7a2db9">operator|=</a> (MemoryEffectsBase Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Union (in-place) with other <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a>. <a href="#a34935466bb869ed05156021faa7a2db9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4e9da0c65bcd238f92100f355d801f1c">operator-</a> (MemoryEffectsBase Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subtract other <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a>. <a href="#a4e9da0c65bcd238f92100f355d801f1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a997b74377e782f9bcfce8e416e291984">operator-=</a> (MemoryEffectsBase Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subtract (in-place) with other <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a>. <a href="#a997b74377e782f9bcfce8e416e291984">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afbb811fd9bb3d6e2e5367a4146c4ab3b">operator==</a> (MemoryEffectsBase Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this is the same as other <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a>. <a href="#afbb811fd9bb3d6e2e5367a4146c4ab3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4de8c4cc39874ea819585ee591caacfe">operator!=</a> (MemoryEffectsBase Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this is different from other <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a>. <a href="#a4de8c4cc39874ea819585ee591caacfe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac96f712f6d153d48c535886b4f8aef99">toIntValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> into an encoded integer value (used by memory attribute). <a href="#ac96f712f6d153d48c535886b4f8aef99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a76a16756c4c05000711a5ab6c68756dc">getModRef</a> (Location Loc) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> for the given <a href="#a802b3c8c587d808116e71ca648a3e868">Location</a>. <a href="#a76a16756c4c05000711a5ab6c68756dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a377f894a55f1314c9c80676af57dd05e">getWithModRef</a> (Location Loc, ModRefInfo MR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get new <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> with modified <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> for <a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>. <a href="#a377f894a55f1314c9c80676af57dd05e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a309d79f032666ad65850aa624a75e2fb">getWithoutLoc</a> (Location Loc) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get new <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> with NoModRef on the given <a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>. <a href="#a309d79f032666ad65850aa624a75e2fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7b1f988b33c9acdb6743a05cf97f61b5">getModRef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> for any location. <a href="#a7b1f988b33c9acdb6743a05cf97f61b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a513f55e474dba6d6c2507997e9920b6d">doesNotAccessMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this function accesses no memory. <a href="#a513f55e474dba6d6c2507997e9920b6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8c57cabc627d282678d407f79da2b6e7">onlyReadsMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this function only (at most) reads memory. <a href="#a8c57cabc627d282678d407f79da2b6e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0fc7f721f42a2177d9d6d94972a5cde5">onlyWritesMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this function only (at most) writes memory. <a href="#a0fc7f721f42a2177d9d6d94972a5cde5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8bc927c80d7734e7e0baef13efd08bc5">onlyAccessesArgPointees</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this function only (at most) accesses argument memory. <a href="#a8bc927c80d7734e7e0baef13efd08bc5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5b51f25d05e964bb12c8386744c9eb05">doesAccessArgPointees</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this function may access argument memory. <a href="#a5b51f25d05e964bb12c8386744c9eb05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a636d669d76e435e9d71cdc417c89a30c">onlyAccessesInaccessibleMem</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this function only (at most) accesses inaccessible memory. <a href="#a636d669d76e435e9d71cdc417c89a30c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afe3bf77a36d10551139f91d68bb00c4d">onlyAccessesInaccessibleOrArgMem</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this function only (at most) accesses argument and inaccessible memory. <a href="#afe3bf77a36d10551139f91d68bb00c4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4fd9abbca99d1a1f6fccc7e10cd0ba76">setModRef</a> (Location Loc, ModRefInfo MR)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0bca4cbd9c0dadcc80f75e22186c5778">Data</a> = 0</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abfc43f0b4a68c9701a315cae51761f66">locations</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns iterator over all supported location kinds. <a href="#abfc43f0b4a68c9701a315cae51761f66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aff771abf487136aeebb6862871d5e715">unknown</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> that can read and write any memory. <a href="#aff771abf487136aeebb6862871d5e715">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af04065f3c729719471689b08089942f3">none</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> that cannot read or write any memory. <a href="#af04065f3c729719471689b08089942f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0dc1a3456bce25673dff8dce6f240a8f">readOnly</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> that can read any memory. <a href="#a0dc1a3456bce25673dff8dce6f240a8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9e3dc568b5f51e03441c9c44b618f337">writeOnly</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> that can write any memory. <a href="#a9e3dc568b5f51e03441c9c44b618f337">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5288b2ba178703d9e1f24a5d3708f594">argMemOnly</a> (ModRefInfo MR=ModRefInfo::ModRef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> that can only access argument memory. <a href="#a5288b2ba178703d9e1f24a5d3708f594">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5cba4a49c183c6c2f6168be64f04a7b9">inaccessibleMemOnly</a> (ModRefInfo MR=ModRefInfo::ModRef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> that can only access inaccessible memory. <a href="#a5cba4a49c183c6c2f6168be64f04a7b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad341f584befc40ff0aefca99682baf7c">inaccessibleOrArgMemOnly</a> (ModRefInfo MR=ModRefInfo::ModRef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> that can only access inaccessible or argument memory. <a href="#ad341f584befc40ff0aefca99682baf7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a93c6a6bc46c56b292db3ba60e92341a5">createFromIntValue</a> (uint32_t Data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> from an encoded integer value (used by memory attribute). <a href="#a93c6a6bc46c56b292db3ba60e92341a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a606cf244f47a20896b8728131fc999c5">getLocationPos</a> (Location Loc)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac3e6e18e6224f0a3ac273f470867fcd4">BitsPerLoc</a> = 2</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename LocationEnum&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6f1e4c10696d1cba1938ef73c182b1f1">LocMask</a> = (1 &lt;&lt; BitsPerLoc) - 1</td>
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


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Location {#a802b3c8c587d808116e71ca648a3e868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemoryEffectsBase&lt; LocationEnum &gt;::Location =  LocationEnum</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MemoryEffectsBase() {#a74997d7ce097d24d16694d10b48a9e5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::MemoryEffectsBase (<a href="#a802b3c8c587d808116e71ca648a3e868">Location</a> Loc, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> MR)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> that can access only the given location with the given <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a>.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

### MemoryEffectsBase() {#a58c45934536d15a5b43f3b3df864958a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::MemoryEffectsBase (<a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> MR)</td>
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

<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> that can access any location with the given <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a>.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### MemoryEffectsBase() {#a847454057de73421174617ea9685e486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::MemoryEffectsBase (uint32_t Data)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator-() {#a4e9da0c65bcd238f92100f355d801f1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffectsBase llvm::MemoryEffectsBase&lt; LocationEnum &gt;::operator- (<a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Subtract other <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a>.</p>

<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

### operator-=() {#a997b74377e782f9bcfce8e416e291984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffectsBase &amp; llvm::MemoryEffectsBase&lt; LocationEnum &gt;::operator-= (<a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Subtract (in-place) with other <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a>.</p>

<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

### operator!=() {#a4de8c4cc39874ea819585ee591caacfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemoryEffectsBase&lt; LocationEnum &gt;::operator!= (<a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this is different from other <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a>.</p>

<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

### operator&amp;() {#a0647b4ca7130ebfaeaf73e2e9ba90bb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffectsBase llvm::MemoryEffectsBase&lt; LocationEnum &gt;::operator&amp; (<a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Intersect with other <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a>.</p>

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

### operator&amp;=() {#a7810e96fc95a23b4c5e3c9dfe4966467}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffectsBase &amp; llvm::MemoryEffectsBase&lt; LocationEnum &gt;::operator&amp;= (<a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Intersect (in-place) with other <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a>.</p>

<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

### operator==() {#afbb811fd9bb3d6e2e5367a4146c4ab3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemoryEffectsBase&lt; LocationEnum &gt;::operator== (<a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this is the same as other <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a>.</p>

<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>


<p>Referenced by <a href="#a4de8c4cc39874ea819585ee591caacfe">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::operator!=</a>.</p>

</div>
</div>

### operator|() {#aae7d83c089436d03366e5af1d477efc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffectsBase llvm::MemoryEffectsBase&lt; LocationEnum &gt;::operator| (<a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Union with other <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a>.</p>

<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

### operator|=() {#a34935466bb869ed05156021faa7a2db9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffectsBase &amp; llvm::MemoryEffectsBase&lt; LocationEnum &gt;::operator|= (<a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Union (in-place) with other <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a>.</p>

<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### doesAccessArgPointees() {#a5b51f25d05e964bb12c8386744c9eb05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemoryEffectsBase&lt; LocationEnum &gt;::doesAccessArgPointees ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether this function may access argument memory.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

### doesNotAccessMemory() {#a513f55e474dba6d6c2507997e9920b6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemoryEffectsBase&lt; LocationEnum &gt;::doesNotAccessMemory ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether this function accesses no memory.</p>

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a8b8a65f41fa956162c7877cb20bc53b9">checkFunctionMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#afc83c1972006a05871f65fdf15ade10f">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::createHvxIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#a4330af78f333c52e594aa71baa274bd1">llvm::AAResults::doesNotAccessMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#a3a92463610cec77938dacc8eecbc3ee4">llvm::AAResults::doesNotAccessMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a16951c81e4ffebc84739c2882a030e4f">llvm::CallBase::doesNotAccessMemory</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#a52100ca4ffaf0494489db89087b1f48a">getFunctionControl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#ad06b99b6c5abffb1da312f75775f2f08">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getKnownStateFromValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ae2b19bc21d3201e045841292463888ba">llvm::SITargetLowering::getTgtMemIntrinsic</a>, <a href="#a8bc927c80d7734e7e0baef13efd08bc5">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::onlyAccessesArgPointees</a>, <a href="#a636d669d76e435e9d71cdc417c89a30c">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::onlyAccessesInaccessibleMem</a> and <a href="#afe3bf77a36d10551139f91d68bb00c4d">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::onlyAccessesInaccessibleOrArgMem</a>.</p>

</div>
</div>

### getModRef() {#a76a16756c4c05000711a5ab6c68756dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModRefInfo llvm::MemoryEffectsBase&lt; LocationEnum &gt;::getModRef (<a href="#a802b3c8c587d808116e71ca648a3e868">Location</a> Loc)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> for the given <a href="#a802b3c8c587d808116e71ca648a3e868">Location</a>.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#aa407dded90aa101d97422c314f4c64fa">addMemoryAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a8b8a65f41fa956162c7877cb20bc53b9">checkFunctionMemoryAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a11e85bd0636c06273039d95814064fd1">determinePointerAccessAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a493e72ce53ee16d92489ba67d7ce2bb0">llvm::Attribute::getAsString</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#ad06b99b6c5abffb1da312f75775f2f08">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getKnownStateFromValue</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#a380206b387f7ab435e1aec0883ec79da">llvm::AAResults::getModRefInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1932ad741b05257d027a7952eb98a98e">llvm::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>.</p>

</div>
</div>

### getModRef() {#a7b1f988b33c9acdb6743a05cf97f61b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModRefInfo llvm::MemoryEffectsBase&lt; LocationEnum &gt;::getModRef ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> for any location.</p>

<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>


<p>Referenced by <a href="#a5b51f25d05e964bb12c8386744c9eb05">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::doesAccessArgPointees</a>, <a href="#a7b1f988b33c9acdb6743a05cf97f61b5">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::getModRef</a>, <a href="#a8c57cabc627d282678d407f79da2b6e7">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::onlyReadsMemory</a> and <a href="#a0fc7f721f42a2177d9d6d94972a5cde5">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::onlyWritesMemory</a>.</p>

</div>
</div>

### getWithModRef() {#a377f894a55f1314c9c80676af57dd05e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffectsBase llvm::MemoryEffectsBase&lt; LocationEnum &gt;::getWithModRef (<a href="#a802b3c8c587d808116e71ca648a3e868">Location</a> Loc, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> MR)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get new <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> with modified <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> for <a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

### getWithoutLoc() {#a309d79f032666ad65850aa624a75e2fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffectsBase llvm::MemoryEffectsBase&lt; LocationEnum &gt;::getWithoutLoc (<a href="#a802b3c8c587d808116e71ca648a3e868">Location</a> Loc)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get new <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> with NoModRef on the given <a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>.</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a8b8a65f41fa956162c7877cb20bc53b9">checkFunctionMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ab55d9da87838f5736581bfcd5b54afa1">llvm::AAResults::getModRefInfo</a>, <a href="#a8bc927c80d7734e7e0baef13efd08bc5">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::onlyAccessesArgPointees</a>, <a href="#a636d669d76e435e9d71cdc417c89a30c">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::onlyAccessesInaccessibleMem</a> and <a href="#afe3bf77a36d10551139f91d68bb00c4d">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::onlyAccessesInaccessibleOrArgMem</a>.</p>

</div>
</div>

### onlyAccessesArgPointees() {#a8bc927c80d7734e7e0baef13efd08bc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemoryEffectsBase&lt; LocationEnum &gt;::onlyAccessesArgPointees ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether this function only (at most) accesses argument memory.</p>

<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aa35af336fee32786b6551e23d5b55fcf">AddAliasScopeMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a1b3a1bca1f908fbc09a8c4cb5df7e155">llvm::objcarc::CanAlterRefCount</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#ad06b99b6c5abffb1da312f75775f2f08">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getKnownStateFromValue</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#adc6331fb2f51f3f964b8f9494ab6620e">llvm::CallBase::onlyAccessesArgMemory</a>.</p>

</div>
</div>

### onlyAccessesInaccessibleMem() {#a636d669d76e435e9d71cdc417c89a30c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemoryEffectsBase&lt; LocationEnum &gt;::onlyAccessesInaccessibleMem ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether this function only (at most) accesses inaccessible memory.</p>

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aa35af336fee32786b6551e23d5b55fcf">AddAliasScopeMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#afc83c1972006a05871f65fdf15ade10f">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::createHvxIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#ad06b99b6c5abffb1da312f75775f2f08">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getKnownStateFromValue</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a34613a108e56086f52edab637d1d55ae">llvm::CallBase::onlyAccessesInaccessibleMemory</a>.</p>

</div>
</div>

### onlyAccessesInaccessibleOrArgMem() {#afe3bf77a36d10551139f91d68bb00c4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemoryEffectsBase&lt; LocationEnum &gt;::onlyAccessesInaccessibleOrArgMem ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether this function only (at most) accesses argument and inaccessible memory.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#ad06b99b6c5abffb1da312f75775f2f08">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getKnownStateFromValue</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a7a2ce134efb83b008e2180d30451ac98">llvm::CallBase::onlyAccessesInaccessibleMemOrArgMem</a>.</p>

</div>
</div>

### onlyReadsMemory() {#a8c57cabc627d282678d407f79da2b6e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemoryEffectsBase&lt; LocationEnum &gt;::onlyReadsMemory ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether this function only (at most) reads memory.</p>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a1b3a1bca1f908fbc09a8c4cb5df7e155">llvm::objcarc::CanAlterRefCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#a52100ca4ffaf0494489db89087b1f48a">getFunctionControl</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ae2b19bc21d3201e045841292463888ba">llvm::SITargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/structs/llvm/aanosync/#a490ad1c48c230e1b6d37e946faee435a">llvm::AANoSync::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/llvm/aawillreturn/#ad0a0762d528846cb12d21320fcab8a24">llvm::AAWillReturn::isImpliedByMustprogressAndReadonly</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsite/#a0451826f9ecd21f9d963cc51401b1b4d">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfunction/#ae444282c6d6bc8d5e9905620c936d39e">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFunction::manifest</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#acc08d3794eb34598ea9f389c9b7f51d1">llvm::AAResults::onlyReadsMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#a886b0258a95e5395f4df14207b1f8255">llvm::AAResults::onlyReadsMemory</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a5be058522f7a1076ffb760c30171b2cd">llvm::CallBase::onlyReadsMemory</a>.</p>

</div>
</div>

### onlyWritesMemory() {#a0fc7f721f42a2177d9d6d94972a5cde5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemoryEffectsBase&lt; LocationEnum &gt;::onlyWritesMemory ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether this function only (at most) writes memory.</p>

<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ae2b19bc21d3201e045841292463888ba">llvm::SITargetLowering::getTgtMemIntrinsic</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#aca77ab9c9b9577f6ae3d1a08d6499738">llvm::CallBase::onlyWritesMemory</a>.</p>

</div>
</div>

### toIntValue() {#ac96f712f6d153d48c535886b4f8aef99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MemoryEffectsBase&lt; LocationEnum &gt;::toIntValue ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> into an encoded integer value (used by memory attribute).</p>

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a6ac29dd4821e6321d0987b951582a85d">llvm::AttrBuilder::addMemoryAttr</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#adaf42001b3cc4c8c631902cbb48106d5">llvm::Attribute::getWithMemoryEffects</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### setModRef() {#a4fd9abbca99d1a1f6fccc7e10cd0ba76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MemoryEffectsBase&lt; LocationEnum &gt;::setModRef (<a href="#a802b3c8c587d808116e71ca648a3e868">Location</a> Loc, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> MR)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Data {#a0bca4cbd9c0dadcc80f75e22186c5778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MemoryEffectsBase&lt; LocationEnum &gt;::Data = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### argMemOnly() {#a5288b2ba178703d9e1f24a5d3708f594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffectsBase llvm::MemoryEffectsBase&lt; LocationEnum &gt;::argMemOnly (<a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> MR=<a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea6524b183b5cd0850f2cff6d30d581af9">ModRefInfo::ModRef</a>)</td>
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

<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> that can only access argument memory.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

### createFromIntValue() {#a93c6a6bc46c56b292db3ba60e92341a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffectsBase llvm::MemoryEffectsBase&lt; LocationEnum &gt;::createFromIntValue (uint32_t Data)</td>
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

<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> from an encoded integer value (used by memory attribute).</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

### inaccessibleMemOnly() {#a5cba4a49c183c6c2f6168be64f04a7b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffectsBase llvm::MemoryEffectsBase&lt; LocationEnum &gt;::inaccessibleMemOnly (<a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> MR=<a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea6524b183b5cd0850f2cff6d30d581af9">ModRefInfo::ModRef</a>)</td>
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

<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> that can only access inaccessible memory.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

### inaccessibleOrArgMemOnly() {#ad341f584befc40ff0aefca99682baf7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffectsBase llvm::MemoryEffectsBase&lt; LocationEnum &gt;::inaccessibleOrArgMemOnly (<a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> MR=<a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea6524b183b5cd0850f2cff6d30d581af9">ModRefInfo::ModRef</a>)</td>
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

<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> that can only access inaccessible or argument memory.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

### locations() {#abfc43f0b4a68c9701a315cae51761f66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto llvm::MemoryEffectsBase&lt; LocationEnum &gt;::locations ()</td>
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

<p>Returns iterator over all supported location kinds.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>


<p>Referenced by <a href="#a7b1f988b33c9acdb6743a05cf97f61b5">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::getModRef</a> and <a href="#a58c45934536d15a5b43f3b3df864958a">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::MemoryEffectsBase</a>.</p>

</div>
</div>

### none() {#af04065f3c729719471689b08089942f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffectsBase llvm::MemoryEffectsBase&lt; LocationEnum &gt;::none ()</td>
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

<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> that cannot read or write any memory.</p>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>


<p>Referenced by <a href="#ad341f584befc40ff0aefca99682baf7c">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::inaccessibleOrArgMemOnly</a>.</p>

</div>
</div>

### readOnly() {#a0dc1a3456bce25673dff8dce6f240a8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffectsBase llvm::MemoryEffectsBase&lt; LocationEnum &gt;::readOnly ()</td>
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

<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> that can read any memory.</p>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

### unknown() {#aff771abf487136aeebb6862871d5e715}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffectsBase llvm::MemoryEffectsBase&lt; LocationEnum &gt;::unknown ()</td>
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

<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> that can read and write any memory.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

### writeOnly() {#a9e3dc568b5f51e03441c9c44b618f337}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffectsBase llvm::MemoryEffectsBase&lt; LocationEnum &gt;::writeOnly ()</td>
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

<p>Create <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase">MemoryEffectsBase</a> that can write any memory.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getLocationPos() {#a606cf244f47a20896b8728131fc999c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MemoryEffectsBase&lt; LocationEnum &gt;::getLocationPos (<a href="#a802b3c8c587d808116e71ca648a3e868">Location</a> Loc)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### BitsPerLoc {#ac3e6e18e6224f0a3ac273f470867fcd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MemoryEffectsBase&lt; LocationEnum &gt;::BitsPerLoc = 2</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

### LocMask {#a6f1e4c10696d1cba1938ef73c182b1f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename LocationEnum&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MemoryEffectsBase&lt; LocationEnum &gt;::LocMask = (1 &lt;&lt; BitsPerLoc) - 1</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">ModRef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
