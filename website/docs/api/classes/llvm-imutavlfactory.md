---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/imutavlfactory
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ImutAVLFactory` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename ImutInfo&gt;
class llvm::ImutAVLFactory&lt;ImutInfo&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">llvm/ADT/ImmutableSet.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a00f7052473a37687f1242aa2fa5a51df">TreeTy</a> = <a href="/web-llvm/docs/api/classes/llvm/imutavltree">ImutAVLTree</a>&lt; ImutInfo &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8108f24f773a2501a1d2fa08711e030f">value_type_ref</a> = typename <a href="/web-llvm/docs/api/classes/llvm/imutavltree/#a962ba280d5ba066ec28da4f9bec7d4a5">TreeTy::value_type_ref</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a192b14d9ec98bc33cb099f7969283beb">key_type_ref</a> = typename <a href="/web-llvm/docs/api/classes/llvm/imutavltree/#a6935ff824f14808b8f11b09c18beaf78">TreeTy::key_type_ref</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4858365953e7cc5079cbf655c1778a8b">CacheTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adfcd91046ec4afdfdcde35ae97617b7a">ImutAVLTree&lt; ImutInfo &gt;</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a60faad75dae080f5619b1544a8a026af">ImutAVLFactory</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a31e11a2072e6b73db4b640b5956e9d52">ImutAVLFactory</a> (BumpPtrAllocator &amp;Alloc)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#adc24f478e08602aa51d9aed91b891d6d">~ImutAVLFactory</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7be3ab461a4f8f8b04a4c9267cea1349">add</a> (TreeTy *T, value_type_ref V)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad0c106945ef04bd818492e04ffa3f850">remove</a> (TreeTy *T, key_type_ref V)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a89243b9731fcb1175dcf09270300bf74">getEmptyTree</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7ac91b62daf64d3c1f1e7c9f35e55725">getCanonicalTree</a> (TreeTy *TNew)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae1a5fd79350e7deafedd6192d28406c9">isEmpty</a> (TreeTy *T) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2784db09a96b5b619c55371faff83c0e">getHeight</a> (TreeTy *T) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a59ee8859b5322d72d90ad2eec2312be4">getLeft</a> (TreeTy *T) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a819d26308a92b907c2f4efe61ddf46bf">getRight</a> (TreeTy *T) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">value_type_ref</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4a99cc36161972c49747d3a07e2c9462">getValue</a> (TreeTy *T) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acdabc3ea76c4f1b10ce30188f0022160">incrementHeight</a> (TreeTy *L, TreeTy *R) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac11252c84426b529419d39bf63bded74">createNode</a> (TreeTy *L, value_type_ref V, TreeTy *R)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9fddf13893d9989b44e15559316381a1">createNode</a> (TreeTy *newLeft, TreeTy *oldTree, TreeTy *newRight)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ade6cf254863ac87b2447630781be56a9">recoverNodes</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2296fc99c051efeb26c611fd0c0f89b4">balanceTree</a> (TreeTy *L, value_type_ref V, TreeTy *R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>balanceTree - Used by add_internal and remove_internal to balance a newly created tree. <a href="#a2296fc99c051efeb26c611fd0c0f89b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a38b7292e32da286807e933d6d8b43c83">add_internal</a> (value_type_ref V, TreeTy *T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>add_internal - Creates a new tree that includes the specified data and the data from the original tree. <a href="#a38b7292e32da286807e933d6d8b43c83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abf415f2f74e9e8b5f97173c200203293">remove_internal</a> (key_type_ref K, TreeTy *T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>remove_internal - Creates a new tree that includes all the data from the original tree except the specified data. <a href="#abf415f2f74e9e8b5f97173c200203293">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa3a1b7e3b1ee1f03f124559ccad5f76f">combineTrees</a> (TreeTy *L, TreeTy *R)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8b58457e9494f6a4fd104ec588a3ad9f">removeMinBinding</a> (TreeTy *T, TreeTy *&amp;Noderemoved)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae16f801c7e64e4557295f1c02623a15e">markImmutable</a> (TreeTy *T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>markImmutable - Clears the mutable bits of a root and all of its descendants. <a href="#ae16f801c7e64e4557295f1c02623a15e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad8135d69758f1f32e7ce5d540c2572d0">ownsAllocator</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaa4fcd5f8346955553bb8363263ef51d">getAllocator</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">CacheTy</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a81afe809ea48cda2e0a65504d47f1ba1">Cache</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uintptr_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7136950be5fc7c17311b13f2e225e9b8">Allocator</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab6f04e579c77d919c3696090ba16c355">createdNodes</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a694a30e0076668bc0666b9f9ca7b6732">freeNodes</a></td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a14372ae02621f4b7d2d0e44f91fc6766">maskCacheIndex</a> (unsigned I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a521d15ab1c2b3a5e89bcccdc54427520">compareTreeWithSection</a> (TreeTy *T, typename TreeTy::iterator &amp;TI, typename TreeTy::iterator &amp;TE)</td>
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


<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### CacheTy {#a4858365953e7cc5079cbf655c1778a8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImutAVLFactory&lt; ImutInfo &gt;::CacheTy =  DenseMap&lt;unsigned, TreeTy*&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### key\_type\_ref {#a192b14d9ec98bc33cb099f7969283beb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImutAVLFactory&lt; ImutInfo &gt;::key_type_ref =  typename TreeTy::key_type_ref</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### TreeTy {#a00f7052473a37687f1242aa2fa5a51df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImutAVLFactory&lt; ImutInfo &gt;::TreeTy =  ImutAVLTree&lt;ImutInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### value\_type\_ref {#a8108f24f773a2501a1d2fa08711e030f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImutAVLFactory&lt; ImutInfo &gt;::value_type_ref =  typename TreeTy::value_type_ref</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### ImutAVLTree&lt; ImutInfo &gt; {#adfcd91046ec4afdfdcde35ae97617b7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/imutavltree">ImutAVLTree</a>&lt; ImutInfo &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/imutavltree/#ace77835f84c5bed9111f65102c9ff04f">llvm::ImutAVLTree&lt; ImutInfo &gt;::release</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ImutAVLFactory() {#a60faad75dae080f5619b1544a8a026af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImutAVLFactory&lt; ImutInfo &gt;::ImutAVLFactory ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### ImutAVLFactory() {#a31e11a2072e6b73db4b640b5956e9d52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImutAVLFactory&lt; ImutInfo &gt;::ImutAVLFactory (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Alloc)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1aea571dc00aef155a16d4e7e1861e1682">llvm::Alloc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ImutAVLFactory() {#adc24f478e08602aa51d9aed91b891d6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImutAVLFactory&lt; ImutInfo &gt;::~ImutAVLFactory ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a7be3ab461a4f8f8b04a4c9267cea1349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy * llvm::ImutAVLFactory&lt; ImutInfo &gt;::add (<a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * T, value_type_ref V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="#a38b7292e32da286807e933d6d8b43c83">llvm::ImutAVLFactory&lt; ImutInfo &gt;::add_internal</a>, <a href="#ae16f801c7e64e4557295f1c02623a15e">llvm::ImutAVLFactory&lt; ImutInfo &gt;::markImmutable</a>, <a href="#ade6cf254863ac87b2447630781be56a9">llvm::ImutAVLFactory&lt; ImutInfo &gt;::recoverNodes</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### getCanonicalTree() {#a7ac91b62daf64d3c1f1e7c9f35e55725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy * llvm::ImutAVLFactory&lt; ImutInfo &gt;::getCanonicalTree (<a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * TNew)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="#a521d15ab1c2b3a5e89bcccdc54427520">llvm::ImutAVLFactory&lt; ImutInfo &gt;::compareTreeWithSection</a>, <a href="/web-llvm/docs/api/classes/llvm/imutavltree/#a167f747ec79ce41b2121359192284ecd">llvm::ImutAVLTree&lt; ImutInfo &gt;::destroy</a>, <a href="#a14372ae02621f4b7d2d0e44f91fc6766">llvm::ImutAVLFactory&lt; ImutInfo &gt;::maskCacheIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### getEmptyTree() {#a89243b9731fcb1175dcf09270300bf74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy * llvm::ImutAVLFactory&lt; ImutInfo &gt;::getEmptyTree ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### remove() {#ad0c106945ef04bd818492e04ffa3f850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy * llvm::ImutAVLFactory&lt; ImutInfo &gt;::remove (<a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * T, key_type_ref V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="#ae16f801c7e64e4557295f1c02623a15e">llvm::ImutAVLFactory&lt; ImutInfo &gt;::markImmutable</a>, <a href="#ade6cf254863ac87b2447630781be56a9">llvm::ImutAVLFactory&lt; ImutInfo &gt;::recoverNodes</a>, <a href="#abf415f2f74e9e8b5f97173c200203293">llvm::ImutAVLFactory&lt; ImutInfo &gt;::remove_internal</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### add\_internal() {#a38b7292e32da286807e933d6d8b43c83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy * llvm::ImutAVLFactory&lt; ImutInfo &gt;::add_internal (value_type_ref V, <a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * T)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>add_internal - Creates a new tree that includes the specified data and the data from the original tree.</p>


<p>If the original tree already contained the data item, the original tree is returned.</p>


<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="#a38b7292e32da286807e933d6d8b43c83">llvm::ImutAVLFactory&lt; ImutInfo &gt;::add_internal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2296fc99c051efeb26c611fd0c0f89b4">llvm::ImutAVLFactory&lt; ImutInfo &gt;::balanceTree</a>, <a href="#ac11252c84426b529419d39bf63bded74">llvm::ImutAVLFactory&lt; ImutInfo &gt;::createNode</a>, <a href="#a59ee8859b5322d72d90ad2eec2312be4">llvm::ImutAVLFactory&lt; ImutInfo &gt;::getLeft</a>, <a href="#a819d26308a92b907c2f4efe61ddf46bf">llvm::ImutAVLFactory&lt; ImutInfo &gt;::getRight</a>, <a href="#a4a99cc36161972c49747d3a07e2c9462">llvm::ImutAVLFactory&lt; ImutInfo &gt;::getValue</a>, <a href="#ae1a5fd79350e7deafedd6192d28406c9">llvm::ImutAVLFactory&lt; ImutInfo &gt;::isEmpty</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a7be3ab461a4f8f8b04a4c9267cea1349">llvm::ImutAVLFactory&lt; ImutInfo &gt;::add</a> and <a href="#a38b7292e32da286807e933d6d8b43c83">llvm::ImutAVLFactory&lt; ImutInfo &gt;::add_internal</a>.</p>

</div>
</div>

### balanceTree() {#a2296fc99c051efeb26c611fd0c0f89b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy * llvm::ImutAVLFactory&lt; ImutInfo &gt;::balanceTree (<a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * L, value_type_ref V, <a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>balanceTree - Used by add_internal and remove_internal to balance a newly created tree.</p>

<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac11252c84426b529419d39bf63bded74">llvm::ImutAVLFactory&lt; ImutInfo &gt;::createNode</a>, <a href="#a2784db09a96b5b619c55371faff83c0e">llvm::ImutAVLFactory&lt; ImutInfo &gt;::getHeight</a>, <a href="#a59ee8859b5322d72d90ad2eec2312be4">llvm::ImutAVLFactory&lt; ImutInfo &gt;::getLeft</a>, <a href="#a819d26308a92b907c2f4efe61ddf46bf">llvm::ImutAVLFactory&lt; ImutInfo &gt;::getRight</a> and <a href="#ae1a5fd79350e7deafedd6192d28406c9">llvm::ImutAVLFactory&lt; ImutInfo &gt;::isEmpty</a>.</p>


<p>Referenced by <a href="#a38b7292e32da286807e933d6d8b43c83">llvm::ImutAVLFactory&lt; ImutInfo &gt;::add_internal</a>, <a href="#aa3a1b7e3b1ee1f03f124559ccad5f76f">llvm::ImutAVLFactory&lt; ImutInfo &gt;::combineTrees</a>, <a href="#abf415f2f74e9e8b5f97173c200203293">llvm::ImutAVLFactory&lt; ImutInfo &gt;::remove_internal</a> and <a href="#a8b58457e9494f6a4fd104ec588a3ad9f">llvm::ImutAVLFactory&lt; ImutInfo &gt;::removeMinBinding</a>.</p>

</div>
</div>

### combineTrees() {#aa3a1b7e3b1ee1f03f124559ccad5f76f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy * llvm::ImutAVLFactory&lt; ImutInfo &gt;::combineTrees (<a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * L, <a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="#a2296fc99c051efeb26c611fd0c0f89b4">llvm::ImutAVLFactory&lt; ImutInfo &gt;::balanceTree</a>, <a href="#a4a99cc36161972c49747d3a07e2c9462">llvm::ImutAVLFactory&lt; ImutInfo &gt;::getValue</a>, <a href="#ae1a5fd79350e7deafedd6192d28406c9">llvm::ImutAVLFactory&lt; ImutInfo &gt;::isEmpty</a> and <a href="#a8b58457e9494f6a4fd104ec588a3ad9f">llvm::ImutAVLFactory&lt; ImutInfo &gt;::removeMinBinding</a>.</p>


<p>Referenced by <a href="#abf415f2f74e9e8b5f97173c200203293">llvm::ImutAVLFactory&lt; ImutInfo &gt;::remove_internal</a>.</p>

</div>
</div>

### createNode() {#ac11252c84426b529419d39bf63bded74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy * llvm::ImutAVLFactory&lt; ImutInfo &gt;::createNode (<a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * L, value_type_ref V, <a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#acdabc3ea76c4f1b10ce30188f0022160">llvm::ImutAVLFactory&lt; ImutInfo &gt;::incrementHeight</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a38b7292e32da286807e933d6d8b43c83">llvm::ImutAVLFactory&lt; ImutInfo &gt;::add_internal</a>, <a href="#a2296fc99c051efeb26c611fd0c0f89b4">llvm::ImutAVLFactory&lt; ImutInfo &gt;::balanceTree</a> and <a href="#a9fddf13893d9989b44e15559316381a1">llvm::ImutAVLFactory&lt; ImutInfo &gt;::createNode</a>.</p>

</div>
</div>

### createNode() {#a9fddf13893d9989b44e15559316381a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy * llvm::ImutAVLFactory&lt; ImutInfo &gt;::createNode (<a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * newLeft, <a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * oldTree, <a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * newRight)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="#ac11252c84426b529419d39bf63bded74">llvm::ImutAVLFactory&lt; ImutInfo &gt;::createNode</a> and <a href="#a4a99cc36161972c49747d3a07e2c9462">llvm::ImutAVLFactory&lt; ImutInfo &gt;::getValue</a>.</p>

</div>
</div>

### getHeight() {#a2784db09a96b5b619c55371faff83c0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ImutAVLFactory&lt; ImutInfo &gt;::getHeight (<a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * T)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a2296fc99c051efeb26c611fd0c0f89b4">llvm::ImutAVLFactory&lt; ImutInfo &gt;::balanceTree</a> and <a href="#acdabc3ea76c4f1b10ce30188f0022160">llvm::ImutAVLFactory&lt; ImutInfo &gt;::incrementHeight</a>.</p>

</div>
</div>

### getLeft() {#a59ee8859b5322d72d90ad2eec2312be4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy * llvm::ImutAVLFactory&lt; ImutInfo &gt;::getLeft (<a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * T)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a38b7292e32da286807e933d6d8b43c83">llvm::ImutAVLFactory&lt; ImutInfo &gt;::add_internal</a>, <a href="#a2296fc99c051efeb26c611fd0c0f89b4">llvm::ImutAVLFactory&lt; ImutInfo &gt;::balanceTree</a>, <a href="#ae16f801c7e64e4557295f1c02623a15e">llvm::ImutAVLFactory&lt; ImutInfo &gt;::markImmutable</a>, <a href="#abf415f2f74e9e8b5f97173c200203293">llvm::ImutAVLFactory&lt; ImutInfo &gt;::remove_internal</a> and <a href="#a8b58457e9494f6a4fd104ec588a3ad9f">llvm::ImutAVLFactory&lt; ImutInfo &gt;::removeMinBinding</a>.</p>

</div>
</div>

### getRight() {#a819d26308a92b907c2f4efe61ddf46bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy * llvm::ImutAVLFactory&lt; ImutInfo &gt;::getRight (<a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * T)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a38b7292e32da286807e933d6d8b43c83">llvm::ImutAVLFactory&lt; ImutInfo &gt;::add_internal</a>, <a href="#a2296fc99c051efeb26c611fd0c0f89b4">llvm::ImutAVLFactory&lt; ImutInfo &gt;::balanceTree</a>, <a href="#ae16f801c7e64e4557295f1c02623a15e">llvm::ImutAVLFactory&lt; ImutInfo &gt;::markImmutable</a>, <a href="#abf415f2f74e9e8b5f97173c200203293">llvm::ImutAVLFactory&lt; ImutInfo &gt;::remove_internal</a> and <a href="#a8b58457e9494f6a4fd104ec588a3ad9f">llvm::ImutAVLFactory&lt; ImutInfo &gt;::removeMinBinding</a>.</p>

</div>
</div>

### getValue() {#a4a99cc36161972c49747d3a07e2c9462}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">value_type_ref llvm::ImutAVLFactory&lt; ImutInfo &gt;::getValue (<a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * T)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a38b7292e32da286807e933d6d8b43c83">llvm::ImutAVLFactory&lt; ImutInfo &gt;::add_internal</a>, <a href="#aa3a1b7e3b1ee1f03f124559ccad5f76f">llvm::ImutAVLFactory&lt; ImutInfo &gt;::combineTrees</a>, <a href="#a9fddf13893d9989b44e15559316381a1">llvm::ImutAVLFactory&lt; ImutInfo &gt;::createNode</a>, <a href="#abf415f2f74e9e8b5f97173c200203293">llvm::ImutAVLFactory&lt; ImutInfo &gt;::remove_internal</a> and <a href="#a8b58457e9494f6a4fd104ec588a3ad9f">llvm::ImutAVLFactory&lt; ImutInfo &gt;::removeMinBinding</a>.</p>

</div>
</div>

### incrementHeight() {#acdabc3ea76c4f1b10ce30188f0022160}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ImutAVLFactory&lt; ImutInfo &gt;::incrementHeight (<a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * L, <a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="#a2784db09a96b5b619c55371faff83c0e">llvm::ImutAVLFactory&lt; ImutInfo &gt;::getHeight</a>.</p>


<p>Referenced by <a href="#ac11252c84426b529419d39bf63bded74">llvm::ImutAVLFactory&lt; ImutInfo &gt;::createNode</a>.</p>

</div>
</div>

### isEmpty() {#ae1a5fd79350e7deafedd6192d28406c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImutAVLFactory&lt; ImutInfo &gt;::isEmpty (<a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * T)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a38b7292e32da286807e933d6d8b43c83">llvm::ImutAVLFactory&lt; ImutInfo &gt;::add_internal</a>, <a href="#a2296fc99c051efeb26c611fd0c0f89b4">llvm::ImutAVLFactory&lt; ImutInfo &gt;::balanceTree</a>, <a href="#aa3a1b7e3b1ee1f03f124559ccad5f76f">llvm::ImutAVLFactory&lt; ImutInfo &gt;::combineTrees</a>, <a href="#abf415f2f74e9e8b5f97173c200203293">llvm::ImutAVLFactory&lt; ImutInfo &gt;::remove_internal</a> and <a href="#a8b58457e9494f6a4fd104ec588a3ad9f">llvm::ImutAVLFactory&lt; ImutInfo &gt;::removeMinBinding</a>.</p>

</div>
</div>

### markImmutable() {#ae16f801c7e64e4557295f1c02623a15e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ImutAVLFactory&lt; ImutInfo &gt;::markImmutable (<a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * T)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>markImmutable - Clears the mutable bits of a root and all of its descendants.</p>

<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="#a59ee8859b5322d72d90ad2eec2312be4">llvm::ImutAVLFactory&lt; ImutInfo &gt;::getLeft</a>, <a href="#a819d26308a92b907c2f4efe61ddf46bf">llvm::ImutAVLFactory&lt; ImutInfo &gt;::getRight</a>, <a href="#ae16f801c7e64e4557295f1c02623a15e">llvm::ImutAVLFactory&lt; ImutInfo &gt;::markImmutable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a7be3ab461a4f8f8b04a4c9267cea1349">llvm::ImutAVLFactory&lt; ImutInfo &gt;::add</a>, <a href="#ae16f801c7e64e4557295f1c02623a15e">llvm::ImutAVLFactory&lt; ImutInfo &gt;::markImmutable</a> and <a href="#ad0c106945ef04bd818492e04ffa3f850">llvm::ImutAVLFactory&lt; ImutInfo &gt;::remove</a>.</p>

</div>
</div>

### recoverNodes() {#ade6cf254863ac87b2447630781be56a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ImutAVLFactory&lt; ImutInfo &gt;::recoverNodes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a7be3ab461a4f8f8b04a4c9267cea1349">llvm::ImutAVLFactory&lt; ImutInfo &gt;::add</a> and <a href="#ad0c106945ef04bd818492e04ffa3f850">llvm::ImutAVLFactory&lt; ImutInfo &gt;::remove</a>.</p>

</div>
</div>

### remove\_internal() {#abf415f2f74e9e8b5f97173c200203293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy * llvm::ImutAVLFactory&lt; ImutInfo &gt;::remove_internal (key_type_ref K, <a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * T)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>remove_internal - Creates a new tree that includes all the data from the original tree except the specified data.</p>


<p>If the specified data did not exist in the original tree, the original tree is returned.</p>


<p>Definition at line 550 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2296fc99c051efeb26c611fd0c0f89b4">llvm::ImutAVLFactory&lt; ImutInfo &gt;::balanceTree</a>, <a href="#aa3a1b7e3b1ee1f03f124559ccad5f76f">llvm::ImutAVLFactory&lt; ImutInfo &gt;::combineTrees</a>, <a href="#a59ee8859b5322d72d90ad2eec2312be4">llvm::ImutAVLFactory&lt; ImutInfo &gt;::getLeft</a>, <a href="#a819d26308a92b907c2f4efe61ddf46bf">llvm::ImutAVLFactory&lt; ImutInfo &gt;::getRight</a>, <a href="#a4a99cc36161972c49747d3a07e2c9462">llvm::ImutAVLFactory&lt; ImutInfo &gt;::getValue</a>, <a href="#ae1a5fd79350e7deafedd6192d28406c9">llvm::ImutAVLFactory&lt; ImutInfo &gt;::isEmpty</a>, <a href="#abf415f2f74e9e8b5f97173c200203293">llvm::ImutAVLFactory&lt; ImutInfo &gt;::remove_internal</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#ad0c106945ef04bd818492e04ffa3f850">llvm::ImutAVLFactory&lt; ImutInfo &gt;::remove</a> and <a href="#abf415f2f74e9e8b5f97173c200203293">llvm::ImutAVLFactory&lt; ImutInfo &gt;::remove_internal</a>.</p>

</div>
</div>

### removeMinBinding() {#a8b58457e9494f6a4fd104ec588a3ad9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy * llvm::ImutAVLFactory&lt; ImutInfo &gt;::removeMinBinding (<a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * T, <a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> *&amp; Noderemoved)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2296fc99c051efeb26c611fd0c0f89b4">llvm::ImutAVLFactory&lt; ImutInfo &gt;::balanceTree</a>, <a href="#a59ee8859b5322d72d90ad2eec2312be4">llvm::ImutAVLFactory&lt; ImutInfo &gt;::getLeft</a>, <a href="#a819d26308a92b907c2f4efe61ddf46bf">llvm::ImutAVLFactory&lt; ImutInfo &gt;::getRight</a>, <a href="#a4a99cc36161972c49747d3a07e2c9462">llvm::ImutAVLFactory&lt; ImutInfo &gt;::getValue</a>, <a href="#ae1a5fd79350e7deafedd6192d28406c9">llvm::ImutAVLFactory&lt; ImutInfo &gt;::isEmpty</a>, <a href="#a8b58457e9494f6a4fd104ec588a3ad9f">llvm::ImutAVLFactory&lt; ImutInfo &gt;::removeMinBinding</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#aa3a1b7e3b1ee1f03f124559ccad5f76f">llvm::ImutAVLFactory&lt; ImutInfo &gt;::combineTrees</a> and <a href="#a8b58457e9494f6a4fd104ec588a3ad9f">llvm::ImutAVLFactory&lt; ImutInfo &gt;::removeMinBinding</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getAllocator() {#aaa4fcd5f8346955553bb8363263ef51d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator &amp; llvm::ImutAVLFactory&lt; ImutInfo &gt;::getAllocator ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### ownsAllocator() {#ad8135d69758f1f32e7ce5d540c2572d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImutAVLFactory&lt; ImutInfo &gt;::ownsAllocator ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allocator {#a7136950be5fc7c17311b13f2e225e9b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uintptr_t llvm::ImutAVLFactory&lt; ImutInfo &gt;::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### Cache {#a81afe809ea48cda2e0a65504d47f1ba1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CacheTy llvm::ImutAVLFactory&lt; ImutInfo &gt;::Cache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### createdNodes {#ab6f04e579c77d919c3696090ba16c355}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;TreeTy*&gt; llvm::ImutAVLFactory&lt; ImutInfo &gt;::createdNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### freeNodes {#a694a30e0076668bc0666b9f9ca7b6732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;TreeTy*&gt; llvm::ImutAVLFactory&lt; ImutInfo &gt;::freeNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### compareTreeWithSection() {#a521d15ab1c2b3a5e89bcccdc54427520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImutAVLFactory&lt; ImutInfo &gt;::compareTreeWithSection (<a href="/web-llvm/docs/api/classes/llvm/imutavltree">TreeTy</a> * T, typename <a href="/web-llvm/docs/api/classes/llvm/imutavltree/#ab8b37da49da9ca4ae345d5acba130df9">TreeTy::iterator</a> &amp; TI, typename <a href="/web-llvm/docs/api/classes/llvm/imutavltree/#ab8b37da49da9ca4ae345d5acba130df9">TreeTy::iterator</a> &amp; TE)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a7ac91b62daf64d3c1f1e7c9f35e55725">llvm::ImutAVLFactory&lt; ImutInfo &gt;::getCanonicalTree</a>.</p>

</div>
</div>

### maskCacheIndex() {#a14372ae02621f4b7d2d0e44f91fc6766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ImutAVLFactory&lt; ImutInfo &gt;::maskCacheIndex (unsigned I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a7ac91b62daf64d3c1f1e7c9f35e55725">llvm::ImutAVLFactory&lt; ImutInfo &gt;::getCanonicalTree</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
