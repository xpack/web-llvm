---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/liveinterval
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LiveInterval` Class

<p><a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> - This class represents the liveness of a register, or stack slot. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LiveInterval { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">llvm/CodeGen/LiveInterval.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents the liveness of a register, stack slot, etc. <a href="/web-llvm/docs/api/classes/llvm/liverange/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39584cc6f48b8315324146bb45d4c150">super</a> = <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bb2822e311a778f7a07e0bab3113014">subrange_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/liveinterval/singlelinkedlistiterator">SingleLinkedListIterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/liveinterval/subrange">SubRange</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae915edbc58e61f681a36e6bbfd622ba6">const_subrange_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/liveinterval/singlelinkedlistiterator">SingleLinkedListIterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval/subrange">SubRange</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75daeb7d8c137774a59f9fbefff10f35">LiveInterval</a> (unsigned Reg, float Weight)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57719453498ea3ee9c8e22d40fc78ea7">~LiveInterval</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cd5b6e093b1239921099f108e8eaabb">operator&lt;</a> (const LiveInterval &amp;other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14d46e70db7e417c8ed5bc66fb295185">reg</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fc46dffc68d1302d150b7e4c28c7983">weight</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c67bbc5f1e899d0bb7eaff6999203f7">incrementWeight</a> (float Inc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9c21366c83a0e52bd68da820745651d">setWeight</a> (float Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5bb2822e311a778f7a07e0bab3113014">subrange_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4b844373ef60b0f6e1a8174877ca375">subrange_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5bb2822e311a778f7a07e0bab3113014">subrange_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adea231813e8e83b6f9922a622a1eda97">subrange_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae915edbc58e61f681a36e6bbfd622ba6">const_subrange_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31aa9d1a436376cb4af48b31c799ff6f">subrange_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae915edbc58e61f681a36e6bbfd622ba6">const_subrange_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bc07f8962736595f3832aac1d5b2dfa">subrange_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a5bb2822e311a778f7a07e0bab3113014">subrange_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9545a896d571165e9f43cf4b29a6d072">subranges</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ae915edbc58e61f681a36e6bbfd622ba6">const_subrange_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc8d90912b80452b5ab51267f0d55546">subranges</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveinterval/subrange">SubRange</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6fb03322f7b38d6e815343732497798">createSubRange</a> (BumpPtrAllocator &amp;Allocator, LaneBitmask LaneMask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new empty subregister live range. <a href="#af6fb03322f7b38d6e815343732497798">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveinterval/subrange">SubRange</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8104005914e3dfed73608d0d8961b822">createSubRangeFrom</a> (BumpPtrAllocator &amp;Allocator, LaneBitmask LaneMask, const LiveRange &amp;CopyFrom)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Like <a href="#af6fb03322f7b38d6e815343732497798">createSubRange()</a> but the new range is filled with a copy of the liveness information in <span class="doxyComputerOutput">CopyFrom</span>. <a href="#a8104005914e3dfed73608d0d8961b822">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c198291d6ee66150b76633cda8a1749">hasSubRanges</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if subregister liveness information is available. <a href="#a1c198291d6ee66150b76633cda8a1749">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbdcbb3187e46987286c59c4963e21ae">clearSubRanges</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes all subregister liveness information. <a href="#afbdcbb3187e46987286c59c4963e21ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aac3ef1eadaa206a70b767730ef3c5b">removeEmptySubRanges</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes all subranges without any segments (subranges without segments are not considered valid and should only exist temporarily). <a href="#a0aac3ef1eadaa206a70b767730ef3c5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d81038ff196d7a9495ff9f7266d667c">getSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSize - Returns the sum of sizes of all the <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a>'s. <a href="#a5d81038ff196d7a9495ff9f7266d667c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a07a284547e2997c90a6a1be428cd47">isSpillable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isSpillable - Can this interval be spilled? <a href="#a1a07a284547e2997c90a6a1be428cd47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f0455af60f6cc894c2f580b82042b0b">markNotSpillable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>markNotSpillable - Mark interval as not spillable <a href="#a0f0455af60f6cc894c2f580b82042b0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4a07ae5c460ac08439a1a71d15e0166">computeSubRangeUndefs</a> (SmallVectorImpl&lt; SlotIndex &gt; &amp;Undefs, LaneBitmask LaneMask, const MachineRegisterInfo &amp;MRI, const SlotIndexes &amp;Indexes) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For a given lane mask <span class="doxyComputerOutput">LaneMask</span>, compute indexes at which the lane is marked undefined by subregister &lt;def,read-undef&gt; definitions. <a href="#af4a07ae5c460ac08439a1a71d15e0166">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a967540f5e5799b56c6fbcee378d110eb">refineSubRanges</a> (BumpPtrAllocator &amp;Allocator, LaneBitmask LaneMask, std::function&lt; void(LiveInterval::SubRange &amp;)&gt; Apply, const SlotIndexes &amp;Indexes, const TargetRegisterInfo &amp;TRI, unsigned ComposeSubRegIdx=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Refines the subranges to support <span class="doxyComputerOutput">LaneMask</span>. <a href="#a967540f5e5799b56c6fbcee378d110eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2b5b2c40dff9929de640b4522b97714">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2648a95467638981fc1d97770747854b">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0bc12f607db8709e37e7819756ae9a2">verify</a> (const MachineRegisterInfo *MRI=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Walks the interval and assert if any invariants fail to hold. <a href="#aa0bc12f607db8709e37e7819756ae9a2">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6d2f2fee60e8bc18bbf45d9b5b3f608">appendSubRange</a> (SubRange *Range)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Appends <span class="doxyComputerOutput">Range</span> to SubRanges list. <a href="#aa6d2f2fee60e8bc18bbf45d9b5b3f608">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77eec6a70ada62acd86928cadc78c5f2">freeSubRange</a> (SubRange *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Free memory held by <a href="/web-llvm/docs/api/classes/llvm/liveinterval/subrange">SubRange</a>. <a href="#a77eec6a70ada62acd86928cadc78c5f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveinterval/subrange">SubRange</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1615248ec8b18e532d3ed993fa5d22cc">SubRanges</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Single linked list of subregister live ranges. <a href="#a1615248ec8b18e532d3ed993fa5d22cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b2fa11f0a4fe18098e2161ff40c3304">Reg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0c64f87b8cab9c44693dec89440def2">Weight</a> = 0.0</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> - This class represents the liveness of a register, or stack slot.</p>

<p>Definition at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_subrange\_iterator {#ae915edbc58e61f681a36e6bbfd622ba6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveInterval::const_subrange_iterator =  SingleLinkedListIterator&lt;const SubRange&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 766 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### subrange\_iterator {#a5bb2822e311a778f7a07e0bab3113014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveInterval::subrange_iterator =  SingleLinkedListIterator&lt;SubRange&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### super {#a39584cc6f48b8315324146bb45d4c150}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveInterval::super =  LiveRange</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LiveInterval() {#a75daeb7d8c137774a59f9fbefff10f35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveInterval::LiveInterval (unsigned Reg, float Weight)</td>
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



<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="#a9cd5b6e093b1239921099f108e8eaabb">operator&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LiveInterval() {#a57719453498ea3ee9c8e22d40fc78ea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveInterval::~LiveInterval ()</td>
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



<p>Definition at line 725 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#afbdcbb3187e46987286c59c4963e21ae">clearSubRanges</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;() {#a9cd5b6e093b1239921099f108e8eaabb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveInterval::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; other)</td>
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



<p>Definition at line 883 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liverange/#a9b4b2c1bb443279588bd6582ad6a86b2">llvm::LiveRange::beginIndex</a> and <a href="#a75daeb7d8c137774a59f9fbefff10f35">LiveInterval</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearSubRanges() {#afbdcbb3187e46987286c59c4963e21ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveInterval::clearSubRanges ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Removes all subregister liveness information.</p>

<p>Declaration at line 815 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 861 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/registercoalescer/#aa408ab9747b8ce0bd0a81465c10e8f29">anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::runOnMachineFunction</a> and <a href="#a57719453498ea3ee9c8e22d40fc78ea7">~LiveInterval</a>.</p>

</div>
</div>

### computeSubRangeUndefs() {#af4a07ae5c460ac08439a1a71d15e0166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveInterval::computeSubRangeUndefs (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt; &amp; Undefs, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> &amp; Indexes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For a given lane mask <span class="doxyComputerOutput">LaneMask</span>, compute indexes at which the lane is marked undefined by subregister &lt;def,read-undef&gt; definitions.</p>

<p>Declaration at line 833 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#aa429e211fd041cb42d26e49dd5d95d75">llvm::SlotIndexes::getInstructionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ae3b98982e2036f3d26806de5ed5e02d0">llvm::SlotIndex::getRegSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a14d46e70db7e417c8ed5bc66fb295185">reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a>.</p>

</div>
</div>

### createSubRange() {#af6fb03322f7b38d6e815343732497798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubRange * llvm::LiveInterval::createSubRange (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask)</td>
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

<p>Creates a new empty subregister live range.</p>


<p>The range is added at the beginning of the subrange list; subrange iterators stay valid.</p>


<p>Definition at line 792 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp/#ad5d00e1d77644d95847b9bf8da12b759">Allocator</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#a5d79e4d110e15056182588d168ac6b2f">llvm::ConnectedVNInfoEqClasses::Distribute</a> and <a href="#a967540f5e5799b56c6fbcee378d110eb">refineSubRanges</a>.</p>

</div>
</div>

### createSubRangeFrom() {#a8104005914e3dfed73608d0d8961b822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubRange * llvm::LiveInterval::createSubRangeFrom (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; CopyFrom)</td>
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

<p>Like <a href="#af6fb03322f7b38d6e815343732497798">createSubRange()</a> but the new range is filled with a copy of the liveness information in <span class="doxyComputerOutput">CopyFrom</span>.</p>

<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp/#ad5d00e1d77644d95847b9bf8da12b759">Allocator</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a00e0b8f47bc603934f5954cd117af178">llvm::LiveRange::LiveRange</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#ad67d6b7f9f91a2d5852b0f9aebfe542a">llvm::LiveIntervalCalc::calculate</a> and <a href="#a967540f5e5799b56c6fbcee378d110eb">refineSubRanges</a>.</p>

</div>
</div>

### dump() {#a2648a95467638981fc1d97770747854b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void LiveInterval::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 890 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 1052 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregcoloring-cpp-/webassemblyregcoloring/#ac27e962fff6fda4c4419bc22281f38dd">anonymous{WebAssemblyRegColoring.cpp}::WebAssemblyRegColoring::runOnMachineFunction</a>.</p>

</div>
</div>

### getSize() {#a5d81038ff196d7a9495ff9f7266d667c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LiveInterval::getSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getSize - Returns the sum of sizes of all the <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a>'s.</p>

<p>Declaration at line 823 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 958 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/liverange/#a9c628b400be67b6adb4fa07e84a96a82">llvm::LiveRange::segments</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mlpriorityadvisor/#ab1ca75ff5e477978c030cd3040346f3d">llvm::MLPriorityAdvisor::getPriorityImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a137403167e291d2e011441ce02d51898">llvm::VirtRegAuxInfo::weightCalcHelper</a>.</p>

</div>
</div>

### hasSubRanges() {#a1c198291d6ee66150b76633cda8a1749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveInterval::hasSubRanges ()</td>
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

<p>Returns true if subregister liveness information is available.</p>

<p>Definition at line 810 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6e3886e9084257e74b5db4a8951d36e0">llvm::LiveIntervals::addKillFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a222d514d23098e92ecbd53e36b3c5084">llvm::GCNDownwardRPTracker::advanceBeforeNext</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#ad930b47a8263b4fcc37e6209e387b897">llvm::LiveRangeEdit::allUsesAvailableAt</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#ad67d6b7f9f91a2d5852b0f9aebfe542a">llvm::LiveIntervalCalc::calculate</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#aa2b8ab3df737c2492c7967447e7abac9">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLiveness</a>, <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#a5d79e4d110e15056182588d168ac6b2f">llvm::ConnectedVNInfoEqClasses::Distribute</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a1659a196eabbdd653b9a5d529ccfcb6e">anonymous{RegisterCoalescer.cpp}::JoinVals::eraseInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a96cdbab4e65a936880975a58e0dde922">llvm::SIRegisterInfo::findReachingDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp/#aab2ae433d483c154d92c727cf7282996">foreachUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#af22048866afa263f60942281802899e5">getLanesWithProperty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#ad17df702dc2863df688cbe4b9d7fe0ba">getLanesWithProperty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a563b8ed395be414427b56ade51afb784">llvm::getLiveLaneMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#ade1f2320fe436fd570559a11f1167746">getRegLiveThroughMask</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a0d7e0d23a0453390a4c1e9a61afccdca">llvm::LiveIntervals::repairIntervalsInRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-twoaddressinstructionpass-cpp-/twoaddressinstructionimpl/#a7bc0a5064c340800de9ce752c881316d">anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/registercoalescer/#aa408ab9747b8ce0bd0a81465c10e8f29">anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-renameindependentsubregs-cpp-/renameindependentsubregs/#a5a7168c10662c11aea9894ec2b7481bb">anonymous{RenameIndependentSubregs.cpp}::RenameIndependentSubregs::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-siformmemoryclauses-cpp-/siformmemoryclauses/#a3b412b093194b8e66d1d42d1cc79d692">anonymous{SIFormMemoryClauses.cpp}::SIFormMemoryClauses::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/liveintervals/hmeditor/#aa060d1bdca0620ff13d49456dccf9303">llvm::LiveIntervals::HMEditor::updateAllRanges</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a787f3f4287374d61c5f0657dd83acbb4">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveInterval</a>.</p>

</div>
</div>

### incrementWeight() {#a9c67bbc5f1e899d0bb7eaff6999203f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveInterval::incrementWeight (float Inc)</td>
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



<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### isSpillable() {#a1a07a284547e2997c90a6a1be428cd47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveInterval::isSpillable ()</td>
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

<p>isSpillable - Can this interval be spilled?</p>

<p>Definition at line 826 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3bc1efc2622aa9bf1e0d05b3d9600de">llvm::huge_valf</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a6f1fe32957cb698200b26a3a96e0145c">anonymous{RegAllocBasic.cpp}::RABasic::selectOrSplit</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinespiller-cpp-/inlinespiller/#af74cc1b6ed58474b37bafc059339a964">anonymous{InlineSpiller.cpp}::InlineSpiller::spill</a> and <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a137403167e291d2e011441ce02d51898">llvm::VirtRegAuxInfo::weightCalcHelper</a>.</p>

</div>
</div>

### markNotSpillable() {#a0f0455af60f6cc894c2f580b82042b0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveInterval::markNotSpillable ()</td>
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

<p>markNotSpillable - Mark interval as not spillable</p>

<p>Definition at line 829 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3bc1efc2622aa9bf1e0d05b3d9600de">llvm::huge_valf</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a137403167e291d2e011441ce02d51898">llvm::VirtRegAuxInfo::weightCalcHelper</a>.</p>

</div>
</div>

### print() {#ab2b5b2c40dff9929de640b4522b97714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveInterval::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 889 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 1034 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liverange/#af62a3dfb9ce9b78c94e7b910a02b28cf">llvm::LiveRange::print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="#a14d46e70db7e417c8ed5bc66fb295185">reg</a> and <a href="#a9545a896d571165e9f43cf4b29a6d072">subranges</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abcb52d0450629f83a1a16da990dc5c1b">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### refineSubRanges() {#a967540f5e5799b56c6fbcee378d110eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveInterval::refineSubRanges (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/liveinterval/subrange">LiveInterval::SubRange</a> &amp;)&gt; Apply, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> &amp; Indexes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, unsigned ComposeSubRegIdx=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Refines the subranges to support <span class="doxyComputerOutput">LaneMask</span>.</p>


<p>This may only be called for LI.hasSubrange()==true. Subregister ranges are split or created until <span class="doxyComputerOutput">LaneMask</span> can be matched exactly. <span class="doxyComputerOutput">Mod</span> is executed on the matching subranges.</p>


<p>Example: Given an interval with subranges with lanemasks L0F00, L00F0 and L000F, refining for mask L0018. Will split the L00F0 lane into L00E0 and L0010 and the L000F lane into L0007 and L0008. The Mod function will be applied to the L0010 and L0008 subranges.</p>


<p><span class="doxyComputerOutput">Indexes</span> and <span class="doxyComputerOutput">TRI</span> are required to clean up the VNIs that don't define the related lane masks after they get shrunk. E.g., when L000F gets split into L0007 and L0008 maybe only a subset of the VNIs that defined L000F defines L0007.</p>


<p>The clean up of the VNIs need to look at the actual instructions to decide what is or is not live at a definition point. If the update of the subranges occurs while the IR does not reflect these changes, <span class="doxyComputerOutput">ComposeSubRegIdx</span> can be used to specify how the definition are going to be rewritten. E.g., let say we want to merge: V1.sub1:&lt;2 x s32&gt; = COPY V2.sub3:&lt;4 x s32&gt; We do that by choosing a class where sub1:&lt;2 x s32&gt; and sub3:&lt;4 x s32&gt; overlap, i.e., by choosing a class where we can find "offset + 1 == 3". Put differently we align V2's sub3 with V1's sub1: V2: sub0 sub1 sub2 sub3 V1: &lt;offset&gt; sub0 sub1</p>


<p>This offset will look like a composed subregidx in the class: V1.(composed sub2 with sub1):&lt;4 x s32&gt; = COPY V2.sub3:&lt;4 x s32&gt; =&gt; V1.(composed sub2 with sub1):&lt;4 x s32&gt; = COPY V2.sub3:&lt;4 x s32&gt;</p>


<p>Now if we didn't rewrite the uses and def of V1, all the checks for V1 need to account for this offset. This happens during coalescing where we update the live-ranges while still having the old IR around because updating the IR on-the-fly would actually clobber some information on how the live-ranges that are being updated look like.</p>


<p>Declaration at line 877 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 919 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a72988cca7ab2262ef68fdd0c5ae54940">llvm::LaneBitmask::any</a>, <a href="#af6fb03322f7b38d6e815343732497798">createSubRange</a>, <a href="#a8104005914e3dfed73608d0d8961b822">createSubRangeFrom</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a60907035da962ba7bea74ffb9af977bd">llvm::LaneBitmask::none</a>, <a href="#a14d46e70db7e417c8ed5bc66fb295185">reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp/#aeb309e71b02f8298a437ec465645fe99">stripValuesNotDefiningMask</a>, <a href="#a9545a896d571165e9f43cf4b29a6d072">subranges</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#ad67d6b7f9f91a2d5852b0f9aebfe542a">llvm::LiveIntervalCalc::calculate</a>.</p>

</div>
</div>

### reg() {#a14d46e70db7e417c8ed5bc66fb295185}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::LiveInterval::reg ()</td>
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



<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#ac0a0c1bb8dc69992e326ead7f5faf286">anonymous{LiveDebugVariables.cpp}::UserValue::addDefsFromCopies</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinespiller-cpp-/hoistspillhelper/#a802b241b8cfc1f00f85b1d4da7eeed73">anonymous{InlineSpiller.cpp}::HoistSpillHelper::addToMergeableSpills</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#ac35fef2aafb20ef4b079d0819394e87d">llvm::RegAllocBase::allocatePhysRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#aca181a8107cd511dad6c6627fe9f6fae">llvm::LiveRegMatrix::assign</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#a6e87024d7fe817808e0288f6b213d40c">assignedRegPartiallyOverlaps</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#ad67d6b7f9f91a2d5852b0f9aebfe542a">llvm::LiveIntervalCalc::calculate</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#a6c15e4226ea85c6c5ffdb7b907023b85">llvm::LiveRangeEdit::calculateRegClassAndHint</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/calcspillweights-cpp/#a413851d287074f68f5d568f75155c283">canMemFoldInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisor/#ab0ec56bd57b2676e33aa9f1b0213f0a4">llvm::RegAllocEvictionAdvisor::canReassign</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a26c99fa2411ae509e9eb030f8aefb4e8">llvm::LiveIntervals::checkRegMaskInterference</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#a0afff12e511e93ff630cada967573162">llvm::LiveRegMatrix::checkRegMaskInterference</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#ad08d47c88b8af3c45df94d19ccc6e679">llvm::LiveRegMatrix::checkRegUnitInterference</a>, <a href="#af4a07ae5c460ac08439a1a71d15e0166">computeSubRangeUndefs</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#af5198110c0058e3d60524eecf500ee51">llvm::LiveIntervalCalc::constructMainRangeFromSubranges</a>, <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#a5d79e4d110e15056182588d168ac6b2f">llvm::ConnectedVNInfoEqClasses::Distribute</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#add47e6d974ce584ea3fa3fc80ee34259">llvm::LiveRangeEdit::eliminateDeadDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a1d4798520a9880c2b801fd18ff8342d2">llvm::RegAllocBase::enqueue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a563b8ed395be414427b56ade51afb784">llvm::getLiveLaneMask</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#a59599eeb1c2ffa96071e18dfee6febc2">llvm::LiveRegMatrix::getOneVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocevictionadvisor/#a3d78f0675943050b646535282e211da6">llvm::RegAllocEvictionAdvisor::getOrderLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#ac2d157d94da9ea6da55d19a1fa8d9247">llvm::LiveRangeEdit::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/extrareginfo/#a2bc3fe5b7a64ed8dbb2681600ba3e793">llvm::RAGreedy::ExtraRegInfo::getStage</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a9e4d1b2ff6c306576d8ffa9922fa8ba3">llvm::VirtRegAuxInfo::isRematerializable</a>, <a href="#ab2b5b2c40dff9929de640b4522b97714">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#a6e634ebc0d21fdf961ec8451940caf20">readsLaneSubset</a>, <a href="#a967540f5e5799b56c6fbcee378d110eb">refineSubRanges</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregcoloring-cpp-/webassemblyregcoloring/#ac27e962fff6fda4c4419bc22281f38dd">anonymous{WebAssemblyRegColoring.cpp}::WebAssemblyRegColoring::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a6f1fe32957cb698200b26a3a96e0145c">anonymous{RegAllocBasic.cpp}::RABasic::selectOrSplit</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/extrareginfo/#a9ed6be3c42e541f0fc355a102aaaf09b">llvm::RAGreedy::ExtraRegInfo::setStage</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a1ee36ec6dd22cf058ebb96f2a7ef0108">llvm::TargetRegisterInfo::shouldRegionSplitForVirtReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac7446b2819c44bf459763351b5bcc29b">llvm::LiveIntervals::shrinkToUses</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#aeffc1bb4ebe64a8ad3478e1253683847">llvm::LiveIntervals::splitSeparateComponents</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#a128d0b27fb99ba10fc96a8c526129157">llvm::LiveRegMatrix::unassign</a>, <a href="#aa0bc12f607db8709e37e7819756ae9a2">verify</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a787f3f4287374d61c5f0657dd83acbb4">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveInterval</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a42f45acfa351a67ac2975773261005d7">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveIntervals</a> and <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a137403167e291d2e011441ce02d51898">llvm::VirtRegAuxInfo::weightCalcHelper</a>.</p>

</div>
</div>

### removeEmptySubRanges() {#a0aac3ef1eadaa206a70b767730ef3c5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveInterval::removeEmptySubRanges ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Removes all subranges without any segments (subranges without segments are not considered valid and should only exist temporarily).</p>

<p>Declaration at line 819 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 842 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#ad67d6b7f9f91a2d5852b0f9aebfe542a">llvm::LiveIntervalCalc::calculate</a>, <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#a5d79e4d110e15056182588d168ac6b2f">llvm::ConnectedVNInfoEqClasses::Distribute</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a98fa413da7a0053bf635119e74970219">llvm::SplitEditor::finish</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a3730642a8860945b6ca5ca954a238592">anonymous{RegisterCoalescer.cpp}::JoinVals::pruneSubRegValues</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac332ca27d85adc8d21edd708be55dfe3">llvm::LiveIntervals::removeVRegDefAt</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a0d7e0d23a0453390a4c1e9a61afccdca">llvm::LiveIntervals::repairIntervalsInRange</a> and <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac7446b2819c44bf459763351b5bcc29b">llvm::LiveIntervals::shrinkToUses</a>.</p>

</div>
</div>

### setWeight() {#af9c21366c83a0e52bd68da820745651d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveInterval::setWeight (float Value)</td>
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



<p>Definition at line 721 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#ab388ef162b7c6b9061678583f9fd0f16">llvm::VirtRegAuxInfo::calculateSpillWeightAndHint</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregcoloring-cpp-/webassemblyregcoloring/#ac27e962fff6fda4c4419bc22281f38dd">anonymous{WebAssemblyRegColoring.cpp}::WebAssemblyRegColoring::runOnMachineFunction</a>.</p>

</div>
</div>

### subrange\_begin() {#ad4b844373ef60b0f6e1a8174877ca375}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">subrange_iterator llvm::LiveInterval::subrange_begin ()</td>
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



<p>Definition at line 768 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="#a9545a896d571165e9f43cf4b29a6d072">subranges</a> and <a href="#acc8d90912b80452b5ab51267f0d55546">subranges</a>.</p>

</div>
</div>

### subrange\_begin() {#a31aa9d1a436376cb4af48b31c799ff6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_subrange_iterator llvm::LiveInterval::subrange_begin ()</td>
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



<p>Definition at line 775 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### subrange\_end() {#adea231813e8e83b6f9922a622a1eda97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">subrange_iterator llvm::LiveInterval::subrange_end ()</td>
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



<p>Definition at line 771 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="#a9545a896d571165e9f43cf4b29a6d072">subranges</a> and <a href="#acc8d90912b80452b5ab51267f0d55546">subranges</a>.</p>

</div>
</div>

### subrange\_end() {#a9bc07f8962736595f3832aac1d5b2dfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_subrange_iterator llvm::LiveInterval::subrange_end ()</td>
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



<p>Definition at line 778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### subranges() {#a9545a896d571165e9f43cf4b29a6d072}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; subrange_iterator &gt; llvm::LiveInterval::subranges ()</td>
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



<p>Definition at line 782 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#ad4b844373ef60b0f6e1a8174877ca375">subrange_begin</a> and <a href="#adea231813e8e83b6f9922a622a1eda97">subrange_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6e3886e9084257e74b5db4a8951d36e0">llvm::LiveIntervals::addKillFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a222d514d23098e92ecbd53e36b3c5084">llvm::GCNDownwardRPTracker::advanceBeforeNext</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#ad930b47a8263b4fcc37e6209e387b897">llvm::LiveRangeEdit::allUsesAvailableAt</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#ad67d6b7f9f91a2d5852b0f9aebfe542a">llvm::LiveIntervalCalc::calculate</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#aa2b8ab3df737c2492c7967447e7abac9">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLiveness</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#af5198110c0058e3d60524eecf500ee51">llvm::LiveIntervalCalc::constructMainRangeFromSubranges</a>, <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#a5d79e4d110e15056182588d168ac6b2f">llvm::ConnectedVNInfoEqClasses::Distribute</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a1659a196eabbdd653b9a5d529ccfcb6e">anonymous{RegisterCoalescer.cpp}::JoinVals::eraseInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a96cdbab4e65a936880975a58e0dde922">llvm::SIRegisterInfo::findReachingDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp/#aab2ae433d483c154d92c727cf7282996">foreachUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#af22048866afa263f60942281802899e5">getLanesWithProperty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#ad17df702dc2863df688cbe4b9d7fe0ba">getLanesWithProperty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a563b8ed395be414427b56ade51afb784">llvm::getLiveLaneMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp/#a8e3cbbade7440fd10534f580ee6f2d06">getSubRangeForMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#a557a8b6ef8191908ae0c534f76b9f782">isDefInSubRange</a>, <a href="#ab2b5b2c40dff9929de640b4522b97714">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a3730642a8860945b6ca5ca954a238592">anonymous{RegisterCoalescer.cpp}::JoinVals::pruneSubRegValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#a6e634ebc0d21fdf961ec8451940caf20">readsLaneSubset</a>, <a href="#a967540f5e5799b56c6fbcee378d110eb">refineSubRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac332ca27d85adc8d21edd708be55dfe3">llvm::LiveIntervals::removeVRegDefAt</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a0d7e0d23a0453390a4c1e9a61afccdca">llvm::LiveIntervals::repairIntervalsInRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-twoaddressinstructionpass-cpp-/twoaddressinstructionimpl/#a7bc0a5064c340800de9ce752c881316d">anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/registercoalescer/#aa408ab9747b8ce0bd0a81465c10e8f29">anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-siformmemoryclauses-cpp-/siformmemoryclauses/#a3b412b093194b8e66d1d42d1cc79d692">anonymous{SIFormMemoryClauses.cpp}::SIFormMemoryClauses::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac7446b2819c44bf459763351b5bcc29b">llvm::LiveIntervals::shrinkToUses</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/renameindependentsubregs-cpp/#ad2f4f6c15691383c1db014fa225c6c36">subRangeLiveAt</a>, <a href="/web-llvm/docs/api/classes/liveintervals/hmeditor/#aa060d1bdca0620ff13d49456dccf9303">llvm::LiveIntervals::HMEditor::updateAllRanges</a>, <a href="#aa0bc12f607db8709e37e7819756ae9a2">verify</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a787f3f4287374d61c5f0657dd83acbb4">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveInterval</a>.</p>

</div>
</div>

### subranges() {#acc8d90912b80452b5ab51267f0d55546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_subrange_iterator &gt; llvm::LiveInterval::subranges ()</td>
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



<p>Definition at line 786 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#ad4b844373ef60b0f6e1a8174877ca375">subrange_begin</a> and <a href="#adea231813e8e83b6f9922a622a1eda97">subrange_end</a>.</p>

</div>
</div>

### verify() {#aa0bc12f607db8709e37e7819756ae9a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveInterval::verify (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Walks the interval and assert if any invariants fail to hold.</p>


<p>Note that this is a no-op when asserts are disabled.</p>


<p>Declaration at line 900 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 1085 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liverange/#a5c2526062a291ca7d78fe98bbf66edb7">llvm::LiveRange::covers</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">llvm::LaneBitmask::getAll</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#a14d46e70db7e417c8ed5bc66fb295185">reg</a>, <a href="#a9545a896d571165e9f43cf4b29a6d072">subranges</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#a84d7fba74d57269f494283490fd93439">llvm::LiveRange::verify</a>.</p>

</div>
</div>

### weight() {#a0fc46dffc68d1302d150b7e4c28c7983}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float llvm::LiveInterval::weight ()</td>
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



<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inlinespiller-cpp-/hoistspillhelper/#a802b241b8cfc1f00f85b1d4da7eeed73">anonymous{InlineSpiller.cpp}::HoistSpillHelper::addToMergeableSpills</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/spillcosts/#a24a1e3c936c56e8a7424d8bd2f4265cb">anonymous{RegAllocPBQP.cpp}::SpillCosts::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/mlpriorityadvisor/#ab1ca75ff5e477978c030cd3040346f3d">llvm::MLPriorityAdvisor::getPriorityImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregcoloring-cpp-/webassemblyregcoloring/#ac27e962fff6fda4c4419bc22281f38dd">anonymous{WebAssemblyRegColoring.cpp}::WebAssemblyRegColoring::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#ab2d41fa069e7edcedf9949fa64aa6e30">anonymous{RegAllocBasic.cpp}::RABasic::spillInterferences</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### appendSubRange() {#aa6d2f2fee60e8bc18bbf45d9b5b3f608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveInterval::appendSubRange (<a href="/web-llvm/docs/api/classes/llvm/liveinterval/subrange">SubRange</a> * Range)</td>
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

<p>Appends <span class="doxyComputerOutput">Range</span> to SubRanges list.</p>

<p>Definition at line 905 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### freeSubRange() {#a77eec6a70ada62acd86928cadc78c5f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveInterval::freeSubRange (<a href="/web-llvm/docs/api/classes/llvm/liveinterval/subrange">SubRange</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Free memory held by <a href="/web-llvm/docs/api/classes/llvm/liveinterval/subrange">SubRange</a>.</p>

<p>Declaration at line 911 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 837 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Reg {#a1b2fa11f0a4fe18098e2161ff40c3304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Register llvm::LiveInterval::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### SubRanges {#a1615248ec8b18e532d3ed993fa5d22cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubRange* llvm::LiveInterval::SubRanges = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Single linked list of subregister live ranges.</p>

<p>Definition at line 712 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### Weight {#af0c64f87b8cab9c44693dec89440def2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float llvm::LiveInterval::Weight = 0.0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 715 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
