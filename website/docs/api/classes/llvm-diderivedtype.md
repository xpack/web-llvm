---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/diderivedtype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DIDerivedType` Class Reference

<p>Derived types. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DIDerivedType { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6714ee0506d6c17745ef9c8d049829a3">DIDerivedType</a> (LLVMContext &amp;C, StorageType Storage, unsigned Tag, unsigned Line, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, std::optional&lt; unsigned &gt; DWARFAddressSpace, std::optional&lt; PtrAuthData &gt; PtrAuthData, DIFlags Flags, ArrayRef&lt; Metadata * &gt; Ops)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2141727ed9113dd998adf39e7d1e227d">~DIDerivedType</a> ()=default</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96a5b6b38b0bd7fe53281082a68611dc">getClassType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get casted version of extra data. <a href="#a96a5b6b38b0bd7fe53281082a68611dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diobjcproperty">DIObjCProperty</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a740de4fd1a1f33cb8628f05c6d671e48">getObjCProperty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf477efc81cd723c2a0e00b3351d24c5">getVBPtrOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa924fdc8fde7c2b788ef157359638ec">getStorageOffsetInBits</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa537b7354f39b1d60795fde760509c7d">getConstant</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae8b365a9d5d34301a15932ab06e104a">getDiscriminantValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa8e1515ffb027f5c60e69e1f4d08427">DEFINE_MDNODE_GET</a> (DIDerivedType,(unsigned Tag, MDString *Name, Metadata *File, unsigned Line, Metadata *Scope, Metadata *BaseType, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, std::optional&lt; unsigned &gt; DWARFAddressSpace, std::optional&lt; PtrAuthData &gt; PtrAuthData, DIFlags Flags, Metadata *ExtraData=nullptr, Metadata *Annotations=nullptr),(Tag, Name, File, Line, Scope, BaseType, SizeInBits, AlignInBits, OffsetInBits, DWARFAddressSpace, PtrAuthData, Flags, ExtraData, Annotations)) DEFINE_MDNODE_GET(DIDerivedType</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aa8d2a14a45d52fef32eb2f3fe0f073">getExtraData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get extra data associated with this derived type. <a href="#a4aa8d2a14a45d52fef32eb2f3fe0f073">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08937f759c0f8d8fe1700ca954a6c870">getRawExtraData</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">DITemplateParameterArray</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6958b4347de68daebb83d4e9e08ed7dc">getTemplateParams</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the template parameters from a template alias. <a href="#a6958b4347de68daebb83d4e9e08ed7dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DINodeArray</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a328b5fa23bf0c532750c9526233526f4">getAnnotations</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get annotations associated with this derived type. <a href="#a328b5fa23bf0c532750c9526233526f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bde68a5c4fca1abcda41554e3a944c1">getRawAnnotations</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">TempDIDerivedType</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a457c45ec55daae36b7045f1e451046fd">cloneImpl</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02bcf6f579ac6e042dd998e0a9211497">Tag</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1f54f3f4b7451da48ec4d7096f6ed1c">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a699e42182b114cf61063fce7dfce2b4a">File</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af15294f245b09c4f60c9c9f15176e1f0">Line</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83d339189080a1ed454e1f558a5d1c9d">Scope</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f7669414c95013716416fd1a154b22e">BaseType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a479f85ff0891fdbc2e13c80e7379ab4b">SizeInBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> uint64_t uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7be8152918c006dc7427b0054747921d">AlignInBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> uint64_t uint32_t uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a727071dbc6a625895be2799f075ea80d">OffsetInBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> uint64_t uint32_t uint64_t std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace41d52b1a070205786bcb0ab1533237">DWARFAddressSpace</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> uint64_t uint32_t uint64_t std::optional&lt; unsigned &gt; std::optional&lt; PtrAuthData &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d46e43aa0575471db4a39049c9eca0d">PtrAuthData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> uint64_t uint32_t uint64_t std::optional&lt; unsigned &gt; std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/diderivedtype/ptrauthdata">PtrAuthData</a> &gt; <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8adc31b129090e085b90f3f9467e61f">Flags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> uint64_t uint32_t uint64_t std::optional&lt; unsigned &gt; std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/diderivedtype/ptrauthdata">PtrAuthData</a> &gt; <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4458933155ed1a171f1e0c1e6a741996">ExtraData</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> unsigned <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> uint64_t uint32_t uint64_t std::optional&lt; unsigned &gt; std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/diderivedtype/ptrauthdata">PtrAuthData</a> &gt; <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> DINodeArray</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e95ddd886443a5191143791b087023d">Annotations</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acac5954c1b95c8e8b2a0d47aafb3ebbe">DWARFAddressSpace</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The DWARF address space of the memory pointed to or referenced by a pointer or reference type respectively. <a href="#acac5954c1b95c8e8b2a0d47aafb3ebbe">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d9c3bc1a502fc402826f48e4f76046c">classof</a> (const Metadata *MD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55c9f75920e744406b2e7b4bf78bac69">getImpl</a> (LLVMContext &amp;Context, unsigned Tag, StringRef Name, DIFile *File, unsigned Line, DIScope *Scope, DIType *BaseType, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, std::optional&lt; unsigned &gt; DWARFAddressSpace, std::optional&lt; PtrAuthData &gt; PtrAuthData, DIFlags Flags, Metadata *ExtraData, DINodeArray Annotations, StorageType Storage, bool ShouldCreate=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad24ec341d78d05f3c7777fc5f71f9ce5">getImpl</a> (LLVMContext &amp;Context, unsigned Tag, MDString *Name, Metadata *File, unsigned Line, Metadata *Scope, Metadata *BaseType, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, std::optional&lt; unsigned &gt; DWARFAddressSpace, std::optional&lt; PtrAuthData &gt; PtrAuthData, DIFlags Flags, Metadata *ExtraData, Metadata *Annotations, StorageType Storage, bool ShouldCreate=true)</td>
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

<p>Derived types.</p>


<p>This includes qualified types, pointers, references, friends, typedefs, and class members.</p>


<p>TODO: Split out members (inheritance, fields, methods, etc.).</p>


<p>Definition at line 997 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


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


<p>Definition at line 1027 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


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


<p>Definition at line 1028 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#a7be8152918c006dc7427b0054747921d">AlignInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a411430e6383606f78f6b5fdd88e3e09e">llvm::DIType::DIType</a>, <a href="#ae8adc31b129090e085b90f3f9467e61f">Flags</a>, <a href="#af15294f245b09c4f60c9c9f15176e1f0">Line</a>, <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>, <a href="#a727071dbc6a625895be2799f075ea80d">OffsetInBits</a>, <a href="#a479f85ff0891fdbc2e13c80e7379ab4b">SizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a8265bf29997e9e49d47a38a762d4bb0f">llvm::Metadata::Storage</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a77e771a2105567c5db8a9a74f7bb9da3">llvm::Metadata::SubclassData32</a> and <a href="#a02bcf6f579ac6e042dd998e0a9211497">Tag</a>.</p>


<p>Referenced by <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### DIDerivedType() {#a6714ee0506d6c17745ef9c8d049829a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DIDerivedType::DIDerivedType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, unsigned Tag, unsigned Line, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, std::optional&lt; unsigned &gt; DWARFAddressSpace, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/diderivedtype/ptrauthdata">PtrAuthData</a> &gt; PtrAuthData, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; Ops)</td>
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



<p>Definition at line 1034 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~DIDerivedType() {#a2141727ed9113dd998adf39e7d1e227d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DIDerivedType::~DIDerivedType ()</td>
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



<p>Definition at line 1046 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getClassType() {#a96a5b6b38b0bd7fe53281082a68611dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIType * DIDerivedType::getClassType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get casted version of extra data.</p>

<p>Declaration at line 1140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 707 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a411430e6383606f78f6b5fdd88e3e09e">llvm::DIType::DIType</a>, <a href="#a4aa8d2a14a45d52fef32eb2f3fe0f073">getExtraData</a> and <a href="/web-llvm/docs/api/classes/llvm/dinode/#a13471a1f55ae60d82d774585bfd3c5da">llvm::DINode::getTag</a>.</p>

</div>
</div>

### getConstant() {#aa537b7354f39b1d60795fde760509c7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * DIDerivedType::getConstant ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="#a4aa8d2a14a45d52fef32eb2f3fe0f073">getExtraData</a>, <a href="/web-llvm/docs/api/classes/llvm/dinode/#a13471a1f55ae60d82d774585bfd3c5da">llvm::DINode::getTag</a> and <a href="/web-llvm/docs/api/classes/llvm/ditype/#a31a8c0c7f286507d2b228429f6bc36c7">llvm::DIType::isStaticMember</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#acc3268e4df66097512cb6b4b87b438d4">llvm::DwarfUnit::getOrCreateStaticMemberDIE</a>.</p>

</div>
</div>

### getDiscriminantValue() {#aae8b365a9d5d34301a15932ab06e104a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * DIDerivedType::getDiscriminantValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 733 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="#a4aa8d2a14a45d52fef32eb2f3fe0f073">getExtraData</a>, <a href="/web-llvm/docs/api/classes/llvm/dinode/#a13471a1f55ae60d82d774585bfd3c5da">llvm::DINode::getTag</a> and <a href="/web-llvm/docs/api/classes/llvm/ditype/#a31a8c0c7f286507d2b228429f6bc36c7">llvm::DIType::isStaticMember</a>.</p>

</div>
</div>

### getObjCProperty() {#a740de4fd1a1f33cb8628f05c6d671e48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIObjCProperty * llvm::DIDerivedType::getObjCProperty ()</td>
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



<p>Definition at line 1142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="#a4aa8d2a14a45d52fef32eb2f3fe0f073">getExtraData</a>.</p>

</div>
</div>

### getStorageOffsetInBits() {#aaa924fdc8fde7c2b788ef157359638ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * DIDerivedType::getStorageOffsetInBits ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 718 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="#a4aa8d2a14a45d52fef32eb2f3fe0f073">getExtraData</a>, <a href="/web-llvm/docs/api/classes/llvm/dinode/#a13471a1f55ae60d82d774585bfd3c5da">llvm::DINode::getTag</a> and <a href="/web-llvm/docs/api/classes/llvm/ditype/#a293fde7dd669a4357ec82df74d685f9b">llvm::DIType::isBitField</a>.</p>

</div>
</div>

### getVBPtrOffset() {#abf477efc81cd723c2a0e00b3351d24c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t DIDerivedType::getVBPtrOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 711 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#a4aa8d2a14a45d52fef32eb2f3fe0f073">getExtraData</a> and <a href="/web-llvm/docs/api/classes/llvm/dinode/#a13471a1f55ae60d82d774585bfd3c5da">llvm::DINode::getTag</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### DEFINE\_MDNODE\_GET() {#afa8e1515ffb027f5c60e69e1f4d08427}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DIDerivedType::DEFINE_MDNODE_GET (<a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a>, (unsigned <a href="#a02bcf6f579ac6e042dd998e0a9211497">Tag</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *<a href="#ab1f54f3f4b7451da48ec4d7096f6ed1c">Name</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#a699e42182b114cf61063fce7dfce2b4a">File</a>, unsigned <a href="#af15294f245b09c4f60c9c9f15176e1f0">Line</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#a83d339189080a1ed454e1f558a5d1c9d">Scope</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ae96315ee246bd4a509133af84c88c5e1">BaseType</a>, uint64_t <a href="#a479f85ff0891fdbc2e13c80e7379ab4b">SizeInBits</a>, uint32_t <a href="#a7be8152918c006dc7427b0054747921d">AlignInBits</a>, uint64_t <a href="#a727071dbc6a625895be2799f075ea80d">OffsetInBits</a>, std::optional&lt; unsigned &gt; DWARFAddressSpace, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/diderivedtype/ptrauthdata">PtrAuthData</a> &gt; <a href="/web-llvm/docs/api/structs/llvm/diderivedtype/ptrauthdata">PtrAuthData</a>, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> <a href="#ae8adc31b129090e085b90f3f9467e61f">Flags</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="#a4458933155ed1a171f1e0c1e6a741996">ExtraData</a>=nullptr, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *<a href="/web-llvm/docs/api/classes/llvm/annotations">Annotations</a>=nullptr), (<a href="#a02bcf6f579ac6e042dd998e0a9211497">Tag</a>, <a href="#ab1f54f3f4b7451da48ec4d7096f6ed1c">Name</a>, <a href="#a699e42182b114cf61063fce7dfce2b4a">File</a>, <a href="#af15294f245b09c4f60c9c9f15176e1f0">Line</a>, <a href="#a83d339189080a1ed454e1f558a5d1c9d">Scope</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ae96315ee246bd4a509133af84c88c5e1">BaseType</a>, <a href="#a479f85ff0891fdbc2e13c80e7379ab4b">SizeInBits</a>, <a href="#a7be8152918c006dc7427b0054747921d">AlignInBits</a>, <a href="#a727071dbc6a625895be2799f075ea80d">OffsetInBits</a>, DWARFAddressSpace, <a href="/web-llvm/docs/api/structs/llvm/diderivedtype/ptrauthdata">PtrAuthData</a>, <a href="#ae8adc31b129090e085b90f3f9467e61f">Flags</a>, <a href="#a4458933155ed1a171f1e0c1e6a741996">ExtraData</a>, <a href="/web-llvm/docs/api/classes/llvm/annotations">Annotations</a>))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1078 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="#a7be8152918c006dc7427b0054747921d">AlignInBits</a>, <a href="#a4e95ddd886443a5191143791b087023d">Annotations</a>, <a href="#a0f7669414c95013716416fd1a154b22e">BaseType</a>, <a href="#a4458933155ed1a171f1e0c1e6a741996">ExtraData</a>, <a href="#a699e42182b114cf61063fce7dfce2b4a">File</a>, <a href="#ae8adc31b129090e085b90f3f9467e61f">Flags</a>, <a href="#af15294f245b09c4f60c9c9f15176e1f0">Line</a>, <a href="#ab1f54f3f4b7451da48ec4d7096f6ed1c">Name</a>, <a href="#a727071dbc6a625895be2799f075ea80d">OffsetInBits</a>, <a href="#a83d339189080a1ed454e1f558a5d1c9d">Scope</a>, <a href="#a479f85ff0891fdbc2e13c80e7379ab4b">SizeInBits</a> and <a href="#a02bcf6f579ac6e042dd998e0a9211497">Tag</a>.</p>

</div>
</div>

### getAnnotations() {#a328b5fa23bf0c532750c9526233526f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DINodeArray llvm::DIDerivedType::getAnnotations ()</td>
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

<p>Get annotations associated with this derived type.</p>

<p>Definition at line 1133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a> and <a href="#a8bde68a5c4fca1abcda41554e3a944c1">getRawAnnotations</a>.</p>

</div>
</div>

### getExtraData() {#a4aa8d2a14a45d52fef32eb2f3fe0f073}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DIDerivedType::getExtraData ()</td>
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

<p>Get extra data associated with this derived type.</p>


<p>Class type for pointer-to-members, objective-c property node for ivars, global constant wrapper for static members, virtual base pointer offset for inheritance, or a tuple of template parameters for template aliases.</p>


<p>TODO: Separate out types that need this extra operand: pointer-to-member types and member fields (static members and ivars).</p>


<p>Definition at line 1124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="#a08937f759c0f8d8fe1700ca954a6c870">getRawExtraData</a>.</p>


<p>Referenced by <a href="#a96a5b6b38b0bd7fe53281082a68611dc">getClassType</a>, <a href="#aa537b7354f39b1d60795fde760509c7d">getConstant</a>, <a href="#aae8b365a9d5d34301a15932ab06e104a">getDiscriminantValue</a>, <a href="#a740de4fd1a1f33cb8628f05c6d671e48">getObjCProperty</a>, <a href="#aaa924fdc8fde7c2b788ef157359638ec">getStorageOffsetInBits</a>, <a href="#a6958b4347de68daebb83d4e9e08ed7dc">getTemplateParams</a> and <a href="#abf477efc81cd723c2a0e00b3351d24c5">getVBPtrOffset</a>.</p>

</div>
</div>

### getRawAnnotations() {#a8bde68a5c4fca1abcda41554e3a944c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DIDerivedType::getRawAnnotations ()</td>
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



<p>Definition at line 1136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="#a328b5fa23bf0c532750c9526233526f4">getAnnotations</a>.</p>

</div>
</div>

### getRawExtraData() {#a08937f759c0f8d8fe1700ca954a6c870}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::DIDerivedType::getRawExtraData ()</td>
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



<p>Definition at line 1125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="#a4aa8d2a14a45d52fef32eb2f3fe0f073">getExtraData</a>.</p>

</div>
</div>

### getTemplateParams() {#a6958b4347de68daebb83d4e9e08ed7dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DITemplateParameterArray llvm::DIDerivedType::getTemplateParams ()</td>
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

<p>Get the template parameters from a template alias.</p>

<p>Definition at line 1128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a> and <a href="#a4aa8d2a14a45d52fef32eb2f3fe0f073">getExtraData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### cloneImpl() {#a457c45ec55daae36b7045f1e451046fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TempDIDerivedType llvm::DIDerivedType::cloneImpl ()</td>
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



<p>Definition at line 1069 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AlignInBits {#a7be8152918c006dc7427b0054747921d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef DIFile unsigned DIScope DIType uint64_t uint32_t llvm::DIDerivedType::AlignInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1093 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#afa8e1515ffb027f5c60e69e1f4d08427">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### Annotations {#a4e95ddd886443a5191143791b087023d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef DIFile unsigned DIScope DIType uint64_t uint32_t uint64_t std::optional&lt;unsigned&gt; std::optional&lt;PtrAuthData&gt; DIFlags Metadata DINodeArray llvm::DIDerivedType::Annotations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= nullptr),
                    (<a href="#a02bcf6f579ac6e042dd998e0a9211497">Tag</a>, <a href="#ab1f54f3f4b7451da48ec4d7096f6ed1c">Name</a>, <a href="#a699e42182b114cf61063fce7dfce2b4a">File</a>, <a href="#af15294f245b09c4f60c9c9f15176e1f0">Line</a>, <a href="#a83d339189080a1ed454e1f558a5d1c9d">Scope</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ae96315ee246bd4a509133af84c88c5e1">BaseType</a>, <a href="#a479f85ff0891fdbc2e13c80e7379ab4b">SizeInBits</a>,
                     <a href="#a7be8152918c006dc7427b0054747921d">AlignInBits</a>, <a href="#a727071dbc6a625895be2799f075ea80d">OffsetInBits</a>, DWARFAddressSpace, <a href="/web-llvm/docs/api/structs/llvm/diderivedtype/ptrauthdata">PtrAuthData</a>,
                     <a href="#ae8adc31b129090e085b90f3f9467e61f">Flags</a>, <a href="#a4458933155ed1a171f1e0c1e6a741996">ExtraData</a>, <a href="/web-llvm/docs/api/classes/llvm/annotations">Annotations</a>))
  TempDIDerivedType <a href="/web-llvm/docs/api/classes/llvm/ditype/#aedf9e2987dd95705a56a95d9ba80fd44">clone</a>() <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> { return cloneImpl(); }
  <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> *<a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#aa831f0a1520a405a32196cb32ec24084">getBaseType</a>() <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> { return <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">cast_or_null</a>&lt;<a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a>&gt;(getRawBaseType()); }
  <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *getRawBaseType() <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> { return <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">getOperand</a>(3); }
  std::optional&lt;unsigned&gt; getDWARFAddressSpace() <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> {
    return DWARFAddressSpace;
  }
  std::optional&lt;<a href="/web-llvm/docs/api/structs/llvm/diderivedtype/ptrauthdata">PtrAuthData</a>&gt; getPtrAuthData() <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>
</div>
</dd>
</dl>

<p>Definition at line 1097 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#afa8e1515ffb027f5c60e69e1f4d08427">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### BaseType {#a0f7669414c95013716416fd1a154b22e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef DIFile unsigned DIScope DIType* llvm::DIDerivedType::BaseType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1092 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#afa8e1515ffb027f5c60e69e1f4d08427">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### DWARFAddressSpace {#ace41d52b1a070205786bcb0ab1533237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef DIFile unsigned DIScope DIType uint64_t uint32_t uint64_t std::optional&lt;unsigned&gt; llvm::DIDerivedType::DWARFAddressSpace</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1094 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### ExtraData {#a4458933155ed1a171f1e0c1e6a741996}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef DIFile unsigned DIScope DIType uint64_t uint32_t uint64_t std::optional&lt;unsigned&gt; std::optional&lt;PtrAuthData&gt; DIFlags Metadata* llvm::DIDerivedType::ExtraData = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1096 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#afa8e1515ffb027f5c60e69e1f4d08427">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### File {#a699e42182b114cf61063fce7dfce2b4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef DIFile* llvm::DIDerivedType::File</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1091 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#afa8e1515ffb027f5c60e69e1f4d08427">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### Flags {#ae8adc31b129090e085b90f3f9467e61f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef DIFile unsigned DIScope DIType uint64_t uint32_t uint64_t std::optional&lt;unsigned&gt; std::optional&lt;PtrAuthData&gt; DIFlags llvm::DIDerivedType::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1095 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#afa8e1515ffb027f5c60e69e1f4d08427">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### Line {#af15294f245b09c4f60c9c9f15176e1f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef DIFile unsigned llvm::DIDerivedType::Line</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1091 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#afa8e1515ffb027f5c60e69e1f4d08427">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### Name {#ab1f54f3f4b7451da48ec4d7096f6ed1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef llvm::DIDerivedType::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1091 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#afa8e1515ffb027f5c60e69e1f4d08427">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### OffsetInBits {#a727071dbc6a625895be2799f075ea80d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef DIFile unsigned DIScope DIType uint64_t uint32_t uint64_t llvm::DIDerivedType::OffsetInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1093 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#afa8e1515ffb027f5c60e69e1f4d08427">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### PtrAuthData {#a6d46e43aa0575471db4a39049c9eca0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef DIFile unsigned DIScope DIType uint64_t uint32_t uint64_t std::optional&lt;unsigned&gt; std::optional&lt;PtrAuthData&gt; llvm::DIDerivedType::PtrAuthData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1095 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Scope {#a83d339189080a1ed454e1f558a5d1c9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef DIFile unsigned DIScope* llvm::DIDerivedType::Scope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1092 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#afa8e1515ffb027f5c60e69e1f4d08427">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### SizeInBits {#a479f85ff0891fdbc2e13c80e7379ab4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StringRef DIFile unsigned DIScope DIType uint64_t llvm::DIDerivedType::SizeInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1092 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#afa8e1515ffb027f5c60e69e1f4d08427">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### Tag {#a02bcf6f579ac6e042dd998e0a9211497}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DIDerivedType::Tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1091 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#afa8e1515ffb027f5c60e69e1f4d08427">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DWARFAddressSpace {#acac5954c1b95c8e8b2a0d47aafb3ebbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;unsigned&gt; llvm::DIDerivedType::DWARFAddressSpace</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The DWARF address space of the memory pointed to or referenced by a pointer or reference type respectively.</p>

<p>Definition at line 1032 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a9d9c3bc1a502fc402826f48e4f76046c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DIDerivedType::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD)</td>
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



<p>Definition at line 1155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/metadata/#a91c7b9c7cf6694f41b9030429b582d26">llvm::Metadata::getMetadataID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getImpl() {#a55c9f75920e744406b2e7b4bf78bac69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDerivedType * llvm::DIDerivedType::getImpl (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, unsigned Tag, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * File, unsigned Line, <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * BaseType, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, std::optional&lt; unsigned &gt; DWARFAddressSpace, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/diderivedtype/ptrauthdata">PtrAuthData</a> &gt; PtrAuthData, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * ExtraData, DINodeArray Annotations, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, bool ShouldCreate=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 1048 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### getImpl() {#ad24ec341d78d05f3c7777fc5f71f9ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIDerivedType * DIDerivedType::getImpl (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, unsigned Tag, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> * Name, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * File, unsigned Line, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * BaseType, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, std::optional&lt; unsigned &gt; DWARFAddressSpace, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/diderivedtype/ptrauthdata">PtrAuthData</a> &gt; PtrAuthData, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aded082f50ef7ec8cbcd27f2b0dec28a9">DIFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * ExtraData, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Annotations, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, bool ShouldCreate=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Declaration at line 1061 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 740 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
