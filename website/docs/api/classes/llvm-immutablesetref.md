---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/immutablesetref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ImmutableSetRef` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;
class llvm::ImmutableSetRef&lt;ValT, ValInfo&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">llvm/ADT/ImmutableSet.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a93c5660a53191122d6acef3c9b735217">value_type</a> = typename ValInfo::value_type</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aac86e3025e640bbfe126eefa3defaf38">value_type_ref</a> = typename ValInfo::value_type_ref</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a27a3c0cf63600c1bc240136b1c688e98">TreeTy</a> = <a href="/web-llvm/docs/api/classes/llvm/imutavltree">ImutAVLTree</a>&lt; ValInfo &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae589e0adc39a1a99179aed161aa0c9e4">FactoryTy</a> = typename <a href="/web-llvm/docs/api/classes/llvm/imutavltree/#a744e5bd7d0965b1bb1cbc5daa85263d7">TreeTy::Factory</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5d719b398e53d7bd856285adce365e56">iterator</a> = <a href="/web-llvm/docs/api/structs/llvm/imutavlvalueiterator">ImutAVLValueIterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/immutablesetref">ImmutableSetRef</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa37c1e77d43150a76272b1a5739445ae">ImmutableSetRef</a> (TreeTy *R, FactoryTy *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs a set from a pointer to a tree root. <a href="#aa37c1e77d43150a76272b1a5739445ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afcd6b106b1cff3a4a91c99af552f3f5f">operator==</a> (const ImmutableSetRef &amp;RHS) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4e1aafdb322bc9029248fc06701e60a7">operator!=</a> (const ImmutableSetRef &amp;RHS) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablesetref">ImmutableSetRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1bd4881656ae7caa31f306d0b46c48c5">add</a> (value_type_ref V)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablesetref">ImmutableSetRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5033f474ff56ccbc4a0f17dfb95f81be">remove</a> (value_type_ref V)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a454f064227154f2cb9c66f8d2f84fcc7">contains</a> (value_type_ref V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the set contains the specified value. <a href="#a454f064227154f2cb9c66f8d2f84fcc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad644f7e6ebe478b0b32030a8d41cc33f">asImmutableSet</a> (bool canonicalize=true) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/immutableset">ImmutableSet</a>&lt; ValT &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a27a3c0cf63600c1bc240136b1c688e98">TreeTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aff0ee9514e4a82cfb09be8c20c12d3d5">getRootWithoutRetain</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a79cf741db69b2490699b14e7f1f8c5b1">isEmpty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isEmpty - Return true if the set contains no elements. <a href="#a79cf741db69b2490699b14e7f1f8c5b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a716af81d14162874d82f3fd1716c3aa8">isSingleton</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isSingleton - Return true if the set contains exactly one element. <a href="#a716af81d14162874d82f3fd1716c3aa8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a5d719b398e53d7bd856285adce365e56">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7942bae34af832c666137188c11b1738">begin</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a5d719b398e53d7bd856285adce365e56">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab9d1b5689e8dce6b3c0b3f58755c01ac">end</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abd02125a5adf6d2f39750667f400acc7">getHeight</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a13fdcec88f373373ed9fb771fae0e3f5">Profile</a> (FoldingSetNodeID &amp;ID) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af5279836e2a1291d0be53298a2cb7f7c">validateTree</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="#a27a3c0cf63600c1bc240136b1c688e98">TreeTy</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8ecdb21be4aadd19393fd8ab675ab57d">Root</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ae589e0adc39a1a99179aed161aa0c9e4">FactoryTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a602686ff72013666f4580cb7c941b81c">Factory</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/immutablesetref">ImmutableSetRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aee67f770c7e26cc07b0b2578ea085a2a">getEmptySet</a> (FactoryTy *F)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a07ad22f466ef05eaeb48ef0cc705aca8">Profile</a> (FoldingSetNodeID &amp;ID, const ImmutableSetRef &amp;S)</td>
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


<p>Definition at line 1083 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### FactoryTy {#ae589e0adc39a1a99179aed161aa0c9e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::FactoryTy =  typename TreeTy::Factory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1088 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### iterator {#a5d719b398e53d7bd856285adce365e56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::iterator =  ImutAVLValueIterator&lt;ImmutableSetRef&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### TreeTy {#a27a3c0cf63600c1bc240136b1c688e98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::TreeTy =  ImutAVLTree&lt;ValInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1087 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### value\_type {#a93c5660a53191122d6acef3c9b735217}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::value_type =  typename ValInfo::value_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1085 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### value\_type\_ref {#aac86e3025e640bbfe126eefa3defaf38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::value_type_ref =  typename ValInfo::value_type_ref</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1086 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ImmutableSetRef() {#aa37c1e77d43150a76272b1a5739445ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::ImmutableSetRef (<a href="#a27a3c0cf63600c1bc240136b1c688e98">TreeTy</a> * R, <a href="#ae589e0adc39a1a99179aed161aa0c9e4">FactoryTy</a> * F)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constructs a set from a pointer to a tree root.</p>


<p>In general one should use a Factory object to create sets instead of directly invoking the constructor, but there are cases where make this constructor public is useful.</p>


<p>Definition at line 1099 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a1bd4881656ae7caa31f306d0b46c48c5">llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::add</a>, <a href="#aee67f770c7e26cc07b0b2578ea085a2a">llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::getEmptySet</a>, <a href="#a4e1aafdb322bc9029248fc06701e60a7">llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::operator!=</a>, <a href="#afcd6b106b1cff3a4a91c99af552f3f5f">llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::operator==</a>, <a href="#a07ad22f466ef05eaeb48ef0cc705aca8">llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::Profile</a> and <a href="#a5033f474ff56ccbc4a0f17dfb95f81be">llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::remove</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a4e1aafdb322bc9029248fc06701e60a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablesetref">ImmutableSetRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="#aa37c1e77d43150a76272b1a5739445ae">llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::ImmutableSetRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#afcd6b106b1cff3a4a91c99af552f3f5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablesetref">ImmutableSetRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="#aa37c1e77d43150a76272b1a5739445ae">llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::ImmutableSetRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a1bd4881656ae7caa31f306d0b46c48c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmutableSetRef llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::add (<a href="#aac86e3025e640bbfe126eefa3defaf38">value_type_ref</a> V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="#aa37c1e77d43150a76272b1a5739445ae">llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::ImmutableSetRef</a>.</p>

</div>
</div>

### asImmutableSet() {#ad644f7e6ebe478b0b32030a8d41cc33f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmutableSet&lt; ValT &gt; llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::asImmutableSet (bool canonicalize=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### begin() {#a7942bae34af832c666137188c11b1738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### contains() {#a454f064227154f2cb9c66f8d2f84fcc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::contains (<a href="#aac86e3025e640bbfe126eefa3defaf38">value_type_ref</a> V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the set contains the specified value.</p>

<p>Definition at line 1114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### end() {#ab9d1b5689e8dce6b3c0b3f58755c01ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### getHeight() {#abd02125a5adf6d2f39750667f400acc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::getHeight ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Referenced by <a href="#a716af81d14162874d82f3fd1716c3aa8">llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::isSingleton</a>.</p>

</div>
</div>

### getRootWithoutRetain() {#aff0ee9514e4a82cfb09be8c20c12d3d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy * llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::getRootWithoutRetain ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### isEmpty() {#a79cf741db69b2490699b14e7f1f8c5b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::isEmpty ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isEmpty - Return true if the set contains no elements.</p>

<p>Definition at line 1135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### isSingleton() {#a716af81d14162874d82f3fd1716c3aa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::isSingleton ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isSingleton - Return true if the set contains exactly one element.</p>


<p>This method runs in constant time.</p>


<p>Definition at line 1139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="#abd02125a5adf6d2f39750667f400acc7">llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::getHeight</a>.</p>

</div>
</div>

### Profile() {#a13fdcec88f373373ed9fb771fae0e3f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="#a13fdcec88f373373ed9fb771fae0e3f5">llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::Profile</a>.</p>


<p>Referenced by <a href="#a13fdcec88f373373ed9fb771fae0e3f5">llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::Profile</a>.</p>

</div>
</div>

### remove() {#a5033f474ff56ccbc4a0f17dfb95f81be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmutableSetRef llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::remove (<a href="#aac86e3025e640bbfe126eefa3defaf38">value_type_ref</a> V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="#aa37c1e77d43150a76272b1a5739445ae">llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::ImmutableSetRef</a>.</p>

</div>
</div>

### validateTree() {#af5279836e2a1291d0be53298a2cb7f7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::validateTree ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Factory {#a602686ff72013666f4580cb7c941b81c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FactoryTy* llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::Factory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1092 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### Root {#a8ecdb21be4aadd19393fd8ab675ab57d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrusiveRefCntPtr&lt;TreeTy&gt; llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::Root</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1091 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getEmptySet() {#aee67f770c7e26cc07b0b2578ea085a2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImmutableSetRef llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::getEmptySet (<a href="#ae589e0adc39a1a99179aed161aa0c9e4">FactoryTy</a> * F)</td>
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



<p>Definition at line 1101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#aa37c1e77d43150a76272b1a5739445ae">llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::ImmutableSetRef</a>.</p>

</div>
</div>

### Profile() {#a07ad22f466ef05eaeb48ef0cc705aca8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablesetref">ImmutableSetRef</a> &amp; S)</td>
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



<p>Definition at line 1156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="#aa37c1e77d43150a76272b1a5739445ae">llvm::ImmutableSetRef&lt; ValT, ValInfo &gt;::ImmutableSetRef</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
