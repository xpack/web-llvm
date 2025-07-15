---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-earlycse-cpp-/earlycse
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `EarlyCSE` Class Reference

<p>A simple and fast domtree-based CSE pass. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{EarlyCSE.cpp}::EarlyCSE { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5e44b61e0788a741722bdc909c40fe8">AllocatorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/recyclingallocator">RecyclingAllocator</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/scopedhashtableval">ScopedHashTableVal</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/simplevalue">SimpleValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba4b51f960b607643c1c0d4b3c103fd9">ScopedHTType</a> = <a href="/web-llvm/docs/api/classes/llvm/scopedhashtable">ScopedHashTable</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/simplevalue">SimpleValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/simplevalue">SimpleValue</a> &gt;, <a href="#ad5e44b61e0788a741722bdc909c40fe8">AllocatorTy</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4867a54fe734bdc2a70b41bea7b3e3eb">LoadMapAllocator</a> = <a href="/web-llvm/docs/api/classes/llvm/recyclingallocator">RecyclingAllocator</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/scopedhashtableval">ScopedHashTableVal</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/earlycse/loadvalue">LoadValue</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b6b2ea90186e58a7f6a79cd5f594577">LoadHTType</a> = <a href="/web-llvm/docs/api/classes/llvm/scopedhashtable">ScopedHashTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/earlycse/loadvalue">LoadValue</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;, <a href="#a4867a54fe734bdc2a70b41bea7b3e3eb">LoadMapAllocator</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad86b6be411685cb1dfe8c8bc2c66b56d">InvariantMapAllocator</a> = <a href="/web-llvm/docs/api/classes/llvm/recyclingallocator">RecyclingAllocator</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/scopedhashtableval">ScopedHashTableVal</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a>, unsigned &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad38dd288c7d4a603bc97133a417068ad">InvariantHTType</a> = <a href="/web-llvm/docs/api/classes/llvm/scopedhashtable">ScopedHashTable</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a>, unsigned, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &gt;, <a href="#ad86b6be411685cb1dfe8c8bc2c66b56d">InvariantMapAllocator</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a628ce8871e87b74dd853b39c782a9381">CallHTType</a> = <a href="/web-llvm/docs/api/classes/llvm/scopedhashtable">ScopedHashTable</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/callvalue">CallValue</a>, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, unsigned &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A scoped hash table of the current values of read-only call values. <a href="#a628ce8871e87b74dd853b39c782a9381">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ce0558a3ab8a0a9896aa27b021bdb25">GEPMapAllocatorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/recyclingallocator">RecyclingAllocator</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a>, <a href="/web-llvm/docs/api/classes/llvm/scopedhashtableval">ScopedHashTableVal</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/gepvalue">GEPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e8ddc4bd4b376bab8ec20e2fa50143f">GEPHTType</a> = <a href="/web-llvm/docs/api/classes/llvm/scopedhashtable">ScopedHashTable</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/gepvalue">GEPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/gepvalue">GEPValue</a> &gt;, <a href="#a9ce0558a3ab8a0a9896aa27b021bdb25">GEPMapAllocatorTy</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25a26ce8b3780d7bf77dbec85d7e3f30">EarlyCSE</a> (const DataLayout &amp;DL, const TargetLibraryInfo &amp;TLI, const TargetTransformInfo &amp;TTI, DominatorTree &amp;DT, AssumptionCache &amp;AC, MemorySSA *MSSA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set up the <a href="/web-llvm/docs/api/classes/anonymous-earlycse-cpp-/earlycse">EarlyCSE</a> runner for a particular function. <a href="#a25a26ce8b3780d7bf77dbec85d7e3f30">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72f98ddc07e318d4fac9e221534c4d73">run</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00020e003e86bd63726a5c6a0269ee7a">processNode</a> (DomTreeNode *Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a735d5fe5931189c691432682ec0adab0">handleBranchCondition</a> (Instruction *CondInst, const BranchInst *BI, const BasicBlock *BB, const BasicBlock *Pred)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a572b0421a1fde42e5d02fec0c828a08b">getMatchingValue</a> (LoadValue &amp;InVal, ParseMemoryInst &amp;MemInst, unsigned CurrentGeneration)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5b48f8089649f86f3cdc647e248799d">overridingStores</a> (const ParseMemoryInst &amp;Earlier, const ParseMemoryInst &amp;Later)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c148ab398f2ebe2ff5f5a7eedd5ae18">getOrCreateResult</a> (Instruction *Inst, Type *ExpectedType) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d7c968d6ff2cb78fe0914b0bd8dc095">isOperatingOnInvariantMemAt</a> (Instruction *I, unsigned GenAt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is known to only operate on memory provably invariant in the given "generation". <a href="#a1d7c968d6ff2cb78fe0914b0bd8dc095">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af225faa19e70288baea91dd678ad0fcd">isSameMemGeneration</a> (unsigned EarlierGeneration, unsigned LaterGeneration, Instruction *EarlierInst, Instruction *LaterInst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the memory referenced by LaterInst is from the same heap version as EarlierInst. <a href="#af225faa19e70288baea91dd678ad0fcd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4384e7b0ca9994f1aa6f46b117bde201">isNonTargetIntrinsicMatch</a> (const IntrinsicInst *Earlier, const IntrinsicInst *Later)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9afe5bb009aafce0dfd689499e3f769b">removeMSSA</a> (Instruction &amp;Inst)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bdb6addaf8968184f15251415fccf28">TLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa29b154aebb64d47175c1b82b04fd614">TTI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cbe256d9112bd806aacb7812242b948">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cf9869f638987e883726c5a9252bb89">AC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9689b67c6e4c612e53720cd9d336af4">SQ</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac9c28e19ee2e771bcbccbda746f76ec">MSSA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2db2f6e229351c765df701cb9de2d239">MSSAUpdater</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aba4b51f960b607643c1c0d4b3c103fd9">ScopedHTType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fdc6655978cda56c76b557d6d4d81e7">AvailableValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A scoped hash table of the current values of all of our simple scalar expressions. <a href="#a1fdc6655978cda56c76b557d6d4d81e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3b6b2ea90186e58a7f6a79cd5f594577">LoadHTType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a768219fcbf1df87b43489be86b71b183">AvailableLoads</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad38dd288c7d4a603bc97133a417068ad">InvariantHTType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1694b8d4b00fb8fccc3d4d074653c73c">AvailableInvariants</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a628ce8871e87b74dd853b39c782a9381">CallHTType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed16834803abfd7e250361e3d2e8be9f">AvailableCalls</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0e8ddc4bd4b376bab8ec20e2fa50143f">GEPHTType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d3d81d3228db9e73432f64b5cb7b6df">AvailableGEPs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f14e671f8f46a7afc8d6bc6e67bb802">CurrentGeneration</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the current generation of the memory value. <a href="#a6f14e671f8f46a7afc8d6bc6e67bb802">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9738f57bb5897ba10ced22f0ae0154b3">ClobberCounter</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d34be1d63a086a11fe19ffb2e1c431d">isHandledNonTargetIntrinsic</a> (Intrinsic::ID ID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f6856d2c6b6353fafea0fe27aaf845e">isHandledNonTargetIntrinsic</a> (const Value *V)</td>
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

<p>A simple and fast domtree-based CSE pass.</p>


<p>This pass does a simple depth-first walk over the dominator tree, eliminating trivially redundant instructions and using instsimplify to canonicalize things as it goes. It is intended to be fast and catch obvious cases so that instcombine and other passes are more effective. It is expected that a later pass of GVN will catch the interesting/hard cases.</p>


<p>Definition at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### AllocatorTy {#ad5e44b61e0788a741722bdc909c40fe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{EarlyCSE.cpp}::EarlyCSE::AllocatorTy = 
      RecyclingAllocator&lt;BumpPtrAllocator,
                         ScopedHashTableVal&lt;SimpleValue, Value *&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

### CallHTType {#a628ce8871e87b74dd853b39c782a9381}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{EarlyCSE.cpp}::EarlyCSE::CallHTType = 
      ScopedHashTable&lt;CallValue, std::pair&lt;Instruction *, unsigned&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A scoped hash table of the current values of read-only call values.</p>


<p>It uses the same generation count as loads.</p>


<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

### GEPHTType {#a0e8ddc4bd4b376bab8ec20e2fa50143f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{EarlyCSE.cpp}::EarlyCSE::GEPHTType =  ScopedHashTable&lt;GEPValue, Value *, DenseMapInfo&lt;GEPValue&gt;,
                                    GEPMapAllocatorTy&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

### GEPMapAllocatorTy {#a9ce0558a3ab8a0a9896aa27b021bdb25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{EarlyCSE.cpp}::EarlyCSE::GEPMapAllocatorTy = 
      RecyclingAllocator&lt;BumpPtrAllocator,
                         ScopedHashTableVal&lt;GEPValue, Value *&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 722 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

### InvariantHTType {#ad38dd288c7d4a603bc97133a417068ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{EarlyCSE.cpp}::EarlyCSE::InvariantHTType = 
      ScopedHashTable&lt;MemoryLocation, unsigned, DenseMapInfo&lt;MemoryLocation&gt;,
                      InvariantMapAllocator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 709 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

### InvariantMapAllocator {#ad86b6be411685cb1dfe8c8bc2c66b56d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{EarlyCSE.cpp}::EarlyCSE::InvariantMapAllocator = 
      RecyclingAllocator&lt;BumpPtrAllocator,
                         ScopedHashTableVal&lt;MemoryLocation, unsigned&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 706 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

### LoadHTType {#a3b6b2ea90186e58a7f6a79cd5f594577}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{EarlyCSE.cpp}::EarlyCSE::LoadHTType = 
      ScopedHashTable&lt;Value *, LoadValue, DenseMapInfo&lt;Value *&gt;,
                      LoadMapAllocator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

### LoadMapAllocator {#a4867a54fe734bdc2a70b41bea7b3e3eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{EarlyCSE.cpp}::EarlyCSE::LoadMapAllocator = 
      RecyclingAllocator&lt;BumpPtrAllocator,
                         ScopedHashTableVal&lt;Value *, LoadValue&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

### ScopedHTType {#aba4b51f960b607643c1c0d4b3c103fd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{EarlyCSE.cpp}::EarlyCSE::ScopedHTType = 
      ScopedHashTable&lt;SimpleValue, Value *, DenseMapInfo&lt;SimpleValue&gt;,
                      AllocatorTy&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 654 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### EarlyCSE() {#a25a26ce8b3780d7bf77dbec85d7e3f30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{EarlyCSE.cpp}::EarlyCSE::EarlyCSE (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> * MSSA)</td>
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

<p>Set up the <a href="/web-llvm/docs/api/classes/anonymous-earlycse-cpp-/earlycse">EarlyCSE</a> runner for a particular function.</p>

<p>Definition at line 733 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>References <a href="#a1cf9869f638987e883726c5a9252bb89">AC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a6cbe256d9112bd806aacb7812242b948">DT</a>, <a href="#aac9c28e19ee2e771bcbccbda746f76ec">MSSA</a>, <a href="#a2db2f6e229351c765df701cb9de2d239">MSSAUpdater</a>, <a href="#af9689b67c6e4c612e53720cd9d336af4">SQ</a>, <a href="#a1bdb6addaf8968184f15251415fccf28">TLI</a> and <a href="#aa29b154aebb64d47175c1b82b04fd614">TTI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a72f98ddc07e318d4fac9e221534c4d73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EarlyCSE::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 739 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aed16834803abfd7e250361e3d2e8be9f">AvailableCalls</a>, <a href="#a1d3d81d3228db9e73432f64b5cb7b6df">AvailableGEPs</a>, <a href="#a1694b8d4b00fb8fccc3d4d074653c73c">AvailableInvariants</a>, <a href="#a768219fcbf1df87b43489be86b71b183">AvailableLoads</a>, <a href="#a1fdc6655978cda56c76b557d6d4d81e7">AvailableValues</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a40b8345d54ada5dab71ae11d71e89d2f">llvm::DomTreeNodeBase&lt; NodeT &gt;::begin</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="#a6f14e671f8f46a7afc8d6bc6e67bb802">CurrentGeneration</a>, <a href="#a6cbe256d9112bd806aacb7812242b948">DT</a> and <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a74111c67a831eb30b020ecf063bce406">llvm::DomTreeNodeBase&lt; NodeT &gt;::end</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getMatchingValue() {#a572b0421a1fde42e5d02fec0c828a08b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * EarlyCSE::getMatchingValue (<a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/earlycse/loadvalue">LoadValue</a> &amp; InVal, ParseMemoryInst &amp; MemInst, unsigned CurrentGeneration)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 962 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

### getOrCreateResult() {#a4c148ab398f2ebe2ff5f5a7eedd5ae18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{EarlyCSE.cpp}::EarlyCSE::getOrCreateResult (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ExpectedType)</td>
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



<p>Definition at line 968 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

### handleBranchCondition() {#a735d5fe5931189c691432682ec0adab0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EarlyCSE::handleBranchCondition (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CondInst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> * BI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Pred)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 959 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

### isNonTargetIntrinsicMatch() {#a4384e7b0ca9994f1aa6f46b117bde201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{EarlyCSE.cpp}::EarlyCSE::isNonTargetIntrinsicMatch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * Earlier, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * Later)</td>
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



<p>Definition at line 997 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

### isOperatingOnInvariantMemAt() {#a1d7c968d6ff2cb78fe0914b0bd8dc095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EarlyCSE::isOperatingOnInvariantMemAt (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, unsigned GenAt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the instruction is known to only operate on memory provably invariant in the given "generation".</p>

<p>Definition at line 992 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

### isSameMemGeneration() {#af225faa19e70288baea91dd678ad0fcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EarlyCSE::isSameMemGeneration (unsigned EarlierGeneration, unsigned LaterGeneration, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * EarlierInst, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * LaterInst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the memory referenced by LaterInst is from the same heap version as EarlierInst.</p>


<p>This is currently called in two scenarios:</p>


<p>load p ... load p</p>


<p>and</p>


<p>x = load p ... store x, p</p>


<p>in both cases we want to verify that there are no possible writes to the memory referenced by p between the earlier and later instruction.</p>


<p>Definition at line 994 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

### overridingStores() {#ab5b48f8089649f86f3cdc647e248799d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EarlyCSE::overridingStores (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ParseMemoryInst &amp; Earlier, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ParseMemoryInst &amp; Later)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

### processNode() {#a00020e003e86bd63726a5c6a0269ee7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EarlyCSE::processNode (<a href="/web-llvm/docs/api/namespaces/llvm/#a58b9df85470fc4e2a8066ff6a62e5a34">DomTreeNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 957 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

### removeMSSA() {#a9afe5bb009aafce0dfd689499e3f769b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{EarlyCSE.cpp}::EarlyCSE::removeMSSA (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Inst)</td>
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



<p>Definition at line 1092 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AC {#a1cf9869f638987e883726c5a9252bb89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache&amp; anonymous{EarlyCSE.cpp}::EarlyCSE::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>Referenced by <a href="#a25a26ce8b3780d7bf77dbec85d7e3f30">EarlyCSE</a>.</p>

</div>
</div>

### AvailableCalls {#aed16834803abfd7e250361e3d2e8be9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallHTType anonymous{EarlyCSE.cpp}::EarlyCSE::AvailableCalls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>Referenced by <a href="#a72f98ddc07e318d4fac9e221534c4d73">run</a>.</p>

</div>
</div>

### AvailableGEPs {#a1d3d81d3228db9e73432f64b5cb7b6df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPHTType anonymous{EarlyCSE.cpp}::EarlyCSE::AvailableGEPs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 727 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>Referenced by <a href="#a72f98ddc07e318d4fac9e221534c4d73">run</a>.</p>

</div>
</div>

### AvailableInvariants {#a1694b8d4b00fb8fccc3d4d074653c73c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InvariantHTType anonymous{EarlyCSE.cpp}::EarlyCSE::AvailableInvariants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>Referenced by <a href="#a72f98ddc07e318d4fac9e221534c4d73">run</a>.</p>

</div>
</div>

### AvailableLoads {#a768219fcbf1df87b43489be86b71b183}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadHTType anonymous{EarlyCSE.cpp}::EarlyCSE::AvailableLoads</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 701 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>Referenced by <a href="#a72f98ddc07e318d4fac9e221534c4d73">run</a>.</p>

</div>
</div>

### AvailableValues {#a1fdc6655978cda56c76b557d6d4d81e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScopedHTType anonymous{EarlyCSE.cpp}::EarlyCSE::AvailableValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A scoped hash table of the current values of all of our simple scalar expressions.</p>


<p>As we walk down the domtree, we look to see if instructions are in this: if so, we replace them with what we find, otherwise we insert them so that dominated values can succeed in their lookup.</p>


<p>Definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>Referenced by <a href="#a72f98ddc07e318d4fac9e221534c4d73">run</a>.</p>

</div>
</div>

### CurrentGeneration {#a6f14e671f8f46a7afc8d6bc6e67bb802}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{EarlyCSE.cpp}::EarlyCSE::CurrentGeneration = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the current generation of the memory value.</p>

<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>Referenced by <a href="#a72f98ddc07e318d4fac9e221534c4d73">run</a>.</p>

</div>
</div>

### DT {#a6cbe256d9112bd806aacb7812242b948}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree&amp; anonymous{EarlyCSE.cpp}::EarlyCSE::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>Referenced by <a href="#a25a26ce8b3780d7bf77dbec85d7e3f30">EarlyCSE</a> and <a href="#a72f98ddc07e318d4fac9e221534c4d73">run</a>.</p>

</div>
</div>

### MSSA {#aac9c28e19ee2e771bcbccbda746f76ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSA* anonymous{EarlyCSE.cpp}::EarlyCSE::MSSA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>Referenced by <a href="#a25a26ce8b3780d7bf77dbec85d7e3f30">EarlyCSE</a>.</p>

</div>
</div>

### MSSAUpdater {#a2db2f6e229351c765df701cb9de2d239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemorySSAUpdater&gt; anonymous{EarlyCSE.cpp}::EarlyCSE::MSSAUpdater</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>Referenced by <a href="#a25a26ce8b3780d7bf77dbec85d7e3f30">EarlyCSE</a>.</p>

</div>
</div>

### SQ {#af9689b67c6e4c612e53720cd9d336af4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SimplifyQuery anonymous{EarlyCSE.cpp}::EarlyCSE::SQ</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 647 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>Referenced by <a href="#a25a26ce8b3780d7bf77dbec85d7e3f30">EarlyCSE</a>.</p>

</div>
</div>

### TLI {#a1bdb6addaf8968184f15251415fccf28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo&amp; anonymous{EarlyCSE.cpp}::EarlyCSE::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>Referenced by <a href="#a25a26ce8b3780d7bf77dbec85d7e3f30">EarlyCSE</a>.</p>

</div>
</div>

### TTI {#aa29b154aebb64d47175c1b82b04fd614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetTransformInfo&amp; anonymous{EarlyCSE.cpp}::EarlyCSE::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 644 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>


<p>Referenced by <a href="#a25a26ce8b3780d7bf77dbec85d7e3f30">EarlyCSE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ClobberCounter {#a9738f57bb5897ba10ced22f0ae0154b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{EarlyCSE.cpp}::EarlyCSE::ClobberCounter = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 742 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### isHandledNonTargetIntrinsic() {#a9d34be1d63a086a11fe19ffb2e1c431d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{EarlyCSE.cpp}::EarlyCSE::isHandledNonTargetIntrinsic (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> ID)</td>
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



<p>Definition at line 943 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

### isHandledNonTargetIntrinsic() {#a1f6856d2c6b6353fafea0fe27aaf845e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{EarlyCSE.cpp}::EarlyCSE::isHandledNonTargetIntrinsic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 951 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp">EarlyCSE.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
