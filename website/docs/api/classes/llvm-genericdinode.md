---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/genericdinode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GenericDINode` Class

<p>Generic tagged DWARF-like metadata node. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GenericDINode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dinode">DINode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tagged DWARF-like metadata node. <a href="/web-llvm/docs/api/classes/llvm/dinode/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54f6b3943b867c81b6e2c7938b7dabbe">GenericDINode</a> (LLVMContext &amp;C, StorageType Storage, unsigned Hash, unsigned Tag, ArrayRef&lt; Metadata * &gt; Ops1, ArrayRef&lt; Metadata * &gt; Ops2)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af20dec707bf9d1831de1cd23dcf1a3a8">~GenericDINode</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81e1c815a784ebc18b9da4f20b82c316">getHash</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeec7f4c294470ea63b2550eb29f6510d">DEFINE_MDNODE_GET</a> (GenericDINode,(unsigned Tag, StringRef Header, ArrayRef&lt; Metadata * &gt; DwarfOps),(Tag, Header, DwarfOps)) DEFINE_MDNODE_GET(GenericDINode</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; <a href="#af77aeddf246dc7ee1ebba5efbbae913f">DwarfOps</a> TempGenericDINode</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55eb6a1c4eda71ae5078fbd1786b69f1">clone</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a (temporary) clone of this. <a href="#a55eb6a1c4eda71ae5078fbd1786b69f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59dbb6700371ed996351198327711511">getTag</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6098a5f2bb7ce800d3b40898e496da0b">getHeader</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a735f9c8f921f913d9332f0b498c90ba9">getRawHeader</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode/#af4fe559b6ceafad40f7144063ef2afd2">op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fb1b5d06540b7a1d8eb97f1a070b133">dwarf_op_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode/#af4fe559b6ceafad40f7144063ef2afd2">op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90265fce01af75775c8ad8a7be3d3b61">dwarf_op_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa71d94c1b9fee4fa58f9cee65a713e66">op_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acca183c390d40cddeec0646c7f54df63">dwarf_operands</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87935febcbafd8fa07e6ec6c4033c3d3">getNumDwarfOperands</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdoperand">MDOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80c7c493a0d195e2ecf3a6b0bba186f8">getDwarfOperand</a> (unsigned I) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af664491ebc87fc1a8ed616b25f502804">replaceDwarfOperandWith</a> (unsigned I, Metadata *New)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05e8ef8b8bd09c9d001ec485f3902b13">setHash</a> (unsigned Hash)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f8834fea8f2a45a198a9f3bfcc80294">recalculateHash</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">TempGenericDINode</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030aa5981b2da03e10047086032200da">cloneImpl</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2284e46e3937ec09ec40cbd2dbd6553c">Tag</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6b3304f8fed0899a95221df3b8b9b5b">Header</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af77aeddf246dc7ee1ebba5efbbae913f">DwarfOps</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7b27caa7800593920e72020e1e5fdf7">Tag</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04e9065dc98f0686739c3e0f0bbd178b">Header</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d8f45c731f112d2b0d4af8ce0bbd140">classof</a> (const Metadata *MD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/genericdinode">GenericDINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af53b7e477747787ef186557f631679b0">getImpl</a> (LLVMContext &amp;Context, unsigned Tag, StringRef Header, ArrayRef&lt; Metadata * &gt; DwarfOps, StorageType Storage, bool ShouldCreate=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/genericdinode">GenericDINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78e28bab876c5ea1a736d13dfaf4b10d">getImpl</a> (LLVMContext &amp;Context, unsigned Tag, MDString *Header, ArrayRef&lt; Metadata * &gt; DwarfOps, StorageType Storage, bool ShouldCreate=true)</td>
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

<p>Generic tagged DWARF-like metadata node.</p>


<p>An un-specialized DWARF-like metadata node. The first operand is a (possibly empty) null-separated <em><a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a></em> header that contains arbitrary fields. The remaining operands are <em><a href="#acca183c390d40cddeec0646c7f54df63">dwarf_operands()</a></em>, and are pointers to other metadata.</p>


<p>Uses the SubclassData32 <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> slot.</p>


<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


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


<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


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


<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/dinode/#a8af3feaeaaec959e6d272d70d06213b6">llvm::DINode::DINode</a>, <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a8265bf29997e9e49d47a38a762d4bb0f">llvm::Metadata::Storage</a> and <a href="#a2284e46e3937ec09ec40cbd2dbd6553c">Tag</a>.</p>


<p>Referenced by <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### GenericDINode() {#a54f6b3943b867c81b6e2c7938b7dabbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericDINode::GenericDINode (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, unsigned Hash, unsigned Tag, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; Ops1, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; Ops2)</td>
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



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~GenericDINode() {#af20dec707bf9d1831de1cd23dcf1a3a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericDINode::~GenericDINode ()</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#a55eb6a1c4eda71ae5078fbd1786b69f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString ArrayRef&lt; Metadata * &gt; DwarfOps TempGenericDINode llvm::GenericDINode::clone ()</td>
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

<p>Return a (temporary) clone of this.</p>

<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="#a55eb6a1c4eda71ae5078fbd1786b69f1">clone</a>.</p>


<p>Referenced by <a href="#a55eb6a1c4eda71ae5078fbd1786b69f1">clone</a>.</p>

</div>
</div>

### DEFINE\_MDNODE\_GET() {#aeec7f4c294470ea63b2550eb29f6510d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericDINode::DEFINE_MDNODE_GET (<a href="/web-llvm/docs/api/classes/llvm/genericdinode">GenericDINode</a>, (unsigned <a href="#a2284e46e3937ec09ec40cbd2dbd6553c">Tag</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="#ab6b3304f8fed0899a95221df3b8b9b5b">Header</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; <a href="#af77aeddf246dc7ee1ebba5efbbae913f">DwarfOps</a>), (<a href="#a2284e46e3937ec09ec40cbd2dbd6553c">Tag</a>, <a href="#ab6b3304f8fed0899a95221df3b8b9b5b">Header</a>, <a href="#af77aeddf246dc7ee1ebba5efbbae913f">DwarfOps</a>))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="#af77aeddf246dc7ee1ebba5efbbae913f">DwarfOps</a>, <a href="#ab6b3304f8fed0899a95221df3b8b9b5b">Header</a> and <a href="#a2284e46e3937ec09ec40cbd2dbd6553c">Tag</a>.</p>

</div>
</div>

### dwarf\_op\_begin() {#a9fb1b5d06540b7a1d8eb97f1a070b133}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_iterator llvm::GenericDINode::dwarf_op_begin ()</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ac9a44b78ebdc1a9be01a96cc5e3bbb59">llvm::MDNode::op_begin</a>.</p>


<p>Referenced by <a href="#acca183c390d40cddeec0646c7f54df63">dwarf_operands</a>.</p>

</div>
</div>

### dwarf\_op\_end() {#a90265fce01af75775c8ad8a7be3d3b61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_iterator llvm::GenericDINode::dwarf_op_end ()</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a679e07915a76a131faa1460665755151">llvm::MDNode::op_end</a>.</p>


<p>Referenced by <a href="#acca183c390d40cddeec0646c7f54df63">dwarf_operands</a>.</p>

</div>
</div>

### dwarf\_operands() {#acca183c390d40cddeec0646c7f54df63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_range llvm::GenericDINode::dwarf_operands ()</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="#a9fb1b5d06540b7a1d8eb97f1a070b133">dwarf_op_begin</a> and <a href="#a90265fce01af75775c8ad8a7be3d3b61">dwarf_op_end</a>.</p>

</div>
</div>

### getDwarfOperand() {#a80c7c493a0d195e2ecf3a6b0bba186f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MDOperand &amp; llvm::GenericDINode::getDwarfOperand (unsigned I)</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getHash() {#a81e1c815a784ebc18b9da4f20b82c316}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GenericDINode::getHash ()</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/metadata/#a77e771a2105567c5db8a9a74f7bb9da3">llvm::Metadata::SubclassData32</a>.</p>

</div>
</div>

### getHeader() {#a6098a5f2bb7ce800d3b40898e496da0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::GenericDINode::getHeader ()</td>
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



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dinode/#a8ca691a16f8c92064df94a30b246b916">llvm::DINode::getStringOperand</a>.</p>

</div>
</div>

### getNumDwarfOperands() {#a87935febcbafd8fa07e6ec6c4033c3d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GenericDINode::getNumDwarfOperands ()</td>
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



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a>.</p>

</div>
</div>

### getRawHeader() {#a735f9c8f921f913d9332f0b498c90ba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString * llvm::GenericDINode::getRawHeader ()</td>
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



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dinode/#a928838d3e896f53856bd269829ddf5e0">llvm::DINode::getOperandAs</a>.</p>

</div>
</div>

### getTag() {#a59dbb6700371ed996351198327711511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Tag GenericDINode::getTag ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/metadata/#a72ff55650cd3d97745402a6cb76c1b3e">llvm::Metadata::SubclassData16</a>.</p>

</div>
</div>

### replaceDwarfOperandWith() {#af664491ebc87fc1a8ed616b25f502804}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericDINode::replaceDwarfOperandWith (unsigned I, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * New)</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a160e9e1a4fd597f83034c8b2ba316984">llvm::MDNode::replaceOperandWith</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### cloneImpl() {#a030aa5981b2da03e10047086032200da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TempGenericDINode llvm::GenericDINode::cloneImpl ()</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### recalculateHash() {#a2f8834fea8f2a45a198a9f3bfcc80294}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GenericDINode::recalculateHash ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>

</div>
</div>

### setHash() {#a05e8ef8b8bd09c9d001ec485f3902b13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GenericDINode::setHash (unsigned Hash)</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DwarfOps {#af77aeddf246dc7ee1ebba5efbbae913f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString ArrayRef&lt;Metadata *&gt; llvm::GenericDINode::DwarfOps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#aeec7f4c294470ea63b2550eb29f6510d">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### Header {#ab6b3304f8fed0899a95221df3b8b9b5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString* llvm::GenericDINode::Header</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#aeec7f4c294470ea63b2550eb29f6510d">DEFINE_MDNODE_GET</a>.</p>

</div>
</div>

### Header {#a04e9065dc98f0686739c3e0f0bbd178b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString ArrayRef&lt;Metadata *&gt; llvm::GenericDINode::Header</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### Tag {#a2284e46e3937ec09ec40cbd2dbd6553c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GenericDINode::Tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#aeec7f4c294470ea63b2550eb29f6510d">DEFINE_MDNODE_GET</a> and <a href="#acf51c34793180f67be514c1d6e4167f3">MDNode</a>.</p>

</div>
</div>

### Tag {#ac7b27caa7800593920e72020e1e5fdf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MDString ArrayRef&lt;Metadata *&gt; llvm::GenericDINode::Tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a4d8f45c731f112d2b0d4af8ce0bbd140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GenericDINode::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD)</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/metadata/#a91c7b9c7cf6694f41b9030429b582d26">llvm::Metadata::getMetadataID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getImpl() {#af53b7e477747787ef186557f631679b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericDINode * llvm::GenericDINode::getImpl (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, unsigned Tag, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Header, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; DwarfOps, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, bool ShouldCreate=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### getImpl() {#a78e28bab876c5ea1a736d13dfaf4b10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericDINode * GenericDINode::getImpl (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, unsigned Tag, <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> * Header, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * &gt; DwarfOps, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a3f931bc86bd57cd5ea0f53528ae88f80">StorageType</a> Storage, bool ShouldCreate=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Declaration at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>

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
