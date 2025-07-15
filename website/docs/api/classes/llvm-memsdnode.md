---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memsdnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MemSDNode` Class Reference

<p>This is an abstract virtual class for memory operations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MemSDNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">llvm/CodeGen/SelectionDAGNodes.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents one node in the <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a>. <a href="/web-llvm/docs/api/classes/llvm/sdnode/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/atomicsdnode">AtomicSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> representing atomic operations. <a href="/web-llvm/docs/api/classes/llvm/atomicsdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fpstateaccesssdnode">FPStateAccessSDNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lsbasesdnode">LSBaseSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for <a href="/web-llvm/docs/api/classes/llvm/loadsdnode">LoadSDNode</a> and <a href="/web-llvm/docs/api/classes/llvm/storesdnode">StoreSDNode</a>. <a href="/web-llvm/docs/api/classes/llvm/lsbasesdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/maskedgatherscattersdnode">MaskedGatherScatterSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a base class used to represent MGATHER and MSCATTER nodes. <a href="/web-llvm/docs/api/classes/llvm/maskedgatherscattersdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/maskedloadstoresdnode">MaskedLoadStoreSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This base class is used to represent MLOAD and MSTORE nodes. <a href="/web-llvm/docs/api/classes/llvm/maskedloadstoresdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memintrinsicsdnode">MemIntrinsicSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> is used for target intrinsics that touch memory and need an associated <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a>. <a href="/web-llvm/docs/api/classes/llvm/memintrinsicsdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbaseloadstoresdnode">VPBaseLoadStoreSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This base class is used to represent VP_LOAD, VP_STORE, EXPERIMENTAL_VP_STRIDED_LOAD and EXPERIMENTAL_VP_STRIDED_STORE nodes. <a href="/web-llvm/docs/api/classes/llvm/vpbaseloadstoresdnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpgatherscattersdnode">VPGatherScatterSDNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a base class used to represent VP_GATHER and VP_SCATTER nodes. <a href="/web-llvm/docs/api/classes/llvm/vpgatherscattersdnode/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00a2cd9501aed5f7e8746c0458990503">MemSDNode</a> (unsigned Opc, unsigned Order, const DebugLoc &amp;dl, SDVTList VTs, EVT memvt, MachineMemOperand *MMO)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c6f1b67f6d43d4ebaec3e0deb3d9bff">readMem</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2952508de5f419e99507aec16b63a6b">writeMem</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85cc92919f7704331920d260e71a7439">getOriginalAlign</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns alignment and volatility of the memory access. <a href="#a85cc92919f7704331920d260e71a7439">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ba669acfce53f64119001f5d46e162f">getAlign</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae80c6b39fd20683261c5f48f849693c7">getRawSubclassData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the SubclassData value, without HasDebugValue. <a href="#ae80c6b39fd20683261c5f48f849693c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64cdf55a9cfb33bd17e61beae253e3aa">isVolatile</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba37cfe8576deaf53760781cffe425fe">isNonTemporal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac689f393979f367a01d766c2d0db529b">isDereferenceable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfc21c6926e533d26ad132d76eb1b0e7">isInvariant</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a869f89c8fec7959857a0de4d7bbf5a93">getSrcValueOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80f0411207d75b649465f8505a2609f6">getAAInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> info that describes the dereference. <a href="#a80f0411207d75b649465f8505a2609f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4913f6364d5b8207efbd4ba07648749b">getRanges</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the Ranges that describes the dereference. <a href="#a4913f6364d5b8207efbd4ba07648749b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81edbfd4f3e9eefe0e4f53822ac11da1">getSyncScopeID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for this memory operation. <a href="#a81edbfd4f3e9eefe0e4f53822ac11da1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e13c962466d74908fd163cf3fde05ee">getSuccessOrdering</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the atomic ordering requirements for this memory operation. <a href="#a9e13c962466d74908fd163cf3fde05ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab82eed0d6910bbb28ef05c224d541e88">getMergedOrdering</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a single atomic ordering that is at least as strong as both the success and failure orderings for an atomic operation. <a href="#ab82eed0d6910bbb28ef05c224d541e88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad18cdcd86c9bf6d833b6763519b84e8a">isAtomic</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the memory operation ordering is Unordered or higher. <a href="#ad18cdcd86c9bf6d833b6763519b84e8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc4a3e33f4bae266e177eb7749e52281">isUnordered</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the memory operation doesn't imply any ordering constraints on surrounding memory operations beyond the normal memory aliasing rules. <a href="#acc4a3e33f4bae266e177eb7749e52281">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f317cf85de4c00ba81d5b5309afd4db">isSimple</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the memory operation is neither atomic or volatile. <a href="#a8f317cf85de4c00ba81d5b5309afd4db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee0e58997cd08983518f051e79b855d9">getMemoryVT</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type of the in-memory value. <a href="#aee0e58997cd08983518f051e79b855d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa078a60d1127b9daad580b6d2ba7ef91">getMemOperand</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> object describing the memory reference performed by operation. <a href="#aa078a60d1127b9daad580b6d2ba7ef91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab58a98ad2eb07046ef0584d2bc8f1d2d">getPointerInfo</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e10f29264df67a4564d4230bf8e98c7">getAddressSpace</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the address space for the associated pointer. <a href="#a2e10f29264df67a4564d4230bf8e98c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf86ebe900295d7c59ea024fc19d0154">refineAlignment</a> (const MachineMemOperand *NewMMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update this <a href="/web-llvm/docs/api/classes/llvm/memsdnode">MemSDNode</a>'s <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> information to reflect the alignment of NewMMO, if it has a greater alignment. <a href="#aaf86ebe900295d7c59ea024fc19d0154">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab858661e16a61c4fc6b27b6b26aac17b">getChain</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa97617ded03926053f78ec06608f32bb">getBasePtr</a> () const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22cf4b7941bcfec9f5f5fe04d55627df">MMO</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> reference information. <a href="#a22cf4b7941bcfec9f5f5fe04d55627df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcf740b486e77f73aa73565014bbab44">MemoryVT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad55691554da9be384e9393e8b42a431a">classof</a> (const SDNode *N)</td>
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

<p>This is an abstract virtual class for memory operations.</p>

<p>Definition at line 1352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MemSDNode() {#a00a2cd9501aed5f7e8746c0458990503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemSDNode::MemSDNode (unsigned Opc, unsigned Order, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; dl, <a href="/web-llvm/docs/api/structs/llvm/sdvtlist">SDVTList</a> VTs, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> memvt, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>, definition at line 12434 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a1572b31fadbd0d758314b8d35a050410">llvm::EVT::getStoreSize</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a338ba7ca7a526243ab1853d07d90fe38">llvm::details::FixedOrScalableQuantity&lt; TypeSize, uint64_t &gt;::isKnownLE</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a434bf5710046ffbca878d6379c5a6be5">llvm::SDNode::MemSDNodeBits</a>, <a href="#a22cf4b7941bcfec9f5f5fe04d55627df">MMO</a> and <a href="/web-llvm/docs/api/classes/llvm/sdnode/#af64f53af99d4ee7bbf57ea0aab719254">llvm::SDNode::SDNode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/atomicsdnode/#a9b8856c7736a3d284467229f318150cb">llvm::AtomicSDNode::AtomicSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/fpstateaccesssdnode/#ab9a711997f966eccb20fa70656b6c4bf">llvm::FPStateAccessSDNode::FPStateAccessSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/lsbasesdnode/#a083785be56ad0ab8dbf81e50a6a761ac">llvm::LSBaseSDNode::LSBaseSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedgatherscattersdnode/#a70ef3f18e52d25106579f0673aaa6b1c">llvm::MaskedGatherScatterSDNode::MaskedGatherScatterSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedloadstoresdnode/#a2e7048e7f25ba106f889cbb5c8ab3d09">llvm::MaskedLoadStoreSDNode::MaskedLoadStoreSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicsdnode/#a7840ddfe91a4ac8a274c60ed76f496cb">llvm::MemIntrinsicSDNode::MemIntrinsicSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbaseloadstoresdnode/#a7cdac375772f7b4e63f30cb6fd02a4c6">llvm::VPBaseLoadStoreSDNode::VPBaseLoadStoreSDNode</a> and <a href="/web-llvm/docs/api/classes/llvm/vpgatherscattersdnode/#a98f56e585d111952edfdc53e8d30e7a5">llvm::VPGatherScatterSDNode::VPGatherScatterSDNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAAInfo() {#a80f0411207d75b649465f8505a2609f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAMDNodes llvm::MemSDNode::getAAInfo ()</td>
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

<p>Returns the <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> info that describes the dereference.</p>

<p>Definition at line 1400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#a22cf4b7941bcfec9f5f5fe04d55627df">MMO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a665ef5a5179d9d6112b5215fe27caa83">llvm::HexagonTargetLowering::LowerLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#afba0648a688bd0202b03710302c89a2f">LowerSTORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a13d359868f5ac633615beeedb6b18b6e">PerformExtractFpToIntStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae17716da714991550ba9ea6f4747831a">PerformSplittingMVETruncToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a91f43e00f77d44c412e9b3675ce35253">PerformSplittingToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a> and <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a16e6c862a36871c4f388c826ad65b07c">llvm::SparcTargetLowering::ReplaceNodeResults</a>.</p>

</div>
</div>

### getAddressSpace() {#a2e10f29264df67a4564d4230bf8e98c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MemSDNode::getAddressSpace ()</td>
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

<p>Return the address space for the associated pointer.</p>

<p>Definition at line 1443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#a2788ec4ff3130471e24ab77dc08f7c50">llvm::MachinePointerInfo::getAddrSpace</a> and <a href="#ab58a98ad2eb07046ef0584d2bc8f1d2d">getPointerInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a0101ddec6987012c164530ddbdcc307c">llvm::R600TargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13463f9ee8babeef33857cbbc8ea4af1">llvm::AMDGPUTargetLowering::performLoadCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad85146c9cfc75b8fe84203e7b920b9e2">llvm::AMDGPUTargetLowering::performStoreCombine</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a9131ae18383241b54e466cf623a7312b">llvm::AMDGPUTargetLowering::shouldReduceLoadWidth</a>.</p>

</div>
</div>

### getAlign() {#a5ba669acfce53f64119001f5d46e162f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MemSDNode::getAlign ()</td>
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



<p>Definition at line 1370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#a22cf4b7941bcfec9f5f5fe04d55627df">MMO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af8092b588e16c93a54d21da99af4814c">combineBVOfConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a4394bc2d4e4e90b47c9876e546e1429d">lowerFP_TO_SINT_STORE</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a665ef5a5179d9d6112b5215fe27caa83">llvm::HexagonTargetLowering::LowerLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a225dca8b49ddf9ae69266aa8448208d0">lowerLoadF128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a5a96f3df430878c8511972852cb08499">lowerLoadI1</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a946850e76d96e9deaab8c5053a86f02b">llvm::HexagonTargetLowering::LowerStore</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a8308bacd5a1d10fdc7ac14c784f6ce0d">llvm::MipsTargetLowering::lowerSTORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#af03b2efb74091548a48b0aebf40349de">lowerStoreF128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#af1126eb4c6731ec07f82bc63d84313fc">lowerStoreI1</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a39595844bf818c3700df1bd898912dcb">llvm::HexagonTargetLowering::LowerUnalignedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a03b14e6aca1277bdee37639aec700ba7">performIntToFpCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13463f9ee8babeef33857cbbc8ea4af1">llvm::AMDGPUTargetLowering::performLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad85146c9cfc75b8fe84203e7b920b9e2">llvm::AMDGPUTargetLowering::performStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aba237afe216b870806584d3e96e575b4">PerformTruncatingStoreCombine</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ae29a60720e41fdf677935d16ad9d3b5b">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode6</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bbdb7f279f14b5f7ff6d7d9a2a97765">splitStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6a7f067c980840336e15888700870c6a">splitStoreSplat</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#acbb9ce3311488486de6d14930b30c5ed">TryCombineBaseUpdate</a>.</p>

</div>
</div>

### getBasePtr() {#aa97617ded03926053f78ec06608f32bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SDValue &amp; llvm::MemSDNode::getBasePtr ()</td>
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



<p>Definition at line 1457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae243ce466d350b1aca774a6ae9aea81c">llvm::ISD::EXPERIMENTAL_VECTOR_HISTOGRAM</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a23f2f5947fc429aff1270651c6d019ea">llvm::SDNode::getOpcode</a> and <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61f23ea50bb7d5e61ca17b8d73bc7f7e">getBROADCAST_LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab7458c4c1d0b716494b03ba16ee86ad2">getParamsForOneTrueMaskedElt</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa03cec0d3e2e816167f41ac37995f274">llvm::AArch64TargetLowering::shouldReduceLoadWidth</a>.</p>

</div>
</div>

### getChain() {#ab858661e16a61c4fc6b27b6b26aac17b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SDValue &amp; llvm::MemSDNode::getChain ()</td>
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



<p>Definition at line 1455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af8092b588e16c93a54d21da99af4814c">combineBVOfConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a44f727169247a0359f485216a83265ac">combineMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4d6ae8095a6353874359d5f5e886410c">combineMOVDQ2Q</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2022f78361af7995aebd0a398e0a67e">combineSIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a414d9dfa6f85f8ad371a510821713e61">llvm::PPCTargetLowering::expandVSXLoadForLE</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#abf2cd323dcdc4b2b0a4741c62b30d0ba">llvm::PPCTargetLowering::expandVSXStoreForLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61f23ea50bb7d5e61ca17b8d73bc7f7e">getBROADCAST_LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a61fb4a306390ea68d7d7252a081464fb">if</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp/#a50de01231a46d2b82c41aebd0c413690">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a1c9b0061be648da87d7a9102c0179018">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#af5649d870c8560e39b54f41b8f5997fd">LowerF128Load</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a30ec39aa33314bba87f6f8d0eded2df8">LowerF128Store</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a4394bc2d4e4e90b47c9876e546e1429d">lowerFP_TO_SINT_STORE</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a665ef5a5179d9d6112b5215fe27caa83">llvm::HexagonTargetLowering::LowerLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a47413709ef916baf36607da462d93ccc">LowerLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a225dca8b49ddf9ae69266aa8448208d0">lowerLoadF128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a5a96f3df430878c8511972852cb08499">lowerLoadI1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a699145421612880595f18dd1b31bf7cb">lowerShuffleAsBroadcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#afba0648a688bd0202b03710302c89a2f">LowerSTORE</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a946850e76d96e9deaab8c5053a86f02b">llvm::HexagonTargetLowering::LowerStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a05914158f39e230548b1b743eee2e5f6">LowerStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#af03b2efb74091548a48b0aebf40349de">lowerStoreF128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#af1126eb4c6731ec07f82bc63d84313fc">lowerStoreI1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a6d57cc28d7c1b1806029db8e12c6a926">lowerUnalignedIntStore</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a39595844bf818c3700df1bd898912dcb">llvm::HexagonTargetLowering::LowerUnalignedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#afdcf01d7d3527e56cd6cc217975aac68">llvm::AMDGPUDAGToDAGISel::matchLoadD16FromBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a528e38dffd58ba9e81a7a05fb7d44c11">narrowExtractedVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#addb3e984dfd51a52d5ab5050a30cd4d4">narrowLoadToVZLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a13d359868f5ac633615beeedb6b18b6e">PerformExtractFpToIntStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8b803a5cecda412b4f4984ad8db7201e">performFPExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a03b14e6aca1277bdee37639aec700ba7">performIntToFpCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13463f9ee8babeef33857cbbc8ea4af1">llvm::AMDGPUTargetLowering::performLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad50cb0376d697cd4ca4f6469bd6bd25c">performMaskedGatherScatterCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae17716da714991550ba9ea6f4747831a">PerformSplittingMVETruncToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a91f43e00f77d44c412e9b3675ce35253">PerformSplittingToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad85146c9cfc75b8fe84203e7b920b9e2">llvm::AMDGPUTargetLowering::performStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aba237afe216b870806584d3e96e575b4">PerformTruncatingStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a47e64a2f9eb3ade81edd0d1e20034ec1">performUnpackCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a40eb7d32bd58dfbdde6c632446a56828">PerformVMOVrhCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa649493d03967e1898ad4354759d89f7">reduceMaskedStoreToScalarStore</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abb4ac2d585a18a9b8db4ac7ffa41fc06">llvm::RISCVTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a16e6c862a36871c4f388c826ad65b07c">llvm::SparcTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a347a0b15c11be2a5567e53730e0fb1b2">ShrinkLoadReplaceStoreWithStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bbdb7f279f14b5f7ff6d7d9a2a97765">splitStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6a7f067c980840336e15888700870c6a">splitStoreSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#abe50b03585622dd5b4b3c76d44ea7a8e">TryDistrubutionADDVecReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#afa371a03066103bb85f89636e86686d7">llvm::RISCVDAGToDAGISel::tryIndexedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a5d176b4adbcf9fd77cae6c4d43f13fb2">tryToFoldExtOfExtload</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a07529501831cc322901e5a24586b7720">tryToFoldExtOfLoad</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa267be29b6ab02eda3ff34dd9c608b0c">tryToFoldExtOfMaskedLoad</a>.</p>

</div>
</div>

### getMemOperand() {#aa078a60d1127b9daad580b6d2ba7ef91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineMemOperand * llvm::MemSDNode::getMemOperand ()</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> object describing the memory reference performed by operation.</p>

<p>Definition at line 1436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#a22cf4b7941bcfec9f5f5fe04d55627df">MMO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#abd574741643b21b2db236255e18656db">AddNodeIDCustom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a44f727169247a0359f485216a83265ac">combineMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4d6ae8095a6353874359d5f5e886410c">combineMOVDQ2Q</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2a80150263a981dc99c6b12775ee495f">CombineVLDDUP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a707c0b0d0b6b4f68d014516e8a8da025">createStoreLR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a414d9dfa6f85f8ad371a510821713e61">llvm::PPCTargetLowering::expandVSXLoadForLE</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#abf2cd323dcdc4b2b0a4741c62b30d0ba">llvm::PPCTargetLowering::expandVSXStoreForLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aee0563473c2eed4e233b639b9ae36911">getAVX2GatherNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61f23ea50bb7d5e61ca17b8d73bc7f7e">getBROADCAST_LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a75c0a729d679d7c1b8504537fbec5840">getGatherNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a58f02653f9d350105b1ffc704762f90a">getScatterNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a61fb4a306390ea68d7d7252a081464fb">if</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a934e0e0b94737441bea75fc4babf0021">llvm::SITargetLowering::isMemOpHasNoClobberedMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3b7d14ce641064b70c1b921dd97afd3e">lowerAtomicArith</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a4394bc2d4e4e90b47c9876e546e1429d">lowerFP_TO_SINT_STORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25a5e94166cf78354826b46e402ebcd9">LowerINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a665ef5a5179d9d6112b5215fe27caa83">llvm::HexagonTargetLowering::LowerLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a47413709ef916baf36607da462d93ccc">LowerLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a699145421612880595f18dd1b31bf7cb">lowerShuffleAsBroadcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#afba0648a688bd0202b03710302c89a2f">LowerSTORE</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a946850e76d96e9deaab8c5053a86f02b">llvm::HexagonTargetLowering::LowerStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a05914158f39e230548b1b743eee2e5f6">LowerStore</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a39595844bf818c3700df1bd898912dcb">llvm::HexagonTargetLowering::LowerUnalignedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#afdcf01d7d3527e56cd6cc217975aac68">llvm::AMDGPUDAGToDAGISel::matchLoadD16FromBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a528e38dffd58ba9e81a7a05fb7d44c11">narrowExtractedVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#addb3e984dfd51a52d5ab5050a30cd4d4">narrowLoadToVZLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a13d359868f5ac633615beeedb6b18b6e">PerformExtractFpToIntStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8b803a5cecda412b4f4984ad8db7201e">performFPExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a03b14e6aca1277bdee37639aec700ba7">performIntToFpCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13463f9ee8babeef33857cbbc8ea4af1">llvm::AMDGPUTargetLowering::performLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad50cb0376d697cd4ca4f6469bd6bd25c">performMaskedGatherScatterCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a77f2232fb1d07b3f88edaef89e94e673">PerformMVEVLDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2fbb20906245b5a07551c13da1409712">performNEONPostLDSTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abdbf7e16d7027d0bbbc9d4e8bf100840">performPostLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae17716da714991550ba9ea6f4747831a">PerformSplittingMVETruncToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a91f43e00f77d44c412e9b3675ce35253">PerformSplittingToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad85146c9cfc75b8fe84203e7b920b9e2">llvm::AMDGPUTargetLowering::performStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aba237afe216b870806584d3e96e575b4">PerformTruncatingStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a47e64a2f9eb3ade81edd0d1e20034ec1">performUnpackCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a40eb7d32bd58dfbdde6c632446a56828">PerformVMOVrhCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa649493d03967e1898ad4354759d89f7">reduceMaskedStoreToScalarStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a43333bc4548cbb52de14105bc979c0e0">ReplaceINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abb4ac2d585a18a9b8db4ac7ffa41fc06">llvm::RISCVTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a16e6c862a36871c4f388c826ad65b07c">llvm::SparcTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisel/#a977ad76f842f5addf1b023121d96465e">anonymous{SystemZISelDAGToDAG.cpp}::SystemZDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a9131ae18383241b54e466cf623a7312b">llvm::AMDGPUTargetLowering::shouldReduceLoadWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a347a0b15c11be2a5567e53730e0fb1b2">ShrinkLoadReplaceStoreWithStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bbdb7f279f14b5f7ff6d7d9a2a97765">splitStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6a7f067c980840336e15888700870c6a">splitStoreSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#acbb9ce3311488486de6d14930b30c5ed">TryCombineBaseUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae7edfd8337d702eebfdbf7010c3b2c74">tryMemPairCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a5d176b4adbcf9fd77cae6c4d43f13fb2">tryToFoldExtOfExtload</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a07529501831cc322901e5a24586b7720">tryToFoldExtOfLoad</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa267be29b6ab02eda3ff34dd9c608b0c">tryToFoldExtOfMaskedLoad</a>.</p>

</div>
</div>

### getMemoryVT() {#aee0e58997cd08983518f051e79b855d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::MemSDNode::getMemoryVT ()</td>
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

<p>Return the type of the in-memory value.</p>

<p>Definition at line 1432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#abd574741643b21b2db236255e18656db">AddNodeIDCustom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a5843fbc0765c997fa4bf9b6d876891b6">allUsesTruncate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a8101c1f13bd0c6b60080e985987c9b92">checkValueWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a257c422be962af393f15b15dbc07b962">checkValueWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a44f727169247a0359f485216a83265ac">combineMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2a80150263a981dc99c6b12775ee495f">CombineVLDDUP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a707c0b0d0b6b4f68d014516e8a8da025">createStoreLR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aee0563473c2eed4e233b639b9ae36911">getAVX2GatherNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a75c0a729d679d7c1b8504537fbec5840">getGatherNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab7458c4c1d0b716494b03ba16ee86ad2">getParamsForOneTrueMaskedElt</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a391ef092ff421faccdfef4cb88424742">llvm::HexagonTargetLowering::getPostIndexedAddressParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a58f02653f9d350105b1ffc704762f90a">getScatterNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a61fb4a306390ea68d7d7252a081464fb">if</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aca34d64e6bca0d10314f1308d636ecf8">isValidSplatLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25a5e94166cf78354826b46e402ebcd9">LowerINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a3fedecc58b422c10a3527f8f5db694bf">LowerLOAD</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a665ef5a5179d9d6112b5215fe27caa83">llvm::HexagonTargetLowering::LowerLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a47413709ef916baf36607da462d93ccc">LowerLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a57a0d1b6cabb33defc1c9f2d2d82a7f8">llvm::VETargetLowering::lowerLOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a5a96f3df430878c8511972852cb08499">lowerLoadI1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#afba0648a688bd0202b03710302c89a2f">LowerSTORE</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a946850e76d96e9deaab8c5053a86f02b">llvm::HexagonTargetLowering::LowerStore</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a8308bacd5a1d10fdc7ac14c784f6ce0d">llvm::MipsTargetLowering::lowerSTORE</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a9f5002398f225b7a1c111cb707669258">llvm::VETargetLowering::lowerSTORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#af1126eb4c6731ec07f82bc63d84313fc">lowerStoreI1</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a39595844bf818c3700df1bd898912dcb">llvm::HexagonTargetLowering::LowerUnalignedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#afdcf01d7d3527e56cd6cc217975aac68">llvm::AMDGPUDAGToDAGISel::matchLoadD16FromBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a6c02410f9bb19b5b6eb61c9711ae4156">PerformANDCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13463f9ee8babeef33857cbbc8ea4af1">llvm::AMDGPUTargetLowering::performLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad50cb0376d697cd4ca4f6469bd6bd25c">performMaskedGatherScatterCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5991e29bae68e989e978dc600f93b48e">performMemPairCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2fbb20906245b5a07551c13da1409712">performNEONPostLDSTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abdbf7e16d7027d0bbbc9d4e8bf100840">performPostLD1Combine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad85146c9cfc75b8fe84203e7b920b9e2">llvm::AMDGPUTargetLowering::performStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aba237afe216b870806584d3e96e575b4">PerformTruncatingStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a47e64a2f9eb3ade81edd0d1e20034ec1">performUnpackCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a43333bc4548cbb52de14105bc979c0e0">ReplaceINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abb4ac2d585a18a9b8db4ac7ffa41fc06">llvm::RISCVTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a16e6c862a36871c4f388c826ad65b07c">llvm::SparcTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ae29a60720e41fdf677935d16ad9d3b5b">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode6</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#abe588c29e26c909dcffe4c763aacaffe">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode6Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa03cec0d3e2e816167f41ac37995f274">llvm::AArch64TargetLowering::shouldReduceLoadWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#afa371a03066103bb85f89636e86686d7">llvm::RISCVDAGToDAGISel::tryIndexedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae7edfd8337d702eebfdbf7010c3b2c74">tryMemPairCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ae362c61a21181f35e570b2d94cdd2056">tryToFoldExtendSelectLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a5d176b4adbcf9fd77cae6c4d43f13fb2">tryToFoldExtOfExtload</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa267be29b6ab02eda3ff34dd9c608b0c">tryToFoldExtOfMaskedLoad</a>.</p>

</div>
</div>

### getMergedOrdering() {#ab82eed0d6910bbb28ef05c224d541e88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AtomicOrdering llvm::MemSDNode::getMergedOrdering ()</td>
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

<p>Return a single atomic ordering that is at least as strong as both the success and failure orderings for an atomic operation.</p>


<p>(For operations other than cmpxchg, this is equivalent to <a href="#a9e13c962466d74908fd163cf3fde05ee">getSuccessOrdering()</a>.)</p>


<p>Definition at line 1418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#a22cf4b7941bcfec9f5f5fe04d55627df">MMO</a>.</p>

</div>
</div>

### getOriginalAlign() {#a85cc92919f7704331920d260e71a7439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MemSDNode::getOriginalAlign ()</td>
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

<p>Returns alignment and volatility of the memory access.</p>

<p>Definition at line 1369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#a22cf4b7941bcfec9f5f5fe04d55627df">MMO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4d6ae8095a6353874359d5f5e886410c">combineMOVDQ2Q</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2022f78361af7995aebd0a398e0a67e">combineSIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab7458c4c1d0b716494b03ba16ee86ad2">getParamsForOneTrueMaskedElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#af5649d870c8560e39b54f41b8f5997fd">LowerF128Load</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a30ec39aa33314bba87f6f8d0eded2df8">LowerF128Store</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a47413709ef916baf36607da462d93ccc">LowerLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#afba0648a688bd0202b03710302c89a2f">LowerSTORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a05914158f39e230548b1b743eee2e5f6">LowerStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#addb3e984dfd51a52d5ab5050a30cd4d4">narrowLoadToVZLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a13d359868f5ac633615beeedb6b18b6e">PerformExtractFpToIntStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae17716da714991550ba9ea6f4747831a">PerformSplittingMVETruncToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a91f43e00f77d44c412e9b3675ce35253">PerformSplittingToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a16e6c862a36871c4f388c826ad65b07c">llvm::SparcTargetLowering::ReplaceNodeResults</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a347a0b15c11be2a5567e53730e0fb1b2">ShrinkLoadReplaceStoreWithStore</a>.</p>

</div>
</div>

### getPointerInfo() {#ab58a98ad2eb07046ef0584d2bc8f1d2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachinePointerInfo &amp; llvm::MemSDNode::getPointerInfo ()</td>
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



<p>Definition at line 1438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#a22cf4b7941bcfec9f5f5fe04d55627df">MMO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#abd574741643b21b2db236255e18656db">AddNodeIDCustom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af8092b588e16c93a54d21da99af4814c">combineBVOfConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4d6ae8095a6353874359d5f5e886410c">combineMOVDQ2Q</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2022f78361af7995aebd0a398e0a67e">combineSIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="#a2e10f29264df67a4564d4230bf8e98c7">getAddressSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#af5649d870c8560e39b54f41b8f5997fd">LowerF128Load</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a30ec39aa33314bba87f6f8d0eded2df8">LowerF128Store</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a4394bc2d4e4e90b47c9876e546e1429d">lowerFP_TO_SINT_STORE</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a665ef5a5179d9d6112b5215fe27caa83">llvm::HexagonTargetLowering::LowerLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a47413709ef916baf36607da462d93ccc">LowerLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a225dca8b49ddf9ae69266aa8448208d0">lowerLoadF128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a5a96f3df430878c8511972852cb08499">lowerLoadI1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#afba0648a688bd0202b03710302c89a2f">LowerSTORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a05914158f39e230548b1b743eee2e5f6">LowerStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a528e38dffd58ba9e81a7a05fb7d44c11">narrowExtractedVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#addb3e984dfd51a52d5ab5050a30cd4d4">narrowLoadToVZLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a13d359868f5ac633615beeedb6b18b6e">PerformExtractFpToIntStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a03b14e6aca1277bdee37639aec700ba7">performIntToFpCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae17716da714991550ba9ea6f4747831a">PerformSplittingMVETruncToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a91f43e00f77d44c412e9b3675ce35253">PerformSplittingToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aba237afe216b870806584d3e96e575b4">PerformTruncatingStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa649493d03967e1898ad4354759d89f7">reduceMaskedStoreToScalarStore</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a16e6c862a36871c4f388c826ad65b07c">llvm::SparcTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a347a0b15c11be2a5567e53730e0fb1b2">ShrinkLoadReplaceStoreWithStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bbdb7f279f14b5f7ff6d7d9a2a97765">splitStores</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6a7f067c980840336e15888700870c6a">splitStoreSplat</a>.</p>

</div>
</div>

### getRanges() {#a4913f6364d5b8207efbd4ba07648749b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MDNode * llvm::MemSDNode::getRanges ()</td>
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

<p>Returns the Ranges that describes the dereference.</p>

<p>Definition at line 1403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#a22cf4b7941bcfec9f5f5fe04d55627df">MMO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a665ef5a5179d9d6112b5215fe27caa83">llvm::HexagonTargetLowering::LowerLoad</a>.</p>

</div>
</div>

### getRawSubclassData() {#ae80c6b39fd20683261c5f48f849693c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MemSDNode::getRawSubclassData ()</td>
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

<p>Return the SubclassData value, without HasDebugValue.</p>


<p>This contains an encoding of the volatile flag, as well as bits used by subclasses. This function should only be used to compute a <a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> value. The HasDebugValue bit is masked out because CSE map needs to match nodes with debug info with nodes without debug info. Same is about isDivergent bit.</p>


<p>Definition at line 1378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a0e80b38dfd0d7e5a37e81b971d633a0f">llvm::SDNode::RawSDNodeBits</a> and <a href="/web-llvm/docs/api/classes/llvm/sdnode/#afb910e6a374ba558af8571d2a0a095ed">llvm::SDNode::SDNodeBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#abd574741643b21b2db236255e18656db">AddNodeIDCustom</a>.</p>

</div>
</div>

### getSrcValueOffset() {#a869f89c8fec7959857a0de4d7bbf5a93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MemSDNode::getSrcValueOffset ()</td>
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



<p>Definition at line 1397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#a22cf4b7941bcfec9f5f5fe04d55627df">MMO</a>.</p>

</div>
</div>

### getSuccessOrdering() {#a9e13c962466d74908fd163cf3fde05ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AtomicOrdering llvm::MemSDNode::getSuccessOrdering ()</td>
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

<p>Return the atomic ordering requirements for this memory operation.</p>


<p>For cmpxchg atomic operations, return the atomic ordering requirements when store occurs.</p>


<p>Definition at line 1411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#a22cf4b7941bcfec9f5f5fe04d55627df">MMO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3b7d14ce641064b70c1b921dd97afd3e">lowerAtomicArith</a>.</p>

</div>
</div>

### getSyncScopeID() {#a81edbfd4f3e9eefe0e4f53822ac11da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SyncScope::ID llvm::MemSDNode::getSyncScopeID ()</td>
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

<p>Returns the synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for this memory operation.</p>

<p>Definition at line 1406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#a22cf4b7941bcfec9f5f5fe04d55627df">MMO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3b7d14ce641064b70c1b921dd97afd3e">lowerAtomicArith</a>.</p>

</div>
</div>

### isAtomic() {#ad18cdcd86c9bf6d833b6763519b84e8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemSDNode::isAtomic ()</td>
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

<p>Return true if the memory operation ordering is Unordered or higher.</p>

<p>Definition at line 1421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#a22cf4b7941bcfec9f5f5fe04d55627df">MMO</a>.</p>


<p>Referenced by <a href="#a8f317cf85de4c00ba81d5b5309afd4db">isSimple</a>.</p>

</div>
</div>

### isDereferenceable() {#ac689f393979f367a01d766c2d0db529b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemSDNode::isDereferenceable ()</td>
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



<p>Definition at line 1393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a434bf5710046ffbca878d6379c5a6be5">llvm::SDNode::MemSDNodeBits</a>.</p>

</div>
</div>

### isInvariant() {#abfc21c6926e533d26ad132d76eb1b0e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemSDNode::isInvariant ()</td>
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



<p>Definition at line 1394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a434bf5710046ffbca878d6379c5a6be5">llvm::SDNode::MemSDNodeBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a9131ae18383241b54e466cf623a7312b">llvm::AMDGPUTargetLowering::shouldReduceLoadWidth</a>.</p>

</div>
</div>

### isNonTemporal() {#aba37cfe8576deaf53760781cffe425fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemSDNode::isNonTemporal ()</td>
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



<p>Definition at line 1392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a434bf5710046ffbca878d6379c5a6be5">llvm::SDNode::MemSDNodeBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61f23ea50bb7d5e61ca17b8d73bc7f7e">getBROADCAST_LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp/#a50de01231a46d2b82c41aebd0c413690">isFusableLoadOpStorePattern</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a1c9b0061be648da87d7a9102c0179018">isFusableLoadOpStorePattern</a>.</p>

</div>
</div>

### isSimple() {#a8f317cf85de4c00ba81d5b5309afd4db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemSDNode::isSimple ()</td>
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

<p>Returns true if the memory operation is neither atomic or volatile.</p>

<p>Definition at line 1429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="#ad18cdcd86c9bf6d833b6763519b84e8a">isAtomic</a> and <a href="#a64cdf55a9cfb33bd17e61beae253e3aa">isVolatile</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4d6ae8095a6353874359d5f5e886410c">combineMOVDQ2Q</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2022f78361af7995aebd0a398e0a67e">combineSIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61f23ea50bb7d5e61ca17b8d73bc7f7e">getBROADCAST_LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a528e38dffd58ba9e81a7a05fb7d44c11">narrowExtractedVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#addb3e984dfd51a52d5ab5050a30cd4d4">narrowLoadToVZLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a13d359868f5ac633615beeedb6b18b6e">PerformExtractFpToIntStores</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13463f9ee8babeef33857cbbc8ea4af1">llvm::AMDGPUTargetLowering::performLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5991e29bae68e989e978dc600f93b48e">performMemPairCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae17716da714991550ba9ea6f4747831a">PerformSplittingMVETruncToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a91f43e00f77d44c412e9b3675ce35253">PerformSplittingToNarrowingStores</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad85146c9cfc75b8fe84203e7b920b9e2">llvm::AMDGPUTargetLowering::performStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#abe50b03585622dd5b4b3c76d44ea7a8e">TryDistrubutionADDVecReduce</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a5d176b4adbcf9fd77cae6c4d43f13fb2">tryToFoldExtOfExtload</a>.</p>

</div>
</div>

### isUnordered() {#acc4a3e33f4bae266e177eb7749e52281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemSDNode::isUnordered ()</td>
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

<p>Returns true if the memory operation doesn't imply any ordering constraints on surrounding memory operations beyond the normal memory aliasing rules.</p>

<p>Definition at line 1426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#a22cf4b7941bcfec9f5f5fe04d55627df">MMO</a>.</p>

</div>
</div>

### isVolatile() {#a64cdf55a9cfb33bd17e61beae253e3aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemSDNode::isVolatile ()</td>
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



<p>Definition at line 1391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a434bf5710046ffbca878d6379c5a6be5">llvm::SDNode::MemSDNodeBits</a>.</p>


<p>Referenced by <a href="#a8f317cf85de4c00ba81d5b5309afd4db">isSimple</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3b7d14ce641064b70c1b921dd97afd3e">lowerAtomicArith</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a225dca8b49ddf9ae69266aa8448208d0">lowerLoadF128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a5a96f3df430878c8511972852cb08499">lowerLoadI1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#af03b2efb74091548a48b0aebf40349de">lowerStoreF128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#af1126eb4c6731ec07f82bc63d84313fc">lowerStoreI1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bbdb7f279f14b5f7ff6d7d9a2a97765">splitStores</a>.</p>

</div>
</div>

### readMem() {#a8c6f1b67f6d43d4ebaec3e0deb3d9bff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemSDNode::readMem ()</td>
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



<p>Definition at line 1365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#a22cf4b7941bcfec9f5f5fe04d55627df">MMO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61f23ea50bb7d5e61ca17b8d73bc7f7e">getBROADCAST_LOAD</a>.</p>

</div>
</div>

### refineAlignment() {#aaf86ebe900295d7c59ea024fc19d0154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MemSDNode::refineAlignment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * NewMMO)</td>
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

<p>Update this <a href="/web-llvm/docs/api/classes/llvm/memsdnode">MemSDNode</a>'s <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> information to reflect the alignment of NewMMO, if it has a greater alignment.</p>


<p>This must only be used when the new alignment applies to all users of this <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a>.</p>


<p>Definition at line 1451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#a22cf4b7941bcfec9f5f5fe04d55627df">MMO</a>.</p>

</div>
</div>

### writeMem() {#ac2952508de5f419e99507aec16b63a6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemSDNode::writeMem ()</td>
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



<p>Definition at line 1366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Reference <a href="#a22cf4b7941bcfec9f5f5fe04d55627df">MMO</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### MMO {#a22cf4b7941bcfec9f5f5fe04d55627df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineMemOperand* llvm::MemSDNode::MMO</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> reference information.</p>

<p>Definition at line 1359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/atomicsdnode/#a9b8856c7736a3d284467229f318150cb">llvm::AtomicSDNode::AtomicSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/fpstateaccesssdnode/#ab9a711997f966eccb20fa70656b6c4bf">llvm::FPStateAccessSDNode::FPStateAccessSDNode</a>, <a href="#a80f0411207d75b649465f8505a2609f6">getAAInfo</a>, <a href="#a5ba669acfce53f64119001f5d46e162f">getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicsdnode/#ab67e251e2cf3f26e84c20b51d33e3553">llvm::AtomicSDNode::getFailureOrdering</a>, <a href="#aa078a60d1127b9daad580b6d2ba7ef91">getMemOperand</a>, <a href="#ab82eed0d6910bbb28ef05c224d541e88">getMergedOrdering</a>, <a href="#a85cc92919f7704331920d260e71a7439">getOriginalAlign</a>, <a href="#ab58a98ad2eb07046ef0584d2bc8f1d2d">getPointerInfo</a>, <a href="#a4913f6364d5b8207efbd4ba07648749b">getRanges</a>, <a href="#a869f89c8fec7959857a0de4d7bbf5a93">getSrcValueOffset</a>, <a href="#a9e13c962466d74908fd163cf3fde05ee">getSuccessOrdering</a>, <a href="#a81edbfd4f3e9eefe0e4f53822ac11da1">getSyncScopeID</a>, <a href="#ad18cdcd86c9bf6d833b6763519b84e8a">isAtomic</a>, <a href="#acc4a3e33f4bae266e177eb7749e52281">isUnordered</a>, <a href="/web-llvm/docs/api/classes/llvm/lsbasesdnode/#a083785be56ad0ab8dbf81e50a6a761ac">llvm::LSBaseSDNode::LSBaseSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedgatherscattersdnode/#a70ef3f18e52d25106579f0673aaa6b1c">llvm::MaskedGatherScatterSDNode::MaskedGatherScatterSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedgathersdnode/#a61aaa10c02d10b52ecae12b34805d901">llvm::MaskedGatherSDNode::MaskedGatherSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedhistogramsdnode/#a09d27369e89e48419993ed215343c7dd">llvm::MaskedHistogramSDNode::MaskedHistogramSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedloadsdnode/#a1a0e8f3ceb0bee93f6278d985e007f82">llvm::MaskedLoadSDNode::MaskedLoadSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedloadstoresdnode/#a2e7048e7f25ba106f889cbb5c8ab3d09">llvm::MaskedLoadStoreSDNode::MaskedLoadStoreSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedscattersdnode/#a271d77d66ae014c74df87920f4ea05b8">llvm::MaskedScatterSDNode::MaskedScatterSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedstoresdnode/#a07562952b3d598a6158355ac26a326cf">llvm::MaskedStoreSDNode::MaskedStoreSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicsdnode/#a7840ddfe91a4ac8a274c60ed76f496cb">llvm::MemIntrinsicSDNode::MemIntrinsicSDNode</a>, <a href="#a00a2cd9501aed5f7e8746c0458990503">MemSDNode</a>, <a href="#a8c6f1b67f6d43d4ebaec3e0deb3d9bff">readMem</a>, <a href="#aaf86ebe900295d7c59ea024fc19d0154">refineAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::LoadSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/storesdnode/#a6398ba1604e154e21413ce15dd4a180e">llvm::StoreSDNode::SelectionDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbaseloadstoresdnode/#a7cdac375772f7b4e63f30cb6fd02a4c6">llvm::VPBaseLoadStoreSDNode::VPBaseLoadStoreSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpgatherscattersdnode/#a98f56e585d111952edfdc53e8d30e7a5">llvm::VPGatherScatterSDNode::VPGatherScatterSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpgathersdnode/#a660c946f46acfd5e943e9f64eb0aaf6a">llvm::VPGatherSDNode::VPGatherSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vploadsdnode/#a9ad1af6c4a3cad363a085a3d68a8d666">llvm::VPLoadSDNode::VPLoadSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscattersdnode/#ac17d22ad754b0cf3279f6b2085f7c77c">llvm::VPScatterSDNode::VPScatterSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstoresdnode/#a3c08669f110fb4a1f82c92cd8bb85e7d">llvm::VPStoreSDNode::VPStoreSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstridedloadsdnode/#ad5cfda85e5251efee3809e81cd8659be">llvm::VPStridedLoadSDNode::VPStridedLoadSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstridedstoresdnode/#a61e2e3de34d6d12b3f1c2d916d21d281">llvm::VPStridedStoreSDNode::VPStridedStoreSDNode</a> and <a href="#ac2952508de5f419e99507aec16b63a6b">writeMem</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MemoryVT {#adcf740b486e77f73aa73565014bbab44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::MemSDNode::MemoryVT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ad55691554da9be384e9393e8b42a431a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MemSDNode::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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



<p>Definition at line 1476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae243ce466d350b1aca774a6ae9aea81c">llvm::ISD::EXPERIMENTAL_VECTOR_HISTOGRAM</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/sdnode/#af64f53af99d4ee7bbf57ea0aab719254">llvm::SDNode::SDNode</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
