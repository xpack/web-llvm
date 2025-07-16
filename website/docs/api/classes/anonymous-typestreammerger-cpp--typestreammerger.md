---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-typestreammerger-cpp-/typestreammerger
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TypeStreamMerger` Class Reference

<p>Implementation of CodeView type stream merging. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{TypeStreamMerger.cpp}::TypeStreamMerger { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9228fb82c65a47ff4aa0708502d80b1">TypeStreamMerger</a> (SmallVectorImpl&lt; TypeIndex &gt; &amp;SourceToDest)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51c2d92478f16e57c2cc7c3f7d304c75">mergeTypesAndIds</a> (MergingTypeTableBuilder &amp;DestIds, MergingTypeTableBuilder &amp;DestTypes, const CVTypeArray &amp;IdsAndTypes, std::optional&lt; PCHMergerInfo &gt; &amp;PCHInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2e29313aefad023e10b5fbcd96e0ba4">mergeIdRecords</a> (MergingTypeTableBuilder &amp;Dest, ArrayRef&lt; TypeIndex &gt; TypeSourceToDest, const CVTypeArray &amp;Ids)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae767fa21736fb1b6d9af5c0c15d477e2">mergeTypeRecords</a> (MergingTypeTableBuilder &amp;Dest, const CVTypeArray &amp;Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62d50e6e2fccc16d0cb1ca33d7397f2f">mergeTypesAndIds</a> (GlobalTypeTableBuilder &amp;DestIds, GlobalTypeTableBuilder &amp;DestTypes, const CVTypeArray &amp;IdsAndTypes, ArrayRef&lt; GloballyHashedType &gt; Hashes, std::optional&lt; PCHMergerInfo &gt; &amp;PCHInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2d91d5b4f4e0a405de342053164c102">mergeIdRecords</a> (GlobalTypeTableBuilder &amp;Dest, ArrayRef&lt; TypeIndex &gt; TypeSourceToDest, const CVTypeArray &amp;Ids, ArrayRef&lt; GloballyHashedType &gt; Hashes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20fa7c422babea2e337894aad29f9724">mergeTypeRecords</a> (GlobalTypeTableBuilder &amp;Dest, const CVTypeArray &amp;Types, ArrayRef&lt; GloballyHashedType &gt; Hashes, std::optional&lt; PCHMergerInfo &gt; &amp;PCHInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86aa3d1ae79b65c4ecb719c0f719217a">doit</a> (const CVTypeArray &amp;Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b6b0ea9343bb9563c9370ce2db08d06">remapAllTypes</a> (const CVTypeArray &amp;Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16ff9b215c4e42edb048cf12c8f3911c">remapType</a> (const CVType &amp;Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09ed99295861d7fbfd89265743d6ae5b">addMapping</a> (TypeIndex Idx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dce93ff56f211c412c48df973b84bdb">remapTypeIndex</a> (TypeIndex &amp;Idx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b57f11e4219cdd9a43823b94bca2c83">remapItemIndex</a> (TypeIndex &amp;Idx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08796ceb93621c1e848d85f2e583d873">hasTypeStream</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7b0b247890af8f23c44de633393529c">hasIdStream</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac65a071e6ca52cd414aed59f5b259e4a">remapIndices</a> (const CVType &amp;OriginalType, MutableArrayRef&lt; uint8_t &gt; Storage)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34b51e81cca1b28beb9f0825291d9c07">remapIndex</a> (TypeIndex &amp;Idx, ArrayRef&lt; TypeIndex &gt; Map)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d5fa53c90c4c6567ab58e78a0e19301">remapIndexSimple</a> (TypeIndex &amp;Idx, ArrayRef&lt; TypeIndex &gt; Map) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a344580c66bcc1822ff541fc2a8aa452a">remapIndexFallback</a> (TypeIndex &amp;Idx, ArrayRef&lt; TypeIndex &gt; Map)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac097f030992b36f33ea27d3f91a4066a">errorCorruptRecord</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacea20cee46c66188e5bcc3a558e9bf0">shouldRemapType</a> (const CVType &amp;Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aa53324427c77170b32cb8cfe4e7944">LastError</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadce504dcd3f07d6771e19c1f6470e58">UseGlobalHashes</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a692433da77e6a714e9e912f6e362a7f9">IsSecondPass</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae87706637a05e846e4f174f31b73de65">NumBadIndices</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e4e7bcf18108e5008c2c33187931642">CurIndex</a> {TypeIndex::FirstNonSimpleIndex}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/mergingtypetablebuilder">MergingTypeTableBuilder</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6979d0319f9a55a6497fa9d53928edb6">DestIdStream</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/mergingtypetablebuilder">MergingTypeTableBuilder</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74eb1b85a41fd767d37fe28c1b13226b">DestTypeStream</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/globaltypetablebuilder">GlobalTypeTableBuilder</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafd33d540d8c89733e84d12cb9e2efb1">DestGlobalIdStream</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/globaltypetablebuilder">GlobalTypeTableBuilder</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3599e132e63b3f0958bc6b308ab5a24d">DestGlobalTypeStream</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30f21ca3740ef74e52bb11c719026f2f">GlobalHashes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e8bee9191ada383c33525737d7e5345">TypeLookup</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b65655952234cdfb7f4242368b2f85c">IndexMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from source type index to destination type index. <a href="#a8b65655952234cdfb7f4242368b2f85c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint8_t, 256 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a009c65776a9960653d4453237fad3ebb">RemapStorage</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Temporary storage that we use to copy a record's data while re-writing its type indices. <a href="#a009c65776a9960653d4453237fad3ebb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/pchmergerinfo">PCHMergerInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60a971d39dd3d4aaabc5944d2c8428d1">PCHInfo</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7568fd1d6a96e85835530d9e2d51a6ce">Untranslated</a></td>
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

<p>Implementation of CodeView type stream merging.</p>


<p>A CodeView type stream is a series of records that reference each other through type indices. A type index is either "simple", meaning it is less than 0x1000 and refers to a builtin type, or it is complex, meaning it refers to a prior type record in the current stream. The type index of a record is equal to the number of records before it in the stream plus 0x1000.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> records are only allowed to use type indices smaller than their own, so a type stream is effectively a topologically sorted DAG. Cycles occurring in the type graph of the source program are resolved with forward declarations of composite types. This class implements the following type stream merging algorithm, which relies on this DAG structure:</p>


<ul class="doxyList ">
<li>Begin with a new empty stream, and a new empty hash table that maps from type record contents to new type index.</li>
<li>For each new type stream, maintain a map from source type index to destination type index.</li>
<li>For each record, copy it and rewrite its type indices to be valid in the destination type stream.</li>
<li>If the new type record is not already present in the destination stream hash table, append it to the destination type stream, assign it the next type index, and update the two hash tables.</li>
<li>If the type record already exists in the destination stream, discard it and update the type index map to forward the source type index to the existing destination type index.</li>
</ul>

<p>As an additional complication, type stream merging actually produces two streams: an item (or IPI) stream and a type stream, as this is what is actually stored in the final PDB. We choose which records go where by looking at the record kind.</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TypeStreamMerger() {#ae9228fb82c65a47ff4aa0708502d80b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::TypeStreamMerger (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &gt; &amp; SourceToDest)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a430de55e5c2543356750109df10f0547">llvm::codeview::mergeIdRecords</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a56089b6df59b900fd953910dccb91612">llvm::codeview::mergeIdRecords</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#abbda73b0e6e64d5f6484c2cf68b4e227">llvm::codeview::mergeTypeAndIdRecords</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a7d3dd9f573c63aef69adf9407e885b6b">llvm::codeview::mergeTypeAndIdRecords</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a67254426685ce2a3d3ee80a32b18c98a">llvm::codeview::mergeTypeRecords</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#add29180c37bd611ab5357b7d2b51bc13">llvm::codeview::mergeTypeRecords</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### mergeIdRecords() {#af2e29313aefad023e10b5fbcd96e0ba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TypeStreamMerger::mergeIdRecords (<a href="/web-llvm/docs/api/classes/llvm/codeview/mergingtypetablebuilder">MergingTypeTableBuilder</a> &amp; Dest, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &gt; TypeSourceToDest, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3b5a871028c3a00c356376368d4d57d9">CVTypeArray</a> &amp; Ids)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### mergeIdRecords() {#ac2d91d5b4f4e0a405de342053164c102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TypeStreamMerger::mergeIdRecords (<a href="/web-llvm/docs/api/classes/llvm/codeview/globaltypetablebuilder">GlobalTypeTableBuilder</a> &amp; Dest, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &gt; TypeSourceToDest, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3b5a871028c3a00c356376368d4d57d9">CVTypeArray</a> &amp; Ids, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a> &gt; Hashes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### mergeTypeRecords() {#ae767fa21736fb1b6d9af5c0c15d477e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TypeStreamMerger::mergeTypeRecords (<a href="/web-llvm/docs/api/classes/llvm/codeview/mergingtypetablebuilder">MergingTypeTableBuilder</a> &amp; Dest, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3b5a871028c3a00c356376368d4d57d9">CVTypeArray</a> &amp; Types)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### mergeTypeRecords() {#a20fa7c422babea2e337894aad29f9724}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TypeStreamMerger::mergeTypeRecords (<a href="/web-llvm/docs/api/classes/llvm/codeview/globaltypetablebuilder">GlobalTypeTableBuilder</a> &amp; Dest, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3b5a871028c3a00c356376368d4d57d9">CVTypeArray</a> &amp; Types, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a> &gt; Hashes, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/pchmergerinfo">PCHMergerInfo</a> &gt; &amp; PCHInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### mergeTypesAndIds() {#a51c2d92478f16e57c2cc7c3f7d304c75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TypeStreamMerger::mergeTypesAndIds (<a href="/web-llvm/docs/api/classes/llvm/codeview/mergingtypetablebuilder">MergingTypeTableBuilder</a> &amp; DestIds, <a href="/web-llvm/docs/api/classes/llvm/codeview/mergingtypetablebuilder">MergingTypeTableBuilder</a> &amp; DestTypes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3b5a871028c3a00c356376368d4d57d9">CVTypeArray</a> &amp; IdsAndTypes, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/pchmergerinfo">PCHMergerInfo</a> &gt; &amp; PCHInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### mergeTypesAndIds() {#a62d50e6e2fccc16d0cb1ca33d7397f2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TypeStreamMerger::mergeTypesAndIds (<a href="/web-llvm/docs/api/classes/llvm/codeview/globaltypetablebuilder">GlobalTypeTableBuilder</a> &amp; DestIds, <a href="/web-llvm/docs/api/classes/llvm/codeview/globaltypetablebuilder">GlobalTypeTableBuilder</a> &amp; DestTypes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3b5a871028c3a00c356376368d4d57d9">CVTypeArray</a> &amp; IdsAndTypes, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype">GloballyHashedType</a> &gt; Hashes, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/pchmergerinfo">PCHMergerInfo</a> &gt; &amp; PCHInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addMapping() {#a09ed99295861d7fbfd89265743d6ae5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TypeStreamMerger::addMapping (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### doit() {#a86aa3d1ae79b65c4ecb719c0f719217a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TypeStreamMerger::doit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3b5a871028c3a00c356376368d4d57d9">CVTypeArray</a> &amp; Types)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### errorCorruptRecord() {#ac097f030992b36f33ea27d3f91a4066a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::errorCorruptRecord ()</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### hasIdStream() {#ad7b0b247890af8f23c44de633393529c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::hasIdStream ()</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### hasTypeStream() {#a08796ceb93621c1e848d85f2e583d873}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::hasTypeStream ()</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### remapAllTypes() {#a0b6b0ea9343bb9563c9370ce2db08d06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TypeStreamMerger::remapAllTypes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a3b5a871028c3a00c356376368d4d57d9">CVTypeArray</a> &amp; Types)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### remapIndex() {#a34b51e81cca1b28beb9f0825291d9c07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::remapIndex (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &amp; Idx, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &gt; Map)</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### remapIndexFallback() {#a344580c66bcc1822ff541fc2a8aa452a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TypeStreamMerger::remapIndexFallback (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &amp; Idx, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &gt; Map)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### remapIndexSimple() {#a1d5fa53c90c4c6567ab58e78a0e19301}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::remapIndexSimple (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &amp; Idx, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &gt; Map)</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### remapIndices() {#ac65a071e6ca52cd414aed59f5b259e4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; TypeStreamMerger::remapIndices (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; OriginalType, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; uint8_t &gt; Storage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### remapItemIndex() {#a5b57f11e4219cdd9a43823b94bca2c83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::remapItemIndex (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &amp; Idx)</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### remapType() {#a16ff9b215c4e42edb048cf12c8f3911c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TypeStreamMerger::remapType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### remapTypeIndex() {#a6dce93ff56f211c412c48df973b84bdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::remapTypeIndex (<a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &amp; Idx)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### shouldRemapType() {#aacea20cee46c66188e5bcc3a558e9bf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; TypeStreamMerger::shouldRemapType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurIndex {#a6e4e7bcf18108e5008c2c33187931642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeIndex anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::CurIndex {TypeIndex::FirstNonSimpleIndex}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### DestGlobalIdStream {#aafd33d540d8c89733e84d12cb9e2efb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalTypeTableBuilder* anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::DestGlobalIdStream = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### DestGlobalTypeStream {#a3599e132e63b3f0958bc6b308ab5a24d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalTypeTableBuilder* anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::DestGlobalTypeStream = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### DestIdStream {#a6979d0319f9a55a6497fa9d53928edb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MergingTypeTableBuilder* anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::DestIdStream = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### DestTypeStream {#a74eb1b85a41fd767d37fe28c1b13226b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MergingTypeTableBuilder* anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::DestTypeStream = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### GlobalHashes {#a30f21ca3740ef74e52bb11c719026f2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;GloballyHashedType&gt; anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::GlobalHashes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### IndexMap {#a8b65655952234cdfb7f4242368b2f85c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt;TypeIndex&gt;&amp; anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::IndexMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from source type index to destination type index.</p>


<p>Indexed by source type index minus 0x1000.</p>


<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### IsSecondPass {#a692433da77e6a714e9e912f6e362a7f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::IsSecondPass = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### LastError {#a6aa53324427c77170b32cb8cfe4e7944}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;Error&gt; anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::LastError</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### NumBadIndices {#ae87706637a05e846e4f174f31b73de65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::NumBadIndices = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### PCHInfo {#a60a971d39dd3d4aaabc5944d2c8428d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;PCHMergerInfo&gt; anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::PCHInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### RemapStorage {#a009c65776a9960653d4453237fad3ebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;uint8_t, 256&gt; anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::RemapStorage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Temporary storage that we use to copy a record's data while re-writing its type indices.</p>

<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### TypeLookup {#a5e8bee9191ada383c33525737d7e5345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;TypeIndex&gt; anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::TypeLookup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

### UseGlobalHashes {#aadce504dcd3f07d6771e19c1f6470e58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::UseGlobalHashes = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### Untranslated {#a7568fd1d6a96e85835530d9e2d51a6ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TypeIndex TypeStreamMerger::Untranslated</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typestreammerger-cpp">TypeStreamMerger.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
