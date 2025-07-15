---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mdnodekeyimpl-da9e4b682a4b3039a31f92ca230d6551
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MDNodeKeyImpl` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::MDNodeKeyImpl&lt;DICompositeType&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">IR/LLVMContextImpl.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a> (unsigned Tag, MDString *Name, Metadata *File, unsigned Line, Metadata *Scope, Metadata *BaseType, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, unsigned Flags, Metadata *Elements, unsigned RuntimeLang, Metadata *VTableHolder, Metadata *TemplateParams, MDString *Identifier, Metadata *Discriminator, Metadata *DataLocation, Metadata *Associated, Metadata *Allocated, Metadata *Rank, Metadata *Annotations, Metadata *Specification, uint32_t NumExtraInhabitants)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> (const DICompositeType *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a> (const DICompositeType *RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b40905c199f3283d05441ed7c8ff160">getHashValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b8fbb061ce97e008d7ab096801a219b">Tag</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ea1750beaa1c518a7350f9b2f7389c9">Name</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a949d419d79d05dac964c04eb353fff50">File</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e2c86d46af2d5c6aa7221f87c5bd71e">Line</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e1a76eef9c34e09cabf00df4d12ade2">Scope</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e1218ad29a742472490f96304d86e4e">BaseType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bb6bc7b6067964faa175c8ce76974a5">SizeInBits</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5899258cd818c3912e0ab64b0c088ec2">OffsetInBits</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a334557c3b58b6033873e340769417b3a">AlignInBits</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa181a3e8225427e81d499fda5ed079ac">Flags</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef78e9eb86bdeb82f493a96e6f82ea63">Elements</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04099e819cfc3fdacf31d490e33ca8ac">RuntimeLang</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b6786ef0334251651939c2e50751f03">VTableHolder</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3311c66e7c1da1f62a5c1dc2ad7a330b">TemplateParams</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ae5eb15049513e2fb739210cd067b2b">Identifier</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2edd21e15fc2d61b94557786f631d92">Discriminator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3264d12efe78785d179b2fbbf2798751">DataLocation</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89562a270c585faa869b6d02a7ba3a15">Associated</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c6894711e0d1bfc0d20e48d976181a2">Allocated</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ab86b1b26143da6a8db1455e287fd1a">Rank</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32eca0a51e1705ba31435f5e195b92cb">Annotations</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb906b4ab51db2ad9342ee8bfaeefc26">Specification</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21f6eacf35c973435de5e0f382fc657d">NumExtraInhabitants</a></td>
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


<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MDNodeKeyImpl() {#ad85aac941678527a644da0245d6a3c97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::MDNodeKeyImpl (unsigned Tag, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> * Name, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * File, unsigned Line, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Scope, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * BaseType, uint64_t SizeInBits, uint32_t AlignInBits, uint64_t OffsetInBits, unsigned Flags, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Elements, unsigned RuntimeLang, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * VTableHolder, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * TemplateParams, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> * Identifier, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Discriminator, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * DataLocation, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Associated, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Allocated, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Rank, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Annotations, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Specification, uint32_t NumExtraInhabitants)</td>
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



<p>Definition at line 661 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#a334557c3b58b6033873e340769417b3a">AlignInBits</a>, <a href="#a6c6894711e0d1bfc0d20e48d976181a2">Allocated</a>, <a href="#a32eca0a51e1705ba31435f5e195b92cb">Annotations</a>, <a href="#a89562a270c585faa869b6d02a7ba3a15">Associated</a>, <a href="#a0e1218ad29a742472490f96304d86e4e">BaseType</a>, <a href="#a3264d12efe78785d179b2fbbf2798751">DataLocation</a>, <a href="#ae2edd21e15fc2d61b94557786f631d92">Discriminator</a>, <a href="#aef78e9eb86bdeb82f493a96e6f82ea63">Elements</a>, <a href="#a949d419d79d05dac964c04eb353fff50">File</a>, <a href="#aa181a3e8225427e81d499fda5ed079ac">Flags</a>, <a href="#a5ae5eb15049513e2fb739210cd067b2b">Identifier</a>, <a href="#a3e2c86d46af2d5c6aa7221f87c5bd71e">Line</a>, <a href="#a1ea1750beaa1c518a7350f9b2f7389c9">Name</a>, <a href="#a21f6eacf35c973435de5e0f382fc657d">NumExtraInhabitants</a>, <a href="#a5899258cd818c3912e0ab64b0c088ec2">OffsetInBits</a>, <a href="#a8ab86b1b26143da6a8db1455e287fd1a">Rank</a>, <a href="#a04099e819cfc3fdacf31d490e33ca8ac">RuntimeLang</a>, <a href="#a5e1a76eef9c34e09cabf00df4d12ade2">Scope</a>, <a href="#a4bb6bc7b6067964faa175c8ce76974a5">SizeInBits</a>, <a href="#abb906b4ab51db2ad9342ee8bfaeefc26">Specification</a>, <a href="#a7b8fbb061ce97e008d7ab096801a219b">Tag</a>, <a href="#a3311c66e7c1da1f62a5c1dc2ad7a330b">TemplateParams</a> and <a href="#a8b6786ef0334251651939c2e50751f03">VTableHolder</a>.</p>

</div>
</div>

### MDNodeKeyImpl() {#a92dc296b7b60e0848408156781b20ec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::MDNodeKeyImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * N)</td>
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



<p>Definition at line 679 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#a334557c3b58b6033873e340769417b3a">AlignInBits</a>, <a href="#a6c6894711e0d1bfc0d20e48d976181a2">Allocated</a>, <a href="#a32eca0a51e1705ba31435f5e195b92cb">Annotations</a>, <a href="#a89562a270c585faa869b6d02a7ba3a15">Associated</a>, <a href="#a0e1218ad29a742472490f96304d86e4e">BaseType</a>, <a href="#a3264d12efe78785d179b2fbbf2798751">DataLocation</a>, <a href="#ae2edd21e15fc2d61b94557786f631d92">Discriminator</a>, <a href="#aef78e9eb86bdeb82f493a96e6f82ea63">Elements</a>, <a href="#a949d419d79d05dac964c04eb353fff50">File</a>, <a href="#aa181a3e8225427e81d499fda5ed079ac">Flags</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a7a3ba7cd94762ae7f243367830320ca2">getFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a8094520fe3fe9f3967fe72b7266a2f68">getTag</a>, <a href="#a5ae5eb15049513e2fb739210cd067b2b">Identifier</a>, <a href="#a3e2c86d46af2d5c6aa7221f87c5bd71e">Line</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a1ea1750beaa1c518a7350f9b2f7389c9">Name</a>, <a href="#a21f6eacf35c973435de5e0f382fc657d">NumExtraInhabitants</a>, <a href="#a5899258cd818c3912e0ab64b0c088ec2">OffsetInBits</a>, <a href="#a8ab86b1b26143da6a8db1455e287fd1a">Rank</a>, <a href="#a04099e819cfc3fdacf31d490e33ca8ac">RuntimeLang</a>, <a href="#a5e1a76eef9c34e09cabf00df4d12ade2">Scope</a>, <a href="#a4bb6bc7b6067964faa175c8ce76974a5">SizeInBits</a>, <a href="#abb906b4ab51db2ad9342ee8bfaeefc26">Specification</a>, <a href="#a7b8fbb061ce97e008d7ab096801a219b">Tag</a>, <a href="#a3311c66e7c1da1f62a5c1dc2ad7a330b">TemplateParams</a> and <a href="#a8b6786ef0334251651939c2e50751f03">VTableHolder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getHashValue() {#a2b40905c199f3283d05441ed7c8ff160}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::getHashValue ()</td>
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



<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#a32eca0a51e1705ba31435f5e195b92cb">Annotations</a>, <a href="#a0e1218ad29a742472490f96304d86e4e">BaseType</a>, <a href="#aef78e9eb86bdeb82f493a96e6f82ea63">Elements</a>, <a href="#a949d419d79d05dac964c04eb353fff50">File</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add71474638430694c84640146383fc44">llvm::hash_combine</a>, <a href="#a3e2c86d46af2d5c6aa7221f87c5bd71e">Line</a>, <a href="#a1ea1750beaa1c518a7350f9b2f7389c9">Name</a>, <a href="#a5e1a76eef9c34e09cabf00df4d12ade2">Scope</a> and <a href="#a3311c66e7c1da1f62a5c1dc2ad7a330b">TemplateParams</a>.</p>

</div>
</div>

### isKeyOf() {#adac5b25ef14bbfa0b913373c03847ec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::isKeyOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * RHS)</td>
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



<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#a334557c3b58b6033873e340769417b3a">AlignInBits</a>, <a href="#a6c6894711e0d1bfc0d20e48d976181a2">Allocated</a>, <a href="#a32eca0a51e1705ba31435f5e195b92cb">Annotations</a>, <a href="#a89562a270c585faa869b6d02a7ba3a15">Associated</a>, <a href="#a0e1218ad29a742472490f96304d86e4e">BaseType</a>, <a href="#a3264d12efe78785d179b2fbbf2798751">DataLocation</a>, <a href="#ae2edd21e15fc2d61b94557786f631d92">Discriminator</a>, <a href="#aef78e9eb86bdeb82f493a96e6f82ea63">Elements</a>, <a href="#a949d419d79d05dac964c04eb353fff50">File</a>, <a href="#aa181a3e8225427e81d499fda5ed079ac">Flags</a>, <a href="#a5ae5eb15049513e2fb739210cd067b2b">Identifier</a>, <a href="#a3e2c86d46af2d5c6aa7221f87c5bd71e">Line</a>, <a href="#a1ea1750beaa1c518a7350f9b2f7389c9">Name</a>, <a href="#a21f6eacf35c973435de5e0f382fc657d">NumExtraInhabitants</a>, <a href="#a5899258cd818c3912e0ab64b0c088ec2">OffsetInBits</a>, <a href="#a8ab86b1b26143da6a8db1455e287fd1a">Rank</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#a04099e819cfc3fdacf31d490e33ca8ac">RuntimeLang</a>, <a href="#a5e1a76eef9c34e09cabf00df4d12ade2">Scope</a>, <a href="#a4bb6bc7b6067964faa175c8ce76974a5">SizeInBits</a>, <a href="#abb906b4ab51db2ad9342ee8bfaeefc26">Specification</a>, <a href="#a7b8fbb061ce97e008d7ab096801a219b">Tag</a>, <a href="#a3311c66e7c1da1f62a5c1dc2ad7a330b">TemplateParams</a> and <a href="#a8b6786ef0334251651939c2e50751f03">VTableHolder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AlignInBits {#a334557c3b58b6033873e340769417b3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::AlignInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Allocated {#a6c6894711e0d1bfc0d20e48d976181a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::Allocated</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Annotations {#a32eca0a51e1705ba31435f5e195b92cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::Annotations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a2b40905c199f3283d05441ed7c8ff160">getHashValue</a>, <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Associated {#a89562a270c585faa869b6d02a7ba3a15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::Associated</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 654 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### BaseType {#a0e1218ad29a742472490f96304d86e4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::BaseType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 642 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a2b40905c199f3283d05441ed7c8ff160">getHashValue</a>, <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### DataLocation {#a3264d12efe78785d179b2fbbf2798751}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::DataLocation</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Discriminator {#ae2edd21e15fc2d61b94557786f631d92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::Discriminator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Elements {#aef78e9eb86bdeb82f493a96e6f82ea63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::Elements</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 647 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a2b40905c199f3283d05441ed7c8ff160">getHashValue</a>, <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### File {#a949d419d79d05dac964c04eb353fff50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::File</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 639 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a2b40905c199f3283d05441ed7c8ff160">getHashValue</a>, <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Flags {#aa181a3e8225427e81d499fda5ed079ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Identifier {#a5ae5eb15049513e2fb739210cd067b2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString* llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::Identifier</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Line {#a3e2c86d46af2d5c6aa7221f87c5bd71e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::Line</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a2b40905c199f3283d05441ed7c8ff160">getHashValue</a>, <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Name {#a1ea1750beaa1c518a7350f9b2f7389c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString* llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 638 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a2b40905c199f3283d05441ed7c8ff160">getHashValue</a>, <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### NumExtraInhabitants {#a21f6eacf35c973435de5e0f382fc657d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::NumExtraInhabitants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### OffsetInBits {#a5899258cd818c3912e0ab64b0c088ec2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::OffsetInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 644 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Rank {#a8ab86b1b26143da6a8db1455e287fd1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::Rank</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### RuntimeLang {#a04099e819cfc3fdacf31d490e33ca8ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::RuntimeLang</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Scope {#a5e1a76eef9c34e09cabf00df4d12ade2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::Scope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a2b40905c199f3283d05441ed7c8ff160">getHashValue</a>, <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### SizeInBits {#a4bb6bc7b6067964faa175c8ce76974a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::SizeInBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Specification {#abb906b4ab51db2ad9342ee8bfaeefc26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::Specification</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### Tag {#a7b8fbb061ce97e008d7ab096801a219b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::Tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### TemplateParams {#a3311c66e7c1da1f62a5c1dc2ad7a330b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::TemplateParams</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a2b40905c199f3283d05441ed7c8ff160">getHashValue</a>, <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

### VTableHolder {#a8b6786ef0334251651939c2e50751f03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata* llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::VTableHolder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#adac5b25ef14bbfa0b913373c03847ec0">isKeyOf</a>, <a href="#a92dc296b7b60e0848408156781b20ec4">MDNodeKeyImpl</a> and <a href="#ad85aac941678527a644da0245d6a3c97">MDNodeKeyImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
