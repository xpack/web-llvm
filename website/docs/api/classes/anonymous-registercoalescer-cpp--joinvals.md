---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-registercoalescer-cpp-/joinvals
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `JoinVals` Class

<p>Track information about values in a single virtual register about to be joined. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{RegisterCoalescer.cpp}::JoinVals { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ConflictResolution { <a href="#a7caa969b35ea838dd4137cd213b8909c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Conflict resolution for overlapping values. <a href="#a7caa969b35ea838dd4137cd213b8909c">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bdb429abc9cabb96a3c3df03e53e2ea">JoinVals</a> (LiveRange &amp;LR, Register Reg, unsigned SubIdx, LaneBitmask LaneMask, SmallVectorImpl&lt; VNInfo * &gt; &amp;newVNInfo, const CoalescerPair &amp;cp, LiveIntervals *lis, const TargetRegisterInfo *TRI, bool SubRangeJoin, bool TrackSubRegLiveness)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a8768b37f48763192c2530de53f97b0">mapValues</a> (JoinVals &amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze defs in LR and compute a value mapping in NewVNInfo. <a href="#a5a8768b37f48763192c2530de53f97b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add7c3bdd8428904f63f53569807b8df6">resolveConflicts</a> (JoinVals &amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to resolve conflicts that require all values to be mapped. <a href="#add7c3bdd8428904f63f53569807b8df6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3fe888e13e687c808085c0cfba933c3">pruneValues</a> (JoinVals &amp;Other, SmallVectorImpl&lt; SlotIndex &gt; &amp;EndPoints, bool changeInstrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prune the live range of values in Other.LR where they would conflict with CR_Replace values in LR. <a href="#aa3fe888e13e687c808085c0cfba933c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3730642a8860945b6ca5ca954a238592">pruneSubRegValues</a> (LiveInterval &amp;LI, LaneBitmask &amp;ShrinkMask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes subranges starting at copies that get removed. <a href="#a3730642a8860945b6ca5ca954a238592">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b3c2e77ef89dfcb6bc2129edc827264">pruneMainSegments</a> (LiveInterval &amp;LI, bool &amp;ShrinkMainRange)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pruning values in subranges can lead to removing segments in these subranges started by IMPLICIT_DEFs. <a href="#a1b3c2e77ef89dfcb6bc2129edc827264">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1659a196eabbdd653b9a5d529ccfcb6e">eraseInstrs</a> (SmallPtrSetImpl&lt; MachineInstr * &gt; &amp;ErasedInstrs, SmallVectorImpl&lt; Register &gt; &amp;ShrinkRegs, LiveInterval *LI=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase any machine instructions that have been coalesced away. <a href="#a1659a196eabbdd653b9a5d529ccfcb6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8546f9a7fa0a18cfe46dc20582dcbed2">removeImplicitDefs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove liverange defs at places where implicit defs will be removed. <a href="#a8546f9a7fa0a18cfe46dc20582dcbed2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e401cb75317feb575c5ab9f844c1da2">getAssignments</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the value assignments suitable for passing to LiveInterval::join. <a href="#a6e401cb75317feb575c5ab9f844c1da2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7caa969b35ea838dd4137cd213b8909c">ConflictResolution</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2073d38573fd65fc21a3b6a205a025d4">getResolution</a> (unsigned Num) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the conflict resolution for a value number. <a href="#a2073d38573fd65fc21a3b6a205a025d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b601b590cadfef81704df7fedb69624">computeWriteLanes</a> (const MachineInstr *DefMI, bool &amp;Redef) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the bitmask of lanes actually written by DefMI. <a href="#a3b601b590cadfef81704df7fedb69624">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52db6b6bd97b58d14370627d4df18c10">followCopyChain</a> (const VNInfo *VNI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the ultimate value that VNI was copied from. <a href="#a52db6b6bd97b58d14370627d4df18c10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f909c08212c6a23345731f266a416b6">valuesIdentical</a> (VNInfo *Value0, VNInfo *Value1, const JoinVals &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7caa969b35ea838dd4137cd213b8909c">ConflictResolution</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f38448e774565f2509e150d077720bc">analyzeValue</a> (unsigned ValNo, JoinVals &amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze ValNo in this live range, and set all fields of Vals[ValNo]. <a href="#a9f38448e774565f2509e150d077720bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae30a0b4535b2f92da284051c9ec5f9ae">computeAssignment</a> (unsigned ValNo, JoinVals &amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the value assignment for ValNo in RI. <a href="#ae30a0b4535b2f92da284051c9ec5f9ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ca697afdb307e5d8509a65dd7419330">taintExtent</a> (unsigned ValNo, LaneBitmask TaintedLanes, JoinVals &amp;Other, SmallVectorImpl&lt; std::pair&lt; SlotIndex, LaneBitmask &gt; &gt; &amp;TaintExtent)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assuming ValNo is going to clobber some valid lanes in Other.LR, compute the extent of the tainted lanes in the block. <a href="#a2ca697afdb307e5d8509a65dd7419330">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed477e65dbeca025bf7fe2569c6ae56a">usesLanes</a> (const MachineInstr &amp;MI, Register, unsigned, LaneBitmask) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if MI uses any of the given Lanes from Reg. <a href="#aed477e65dbeca025bf7fe2569c6ae56a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcd0b50c56e4d0c0fc61d306d86e9739">isPrunedValue</a> (unsigned ValNo, JoinVals &amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if ValNo is a copy of a value number in LR or Other.LR that will be pruned: <a href="#afcd0b50c56e4d0c0fc61d306d86e9739">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87036fce73f22c86c223b4bd7760cb6b">LR</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Live range we work on. <a href="#a87036fce73f22c86c223b4bd7760cb6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6bf2b256fbb6a03d7a2f05a6ad0a1f4">Reg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>(Main) register we work on. <a href="#ad6bf2b256fbb6a03d7a2f05a6ad0a1f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00b16137289c18d9b40835d65fcb0ccb">SubIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reg (and therefore the values in this liverange) will end up as subregister SubIdx in the coalesced register. <a href="#a00b16137289c18d9b40835d65fcb0ccb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cae4b22a19d4de03a2bd5a3f9f17867">LaneMask</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The LaneMask that this liverange will occupy the coalesced register. <a href="#a8cae4b22a19d4de03a2bd5a3f9f17867">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d3cea41a4b61ccea063ee5a717b8867">SubRangeJoin</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is true when joining sub register ranges, false when joining main ranges. <a href="#a8d3cea41a4b61ccea063ee5a717b8867">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cc9c5a4fe37b635831c4b622b5ae350">TrackSubRegLiveness</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the current <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> tracks subregister liveness. <a href="#a5cc9c5a4fe37b635831c4b622b5ae350">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adca2cec60f0ea667907cbcb02676b5c5">NewVNInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Values that will be present in the final live range. <a href="#adca2cec60f0ea667907cbcb02676b5c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/coalescerpair">CoalescerPair</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2acb84b6d047282d222a27ee05d0a73">CP</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa0132b120c5860a4450968879f28b91">LIS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e72f48daa6146407f9cec4837acfbf8">Indexes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa624e808af5f76a7545541a1702b6a0d">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51ac22cac123d277c544dc93ecca618d">Assignments</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> number assignments. <a href="#a51ac22cac123d277c544dc93ecca618d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; Val, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd0156cc106a925e972fa89e2f4c5e66">Vals</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>One entry per value number in LI. <a href="#acd0156cc106a925e972fa89e2f4c5e66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Track information about values in a single virtual register about to be joined.</p>


<p>Objects of this class are always created in pairs - one for each side of the <a href="/web-llvm/docs/api/classes/llvm/coalescerpair">CoalescerPair</a> (or one for each lane of a side of the coalescer pair)</p>


<p>Definition at line 2458 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ConflictResolution {#a7caa969b35ea838dd4137cd213b8909c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{RegisterCoalescer.cpp}::JoinVals::ConflictResolution </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Conflict resolution for overlapping values.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CR_Keep<a id="a7caa969b35ea838dd4137cd213b8909cae68dda580bbff218085b3f189b9e7c73"></a></td>
<td class="doxyEnumItemDescription">No overlap, simply keep this value</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CR_Erase<a id="a7caa969b35ea838dd4137cd213b8909ca8a7b9f2adcff0b230512d2547f5fd44d"></a></td>
<td class="doxyEnumItemDescription">Merge this value into OtherVNI and erase the defining instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CR_Merge<a id="a7caa969b35ea838dd4137cd213b8909ca58561957307c3721aad71b897e448647"></a></td>
<td class="doxyEnumItemDescription">Merge this value into OtherVNI but keep the defining instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CR_Replace<a id="a7caa969b35ea838dd4137cd213b8909ca191f458a9d415a178a901a75baa4bd0e"></a></td>
<td class="doxyEnumItemDescription">Keep this value, and have it replace OtherVNI where possible</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CR_Unresolved<a id="a7caa969b35ea838dd4137cd213b8909cabd7e0ab4ddda4ab7abfdc4077f6d8a50"></a></td>
<td class="doxyEnumItemDescription">Unresolved conflict. Visit later when all values have been mapped</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CR_Impossible<a id="a7caa969b35ea838dd4137cd213b8909cadf133404fe2559cd68f16253fac30869"></a></td>
<td class="doxyEnumItemDescription">Unresolvable conflict. Abort the join</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 2495 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### JoinVals() {#a5bdb429abc9cabb96a3c3df03e53e2ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RegisterCoalescer.cpp}::JoinVals::JoinVals (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, unsigned SubIdx, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * &gt; &amp; newVNInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/coalescerpair">CoalescerPair</a> &amp; cp, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * lis, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, bool SubRangeJoin, bool TrackSubRegLiveness)</td>
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



<p>Definition at line 2643 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>Referenced by <a href="#a5a8768b37f48763192c2530de53f97b0">mapValues</a>, <a href="#aa3fe888e13e687c808085c0cfba933c3">pruneValues</a> and <a href="#add7c3bdd8428904f63f53569807b8df6">resolveConflicts</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### eraseInstrs() {#a1659a196eabbdd653b9a5d529ccfcb6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void JoinVals::eraseInstrs (<a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; ErasedInstrs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; ShrinkRegs, <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> * LI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Erase any machine instructions that have been coalesced away.</p>


<p>Add erased instructions to ErasedInstrs. Add foreign virtual registers to ShrinkRegs if their live range ended at the erased instrs.</p>


<p>Definition at line 2685 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7caa969b35ea838dd4137cd213b8909ca8a7b9f2adcff0b230512d2547f5fd44d">CR_Erase</a>, <a href="#a7caa969b35ea838dd4137cd213b8909cae68dda580bbff218085b3f189b9e7c73">CR_Keep</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a757fd6afba0f531db70e78e057d147c6">llvm::LiveRange::end</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#afeb00b9049a2391c990df15692caef63">llvm::LiveRange::find</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a1c198291d6ee66150b76633cda8a1749">llvm::LiveInterval::hasSubRanges</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a5bcdd85778add4287db384472cde8acd">llvm::SlotIndex::isValid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#a81775e4a3dbcbc42d828c3e4becd9190">llvm::VNInfo::markUnused</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9545a896d571165e9f43cf4b29a6d072">llvm::LiveInterval::subranges</a>.</p>

</div>
</div>

### getAssignments() {#a6e401cb75317feb575c5ab9f844c1da2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int * anonymous{RegisterCoalescer.cpp}::JoinVals::getAssignments ()</td>
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

<p>Get the value assignments suitable for passing to LiveInterval::join.</p>

<p>Definition at line 2693 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### getResolution() {#a2073d38573fd65fc21a3b6a205a025d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConflictResolution anonymous{RegisterCoalescer.cpp}::JoinVals::getResolution (unsigned Num)</td>
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

<p>Get the conflict resolution for a value number.</p>

<p>Definition at line 2696 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### mapValues() {#a5a8768b37f48763192c2530de53f97b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool JoinVals::mapValues (<a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals">JoinVals</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze defs in LR and compute a value mapping in NewVNInfo.</p>


<p>Returns false if any conflicts were impossible to resolve.</p>


<p>Definition at line 2655 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>References <a href="#a7caa969b35ea838dd4137cd213b8909cadf133404fe2559cd68f16253fac30869">CR_Impossible</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a5bdb429abc9cabb96a3c3df03e53e2ea">JoinVals</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>.</p>

</div>
</div>

### pruneMainSegments() {#a1b3c2e77ef89dfcb6bc2129edc827264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void JoinVals::pruneMainSegments (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI, bool &amp; ShrinkMainRange)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pruning values in subranges can lead to removing segments in these subranges started by IMPLICIT_DEFs.</p>


<p>The corresponding segments in the main range also need to be removed. This function will mark the corresponding values in the main range as pruned, so that eraseInstrs can do the final cleanup. The parameter <span class="doxyComputerOutput">LI</span> must be the interval whose main range is the live range LR.</p>


<p>Definition at line 2679 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7caa969b35ea838dd4137cd213b8909cae68dda580bbff218085b3f189b9e7c73">CR_Keep</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#a557a8b6ef8191908ae0c534f76b9f782">isDefInSubRange</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae72fbcf51be7574c84817cde814df07e">llvm::VNInfo::isPHIDef</a> and <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ab72366fd538f240cbb53dac39368cdfc">llvm::VNInfo::isUnused</a>.</p>

</div>
</div>

### pruneSubRegValues() {#a3730642a8860945b6ca5ca954a238592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void JoinVals::pruneSubRegValues (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> &amp; ShrinkMask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Removes subranges starting at copies that get removed.</p>


<p>Consider the following situation when coalescing the copy between %31 and %45 at 800.</p>


<p>This sometimes happens when undefined subranges are copied around. These ranges contain no useful information and can be removed.</p>


<p>(The vertical lines represent live range segments.)</p>



<pre><code>                         Main range         Subrange 0004 (sub2)
                         %31    %45           %31    %45
</code></pre>


<p>544 %45 = COPY %28 + + | v1 | v1 560B bb.1: + + 624 = %45.sub2 | v2 | v2 800 %31 = COPY %45 + + + + | v0 | v0 816 %31.sub1 = ... + | 880 %30 = COPY %31 | v1 + 928 %45 = COPY %30 | + + | | v0 | v0 &lt;–+ 992B ; backedge -&gt; bb.1 | + + | 1040 = %31.sub0 + | This value must remain live-out!</p>


<p>Assuming that %31 is coalesced into %45, the copy at 928 becomes redundant, since it copies the value from %45 back into it. The conflict resolution for the main range determines that %45.v0 is to be erased, which is ok since %31.v1 is identical to it. The problem happens with the subrange for sub2: it has to be live on exit from the block, but since 928 was actually a point of definition of %45.sub2, %45.sub2 was not live immediately prior to that definition. As a result, when 928 was erased, the value v0 for %45.sub2 was pruned in pruneSubRegValues. Consequently, an IMPLICIT_DEF was inserted as a "backedge" definition for %45.sub2, providing an incorrect value to the use at 624.</p>


<p>Since the main-range values %31.v1 and %45.v0 were proved to be identical, the corresponding values in subranges must also be the same. A redundant copy is removed because it's not needed, and not because it copied an undefined value, so any liveness that originated from that copy cannot disappear. When pruning a value that started at the removed copy, the corresponding identical value must be extended to replace it.</p>


<p>Definition at line 2670 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>References <a href="#a7caa969b35ea838dd4137cd213b8909ca8a7b9f2adcff0b230512d2547f5fd44d">CR_Erase</a>, <a href="#a7caa969b35ea838dd4137cd213b8909cae68dda580bbff218085b3f189b9e7c73">CR_Keep</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#a643bfbd7372690fe71cc63171a3219bf">isLiveThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae72fbcf51be7574c84817cde814df07e">llvm::VNInfo::isPHIDef</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#a81775e4a3dbcbc42d828c3e4becd9190">llvm::VNInfo::markUnused</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e30e18d6f7ebd943eaf8ebc3a2b2930">llvm::PrintLaneMask</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a0aac3ef1eadaa206a70b767730ef3c5b">llvm::LiveInterval::removeEmptySubRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9545a896d571165e9f43cf4b29a6d072">llvm::LiveInterval::subranges</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a527e4a21e13a8455c75eb0d811701066">llvm::LiveQueryResult::valueIn</a>, <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a8c9627b7e8bbfa4fbd02f6644907147f">llvm::LiveQueryResult::valueOut</a> and <a href="/web-llvm/docs/api/classes/llvm/livequeryresult/#a001d69b0b75e2841cc109cbe8729ba87">llvm::LiveQueryResult::valueOutOrDead</a>.</p>

</div>
</div>

### pruneValues() {#aa3fe888e13e687c808085c0cfba933c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void JoinVals::pruneValues (<a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals">JoinVals</a> &amp; Other, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt; &amp; EndPoints, bool changeInstrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prune the live range of values in Other.LR where they would conflict with CR_Replace values in LR.</p>


<p>Collect end points for restoring the live range after joining.</p>


<p>Definition at line 2664 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>References <a href="#a7caa969b35ea838dd4137cd213b8909ca8a7b9f2adcff0b230512d2547f5fd44d">CR_Erase</a>, <a href="#a7caa969b35ea838dd4137cd213b8909cadf133404fe2559cd68f16253fac30869">CR_Impossible</a>, <a href="#a7caa969b35ea838dd4137cd213b8909cae68dda580bbff218085b3f189b9e7c73">CR_Keep</a>, <a href="#a7caa969b35ea838dd4137cd213b8909ca58561957307c3721aad71b897e448647">CR_Merge</a>, <a href="#a7caa969b35ea838dd4137cd213b8909ca191f458a9d415a178a901a75baa4bd0e">CR_Replace</a>, <a href="#a7caa969b35ea838dd4137cd213b8909cabd7e0ab4ddda4ab7abfdc4077f6d8a50">CR_Unresolved</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a1255befbcd6e034394681b1bcd3529ff">llvm::MachineOperand::isUndef</a>, <a href="#a5bdb429abc9cabb96a3c3df03e53e2ea">JoinVals</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a61a42c85bd86c6ca4554e27d33c3f798">llvm::MachineOperand::setIsDead</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab979122f21b7fa46d3d2d9b21983068b">llvm::MachineOperand::setIsUndef</a>.</p>

</div>
</div>

### removeImplicitDefs() {#a8546f9a7fa0a18cfe46dc20582dcbed2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void JoinVals::removeImplicitDefs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove liverange defs at places where implicit defs will be removed.</p>

<p>Definition at line 2690 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>References <a href="#a7caa969b35ea838dd4137cd213b8909cae68dda580bbff218085b3f189b9e7c73">CR_Keep</a> and <a href="/web-llvm/docs/api/classes/llvm/vninfo/#a81775e4a3dbcbc42d828c3e4becd9190">llvm::VNInfo::markUnused</a>.</p>

</div>
</div>

### resolveConflicts() {#add7c3bdd8428904f63f53569807b8df6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool JoinVals::resolveConflicts (<a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals">JoinVals</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to resolve conflicts that require all values to be mapped.</p>


<p>Returns false if any conflicts were impossible to resolve.</p>


<p>Definition at line 2659 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7caa969b35ea838dd4137cd213b8909cadf133404fe2559cd68f16253fac30869">CR_Impossible</a>, <a href="#a7caa969b35ea838dd4137cd213b8909ca191f458a9d415a178a901a75baa4bd0e">CR_Replace</a>, <a href="#a7caa969b35ea838dd4137cd213b8909cabd7e0ab4ddda4ab7abfdc4077f6d8a50">CR_Unresolved</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a58dc840fc84420b7f0b773794b8101c1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a305ac7d0553ef0ce21d461f5eabfe71c">llvm::SlotIndex::isEarlyClobber</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae72fbcf51be7574c84817cde814df07e">llvm::VNInfo::isPHIDef</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a0b73244049319d841fd11a238f35b5d1">llvm::SlotIndex::isSameInstr</a>, <a href="#a5bdb429abc9cabb96a3c3df03e53e2ea">JoinVals</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e30e18d6f7ebd943eaf8ebc3a2b2930">llvm::PrintLaneMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### analyzeValue() {#a9f38448e774565f2509e150d077720bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JoinVals::ConflictResolution JoinVals::analyzeValue (unsigned ValNo, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals">JoinVals</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze ValNo in this live range, and set all fields of Vals[ValNo].</p>


<p>Return a conflict resolution when possible, but leave the hard cases as CR_Unresolved. Recursively calls computeAssignment() on this and Other, guaranteeing that both OtherVNI and RedefVNI have been analyzed and mapped before returning. The recursion always goes upwards in the dominator tree, making loops impossible.</p>


<p>Definition at line 2604 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### computeAssignment() {#ae30a0b4535b2f92da284051c9ec5f9ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void JoinVals::computeAssignment (unsigned ValNo, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals">JoinVals</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the value assignment for ValNo in RI.</p>


<p>This may be called recursively by analyzeValue(), but never for a ValNo on the stack.</p>


<p>Definition at line 2609 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### computeWriteLanes() {#a3b601b590cadfef81704df7fedb69624}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LaneBitmask JoinVals::computeWriteLanes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * DefMI, bool &amp; Redef)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the bitmask of lanes actually written by DefMI.</p>


<p>Set Redef if there are any partial register definitions that depend on the previous value of the register.</p>


<p>Definition at line 2589 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### followCopyChain() {#a52db6b6bd97b58d14370627d4df18c10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; const VNInfo *, Register &gt; JoinVals::followCopyChain (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * VNI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the ultimate value that VNI was copied from.</p>

<p>Definition at line 2592 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### isPrunedValue() {#afcd0b50c56e4d0c0fc61d306d86e9739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool JoinVals::isPrunedValue (unsigned ValNo, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals">JoinVals</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if ValNo is a copy of a value number in LR or Other.LR that will be pruned:</p>


<p>dst = COPY src src = COPY dst &lt;– This value to be pruned. dst = COPY src &lt;– This value is a copy of a pruned value.</p>


<p>Definition at line 2640 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### taintExtent() {#a2ca697afdb307e5d8509a65dd7419330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool JoinVals::taintExtent (unsigned ValNo, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> TaintedLanes, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals">JoinVals</a> &amp; Other, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> &gt; &gt; &amp; TaintExtent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assuming ValNo is going to clobber some valid lanes in Other.LR, compute the extent of the tainted lanes in the block.</p>


<p>Multiple values in Other.LR can be affected since partial redefinitions can preserve previously tainted lanes.</p>


<p>1 dst = VLOAD &lt;– Define all lanes in dst 2 src = FOO &lt;– ValNo to be joined with dst:ssub0 3 dst:ssub1 = BAR &lt;– Partial redef doesn't clear taint in ssub0 4 dst:ssub0 = COPY src &lt;– Conflict resolved, ssub0 wasn't read</p>


<p>For each ValNo in Other that is affected, add an (EndIndex, TaintedLanes) entry to TaintedVals.</p>


<p>Returns false if the tainted lanes extend beyond the basic block.</p>


<p>Definition at line 2627 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### usesLanes() {#aed477e65dbeca025bf7fe2569c6ae56a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool JoinVals::usesLanes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, unsigned SubIdx, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> Lanes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if MI uses any of the given Lanes from Reg.</p>


<p>This does not include partial redefinitions of Reg.</p>


<p>Definition at line 2632 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### valuesIdentical() {#a7f909c08212c6a23345731f266a416b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool JoinVals::valuesIdentical (<a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * Value0, <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * Value1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals">JoinVals</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2594 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Assignments {#a51ac22cac123d277c544dc93ecca618d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;int, 8&gt; anonymous{RegisterCoalescer.cpp}::JoinVals::Assignments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> number assignments.</p>


<p>Maps value numbers in LI to entries in NewVNInfo. This is suitable for passing to LiveInterval::join().</p>


<p>Definition at line 2491 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### CP {#aa2acb84b6d047282d222a27ee05d0a73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CoalescerPair&amp; anonymous{RegisterCoalescer.cpp}::JoinVals::CP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2484 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### Indexes {#a7e72f48daa6146407f9cec4837acfbf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndexes* anonymous{RegisterCoalescer.cpp}::JoinVals::Indexes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2486 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### LaneMask {#a8cae4b22a19d4de03a2bd5a3f9f17867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LaneBitmask anonymous{RegisterCoalescer.cpp}::JoinVals::LaneMask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The LaneMask that this liverange will occupy the coalesced register.</p>


<p>May be smaller than the lanemask produced by SubIdx when merging subranges.</p>


<p>Definition at line 2472 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### LIS {#aaa0132b120c5860a4450968879f28b91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals* anonymous{RegisterCoalescer.cpp}::JoinVals::LIS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2485 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### LR {#a87036fce73f22c86c223b4bd7760cb6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRange&amp; anonymous{RegisterCoalescer.cpp}::JoinVals::LR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Live range we work on.</p>

<p>Definition at line 2460 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### NewVNInfo {#adca2cec60f0ea667907cbcb02676b5c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt;VNInfo *&gt;&amp; anonymous{RegisterCoalescer.cpp}::JoinVals::NewVNInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Values that will be present in the final live range.</p>

<p>Definition at line 2482 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### Reg {#ad6bf2b256fbb6a03d7a2f05a6ad0a1f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Register anonymous{RegisterCoalescer.cpp}::JoinVals::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>(Main) register we work on.</p>

<p>Definition at line 2463 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### SubIdx {#a00b16137289c18d9b40835d65fcb0ccb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned anonymous{RegisterCoalescer.cpp}::JoinVals::SubIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reg (and therefore the values in this liverange) will end up as subregister SubIdx in the coalesced register.</p>


<p>Either CP.DstIdx or CP.SrcIdx.</p>


<p>Definition at line 2468 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### SubRangeJoin {#a8d3cea41a4b61ccea063ee5a717b8867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool anonymous{RegisterCoalescer.cpp}::JoinVals::SubRangeJoin</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is true when joining sub register ranges, false when joining main ranges.</p>

<p>Definition at line 2476 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### TrackSubRegLiveness {#a5cc9c5a4fe37b635831c4b622b5ae350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool anonymous{RegisterCoalescer.cpp}::JoinVals::TrackSubRegLiveness</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether the current <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> tracks subregister liveness.</p>

<p>Definition at line 2479 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### TRI {#aa624e808af5f76a7545541a1702b6a0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* anonymous{RegisterCoalescer.cpp}::JoinVals::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2487 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

### Vals {#acd0156cc106a925e972fa89e2f4c5e66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Val, 8&gt; anonymous{RegisterCoalescer.cpp}::JoinVals::Vals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>One entry per value number in LI.</p>

<p>Definition at line 2584 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp">RegisterCoalescer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
