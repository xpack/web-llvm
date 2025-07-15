---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/metadataasvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MetadataAsValue` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> wrapper in the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> hierarchy. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MetadataAsValue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> Representation. <a href="/web-llvm/docs/api/classes/llvm/value/#details">More...</a></p>
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

</table>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34cdf3ee3704a10bdb1868a27a1ad9ac">MetadataAsValue</a> (Type *Ty, Metadata *MD)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8f5b66c1e3e1c2f0740764818920442">~MetadataAsValue</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac524678278da9691379135d01953a8e9">getMetadata</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b96dbd32661f039c7338ade5cbad230">dropUse</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop use of metadata (during teardown). <a href="#a0b96dbd32661f039c7338ade5cbad230">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff60ce5524ea2f4d99b5ae93dfb6201f">handleChangedMetadata</a> (Metadata *MD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf4589f79b38a3ed75dd2200b7ca65bc">track</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29d5922d3a2c2f94af3375c22509253b">untrack</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99f0953a474b8503f1a9134bb7bfe635">MD</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue">MetadataAsValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3188a1aa0df768d8f254cd8d8fdeface">get</a> (LLVMContext &amp;Context, Metadata *MD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue">MetadataAsValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43da96a342731ffba21f83523a9c787a">getIfExists</a> (LLVMContext &amp;Context, Metadata *MD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf3b2a9fa43c739eca76fdd58900d2fa">classof</a> (const Value *V)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> wrapper in the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> hierarchy.</p>


<p>A member of the <em><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></em> hierarchy to represent a reference to metadata. This allows, e.g., intrinsics to have metadata as operands.</p>


<p>Notably, this is the only thing in either hierarchy that is allowed to reference <em><a href="/web-llvm/docs/api/classes/llvm/localasmetadata">LocalAsMetadata</a></em>.</p>


<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


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


<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a>.</p>


<p>Referenced by <a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a>.</p>

</div>
</div>

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


<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="#a8e487c1ea4559300508da2e4789fb763">ReplaceableMetadataImpl</a>.</p>


<p>Referenced by <a href="#a8e487c1ea4559300508da2e4789fb763">ReplaceableMetadataImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### MetadataAsValue() {#a34cdf3ee3704a10bdb1868a27a1ad9ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MetadataAsValue::MetadataAsValue (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MetadataAsValue() {#aa8f5b66c1e3e1c2f0740764818920442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MetadataAsValue::~MetadataAsValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a0f84a0b5ee0bc1f89540f7dac8cf80a0">llvm::LLVMContextImpl::MetadataAsValues</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aa142c8c536b95dd8e8a243cb67b57a80">llvm::LLVMContext::pImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getMetadata() {#ac524678278da9691379135d01953a8e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * llvm::MetadataAsValue::getMetadata ()</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#ac7b438ce165bdc9f0bff4c55f8c0f499">llvm::FunctionComparator::cmpValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a39c9d039f5cbab6c4155e907c466ab25">extractMDNode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#ab5e88a19352e7dce1b0115f5e6b37b47">getArgSPIRVType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### dropUse() {#a0b96dbd32661f039c7338ade5cbad230}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MetadataAsValue::dropUse ()</td>
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

<p>Drop use of metadata (during teardown).</p>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

### handleChangedMetadata() {#aff60ce5524ea2f4d99b5ae93dfb6201f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MetadataAsValue::handleChangedMetadata (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>

</div>
</div>

### track() {#aaf4589f79b38a3ed75dd2200b7ca65bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MetadataAsValue::track ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>

</div>
</div>

### untrack() {#a29d5922d3a2c2f94af3375c22509253b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MetadataAsValue::untrack ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MD {#a99f0953a474b8503f1a9134bb7bfe635}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MetadataAsValue::MD</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#aaf3b2a9fa43c739eca76fdd58900d2fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MetadataAsValue::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#a18dbfcb332af7515599ee795cf462843">llvm::Value::Value</a>.</p>

</div>
</div>

### get() {#a3188a1aa0df768d8f254cd8d8fdeface}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MetadataAsValue * MetadataAsValue::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD)</td>
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



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp/#a20a678afa540694502fca3ed77617af8">canonicalizeMetadataForValue</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a28fdf240b8220065bc60d6d1b1a2f174">llvm::Type::getMetadataTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a1fb252b26b548e2ed904e02782013abd">llvm::DbgVariableIntrinsic::addVariableLocationOps</a>, <a href="/web-llvm/docs/api/structs/anonymous-crossdsocfi-cpp-/crossdsocfi/#ab29f15fad3f35ea8248e93e3dc805224">anonymous{CrossDSOCFI.cpp}::CrossDSOCFI::buildCFICheck</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-spirvemitintrinsics-cpp-/#a54b7a397102703566ccbb015b4405474">anonymous{SPIRVEmitIntrinsics.cpp}::buildMD</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#afbf9fd3d3729664031c88766bcefcdf0">anonymous{CloneFunction.cpp}::PruningFunctionCloner::cloneInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord/#adc686ba917c4b589803df62f9a0c75d6">llvm::DbgLabelRecord::createDebugIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ad399adefaffab058aa56567aa1b59df9">llvm::DbgVariableRecord::createDebugIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#a58d2814d7f3eeff5857d17753ff5f7cb">createDecorationIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab0304f49029dc84f0b339aeb9cbe6ce3">llvm::IRBuilderBase::CreateNoAliasScopeDeclaration</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#ad5ee8b40336e0c147c85f2520ada223c">getDbgIntrinsicValueImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#aa4b48d750cec06b65003055986a16b40">getMDNodeOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a5a6937fcd639ac78a93b48ab6624e957">llvm::DIBuilder::insertDbgAssign</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a214637beca449d58d4313a69a9ba32af">llvm::DIBuilder::insertDeclare</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#adb6aff41bfe64d206d563112993cfb01">llvm::DIBuilder::insertLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/groups/llvmccoreinstructionbuilder/#gaeda8f1dd5842f278e879841baa10033f">LLVMGetCurrentDebugLocation</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueinstruction/#gab587f74afd6c80d1aa5fce85a6ece0fd">LLVMGetMetadata</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#gae134c00653fcc70b850fb03af410be9c">LLVMGetNamedMetadataOperands</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluemetadata/#gab79cef5ec6dd638a424edf41f6caaed8">LLVMMDNodeInContext</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluemetadata/#gaa19549aa848905ca658ce4efe7f7b07b">LLVMMDStringInContext</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluemetadata/#ga1021d979b3dd430fbab93b359544afc0">LLVMMetadataAsValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a5e5cf24df0a45159407988a98fe42700">lowerPtrAnnotation</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a7d5502a6047fb27d6c33ea2820608c2c">anonymous{ValueMapper.cpp}::Mapper::mapValue</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a0a084f86091fd327d3113e8674c54192">anonymous{ThinLTOBitcodeWriter.cpp}::promoteTypeIds</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#ab31b894cd23f1d93468a50153a385fa1">llvm::memtag::readRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a9f66dfca05bfb9a4f5bddbad1ad043e6">llvm::DbgVariableIntrinsic::replaceVariableLocationOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a3d995a069d73ebebbd6a4aace342ef76">llvm::DbgVariableIntrinsic::replaceVariableLocationOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic/#aef2660c212a6794faf7ec16cae82248a">llvm::DbgAssignIntrinsic::setAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic/#af50410033f7fa1450e7030aa25eae45e">llvm::DbgAssignIntrinsic::setAddressExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic/#a4c46f4f09337677b638261fc6487aade">llvm::DbgAssignIntrinsic::setAssignId</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a71808acf992f787300ec18d5700f09cc">llvm::DbgVariableIntrinsic::setExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dbglabelinst/#a91ea3c7496ba4e21be7e4d1ed54b03c6">llvm::DbgLabelInst::setLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a2faebe0374c9b44fdb9bd71cafdef798">llvm::DbgVariableIntrinsic::setRawLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/noaliasscopedeclinst/#a2defed486cd9ee3d4ff214afbd0c9066">llvm::NoAliasScopeDeclInst::setScopeList</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic/#a06c7810ad5d205218bce57bff448b2e3">llvm::DbgAssignIntrinsic::setValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a180601bf52af11126dcf05266de02500">llvm::DbgVariableIntrinsic::setVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a> and <a href="/web-llvm/docs/api/classes/anonymous-spirvemitintrinsics-cpp-/spirvemitintrinsics/#ac6e0980539d623cb69d94e25d2e52481">anonymous{SPIRVEmitIntrinsics.cpp}::SPIRVEmitIntrinsics::visitCallInst</a>.</p>

</div>
</div>

### getIfExists() {#a43da96a342731ffba21f83523a9c787a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MetadataAsValue * MetadataAsValue::getIfExists (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD)</td>
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



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp/#a20a678afa540694502fca3ed77617af8">canonicalizeMetadataForValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a19d345e6fa45d60ff4092769417b89b2">llvm::findDbgDeclares</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#ac43142f662a5dd59c09abd92322a9821">findDbgIntrinsics</a> and <a href="/web-llvm/docs/api/namespaces/llvm/at/#a3c90899e8f022656e511630de42b916c">llvm::at::getAssignmentMarkers</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
