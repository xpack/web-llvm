---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mdnodeopskey
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MDNodeOpsKey` Class Reference

<p>Structure for hashing arbitrary <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> operands. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MDNodeOpsKey { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">IR/LLVMContextImpl.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-790d8f2739f010df55f45d6a1d49d352">MDNodeKeyImpl&lt;GenericDINode&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a> for <a href="/web-llvm/docs/api/classes/llvm/genericdinode">GenericDINode</a>. <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-790d8f2739f010df55f45d6a1d49d352/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-4af0d7051d6a9d6ec61ff79a979bea68">MDNodeKeyImpl&lt;MDTuple&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a> for <a href="/web-llvm/docs/api/classes/llvm/mdtuple">MDTuple</a>. <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-4af0d7051d6a9d6ec61ff79a979bea68/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad08287a647a3ffe5c29b19bcff3dd42f">MDNodeOpsKey</a> (ArrayRef&lt; Metadata * &gt; Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa628cfe65b6dc4ae7f48348eef171ba8">MDNodeOpsKey</a> (const NodeTy *N, unsigned Offset=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac15988f3ec9cb4dd7685299349c408fe">getHash</a> () const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abe417f3bcbd5e957d1b91ba01bd01663">compareOps</a> (const NodeTy *RHS, unsigned Offset=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3bdc05e215cf8bcef868c5d57f4411b">RawOps</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mdoperand">MDOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0442799dd5f9f3fe2ebbcc674d217a6">Ops</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa002ca168fc8766a08230a6854299469">Hash</a></td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea1b184b8290b9c4bed5a42aaa6f1bb1">calculateHash</a> (MDNode *N, unsigned Offset=0)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a559b5151611836a688a0df26e988657f">compareOps</a> (ArrayRef&lt; T &gt; Ops, const MDNode *RHS, unsigned Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a975262b95040c006cced62c17b57de12">calculateHash</a> (ArrayRef&lt; Metadata * &gt; Ops)</td>
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

<p>Structure for hashing arbitrary <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> operands.</p>

<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### MDNodeOpsKey() {#ad08287a647a3ffe5c29b19bcff3dd42f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MDNodeOpsKey::MDNodeOpsKey (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; Ops)</td>
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



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Reference <a href="#aea1b184b8290b9c4bed5a42aaa6f1bb1">calculateHash</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-790d8f2739f010df55f45d6a1d49d352/#a5e9b70774f382997c37be2028a8c26fe">llvm::MDNodeKeyImpl&lt; GenericDINode &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-790d8f2739f010df55f45d6a1d49d352/#aea76ac02eabcef8a85166b9b6d7f5b3a">llvm::MDNodeKeyImpl&lt; GenericDINode &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-4af0d7051d6a9d6ec61ff79a979bea68/#a4a3399cabce5ac126981528bf7bbe083">llvm::MDNodeKeyImpl&lt; MDTuple &gt;::MDNodeKeyImpl</a> and <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-4af0d7051d6a9d6ec61ff79a979bea68/#a7d41b466a5e45cb1f341dbdb2a645b21">llvm::MDNodeKeyImpl&lt; MDTuple &gt;::MDNodeKeyImpl</a>.</p>

</div>
</div>

### MDNodeOpsKey() {#aa628cfe65b6dc4ae7f48348eef171ba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MDNodeOpsKey::MDNodeOpsKey (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeTy * N, unsigned Offset=0)</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="#ac15988f3ec9cb4dd7685299349c408fe">getHash</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getHash() {#ac15988f3ec9cb4dd7685299349c408fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MDNodeOpsKey::getHash ()</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#abe417f3bcbd5e957d1b91ba01bd01663">compareOps</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-790d8f2739f010df55f45d6a1d49d352/#a58b864575220e6ee98e3ef16b64971d5">llvm::MDNodeKeyImpl&lt; GenericDINode &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-4af0d7051d6a9d6ec61ff79a979bea68/#a9458d03372c48f8d6e4f8119752b93d4">llvm::MDNodeKeyImpl&lt; MDTuple &gt;::getHashValue</a> and <a href="#aa628cfe65b6dc4ae7f48348eef171ba8">MDNodeOpsKey</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### compareOps() {#abe417f3bcbd5e957d1b91ba01bd01663}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MDNodeOpsKey::compareOps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NodeTy * RHS, unsigned Offset=0)</td>
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



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abe417f3bcbd5e957d1b91ba01bd01663">compareOps</a>, <a href="#ac15988f3ec9cb4dd7685299349c408fe">getHash</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#abe417f3bcbd5e957d1b91ba01bd01663">compareOps</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-790d8f2739f010df55f45d6a1d49d352/#af39a42b5c29aaa9c6e755ad8572da8ef">llvm::MDNodeKeyImpl&lt; GenericDINode &gt;::isKeyOf</a> and <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-4af0d7051d6a9d6ec61ff79a979bea68/#a1bb875a9797fd7d2a450d887ce970c8c">llvm::MDNodeKeyImpl&lt; MDTuple &gt;::isKeyOf</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Hash {#aa002ca168fc8766a08230a6854299469}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MDNodeOpsKey::Hash</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### Ops {#aa0442799dd5f9f3fe2ebbcc674d217a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;MDOperand&gt; llvm::MDNodeOpsKey::Ops</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### RawOps {#ad3bdc05e215cf8bcef868c5d57f4411b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;Metadata *&gt; llvm::MDNodeOpsKey::RawOps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### calculateHash() {#aea1b184b8290b9c4bed5a42aaa6f1bb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDNodeOpsKey::calculateHash (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * N, unsigned Offset=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>, definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-cpp">LLVMContextImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aea1b184b8290b9c4bed5a42aaa6f1bb1">calculateHash</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af80edfc5e42059e045aa7bf7fe42bee3">llvm::hash_combine_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-790d8f2739f010df55f45d6a1d49d352/#a292d747f08f9f3205408e48de409547c">llvm::MDNodeKeyImpl&lt; GenericDINode &gt;::calculateHash</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-4af0d7051d6a9d6ec61ff79a979bea68/#adabb7a070201960968475b768df70c28">llvm::MDNodeKeyImpl&lt; MDTuple &gt;::calculateHash</a>, <a href="#aea1b184b8290b9c4bed5a42aaa6f1bb1">calculateHash</a> and <a href="#ad08287a647a3ffe5c29b19bcff3dd42f">MDNodeOpsKey</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### calculateHash() {#a975262b95040c006cced62c17b57de12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDNodeOpsKey::calculateHash (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; Ops)</td>
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



<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-cpp">LLVMContextImpl.cpp</a>.</p>

</div>
</div>

### compareOps() {#a559b5151611836a688a0df26e988657f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MDNodeOpsKey::compareOps (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt; Ops, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * RHS, unsigned Offset)</td>
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



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-cpp">LLVMContextImpl.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
