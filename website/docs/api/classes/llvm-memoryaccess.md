---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memoryaccess
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MemoryAccess` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MemoryAccess { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">llvm/Analysis/MemorySSA.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/deriveduser">DerivedUser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/extension">Extension</a> point for the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> hierarchy. <a href="/web-llvm/docs/api/classes/llvm/deriveduser/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node&lt;T, Options&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node&lt;T, Options&gt;</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryphi">MemoryPhi</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents phi nodes for memory accesses. <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryuseordef">MemoryUseOrDef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class that has the common methods + fields of memory uses/defs. <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6da91be15b430bca4a68c9d0cd15b23c">AllAccessType</a> = <a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-tag">ilist_tag</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mssahelpers/allaccesstag">MSSAHelpers::AllAccessTag</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92c9e4b2a29af6dd656a7672b062913f">DefsOnlyType</a> = <a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-tag">ilist_tag</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mssahelpers/defsonlytag">MSSAHelpers::DefsOnlyTag</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b793bc0883df3a0b7b7afe9ec43dfc6">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/value/#acd2fbee42afeb868be98aaae56528636">user_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The user iterators for a memory access. <a href="#a9b793bc0883df3a0b7b7afe9ec43dfc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebcc722800c62965a8a41a0ab4f98527">const_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/value/#a146665db2d7a79fa164098370a3a34c4">const_user_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a989b4c996f27373edde01fe749a72961">MemoryDef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cb5a37cd09a809853831406bd139a79">MemoryPhi</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a049277aa22bd6d1efded38d340c37960">MemorySSA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a348fb6ffcc26b7c17ceb5c6b76ec5f31">MemoryUse</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a574278457b55647c422ca78ba83eb04e">MemoryUseOrDef</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b9eff8c50a34b8b28a26dc74f949fca">MemoryAccess</a> (const MemoryAccess &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a866e08b474db229fb44b37b329f65240">MemoryAccess</a> (LLVMContext &amp;C, unsigned Vty, DeleteValueTy DeleteValue, BasicBlock *BB, AllocInfo AllocInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81df4b6539b9b7b95dc08641f4585e94">~MemoryAccess</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4071a3d782a43d229380c3adb127ceb">operator=</a> (const MemoryAccess &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71a31d17991a93f1ce6429d4414de3e8">operator new</a> (size_t)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a9c59da949d32a269725b6e254d426f">getBlock</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadff5eaae30623b4077b9dec90f29dcf">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0323cfb2d9032e14069108390831f5b7">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aec5f4ddc48f269887307e09fae57bf7f">memoryaccess_def_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3268bc2d8e89a606bb23b741d05fa0c">defs_begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This iterator walks over all of the defs in a given <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a>. <a href="#af3268bc2d8e89a606bb23b741d05fa0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ac94f37be30dce2df77b014b804b6a70b">const_memoryaccess_def_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f357487de140ef7f4669b4acc1ea751">defs_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aec5f4ddc48f269887307e09fae57bf7f">memoryaccess_def_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a750c6ded9231937aab94621a2deff127">defs_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ac94f37be30dce2df77b014b804b6a70b">const_memoryaccess_def_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a459c6a69c7c8938b780d0ed18684ba78">defs_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#a69f57da2cbacc606919dd017badf7da1">AllAccessType::self_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9653b051f47859d60d83527d0460e87">getIterator</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the iterators for the all access list and the defs only list We default to the all access list. <a href="#af9653b051f47859d60d83527d0460e87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#a062ff5e5271611eab47e721ed04fb5e6">AllAccessType::const_self_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fc1bd8c18c606de91bfce96a9ce7b50">getIterator</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#ad170cf283717735d286c0d6975a9ccfa">AllAccessType::reverse_self_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0335bbe7f97148c901d8cd85ef2b7858">getReverseIterator</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#a5d9f729fc5a6da4e689f24e7b28fc37e">AllAccessType::const_reverse_self_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa921b533f8d032b3db40d3ff42cf3767">getReverseIterator</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#a69f57da2cbacc606919dd017badf7da1">DefsOnlyType::self_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6141f01c038a2c06c7b2e8f434aa81b6">getDefsIterator</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#a062ff5e5271611eab47e721ed04fb5e6">DefsOnlyType::const_self_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5910c0aae54b0639798fd96cc8450b45">getDefsIterator</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#ad170cf283717735d286c0d6975a9ccfa">DefsOnlyType::reverse_self_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d56464060a479164dcac19b3a0fd7e3">getReverseDefsIterator</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#a5d9f729fc5a6da4e689f24e7b28fc37e">DefsOnlyType::const_reverse_self_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a707579b9929664f975f53cb858685397">getReverseDefsIterator</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaa94f3c67c7301f0172b1aa9dad07fe">setBlock</a> (BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used by <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> to change the block of a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> when it is moved. <a href="#adaa94f3c67c7301f0172b1aa9dad07fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3a9d1e32d4473460c83d5db60bd0d8b">getID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used for debugging and tracking things about MemoryAccesses. <a href="#ab3a9d1e32d4473460c83d5db60bd0d8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76be6234df997d597b3fcf26e1d54c71">Block</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20129d55ad455c11e932d68e4bd32581">classof</a> (const Value *V)</td>
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


<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### AllAccessType {#a6da91be15b430bca4a68c9d0cd15b23c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemoryAccess::AllAccessType = 
      ilist_node&lt;MemoryAccess, ilist_tag&lt;MSSAHelpers::AllAccessTag&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### const\_iterator {#aebcc722800c62965a8a41a0ab4f98527}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemoryAccess::const_iterator =  const_user_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### DefsOnlyType {#a92c9e4b2a29af6dd656a7672b062913f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemoryAccess::DefsOnlyType = 
      ilist_node&lt;MemoryAccess, ilist_tag&lt;MSSAHelpers::DefsOnlyTag&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### iterator {#a9b793bc0883df3a0b7b7afe9ec43dfc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MemoryAccess::iterator =  user_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The user iterators for a memory access.</p>

<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### MemoryDef {#a989b4c996f27373edde01fe749a72961}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/memorydef">MemoryDef</a></td>
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


<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="#a989b4c996f27373edde01fe749a72961">MemoryDef</a>.</p>


<p>Referenced by <a href="#a989b4c996f27373edde01fe749a72961">MemoryDef</a> and <a href="#aadff5eaae30623b4077b9dec90f29dcf">print</a>.</p>

</div>
</div>

### MemoryPhi {#a5cb5a37cd09a809853831406bd139a79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/memoryphi">MemoryPhi</a></td>
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


<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="#a5cb5a37cd09a809853831406bd139a79">MemoryPhi</a>.</p>


<p>Referenced by <a href="#a5cb5a37cd09a809853831406bd139a79">MemoryPhi</a> and <a href="#aadff5eaae30623b4077b9dec90f29dcf">print</a>.</p>

</div>
</div>

### MemorySSA {#a049277aa22bd6d1efded38d340c37960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a></td>
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


<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="#a049277aa22bd6d1efded38d340c37960">MemorySSA</a>.</p>


<p>Referenced by <a href="#a049277aa22bd6d1efded38d340c37960">MemorySSA</a>.</p>

</div>
</div>

### MemoryUse {#a348fb6ffcc26b7c17ceb5c6b76ec5f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/memoryuse">MemoryUse</a></td>
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


<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="#a348fb6ffcc26b7c17ceb5c6b76ec5f31">MemoryUse</a>.</p>


<p>Referenced by <a href="#a348fb6ffcc26b7c17ceb5c6b76ec5f31">MemoryUse</a> and <a href="#aadff5eaae30623b4077b9dec90f29dcf">print</a>.</p>

</div>
</div>

### MemoryUseOrDef {#a574278457b55647c422ca78ba83eb04e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef">MemoryUseOrDef</a></td>
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


<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="#a574278457b55647c422ca78ba83eb04e">MemoryUseOrDef</a>.</p>


<p>Referenced by <a href="#a574278457b55647c422ca78ba83eb04e">MemoryUseOrDef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MemoryAccess() {#a1b9eff8c50a34b8b28a26dc74f949fca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemoryAccess::MemoryAccess (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="#a1b9eff8c50a34b8b28a26dc74f949fca">MemoryAccess</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#ab9945ed381faa9dbee65a92e6225768d">llvm::MemoryPhi::addIncoming</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#a1b93fa16dd0d9ce7a029e2db5e3035a0">llvm::MemoryPhi::DECLARE_TRANSPARENT_OPERAND_ACCESSORS</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#a792e0faf86cbefc35a8882c9aeee602d">llvm::MemoryUseOrDef::DECLARE_TRANSPARENT_OPERAND_ACCESSORS</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#a20455da69cab73871b8c0111f0afe712">llvm::MemoryUseOrDef::getDefiningAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#ad9a4d921199ae54b411ddadde3530a0f">llvm::MemoryPhi::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#a24ab20ad79a1c1164e68c2244282d72c">llvm::MemoryPhi::getIncomingValueForBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#a21c9af41f764a585b597e61dc8c92e19">llvm::MemoryUseOrDef::getOptimized</a>, <a href="#a1b9eff8c50a34b8b28a26dc74f949fca">MemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#ad97f929f3156780ebc1bb6f35749de92">llvm::MemoryPhi::MemoryPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#a19b6da2dcbf49628676be73a2ccd2e3e">llvm::MemoryUseOrDef::MemoryUseOrDef</a>, <a href="#ac4071a3d782a43d229380c3adb127ceb">operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#ad75b48c94bacfc6a1d166164bd51af8b">llvm::MemoryPhi::print</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#a5c00de32cf1426ab78c346e7a251d608">llvm::MemoryUseOrDef::setDefiningAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#a055daa2efd196d7b72c0f2d36019854e">llvm::MemoryPhi::setIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#a7511908f467d3bc7c3c2428994134244">llvm::MemoryUseOrDef::setOptimized</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#aceabdea6bb478bd1b6e26c787e3c53ac">llvm::MemoryPhi::unorderedDeleteIncomingBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#a0b0c413123de1971c266455a4672ea54">llvm::MemoryPhi::unorderedDeleteIncomingValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### MemoryAccess() {#a866e08b474db229fb44b37b329f65240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemoryAccess::MemoryAccess (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned Vty, <a href="/web-llvm/docs/api/classes/llvm/deriveduser/#a669415c3e7013700123a78ed8a10651c">DeleteValueTy</a> DeleteValue, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/structs/llvm/user/allocinfo">AllocInfo</a> AllocInfo)</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/classes/llvm/deriveduser/#a88f2e1a4bb7547921039149d75b78c05">llvm::DerivedUser::DerivedUser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~MemoryAccess() {#a81df4b6539b9b7b95dc08641f4585e94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemoryAccess::~MemoryAccess ()</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator new() {#a71a31d17991a93f1ce6429d4414de3e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::MemoryAccess::operator new (size_t)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### operator=() {#ac4071a3d782a43d229380c3adb127ceb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess &amp; llvm::MemoryAccess::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="#a1b9eff8c50a34b8b28a26dc74f949fca">MemoryAccess</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### defs\_begin() {#af3268bc2d8e89a606bb23b741d05fa0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">memoryaccess_def_iterator llvm::MemoryAccess::defs_begin ()</td>
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

<p>This iterator walks over all of the defs in a given <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a>.</p>


<p>For <a href="/web-llvm/docs/api/classes/llvm/memoryphi">MemoryPhi</a> nodes, this walks arguments. For MemoryUse/MemoryDef, this walks the defining access.</p>


<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### defs\_begin() {#a0f357487de140ef7f4669b4acc1ea751}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_memoryaccess_def_iterator llvm::MemoryAccess::defs_begin ()</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### defs\_end() {#a750c6ded9231937aab94621a2deff127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">memoryaccess_def_iterator llvm::MemoryAccess::defs_end ()</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### defs\_end() {#a459c6a69c7c8938b780d0ed18684ba78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_memoryaccess_def_iterator llvm::MemoryAccess::defs_end ()</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

### dump() {#a0323cfb2d9032e14069108390831f5b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemoryAccess::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 2272 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#afa9b4a650e1a6de2061538a19be3a234">llvm::MemorySSA::print</a>.</p>

</div>
</div>

### getBlock() {#a9a9c59da949d32a269725b6e254d426f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::MemoryAccess::getBlock ()</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp/#a732b03e0a47de172531cbae6e0ae0193">accessedBetween</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#acf9a0bb25aae89d274ee9ae7dd0cf9b2">llvm::MemorySSAUpdater::createMemoryAccessAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a1c21c2f4d41d5c6f6807992d60347bbd">llvm::MemorySSAUpdater::createMemoryAccessBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a56004f54560e9950f6eb148cb5dfa0a3">llvm::MemorySSA::dominates</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a4e92272bbf0049770569394d4956918b">llvm::MemorySSA::dominates</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#acdd3b591101453540fdf4b9d17d49100">anonymous{DeadStoreElimination.cpp}::DSEState::eliminateDeadDefs</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a0b9027fe8e7ff91d9d6ee565fbdb3db4">anonymous{DeadStoreElimination.cpp}::DSEState::getDomMemoryDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae78f734e49b5ad94836bf32dda101ec6">llvm::hasPartialIVCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a21fc5eae685ef3e2dce4403a75d5ff2f">llvm::MemorySSAUpdater::insertDef</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a9ab9d33dbeb44b5ba49ab27201e6bd76">llvm::MemorySSAUpdater::insertUse</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#ade88aedcbd2b55711000cf3e36c0fc91">llvm::MemorySSA::locallyDominates</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a2d537a2dd5afbd1eba9a402cda94e067">llvm::MemorySSAUpdater::moveAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#af58e16a1d7ebc8f202ae2f8037b42df6">llvm::MemorySSAUpdater::moveBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a13073dfc4fd40b8388fb60885e493f8d">llvm::MemorySSA::moveTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#aed7e046ac6f7dd5ff0edb6e7b7a30e2e">pointerInvalidatedByBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#ae20e35b50e6cf67987421c996cf14a8c">llvm::MemorySSA::removeFromLists</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#acd0427b84adce00e5b26f993c7aa48c8">llvm::MemorySSA::removeFromLookups</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp/#ab06d3147949b764919b5ad90014afdfd">writtenBetween</a>.</p>

</div>
</div>

### getDefsIterator() {#a6141f01c038a2c06c7b2e8f434aa81b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefsOnlyType::self_iterator llvm::MemoryAccess::getDefsIterator ()</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>.</p>

</div>
</div>

### getDefsIterator() {#a5910c0aae54b0639798fd96cc8450b45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefsOnlyType::const_self_iterator llvm::MemoryAccess::getDefsIterator ()</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>.</p>

</div>
</div>

### getIterator() {#af9653b051f47859d60d83527d0460e87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllAccessType::self_iterator llvm::MemoryAccess::getIterator ()</td>
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

<p>Get the iterators for the all access list and the defs only list We default to the all access list.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp/#a732b03e0a47de172531cbae6e0ae0193">accessedBetween</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#acf9a0bb25aae89d274ee9ae7dd0cf9b2">llvm::MemorySSAUpdater::createMemoryAccessAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a1c21c2f4d41d5c6f6807992d60347bbd">llvm::MemorySSAUpdater::createMemoryAccessBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a2d537a2dd5afbd1eba9a402cda94e067">llvm::MemorySSAUpdater::moveAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#af58e16a1d7ebc8f202ae2f8037b42df6">llvm::MemorySSAUpdater::moveBefore</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp/#ab06d3147949b764919b5ad90014afdfd">writtenBetween</a>.</p>

</div>
</div>

### getIterator() {#a0fc1bd8c18c606de91bfce96a9ce7b50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllAccessType::const_self_iterator llvm::MemoryAccess::getIterator ()</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>.</p>

</div>
</div>

### getReverseDefsIterator() {#a6d56464060a479164dcac19b3a0fd7e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefsOnlyType::reverse_self_iterator llvm::MemoryAccess::getReverseDefsIterator ()</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#ad4bb544993573a6677d97cf5413110c7">llvm::ilist_node_impl&lt; OptionsT &gt;::getReverseIterator</a>.</p>

</div>
</div>

### getReverseDefsIterator() {#a707579b9929664f975f53cb858685397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefsOnlyType::const_reverse_self_iterator llvm::MemoryAccess::getReverseDefsIterator ()</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#ad4bb544993573a6677d97cf5413110c7">llvm::ilist_node_impl&lt; OptionsT &gt;::getReverseIterator</a>.</p>

</div>
</div>

### getReverseIterator() {#a0335bbe7f97148c901d8cd85ef2b7858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllAccessType::reverse_self_iterator llvm::MemoryAccess::getReverseIterator ()</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#ad4bb544993573a6677d97cf5413110c7">llvm::ilist_node_impl&lt; OptionsT &gt;::getReverseIterator</a>.</p>

</div>
</div>

### getReverseIterator() {#aa921b533f8d032b3db40d3ff42cf3767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllAccessType::const_reverse_self_iterator llvm::MemoryAccess::getReverseIterator ()</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#ad4bb544993573a6677d97cf5413110c7">llvm::ilist_node_impl&lt; OptionsT &gt;::getReverseIterator</a>.</p>

</div>
</div>

### print() {#aadff5eaae30623b4077b9dec90f29dcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemoryAccess::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>, definition at line 2211 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#a4a6ca5a5b87bd84231be9d8dbec46c1a">llvm::Value::getValueID</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a989b4c996f27373edde01fe749a72961">MemoryDef</a>, <a href="#a5cb5a37cd09a809853831406bd139a79">MemoryPhi</a>, <a href="#a348fb6ffcc26b7c17ceb5c6b76ec5f31">MemoryUse</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#afa9b4a650e1a6de2061538a19be3a234">llvm::MemorySSA::print</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af062c3c25f93ae994174b4d280843ae5">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getID() {#ab3a9d1e32d4473460c83d5db60bd0d8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MemoryAccess::getID ()</td>
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

<p>Used for debugging and tracking things about MemoryAccesses.</p>


<p>Guaranteed unique among MemoryAccesses, no guarantees otherwise.</p>


<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryuse/#a941afe9aa7511796d27d11486a70c6c5">llvm::MemoryUse::isOptimized</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#ad75b48c94bacfc6a1d166164bd51af8b">llvm::MemoryPhi::print</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuse/#a39bac19197190015e13adba7ddb9db2f">llvm::MemoryUse::print</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydef/#af8ce9c4c2a0f042aa8a7c365a293d642">llvm::MemoryDef::setOptimized</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryuse/#ad8b436737742919b2ba59790edaaf64a">llvm::MemoryUse::setOptimized</a>.</p>

</div>
</div>

### setBlock() {#adaa94f3c67c7301f0172b1aa9dad07fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MemoryAccess::setBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Used by <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> to change the block of a <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> when it is moved.</p>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Block {#a76be6234df997d597b3fcf26e1d54c71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* llvm::MemoryAccess::Block</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a20129d55ad455c11e932d68e4bd32581}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemoryAccess::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/deriveduser/#aeceedf6e1a7d48a588516ce2b1983d6f">llvm::DerivedUser::Value</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssa-h">MemorySSA.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
