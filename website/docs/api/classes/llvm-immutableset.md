---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/immutableset
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ImmutableSet` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;
class llvm::ImmutableSet&lt;ValT, ValInfo&gt; { ... }
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2a389fd4542aa18e9f755fe7cac852b2">value_type</a> = typename ValInfo::value_type</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af9d4d557fa1ad307d13311d54f960392">value_type_ref</a> = typename ValInfo::value_type_ref</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a76b245ae003c408716f8f4d4263d4885">TreeTy</a> = <a href="/web-llvm/docs/api/classes/llvm/imutavltree">ImutAVLTree</a>&lt; ValInfo &gt;</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad9721ad1220856737611cff04f9a36ba">iterator</a> = <a href="/web-llvm/docs/api/structs/llvm/imutavlvalueiterator">ImutAVLValueIterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/immutableset">ImmutableSet</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a328c093d609680cca505905c6d49901a">Factory</a></td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a577937683fc13ab01a50897993da60af">ImmutableSet</a> (TreeTy *R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs a set from a pointer to a tree root. <a href="#a577937683fc13ab01a50897993da60af">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4882bca2e2ae25ebfad6f18b191b5e44">operator==</a> (const ImmutableSet &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a271e769d96e8db238941731cb7f1a632">operator!=</a> (const ImmutableSet &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a974c036cd5a71efbbcfc5be5b9f02cf3">contains</a> (value_type_ref V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the set contains the specified value. <a href="#a974c036cd5a71efbbcfc5be5b9f02cf3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a76b245ae003c408716f8f4d4263d4885">TreeTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac0b84679129186b3b66254b4fe9b20f6">getRoot</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a76b245ae003c408716f8f4d4263d4885">TreeTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a704bee19f2e46ad415120157722354f5">getRootWithoutRetain</a> () const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a51bd5ce41bd5fab9fd1358f0ba5035d3">isEmpty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isEmpty - Return true if the set contains no elements. <a href="#a51bd5ce41bd5fab9fd1358f0ba5035d3">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6c53965a2e1dcdff9b82d7acfa7bd554">isSingleton</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isSingleton - Return true if the set contains exactly one element. <a href="#a6c53965a2e1dcdff9b82d7acfa7bd554">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ad9721ad1220856737611cff04f9a36ba">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab5e29eeb2cb12b2a0117842ce3efdfda">begin</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ad9721ad1220856737611cff04f9a36ba">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4dd5cf3f51a7ba3dee61f8024bfe481d">end</a> () const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab718af213e193504f9e4e3207ab7e1d4">getHeight</a> () const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aae2f63c4639739e91a1a90e7f12ce7a7">Profile</a> (FoldingSetNodeID &amp;ID) const</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8cf82ca6b26ff58796f8009b98f8f3aa">validateTree</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="#a76b245ae003c408716f8f4d4263d4885">TreeTy</a> &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2abfebc231353d0960559f25f9871195">Root</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acae16c981fabd37fa4df79f5cf567896">Profile</a> (FoldingSetNodeID &amp;ID, const ImmutableSet &amp;S)</td>
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


<p>Definition at line 957 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#ad9721ad1220856737611cff04f9a36ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableSet&lt; ValT, ValInfo &gt;::iterator =  ImutAVLValueIterator&lt;ImmutableSet&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1057 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### TreeTy {#a76b245ae003c408716f8f4d4263d4885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableSet&lt; ValT, ValInfo &gt;::TreeTy =  ImutAVLTree&lt;ValInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 961 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### value\_type {#a2a389fd4542aa18e9f755fe7cac852b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableSet&lt; ValT, ValInfo &gt;::value_type =  typename ValInfo::value_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 959 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### value\_type\_ref {#af9d4d557fa1ad307d13311d54f960392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImmutableSet&lt; ValT, ValInfo &gt;::value_type_ref =  typename ValInfo::value_type_ref</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 960 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### Factory {#a328c093d609680cca505905c6d49901a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class Factory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1023 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ImmutableSet() {#a577937683fc13ab01a50897993da60af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::ImmutableSet (<a href="#a76b245ae003c408716f8f4d4263d4885">TreeTy</a> * R)</td>
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

<p>Constructs a set from a pointer to a tree root.</p>


<p>In general one should use a <a href="/web-llvm/docs/api/classes/llvm/immutableset/factory">Factory</a> object to create sets instead of directly invoking the constructor, but there are cases where make this constructor public is useful.</p>


<p>Definition at line 971 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/immutableset/factory/#afbc2f64a137fe78f0be7a6b1254bd42d">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Factory::add</a>, <a href="/web-llvm/docs/api/classes/llvm/immutableset/factory/#ad51e2cd257a3ee2c43a879fc311d621d">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Factory::getEmptySet</a>, <a href="#a271e769d96e8db238941731cb7f1a632">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::operator!=</a>, <a href="#a4882bca2e2ae25ebfad6f18b191b5e44">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::operator==</a>, <a href="#acae16c981fabd37fa4df79f5cf567896">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Profile</a> and <a href="/web-llvm/docs/api/classes/llvm/immutableset/factory/#afb1072e635625a2c8613ddb9610ee41d">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Factory::remove</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a271e769d96e8db238941731cb7f1a632}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImmutableSet&lt; ValT, ValInfo &gt;::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutableset">ImmutableSet</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1034 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="#a577937683fc13ab01a50897993da60af">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::ImmutableSet</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#a4882bca2e2ae25ebfad6f18b191b5e44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImmutableSet&lt; ValT, ValInfo &gt;::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutableset">ImmutableSet</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1030 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>References <a href="#a577937683fc13ab01a50897993da60af">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::ImmutableSet</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#ab5e29eeb2cb12b2a0117842ce3efdfda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::ImmutableSet&lt; ValT, ValInfo &gt;::begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1059 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### contains() {#a974c036cd5a71efbbcfc5be5b9f02cf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImmutableSet&lt; ValT, ValInfo &gt;::contains (<a href="#af9d4d557fa1ad307d13311d54f960392">value_type_ref</a> V)</td>
</tr>
</table>
</td>
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

<p>Definition at line 1026 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### end() {#a4dd5cf3f51a7ba3dee61f8024bfe481d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::ImmutableSet&lt; ValT, ValInfo &gt;::end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1060 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### getHeight() {#ab718af213e193504f9e4e3207ab7e1d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ImmutableSet&lt; ValT, ValInfo &gt;::getHeight ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1066 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Referenced by <a href="#a6c53965a2e1dcdff9b82d7acfa7bd554">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::isSingleton</a>.</p>

</div>
</div>

### getRoot() {#ac0b84679129186b3b66254b4fe9b20f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy * llvm::ImmutableSet&lt; ValT, ValInfo &gt;::getRoot ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1039 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### getRootWithoutRetain() {#a704bee19f2e46ad415120157722354f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeTy * llvm::ImmutableSet&lt; ValT, ValInfo &gt;::getRootWithoutRetain ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1044 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### isEmpty() {#a51bd5ce41bd5fab9fd1358f0ba5035d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImmutableSet&lt; ValT, ValInfo &gt;::isEmpty ()</td>
</tr>
</table>
</td>
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

<p>Definition at line 1047 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### isSingleton() {#a6c53965a2e1dcdff9b82d7acfa7bd554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImmutableSet&lt; ValT, ValInfo &gt;::isSingleton ()</td>
</tr>
</table>
</td>
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


<p>Definition at line 1051 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="#ab718af213e193504f9e4e3207ab7e1d4">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::getHeight</a>.</p>

</div>
</div>

### Profile() {#aae2f63c4639739e91a1a90e7f12ce7a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1072 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="#aae2f63c4639739e91a1a90e7f12ce7a7">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Profile</a>.</p>


<p>Referenced by <a href="#aae2f63c4639739e91a1a90e7f12ce7a7">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Profile</a>.</p>

</div>
</div>

### validateTree() {#a8cf82ca6b26ff58796f8009b98f8f3aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ImmutableSet&lt; ValT, ValInfo &gt;::validateTree ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1078 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Root {#a2abfebc231353d0960559f25f9871195}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrusiveRefCntPtr&lt;TreeTy&gt; llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Root</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 964 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Profile() {#acae16c981fabd37fa4df79f5cf567896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValT, typename ValInfo = ImutContainerInfo&lt;ValT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ImmutableSet&lt; ValT, ValInfo &gt;::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutableset">ImmutableSet</a> &amp; S)</td>
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



<p>Definition at line 1068 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="#a577937683fc13ab01a50897993da60af">llvm::ImmutableSet&lt; ValT, ValInfo &gt;::ImmutableSet</a>.</p>

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
