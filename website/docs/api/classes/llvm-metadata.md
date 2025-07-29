---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/metadata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Metadata` Class

<p>Root of the metadata hierarchy. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::Metadata { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diarglist">DIArgList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata">ValueAsMetadata</a>, to be used as an argument to a dbg.value intrinsic. <a href="/web-llvm/docs/api/classes/llvm/diarglist/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/distinctmdoperandplaceholder">DistinctMDOperandPlaceholder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Placeholder metadata for operands of distinct MDNodes. <a href="/web-llvm/docs/api/classes/llvm/distinctmdoperandplaceholder/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> node. <a href="/web-llvm/docs/api/classes/llvm/mdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A single uniqued string. <a href="/web-llvm/docs/api/classes/llvm/mdstring/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valueasmetadata">ValueAsMetadata</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> wrapper in the <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> hierarchy. <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">StorageType { <a href="#a3f931bc86bd57cd5ea0f53528ae88f80">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Active type of storage. <a href="#a3f931bc86bd57cd5ea0f53528ae88f80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MetadataKind { <a href="#af9aae2fe3abf1dd134799c030c73cd8c">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e487c1ea4559300508da2e4789fb763">ReplaceableMetadataImpl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac265aa582f1e66e4e45d6a964b9bd303">Metadata</a> (unsigned ID, StorageType Storage)</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78baef6c2b2bc4a6a5fcb40817f012af">~Metadata</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedf06cf00de1efbdc1a745946d533b4f">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>User-friendly dump. <a href="#aedf06cf00de1efbdc1a745946d533b4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a729103ecdea80ee058ef426cb4e0bf5a">dump</a> (const Module *M) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a451513f65fe632b0369c9f016117263f">print</a> (raw_ostream &amp;OS, const Module *M=nullptr, bool IsForDebug=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print. <a href="#a451513f65fe632b0369c9f016117263f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af19061fd60c2e268172ccc93ab3f5449">print</a> (raw_ostream &amp;OS, ModuleSlotTracker &amp;MST, const Module *M=nullptr, bool IsForDebug=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abea60f56bef2a0f9437eed8c8bb9ec58">printAsOperand</a> (raw_ostream &amp;OS, const Module *M=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print as operand. <a href="#abea60f56bef2a0f9437eed8c8bb9ec58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1266599a812617ff001dab4a94eb4a62">printAsOperand</a> (raw_ostream &amp;OS, ModuleSlotTracker &amp;MST, const Module *M=nullptr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91c7b9c7cf6694f41b9030429b582d26">getMetadataID</a> () const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a026cd28d293ce28bf5982ea6d15aaf00">handleChangedOperand</a> (void *, Metadata *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default handling of a changed operand, which asserts. <a href="#a026cd28d293ce28bf5982ea6d15aaf00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8265bf29997e9e49d47a38a762d4bb0f">Storage</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Storage flag for non-uniqued, otherwise unowned, metadata. <a href="#a8265bf29997e9e49d47a38a762d4bb0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc1edd99ba896e4a2dae82f7b1a750e2">SubclassData1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72ff55650cd3d97745402a6cb76c1b3e">SubclassData16</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77e771a2105567c5db8a9a74f7bb9da3">SubclassData32</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34f35ce0405bc76111e79d2ef41e6139">SubclassID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RTTI. <a href="#a34f35ce0405bc76111e79d2ef41e6139">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58d89444e861edbf2a966fd172480aac">PoisonGeneratingIDs</a>[] = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> IDs that may generate poison. <a href="#a58d89444e861edbf2a966fd172480aac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Root of the metadata hierarchy.</p>


<p>This is a root class for typeless data in the IR.</p>


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### MetadataKind {#af9aae2fe3abf1dd134799c030c73cd8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Metadata::MetadataKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

### StorageType {#a3f931bc86bd57cd5ea0f53528ae88f80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Metadata::StorageType </td>
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

<p>Active type of storage.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Uniqued<a id="a3f931bc86bd57cd5ea0f53528ae88f80a61241884137094280e36b31589c2b6ba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Distinct<a id="a3f931bc86bd57cd5ea0f53528ae88f80a371ec05b3e6903fb1dcad8a46bae5d38"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Temporary<a id="a3f931bc86bd57cd5ea0f53528ae88f80ab9ea9db2d2364aa9b1377cb220f4ddf2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### ReplaceableMetadataImpl {#a8e487c1ea4559300508da2e4789fb763}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/replaceablemetadataimpl">ReplaceableMetadataImpl</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="#a8e487c1ea4559300508da2e4789fb763">ReplaceableMetadataImpl</a>.</p>


<p>Referenced by <a href="#a8e487c1ea4559300508da2e4789fb763">ReplaceableMetadataImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### Metadata() {#ac265aa582f1e66e4e45d6a964b9bd303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Metadata::Metadata (unsigned ID, <a href="#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="#a8265bf29997e9e49d47a38a762d4bb0f">Storage</a> and <a href="#abc1edd99ba896e4a2dae82f7b1a750e2">SubclassData1</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diarglist/#a4b0f2da357ab396e090804a59bac0d76">llvm::DIArgList::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a8343692ff9294e7f1e33bdc9f7e82afc">llvm::MDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#a78dc01a1546e4f8b88d378910889b5a6">llvm::MDString::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#aa43667dba0fa5fec06e81ca2bb7fef75">llvm::ValueAsMetadata::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/distinctmdoperandplaceholder/#af6749770ad338c5719e1f3602bd8b5ea">llvm::DistinctMDOperandPlaceholder::DistinctMDOperandPlaceholder</a>, <a href="/web-llvm/docs/api/classes/llvm/diarglist/#a262bd33fc97cc729eb9418cc281dc69d">llvm::DIArgList::handleChangedOperand</a>, <a href="#a026cd28d293ce28bf5982ea6d15aaf00">handleChangedOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#acdbfda46c9837123ef7143244fc1f904">llvm::MDNode::intersect</a>, <a href="/web-llvm/docs/api/classes/llvm/diarglist/#aa81f87de855d80e4275071841a7e0c83">llvm::DIArgList::LLVMContextImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa62a8f06c7c38176942b29855f33ddbc">llvm::MDNode::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/distinctmdoperandplaceholder/#a015198d4eb305d0da10bbc6240d66cc3">llvm::DistinctMDOperandPlaceholder::MetadataTracking</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a2e9fe39301fbac7276c8d9f3e1884dc2">llvm::MDNode::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a3011a4758b31e15d77951d24386c68bf">llvm::ValueAsMetadata::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a160e9e1a4fd597f83034c8b2ba316984">llvm::MDNode::replaceOperandWith</a>, <a href="/web-llvm/docs/api/classes/llvm/distinctmdoperandplaceholder/#a00aa234931f09b9795007fe1cf69d7fc">llvm::DistinctMDOperandPlaceholder::replaceUseWith</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#abfa8b6d71b4325aa92a1f18cc566cfeb">llvm::MDNode::setOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#ae699a35dd5340fd282eac36e1456f36a">llvm::ValueAsMetadata::ValueAsMetadata</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~Metadata() {#a78baef6c2b2bc4a6a5fcb40817f012af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Metadata::~Metadata ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### dump() {#aedf06cf00de1efbdc1a745946d533b4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void Metadata::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>User-friendly dump.</p>


<p>If <span class="doxyComputerOutput">M</span> is provided, metadata nodes will be numbered canonically; otherwise, pointer addresses are substituted.</p>


<p>Note: this uses an explicit overload instead of default arguments so that the nullptr version is easy to call from a debugger.</p>


<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 5337 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a03503773241005f01b090b9862aad304">llvm::dump</a> and <a href="#aedf06cf00de1efbdc1a745946d533b4f">dump</a>.</p>


<p>Referenced by <a href="#aedf06cf00de1efbdc1a745946d533b4f">dump</a>, <a href="#a729103ecdea80ee058ef426cb4e0bf5a">dump</a> and <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a68cdc2666693dffb9173a9dffee11ab8">llvm::SDValue::dump</a>.</p>

</div>
</div>

### dump() {#a729103ecdea80ee058ef426cb4e0bf5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void Metadata::dump (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 5340 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#aedf06cf00de1efbdc1a745946d533b4f">dump</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>

</div>
</div>

### print() {#a451513f65fe632b0369c9f016117263f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Metadata::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M=nullptr, bool IsForDebug=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print.</p>


<p>Prints definition of <span class="doxyComputerOutput">this</span>.</p>


<p>If <span class="doxyComputerOutput">M</span> is provided, metadata nodes will be numbered canonically; otherwise, pointer addresses are substituted.</p>


<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 5260 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a451513f65fe632b0369c9f016117263f">print</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a2c3485cc2e63a9ea902dccf6dc02a555">printMetadataImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7bb2458a66268cd58b9cd2460c6f7bd2">llvm::operator&lt;&lt;</a>, <a href="#a451513f65fe632b0369c9f016117263f">print</a>, <a href="#af19061fd60c2e268172ccc93ab3f5449">print</a>, <a href="/web-llvm/docs/api/classes/llvm/valueenumerator/#abbd8654ef76eb2b675637bfb413b3206">llvm::ValueEnumerator::print</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resources/#aeccc967338a23aaf0392de3d0b84bdd3">llvm::dxil::Resources::printCBuffers</a> and <a href="/web-llvm/docs/api/classes/llvm/dxil/resources/#adcb0a0862be18e7a3f204477d1c37262">llvm::dxil::Resources::printUAVs</a>.</p>

</div>
</div>

### print() {#af19061fd60c2e268172ccc93ab3f5449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Metadata::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M=nullptr, bool IsForDebug=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 5266 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#a451513f65fe632b0369c9f016117263f">print</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a2c3485cc2e63a9ea902dccf6dc02a555">printMetadataImpl</a>.</p>

</div>
</div>

### printAsOperand() {#abea60f56bef2a0f9437eed8c8bb9ec58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Metadata::printAsOperand (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print as operand.</p>


<p>Prints reference of <span class="doxyComputerOutput">this</span>.</p>


<p>If <span class="doxyComputerOutput">M</span> is provided, metadata nodes will be numbered canonically; otherwise, pointer addresses are substituted.</p>


<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 5250 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#abea60f56bef2a0f9437eed8c8bb9ec58">printAsOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a2c3485cc2e63a9ea902dccf6dc02a555">printMetadataImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a48e904486c2be7b98450bc2306c10648">llvm::MachineInstr::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a4706e639e364501f6000985df1222c58">llvm::MachineMemOperand::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76123bb0e0b41f5dbae594726160db22">llvm::MachineOperand::print</a>, <a href="#abea60f56bef2a0f9437eed8c8bb9ec58">printAsOperand</a>, <a href="#a1266599a812617ff001dab4a94eb4a62">printAsOperand</a> and <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ace4a165fe83a11188e7e9393c2e6cbed">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::printOperand</a>.</p>

</div>
</div>

### printAsOperand() {#a1266599a812617ff001dab4a94eb4a62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Metadata::printAsOperand (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 5255 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#abea60f56bef2a0f9437eed8c8bb9ec58">printAsOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a2c3485cc2e63a9ea902dccf6dc02a555">printMetadataImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getMetadataID() {#a91c7b9c7cf6694f41b9030429b582d26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Metadata::getMetadataID ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#adf7319ea74da6cc88920a880b418ff83">llvm::ConstantAsMetadata::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/diarglist/#a4b0f2da357ab396e090804a59bac0d76">llvm::DIArgList::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/diassignid/#a009250b5fa4b8d5f23578d8607f2fe07">llvm::DIAssignID::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dibasictype/#a689315e801724f3c05a04c75e9711fee">llvm::DIBasicType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dicommonblock/#a94190aa2a95618434606219c40368990">llvm::DICommonBlock::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a7797d4a32dbb959f7f4372b6d48f3601">llvm::DICompileUnit::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompositetype/#aee7a6f209c3a862a0e7d5b3cd6ad0e67">llvm::DICompositeType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/diderivedtype/#a9d9c3bc1a502fc402826f48e4f76046c">llvm::DIDerivedType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dienumerator/#adac2a62bc41f49527dcdc18e32992fa6">llvm::DIEnumerator::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a9c9178f86e040a88869d74de58943905">llvm::DIExpression::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/difile/#a0c6e35059ea273f206458b0b50fc0293">llvm::DIFile::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/digenericsubrange/#ab1cc0dd4e614ecded6fd23f5165aec35">llvm::DIGenericSubrange::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/diglobalvariable/#ab215da13e2c2716aad2a6c39f67c547d">llvm::DIGlobalVariable::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/diglobalvariableexpression/#aa276c411e902db0c483c6c558c52d6f1">llvm::DIGlobalVariableExpression::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dilabel/#a235c08f034505ae3fa364a8162553d4e">llvm::DILabel::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dilexicalblock/#a69327c3fe0b76e1cdcc9f4a5b5cd5c23">llvm::DILexicalBlock::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dilexicalblockbase/#a21dba2529ae67a118000ff0fb7adf014">llvm::DILexicalBlockBase::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dilexicalblockfile/#a2f6bfc24cc1b542fd8ea61f745e2391a">llvm::DILexicalBlockFile::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalscope/#a7232dd5ab71a7bfff29b2608b4c12ede">llvm::DILocalScope::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable/#a31d3ef15b0ed06025f3a903bbc2a6a1d">llvm::DILocalVariable::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#af599fdffda00cb0c8f6d243a30d60d88">llvm::DILocation::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dimacro/#af45e86f39276a04c27a4b1f0535e5cc8">llvm::DIMacro::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dimacrofile/#a8e6c632003f94eecc26f8a1e16a12c59">llvm::DIMacroFile::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dimacronode/#a8bf3664c010e37118b0284aa4e97aca3">llvm::DIMacroNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dinamespace/#a111eae53c4d3b7b7dfec29f85685b056">llvm::DINamespace::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dinode/#aaf51521fa5a968f10c00df1d3bfcda5f">llvm::DINode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/diobjcproperty/#a8a9d7da619fb9cf663a953086f063c89">llvm::DIObjCProperty::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/discope/#a6188a235c0a049194ce92450214199a1">llvm::DIScope::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/distringtype/#a20be119ec8f3fcb07cdd2aaa9be41e31">llvm::DIStringType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/disubprogram/#ac550a9aee8aa1c96d0ea854dfe299b4d">llvm::DISubprogram::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/disubrange/#a0d26bccd2eddd8d4f993de3dc0898e6a">llvm::DISubrange::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/disubroutinetype/#aa710f52123976efaee807f991fafc795">llvm::DISubroutineType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/ditemplateparameter/#a28d0416bd786276796f7114a49152a15">llvm::DITemplateParameter::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/ditemplatetypeparameter/#a40043a82d12585f4172380ef7dae72b6">llvm::DITemplateTypeParameter::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/ditemplatevalueparameter/#a4f5b3c1deb8c8307c70e88610abeb4d4">llvm::DITemplateValueParameter::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#aa000769a8d09e7cf12bbf23e8bad89fa">llvm::DIType::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/divariable/#acf42be98cd6e17f1a1b1ed3048d8084f">llvm::DIVariable::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/genericdinode/#a4d8f45c731f112d2b0d4af8ce0bbd140">llvm::GenericDINode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/localasmetadata/#ac602125aec50378ea4f94cea7996b8c4">llvm::LocalAsMetadata::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a8343692ff9294e7f1e33bdc9f7e82afc">llvm::MDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#a78dc01a1546e4f8b88d378910889b5a6">llvm::MDString::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mdtuple/#a449b8da9ec6d4dceff8405d4f8ddf247">llvm::MDTuple::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#aa43667dba0fa5fec06e81ca2bb7fef75">llvm::ValueAsMetadata::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aab52b512e1b50fff8d9f117c5e8a6bef">llvm::MDNode::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/replaceablemetadataimpl/#a97f281369b9902c19df7f1f55975065d">llvm::ReplaceableMetadataImpl::getAllArgListUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#affc6bc66f15352140caa79643837f683">llvm::MDNode::isAlwaysReplaceable</a>, <a href="/web-llvm/docs/api/classes/llvm/replaceablemetadataimpl/#a2b9c0ec6595f7f4b7d737415a8cb0aaf">llvm::ReplaceableMetadataImpl::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa3d2cc23382fca0aa0dde1f609347861">llvm::MDNode::resize</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a478c26e31b9b99fab1ba3036f966f5c9">llvm::MDNode::storeDistinctInContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### handleChangedOperand() {#a026cd28d293ce28bf5982ea6d15aaf00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Metadata::handleChangedOperand (void *, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *)</td>
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

<p>Default handling of a changed operand, which asserts.</p>


<p>If subclasses pass themselves in as owners to a tracking node reference, they must provide an implementation of this method.</p>


<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#ac265aa582f1e66e4e45d6a964b9bd303">Metadata</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Storage {#a8265bf29997e9e49d47a38a762d4bb0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::Metadata::Storage</td>
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

<p>Storage flag for non-uniqued, otherwise unowned, metadata.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dilexicalblockbase/#aae8819061d0ae275728e22c6fe5ca7c1">llvm::DILexicalBlockBase::DILexicalBlockBase</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalscope/#a69a0d7ba2e30781c0a164477f6860187">llvm::DILocalScope::DILocalScope</a>, <a href="/web-llvm/docs/api/classes/llvm/dimacronode/#a1cfa43577d3ed97bffbba7db54f105e2">llvm::DIMacroNode::DIMacroNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dinode/#a8af3feaeaaec959e6d272d70d06213b6">llvm::DINode::DINode</a>, <a href="/web-llvm/docs/api/classes/llvm/discope/#adade65a33056238a2e1698347d0d167f">llvm::DIScope::DIScope</a>, <a href="/web-llvm/docs/api/classes/llvm/ditemplateparameter/#a9565f1aad221ac7b3987d14229a815a7">llvm::DITemplateParameter::DITemplateParameter</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a411430e6383606f78f6b5fdd88e3e09e">llvm::DIType::DIType</a>, <a href="/web-llvm/docs/api/classes/llvm/divariable/#ad486b3ac091931adba21e5cae538243c">llvm::DIVariable::DIVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ab04c4c3fbcec8ecc3fa493fa3bcff8e3">llvm::MDNode::isDistinct</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a4a3aafff3f29eba4c6d639e6648c330c">llvm::MDNode::isTemporary</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a92fd2fda0d83920749a3b0ef851b4580">llvm::MDNode::isUniqued</a>, <a href="/web-llvm/docs/api/classes/llvm/diassignid/#acf51c34793180f67be514c1d6e4167f3">llvm::DIAssignID::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dibasictype/#acf51c34793180f67be514c1d6e4167f3">llvm::DIBasicType::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dicommonblock/#acf51c34793180f67be514c1d6e4167f3">llvm::DICommonBlock::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompositetype/#acf51c34793180f67be514c1d6e4167f3">llvm::DICompositeType::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/diderivedtype/#acf51c34793180f67be514c1d6e4167f3">llvm::DIDerivedType::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dienumerator/#acf51c34793180f67be514c1d6e4167f3">llvm::DIEnumerator::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#acf51c34793180f67be514c1d6e4167f3">llvm::DIExpression::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/digenericsubrange/#acf51c34793180f67be514c1d6e4167f3">llvm::DIGenericSubrange::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/diglobalvariable/#acf51c34793180f67be514c1d6e4167f3">llvm::DIGlobalVariable::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/diglobalvariableexpression/#acf51c34793180f67be514c1d6e4167f3">llvm::DIGlobalVariableExpression::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/diimportedentity/#acf51c34793180f67be514c1d6e4167f3">llvm::DIImportedEntity::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dilabel/#acf51c34793180f67be514c1d6e4167f3">llvm::DILabel::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dilexicalblock/#acf51c34793180f67be514c1d6e4167f3">llvm::DILexicalBlock::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dilexicalblockfile/#acf51c34793180f67be514c1d6e4167f3">llvm::DILexicalBlockFile::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable/#acf51c34793180f67be514c1d6e4167f3">llvm::DILocalVariable::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#acf51c34793180f67be514c1d6e4167f3">llvm::DILocation::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dimacro/#acf51c34793180f67be514c1d6e4167f3">llvm::DIMacro::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dimacrofile/#acf51c34793180f67be514c1d6e4167f3">llvm::DIMacroFile::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dimodule/#acf51c34793180f67be514c1d6e4167f3">llvm::DIModule::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dinamespace/#acf51c34793180f67be514c1d6e4167f3">llvm::DINamespace::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/diobjcproperty/#acf51c34793180f67be514c1d6e4167f3">llvm::DIObjCProperty::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/distringtype/#acf51c34793180f67be514c1d6e4167f3">llvm::DIStringType::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/disubrange/#acf51c34793180f67be514c1d6e4167f3">llvm::DISubrange::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/disubroutinetype/#acf51c34793180f67be514c1d6e4167f3">llvm::DISubroutineType::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/ditemplatetypeparameter/#acf51c34793180f67be514c1d6e4167f3">llvm::DITemplateTypeParameter::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/ditemplatevalueparameter/#acf51c34793180f67be514c1d6e4167f3">llvm::DITemplateValueParameter::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/genericdinode/#acf51c34793180f67be514c1d6e4167f3">llvm::GenericDINode::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa62a8f06c7c38176942b29855f33ddbc">llvm::MDNode::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/mdtuple/#acf51c34793180f67be514c1d6e4167f3">llvm::MDTuple::MDNode</a>, <a href="#ac265aa582f1e66e4e45d6a964b9bd303">Metadata</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#abd7afd5fab5f5b746a194e87d1a606fc">llvm::MDNode::operator new</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a478c26e31b9b99fab1ba3036f966f5c9">llvm::MDNode::storeDistinctInContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a20d3b0b5da786f4ad0747424704116bb">llvm::MDNode::storeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad0c6e5f8501b6685c39f35bd56cf0fd2">llvm::MDNode::storeImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#adfe4d363be6cb0594027dd4917a9bfb1">llvm::MDNode::~MDNode</a>.</p>

</div>
</div>

### SubclassData1 {#abc1edd99ba896e4a2dae82f7b1a750e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::Metadata::SubclassData1</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ditemplateparameter/#a9565f1aad221ac7b3987d14229a815a7">llvm::DITemplateParameter::DITemplateParameter</a>, <a href="/web-llvm/docs/api/classes/llvm/dinamespace/#acdacfd705e894f30ff22112a2bd1299d">llvm::DINamespace::getExportSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/ditemplateparameter/#a261c9fd10402fc9c1a44ee450f61aad6">llvm::DITemplateParameter::isDefault</a> and <a href="#ac265aa582f1e66e4e45d6a964b9bd303">Metadata</a>.</p>

</div>
</div>

### SubclassData16 {#a72ff55650cd3d97745402a6cb76c1b3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::Metadata::SubclassData16 = 0</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dimacronode/#a62b1e87b8ea3d11962d216539ea684e4">llvm::DIMacroNode::getMacinfoType</a>, <a href="/web-llvm/docs/api/classes/llvm/dinode/#a13471a1f55ae60d82d774585bfd3c5da">llvm::DINode::getTag</a>, <a href="/web-llvm/docs/api/classes/llvm/genericdinode/#a59dbb6700371ed996351198327711511">llvm::GenericDINode::getTag</a> and <a href="/web-llvm/docs/api/classes/llvm/dinode/#a7e678effd23ac947241b4bfcc65ce2f9">llvm::DINode::setTag</a>.</p>

</div>
</div>

### SubclassData32 {#a77e771a2105567c5db8a9a74f7bb9da3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Metadata::SubclassData32 = 0</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/distinctmdoperandplaceholder/#af6749770ad338c5719e1f3602bd8b5ea">llvm::DistinctMDOperandPlaceholder::DistinctMDOperandPlaceholder</a>, <a href="/web-llvm/docs/api/classes/llvm/divariable/#ad486b3ac091931adba21e5cae538243c">llvm::DIVariable::DIVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#aafecafc5b47638df4c3080736b1c3934">llvm::DIType::getAlignInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/divariable/#a08730cf239c9ebb27c7c1dc2c3ee5936">llvm::DIVariable::getAlignInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/dilexicalblockfile/#a4bcc88641341d54a32972556cf8d1a4f">llvm::DILexicalBlockFile::getDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/genericdinode/#a81e1c815a784ebc18b9da4f20b82c316">llvm::GenericDINode::getHash</a>, <a href="/web-llvm/docs/api/classes/llvm/mdtuple/#a924b591e02b3cd62494bf001e2ce1ce0">llvm::MDTuple::getHash</a>, <a href="/web-llvm/docs/api/classes/llvm/distinctmdoperandplaceholder/#a629021baa296713fdc2ab0c208904d16">llvm::DistinctMDOperandPlaceholder::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/dilabel/#a30e4e7c5816fb2eed1f26cf70390550a">llvm::DILabel::getLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dilexicalblock/#a547be10e43af4f8c6d24c961b0853da4">llvm::DILexicalBlock::getLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dimacro/#a18aba01d653fd94e4625e8f06db60530">llvm::DIMacro::getLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dimacrofile/#a7c7b2322f51f70feb7ceba60abcd8332">llvm::DIMacroFile::getLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dicommonblock/#a96d85338ed343e59f7cd31ffe951eea7">llvm::DICommonBlock::getLineNo</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#ac2139a587bc6e8d87e958964e10fb5d6">llvm::DIType::init</a>, <a href="/web-llvm/docs/api/classes/llvm/dienumerator/#ae03f1d1ab707727d2a0bba870375e648">llvm::DIEnumerator::isUnsigned</a>, <a href="/web-llvm/docs/api/classes/llvm/diderivedtype/#acf51c34793180f67be514c1d6e4167f3">llvm::DIDerivedType::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/diimportedentity/#acf51c34793180f67be514c1d6e4167f3">llvm::DIImportedEntity::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dilexicalblock/#acf51c34793180f67be514c1d6e4167f3">llvm::DILexicalBlock::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dilexicalblockfile/#acf51c34793180f67be514c1d6e4167f3">llvm::DILexicalBlockFile::MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dimacro/#acf51c34793180f67be514c1d6e4167f3">llvm::DIMacro::MDNode</a> and <a href="/web-llvm/docs/api/classes/llvm/dimacrofile/#acf51c34793180f67be514c1d6e4167f3">llvm::DIMacroFile::MDNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### SubclassID {#a34f35ce0405bc76111e79d2ef41e6139}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned char llvm::Metadata::SubclassID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RTTI.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### PoisonGeneratingIDs {#a58d89444e861edbf2a966fd172480aac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::Metadata::PoisonGeneratingIDs[]</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> IDs that may generate poison.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
      LLVMContext::MD_range, LLVMContext::MD_nonnull, LLVMContext::MD_align}
</div>
</dd>
</dl>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3ba96a0d49ec5f1a062b075f54536a3c">llvm::InstCombinerImpl::visitLoadInst</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
