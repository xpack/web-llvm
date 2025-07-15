---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/aamdnodes
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AAMDNodes` Struct Reference

<p>A collection of metadata nodes that might be associated with a memory access used by the alias-analysis infrastructure. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::AAMDNodes { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acef9ef68ccae3536d0386cd0488a55ba">AAMDNodes</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8daf5329dec4f1f687b9ed9bcaf9f113">AAMDNodes</a> (MDNode *T, MDNode *TS, MDNode *S, MDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfdc24104b551b1f06bc74b598e30f26">operator==</a> (const AAMDNodes &amp;A) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26909aa0d62b34d64c4a09cab6990ec4">operator!=</a> (const AAMDNodes &amp;A) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab112e2d654ad67849d9ec7ea8c7f1d83">operator bool</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89a638f74d3b14c52c4065657ba095fb">intersect</a> (const AAMDNodes &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given two sets of <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> that apply to the same pointer, give the best <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> that are compatible with both (i.e. <a href="#a89a638f74d3b14c52c4065657ba095fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f73e1d64fc604ae208d9eee356dd2ab">shift</a> (size_t Offset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new AAMDNode that describes this AAMDNode after applying a constant offset to the start of the pointer. <a href="#a5f73e1d64fc604ae208d9eee356dd2ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc415418337d16a2b07a2b8ab6e8dc36">extendTo</a> (ssize_t Len) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new AAMDNode that describes this AAMDNode after extending it to apply to a series of bytes of length Len. <a href="#abc415418337d16a2b07a2b8ab6e8dc36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b173e97523275314f3f2b433a5f71a9">merge</a> (const AAMDNodes &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given two sets of <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> applying to potentially different locations, determine the best <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> that apply to both. <a href="#a6b173e97523275314f3f2b433a5f71a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17815a975c66fae245b9c87142c3a8b7">concat</a> (const AAMDNodes &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the best <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> after concatenating two different locations together. <a href="#a17815a975c66fae245b9c87142c3a8b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c82bb8e10db405d4dd265c150fc52b9">adjustForAccess</a> (unsigned AccessSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new AAMDNode for accessing <span class="doxyComputerOutput">AccessSize</span> bytes of this AAMDNode. <a href="#a9c82bb8e10db405d4dd265c150fc52b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d066800275189cc6d2c95d942fd9f44">adjustForAccess</a> (size_t Offset, Type *AccessTy, const DataLayout &amp;DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9334b58450cbcef241fcfda5bcbe039">adjustForAccess</a> (size_t Offset, unsigned AccessSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56188042f9dd6003cb8ed087e8ae654f">TBAA</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The tag for type-based alias analysis. <a href="#a56188042f9dd6003cb8ed087e8ae654f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4831dbe1cbfb8f0e07600bf890af8353">TBAAStruct</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The tag for type-based alias analysis (tbaa struct). <a href="#a4831dbe1cbfb8f0e07600bf890af8353">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5175e1defb539f65df5ded7a806fa5c8">Scope</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The tag for alias scope specification (used with noalias). <a href="#a5175e1defb539f65df5ded7a806fa5c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81f3c11f463009d8b19b544f5bfed40c">NoAlias</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The tag specifying the noalias scope. <a href="#a81f3c11f463009d8b19b544f5bfed40c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad25413c097c370ed086055ecdbc75b1e">shiftTBAA</a> (MDNode *M, size_t off)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25af03cf36c07d235f487e525e5dcd07">shiftTBAAStruct</a> (MDNode *M, size_t off)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53468ec93dc5de2584b89a719ab34627">extendToTBAA</a> (MDNode *TBAA, ssize_t len)</td>
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

<p>A collection of metadata nodes that might be associated with a memory access used by the alias-analysis infrastructure.</p>

<p>Definition at line 764 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AAMDNodes() {#acef9ef68ccae3536d0386cd0488a55ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AAMDNodes::AAMDNodes ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Referenced by <a href="#a7d066800275189cc6d2c95d942fd9f44">adjustForAccess</a>, <a href="#af9334b58450cbcef241fcfda5bcbe039">adjustForAccess</a>, <a href="#a9c82bb8e10db405d4dd265c150fc52b9">adjustForAccess</a>, <a href="#a17815a975c66fae245b9c87142c3a8b7">concat</a>, <a href="#abc415418337d16a2b07a2b8ab6e8dc36">extendTo</a>, <a href="#a89a638f74d3b14c52c4065657ba095fb">intersect</a>, <a href="#a6b173e97523275314f3f2b433a5f71a9">merge</a>, <a href="#a26909aa0d62b34d64c4a09cab6990ec4">operator!=</a>, <a href="#abfdc24104b551b1f06bc74b598e30f26">operator==</a> and <a href="#a5f73e1d64fc604ae208d9eee356dd2ab">shift</a>.</p>

</div>
</div>

### AAMDNodes() {#a8daf5329dec4f1f687b9ed9bcaf9f113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AAMDNodes::AAMDNodes (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * T, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * TS, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * S, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * N)</td>
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



<p>Definition at line 766 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a81f3c11f463009d8b19b544f5bfed40c">NoAlias</a>, <a href="#a5175e1defb539f65df5ded7a806fa5c8">Scope</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="#a56188042f9dd6003cb8ed087e8ae654f">TBAA</a> and <a href="#a4831dbe1cbfb8f0e07600bf890af8353">TBAAStruct</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#ab112e2d654ad67849d9ec7ea8c7f1d83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AAMDNodes::operator bool ()</td>
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



<p>Definition at line 776 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="#a81f3c11f463009d8b19b544f5bfed40c">NoAlias</a>, <a href="#a5175e1defb539f65df5ded7a806fa5c8">Scope</a>, <a href="#a56188042f9dd6003cb8ed087e8ae654f">TBAA</a> and <a href="#a4831dbe1cbfb8f0e07600bf890af8353">TBAAStruct</a>.</p>

</div>
</div>

### operator!=() {#a26909aa0d62b34d64c4a09cab6990ec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMDNodes::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> &amp; A)</td>
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



<p>Definition at line 774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#acef9ef68ccae3536d0386cd0488a55ba">AAMDNodes</a>.</p>

</div>
</div>

### operator==() {#abfdc24104b551b1f06bc74b598e30f26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMDNodes::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> &amp; A)</td>
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



<p>Definition at line 769 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#acef9ef68ccae3536d0386cd0488a55ba">AAMDNodes</a>, <a href="#a81f3c11f463009d8b19b544f5bfed40c">NoAlias</a>, <a href="#a5175e1defb539f65df5ded7a806fa5c8">Scope</a>, <a href="#a56188042f9dd6003cb8ed087e8ae654f">TBAA</a> and <a href="#a4831dbe1cbfb8f0e07600bf890af8353">TBAAStruct</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### adjustForAccess() {#a9c82bb8e10db405d4dd265c150fc52b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAMDNodes AAMDNodes::adjustForAccess (unsigned AccessSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new AAMDNode for accessing <span class="doxyComputerOutput">AccessSize</span> bytes of this AAMDNode.</p>


<p>If this AAMDNode has !tbaa.struct and <span class="doxyComputerOutput">AccessSize</span> matches the size of the field at offset 0, get the TBAA tag describing the accessed field. If such an AAMDNode already embeds !tbaa, the existing one is retrieved. Finally, !tbaa.struct is zeroed out.</p>


<p>Declaration at line 857 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 827 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>


<p>References <a href="#acef9ef68ccae3536d0386cd0488a55ba">AAMDNodes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#a7f12b8ac7462ea82d735ac7d56f6260b">llvm::mdconst::hasa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### adjustForAccess() {#a7d066800275189cc6d2c95d942fd9f44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAMDNodes AAMDNodes::adjustForAccess (size_t Offset, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * AccessTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 858 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 843 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>


<p>References <a href="#acef9ef68ccae3536d0386cd0488a55ba">AAMDNodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a5f73e1d64fc604ae208d9eee356dd2ab">shift</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### adjustForAccess() {#af9334b58450cbcef241fcfda5bcbe039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAMDNodes AAMDNodes::adjustForAccess (size_t Offset, unsigned AccessSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 860 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 855 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>


<p>References <a href="#acef9ef68ccae3536d0386cd0488a55ba">AAMDNodes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a5f73e1d64fc604ae208d9eee356dd2ab">shift</a>.</p>

</div>
</div>

### concat() {#a17815a975c66fae245b9c87142c3a8b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAMDNodes AAMDNodes::concat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine the best <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> after concatenating two different locations together.</p>


<p>Different from <span class="doxyComputerOutput">merge</span>, where different locations should overlap each other, <span class="doxyComputerOutput">concat</span> puts non-overlapping locations together.</p>


<p>Declaration at line 850 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>


<p>References <a href="#acef9ef68ccae3536d0386cd0488a55ba">AAMDNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a088247f165cc7e2ca9a3917adc0e75df">llvm::MDNode::getMostGenericAliasScope</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#acdbfda46c9837123ef7143244fc1f904">llvm::MDNode::intersect</a>, <a href="#a81f3c11f463009d8b19b544f5bfed40c">NoAlias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a5175e1defb539f65df5ded7a806fa5c8">Scope</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a8f64e8576d57bb362e730214c7e6fae9">foldLoadsRecursive</a>.</p>

</div>
</div>

### extendTo() {#abc415418337d16a2b07a2b8ab6e8dc36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAMDNodes llvm::AAMDNodes::extendTo (ssize_t Len)</td>
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

<p>Create a new AAMDNode that describes this AAMDNode after extending it to apply to a series of bytes of length Len.</p>


<p>A size of -1 denotes an unknown size.</p>


<p>Definition at line 831 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="#acef9ef68ccae3536d0386cd0488a55ba">AAMDNodes</a>, <a href="#a53468ec93dc5de2584b89a719ab34627">extendToTBAA</a>, <a href="#a81f3c11f463009d8b19b544f5bfed40c">NoAlias</a>, <a href="#a5175e1defb539f65df5ded7a806fa5c8">Scope</a>, <a href="#a56188042f9dd6003cb8ed087e8ae654f">TBAA</a> and <a href="#a4831dbe1cbfb8f0e07600bf890af8353">TBAAStruct</a>.</p>

</div>
</div>

### intersect() {#a89a638f74d3b14c52c4065657ba095fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAMDNodes llvm::AAMDNodes::intersect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> &amp; Other)</td>
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

<p>Given two sets of <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> that apply to the same pointer, give the best <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> that are compatible with both (i.e.</p>


<p>a set of nodes whose allowable aliasing conclusions are a subset of those allowable by both of the inputs). However, for efficiency reasons, do not create any new MDNodes.</p>


<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="#acef9ef68ccae3536d0386cd0488a55ba">AAMDNodes</a>, <a href="#a81f3c11f463009d8b19b544f5bfed40c">NoAlias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a5175e1defb539f65df5ded7a806fa5c8">Scope</a>, <a href="#a56188042f9dd6003cb8ed087e8ae654f">TBAA</a> and <a href="#a4831dbe1cbfb8f0e07600bf890af8353">TBAAStruct</a>.</p>

</div>
</div>

### merge() {#a6b173e97523275314f3f2b433a5f71a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAMDNodes AAMDNodes::merge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given two sets of <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> applying to potentially different locations, determine the best <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> that apply to both.</p>

<p>Declaration at line 845 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>


<p>References <a href="#acef9ef68ccae3536d0386cd0488a55ba">AAMDNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a088247f165cc7e2ca9a3917adc0e75df">llvm::MDNode::getMostGenericAliasScope</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a3c210e8905029a012df3384a7eeb63ad">llvm::MDNode::getMostGenericTBAA</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#acdbfda46c9837123ef7143244fc1f904">llvm::MDNode::intersect</a>, <a href="#a81f3c11f463009d8b19b544f5bfed40c">NoAlias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a5175e1defb539f65df5ded7a806fa5c8">Scope</a> and <a href="#a56188042f9dd6003cb8ed087e8ae654f">TBAA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a1a5189be752e56bf8343fd72f45720ee">mergeConditionalStoreToAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>.</p>

</div>
</div>

### shift() {#a5f73e1d64fc604ae208d9eee356dd2ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAMDNodes llvm::AAMDNodes::shift (size_t Offset)</td>
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

<p>Create a new AAMDNode that describes this AAMDNode after applying a constant offset to the start of the pointer.</p>

<p>Definition at line 818 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="#acef9ef68ccae3536d0386cd0488a55ba">AAMDNodes</a>, <a href="#a81f3c11f463009d8b19b544f5bfed40c">NoAlias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a5175e1defb539f65df5ded7a806fa5c8">Scope</a>, <a href="#ad25413c097c370ed086055ecdbc75b1e">shiftTBAA</a>, <a href="#a25af03cf36c07d235f487e525e5dcd07">shiftTBAAStruct</a>, <a href="#a56188042f9dd6003cb8ed087e8ae654f">TBAA</a> and <a href="#a4831dbe1cbfb8f0e07600bf890af8353">TBAAStruct</a>.</p>


<p>Referenced by <a href="#a7d066800275189cc6d2c95d942fd9f44">adjustForAccess</a> and <a href="#af9334b58450cbcef241fcfda5bcbe039">adjustForAccess</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### NoAlias {#a81f3c11f463009d8b19b544f5bfed40c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode* llvm::AAMDNodes::NoAlias = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The tag specifying the noalias scope.</p>

<p>Definition at line 790 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Referenced by <a href="#a8daf5329dec4f1f687b9ed9bcaf9f113">AAMDNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/scopednoaliasaaresult/#ab972fe828052b5cbeeeb3e9b8cfe0764">llvm::ScopedNoAliasAAResult::alias</a>, <a href="#a17815a975c66fae245b9c87142c3a8b7">concat</a>, <a href="#abc415418337d16a2b07a2b8ab6e8dc36">extendTo</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-2fb65b0a1a0a6b552e5196839bac56e7/#a63412da22c3f0c661331ab7d225502cc">llvm::DenseMapInfo&lt; AAMDNodes &gt;::getHashValue</a>, <a href="#a89a638f74d3b14c52c4065657ba095fb">intersect</a>, <a href="#a6b173e97523275314f3f2b433a5f71a9">merge</a>, <a href="#ab112e2d654ad67849d9ec7ea8c7f1d83">operator bool</a>, <a href="#abfdc24104b551b1f06bc74b598e30f26">operator==</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#aaf6c3eb212e9e66ac2d36fdb7e0a51ed">anonymous{MIParser.cpp}::MIParser::parseMachineMemoryOperand</a> and <a href="#a5f73e1d64fc604ae208d9eee356dd2ab">shift</a>.</p>

</div>
</div>

### Scope {#a5175e1defb539f65df5ded7a806fa5c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode* llvm::AAMDNodes::Scope = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The tag for alias scope specification (used with noalias).</p>

<p>Definition at line 787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Referenced by <a href="#a8daf5329dec4f1f687b9ed9bcaf9f113">AAMDNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/scopednoaliasaaresult/#ab972fe828052b5cbeeeb3e9b8cfe0764">llvm::ScopedNoAliasAAResult::alias</a>, <a href="#a17815a975c66fae245b9c87142c3a8b7">concat</a>, <a href="#abc415418337d16a2b07a2b8ab6e8dc36">extendTo</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-2fb65b0a1a0a6b552e5196839bac56e7/#a63412da22c3f0c661331ab7d225502cc">llvm::DenseMapInfo&lt; AAMDNodes &gt;::getHashValue</a>, <a href="#a89a638f74d3b14c52c4065657ba095fb">intersect</a>, <a href="#a6b173e97523275314f3f2b433a5f71a9">merge</a>, <a href="#ab112e2d654ad67849d9ec7ea8c7f1d83">operator bool</a>, <a href="#abfdc24104b551b1f06bc74b598e30f26">operator==</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#aaf6c3eb212e9e66ac2d36fdb7e0a51ed">anonymous{MIParser.cpp}::MIParser::parseMachineMemoryOperand</a> and <a href="#a5f73e1d64fc604ae208d9eee356dd2ab">shift</a>.</p>

</div>
</div>

### TBAA {#a56188042f9dd6003cb8ed087e8ae654f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode* llvm::AAMDNodes::TBAA = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The tag for type-based alias analysis.</p>

<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Referenced by <a href="#a8daf5329dec4f1f687b9ed9bcaf9f113">AAMDNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/typebasedaaresult/#ac92480fed6d1bffab7843f41e0a51c20">llvm::TypeBasedAAResult::alias</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/typesanitizer-cpp/#a8fe9c2e5d8a275393677c1c46c5f0596">collectMemAccessInfo</a>, <a href="#abc415418337d16a2b07a2b8ab6e8dc36">extendTo</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-2fb65b0a1a0a6b552e5196839bac56e7/#a63412da22c3f0c661331ab7d225502cc">llvm::DenseMapInfo&lt; AAMDNodes &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a623eef1675bd2f33cfacc50b2fec0c71">getMemmoveLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a>, <a href="#a89a638f74d3b14c52c4065657ba095fb">intersect</a>, <a href="#a6b173e97523275314f3f2b433a5f71a9">merge</a>, <a href="#ab112e2d654ad67849d9ec7ea8c7f1d83">operator bool</a>, <a href="#abfdc24104b551b1f06bc74b598e30f26">operator==</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#aaf6c3eb212e9e66ac2d36fdb7e0a51ed">anonymous{MIParser.cpp}::MIParser::parseMachineMemoryOperand</a> and <a href="#a5f73e1d64fc604ae208d9eee356dd2ab">shift</a>.</p>

</div>
</div>

### TBAAStruct {#a4831dbe1cbfb8f0e07600bf890af8353}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode* llvm::AAMDNodes::TBAAStruct = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The tag for type-based alias analysis (tbaa struct).</p>

<p>Definition at line 784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Referenced by <a href="#a8daf5329dec4f1f687b9ed9bcaf9f113">AAMDNodes</a>, <a href="#abc415418337d16a2b07a2b8ab6e8dc36">extendTo</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-2fb65b0a1a0a6b552e5196839bac56e7/#a63412da22c3f0c661331ab7d225502cc">llvm::DenseMapInfo&lt; AAMDNodes &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a623eef1675bd2f33cfacc50b2fec0c71">getMemmoveLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a>, <a href="#a89a638f74d3b14c52c4065657ba095fb">intersect</a>, <a href="#ab112e2d654ad67849d9ec7ea8c7f1d83">operator bool</a>, <a href="#abfdc24104b551b1f06bc74b598e30f26">operator==</a> and <a href="#a5f73e1d64fc604ae208d9eee356dd2ab">shift</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### extendToTBAA() {#a53468ec93dc5de2584b89a719ab34627}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * AAMDNodes::extendToTBAA (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * TBAA, ssize_t len)</td>
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



<p>Declaration at line 800 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 793 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantint/#ae2863695d9b93a15492fa489f4f85e09">llvm::ConstantInt::equalsInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp/#a5e19d69f8c65d343b518e66bef56db58">isStructPathTBAA</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a571612461ea4af620bc4c441d61579a3">llvm::MDNode::operands</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>


<p>Referenced by <a href="#abc415418337d16a2b07a2b8ab6e8dc36">extendTo</a>.</p>

</div>
</div>

### shiftTBAA() {#ad25413c097c370ed086055ecdbc75b1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * AAMDNodes::shiftTBAA (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * M, size_t off)</td>
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



<p>Declaration at line 793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 744 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp/#a5e19d69f8c65d343b518e66bef56db58">isStructPathTBAA</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a5f73e1d64fc604ae208d9eee356dd2ab">shift</a>.</p>

</div>
</div>

### shiftTBAAStruct() {#a25af03cf36c07d235f487e525e5dcd07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * AAMDNodes::shiftTBAAStruct (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * M, size_t off)</td>
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



<p>Declaration at line 796 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 763 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#ac09a21c371a9c535cbc13e8f82503aec">llvm::ConstantInt::getZExtValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>


<p>Referenced by <a href="#a5f73e1d64fc604ae208d9eee356dd2ab">shift</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp">TypeBasedAliasAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
