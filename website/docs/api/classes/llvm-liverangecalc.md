---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/liverangecalc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LiveRangeCalc` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::LiveRangeCalc { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">llvm/CodeGen/LiveRangeCalc.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc">LiveIntervalCalc</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85afb5ab5edc2205dfdcdb8f5fad518d">LiveOutPair</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#a94b65b831ad8756f7d3a029a1e599f75">MachineDomTreeNode</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LiveOutPair - A value and the block that defined it. <a href="#a85afb5ab5edc2205dfdcdb8f5fad518d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8fd2372769502e3833805b30b621403">LiveOutMap</a> = <a href="/web-llvm/docs/api/classes/llvm/indexedmap">IndexedMap</a>&lt; LiveOutPair, <a href="/web-llvm/docs/api/structs/llvm/mbb2numberfunctor">MBB2NumberFunctor</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LiveOutMap - Map basic blocks to the value leaving the block. <a href="#aa8fd2372769502e3833805b30b621403">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac4eda35d4dd1470f532505eeeb8cf96">EntryInfoMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> *, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> to sets of blocks (represented by bit vectors) that in the live range are defined on entry and undefined on entry. <a href="#aac4eda35d4dd1470f532505eeeb8cf96">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae41cc4877968749dfa2b1fc3f1110a19">LiveRangeCalc</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65f0beed94a7dbdf8c8d7e2b46a0afa0">reset</a> (const MachineFunction *mf, SlotIndexes *SI, MachineDominatorTree *MDT, VNInfo::Allocator *VNIA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reset - Prepare caches for a new set of non-overlapping live ranges. <a href="#a65f0beed94a7dbdf8c8d7e2b46a0afa0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad445a5028efdf094173a202811f003e3">extend</a> (LiveRange &amp;LR, SlotIndex Use, unsigned PhysReg, ArrayRef&lt; SlotIndex &gt; Undefs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extend the live range of <span class="doxyComputerOutput">LR</span> to reach <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span>. <a href="#ad445a5028efdf094173a202811f003e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8e6fcd2d2e7e04fb1aa8fab71910f68">setLiveOutValue</a> (MachineBasicBlock *MBB, VNInfo *VNI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setLiveOutValue - Indicate that VNI is live out from MBB. <a href="#ae8e6fcd2d2e7e04fb1aa8fab71910f68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46981dd5d4bb3043b740ce285b7b4a95">addLiveInBlock</a> (LiveRange &amp;LR, MachineDomTreeNode *DomNode, SlotIndex Kill=SlotIndex())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addLiveInBlock - Add a block with an unknown live-in value. <a href="#a46981dd5d4bb3043b740ce285b7b4a95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5c960114840d1c6dddfbaa529ac633e">calculateValues</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>calculateValues - Calculate the value that will be live-in to each block added with addLiveInBlock. <a href="#ae5c960114840d1c6dddfbaa529ac633e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab032314f07277bf920fd315187ab9605">getMachineFunction</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some getters to expose in a read-only way some private fields to subclasses. <a href="#ab032314f07277bf920fd315187ab9605">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad09d2d2f0c1d47c7bc6eb04e33b5e51d">getRegInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11a21f58b3a7b8b7c401958cd3f7304f">getIndexes</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c8fd02f213ccc28812243ec1f36957c">getDomTree</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo/#aa750a7f159760b9c378d930deb6a9837">VNInfo::Allocator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60d4123651abf23e886661980d951ffc">getVNAlloc</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56cefbb66ed770ce1e6df7cbd1fa90d1">resetLiveOutMap</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset Map and Seen fields. <a href="#a56cefbb66ed770ce1e6df7cbd1fa90d1">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecb04af202c3560e42fad62a5506f763">isDefOnEntry</a> (LiveRange &amp;LR, ArrayRef&lt; SlotIndex &gt; Undefs, MachineBasicBlock &amp;MBB, BitVector &amp;DefOnEntry, BitVector &amp;UndefOnEntry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the entry to block <span class="doxyComputerOutput">MBB</span> can be reached by any of the defs in <span class="doxyComputerOutput">LR</span>. <a href="#aecb04af202c3560e42fad62a5506f763">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae243990ea455fd5ec0c3c70785a17228">findReachingDefs</a> (LiveRange &amp;LR, MachineBasicBlock &amp;UseMBB, SlotIndex Use, unsigned PhysReg, ArrayRef&lt; SlotIndex &gt; Undefs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the set of defs that can reach <span class="doxyComputerOutput">Kill</span>. <a href="#ae243990ea455fd5ec0c3c70785a17228">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8724ca9a385ad023d80339599cc037df">updateSSA</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>updateSSA - Compute the values that will be live in to all requested blocks in LiveIn. <a href="#a8724ca9a385ad023d80339599cc037df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabd755af5c29164f99a73388406d9e8a">updateFromLiveIns</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfer information from the LiveIn vector to the live ranges and update the given <span class="doxyComputerOutput">LiveOuts</span>. <a href="#aabd755af5c29164f99a73388406d9e8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e21e9bb116a8e83265610c24217afc8">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e7f801341553dc1123d8793e6687697">MRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f9a3a7dda1749ddcaf3c9f3ab9c9c73">Indexes</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeae2aad504a71d29ff10f6527be73e97">DomTree</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo/#aa750a7f159760b9c378d930deb6a9837">VNInfo::Allocator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1e119e1a29c2047e295b1e66153cf3e">Alloc</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b21a9bc676c95be138caf3757ac6d59">Seen</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bit vector of active entries in LiveOut, also used as a visited set by findReachingDefs. <a href="#a5b21a9bc676c95be138caf3757ac6d59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">EntryInfoMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4af75b162ef660fbe3a08262c84c7825">EntryInfos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexedmap">LiveOutMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e5608bb9852fb86990af4dd05842128">Map</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map each basic block where a live range is live out to the live-out value and its defining block. <a href="#a9e5608bb9852fb86990af4dd05842128">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; LiveInBlock, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb6fcf43c4c5e0e2778ce03512250a3">LiveIn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LiveIn - Work list of blocks where the live-in value has yet to be determined. <a href="#abbb6fcf43c4c5e0e2778ce03512250a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#acc1c483f4b4ee2f17bb6643a3b353609">LLVM_ATTRIBUTE_UNUSED</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13c4005ea769c09d88be76fa40744e7e">isJointlyDominated</a> (const MachineBasicBlock *MBB, ArrayRef&lt; SlotIndex &gt; Defs, const SlotIndexes &amp;Indexes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A diagnostic function to check if the end of the block <span class="doxyComputerOutput">MBB</span> is jointly dominated by the blocks corresponding to the slot indices in <span class="doxyComputerOutput">Defs</span>. <a href="#a13c4005ea769c09d88be76fa40744e7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### EntryInfoMap {#aac4eda35d4dd1470f532505eeeb8cf96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveRangeCalc::EntryInfoMap =  DenseMap&lt;LiveRange *, std::pair&lt;BitVector, BitVector&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> to sets of blocks (represented by bit vectors) that in the live range are defined on entry and undefined on entry.</p>


<p>A block is defined on entry if there is a path from at least one of the defs in the live range to the entry of the block, and conversely, a block is undefined on entry, if there is no such path (i.e. no definition reaches the entry of the block). A single <a href="/web-llvm/docs/api/classes/llvm/liverangecalc">LiveRangeCalc</a> object is used to track live-out information for multiple registers in live range splitting (which is ok, since the live ranges of these registers do not overlap), but the defined/undefined information must be kept separate for each individual range. By convention, EntryInfoMap[&amp;LR] = { Defined, Undefined }.</p>


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>

</div>
</div>

### LiveOutMap {#aa8fd2372769502e3833805b30b621403}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveRangeCalc::LiveOutMap =  IndexedMap&lt;LiveOutPair, MBB2NumberFunctor&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LiveOutMap - Map basic blocks to the value leaving the block.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>

</div>
</div>

### LiveOutPair {#a85afb5ab5edc2205dfdcdb8f5fad518d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveRangeCalc::LiveOutPair =  std::pair&lt;VNInfo *, MachineDomTreeNode *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LiveOutPair - A value and the block that defined it.</p>


<p>The domtree node is redundant, it can be computed as: MDT[Indexes.getMBBFromIndex(VNI-&gt;def)].</p>


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LiveRangeCalc() {#ae41cc4877968749dfa2b1fc3f1110a19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveRangeCalc::LiveRangeCalc ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addLiveInBlock() {#a46981dd5d4bb3043b740ce285b7b4a95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveRangeCalc::addLiveInBlock (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/namespaces/llvm/#a94b65b831ad8756f7d3a029a1e599f75">MachineDomTreeNode</a> * DomNode, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Kill=<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a>())</td>
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

<p>addLiveInBlock - Add a block with an unknown live-in value.</p>


<p>This function can only be called once per basic block. Once the live-in value has been determined, <a href="#ae5c960114840d1c6dddfbaa529ac633e">calculateValues()</a> will add liveness to LI.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">LR</td>
<td class="doxyParamItemDescription"><p>The live range that is live-in to the block.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DomNode</td>
<td class="doxyParamItemDescription"><p>The domtree node for the block.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Kill</td>
<td class="doxyParamItemDescription"><p>Index in block where LI is killed. If the value is live-through, set Kill = SLotIndex() and also call setLiveOutValue(MBB, 0).</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>

</div>
</div>

### calculateValues() {#ae5c960114840d1c6dddfbaa529ac633e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRangeCalc::calculateValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>calculateValues - Calculate the value that will be live-in to each block added with addLiveInBlock.</p>


<p>Add PHI-def values as needed to preserve SSA form. Add liveness to all live-in blocks up to the Kill point, or the whole block for live-through blocks.</p>


<p>Every predecessor of a live-in block must have been given a value with setLiveOutValue, the value may be null for live-trough blocks.</p>


<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangecalc-cpp">LiveRangeCalc.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#ad445a5028efdf094173a202811f003e3">extend</a>.</p>

</div>
</div>

### extend() {#ad445a5028efdf094173a202811f003e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRangeCalc::extend (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Use, unsigned PhysReg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt; Undefs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extend the live range of <span class="doxyComputerOutput">LR</span> to reach <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span>.</p>


<p>The existing values in <span class="doxyComputerOutput">LR</span> must be live so they jointly dominate <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span>. If <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span> is not dominated by a single existing value, PHI-defs are inserted as required to preserve SSA form.</p>


<p>PhysReg, when set, is used to verify live-in lists on basic blocks.</p>


<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangecalc-cpp">LiveRangeCalc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae5c960114840d1c6dddfbaa529ac633e">calculateValues</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#a81f9d3d0b958e57c0c0f24982230885d">llvm::LiveRange::extendInBlock</a>.</p>

</div>
</div>

### reset() {#a65f0beed94a7dbdf8c8d7e2b46a0afa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRangeCalc::reset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * mf, <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> * SI, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * MDT, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#aa750a7f159760b9c378d930deb6a9837">VNInfo::Allocator</a> * VNIA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>reset - Prepare caches for a new set of non-overlapping live ranges.</p>


<p>The caches must be reset before attempting calculations with a live range that may overlap a previously computed live range, and before the first live range in a function. If live ranges are not known to be non-overlapping, call reset before each.</p>


<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangecalc-cpp">LiveRangeCalc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a> and <a href="#a56cefbb66ed770ce1e6df7cbd1fa90d1">resetLiveOutMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#ad67d6b7f9f91a2d5852b0f9aebfe542a">llvm::LiveIntervalCalc::calculate</a>.</p>

</div>
</div>

### setLiveOutValue() {#ae8e6fcd2d2e7e04fb1aa8fab71910f68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveRangeCalc::setLiveOutValue (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * VNI)</td>
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

<p>setLiveOutValue - Indicate that VNI is live out from MBB.</p>


<p>The <a href="#ae5c960114840d1c6dddfbaa529ac633e">calculateValues()</a> function will not add liveness for MBB, the caller should take care of that.</p>


<p>VNI may be null only if MBB is a live-through block also passed to <a href="#a46981dd5d4bb3043b740ce285b7b4a95">addLiveInBlock()</a>.</p>


<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getDomTree() {#a3c8fd02f213ccc28812243ec1f36957c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineDominatorTree * llvm::LiveRangeCalc::getDomTree ()</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#ad67d6b7f9f91a2d5852b0f9aebfe542a">llvm::LiveIntervalCalc::calculate</a>.</p>

</div>
</div>

### getIndexes() {#a11a21f58b3a7b8b7c401958cd3f7304f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndexes * llvm::LiveRangeCalc::getIndexes ()</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#ad67d6b7f9f91a2d5852b0f9aebfe542a">llvm::LiveIntervalCalc::calculate</a> and <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#a1c36b75f4a0dac1a833a459617f03c76">llvm::LiveIntervalCalc::createDeadDefs</a>.</p>

</div>
</div>

### getMachineFunction() {#ab032314f07277bf920fd315187ab9605}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction * llvm::LiveRangeCalc::getMachineFunction ()</td>
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

<p>Some getters to expose in a read-only way some private fields to subclasses.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#ad67d6b7f9f91a2d5852b0f9aebfe542a">llvm::LiveIntervalCalc::calculate</a>.</p>

</div>
</div>

### getRegInfo() {#ad09d2d2f0c1d47c7bc6eb04e33b5e51d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineRegisterInfo * llvm::LiveRangeCalc::getRegInfo ()</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#ad67d6b7f9f91a2d5852b0f9aebfe542a">llvm::LiveIntervalCalc::calculate</a> and <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#a1c36b75f4a0dac1a833a459617f03c76">llvm::LiveIntervalCalc::createDeadDefs</a>.</p>

</div>
</div>

### getVNAlloc() {#a60d4123651abf23e886661980d951ffc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo::Allocator * llvm::LiveRangeCalc::getVNAlloc ()</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#ad67d6b7f9f91a2d5852b0f9aebfe542a">llvm::LiveIntervalCalc::calculate</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#af5198110c0058e3d60524eecf500ee51">llvm::LiveIntervalCalc::constructMainRangeFromSubranges</a> and <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#a1c36b75f4a0dac1a833a459617f03c76">llvm::LiveIntervalCalc::createDeadDefs</a>.</p>

</div>
</div>

### resetLiveOutMap() {#a56cefbb66ed770ce1e6df7cbd1fa90d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRangeCalc::resetLiveOutMap ()</td>
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

<p>Reset Map and Seen fields.</p>

<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangecalc-cpp">LiveRangeCalc.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#ad67d6b7f9f91a2d5852b0f9aebfe542a">llvm::LiveIntervalCalc::calculate</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#af5198110c0058e3d60524eecf500ee51">llvm::LiveIntervalCalc::constructMainRangeFromSubranges</a> and <a href="#a65f0beed94a7dbdf8c8d7e2b46a0afa0">reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### findReachingDefs() {#ae243990ea455fd5ec0c3c70785a17228}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRangeCalc::findReachingDefs (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; UseMBB, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Use, unsigned PhysReg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt; Undefs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the set of defs that can reach <span class="doxyComputerOutput">Kill</span>.</p>


<p><span class="doxyComputerOutput">Kill</span> must belong to <span class="doxyComputerOutput">UseMBB</span>.</p>


<p>If exactly one def can reach <span class="doxyComputerOutput">UseMBB</span>, and the def dominates <span class="doxyComputerOutput">Kill</span>, all paths from the def to <span class="doxyComputerOutput">UseMBB</span> are added to <span class="doxyComputerOutput">LR</span>, and the function returns true.</p>


<p>If multiple values can reach <span class="doxyComputerOutput">UseMBB</span>, the blocks that need <span class="doxyComputerOutput">LR</span> to be live in are added to the LiveIn array, and the function returns false.</p>


<p>The array <span class="doxyComputerOutput">Undef</span> provides the locations where the range <span class="doxyComputerOutput">LR</span> becomes undefined by &lt;def,read-undef&gt; operands on other subranges. If <span class="doxyComputerOutput">Undef</span> is non-empty and <span class="doxyComputerOutput">Kill</span> is jointly dominated only by the entries of <span class="doxyComputerOutput">Undef</span>, the function returns false.</p>


<p>PhysReg, when set, is used to verify live-in lists on basic blocks.</p>


<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>, definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangecalc-cpp">LiveRangeCalc.cpp</a>.</p>

</div>
</div>

### isDefOnEntry() {#aecb04af202c3560e42fad62a5506f763}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRangeCalc::isDefOnEntry (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt; Undefs, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; DefOnEntry, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; UndefOnEntry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the entry to block <span class="doxyComputerOutput">MBB</span> can be reached by any of the defs in <span class="doxyComputerOutput">LR</span>.</p>


<p>Return true if none of the defs reach the entry to <span class="doxyComputerOutput">MBB</span>.</p>


<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangecalc-cpp">LiveRangeCalc.cpp</a>.</p>

</div>
</div>

### updateFromLiveIns() {#aabd755af5c29164f99a73388406d9e8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRangeCalc::updateFromLiveIns ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transfer information from the LiveIn vector to the live ranges and update the given <span class="doxyComputerOutput">LiveOuts</span>.</p>

<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangecalc-cpp">LiveRangeCalc.cpp</a>.</p>

</div>
</div>

### updateSSA() {#a8724ca9a385ad023d80339599cc037df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRangeCalc::updateSSA ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>updateSSA - Compute the values that will be live in to all requested blocks in LiveIn.</p>


<p>Create PHI-def values as required to preserve SSA form.</p>


<p>Every live-in block must be jointly dominated by the added live-out blocks. No values are read from the live ranges.</p>


<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>, definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangecalc-cpp">LiveRangeCalc.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Alloc {#aa1e119e1a29c2047e295b1e66153cf3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo::Allocator* llvm::LiveRangeCalc::Alloc = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>

</div>
</div>

### DomTree {#aeae2aad504a71d29ff10f6527be73e97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineDominatorTree* llvm::LiveRangeCalc::DomTree = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>

</div>
</div>

### EntryInfos {#a4af75b162ef660fbe3a08262c84c7825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EntryInfoMap llvm::LiveRangeCalc::EntryInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>

</div>
</div>

### Indexes {#a9f9a3a7dda1749ddcaf3c9f3ab9c9c73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndexes* llvm::LiveRangeCalc::Indexes = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>

</div>
</div>

### LiveIn {#abbb6fcf43c4c5e0e2778ce03512250a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;LiveInBlock, 16&gt; llvm::LiveRangeCalc::LiveIn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LiveIn - Work list of blocks where the live-in value has yet to be determined.</p>


<p>This list is typically computed by findReachingDefs() and used as a work list by updateSSA(). The low-level interface may also be used to add entries directly.</p>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>

</div>
</div>

### Map {#a9e5608bb9852fb86990af4dd05842128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveOutMap llvm::LiveRangeCalc::Map</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map each basic block where a live range is live out to the live-out value and its defining block.</p>


<p>For every basic block, MBB, one of these conditions shall be true:</p>


<ol class="doxyList" type="1">
<li>!Seen.count(MBB-&gt;getNumber()) Blocks without a Seen bit are ignored.</li>
<li>LiveOut[MBB].second.getNode() == MBB The live-out value is defined in MBB.</li>
<li>forall P in preds(MBB): LiveOut[P] == LiveOut[MBB] The live-out value passses through MBB. All predecessors must carry the same value.</li>
</ol>

<p>The domtree node may be null, it can be computed.</p>


<p>The map can be shared by multiple live ranges as long as no two are live-out of the same block.</p>


<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>

</div>
</div>

### MF {#a1e21e9bb116a8e83265610c24217afc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction* llvm::LiveRangeCalc::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>

</div>
</div>

### MRI {#a9e7f801341553dc1123d8793e6687697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineRegisterInfo* llvm::LiveRangeCalc::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>

</div>
</div>

### Seen {#a5b21a9bc676c95be138caf3757ac6d59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::LiveRangeCalc::Seen</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Bit vector of active entries in LiveOut, also used as a visited set by findReachingDefs.</p>


<p>One entry per basic block, indexed by block number. This is kept as a separate bit vector because it can be cleared quickly when switching live ranges.</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isJointlyDominated() {#a13c4005ea769c09d88be76fa40744e7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRangeCalc::isJointlyDominated (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt; Defs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> &amp; Indexes)</td>
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

<p>A diagnostic function to check if the end of the block <span class="doxyComputerOutput">MBB</span> is jointly dominated by the blocks corresponding to the slot indices in <span class="doxyComputerOutput">Defs</span>.</p>


<p>This function is mainly for use in self-verification checks.</p>


<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a>, definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangecalc-cpp">LiveRangeCalc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a> and <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangecalc-h">LiveRangeCalc.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangecalc-cpp">LiveRangeCalc.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
