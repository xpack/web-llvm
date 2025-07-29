---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/attributeimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AttributeImpl` Class

<p>This class represents a single, uniqued attribute. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AttributeImpl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">IR/AttributeImpl.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/node">Node</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/node">Node</a> - This class is used to maintain the singly linked bucket list in a folding set. <a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/node/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/enumattributeimpl">EnumAttributeImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A set of classes that contain the value of the attribute object. <a href="/web-llvm/docs/api/classes/llvm/enumattributeimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringattributeimpl">StringAttributeImpl</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AttrEntryKind { <a href="#ad687fe589b8c087f908d4e41bcf66166">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81e2276b47566272c5c9d87193ab409d">AttributeImpl</a> (const AttributeImpl &amp;)=delete</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a802c6cb7f206ed389cbe1998a0ee01a9">AttributeImpl</a> (AttrEntryKind KindID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributeimpl">AttributeImpl</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a20a902fbbe903e4e591fccf3982f0a">operator=</a> (const AttributeImpl &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dc4bacb61d0b726ec23d18fda5f1a76">operator&lt;</a> (const AttributeImpl &amp;AI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used when sorting the attributes. <a href="#a3dc4bacb61d0b726ec23d18fda5f1a76">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac82722cd2063bb39b4a37b2a90fda40a">isEnumAttribute</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e84d6fd7d3a6ef11c83ead650d38f9c">isIntAttribute</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae02b37952f7583a393946593dae35fdb">isStringAttribute</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a618c8ff522577f59712aec5845443d7b">isTypeAttribute</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bd27b76c67871232b7797518a46e923">isConstantRangeAttribute</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad228c2a1fba41cadc79fb716cbd1e92c">isConstantRangeListAttribute</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0daa077a9ade7e3b8fafcde322dc8a3a">hasAttribute</a> (Attribute::AttrKind A) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a150bd3a1662e3c18443acd93c8a14aa9">hasAttribute</a> (StringRef Kind) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d5688ec3c9362d11c03b1f6de813953">getKindAsEnum</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4da6f9c23016f3bf3e0f505af90a42d5">getValueAsInt</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab06d58fe7aedd28c4219a1d26ec33c0e">getValueAsBool</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab492e48341c1c2045e053857882be880">getKindAsString</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7a6cfbcd78906a5e27a0f1d6e013605">getValueAsString</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2237f342f2aeab6f2a02c7bb3ed5f423">getValueAsType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd9c0d5f036b466320fc56a76ba3023a">getValueAsConstantRange</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1d3b93d1478348edcd9b073d2352fc1">getValueAsConstantRangeList</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09dae4090576d1532ff1c430cacf0419">cmp</a> (const AttributeImpl &amp;AI, bool KindOnly) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to sort attributes. <a href="#a09dae4090576d1532ff1c430cacf0419">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fc4cec7529e980229ddd28ef18898fe">Profile</a> (FoldingSetNodeID &amp;ID) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ef84dd33a85401b82bc10e714e7dd23">KindID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds the <a href="#ad687fe589b8c087f908d4e41bcf66166">AttrEntryKind</a> of the attribute. <a href="#a2ef84dd33a85401b82bc10e714e7dd23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b9407f2fcb1a0cc5624be342512a31f">Profile</a> (FoldingSetNodeID &amp;ID, Attribute::AttrKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48b71d6b1b3a5ef2016ed307e23b2f71">Profile</a> (FoldingSetNodeID &amp;ID, Attribute::AttrKind Kind, uint64_t Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d70fffce492b01bdb5fb0e43d33372c">Profile</a> (FoldingSetNodeID &amp;ID, StringRef Kind, StringRef Values)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97c78388fc8487249582c342b339a834">Profile</a> (FoldingSetNodeID &amp;ID, Attribute::AttrKind Kind, Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af02f5875e490164276cc8aac0f31b78e">Profile</a> (FoldingSetNodeID &amp;ID, Attribute::AttrKind Kind, const ConstantRange &amp;CR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6799f9331fcf2d45f792f8c23038aea3">Profile</a> (FoldingSetNodeID &amp;ID, Attribute::AttrKind Kind, ArrayRef&lt; ConstantRange &gt; Val)</td>
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

<p>This class represents a single, uniqued attribute.</p>


<p>That attribute could be a single enum, a tuple, or a string.</p>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### AttrEntryKind {#ad687fe589b8c087f908d4e41bcf66166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AttributeImpl::AttrEntryKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
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
<td class="doxyEnumItemName">EnumAttrEntry<a id="ad687fe589b8c087f908d4e41bcf66166ad37a811c5a3b72fb28a35a0a6be5c2ca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IntAttrEntry<a id="ad687fe589b8c087f908d4e41bcf66166a78af050f3f423cf7f8be90b5c35b8e20"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StringAttrEntry<a id="ad687fe589b8c087f908d4e41bcf66166a1b51d0afcac6cd797bb3a9d8c6c13fae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TypeAttrEntry<a id="ad687fe589b8c087f908d4e41bcf66166a18489fdf6d3f3fd183ea79c13c4f5a00"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ConstantRangeAttrEntry<a id="ad687fe589b8c087f908d4e41bcf66166a271ef5b5f2c87258f3f77734085dc7f2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ConstantRangeListAttrEntry<a id="ad687fe589b8c087f908d4e41bcf66166a7cd0e070919ef1d8a4b4f7f78bcd16e7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AttributeImpl() {#a81e2276b47566272c5c9d87193ab409d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AttributeImpl::AttributeImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributeimpl">AttributeImpl</a> &amp;)</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>.</p>


<p>Reference <a href="#a802c6cb7f206ed389cbe1998a0ee01a9">AttributeImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### AttributeImpl() {#a802c6cb7f206ed389cbe1998a0ee01a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AttributeImpl::AttributeImpl (<a href="#ad687fe589b8c087f908d4e41bcf66166">AttrEntryKind</a> KindID)</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>.</p>


<p>Referenced by <a href="#a81e2276b47566272c5c9d87193ab409d">AttributeImpl</a>, <a href="#a09dae4090576d1532ff1c430cacf0419">cmp</a>, <a href="/web-llvm/docs/api/classes/llvm/enumattributeimpl/#a3a4aa3bb40c2bfce8a6cd0c9fd384857">llvm::EnumAttributeImpl::EnumAttributeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/enumattributeimpl/#ac677481f1e26f5efbdfc56d6f9221e7d">llvm::EnumAttributeImpl::EnumAttributeImpl</a>, <a href="#a3dc4bacb61d0b726ec23d18fda5f1a76">operator&lt;</a>, <a href="#a4a20a902fbbe903e4e591fccf3982f0a">operator=</a> and <a href="/web-llvm/docs/api/classes/llvm/stringattributeimpl/#a041f1a5a4d3269c9d333908d2eba2cde">llvm::StringAttributeImpl::StringAttributeImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;() {#a3dc4bacb61d0b726ec23d18fda5f1a76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AttributeImpl::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributeimpl">AttributeImpl</a> &amp; AI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used when sorting the attributes.</p>

<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>, definition at line 902 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#a802c6cb7f206ed389cbe1998a0ee01a9">AttributeImpl</a> and <a href="#a09dae4090576d1532ff1c430cacf0419">cmp</a>.</p>

</div>
</div>

### operator=() {#a4a20a902fbbe903e4e591fccf3982f0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeImpl &amp; llvm::AttributeImpl::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributeimpl">AttributeImpl</a> &amp;)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>.</p>


<p>Reference <a href="#a802c6cb7f206ed389cbe1998a0ee01a9">AttributeImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### cmp() {#a09dae4090576d1532ff1c430cacf0419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int AttributeImpl::cmp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributeimpl">AttributeImpl</a> &amp; AI, bool KindOnly)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to sort attributes.</p>


<p>KindOnly controls if the sort includes the attributes' values or just the kind.</p>


<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>, definition at line 867 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a802c6cb7f206ed389cbe1998a0ee01a9">AttributeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae0c6424784f132b91eb387a3ee0b57c9">llvm::StringRef::compare</a>, <a href="#a2d5688ec3c9362d11c03b1f6de813953">getKindAsEnum</a>, <a href="#ab492e48341c1c2045e053857882be880">getKindAsString</a>, <a href="#a4da6f9c23016f3bf3e0f505af90a42d5">getValueAsInt</a>, <a href="#ab7a6cfbcd78906a5e27a0f1d6e013605">getValueAsString</a>, <a href="#a0bd27b76c67871232b7797518a46e923">isConstantRangeAttribute</a>, <a href="#ad228c2a1fba41cadc79fb716cbd1e92c">isConstantRangeListAttribute</a>, <a href="#ac82722cd2063bb39b4a37b2a90fda40a">isEnumAttribute</a>, <a href="#a4e84d6fd7d3a6ef11c83ead650d38f9c">isIntAttribute</a>, <a href="#ae02b37952f7583a393946593dae35fdb">isStringAttribute</a> and <a href="#a618c8ff522577f59712aec5845443d7b">isTypeAttribute</a>.</p>


<p>Referenced by <a href="#a3dc4bacb61d0b726ec23d18fda5f1a76">operator&lt;</a>.</p>

</div>
</div>

### getKindAsEnum() {#a2d5688ec3c9362d11c03b1f6de813953}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute::AttrKind AttributeImpl::getKindAsEnum ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>, definition at line 824 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0bd27b76c67871232b7797518a46e923">isConstantRangeAttribute</a>, <a href="#ad228c2a1fba41cadc79fb716cbd1e92c">isConstantRangeListAttribute</a>, <a href="#ac82722cd2063bb39b4a37b2a90fda40a">isEnumAttribute</a>, <a href="#a4e84d6fd7d3a6ef11c83ead650d38f9c">isIntAttribute</a> and <a href="#a618c8ff522577f59712aec5845443d7b">isTypeAttribute</a>.</p>


<p>Referenced by <a href="#a09dae4090576d1532ff1c430cacf0419">cmp</a>, <a href="#a0daa077a9ade7e3b8fafcde322dc8a3a">hasAttribute</a> and <a href="#a0fc4cec7529e980229ddd28ef18898fe">Profile</a>.</p>

</div>
</div>

### getKindAsString() {#ab492e48341c1c2045e053857882be880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef AttributeImpl::getKindAsString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>, definition at line 840 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ae02b37952f7583a393946593dae35fdb">isStringAttribute</a>.</p>


<p>Referenced by <a href="#a09dae4090576d1532ff1c430cacf0419">cmp</a>, <a href="#a150bd3a1662e3c18443acd93c8a14aa9">hasAttribute</a> and <a href="#a0fc4cec7529e980229ddd28ef18898fe">Profile</a>.</p>

</div>
</div>

### getValueAsBool() {#ab06d58fe7aedd28c4219a1d26ec33c0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AttributeImpl::getValueAsBool ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>, definition at line 835 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ab7a6cfbcd78906a5e27a0f1d6e013605">getValueAsString</a>.</p>

</div>
</div>

### getValueAsConstantRange() {#afd9c0d5f036b466320fc56a76ba3023a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConstantRange &amp; AttributeImpl::getValueAsConstantRange ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>, definition at line 855 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a0bd27b76c67871232b7797518a46e923">isConstantRangeAttribute</a>.</p>


<p>Referenced by <a href="#a0fc4cec7529e980229ddd28ef18898fe">Profile</a>.</p>

</div>
</div>

### getValueAsConstantRangeList() {#ad1d3b93d1478348edcd9b073d2352fc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; ConstantRange &gt; AttributeImpl::getValueAsConstantRangeList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>, definition at line 861 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad228c2a1fba41cadc79fb716cbd1e92c">isConstantRangeListAttribute</a>.</p>


<p>Referenced by <a href="#a0fc4cec7529e980229ddd28ef18898fe">Profile</a>.</p>

</div>
</div>

### getValueAsInt() {#a4da6f9c23016f3bf3e0f505af90a42d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t AttributeImpl::getValueAsInt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>, definition at line 830 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4e84d6fd7d3a6ef11c83ead650d38f9c">isIntAttribute</a>.</p>


<p>Referenced by <a href="#a09dae4090576d1532ff1c430cacf0419">cmp</a> and <a href="#a0fc4cec7529e980229ddd28ef18898fe">Profile</a>.</p>

</div>
</div>

### getValueAsString() {#ab7a6cfbcd78906a5e27a0f1d6e013605}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef AttributeImpl::getValueAsString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>, definition at line 845 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ae02b37952f7583a393946593dae35fdb">isStringAttribute</a>.</p>


<p>Referenced by <a href="#a09dae4090576d1532ff1c430cacf0419">cmp</a>, <a href="#ab06d58fe7aedd28c4219a1d26ec33c0e">getValueAsBool</a> and <a href="#a0fc4cec7529e980229ddd28ef18898fe">Profile</a>.</p>

</div>
</div>

### getValueAsType() {#a2237f342f2aeab6f2a02c7bb3ed5f423}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * AttributeImpl::getValueAsType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>, definition at line 850 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a618c8ff522577f59712aec5845443d7b">isTypeAttribute</a>.</p>


<p>Referenced by <a href="#a0fc4cec7529e980229ddd28ef18898fe">Profile</a>.</p>

</div>
</div>

### hasAttribute() {#a0daa077a9ade7e3b8fafcde322dc8a3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AttributeImpl::hasAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>, definition at line 814 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a2d5688ec3c9362d11c03b1f6de813953">getKindAsEnum</a> and <a href="#ae02b37952f7583a393946593dae35fdb">isStringAttribute</a>.</p>

</div>
</div>

### hasAttribute() {#a150bd3a1662e3c18443acd93c8a14aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AttributeImpl::hasAttribute (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>, definition at line 819 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a>.</p>


<p>References <a href="#ab492e48341c1c2045e053857882be880">getKindAsString</a> and <a href="#ae02b37952f7583a393946593dae35fdb">isStringAttribute</a>.</p>

</div>
</div>

### isConstantRangeAttribute() {#a0bd27b76c67871232b7797518a46e923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeImpl::isConstantRangeAttribute ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>.</p>


<p>Reference <a href="#ad687fe589b8c087f908d4e41bcf66166a271ef5b5f2c87258f3f77734085dc7f2">ConstantRangeAttrEntry</a>.</p>


<p>Referenced by <a href="#a09dae4090576d1532ff1c430cacf0419">cmp</a>, <a href="#a2d5688ec3c9362d11c03b1f6de813953">getKindAsEnum</a>, <a href="#afd9c0d5f036b466320fc56a76ba3023a">getValueAsConstantRange</a> and <a href="#a0fc4cec7529e980229ddd28ef18898fe">Profile</a>.</p>

</div>
</div>

### isConstantRangeListAttribute() {#ad228c2a1fba41cadc79fb716cbd1e92c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeImpl::isConstantRangeListAttribute ()</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>.</p>


<p>Reference <a href="#ad687fe589b8c087f908d4e41bcf66166a7cd0e070919ef1d8a4b4f7f78bcd16e7">ConstantRangeListAttrEntry</a>.</p>


<p>Referenced by <a href="#a09dae4090576d1532ff1c430cacf0419">cmp</a>, <a href="#a2d5688ec3c9362d11c03b1f6de813953">getKindAsEnum</a> and <a href="#ad1d3b93d1478348edcd9b073d2352fc1">getValueAsConstantRangeList</a>.</p>

</div>
</div>

### isEnumAttribute() {#ac82722cd2063bb39b4a37b2a90fda40a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeImpl::isEnumAttribute ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>.</p>


<p>Reference <a href="#ad687fe589b8c087f908d4e41bcf66166ad37a811c5a3b72fb28a35a0a6be5c2ca">EnumAttrEntry</a>.</p>


<p>Referenced by <a href="#a09dae4090576d1532ff1c430cacf0419">cmp</a>, <a href="#a2d5688ec3c9362d11c03b1f6de813953">getKindAsEnum</a> and <a href="#a0fc4cec7529e980229ddd28ef18898fe">Profile</a>.</p>

</div>
</div>

### isIntAttribute() {#a4e84d6fd7d3a6ef11c83ead650d38f9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeImpl::isIntAttribute ()</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>.</p>


<p>Reference <a href="#ad687fe589b8c087f908d4e41bcf66166a78af050f3f423cf7f8be90b5c35b8e20">IntAttrEntry</a>.</p>


<p>Referenced by <a href="#a09dae4090576d1532ff1c430cacf0419">cmp</a>, <a href="#a2d5688ec3c9362d11c03b1f6de813953">getKindAsEnum</a>, <a href="#a4da6f9c23016f3bf3e0f505af90a42d5">getValueAsInt</a> and <a href="#a0fc4cec7529e980229ddd28ef18898fe">Profile</a>.</p>

</div>
</div>

### isStringAttribute() {#ae02b37952f7583a393946593dae35fdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeImpl::isStringAttribute ()</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>.</p>


<p>Reference <a href="#ad687fe589b8c087f908d4e41bcf66166a1b51d0afcac6cd797bb3a9d8c6c13fae">StringAttrEntry</a>.</p>


<p>Referenced by <a href="#a09dae4090576d1532ff1c430cacf0419">cmp</a>, <a href="#ab492e48341c1c2045e053857882be880">getKindAsString</a>, <a href="#ab7a6cfbcd78906a5e27a0f1d6e013605">getValueAsString</a>, <a href="#a0daa077a9ade7e3b8fafcde322dc8a3a">hasAttribute</a>, <a href="#a150bd3a1662e3c18443acd93c8a14aa9">hasAttribute</a> and <a href="#a0fc4cec7529e980229ddd28ef18898fe">Profile</a>.</p>

</div>
</div>

### isTypeAttribute() {#a618c8ff522577f59712aec5845443d7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AttributeImpl::isTypeAttribute ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>.</p>


<p>Reference <a href="#ad687fe589b8c087f908d4e41bcf66166a18489fdf6d3f3fd183ea79c13c4f5a00">TypeAttrEntry</a>.</p>


<p>Referenced by <a href="#a09dae4090576d1532ff1c430cacf0419">cmp</a>, <a href="#a2d5688ec3c9362d11c03b1f6de813953">getKindAsEnum</a>, <a href="#a2237f342f2aeab6f2a02c7bb3ed5f423">getValueAsType</a> and <a href="#a0fc4cec7529e980229ddd28ef18898fe">Profile</a>.</p>

</div>
</div>

### Profile() {#a0fc4cec7529e980229ddd28ef18898fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AttributeImpl::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID)</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>.</p>


<p>References <a href="#a2d5688ec3c9362d11c03b1f6de813953">getKindAsEnum</a>, <a href="#ab492e48341c1c2045e053857882be880">getKindAsString</a>, <a href="#afd9c0d5f036b466320fc56a76ba3023a">getValueAsConstantRange</a>, <a href="#ad1d3b93d1478348edcd9b073d2352fc1">getValueAsConstantRangeList</a>, <a href="#a4da6f9c23016f3bf3e0f505af90a42d5">getValueAsInt</a>, <a href="#ab7a6cfbcd78906a5e27a0f1d6e013605">getValueAsString</a>, <a href="#a2237f342f2aeab6f2a02c7bb3ed5f423">getValueAsType</a>, <a href="#a0bd27b76c67871232b7797518a46e923">isConstantRangeAttribute</a>, <a href="#ac82722cd2063bb39b4a37b2a90fda40a">isEnumAttribute</a>, <a href="#a4e84d6fd7d3a6ef11c83ead650d38f9c">isIntAttribute</a>, <a href="#ae02b37952f7583a393946593dae35fdb">isStringAttribute</a>, <a href="#a618c8ff522577f59712aec5845443d7b">isTypeAttribute</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp/#a009775794ead70aa23c76df46ab4ed8a">Profile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### KindID {#a2ef84dd33a85401b82bc10e714e7dd23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::AttributeImpl::KindID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds the <a href="#ad687fe589b8c087f908d4e41bcf66166">AttrEntryKind</a> of the attribute.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Profile() {#a4b9407f2fcb1a0cc5624be342512a31f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AttributeImpl::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#ad343d2ea041d596a04db3252e3017cad">llvm::Attribute::isEnumAttrKind</a>.</p>

</div>
</div>

### Profile() {#a48b71d6b1b3a5ef2016ed307e23b2f71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AttributeImpl::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind, uint64_t Val)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#ac2d5f8ba4215304f89a401248abed393">llvm::Attribute::isIntAttrKind</a>.</p>

</div>
</div>

### Profile() {#a2d70fffce492b01bdb5fb0e43d33372c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AttributeImpl::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Values)</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>.</p>

</div>
</div>

### Profile() {#a97c78388fc8487249582c342b339a834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AttributeImpl::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>.</p>

</div>
</div>

### Profile() {#af02f5875e490164276cc8aac0f31b78e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AttributeImpl::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR)</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a23f4339e49343721146062b10c144052">llvm::ConstantRange::getLower</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa1955c426e1ff66455b4bb6657ee995d">llvm::ConstantRange::getUpper</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#adb1c052266ebacdbf28164fae9106b0a">llvm::APInt::Profile</a>.</p>

</div>
</div>

### Profile() {#a6799f9331fcf2d45f792f8c23038aea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AttributeImpl::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt; Val)</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/attributeimpl-h">AttributeImpl.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp">Attributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
