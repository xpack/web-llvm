---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dibasictype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DIBasicType` Class Reference

<p>Basic type, like 'int' or 'float'. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DIBasicType { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for types. <a href="/web-llvm/docs/api/classes/llvm/ditype/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Signedness { <a href="#a60f94cc0e71193b01ca24ef37de9845a">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a839c7018604b2469c1ac5128468f60">DIBasicType</a> (LLVMContext &amp;C, StorageType Storage, unsigned Tag, uint64_t SizeInBits, uint32_t AlignInBits, unsigned Encoding, uint32_t NumExtraInhabitants, DIFlags Flags, ArrayRef&lt; Metadata * &gt; Ops)</td>
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

## Private Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6683ab4898c05216627d8ceb6cd67612">~DIBasicType</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecc478d4d96a5c30f453d2bb726e58ad">DEFINE_MDNODE_GET</a> (DIBasicType,(unsigned Tag, StringRef Name),(Tag, Name, 0, 0, 0, 0, FlagZero)) DEFINE_MDNODE_GET(DIBasicType</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a0842b05736a1668538b180f36bb2c7">DEFINE_MDNODE_GET</a> (DIBasicType,(unsigned Tag, MDString *Name, uint64_t SizeInBits),(Tag, Name, SizeInBits, 0, 0, 0, FlagZero)) DEFINE_MDNODE_GET(DIBasicType</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28856b04f8879e8c9cfb2f0ae1ad42f2">DEFINE_MDNODE_GET</a> (DIBasicType,(unsigned Tag, MDString *Name, uint64_t SizeInBits, uint32_t AlignInBits, unsigned Encoding, DIFlags Flags),(Tag, Name, SizeInBits, AlignInBits, Encoding, 0, Flags)) DEFINE_MDNODE_GET(DIBasicType</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned uint32_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ccd730209f28b0d2e70abf2d117ed27">DEFINE_MDNODE_GET</a> (DIBasicType,(unsigned Tag, MDString *Name, uint64_t SizeInBits, uint32_t AlignInBits, unsigned Encoding, uint32_t NumExtraInhabitants, DIFlags Flags),(Tag, Name, SizeInBits, AlignInBits, Encoding, NumExtraInhabitants, Flags)) TempDIBasicType clone() const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc5ec1526159a27a8fa8d975242e445b">getEncoding</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="#a60f94cc0e71193b01ca24ef37de9845a">Signedness</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae1e393d45303ceff9f1eababfa47926">getSignedness</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the signedness of this type, or std::nullopt if this type is neither signed nor unsigned. <a href="#aae1e393d45303ceff9f1eababfa47926">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">TempDIBasicType</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35af12812c29875e143fe21511494238">cloneImpl</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a160b3179f217d73ddb4fd26bada9c1ac">Tag</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6cf2a01db00d64d9fe3b7ad27c40bba">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa67c8171ec9e2b3a0bfa7b035e74bc14">SizeInBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a742ec1af247b25c8d6cffb888078c0b1">Tag</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dcca98cd2696c1ca08cd27941a8bf64">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa87a6d33c0b658a26c06a8eba82df59c">Tag</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa465e9c2035fb42e52bf4f02a08f1c5a">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5096a30360ebcc58fd43ea14ed24ec74">SizeInBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb4ef70b790ca71cb4b8e04fcc62a011">AlignInBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a6389c506acdfe72df947ac28b8e386">Encoding</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a8d6b1806d2134fc9bed860def7d6df">Tag</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bb07f65b0dea6610923f85d54563861">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01e335f7455d8d56715875c6276ccb62">SizeInBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c60bf8bd4066a66089888551b2d201a">AlignInBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f5b796cc2988412fa46e6879e5ac203">Encoding</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea88c3336df816d9f92b9e5c59f37598">Tag</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabb68d1d2679affeb2c047babc56a1e5">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1baa50e4b79398b2e5d840774f7e230b">SizeInBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1cef7a468ab1804c57056ed897c55ee">AlignInBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed3a233bb9da6558ee4623846c581df4">Encoding</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac58745f48a380dad76c17363ac9ffee2">NumExtraInhabitants</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> Flags unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned uint32_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad57aa86ec87420e44e5ec1fd427a04a8">Flags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned uint32_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c017dff637a18b64a8816c6b590878b">Tag</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned uint32_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50b6f97e290dad07f9473b35c6033b01">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned uint32_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26b5e22e43b6b0ac3b271181beb7e6a9">SizeInBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned uint32_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b5483f3256308087fe4da02eb24761b">AlignInBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned uint32_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaacc42ced0507aa41aae3bb2821cdea">Encoding</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t FlagZero unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> uint64_t uint32_t unsigned uint32_t <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73583ef040765ef9a9a0eaa38fd3c559">NumExtraInhabitants</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47d013298d351f0f463ba7f3ae96b6b6">Encoding</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a689315e801724f3c05a04c75e9711fee">classof</a> (const Metadata *MD)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dibasictype">DIBasicType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9afa1d88b4c0e8fcc103d555067e06c0">getImpl</a> (LLVMContext &amp;Context, unsigned Tag, StringRef Name, uint64_t SizeInBits, uint32_t AlignInBits, unsigned Encoding, uint32_t NumExtraInhabitants, DIFlags Flags, StorageType Storage, bool ShouldCreate=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dibasictype">DIBasicType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a2ce59463a24f22a016f8491dbf1e64">getImpl</a> (LLVMContext &amp;Context, unsigned Tag, MDString *Name, uint64_t SizeInBits, uint32_t AlignInBits, unsigned Encoding, uint32_t NumExtraInhabitants, DIFlags Flags, StorageType Storage, bool ShouldCreate=true)</td>
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

<p>Basic type, like 'int' or 'float'.</p>


<p>TODO: Split out DW_TAG_unspecified_type. TODO: Drop unused accessors.</p>


<p>Definition at line 823 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Signedness {#a60f94cc0e71193b01ca24ef37de9845a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::DIBasicType::Signedness </td>
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
<td class="doxyEnumItemName">Signed<a id="a60f94cc0e71193b01ca24ef37de9845aa71fed0c3428bf1a2e19af257c4bac379"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unsigned<a id="a60f94cc0e71193b01ca24ef37de9845aaa1a914735b205424ba6c40b85528d78a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 893 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### LLVMContextImpl {#aa81f87de855d80e4275071841a7e0c83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl">LLVMContextImpl</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 824 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a>.</p>


<p>Referenced by <a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a>.</p>

</div>
</div>

### MDNode {#acf51c34793180f67be514c1d6e4167f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 825 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#adb4ef70b790ca71cb4b8e04fcc62a011">AlignInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a411430e6383606f78f6b5fdd88e3e09e">llvm::DIType::DIType</a>, <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a>, <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>, <a href="#ac58745f48a380dad76c17363ac9ffee2">NumExtraInhabitants</a>, <a href="#aa67c8171ec9e2b3a0bfa7b035e74bc14">SizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a8265bf29997e9e49d47a38a762d4bb0f">llvm::Metadata::Storage</a> and <a href="#a160b3179f217d73ddb4fd26bada9c1ac">Tag</a>.</p>


<p>Referenced by <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### DIBasicType() {#a1a839c7018604b2469c1ac5128468f60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DIBasicType::DIBasicType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, unsigned Tag, uint64_t SizeInBits, uint32_t AlignInBits, unsigned Encoding, uint32_t NumExtraInhabitants, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; Ops)</td>
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



<p>Definition at line 829 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~DIBasicType() {#a6683ab4898c05216627d8ceb6cd67612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DIBasicType::~DIBasicType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 836 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### DEFINE\_MDNODE\_GET() {#aecc478d4d96a5c30f453d2bb726e58ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DIBasicType::DEFINE_MDNODE_GET (<a href="/web-llvm/docs/api/classes/llvm/dibasictype">DIBasicType</a>, (unsigned <a href="#a160b3179f217d73ddb4fd26bada9c1ac">Tag</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="#ad6cf2a01db00d64d9fe3b7ad27c40bba">Name</a>), (<a href="#a160b3179f217d73ddb4fd26bada9c1ac">Tag</a>, <a href="#ad6cf2a01db00d64d9fe3b7ad27c40bba">Name</a>, 0, 0, 0, 0, FlagZero))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 860 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="#ad6cf2a01db00d64d9fe3b7ad27c40bba">Name</a> and <a href="#a160b3179f217d73ddb4fd26bada9c1ac">Tag</a>.</p>


<p>Referenced by <a href="#a7a0842b05736a1668538b180f36bb2c7">DEFINE_MDNODE_GET</a>, <a href="#a28856b04f8879e8c9cfb2f0ae1ad42f2">DEFINE_MDNODE_GET</a> and <a href="#a7ccd730209f28b0d2e70abf2d117ed27">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### DEFINE\_MDNODE\_GET() {#a7a0842b05736a1668538b180f36bb2c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero llvm::DIBasicType::DEFINE_MDNODE_GET (<a href="/web-llvm/docs/api/classes/llvm/dibasictype">DIBasicType</a>, (unsigned <a href="#a160b3179f217d73ddb4fd26bada9c1ac">Tag</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *<a href="#ad6cf2a01db00d64d9fe3b7ad27c40bba">Name</a>, uint64_t <a href="#aa67c8171ec9e2b3a0bfa7b035e74bc14">SizeInBits</a>), (<a href="#a160b3179f217d73ddb4fd26bada9c1ac">Tag</a>, <a href="#ad6cf2a01db00d64d9fe3b7ad27c40bba">Name</a>, <a href="#aa67c8171ec9e2b3a0bfa7b035e74bc14">SizeInBits</a>, 0, 0, 0, FlagZero))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 865 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="#aecc478d4d96a5c30f453d2bb726e58ad">DEFINE_MDNODE_GET</a>, <a href="#ad6cf2a01db00d64d9fe3b7ad27c40bba">Name</a>, <a href="#aa67c8171ec9e2b3a0bfa7b035e74bc14">SizeInBits</a> and <a href="#a160b3179f217d73ddb4fd26bada9c1ac">Tag</a>.</p>

</div>
</div>

### DEFINE\_MDNODE\_GET() {#a28856b04f8879e8c9cfb2f0ae1ad42f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags Flags llvm::DIBasicType::DEFINE_MDNODE_GET (<a href="/web-llvm/docs/api/classes/llvm/dibasictype">DIBasicType</a>, (unsigned <a href="#a160b3179f217d73ddb4fd26bada9c1ac">Tag</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *<a href="#ad6cf2a01db00d64d9fe3b7ad27c40bba">Name</a>, uint64_t <a href="#aa67c8171ec9e2b3a0bfa7b035e74bc14">SizeInBits</a>, uint32_t <a href="#adb4ef70b790ca71cb4b8e04fcc62a011">AlignInBits</a>, unsigned Encoding, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a>), (<a href="#a160b3179f217d73ddb4fd26bada9c1ac">Tag</a>, <a href="#ad6cf2a01db00d64d9fe3b7ad27c40bba">Name</a>, <a href="#aa67c8171ec9e2b3a0bfa7b035e74bc14">SizeInBits</a>, <a href="#adb4ef70b790ca71cb4b8e04fcc62a011">AlignInBits</a>, Encoding, 0, <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a>))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 872 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="#adb4ef70b790ca71cb4b8e04fcc62a011">AlignInBits</a>, <a href="#aecc478d4d96a5c30f453d2bb726e58ad">DEFINE_MDNODE_GET</a>, <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a>, <a href="#ad6cf2a01db00d64d9fe3b7ad27c40bba">Name</a>, <a href="#aa67c8171ec9e2b3a0bfa7b035e74bc14">SizeInBits</a> and <a href="#a160b3179f217d73ddb4fd26bada9c1ac">Tag</a>.</p>

</div>
</div>

### DEFINE\_MDNODE\_GET() {#a7ccd730209f28b0d2e70abf2d117ed27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags Flags unsigned StringRef uint64_t uint32_t unsigned uint32_t DIFlags Flags llvm::DIBasicType::DEFINE_MDNODE_GET (<a href="/web-llvm/docs/api/classes/llvm/dibasictype">DIBasicType</a>, (unsigned <a href="#a160b3179f217d73ddb4fd26bada9c1ac">Tag</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *<a href="#ad6cf2a01db00d64d9fe3b7ad27c40bba">Name</a>, uint64_t <a href="#aa67c8171ec9e2b3a0bfa7b035e74bc14">SizeInBits</a>, uint32_t <a href="#adb4ef70b790ca71cb4b8e04fcc62a011">AlignInBits</a>, unsigned Encoding, uint32_t <a href="#ac58745f48a380dad76c17363ac9ffee2">NumExtraInhabitants</a>, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a>), (<a href="#a160b3179f217d73ddb4fd26bada9c1ac">Tag</a>, <a href="#ad6cf2a01db00d64d9fe3b7ad27c40bba">Name</a>, <a href="#aa67c8171ec9e2b3a0bfa7b035e74bc14">SizeInBits</a>, <a href="#adb4ef70b790ca71cb4b8e04fcc62a011">AlignInBits</a>, Encoding, <a href="#ac58745f48a380dad76c17363ac9ffee2">NumExtraInhabitants</a>, <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a>))</td>
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



<p>Definition at line 882 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="#adb4ef70b790ca71cb4b8e04fcc62a011">AlignInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#aedf9e2987dd95705a56a95d9ba80fd44">llvm::DIType::clone</a>, <a href="#aecc478d4d96a5c30f453d2bb726e58ad">DEFINE_MDNODE_GET</a>, <a href="#a2bf2baedc84f05f3e67a5354edcb1aa0">Flags</a>, <a href="#ad6cf2a01db00d64d9fe3b7ad27c40bba">Name</a>, <a href="#ac58745f48a380dad76c17363ac9ffee2">NumExtraInhabitants</a>, <a href="#aa67c8171ec9e2b3a0bfa7b035e74bc14">SizeInBits</a> and <a href="#a160b3179f217d73ddb4fd26bada9c1ac">Tag</a>.</p>

</div>
</div>

### getEncoding() {#abc5ec1526159a27a8fa8d975242e445b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DIBasicType::getEncoding ()</td>
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



<p>Definition at line 891 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#aae1e393d45303ceff9f1eababfa47926">getSignedness</a>.</p>

</div>
</div>

### getSignedness() {#aae1e393d45303ceff9f1eababfa47926}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DIBasicType::Signedness &gt; DIBasicType::getSignedness ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the signedness of this type, or std::nullopt if this type is neither signed nor unsigned.</p>

<p>Declaration at line 897 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 678 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="#abc5ec1526159a27a8fa8d975242e445b">getEncoding</a>, <a href="#a60f94cc0e71193b01ca24ef37de9845aa71fed0c3428bf1a2e19af257c4bac379">Signed</a> and <a href="#a60f94cc0e71193b01ca24ef37de9845aaa1a914735b205424ba6c40b85528d78a">Unsigned</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### cloneImpl() {#a35af12812c29875e143fe21511494238}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TempDIBasicType llvm::DIBasicType::cloneImpl ()</td>
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



<p>Definition at line 853 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AlignInBits {#adb4ef70b790ca71cb4b8e04fcc62a011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t llvm::DIBasicType::AlignInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 870 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#a28856b04f8879e8c9cfb2f0ae1ad42f2">DEFINE_MDNODE_GET</a>, <a href="#a7ccd730209f28b0d2e70abf2d117ed27">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### AlignInBits {#a1c60bf8bd4066a66089888551b2d201a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags llvm::DIBasicType::AlignInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### AlignInBits {#aa1cef7a468ab1804c57056ed897c55ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags Flags unsigned StringRef uint64_t uint32_t llvm::DIBasicType::AlignInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 878 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### AlignInBits {#a4b5483f3256308087fe4da02eb24761b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags Flags unsigned StringRef uint64_t uint32_t unsigned uint32_t DIFlags llvm::DIBasicType::AlignInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Encoding {#a1a6389c506acdfe72df947ac28b8e386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned llvm::DIBasicType::Encoding</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 870 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Encoding {#a4f5b796cc2988412fa46e6879e5ac203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags llvm::DIBasicType::Encoding</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Encoding {#aed3a233bb9da6558ee4623846c581df4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags Flags unsigned StringRef uint64_t uint32_t unsigned llvm::DIBasicType::Encoding</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 878 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Encoding {#aaaacc42ced0507aa41aae3bb2821cdea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags Flags unsigned StringRef uint64_t uint32_t unsigned uint32_t DIFlags llvm::DIBasicType::Encoding</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Flags {#a2bf2baedc84f05f3e67a5354edcb1aa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags llvm::DIBasicType::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 870 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#a28856b04f8879e8c9cfb2f0ae1ad42f2">DEFINE_MDNODE_GET</a>, <a href="#a7ccd730209f28b0d2e70abf2d117ed27">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### Flags {#ad57aa86ec87420e44e5ec1fd427a04a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags Flags unsigned StringRef uint64_t uint32_t unsigned uint32_t DIFlags llvm::DIBasicType::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 879 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Name {#ad6cf2a01db00d64d9fe3b7ad27c40bba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef llvm::DIBasicType::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 863 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#a7a0842b05736a1668538b180f36bb2c7">DEFINE_MDNODE_GET</a>, <a href="#a28856b04f8879e8c9cfb2f0ae1ad42f2">DEFINE_MDNODE_GET</a>, <a href="#a7ccd730209f28b0d2e70abf2d117ed27">DEFINE_MDNODE_GET</a> and <a href="#aecc478d4d96a5c30f453d2bb726e58ad">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### Name {#a1dcca98cd2696c1ca08cd27941a8bf64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t llvm::DIBasicType::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 864 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Name {#aa465e9c2035fb42e52bf4f02a08f1c5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef llvm::DIBasicType::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 869 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Name {#a6bb07f65b0dea6610923f85d54563861}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags llvm::DIBasicType::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Name {#aabb68d1d2679affeb2c047babc56a1e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags Flags unsigned StringRef llvm::DIBasicType::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 877 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Name {#a50b6f97e290dad07f9473b35c6033b01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags Flags unsigned StringRef uint64_t uint32_t unsigned uint32_t DIFlags llvm::DIBasicType::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### NumExtraInhabitants {#ac58745f48a380dad76c17363ac9ffee2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags Flags unsigned StringRef uint64_t uint32_t unsigned uint32_t llvm::DIBasicType::NumExtraInhabitants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 879 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#a7ccd730209f28b0d2e70abf2d117ed27">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### NumExtraInhabitants {#a73583ef040765ef9a9a0eaa38fd3c559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags Flags unsigned StringRef uint64_t uint32_t unsigned uint32_t DIFlags llvm::DIBasicType::NumExtraInhabitants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 881 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### SizeInBits {#aa67c8171ec9e2b3a0bfa7b035e74bc14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t llvm::DIBasicType::SizeInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 863 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#a7a0842b05736a1668538b180f36bb2c7">DEFINE_MDNODE_GET</a>, <a href="#a28856b04f8879e8c9cfb2f0ae1ad42f2">DEFINE_MDNODE_GET</a>, <a href="#a7ccd730209f28b0d2e70abf2d117ed27">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### SizeInBits {#a5096a30360ebcc58fd43ea14ed24ec74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t llvm::DIBasicType::SizeInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 869 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### SizeInBits {#a01e335f7455d8d56715875c6276ccb62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags llvm::DIBasicType::SizeInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### SizeInBits {#a1baa50e4b79398b2e5d840774f7e230b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags Flags unsigned StringRef uint64_t llvm::DIBasicType::SizeInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 877 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### SizeInBits {#a26b5e22e43b6b0ac3b271181beb7e6a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags Flags unsigned StringRef uint64_t uint32_t unsigned uint32_t DIFlags llvm::DIBasicType::SizeInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Tag {#a160b3179f217d73ddb4fd26bada9c1ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DIBasicType::Tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 863 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#a7a0842b05736a1668538b180f36bb2c7">DEFINE_MDNODE_GET</a>, <a href="#a28856b04f8879e8c9cfb2f0ae1ad42f2">DEFINE_MDNODE_GET</a>, <a href="#a7ccd730209f28b0d2e70abf2d117ed27">DEFINE_MDNODE_GET</a>, <a href="#aecc478d4d96a5c30f453d2bb726e58ad">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### Tag {#a742ec1af247b25c8d6cffb888078c0b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t llvm::DIBasicType::Tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 864 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Tag {#aa87a6d33c0b658a26c06a8eba82df59c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned llvm::DIBasicType::Tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 869 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Tag {#a4a8d6b1806d2134fc9bed860def7d6df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags llvm::DIBasicType::Tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Tag {#aea88c3336df816d9f92b9e5c59f37598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags Flags unsigned llvm::DIBasicType::Tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 877 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Tag {#a9c017dff637a18b64a8816c6b590878b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef uint64_t FlagZero unsigned StringRef uint64_t uint32_t unsigned DIFlags Flags unsigned StringRef uint64_t uint32_t unsigned uint32_t DIFlags llvm::DIBasicType::Tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Encoding {#a47d013298d351f0f463ba7f3ae96b6b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DIBasicType::Encoding</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 827 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a689315e801724f3c05a04c75e9711fee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIBasicType::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD)</td>
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



<p>Definition at line 899 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/metadata/#a91c7b9c7cf6694f41b9030429b582d26">llvm::Metadata::getMetadataID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getImpl() {#a9afa1d88b4c0e8fcc103d555067e06c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIBasicType * llvm::DIBasicType::getImpl (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, unsigned Tag, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, uint64_t SizeInBits, uint32_t AlignInBits, unsigned Encoding, uint32_t NumExtraInhabitants, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, bool ShouldCreate=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 838 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### getImpl() {#a9a2ce59463a24f22a016f8491dbf1e64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIBasicType * DIBasicType::getImpl (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, unsigned Tag, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> * Name, uint64_t SizeInBits, uint32_t AlignInBits, unsigned Encoding, uint32_t NumExtraInhabitants, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, bool ShouldCreate=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Declaration at line 847 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
