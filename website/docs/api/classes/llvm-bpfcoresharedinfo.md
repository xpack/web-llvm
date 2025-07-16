---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/bpfcoresharedinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BPFCoreSharedInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::BPFCoreSharedInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcore-h">Target/BPF/BPFCORE.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">BTFTypeIdFlag : uint32_t { <a href="#afa46679f06848e221706a3421f6cb995">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PreserveTypeInfo : uint32_t { <a href="#a72bd0b0c1f71f6d6b41db97476da3e80">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PreserveEnumValue : uint32_t { <a href="#abf9930915d15aa0be8bab24368dc4ce5">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adee485b8d8a010d18877f5f41286b079">insertPassThrough</a> (Module *M, BasicBlock *BB, Instruction *Input, Instruction *Before)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a bpf passthrough builtin function. <a href="#adee485b8d8a010d18877f5f41286b079">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04e285b845fc80b08ac9de9ee165eba8">removeArrayAccessCall</a> (CallInst *Call)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f48ea4e71fc12dd8df2cab7604733eb">removeStructAccessCall</a> (CallInst *Call)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4130d48cbde089a67670a64e0b96172">removeUnionAccessCall</a> (CallInst *Call)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6913d71a49a3da6e91a2afa6a0cf644">AmaAttr</a> = "btf_ama"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The attribute attached to globals representing a field access. <a href="#af6913d71a49a3da6e91a2afa6a0cf644">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa34216df2ec6cc3245ab11f1ac3775ed">TypeIdAttr</a> = "btf_type_id"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The attribute attached to globals representing a type id. <a href="#aa34216df2ec6cc3245ab11f1ac3775ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a204ed5d7cbae670b9a08ff15ed18d4aa">SeqNum</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>llvm.bpf.passthrough builtin seq number <a href="#a204ed5d7cbae670b9a08ff15ed18d4aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcore-h">BPFCORE.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### BTFTypeIdFlag {#afa46679f06848e221706a3421f6cb995}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::BPFCoreSharedInfo::BTFTypeIdFlag : uint32_t</td>
</tr>
</table>
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
<td class="doxyEnumItemName">BTF_TYPE_ID_LOCAL_RELOC<a id="afa46679f06848e221706a3421f6cb995afedcfc4d4b6376f695095aad3a363358"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BTF_TYPE_ID_REMOTE_RELOC<a id="afa46679f06848e221706a3421f6cb995aa1687a17537a8101fdb3b6abb76cf8c2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAX_BTF_TYPE_ID_FLAG<a id="afa46679f06848e221706a3421f6cb995a9062c35b270f617deb19f51a2850134d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcore-h">BPFCORE.h</a>.</p>

</div>
</div>

### PreserveEnumValue {#abf9930915d15aa0be8bab24368dc4ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::BPFCoreSharedInfo::PreserveEnumValue : uint32_t</td>
</tr>
</table>
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
<td class="doxyEnumItemName">PRESERVE_ENUM_VALUE_EXISTENCE<a id="abf9930915d15aa0be8bab24368dc4ce5a1003a7e958cea4b90a901d90230b93e7"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRESERVE_ENUM_VALUE<a id="abf9930915d15aa0be8bab24368dc4ce5a766a01794e6619acb783a233bd49793d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAX_PRESERVE_ENUM_VALUE_FLAG<a id="abf9930915d15aa0be8bab24368dc4ce5ad93c58a2446e48b22f1050261c49af57"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcore-h">BPFCORE.h</a>.</p>

</div>
</div>

### PreserveTypeInfo {#a72bd0b0c1f71f6d6b41db97476da3e80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::BPFCoreSharedInfo::PreserveTypeInfo : uint32_t</td>
</tr>
</table>
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
<td class="doxyEnumItemName">PRESERVE_TYPE_INFO_EXISTENCE<a id="a72bd0b0c1f71f6d6b41db97476da3e80a03be2c343e8e68c15daf556ebbf03c1c"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRESERVE_TYPE_INFO_SIZE<a id="a72bd0b0c1f71f6d6b41db97476da3e80ae675b33ca68dc4446dfa53bc3dec9c72"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PRESERVE_TYPE_INFO_MATCH<a id="a72bd0b0c1f71f6d6b41db97476da3e80ad7a6b49ef9bad33727d562a1f5a1103a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAX_PRESERVE_TYPE_INFO_FLAG<a id="a72bd0b0c1f71f6d6b41db97476da3e80a29fb712512702fe409518e1ab8265977"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcore-h">BPFCORE.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### insertPassThrough() {#adee485b8d8a010d18877f5f41286b079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::BPFCoreSharedInfo::insertPassThrough (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Input, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Before)</td>
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

<p>Insert a bpf passthrough builtin function.</p>

<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcore-h">BPFCORE.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#aa04721251be00370fbde6d21f47fed1a">llvm::CallInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aa286a0f7f5d38488d593bb7ef0ba183e">llvm::BasicBlock::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a> and <a href="#a204ed5d7cbae670b9a08ff15ed18d4aa">SeqNum</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-bpfpreserveditype-cpp-/#a72adf7d117af6ebe1a3aee68b6e3e782">anonymous{BPFPreserveDIType.cpp}::BPFPreserveDITypeImpl</a>.</p>

</div>
</div>

### removeArrayAccessCall() {#a04e285b845fc80b08ac9de9ee165eba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BPFCoreSharedInfo::removeArrayAccessCall (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * Call)</td>
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



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcore-h">BPFCORE.h</a>, definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp/#a36be37a99f7cf2fdd84b942e5dafba1b">replaceWithGEP</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a36fe1ed1682023b7fb3c4699f9009d31">removePAICalls</a>.</p>

</div>
</div>

### removeStructAccessCall() {#a2f48ea4e71fc12dd8df2cab7604733eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BPFCoreSharedInfo::removeStructAccessCall (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * Call)</td>
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



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcore-h">BPFCORE.h</a>, definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp/#a36be37a99f7cf2fdd84b942e5dafba1b">replaceWithGEP</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a36fe1ed1682023b7fb3c4699f9009d31">removePAICalls</a>.</p>

</div>
</div>

### removeUnionAccessCall() {#ab4130d48cbde089a67670a64e0b96172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BPFCoreSharedInfo::removeUnionAccessCall (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * Call)</td>
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



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcore-h">BPFCORE.h</a>, definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a36fe1ed1682023b7fb3c4699f9009d31">removePAICalls</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### AmaAttr {#af6913d71a49a3da6e91a2afa6a0cf644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::BPFCoreSharedInfo::AmaAttr = "btf_ama"</td>
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

<p>The attribute attached to globals representing a field access.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcore-h">BPFCORE.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a3b244792bc2277f0800d9e15c2eb935b">llvm::BTFDebug::InstLower</a>.</p>

</div>
</div>

### SeqNum {#a204ed5d7cbae670b9a08ff15ed18d4aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::BPFCoreSharedInfo::SeqNum</td>
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

<p>llvm.bpf.passthrough builtin seq number</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcore-h">BPFCORE.h</a>.</p>


<p>Referenced by <a href="#adee485b8d8a010d18877f5f41286b079">insertPassThrough</a>.</p>

</div>
</div>

### TypeIdAttr {#aa34216df2ec6cc3245ab11f1ac3775ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::BPFCoreSharedInfo::TypeIdAttr = "btf_type_id"</td>
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

<p>The attribute attached to globals representing a type id.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcore-h">BPFCORE.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-bpfpreserveditype-cpp-/#a72adf7d117af6ebe1a3aee68b6e3e782">anonymous{BPFPreserveDIType.cpp}::BPFPreserveDITypeImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a3b244792bc2277f0800d9e15c2eb935b">llvm::BTFDebug::InstLower</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp">BPFAbstractMemberAccess.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcore-h">BPFCORE.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
