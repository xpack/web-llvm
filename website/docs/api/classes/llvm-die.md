---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/die
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DIE` Class

<p>A structured debug information entry. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DIE { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">llvm/CodeGen/DIE.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/intrusivebacklistnode">IntrusiveBackListNode</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dievaluelist">DIEValueList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> values. <a href="/web-llvm/docs/api/classes/llvm/dievaluelist/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3af72b2770535fe133ac955a21c0d034">child_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/intrusivebacklist">IntrusiveBackList</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &gt;::iterator</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11f95b415d4d2e5d451b26fcb0817d9a">const_child_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/intrusivebacklist">IntrusiveBackList</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &gt;::const_iterator</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba14bc5583ebeea9f171a2c55b36bd27">child_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a3af72b2770535fe133ac955a21c0d034">child_iterator</a> &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0a9ca5bf2fb0c29e11d64db7076879e">const_child_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a11f95b415d4d2e5d451b26fcb0817d9a">const_child_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a456ecbb0c55f0845b0bd3b5acdeb4e14">IntrusiveBackList&lt; DIE &gt;</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a222e8b29dfdd300df3f06c9ecdd47f81">DIEUnit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa708a4501ac8ca4afb2625745da3bed0">DIE</a> ()=delete</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a472dc32496f7d4e783402ee49cf74134">DIE</a> (const DIE &amp;RHS)=delete</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c734d96ae5a2914daf2cd2d2852f87e">DIE</a> (DIE &amp;&amp;RHS)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a117714ef219ff48367f4c2ecbb8a46f5">DIE</a> (dwarf::Tag Tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ed68ae793abec624d58d5991223edfe">operator=</a> (const DIE &amp;RHS)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefdac98c044cde2a85699a2dfe8c20f4">operator=</a> (const DIE &amp;&amp;RHS)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a191332ee5e954e8a95460cfaa5e88f26">getAbbrevNumber</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeac16c22ec5a0c13658381144c7e3439">getTag</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac44e64e0d814099105dde610b11c9914">getOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the compile/type unit relative offset of this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#ac44e64e0d814099105dde610b11c9914">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a260b23f8c0c3b34a94b27886008630f9">getSize</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac91c79b70f4cc8c8cfe0dff567124ea4">hasChildren</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8f4097aac3899eaf9c6f1ffbaacbf0e">setForceChildren</a> (bool B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aba14bc5583ebeea9f171a2c55b36bd27">child_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95e4509deb2adbc00a3091aab5c36e50">children</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae0a9ca5bf2fb0c29e11d64db7076879e">const_child_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a271bee45c8170f0789b57e0d971b0e7d">children</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af985c8a58986e45114a8c3e6cbf0504a">getParent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dieabbrev">DIEAbbrev</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47e67f02f858b710768cbecf7fd08244">generateAbbrev</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate the abbreviation for this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a47e67f02f858b710768cbecf7fd08244">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1516bd8f1676ec9e541a375a0dea5b1">setAbbrevNumber</a> (unsigned I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the abbreviation number for this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#ab1516bd8f1676ec9e541a375a0dea5b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad17e92ea5b8abfc21028d5ebc6be8c16">getDebugSectionOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the absolute offset within the .debug_info or .debug_types section for this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#ad17e92ea5b8abfc21028d5ebc6be8c16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4db4b8aaa0f0da8dd11c5a279f4cfd6c">computeOffsetsAndAbbrevs</a> (const dwarf::FormParams &amp;FormParams, DIEAbbrevSet &amp;AbbrevSet, unsigned CUOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the offset of this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and all its children. <a href="#a4db4b8aaa0f0da8dd11c5a279f4cfd6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0a7f64f121eaf4d95424a3fbfcc921c">getUnitDie</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Climb up the parent chain to get the compile unit or type unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> that this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> belongs to. <a href="#ab0a7f64f121eaf4d95424a3fbfcc921c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dieunit">DIEUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d981b742b9e50f3499554c31c6aa001">getUnit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Climb up the parent chain to get the compile unit or type unit that this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> belongs to. <a href="#a7d981b742b9e50f3499554c31c6aa001">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5e71a222d770109a27a408f3df9d573">setOffset</a> (unsigned O)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64a6a6e0ea513fadb1e384e8ef04bcca">setSize</a> (unsigned S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bd79b4ce04e1141856b6076717b4615">addChild</a> (DIE *Child)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a child to the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a3bd79b4ce04e1141856b6076717b4615">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d4a5eccaf92037114cb5911b0bb457f">addChildFront</a> (DIE *Child)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dievalue">DIEValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a008bf8f3472eb0014e766bac06fbe537">findAttribute</a> (dwarf::Attribute Attribute) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find a value in the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> with the attribute given. <a href="#a008bf8f3472eb0014e766bac06fbe537">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07a09075f3cc7237c251adf0f4e8ba49">print</a> (raw_ostream &amp;O, unsigned IndentCount=0) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeec7f1000c747324d45318321277b7b9">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c74be0a2f1f685173e09698f86a25cf">Offset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dwarf unit relative offset. <a href="#a1c74be0a2f1f685173e09698f86a25cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9329def93f390c4c2e2e88765cc81be">Size</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size of instance + children. <a href="#af9329def93f390c4c2e2e88765cc81be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a297570118498c03ee8ddfdb92a5d30fe">AbbrevNumber</a> = ~0u</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03619e3b6c7c7e6136adb83d070fde05">Tag</a> = (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a>)0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dwarf tag code. <a href="#a03619e3b6c7c7e6136adb83d070fde05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af71b5ae985607b386621a13ed469153b">ForceChildren</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set to true to force a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> to emit an abbreviation that says it has children even when it doesn't. <a href="#af71b5ae985607b386621a13ed469153b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intrusivebacklist">IntrusiveBackList</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac660ab78edc3ed32a1c687e0213760a0">Children</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Children DIEs. <a href="#ac660ab78edc3ed32a1c687e0213760a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *, <a href="/web-llvm/docs/api/classes/llvm/dieunit">DIEUnit</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f63989aa5de6e7b9bc1f29b8fe7a888">Owner</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The owner is either the parent <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for children of other DIEs, or a <a href="/web-llvm/docs/api/classes/llvm/dieunit">DIEUnit</a> which contains this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> as its unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a9f63989aa5de6e7b9bc1f29b8fe7a888">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75692ef0b9a881db75fc0e0a79db0d1d">get</a> (BumpPtrAllocator &amp;Alloc, dwarf::Tag Tag)</td>
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

<p>A structured debug information entry.</p>


<p>Has an abbreviation which describes its organization.</p>


<p>Definition at line 819 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### child\_iterator {#a3af72b2770535fe133ac955a21c0d034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DIE::child_iterator =  IntrusiveBackList&lt;DIE&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 870 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>

</div>
</div>

### child\_range {#aba14bc5583ebeea9f171a2c55b36bd27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DIE::child_range =  iterator_range&lt;child_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 872 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>

</div>
</div>

### const\_child\_iterator {#a11f95b415d4d2e5d451b26fcb0817d9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DIE::const_child_iterator =  IntrusiveBackList&lt;DIE&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>

</div>
</div>

### const\_child\_range {#ae0a9ca5bf2fb0c29e11d64db7076879e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DIE::const_child_range =  iterator_range&lt;const_child_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 873 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DIEUnit {#a222e8b29dfdd300df3f06c9ecdd47f81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/dieunit">DIEUnit</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>Reference <a href="#a222e8b29dfdd300df3f06c9ecdd47f81">DIEUnit</a>.</p>


<p>Referenced by <a href="#a222e8b29dfdd300df3f06c9ecdd47f81">DIEUnit</a>, <a href="#ad17e92ea5b8abfc21028d5ebc6be8c16">getDebugSectionOffset</a> and <a href="#a7d981b742b9e50f3499554c31c6aa001">getUnit</a>.</p>

</div>
</div>

### IntrusiveBackList&lt; DIE &gt; {#a456ecbb0c55f0845b0bd3b5acdeb4e14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/intrusivebacklist">IntrusiveBackList</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 734 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/iterator-adaptor-base/#a0b53ab0bf798b3740b3d2b0fea0c49ed">llvm::iterator_adaptor_base&lt; const_value_iterator, ListTy::const_iterator, std::forward_iterator_tag, const DIEValue &gt;::wrapped</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DIE() {#aa708a4501ac8ca4afb2625745da3bed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DIE::DIE ()</td>
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



<p>Definition at line 843 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>Referenced by <a href="#a75692ef0b9a881db75fc0e0a79db0d1d">get</a>.</p>

</div>
</div>

### DIE() {#a472dc32496f7d4e783402ee49cf74134}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DIE::DIE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; RHS)</td>
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



<p>Definition at line 844 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### DIE() {#a1c734d96ae5a2914daf2cd2d2852f87e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DIE::DIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp;&amp; RHS)</td>
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



<p>Definition at line 845 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### DIE() {#a117714ef219ff48367f4c2ecbb8a46f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DIE::DIE (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> Tag)</td>
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



<p>Definition at line 840 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a9ed68ae793abec624d58d5991223edfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE &amp; llvm::DIE::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp; RHS)</td>
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



<p>Definition at line 846 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator=() {#aefdac98c044cde2a85699a2dfe8c20f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE &amp; llvm::DIE::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> &amp;&amp; RHS)</td>
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



<p>Definition at line 847 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addChild() {#a3bd79b4ce04e1141856b6076717b4615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE &amp; llvm::DIE::addChild (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * Child)</td>
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

<p>Add a child to the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 934 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#af985c8a58986e45114a8c3e6cbf0504a">getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0284131decd7881e49a1dc2b82e4ac58">llvm::DwarfCompileUnit::constructCallSiteParmEntryDIEs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">llvm::DwarfCompileUnit::constructImportedEntityDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a47e64bee9baa8d3436add9ec49d1c880">llvm::DwarfCompileUnit::constructInlinedScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#acf65d0311d21263e1470c9c5f2ad57d8">llvm::DwarfCompileUnit::constructScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a8cbe3dd2e5c24c363d750bd49f46838a">llvm::DwarfCompileUnit::constructSubprogramScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4053999da10fee3e053346031495319">llvm::DwarfUnit::createAndAddDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aa0d14e865eff41f3f1c6f53e1604e67e">llvm::DwarfCompileUnit::createAndAddScopeChildren</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a1b6f98e91ce662c3a7a89705a00ef67f">llvm::DwarfCompileUnit::getOrCreateImportedEntityDIE</a>.</p>

</div>
</div>

### addChildFront() {#a5d4a5eccaf92037114cb5911b0bb457f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE &amp; llvm::DIE::addChildFront (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * Child)</td>
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



<p>Definition at line 941 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#af985c8a58986e45114a8c3e6cbf0504a">getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a4c89d112b2f04f66826428c19d11301b">llvm::DwarfCompileUnit::createBaseTypeDIEs</a>.</p>

</div>
</div>

### children() {#a95e4509deb2adbc00a3091aab5c36e50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">child_range llvm::DIE::children ()</td>
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



<p>Definition at line 875 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="#a4db4b8aaa0f0da8dd11c5a279f4cfd6c">computeOffsetsAndAbbrevs</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1bcc04bcd84245c861201c01d2cc1a4c">llvm::AsmPrinter::emitDwarfDIE</a> and <a href="#a07a09075f3cc7237c251adf0f4e8ba49">print</a>.</p>

</div>
</div>

### children() {#a271bee45c8170f0789b57e0d971b0e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_child_range llvm::DIE::children ()</td>
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



<p>Definition at line 878 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### computeOffsetsAndAbbrevs() {#a4db4b8aaa0f0da8dd11c5a279f4cfd6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DIE::computeOffsetsAndAbbrevs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">dwarf::FormParams</a> &amp; FormParams, <a href="/web-llvm/docs/api/classes/llvm/dieabbrevset">DIEAbbrevSet</a> &amp; AbbrevSet, unsigned CUOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the offset of this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and all its children.</p>


<p>This function gets called just before we are going to generate the debug information and gives each <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> a chance to figure out its <a href="/web-llvm/docs/api/namespaces/cu">CU</a> relative <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset, unique its abbreviation and fill in the abbreviation code, and return the unit offset that points to where the next <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> will be emitted within the debug unit section. After this function has been called for all <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> objects, the DWARF can be generated since all DIEs will be able to properly refer to other <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> objects since all DIEs have calculated their offsets.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">FormParams</td>
<td class="doxyParamItemDescription"><p>Used when calculating sizes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AbbrevSet</td>
<td class="doxyParamItemDescription"><p>the abbreviation used to unique <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> abbreviations.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CUOffset</td>
<td class="doxyParamItemDescription"><p>the compile/type unit relative offset in bytes.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the offset for the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> that follows this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> within the current compile/type unit.</p></dd>
</dl>


<p>Declaration at line 913 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>, definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/die-cpp">DIE.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a95e4509deb2adbc00a3091aab5c36e50">children</a>, <a href="#a191332ee5e954e8a95460cfaa5e88f26">getAbbrevNumber</a>, <a href="#ac44e64e0d814099105dde610b11c9914">getOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa02a1d8fb0f561ab81f4a2570db7dc28">llvm::getULEB128Size</a>, <a href="#ac91c79b70f4cc8c8cfe0dff567124ea4">hasChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/dieabbrev/#af44687d5face91653e5e63e9343b8d7b">llvm::DIEAbbrev::hasChildren</a>, <a href="#ac5e71a222d770109a27a408f3df9d573">setOffset</a>, <a href="#a64a6a6e0ea513fadb1e384e8ef04bcca">setSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dieabbrevset/#acd0912271cf17bd2b546eec9350021fa">llvm::DIEAbbrevSet::uniqueAbbreviation</a> and <a href="/web-llvm/docs/api/classes/llvm/dievaluelist/#aaac0a2276b1fe9c13ec247892a7c3703">llvm::DIEValueList::values</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarffile/#a12d25783e3fd286b1fea14b6fafbf9f6">llvm::DwarfFile::computeSizeAndOffset</a>.</p>

</div>
</div>

### dump() {#aeec7f1000c747324d45318321277b7b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void DIE::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 955 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>, definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/die-cpp">DIE.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a07a09075f3cc7237c251adf0f4e8ba49">print</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#abab9675572d9fe6ef8cf9674b1bab8f7">llvm::dwarf_linker::parallel::DependencyTracker::isLiveSubprogramEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#ac9a57660f0db8e2b356c3ebccd34b063">llvm::dwarf_linker::parallel::DependencyTracker::isLiveVariableEntry</a>.</p>

</div>
</div>

### findAttribute() {#a008bf8f3472eb0014e766bac06fbe537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIEValue DIE::findAttribute (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attribute)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find a value in the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> with the attribute given.</p>


<p>Returns a default-constructed <a href="/web-llvm/docs/api/classes/llvm/dievalue">DIEValue</a> (where <em><a href="/web-llvm/docs/api/classes/llvm/dievalue/#a2ed338bd1479742d64995ffe21d681bb">DIEValue::getType()</a></em> gives <em><a href="/web-llvm/docs/api/classes/llvm/dievalue/#aa473b7c3718900606e0e4770df7446e1a8a20cff4af569f12d35ad33a015dd939">DIEValue::isNone</a></em>) if no such attribute exists.</p>


<p>Declaration at line 952 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/die-cpp">DIE.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dievaluelist/#aaac0a2276b1fe9c13ec247892a7c3703">llvm::DIEValueList::values</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a4a6055a40e65d2916f98811698ce5b4f">computeIndexValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3f002d26ef8a98b14c82c510d49e26b2">llvm::DwarfCompileUnit::constructCallSiteEntryDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltabledata/#aa762f32385fad86a276bd941c5844a96">llvm::DWARF5AccelTableData::getDefiningParentDieOffset</a>.</p>

</div>
</div>

### generateAbbrev() {#a47e67f02f858b710768cbecf7fd08244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIEAbbrev DIE::generateAbbrev ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate the abbreviation for this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>


<p>Calculate the abbreviation for this, which should be uniqued and eventually used to call <em><a href="#ab1516bd8f1676ec9e541a375a0dea5b1">setAbbrevNumber()</a></em>.</p>


<p>Declaration at line 888 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/die-cpp">DIE.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dieabbrev/#a6d72a63ac1bc9b87b6866afa8bdc05a5">llvm::DIEAbbrev::AddAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dieabbrev/#a0eaf3cdeee5108ca35546d43255ecb74">llvm::DIEAbbrev::AddImplicitConstAttribute</a>, <a href="#ac91c79b70f4cc8c8cfe0dff567124ea4">hasChildren</a> and <a href="/web-llvm/docs/api/classes/llvm/dievaluelist/#aaac0a2276b1fe9c13ec247892a7c3703">llvm::DIEValueList::values</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dieabbrevset/#acd0912271cf17bd2b546eec9350021fa">llvm::DIEAbbrevSet::uniqueAbbreviation</a>.</p>

</div>
</div>

### getAbbrevNumber() {#a191332ee5e954e8a95460cfaa5e88f26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DIE::getAbbrevNumber ()</td>
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



<p>Definition at line 854 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>Referenced by <a href="#a4db4b8aaa0f0da8dd11c5a279f4cfd6c">computeOffsetsAndAbbrevs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#aafd0fac7574417fa923ca2bce4b9b85c">llvm::dwarf_linker::parallel::TypeUnit::createDIETree</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1bcc04bcd84245c861201c01d2cc1a4c">llvm::AsmPrinter::emitDwarfDIE</a>.</p>

</div>
</div>

### getDebugSectionOffset() {#ad17e92ea5b8abfc21028d5ebc6be8c16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t DIE::getDebugSectionOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the absolute offset within the .debug_info or .debug_types section for this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Declaration at line 895 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/die-cpp">DIE.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a222e8b29dfdd300df3f06c9ecdd47f81">DIEUnit</a>, <a href="#ac44e64e0d814099105dde610b11c9914">getOffset</a> and <a href="#a7d981b742b9e50f3499554c31c6aa001">getUnit</a>.</p>

</div>
</div>

### getOffset() {#ac44e64e0d814099105dde610b11c9914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DIE::getOffset ()</td>
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

<p>Get the compile/type unit relative offset of this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 857 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a09b5d1027676907c7bc194a865ffe0df">llvm::dwarf_linker::parallel::OutputSections::applyPatches</a>, <a href="#a4db4b8aaa0f0da8dd11c5a279f4cfd6c">computeOffsetsAndAbbrevs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#aafd0fac7574417fa923ca2bce4b9b85c">llvm::dwarf_linker::parallel::TypeUnit::createDIETree</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1bcc04bcd84245c861201c01d2cc1a4c">llvm::AsmPrinter::emitDwarfDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit/#a0af355b794e2a9bcb54dd930f7ad4b54">llvm::dwarf_linker::classic::CompileUnit::fixupForwardReferences</a>, <a href="#ad17e92ea5b8abfc21028d5ebc6be8c16">getDebugSectionOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a811bebdebe4a92be5bab22a83979dff4">llvm::DWARFUnit::getDIEIndexForOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/addressesmap/#af518b8bb3f9740abb54f9aadf86d7344">llvm::dwarf_linker::AddressesMap::getVariableRelocAdjustment</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/acceleratorrecordssaver/#ae49a5ef1608e2df3b53c880ef1543616">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::saveNameRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/acceleratorrecordssaver/#a3fdaa3ade4765ff2fc5c85c753c7a41b">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::saveNamespaceRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/acceleratorrecordssaver/#a4cb4f618e8ceb12af873c37a5d9c554b">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::saveObjCNameRecord</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/acceleratorrecordssaver/#a09878fd3b26b9ee9ab928cd3c1922bfe">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::saveTypeRecord</a>.</p>

</div>
</div>

### getParent() {#af985c8a58986e45114a8c3e6cbf0504a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * DIE::getParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 882 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>, definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/die-cpp">DIE.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a>.</p>


<p>Referenced by <a href="#a3bd79b4ce04e1141856b6076717b4615">addChild</a>, <a href="#a5d4a5eccaf92037114cb5911b0bb457f">addChildFront</a>, <a href="/web-llvm/docs/api/classes/llvm/diehash/#a22e2fce16609b6482e290f3f24172f85">llvm::DIEHash::computeTypeSignature</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf5acceltabledata/#aa762f32385fad86a276bd941c5844a96">llvm::DWARF5AccelTableData::getDefiningParentDieOffset</a>.</p>

</div>
</div>

### getSize() {#a260b23f8c0c3b34a94b27886008630f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DIE::getSize ()</td>
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



<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a3e1d9b11ad28b498cafb76889dc09239">llvm::dwarf_linker::classic::DwarfStreamer::emitDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfemitterimpl/#ac5ac850992c69e76c0e1d40b83d9b0ff">llvm::dwarf_linker::parallel::DwarfEmitterImpl::emitDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1bcc04bcd84245c861201c01d2cc1a4c">llvm::AsmPrinter::emitDwarfDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a68d4481aea40e318a364df01ae10d308">llvm::DwarfCompileUnit::getLength</a>.</p>

</div>
</div>

### getTag() {#aeac16c22ec5a0c13658381144c7e3439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Tag llvm::DIE::getTag ()</td>
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



<p>Definition at line 855 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a4a6055a40e65d2916f98811698ce5b4f">computeIndexValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ade80cb280096b057a649d3570dde295f">llvm::DwarfUnit::constructTypeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1bcc04bcd84245c861201c01d2cc1a4c">llvm::AsmPrinter::emitDwarfDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/declcontexttree/#a4bd9844a95feccd824a78e62c476f423">llvm::dwarf_linker::classic::DeclContextTree::getChildDeclContext</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#ac3b09300d5e9ca1002c2a91191aee71b">llvm::DWARFContext::getDIEsForAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp/#a6f090dc6a03cf0325f76deb6d6eaca41">getNames</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acc3268e4df66097512cb6b4b87b438d4">llvm::DwarfUnit::getOrCreateStaticMemberDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/addressesmap/#af518b8bb3f9740abb54f9aadf86d7344">llvm::dwarf_linker::AddressesMap::getVariableRelocAdjustment</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#abab9675572d9fe6ef8cf9674b1bab8f7">llvm::dwarf_linker::parallel::DependencyTracker::isLiveSubprogramEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit/#ae37905defe9c94924f281526d50be047">llvm::dwarf_linker::classic::CompileUnit::markEverythingAsKept</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit/#a87ab998fa372edd70feb6fea541b02c3">llvm::dwarf_linker::classic::CompileUnit::noteRangeAttribute</a> and <a href="#a07a09075f3cc7237c251adf0f4e8ba49">print</a>.</p>

</div>
</div>

### getUnit() {#a7d981b742b9e50f3499554c31c6aa001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIEUnit * DIE::getUnit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Climb up the parent chain to get the compile unit or type unit that this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> belongs to.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the <a href="/web-llvm/docs/api/classes/llvm/dieunit">DIEUnit</a> that represents the compile or type unit that owns this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>, or NULL if this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> hasn't been added to a unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p></dd>
</dl>


<p>Declaration at line 928 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>, definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/die-cpp">DIE.cpp</a>.</p>


<p>References <a href="#a222e8b29dfdd300df3f06c9ecdd47f81">DIEUnit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a> and <a href="#ab0a7f64f121eaf4d95424a3fbfcc921c">getUnitDie</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6d50108df42008d870359f0e7c98ea5d">llvm::DwarfUnit::addDIEEntry</a>, <a href="#ad17e92ea5b8abfc21028d5ebc6be8c16">getDebugSectionOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad258972cf15e00c497db2e2621c60e7b">llvm::DwarfUnit::getOrCreateSubprogramDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a061639ab612b4f5036d163a01275ced0">llvm::DwarfUnit::getOrCreateTypeDIE</a>.</p>

</div>
</div>

### getUnitDie() {#ab0a7f64f121eaf4d95424a3fbfcc921c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DIE * DIE::getUnitDie ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Climb up the parent chain to get the compile unit or type unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> that this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> belongs to.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the compile or type unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> that owns this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>, or NULL if this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> hasn't been added to a unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p></dd>
</dl>


<p>Declaration at line 921 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/die-cpp">DIE.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a150001a8f1d0061691188b80802e0365">llvm::DwarfCompileUnit::constructAbstractSubprogramScopeDIE</a> and <a href="#a7d981b742b9e50f3499554c31c6aa001">getUnit</a>.</p>

</div>
</div>

### hasChildren() {#ac91c79b70f4cc8c8cfe0dff567124ea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIE::hasChildren ()</td>
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



<p>Definition at line 867 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>Referenced by <a href="#a4db4b8aaa0f0da8dd11c5a279f4cfd6c">computeOffsetsAndAbbrevs</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1bcc04bcd84245c861201c01d2cc1a4c">llvm::AsmPrinter::emitDwarfDIE</a>, <a href="#a47e67f02f858b710768cbecf7fd08244">generateAbbrev</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a98b7757799d6bf9e5674586eaa362a61">llvm::DwarfUnit::hasContent</a> and <a href="#a07a09075f3cc7237c251adf0f4e8ba49">print</a>.</p>

</div>
</div>

### print() {#a07a09075f3cc7237c251adf0f4e8ba49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void DIE::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, unsigned IndentCount=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 954 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>, definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/die-cpp">DIE.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga3022f1d3f256e296d351404c6041d776">llvm::dwarf::AttributeString</a>, <a href="#a95e4509deb2adbc00a3091aab5c36e50">children</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga8e1e6661bc01fb23edee536f58d0ed06">llvm::dwarf::ChildrenString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga4863132f9f3dd24b6df4cfc6c9cfb676">llvm::dwarf::FormEncodingString</a>, <a href="#aeac16c22ec5a0c13658381144c7e3439">getTag</a>, <a href="#ac91c79b70f4cc8c8cfe0dff567124ea4">hasChildren</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gaf17a843ca40c67635b127ba50ad45bdf">llvm::dwarf::TagString</a> and <a href="/web-llvm/docs/api/classes/llvm/dievaluelist/#aaac0a2276b1fe9c13ec247892a7c3703">llvm::DIEValueList::values</a>.</p>


<p>Referenced by <a href="#aeec7f1000c747324d45318321277b7b9">dump</a>.</p>

</div>
</div>

### setAbbrevNumber() {#ab1516bd8f1676ec9e541a375a0dea5b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DIE::setAbbrevNumber (unsigned I)</td>
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

<p>Set the abbreviation number for this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 891 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dieabbrevset/#acd0912271cf17bd2b546eec9350021fa">llvm::DIEAbbrevSet::uniqueAbbreviation</a>.</p>

</div>
</div>

### setForceChildren() {#ac8f4097aac3899eaf9c6f1ffbaacbf0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DIE::setForceChildren (bool B)</td>
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



<p>Definition at line 868 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

</div>
</div>

### setOffset() {#ac5e71a222d770109a27a408f3df9d573}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DIE::setOffset (unsigned O)</td>
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



<p>Definition at line 930 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>Referenced by <a href="#a4db4b8aaa0f0da8dd11c5a279f4cfd6c">computeOffsetsAndAbbrevs</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#aafd0fac7574417fa923ca2bce4b9b85c">llvm::dwarf_linker::parallel::TypeUnit::createDIETree</a>.</p>

</div>
</div>

### setSize() {#a64a6a6e0ea513fadb1e384e8ef04bcca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DIE::setSize (unsigned S)</td>
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



<p>Definition at line 931 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>Referenced by <a href="#a4db4b8aaa0f0da8dd11c5a279f4cfd6c">computeOffsetsAndAbbrevs</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#aafd0fac7574417fa923ca2bce4b9b85c">llvm::dwarf_linker::parallel::TypeUnit::createDIETree</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AbbrevNumber {#a297570118498c03ee8ddfdb92a5d30fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DIE::AbbrevNumber = ~0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 827 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>

</div>
</div>

### Children {#ac660ab78edc3ed32a1c687e0213760a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrusiveBackList&lt;DIE&gt; llvm::DIE::Children</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Children DIEs.</p>

<p>Definition at line 834 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>

</div>
</div>

### ForceChildren {#af71b5ae985607b386621a13ed469153b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIE::ForceChildren = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set to true to force a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> to emit an abbreviation that says it has children even when it doesn't.</p>


<p>This is used for unit testing purposes.</p>


<p>Definition at line 832 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>

</div>
</div>

### Offset {#a1c74be0a2f1f685173e09698f86a25cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DIE::Offset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dwarf unit relative offset.</p>

<p>Definition at line 824 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>

</div>
</div>

### Owner {#a9f63989aa5de6e7b9bc1f29b8fe7a888}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerUnion&lt;DIE *, DIEUnit *&gt; llvm::DIE::Owner</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The owner is either the parent <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for children of other DIEs, or a <a href="/web-llvm/docs/api/classes/llvm/dieunit">DIEUnit</a> which contains this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> as its unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 838 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>

</div>
</div>

### Size {#af9329def93f390c4c2e2e88765cc81be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DIE::Size = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size of instance + children.</p>

<p>Definition at line 826 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>

</div>
</div>

### Tag {#a03619e3b6c7c7e6136adb83d070fde05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Tag llvm::DIE::Tag = (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a>)0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dwarf tag code.</p>

<p>Definition at line 829 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#a75692ef0b9a881db75fc0e0a79db0d1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * llvm::DIE::get (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Alloc, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> Tag)</td>
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



<p>Definition at line 849 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1aea571dc00aef155a16d4e7e1861e1682">llvm::Alloc</a> and <a href="#aa708a4501ac8ca4afb2625745da3bed0">DIE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a0284131decd7881e49a1dc2b82e4ac58">llvm::DwarfCompileUnit::constructCallSiteParmEntryDIEs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">llvm::DwarfCompileUnit::constructImportedEntityDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a47e64bee9baa8d3436add9ec49d1c880">llvm::DwarfCompileUnit::constructInlinedScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad6d394e7617fdbb955ce7db1fc9aaff7">llvm::DwarfCompileUnit::constructLabelDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ac43078e4f82c8dea48b4a483de6f434a">llvm::DwarfCompileUnit::constructLexicalScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a8cbe3dd2e5c24c363d750bd49f46838a">llvm::DwarfCompileUnit::constructSubprogramScopeDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a90e6b90f1ecca9999a225bac737d2fdc">llvm::DwarfCompileUnit::constructVariableDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4053999da10fee3e053346031495319">llvm::DwarfUnit::createAndAddDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a4c89d112b2f04f66826428c19d11301b">llvm::DwarfCompileUnit::createBaseTypeDIEs</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/diegenerator/#a7bcf59b48e896fea4f6661dffa7351da">llvm::dwarf_linker::parallel::DIEGenerator::createDIE</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/die-h">DIE.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/die-cpp">DIE.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
