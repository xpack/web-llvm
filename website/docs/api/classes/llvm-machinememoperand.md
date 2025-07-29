---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machinememoperand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachineMemOperand` Class

<p>A description of a memory reference used in the backend. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachineMemOperand { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">llvm/CodeGen/MachineMemOperand.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Flags : uint16_t { <a href="#aaa2020e47e35179234b9ea27d555b2dd">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#aaa2020e47e35179234b9ea27d555b2dd">Flags</a> values. These may be or'd together. <a href="#aaa2020e47e35179234b9ea27d555b2dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0d610acb6092363a1671bdbaf6d6a8b">operator==</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c38ed64cdc76859d04bae00124d59a4">operator!=</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f79d1bbb6720756b5115dd20f499bfb">MachineMemOperand</a> (MachinePointerInfo PtrInfo, Flags flags, LocationSize TS, Align a, const AAMDNodes &amp;AAInfo=AAMDNodes(), const MDNode *Ranges=nullptr, SyncScope::ID SSID=SyncScope::System, AtomicOrdering Ordering=AtomicOrdering::NotAtomic, AtomicOrdering FailureOrdering=AtomicOrdering::NotAtomic)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> object with the specified PtrInfo, flags, size, and base alignment. <a href="#a8f79d1bbb6720756b5115dd20f499bfb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9463512c8c82f1d0c2a16f0cc271c6ab">MachineMemOperand</a> (MachinePointerInfo PtrInfo, Flags flags, LLT type, Align a, const AAMDNodes &amp;AAInfo=AAMDNodes(), const MDNode *Ranges=nullptr, SyncScope::ID SSID=SyncScope::System, AtomicOrdering Ordering=AtomicOrdering::NotAtomic, AtomicOrdering FailureOrdering=AtomicOrdering::NotAtomic)</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4706e639e364501f6000985df1222c58">print</a> (raw_ostream &amp;OS, ModuleSlotTracker &amp;MST, SmallVectorImpl&lt; StringRef &gt; &amp;SSNs, const LLVMContext &amp;Context, const MachineFrameInfo *MFI, const TargetInstrInfo *TII) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Support for operator&lt;&lt;. <a href="#a4706e639e364501f6000985df1222c58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf6610b5b6565e4f1b56ca78c804654f">getPointerInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add9e6ff8fe1923cb64757a6dbcd61676">getValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the base address of the memory access. <a href="#add9e6ff8fe1923cb64757a6dbcd61676">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a308f77ae6a78f1164adfe7e1047cc25c">getPseudoValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87d1d327c95a61bd26cd5e82906d1787">getOpaqueValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aaa2020e47e35179234b9ea27d555b2dd">Flags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab991bb1444579648a165d1b134a0854d">getFlags</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the raw flags of the source value,. <a href="#ab991bb1444579648a165d1b134a0854d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadac6e7fd2d1087b6489906659bb8afb">setFlags</a> (Flags f)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bitwise OR the current flags with the given flags. <a href="#aadac6e7fd2d1087b6489906659bb8afb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa0fb135809edd33ea2b3d0497aa610c">getOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For normal values, this is a byte offset added to the base address. <a href="#afa0fb135809edd33ea2b3d0497aa610c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f583e2bb417139560bde043214d064a">getAddrSpace</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e9d2a9063bce7f5b3d7dd21fd05c79d">getMemoryType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the memory type of the memory reference. <a href="#a3e9d2a9063bce7f5b3d7dd21fd05c79d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ffa31699dee0349f9b9ae1d3ccb21f1">getSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size in bytes of the memory reference. <a href="#a0ffa31699dee0349f9b9ae1d3ccb21f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcceb535a4bb1e23c320e7628476bd5d">getSizeInBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size in bits of the memory reference. <a href="#abcceb535a4bb1e23c320e7628476bd5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01817266a98d1c6b9cf0534d58fff7f5">getType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc15369ab4cc583332950b913e2ef1dd">getAlign</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the minimum known alignment in bytes of the actual memory reference. <a href="#abc15369ab4cc583332950b913e2ef1dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeca5db48b31ea1b54d6fa2f357b11ed3">getBaseAlign</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the minimum known alignment in bytes of the base address, without the offset. <a href="#aeca5db48b31ea1b54d6fa2f357b11ed3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4e46eec152e23bfb02096e53bde67da">getAAInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> tags for the memory reference. <a href="#ad4e46eec152e23bfb02096e53bde67da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ea985de61dfccc6e599ccf7a460c3a3">getRanges</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the range tag for the memory reference. <a href="#a5ea985de61dfccc6e599ccf7a460c3a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a868d2f3118207e595642df68490eeb58">getSyncScopeID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for this memory operation. <a href="#a868d2f3118207e595642df68490eeb58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa45abfa63d76025a0e5b9a46e25dd8d">getSuccessOrdering</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the atomic ordering requirements for this memory operation. <a href="#aaa45abfa63d76025a0e5b9a46e25dd8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d7f5621b8722f892ff704561db9d1cb">getFailureOrdering</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For cmpxchg atomic operations, return the atomic ordering requirements when store does not occur. <a href="#a2d7f5621b8722f892ff704561db9d1cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9919b152ce2ca13aa22426b619c1afca">getMergedOrdering</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a single atomic ordering that is at least as strong as both the success and failure orderings for an atomic operation. <a href="#a9919b152ce2ca13aa22426b619c1afca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a920b2cba409f32b628f4467836ae818e">isLoad</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8215fe1de88affa6954cfbb8fc65612">isStore</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d07cda64e7150bb7f330057c41a2965">isVolatile</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5441fef0bf0e46bdc1f822a2b8545684">isNonTemporal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf40230689d32060ee584e4ba4bf3cc8">isDereferenceable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88b252120eea5192e81cf30e81eccbe9">isInvariant</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6829ff090c767b553f2390e0785adf4a">isAtomic</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this operation has an atomic ordering requirement of unordered or higher, false otherwise. <a href="#a6829ff090c767b553f2390e0785adf4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55d6f8587efdb9efb8cb374f11fe4408">isUnordered</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this memory operation doesn't have any ordering constraints other than normal aliasing. <a href="#a55d6f8587efdb9efb8cb374f11fe4408">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cf00cf755c1275eba246de7ebf7842d">refineAlignment</a> (const MachineMemOperand *MMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update this <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> to reflect the alignment of MMO, if it has a greater alignment. <a href="#a6cf00cf755c1275eba246de7ebf7842d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a606d73cbc9cc6210d626ec4b12c6c32e">setValue</a> (const Value *NewSV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the SourceValue for this <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a>. <a href="#a606d73cbc9cc6210d626ec4b12c6c32e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add89d597c6f35d6071ce2bbf8655d1ff">setValue</a> (const PseudoSourceValue *NewSV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b7acc8555a4466888d20106e3812548">setOffset</a> (int64_t NewOffset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0204ff8c047858d1fb330cafa728b51e">setType</a> (LLT NewTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset the tracked memory type. <a href="#a0204ff8c047858d1fb330cafa728b51e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42f1b2797add6ad1d60e895ad57ecf12">clearRanges</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unset the tracked range metadata. <a href="#a42f1b2797add6ad1d60e895ad57ecf12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a443bfbd40d5c21e1dd1b4b01360a6cb0">PtrInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac53f28dce8545babee163faa4225d232">MemoryType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Track the memory type of the access. <a href="#ac53f28dce8545babee163faa4225d232">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aaa2020e47e35179234b9ea27d555b2dd">Flags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a462af0b273f9c65058b44fd23d44e100">FlagVals</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4485ae384604c9aab024dcb05c5d39da">BaseAlign</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MachineAtomicInfo</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef4a4190e82c8a16bbf7cd07afa55915">AtomicInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fcbb4fe8fb645ad9ce8d3c255d82b8b">AAInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a973f8a68f753bd95de1344d250f883">Ranges</a></td>
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

<p>A description of a memory reference used in the backend.</p>


<p>Instead of holding a <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> or <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a>, this class holds the address <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of the reference along with a byte size and offset. This allows it to describe lowered loads and stores. Also, the special <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> objects can be used to represent loads and stores to memory locations that aren't explicit in the regular LLVM IR.</p>


<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Flags {#aaa2020e47e35179234b9ea27d555b2dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MachineMemOperand::Flags : uint16_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#aaa2020e47e35179234b9ea27d555b2dd">Flags</a> values. These may be or'd together.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MONone<a id="aaa2020e47e35179234b9ea27d555b2ddac2989bebe46c9b9fcb7a92e5ade8dde6"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOLoad<a id="aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494"></a></td>
<td class="doxyEnumItemDescription">The memory access reads data (= 1u &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOStore<a id="aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374"></a></td>
<td class="doxyEnumItemDescription">The memory access writes data (= 1u &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOVolatile<a id="aaa2020e47e35179234b9ea27d555b2dda796891d6ca349b671fce24b6d01d77a8"></a></td>
<td class="doxyEnumItemDescription">The memory access is volatile (= 1u &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MONonTemporal<a id="aaa2020e47e35179234b9ea27d555b2dda8d09c51969b0954512ed65ee26551081"></a></td>
<td class="doxyEnumItemDescription">The memory access is non-temporal (= 1u &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODereferenceable<a id="aaa2020e47e35179234b9ea27d555b2dda7b999a936bc7a4d45dfadbe356e77b3f"></a></td>
<td class="doxyEnumItemDescription">The memory access is dereferenceable (i.e., doesn't trap) (= 1u &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOInvariant<a id="aaa2020e47e35179234b9ea27d555b2ddac63dd9c4fe69bfeaac7a363fda846ac6"></a></td>
<td class="doxyEnumItemDescription">The memory access always returns the same value (or traps) (= 1u &lt;&lt; 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOTargetFlag1<a id="aaa2020e47e35179234b9ea27d555b2ddace83cf304d65cdb6b3b22cc485eed877"></a></td>
<td class="doxyEnumItemDescription"> (= 1u &lt;&lt; 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOTargetFlag2<a id="aaa2020e47e35179234b9ea27d555b2dda036efcf0f4eac932646d211f480528c3"></a></td>
<td class="doxyEnumItemDescription"> (= 1u &lt;&lt; 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOTargetFlag3<a id="aaa2020e47e35179234b9ea27d555b2ddad7c78ebdd6e4c475178f5ca950914f33"></a></td>
<td class="doxyEnumItemDescription"> (= 1u &lt;&lt; 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOTargetFlag4<a id="aaa2020e47e35179234b9ea27d555b2ddaedf4acd5685f78004a429b3945764d81"></a></td>
<td class="doxyEnumItemDescription"> (= 1u &lt;&lt; 9)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### operator!= {#a8c38ed64cdc76859d04bae00124d59a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; RHS</td>
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


<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="#a8f79d1bbb6720756b5115dd20f499bfb">MachineMemOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator== {#ac0d610acb6092363a1671bdbaf6d6a8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> &amp; RHS</td>
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


<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="#a8f79d1bbb6720756b5115dd20f499bfb">MachineMemOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachineMemOperand() {#a8f79d1bbb6720756b5115dd20f499bfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineMemOperand::MachineMemOperand (<a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> PtrInfo, <a href="#aaa2020e47e35179234b9ea27d555b2dd">Flags</a> flags, <a href="/web-llvm/docs/api/classes/llvm/locationsize">LocationSize</a> TS, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> a, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> &amp; AAInfo=<a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a>(), <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Ranges=nullptr, <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> SSID=<a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a15caddcf5c9b41f2f15c2ec363589f6caf9706a2e196638078e8323bfd9ba17de">SyncScope::System</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ordering=<a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">AtomicOrdering::NotAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> FailureOrdering=<a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">AtomicOrdering::NotAtomic</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> object with the specified PtrInfo, flags, size, and base alignment.</p>


<p>For atomic operations the synchronization scope and atomic ordering requirements must also be specified. For cmpxchg atomic operations the atomic ordering requirements when store does not occur must also be specified.</p>


<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>, definition at line 1114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#add9e6ff8fe1923cb64757a6dbcd61676">getValue</a> and <a href="#a8f79d1bbb6720756b5115dd20f499bfb">MachineMemOperand</a>.</p>


<p>Referenced by <a href="#a8f79d1bbb6720756b5115dd20f499bfb">MachineMemOperand</a>, <a href="#a8c38ed64cdc76859d04bae00124d59a4">operator!=</a>, <a href="#ac0d610acb6092363a1671bdbaf6d6a8b">operator==</a> and <a href="#a6cf00cf755c1275eba246de7ebf7842d">refineAlignment</a>.</p>

</div>
</div>

### MachineMemOperand() {#a9463512c8c82f1d0c2a16f0cc271c6ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineMemOperand::MachineMemOperand (<a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> PtrInfo, <a href="#aaa2020e47e35179234b9ea27d555b2dd">Flags</a> flags, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> type, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> a, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> &amp; AAInfo=<a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a>(), <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Ranges=nullptr, <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> SSID=<a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a15caddcf5c9b41f2f15c2ec363589f6caf9706a2e196638078e8323bfd9ba17de">SyncScope::System</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ordering=<a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">AtomicOrdering::NotAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> FailureOrdering=<a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">AtomicOrdering::NotAtomic</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>, definition at line 1094 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a2d7f5621b8722f892ff704561db9d1cb">getFailureOrdering</a>, <a href="#aaa45abfa63d76025a0e5b9a46e25dd8d">getSuccessOrdering</a>, <a href="#a868d2f3118207e595642df68490eeb58">getSyncScopeID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a920b2cba409f32b628f4467836ae818e">isLoad</a> and <a href="#aa8215fe1de88affa6954cfbb8fc65612">isStore</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### print() {#a4706e639e364501f6000985df1222c58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineMemOperand::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; SSNs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> * MFI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Support for operator&lt;&lt;.</p>

<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>, definition at line 1150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue/#a9959ffdc41bc31cf2211b8824f79259eae05129b008395b214fc0ee1bea862f29">llvm::PseudoSourceValue::ConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue/#a9959ffdc41bc31cf2211b8824f79259eaac8626d58c6d77b8394e51a3e1170f04">llvm::PseudoSourceValue::ExternalSymbolCallEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue/#a9959ffdc41bc31cf2211b8824f79259eaf38d1857511c3f0404c95f65664b36ab">llvm::PseudoSourceValue::FixedStack</a>, <a href="#ad4e46eec152e23bfb02096e53bde67da">getAAInfo</a>, <a href="#a3f583e2bb417139560bde043214d064a">getAddrSpace</a>, <a href="#abc15369ab4cc583332950b913e2ef1dd">getAlign</a>, <a href="#aeca5db48b31ea1b54d6fa2f357b11ed3">getBaseAlign</a>, <a href="#a2d7f5621b8722f892ff704561db9d1cb">getFailureOrdering</a>, <a href="#ab991bb1444579648a165d1b134a0854d">getFlags</a>, <a href="#a3e9d2a9063bce7f5b3d7dd21fd05c79d">getMemoryType</a>, <a href="#afa0fb135809edd33ea2b3d0497aa610c">getOffset</a>, <a href="#a87d1d327c95a61bd26cd5e82906d1787">getOpaqueValue</a>, <a href="#a308f77ae6a78f1164adfe7e1047cc25c">getPseudoValue</a>, <a href="#a5ea985de61dfccc6e599ccf7a460c3a3">getRanges</a>, <a href="#a0ffa31699dee0349f9b9ae1d3ccb21f1">getSize</a>, <a href="#aaa45abfa63d76025a0e5b9a46e25dd8d">getSuccessOrdering</a>, <a href="#a868d2f3118207e595642df68490eeb58">getSyncScopeID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a8958e62bf7c2eb551a7004ae14def896">getTargetMMOFlagName</a>, <a href="#add9e6ff8fe1923cb64757a6dbcd61676">getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue/#a9959ffdc41bc31cf2211b8824f79259ea989f21374348c0921d46fda31fb0c29f">llvm::PseudoSourceValue::GlobalValueCallEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue/#a9959ffdc41bc31cf2211b8824f79259ea312314536c6c788acece6a3f1cb47d1c">llvm::PseudoSourceValue::GOT</a>, <a href="#abf40230689d32060ee584e4ba4bf3cc8">isDereferenceable</a>, <a href="#a88b252120eea5192e81cf30e81eccbe9">isInvariant</a>, <a href="#a920b2cba409f32b628f4467836ae818e">isLoad</a>, <a href="#a5441fef0bf0e46bdc1f822a2b8545684">isNonTemporal</a>, <a href="#aa8215fe1de88affa6954cfbb8fc65612">isStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a>, <a href="#a1d07cda64e7150bb7f330057c41a2965">isVolatile</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lint-cpp/#a45005634b54e2126cb3e6ec0dbc9ade4">isZero</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue/#a9959ffdc41bc31cf2211b8824f79259eaa9507353b6734246ea32fe68212077de">llvm::PseudoSourceValue::JumpTable</a>, <a href="#aaa2020e47e35179234b9ea27d555b2ddace83cf304d65cdb6b3b22cc485eed877">MOTargetFlag1</a>, <a href="#aaa2020e47e35179234b9ea27d555b2dda036efcf0f4eac932646d211f480528c3">MOTargetFlag2</a>, <a href="#aaa2020e47e35179234b9ea27d555b2ddad7c78ebdd6e4c475178f5ca950914f33">MOTargetFlag3</a>, <a href="#aaa2020e47e35179234b9ea27d555b2ddaedf4acd5685f78004a429b3945764d81">MOTargetFlag4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata/#abea60f56bef2a0f9437eed8c8bb9ec58">llvm::Metadata::printAsOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mirformatter/#ac7f9e48c43ea5f9f37fee565d0a18b36">llvm::MIRFormatter::printCustomPseudoSourceValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a294946bd7b49d5ef31f4f42120f75b92">printFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mirformatter/#afe314b6a6d04121d7d8bf9f8ad80605b">llvm::MIRFormatter::printIRValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef01c7734472703b7f3d76c5af23e1d3">llvm::printLLVMNameWithoutPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a91a415f70087b68402bb454cc1b8fa18">llvm::MachineOperand::printOperandOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a12b99b3e536e8f7ddb0167814d1c0d50">printSyncScope</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue/#a9959ffdc41bc31cf2211b8824f79259ea4409983ec879eefed025abf900eeed47">llvm::PseudoSourceValue::Stack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a473a7928f2af5c01022800db638773">llvm::toIRString</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp/#ace21909c26dd090286cc93b20b5a3cc4">printMemOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearRanges() {#a42f1b2797add6ad1d60e895ad57ecf12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineMemOperand::clearRanges ()</td>
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

<p>Unset the tracked range metadata.</p>

<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6c12dbad109a5d725ce01a9a8363f948">llvm::LegalizerHelper::bitcast</a>.</p>

</div>
</div>

### getAAInfo() {#ad4e46eec152e23bfb02096e53bde67da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAMDNodes llvm::MachineMemOperand::getAAInfo ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> tags for the memory reference.</p>

<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a1aeb03a2dac908dce3ff3979e298fb21">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4daf9210f39aa637461ce01733361b89">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a3d46b900827f1a36ca44ea87cfb18e1f">MemOperandsHaveAlias</a> and <a href="#a4706e639e364501f6000985df1222c58">print</a>.</p>

</div>
</div>

### getAddrSpace() {#a3f583e2bb417139560bde043214d064a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineMemOperand::getAddrSpace ()</td>
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



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a174b5d5b553214494871f914bef97780">llvm::TargetLoweringBase::allowsMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a771899ed4c24646810028006d103550e">llvm::TargetLoweringBase::allowsMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a76385ca67c48554c408107c686ed0c68">llvm::X86TargetLowering::allowsMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6a8fb0e41c4f07f036e247f9503e3a24">llvm::TargetLoweringBase::allowsMemoryAccessForAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a87ac3f636dddf683cf1f9b7f1a60b1ae">llvm::AMDGPURegisterBankInfo::applyMappingLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a7ebf01237ea354d0baf26fae2f0a04a3">llvm::AMDGPURegisterBankInfo::isScalarLoadLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstrinfo/#aa510d94632f7a11fd571d2c2271fb2b5">llvm::AMDGPUInstrInfo::isUniformMMO</a>, <a href="#a4706e639e364501f6000985df1222c58">print</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpu/regbanklegalizerules/#a4b79850edbd4118074e95097dca45fa5">llvm::AMDGPU::RegBankLegalizeRules::RegBankLegalizeRules</a>.</p>

</div>
</div>

### getAlign() {#abc15369ab4cc583332950b913e2ef1dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align MachineMemOperand::getAlign ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the minimum known alignment in bytes of the actual memory reference.</p>


<p>getAlign - Return the minimum known alignment in bytes of the actual memory reference.</p>


<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>, definition at line 1146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd6aa057934751aaac54e5c18bcc18eb">llvm::commonAlignment</a>, <a href="#aeca5db48b31ea1b54d6fa2f357b11ed3">getBaseAlign</a> and <a href="#afa0fb135809edd33ea2b3d0497aa610c">getOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a174b5d5b553214494871f914bef97780">llvm::TargetLoweringBase::allowsMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a771899ed4c24646810028006d103550e">llvm::TargetLoweringBase::allowsMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a76385ca67c48554c408107c686ed0c68">llvm::X86TargetLowering::allowsMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6a8fb0e41c4f07f036e247f9503e3a24">llvm::TargetLoweringBase::allowsMemoryAccessForAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a87ac3f636dddf683cf1f9b7f1a60b1ae">llvm::AMDGPURegisterBankInfo::applyMappingLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a3ad30602142008d0355fc41c4f0626d0">isMemoryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a7ebf01237ea354d0baf26fae2f0a04a3">llvm::AMDGPURegisterBankInfo::isScalarLoadLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af13d2c38b3bf7586a8f07d511eda68e8">llvm::AMDGPULegalizerInfo::legalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a28a0f1422b780a83a9632e5d46993dfc">llvm::CombinerHelper::matchCombineExtractedVectorLoad</a>, <a href="#a4706e639e364501f6000985df1222c58">print</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpu/regbanklegalizerules/#a4b79850edbd4118074e95097dca45fa5">llvm::AMDGPU::RegBankLegalizeRules::RegBankLegalizeRules</a>.</p>

</div>
</div>

### getBaseAlign() {#aeca5db48b31ea1b54d6fa2f357b11ed3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MachineMemOperand::getBaseAlign ()</td>
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

<p>Return the minimum known alignment in bytes of the base address, without the offset.</p>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Referenced by <a href="#abc15369ab4cc583332950b913e2ef1dd">getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6955c5032aa85a99ea502c0143fd6b49">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#abfa1dc430433ec6f98c1d88468e053a5">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a30d0854bc31e4a30a47cfd3d2d1d6e18">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a1aeb03a2dac908dce3ff3979e298fb21">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4daf9210f39aa637461ce01733361b89">llvm::MachineFunction::getMachineMemOperand</a>, <a href="#a4706e639e364501f6000985df1222c58">print</a> and <a href="#a6cf00cf755c1275eba246de7ebf7842d">refineAlignment</a>.</p>

</div>
</div>

### getFailureOrdering() {#a2d7f5621b8722f892ff704561db9d1cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AtomicOrdering llvm::MachineMemOperand::getFailureOrdering ()</td>
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

<p>For cmpxchg atomic operations, return the atomic ordering requirements when store does not occur.</p>

<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6955c5032aa85a99ea502c0143fd6b49">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#abfa1dc430433ec6f98c1d88468e053a5">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a30d0854bc31e4a30a47cfd3d2d1d6e18">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a1aeb03a2dac908dce3ff3979e298fb21">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4daf9210f39aa637461ce01733361b89">llvm::MachineFunction::getMachineMemOperand</a>, <a href="#a9919b152ce2ca13aa22426b619c1afca">getMergedOrdering</a>, <a href="#a9463512c8c82f1d0c2a16f0cc271c6ab">MachineMemOperand</a> and <a href="#a4706e639e364501f6000985df1222c58">print</a>.</p>

</div>
</div>

### getFlags() {#ab991bb1444579648a165d1b134a0854d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Flags llvm::MachineMemOperand::getFlags ()</td>
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

<p>Return the raw flags of the source value,.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#aaa2020e47e35179234b9ea27d555b2dd">Flags</a>.</p></dd>
</dl>


<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#abd574741643b21b2db236255e18656db">AddNodeIDCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a174b5d5b553214494871f914bef97780">llvm::TargetLoweringBase::allowsMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a771899ed4c24646810028006d103550e">llvm::TargetLoweringBase::allowsMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a76385ca67c48554c408107c686ed0c68">llvm::X86TargetLowering::allowsMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6a8fb0e41c4f07f036e247f9503e3a24">llvm::TargetLoweringBase::allowsMemoryAccessForAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a57982dfc711f20ecf31431bc37259cd7">llvm::SIRegisterInfo::buildSpillLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4d6ae8095a6353874359d5f5e886410c">combineMOVDQ2Q</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1a1f2f01c1eb849390f448f90643c6ff">llvm::SelectionDAG::getAtomic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5bd5e426c197fd66ec0ac6f088d51185">llvm::SelectionDAG::getGatherVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3af6334751e0a4eaf2b2a253f545a861">llvm::SelectionDAG::getGetFPEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab280576b46181ebb3a3716370169c287">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab517db4292565daf5cea12e127f9db87">llvm::SelectionDAG::getLoadVP</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6955c5032aa85a99ea502c0143fd6b49">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#abfa1dc430433ec6f98c1d88468e053a5">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a30d0854bc31e4a30a47cfd3d2d1d6e18">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a1aeb03a2dac908dce3ff3979e298fb21">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0bc0f0450beae61b3c7c3f110d3b7c5c">llvm::SelectionDAG::getMaskedGather</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a77eef56a45fec10f706e25be688f3beb">llvm::SelectionDAG::getMaskedHistogram</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af2a48350a921ca25a0939a82228555f4">llvm::SelectionDAG::getMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aff2202a13bbfad20f9b5156fd930cf01">llvm::SelectionDAG::getMaskedScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa83e0455dcd3f0feb08e08ebb0a18db0">llvm::SelectionDAG::getMaskedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6fc57a7458164a2086dfee32a82530db">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8b2b591dc9b054d04368b7d069fb76c">llvm::SelectionDAG::getScatterVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa7cfce69eeecdf585f55b39efbdff6ba">llvm::SelectionDAG::getSetFPEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a211f6d3863ce35b5a5893032fe0449cc">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7bebd21fcb08b6b7288fee3de1246c52">llvm::SelectionDAG::getStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c2603648fb228b097b421cfd6c577e2">llvm::SelectionDAG::getTruncStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2b70646a1a7d39196c9e405e6e765b98">llvm::SelectionDAG::getTruncStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a934e0e0b94737441bea75fc4babf0021">llvm::SITargetLowering::isMemOpHasNoClobberedMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a7ebf01237ea354d0baf26fae2f0a04a3">llvm::AMDGPURegisterBankInfo::isScalarLoadLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a4394bc2d4e4e90b47c9876e546e1429d">lowerFP_TO_SINT_STORE</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a665ef5a5179d9d6112b5215fe27caa83">llvm::HexagonTargetLowering::LowerLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a47413709ef916baf36607da462d93ccc">LowerLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#afba0648a688bd0202b03710302c89a2f">LowerSTORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a05914158f39e230548b1b743eee2e5f6">LowerStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#addb3e984dfd51a52d5ab5050a30cd4d4">narrowLoadToVZLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a13d359868f5ac633615beeedb6b18b6e">PerformExtractFpToIntStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a03b14e6aca1277bdee37639aec700ba7">performIntToFpCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13463f9ee8babeef33857cbbc8ea4af1">llvm::AMDGPUTargetLowering::performLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae17716da714991550ba9ea6f4747831a">PerformSplittingMVETruncToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a91f43e00f77d44c412e9b3675ce35253">PerformSplittingToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad85146c9cfc75b8fe84203e7b920b9e2">llvm::AMDGPUTargetLowering::performStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aba237afe216b870806584d3e96e575b4">PerformTruncatingStoreCombine</a>, <a href="#a4706e639e364501f6000985df1222c58">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa649493d03967e1898ad4354759d89f7">reduceMaskedStoreToScalarStore</a>, <a href="#a6cf00cf755c1275eba246de7ebf7842d">refineAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a16e6c862a36871c4f388c826ad65b07c">llvm::SparcTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bbdb7f279f14b5f7ff6d7d9a2a97765">splitStores</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6a7f067c980840336e15888700870c6a">splitStoreSplat</a>.</p>

</div>
</div>

### getMemoryType() {#a3e9d2a9063bce7f5b3d7dd21fd05c79d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT llvm::MachineMemOperand::getMemoryType ()</td>
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

<p>Return the memory type of the memory reference.</p>


<p>This should only be relied on for GlobalISel G_* operation legalization.</p>


<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6c12dbad109a5d725ce01a9a8363f948">llvm::LegalizerHelper::bitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a89e5277b1b90b54ea21a51120f9a4206">llvm::AMDGPULegalizerInfo::legalizeBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2324ad614c957fc91b34a00f32e89d60">llvm::AMDGPULegalizerInfo::legalizeBufferStore</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af13d2c38b3bf7586a8f07d511eda68e8">llvm::AMDGPULegalizerInfo::legalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1dbb219846876149646e81e84ee81a47">llvm::LegalizerHelper::lowerLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a40e2e64056fc2e2dabadfb9ceae338f6">llvm::LegalizerHelper::lowerStore</a>, <a href="#a4706e639e364501f6000985df1222c58">print</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6d8b5e9460092c4517e5e594756fcb82">llvm::LegalizerHelper::scalarizeVectorBooleanStore</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>.</p>

</div>
</div>

### getMergedOrdering() {#a9919b152ce2ca13aa22426b619c1afca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AtomicOrdering llvm::MachineMemOperand::getMergedOrdering ()</td>
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


<p>(For operations other than cmpxchg, this is equivalent to <a href="#aaa45abfa63d76025a0e5b9a46e25dd8d">getSuccessOrdering()</a>.)</p>


<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>References <a href="#a2d7f5621b8722f892ff704561db9d1cb">getFailureOrdering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71b43b93703d7128b0cec9c04a91818a">llvm::getMergedAtomicOrdering</a> and <a href="#aaa45abfa63d76025a0e5b9a46e25dd8d">getSuccessOrdering</a>.</p>

</div>
</div>

### getOffset() {#afa0fb135809edd33ea2b3d0497aa610c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MachineMemOperand::getOffset ()</td>
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

<p>For normal values, this is a byte offset added to the base address.</p>


<p>For PseudoSourceValue::FPRel values, this is the FrameIndex number.</p>


<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#ab357dab967cae539bb19a9aa0a101fed">llvm::SystemZInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/ppchazardrecognizer970/#afe71af95c1e795a56d13e488898d58f5">llvm::PPCHazardRecognizer970::EmitInstruction</a>, <a href="#abc15369ab4cc583332950b913e2ef1dd">getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/ppchazardrecognizer970/#a930f5688f2bff088096f72a68000c94e">llvm::PPCHazardRecognizer970::getHazardType</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6955c5032aa85a99ea502c0143fd6b49">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a3d46b900827f1a36ca44ea87cfb18e1f">MemOperandsHaveAlias</a> and <a href="#a4706e639e364501f6000985df1222c58">print</a>.</p>

</div>
</div>

### getOpaqueValue() {#a87d1d327c95a61bd26cd5e82906d1787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const void * llvm::MachineMemOperand::getOpaqueValue ()</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Referenced by <a href="#a4706e639e364501f6000985df1222c58">print</a>.</p>

</div>
</div>

### getPointerInfo() {#aaf6610b5b6565e4f1b56ca78c804654f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachinePointerInfo &amp; llvm::MachineMemOperand::getPointerInfo ()</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a57982dfc711f20ecf31431bc37259cd7">llvm::SIRegisterInfo::buildSpillLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1a1f2f01c1eb849390f448f90643c6ff">llvm::SelectionDAG::getAtomic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5bd5e426c197fd66ec0ac6f088d51185">llvm::SelectionDAG::getGatherVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3af6334751e0a4eaf2b2a253f545a861">llvm::SelectionDAG::getGetFPEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab280576b46181ebb3a3716370169c287">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab517db4292565daf5cea12e127f9db87">llvm::SelectionDAG::getLoadVP</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a1aeb03a2dac908dce3ff3979e298fb21">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4daf9210f39aa637461ce01733361b89">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0bc0f0450beae61b3c7c3f110d3b7c5c">llvm::SelectionDAG::getMaskedGather</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a77eef56a45fec10f706e25be688f3beb">llvm::SelectionDAG::getMaskedHistogram</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af2a48350a921ca25a0939a82228555f4">llvm::SelectionDAG::getMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aff2202a13bbfad20f9b5156fd930cf01">llvm::SelectionDAG::getMaskedScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa83e0455dcd3f0feb08e08ebb0a18db0">llvm::SelectionDAG::getMaskedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6fc57a7458164a2086dfee32a82530db">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8b2b591dc9b054d04368b7d069fb76c">llvm::SelectionDAG::getScatterVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa7cfce69eeecdf585f55b39efbdff6ba">llvm::SelectionDAG::getSetFPEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a211f6d3863ce35b5a5893032fe0449cc">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7bebd21fcb08b6b7288fee3de1246c52">llvm::SelectionDAG::getStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2319cb3270540dfd23ffd53d5a9bd8aa">llvm::SelectionDAG::getStridedLoadVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4eeee43813ecf8dee2c4ccb837ec33b5">llvm::SelectionDAG::getStridedStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c2603648fb228b097b421cfd6c577e2">llvm::SelectionDAG::getTruncStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2b70646a1a7d39196c9e405e6e765b98">llvm::SelectionDAG::getTruncStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ace48e423cac6b59de28c739fbe31c34d">llvm::SelectionDAG::getTruncStridedStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1dbb219846876149646e81e84ee81a47">llvm::LegalizerHelper::lowerLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a40e2e64056fc2e2dabadfb9ceae338f6">llvm::LegalizerHelper::lowerStore</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a28a0f1422b780a83a9632e5d46993dfc">llvm::CombinerHelper::matchCombineExtractedVectorLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a5d600f23e7d301bfcf60b292eaba31ef">llvm::CombinerHelper::matchCombineLoadWithAndMask</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a070e7ae88917971c8b99b3bb7f3d5942">llvm::CombinerHelper::matchLoadOrCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6d8b5e9460092c4517e5e594756fcb82">llvm::LegalizerHelper::scalarizeVectorBooleanStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae7edfd8337d702eebfdbf7010c3b2c74">tryMemPairCombine</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a>.</p>

</div>
</div>

### getPseudoValue() {#a308f77ae6a78f1164adfe7e1047cc25c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PseudoSourceValue * llvm::MachineMemOperand::getPseudoValue ()</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#ab357dab967cae539bb19a9aa0a101fed">llvm::SystemZInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6885e40448874565521daac98e11f50d">llvm::TargetInstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6955c5032aa85a99ea502c0143fd6b49">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#af70c8631842f164543c4c32149b97759">getMMOFrameID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a3d46b900827f1a36ca44ea87cfb18e1f">MemOperandsHaveAlias</a> and <a href="#a4706e639e364501f6000985df1222c58">print</a>.</p>

</div>
</div>

### getRanges() {#a5ea985de61dfccc6e599ccf7a460c3a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MDNode * llvm::MachineMemOperand::getRanges ()</td>
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

<p>Return the range tag for the memory reference.</p>

<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a0e367b6a777f570054f6c62eb885a609">llvm::GISelKnownBits::computeKnownBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6955c5032aa85a99ea502c0143fd6b49">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4daf9210f39aa637461ce01733361b89">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ganyload/#af79e3c82a97791f6e46aecd8bbdcf6ac">llvm::GAnyLoad::getRanges</a>, <a href="#a4706e639e364501f6000985df1222c58">print</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### getSize() {#a0ffa31699dee0349f9b9ae1d3ccb21f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationSize llvm::MachineMemOperand::getSize ()</td>
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

<p>Return the size in bytes of the memory reference.</p>

<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a837cf7f4d88580c0adb92afc6a3b08b0">llvm::LocationSize::beforeOrAfterPointer</a> and <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a131715ceeb92fb803a329d6b76d14e0d">llvm::LocationSize::precise</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a87ac3f636dddf683cf1f9b7f1a60b1ae">llvm::AMDGPURegisterBankInfo::applyMappingLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#ab357dab967cae539bb19a9aa0a101fed">llvm::SystemZInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6885e40448874565521daac98e11f50d">llvm::TargetInstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppchazardrecognizer970/#afe71af95c1e795a56d13e488898d58f5">llvm::PPCHazardRecognizer970::EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a414d9dfa6f85f8ad371a510821713e61">llvm::PPCTargetLowering::expandVSXLoadForLE</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#abf2cd323dcdc4b2b0a4741c62b30d0ba">llvm::PPCTargetLowering::expandVSXStoreForLE</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ppchazardrecognizer970/#a930f5688f2bff088096f72a68000c94e">llvm::PPCHazardRecognizer970::getHazardType</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6955c5032aa85a99ea502c0143fd6b49">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4daf9210f39aa637461ce01733361b89">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#a515116c40bd191aee04f328b504d5692">llvm::GMemOperation::getMemSize</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a7ebf01237ea354d0baf26fae2f0a04a3">llvm::AMDGPURegisterBankInfo::isScalarLoadLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2324ad614c957fc91b34a00f32e89d60">llvm::AMDGPULegalizerInfo::legalizeBufferStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a3d46b900827f1a36ca44ea87cfb18e1f">MemOperandsHaveAlias</a>, <a href="#a4706e639e364501f6000985df1222c58">print</a>, <a href="#a6cf00cf755c1275eba246de7ebf7842d">refineAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/regbanklegalizerules/#a4b79850edbd4118074e95097dca45fa5">llvm::AMDGPU::RegBankLegalizeRules::RegBankLegalizeRules</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### getSizeInBits() {#abcceb535a4bb1e23c320e7628476bd5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationSize llvm::MachineMemOperand::getSizeInBits ()</td>
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

<p>Return the size in bits of the memory reference.</p>

<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a837cf7f4d88580c0adb92afc6a3b08b0">llvm::LocationSize::beforeOrAfterPointer</a> and <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a131715ceeb92fb803a329d6b76d14e0d">llvm::LocationSize::precise</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/giselknownbits/#a651adf8bbb2fece837c1ef70250e19ce">llvm::GISelKnownBits::computeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#ac815a03646b3fcf26176feb2c669fb9e">llvm::GMemOperation::getMemSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### getSuccessOrdering() {#aaa45abfa63d76025a0e5b9a46e25dd8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AtomicOrdering llvm::MachineMemOperand::getSuccessOrdering ()</td>
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


<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6955c5032aa85a99ea502c0143fd6b49">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#abfa1dc430433ec6f98c1d88468e053a5">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a30d0854bc31e4a30a47cfd3d2d1d6e18">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a1aeb03a2dac908dce3ff3979e298fb21">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4daf9210f39aa637461ce01733361b89">llvm::MachineFunction::getMachineMemOperand</a>, <a href="#a9919b152ce2ca13aa22426b619c1afca">getMergedOrdering</a>, <a href="#a6829ff090c767b553f2390e0785adf4a">isAtomic</a>, <a href="#a55d6f8587efdb9efb8cb374f11fe4408">isUnordered</a>, <a href="#a9463512c8c82f1d0c2a16f0cc271c6ab">MachineMemOperand</a>, <a href="#a4706e639e364501f6000985df1222c58">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### getSyncScopeID() {#a868d2f3118207e595642df68490eeb58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SyncScope::ID llvm::MachineMemOperand::getSyncScopeID ()</td>
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

<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6955c5032aa85a99ea502c0143fd6b49">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#abfa1dc430433ec6f98c1d88468e053a5">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a30d0854bc31e4a30a47cfd3d2d1d6e18">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a1aeb03a2dac908dce3ff3979e298fb21">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a4daf9210f39aa637461ce01733361b89">llvm::MachineFunction::getMachineMemOperand</a>, <a href="#a9463512c8c82f1d0c2a16f0cc271c6ab">MachineMemOperand</a> and <a href="#a4706e639e364501f6000985df1222c58">print</a>.</p>

</div>
</div>

### getType() {#a01817266a98d1c6b9cf0534d58fff7f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT llvm::MachineMemOperand::getType ()</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>

</div>
</div>

### getValue() {#add9e6ff8fe1923cb64757a6dbcd61676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * llvm::MachineMemOperand::getValue ()</td>
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

<p>Return the base address of the memory access.</p>


<p>This may either be a normal LLVM IR <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, or one of the special values used in CodeGen. Special values are those obtained via PseudoSourceValue::getFixedStack(int), PseudoSourceValue::getStack, and other <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> member functions which return objects which stand for frame/stack pointer relative references and other special references which are not representable in the high-level IR.</p>


<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#ab357dab967cae539bb19a9aa0a101fed">llvm::SystemZInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/ppchazardrecognizer970/#afe71af95c1e795a56d13e488898d58f5">llvm::PPCHazardRecognizer970::EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/ppchazardrecognizer970/#a930f5688f2bff088096f72a68000c94e">llvm::PPCHazardRecognizer970::getHazardType</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6955c5032aa85a99ea502c0143fd6b49">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#af70c8631842f164543c4c32149b97759">getMMOFrameID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a1c6ca3bca5d47b669bf974f527f05c8c">getUnderlyingObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstrinfo/#aa510d94632f7a11fd571d2c2271fb2b5">llvm::AMDGPUInstrInfo::isUniformMMO</a>, <a href="#a8f79d1bbb6720756b5115dd20f499bfb">MachineMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a3d46b900827f1a36ca44ea87cfb18e1f">MemOperandsHaveAlias</a> and <a href="#a4706e639e364501f6000985df1222c58">print</a>.</p>

</div>
</div>

### isAtomic() {#a6829ff090c767b553f2390e0785adf4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineMemOperand::isAtomic ()</td>
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

<p>Returns true if this operation has an atomic ordering requirement of unordered or higher, false otherwise.</p>

<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>References <a href="#aaa45abfa63d76025a0e5b9a46e25dd8d">getSuccessOrdering</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a497e8884b8ae421c7dadff0f0eea5e3e">llvm::MachineIRBuilder::buildAtomicRMW</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaimemalucombiner-cpp/#a3d8451ff05b58b604cb87a1623ef73b3">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#a9c309120c87f6a16704169f193bfc711">llvm::GMemOperation::isAtomic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a3ad30602142008d0355fc41c4f0626d0">isMemoryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a7ebf01237ea354d0baf26fae2f0a04a3">llvm::AMDGPURegisterBankInfo::isScalarLoadLegal</a> and <a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisel/#a977ad76f842f5addf1b023121d96465e">anonymous{SystemZISelDAGToDAG.cpp}::SystemZDAGToDAGISel::Select</a>.</p>

</div>
</div>

### isDereferenceable() {#abf40230689d32060ee584e4ba4bf3cc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineMemOperand::isDereferenceable ()</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Reference <a href="#aaa2020e47e35179234b9ea27d555b2dda7b999a936bc7a4d45dfadbe356e77b3f">MODereferenceable</a>.</p>


<p>Referenced by <a href="#a4706e639e364501f6000985df1222c58">print</a>.</p>

</div>
</div>

### isInvariant() {#a88b252120eea5192e81cf30e81eccbe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineMemOperand::isInvariant ()</td>
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



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Reference <a href="#aaa2020e47e35179234b9ea27d555b2ddac63dd9c4fe69bfeaac7a363fda846ac6">MOInvariant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a7ebf01237ea354d0baf26fae2f0a04a3">llvm::AMDGPURegisterBankInfo::isScalarLoadLegal</a> and <a href="#a4706e639e364501f6000985df1222c58">print</a>.</p>

</div>
</div>

### isLoad() {#a920b2cba409f32b628f4467836ae818e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineMemOperand::isLoad ()</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Reference <a href="#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">MOLoad</a>.</p>


<p>Referenced by <a href="#a9463512c8c82f1d0c2a16f0cc271c6ab">MachineMemOperand</a> and <a href="#a4706e639e364501f6000985df1222c58">print</a>.</p>

</div>
</div>

### isNonTemporal() {#a5441fef0bf0e46bdc1f822a2b8545684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineMemOperand::isNonTemporal ()</td>
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



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Reference <a href="#aaa2020e47e35179234b9ea27d555b2dda8d09c51969b0954512ed65ee26551081">MONonTemporal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a8424c147a24cf4d707de1b7392597e48">llvm::RISCVInstrInfo::getInstSizeInBytes</a> and <a href="#a4706e639e364501f6000985df1222c58">print</a>.</p>

</div>
</div>

### isStore() {#aa8215fe1de88affa6954cfbb8fc65612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineMemOperand::isStore ()</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Reference <a href="#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">MOStore</a>.</p>


<p>Referenced by <a href="#a9463512c8c82f1d0c2a16f0cc271c6ab">MachineMemOperand</a> and <a href="#a4706e639e364501f6000985df1222c58">print</a>.</p>

</div>
</div>

### isUnordered() {#a55d6f8587efdb9efb8cb374f11fe4408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineMemOperand::isUnordered ()</td>
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

<p>Returns true if this memory operation doesn't have any ordering constraints other than normal aliasing.</p>


<p>Volatile and (ordered) atomic memory operations can't be reordered.</p>


<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>References <a href="#aaa45abfa63d76025a0e5b9a46e25dd8d">getSuccessOrdering</a>, <a href="#a1d07cda64e7150bb7f330057c41a2965">isVolatile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aabc3917d917c6247778c88107945d13b">llvm::MachineInstr::hasOrderedMemoryRef</a> and <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#a5de9f33a91663caa0f07d6f873514b65">llvm::GMemOperation::isUnordered</a>.</p>

</div>
</div>

### isVolatile() {#a1d07cda64e7150bb7f330057c41a2965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineMemOperand::isVolatile ()</td>
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



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Reference <a href="#aaa2020e47e35179234b9ea27d555b2dda796891d6ca349b671fce24b6d01d77a8">MOVolatile</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaimemalucombiner-cpp/#a3d8451ff05b58b604cb87a1623ef73b3">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a3ad30602142008d0355fc41c4f0626d0">isMemoryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a7ebf01237ea354d0baf26fae2f0a04a3">llvm::AMDGPURegisterBankInfo::isScalarLoadLegal</a>, <a href="#a55d6f8587efdb9efb8cb374f11fe4408">isUnordered</a>, <a href="/web-llvm/docs/api/classes/llvm/gmemoperation/#aabaa8933d3413bda663f85d8bc2086db">llvm::GMemOperation::isVolatile</a> and <a href="#a4706e639e364501f6000985df1222c58">print</a>.</p>

</div>
</div>

### refineAlignment() {#a6cf00cf755c1275eba246de7ebf7842d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineMemOperand::refineAlignment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * MMO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update this <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> to reflect the alignment of MMO, if it has a greater alignment.</p>


<p>This must only be used when the new alignment applies to all users of this <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a>.</p>


<p>Declaration at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>, definition at line 1128 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aeca5db48b31ea1b54d6fa2f357b11ed3">getBaseAlign</a>, <a href="#ab991bb1444579648a165d1b134a0854d">getFlags</a>, <a href="#a0ffa31699dee0349f9b9ae1d3ccb21f1">getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a0b0401973fc9567440717a5d32a8eb8d">llvm::LocationSize::hasValue</a> and <a href="#a8f79d1bbb6720756b5115dd20f499bfb">MachineMemOperand</a>.</p>

</div>
</div>

### setFlags() {#aadac6e7fd2d1087b6489906659bb8afb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineMemOperand::setFlags (<a href="#aaa2020e47e35179234b9ea27d555b2dd">Flags</a> f)</td>
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

<p>Bitwise OR the current flags with the given flags.</p>

<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpumarklastscratchload-cpp-/amdgpumarklastscratchload/#adb457e87e019538757ec91bec7a7e5f0">anonymous{AMDGPUMarkLastScratchLoad.cpp}::AMDGPUMarkLastScratchLoad::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a7d60a41c0d5e450f770042d3427928d0">llvm::RISCVDAGToDAGISel::Select</a>.</p>

</div>
</div>

### setOffset() {#a9b7acc8555a4466888d20106e3812548}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineMemOperand::setOffset (int64_t NewOffset)</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>

</div>
</div>

### setType() {#a0204ff8c047858d1fb330cafa728b51e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineMemOperand::setType (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NewTy)</td>
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

<p>Reset the tracked memory type.</p>

<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6c12dbad109a5d725ce01a9a8363f948">llvm::LegalizerHelper::bitcast</a>.</p>

</div>
</div>

### setValue() {#a606d73cbc9cc6210d626ec4b12c6c32e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineMemOperand::setValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewSV)</td>
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

<p>Change the SourceValue for this <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a>.</p>


<p>This should only be used when an object is being relocated and all references to it are being updated.</p>


<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>

</div>
</div>

### setValue() {#add89d597c6f35d6071ce2bbf8655d1ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineMemOperand::setValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> * NewSV)</td>
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



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AAInfo {#a7fcbb4fe8fb645ad9ce8d3c255d82b8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAMDNodes llvm::MachineMemOperand::AAInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>

</div>
</div>

### AtomicInfo {#aef4a4190e82c8a16bbf7cd07afa55915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineAtomicInfo llvm::MachineMemOperand::AtomicInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>

</div>
</div>

### BaseAlign {#a4485ae384604c9aab024dcb05c5d39da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MachineMemOperand::BaseAlign</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>

</div>
</div>

### FlagVals {#a462af0b273f9c65058b44fd23d44e100}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Flags llvm::MachineMemOperand::FlagVals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>

</div>
</div>

### MemoryType {#ac53f28dce8545babee163faa4225d232}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT llvm::MachineMemOperand::MemoryType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Track the memory type of the access.</p>


<p>An access size which is unknown or too large to be represented by <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> should use the invalid <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>.</p>


<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>

</div>
</div>

### PtrInfo {#a443bfbd40d5c21e1dd1b4b01360a6cb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachinePointerInfo llvm::MachineMemOperand::PtrInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>

</div>
</div>

### Ranges {#a4a973f8a68f753bd95de1344d250f883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MDNode* llvm::MachineMemOperand::Ranges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">MachineMemOperand.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
