---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/localasmetadata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LocalAsMetadata` Class



## Declaration

<div class="doxyDeclaration">
class llvm::LocalAsMetadata { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cbd9e338a58f62b38e2b820de8c1e6f">ValueAsMetadata</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9e7f323b72c19878a58d472f24547f9">LocalAsMetadata</a> (Value *Local)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/localasmetadata">LocalAsMetadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac29220d2b2888d19541f9e3862b2b67a">get</a> (Value *Local)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/localasmetadata">LocalAsMetadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3824551809fd3b92409d32854adff80">getIfExists</a> (Value *Local)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac602125aec50378ea4f94cea7996b8c4">classof</a> (const Metadata *MD)</td>
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


<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<div class="doxySectionDef">

## Friends

### ValueAsMetadata {#a3cbd9e338a58f62b38e2b820de8c1e6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata">ValueAsMetadata</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 550 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/globalmergefunctions-h/#a54f7429fa5826ff9909619b76d2bf319a509820290d57f333403f490dde7316f4">Local</a> and <a href="#a3cbd9e338a58f62b38e2b820de8c1e6f">ValueAsMetadata</a>.</p>


<p>Referenced by <a href="#a3cbd9e338a58f62b38e2b820de8c1e6f">ValueAsMetadata</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### LocalAsMetadata() {#aa9e7f323b72c19878a58d472f24547f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LocalAsMetadata::LocalAsMetadata (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Local)</td>
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



<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ac602125aec50378ea4f94cea7996b8c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LocalAsMetadata::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD)</td>
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



<p>Definition at line 566 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/metadata/#a91c7b9c7cf6694f41b9030429b582d26">llvm::Metadata::getMetadataID</a>.</p>

</div>
</div>

### get() {#ac29220d2b2888d19541f9e3862b2b67a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocalAsMetadata * llvm::LocalAsMetadata::get (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Local)</td>
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



<p>Definition at line 558 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a4972b9f38f647704eefe3399d6c6ef2f">llvm::ValueAsMetadata::getLocal</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/globalmergefunctions-h/#a54f7429fa5826ff9909619b76d2bf319a509820290d57f333403f490dde7316f4">Local</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmccorevaluemetadata/#gab79cef5ec6dd638a424edf41f6caaed8">LLVMMDNodeInContext</a>.</p>

</div>
</div>

### getIfExists() {#ab3824551809fd3b92409d32854adff80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocalAsMetadata * llvm::LocalAsMetadata::getIfExists (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Local)</td>
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



<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a1809a39b13d176d4cc1277d1cda9d046">llvm::ValueAsMetadata::getLocalIfExists</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/globalmergefunctions-h/#a54f7429fa5826ff9909619b76d2bf319a509820290d57f333403f490dde7316f4">Local</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a19d345e6fa45d60ff4092769417b89b2">llvm::findDbgDeclares</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#ac43142f662a5dd59c09abd92322a9821">findDbgIntrinsics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9c256eafdc8fb849f7320bc37120a5c">llvm::findDVRDeclares</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8986bcfeec47c38c0078ef3d3e1c8707">llvm::findDVRValues</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
