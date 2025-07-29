---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/liverange
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LiveRange` Class

<p>This class represents the liveness of a register, stack slot, etc. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LiveRange { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">llvm/CodeGen/LiveInterval.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> - This class represents the liveness of a register, or stack slot. <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveinterval/subrange">SubRange</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A live range for subregisters. <a href="/web-llvm/docs/api/classes/llvm/liveinterval/subrange/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad156d10b494ea747d7c2a8776c02ca42">Segments</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a>, 2 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefb141f259f039ab6207a184ca74dd4d">VNInfoList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *, 2 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48b28ef05db480eb6428eca80a67ec14">SegmentSet</a> = std::set&lt; <a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a143c1fcb6066cb301f828ec4c18d79f4">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a9eae7ba1448d9866beca95a042de2e11">Segments::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fc869c7f6d53c3fbb4e572b7821dd05">const_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aa11b903431c1931920939bac6b5293a2">Segments::const_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d39c8cfe85b466b9e7e2e65706733fa">vni_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ac5b936169badf0b703567eb960278648">VNInfoList::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade5d926ff67db0c0e9f873c13003bebc">const_vni_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a641b0782e0cc309372855bfc19fdfd97">VNInfoList::const_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92d79994c676d5d28a2f765b7e6dfd9d">LiveRangeUpdater</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00e0b8f47bc603934f5954cd117af178">LiveRange</a> (bool UseSegmentSet=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs a new <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> object. <a href="#a00e0b8f47bc603934f5954cd117af178">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d54b859f7cec2b9d7e0e6a06b2f81ad">LiveRange</a> (const LiveRange &amp;Other, BumpPtrAllocator &amp;Allocator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs a new <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> object by copying segments and valnos from another <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a>. <a href="#a3d54b859f7cec2b9d7e0e6a06b2f81ad">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefd338315367c7476ba86002655d3c12">operator&lt;</a> (const LiveRange &amp;other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a143c1fcb6066cb301f828ec4c18d79f4">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a5e7c523f12f9f164b786769de1ca47">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a143c1fcb6066cb301f828ec4c18d79f4">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a757fd6afba0f531db70e78e057d147c6">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3fc869c7f6d53c3fbb4e572b7821dd05">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e1217331523ec239d385d5117b6bfed">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3fc869c7f6d53c3fbb4e572b7821dd05">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cf54954ea6cbc5ff4895e3f7f7ca1af">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1d39c8cfe85b466b9e7e2e65706733fa">vni_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fb099e2afb74f4c922f32894b30b279">vni_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1d39c8cfe85b466b9e7e2e65706733fa">vni_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca7b7d6f329690e6bd5b5e1c83db7c1e">vni_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ade5d926ff67db0c0e9f873c13003bebc">const_vni_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64661635fc0bf729d6e39b2dfa8a965e">vni_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ade5d926ff67db0c0e9f873c13003bebc">const_vni_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a812e5c85e99795c3985efdd87946edf5">vni_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a1d39c8cfe85b466b9e7e2e65706733fa">vni_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3524c5585af87a1c875f60fe849d241f">vnis</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ade5d926ff67db0c0e9f873c13003bebc">const_vni_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01f43c892ce74d401d4d7380fc2d176c">vnis</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7eb95d6c78b269fe03ed9c78cf2c33f">assign</a> (const LiveRange &amp;Other, BumpPtrAllocator &amp;Allocator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copies values numbers and live segments from <span class="doxyComputerOutput">Other</span> into this range. <a href="#ae7eb95d6c78b269fe03ed9c78cf2c33f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a143c1fcb6066cb301f828ec4c18d79f4">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60203ad10397a7340f8a0e44ac25368d">advanceTo</a> (iterator I, SlotIndex Pos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>advanceTo - Advance the specified iterator to point to the <a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a> containing the specified position, or <a href="#a757fd6afba0f531db70e78e057d147c6">end()</a> if the position is past the end of the range. <a href="#a60203ad10397a7340f8a0e44ac25368d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3fc869c7f6d53c3fbb4e572b7821dd05">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c5f46066435ccdbcc893d51b5a2ad31">advanceTo</a> (const_iterator I, SlotIndex Pos) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a143c1fcb6066cb301f828ec4c18d79f4">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeb00b9049a2391c990df15692caef63">find</a> (SlotIndex Pos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>find - Return an iterator pointing to the first segment that ends after Pos, or <a href="#a757fd6afba0f531db70e78e057d147c6">end()</a>. <a href="#afeb00b9049a2391c990df15692caef63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3fc869c7f6d53c3fbb4e572b7821dd05">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c0d1740405c9223c998127f7a8e27a0">find</a> (SlotIndex Pos) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1555194b9f176612b04fbd38f49b40d">clear</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac80c04546dae620bf4dca9d6137d6a61">size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace8519cea9fa2e688a052df670afe41e">hasAtLeastOneValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5db2ca7684625ebf424170b9e98f404">containsOneValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93450063916ca1ab1f11bf3304a6ad03">getNumValNums</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a060100d6b75129bdef5516fac8f89a55">getValNumInfo</a> (unsigned ValNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getValNumInfo - Returns pointer to the specified val#. <a href="#a060100d6b75129bdef5516fac8f89a55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b4b1397b800d411d5e89bd09cde5b2a">getValNumInfo</a> (unsigned ValNo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c036680263adf0032709cd2e7c3c9c3">containsValue</a> (const VNInfo *VNI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>containsValue - Returns true if VNI belongs to this range. <a href="#a5c036680263adf0032709cd2e7c3c9c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae609c36884142cbc16989cdf3bec4dad">getNextValue</a> (SlotIndex Def, VNInfo::Allocator &amp;VNInfoAllocator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getNextValue - Create a new value number and return it. <a href="#ae609c36884142cbc16989cdf3bec4dad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4258d794235c7a408b3f52e5e4ef7159">createDeadDef</a> (SlotIndex Def, VNInfo::Allocator &amp;VNIAlloc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createDeadDef - Make sure the range has a value defined at Def. <a href="#a4258d794235c7a408b3f52e5e4ef7159">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbfe0544c5d2588941c44827f801e64b">createDeadDef</a> (VNInfo *VNI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a def of value <span class="doxyComputerOutput">VNI</span>. <a href="#adbfe0544c5d2588941c44827f801e64b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e577095d60431acbf1416db9bb8ec78">createValueCopy</a> (const VNInfo *orig, VNInfo::Allocator &amp;VNInfoAllocator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a copy of the given value. <a href="#a3e577095d60431acbf1416db9bb8ec78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a687cab1756967efc8f0ce66105531755">RenumberValues</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RenumberValues - Renumber all values in order of appearance and remove unused values. <a href="#a687cab1756967efc8f0ce66105531755">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92e17326c2170e889ae4390c56878b77">MergeValueNumberInto</a> (VNInfo *V1, VNInfo *V2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MergeValueNumberInto - This method is called when two value numbers are found to be equivalent. <a href="#a92e17326c2170e889ae4390c56878b77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae51d91c7cb4dc1a4ffabbfd1b7be9a1">MergeSegmentsInAsValue</a> (const LiveRange &amp;RHS, VNInfo *LHSValNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge all of the live segments of a specific val# in RHS into this live range as the specified value number. <a href="#aae51d91c7cb4dc1a4ffabbfd1b7be9a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a325a4ec9c33a3dead9ff01c9e70fd534">MergeValueInAsValue</a> (const LiveRange &amp;RHS, const VNInfo *RHSValNo, VNInfo *LHSValNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MergeValueInAsValue - Merge all of the segments of a specific val# in RHS into this live range as the specified value number. <a href="#a325a4ec9c33a3dead9ff01c9e70fd534">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66ff664a97cd3c30de7e873335a0c075">empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b4b2c1bb443279588bd6582ad6a86b2">beginIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>beginIndex - Return the lowest numbered slot covered. <a href="#a9b4b2c1bb443279588bd6582ad6a86b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1bc5510e870a77ebe055b1524d9fd26">endIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>endNumber - return the maximum point of the range of the whole, exclusive. <a href="#aa1bc5510e870a77ebe055b1524d9fd26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a847f686bd17a148675f6659c99b96019">expiredAt</a> (SlotIndex index) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a400c0b88110521ad1de258a7885d9038">liveAt</a> (SlotIndex index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cde3a312b39ac23baecfce5fee662f7">getSegmentContaining</a> (SlotIndex Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the segment that contains the specified index, or null if there is none. <a href="#a1cde3a312b39ac23baecfce5fee662f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2f1d4a3bccca2391d35fb1391ebf287">getSegmentContaining</a> (SlotIndex Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the live segment that contains the specified index, or null if there is none. <a href="#ab2f1d4a3bccca2391d35fb1391ebf287">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe7daa73e4cee4edb9f137a8008dfb73">getVNInfoAt</a> (SlotIndex Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getVNInfoAt - Return the <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> that is live at Idx, or NULL. <a href="#afe7daa73e4cee4edb9f137a8008dfb73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e1ec6260b229b2f5913405b758bc146">getVNInfoBefore</a> (SlotIndex Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getVNInfoBefore - Return the <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> that is live up to but not necessarily including Idx, or NULL. <a href="#a7e1ec6260b229b2f5913405b758bc146">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a143c1fcb6066cb301f828ec4c18d79f4">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6eab1035db7ba328354fa739be090f0">FindSegmentContaining</a> (SlotIndex Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an iterator to the segment that contains the specified index, or <a href="#a757fd6afba0f531db70e78e057d147c6">end()</a> if there is none. <a href="#ae6eab1035db7ba328354fa739be090f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3fc869c7f6d53c3fbb4e572b7821dd05">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17255219eb93e6a7f59c1ff32f79f544">FindSegmentContaining</a> (SlotIndex Idx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69ef19ea9e324373a8f6d2cadfd1dad3">overlaps</a> (const LiveRange &amp;other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>overlaps - Return true if the intersection of the two live ranges is not empty. <a href="#a69ef19ea9e324373a8f6d2cadfd1dad3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4d61431580966063160f1cc3fdc1d2e">overlaps</a> (const LiveRange &amp;Other, const CoalescerPair &amp;CP, const SlotIndexes &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>overlaps - Return true if the two ranges have overlapping segments that are not coalescable according to CP. <a href="#af4d61431580966063160f1cc3fdc1d2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad099290f57deba5658668df9518605bb">overlaps</a> (SlotIndex Start, SlotIndex End) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>overlaps - Return true if the live range overlaps an interval specified by [Start, End). <a href="#ad099290f57deba5658668df9518605bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bd7e5014a81b162dccedd9330615546">overlapsFrom</a> (const LiveRange &amp;Other, const_iterator StartPos) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>overlapsFrom - Return true if the intersection of the two live ranges is not empty. <a href="#a6bd7e5014a81b162dccedd9330615546">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c2526062a291ca7d78fe98bbf66edb7">covers</a> (const LiveRange &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if all segments of the <span class="doxyComputerOutput">Other</span> live range are completely covered by this live range. <a href="#a5c2526062a291ca7d78fe98bbf66edb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a143c1fcb6066cb301f828ec4c18d79f4">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b73c8d5ae32ca13dd02ddde86ffd0a2">addSegment</a> (Segment S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the specified <a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a> to this range, merging segments as appropriate. <a href="#a0b73c8d5ae32ca13dd02ddde86ffd0a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81f9d3d0b958e57c0c0f24982230885d">extendInBlock</a> (ArrayRef&lt; SlotIndex &gt; Undefs, SlotIndex StartIdx, SlotIndex Kill)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to extend a value defined after <span class="doxyComputerOutput">StartIdx</span> to include <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span>. <a href="#a81f9d3d0b958e57c0c0f24982230885d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc063bb08668434f0df98f4230901d10">extendInBlock</a> (SlotIndex StartIdx, SlotIndex Kill)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simplified version of the above "extendInBlock", which assumes that no register lanes are undefined by &lt;def,read-undef&gt; operands. <a href="#acc063bb08668434f0df98f4230901d10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b10543d5f749956dd408fd7ebb3c552">join</a> (LiveRange &amp;Other, const int *ValNoAssignments, const int *RHSValNoAssignments, SmallVectorImpl&lt; VNInfo * &gt; &amp;NewVNInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>join - Join two live ranges (this, and other) together. <a href="#a2b10543d5f749956dd408fd7ebb3c552">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae17e7d305505cddb57d8093ee934c387">isLocal</a> (SlotIndex Start, SlotIndex End) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True iff this segment is a single segment that lies between the specified boundaries, exclusively. <a href="#ae17e7d305505cddb57d8093ee934c387">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8bd4b098d55a431c12cfba2a11c94bb">removeSegment</a> (SlotIndex Start, SlotIndex End, bool RemoveDeadValNo=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the specified interval from this live range. <a href="#ae8bd4b098d55a431c12cfba2a11c94bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedd2a145f951aba2dc5ee491dfdbfceb">removeSegment</a> (Segment S, bool RemoveDeadValNo=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a143c1fcb6066cb301f828ec4c18d79f4">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acea134ac1ed40b2215b8a1065a176d96">removeSegment</a> (iterator I, bool RemoveDeadValNo=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove segment pointed to by iterator <span class="doxyComputerOutput">I</span> from this range. <a href="#acea134ac1ed40b2215b8a1065a176d96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea1f4a9101ccc20faa0e67fdef1e5086">removeValNoIfDead</a> (VNInfo *ValNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark <span class="doxyComputerOutput">ValNo</span> for deletion if no segments in this range use it. <a href="#aea1f4a9101ccc20faa0e67fdef1e5086">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/livequeryresult">LiveQueryResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eb0e49d283729a5f8b99d4efa1be7c1">Query</a> (SlotIndex Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query Liveness at Idx. <a href="#a6eb0e49d283729a5f8b99d4efa1be7c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63176e601338dbe403676b86e78c7203">removeValNo</a> (VNInfo *ValNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeValNo - Remove all the segments defined by the specified value#. <a href="#a63176e601338dbe403676b86e78c7203">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61f530037a29a00a48799b14104a68d1">isZeroLength</a> (SlotIndexes *Indexes) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the live range is zero length, i.e. <a href="#a61f530037a29a00a48799b14104a68d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e12c0cb71a44b8822c5a35cbbe5c731">isLiveAtIndexes</a> (ArrayRef&lt; SlotIndex &gt; Slots) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab78d2b1052d3be8da6bba690bce9336f">isUndefIn</a> (ArrayRef&lt; SlotIndex &gt; Undefs, SlotIndex Begin, SlotIndex End) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if there is an explicit "undef" between <span class="doxyComputerOutput">Begin</span> <span class="doxyComputerOutput">End</span>. <a href="#ab78d2b1052d3be8da6bba690bce9336f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb60ddfb929ff4265623f2aa4f39a83e">flushSegmentSet</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flush segment set into the regular segment vector. <a href="#afb60ddfb929ff4265623f2aa4f39a83e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Range, typename OutputIt&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a76906231c2b079d1b909ddae48ef6e14">findIndexesLiveAt</a> (Range &amp;&amp;R, OutputIt O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stores indexes from the input index sequence R at which this <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> is live to the output O iterator. <a href="#a76906231c2b079d1b909ddae48ef6e14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af62a3dfb9ce9b78c94e7b910a02b28cf">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee80ffb31cdad64c9ef4dbd42e794b68">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84d7fba74d57269f494283490fd93439">verify</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Walk the range and assert if any invariants fail to hold. <a href="#a84d7fba74d57269f494283490fd93439">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fc86da696e49b67827c940045434c4b">append</a> (const LiveRange::Segment S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append a segment to the list of segments. <a href="#a8fc86da696e49b67827c940045434c4b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa34a887f9079608a6d196af2389b9683">addSegmentToSet</a> (Segment S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70f57fbad3e7df42d40124e64583577a">markValNoForDeletion</a> (VNInfo *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ValNo is dead, remove it. <a href="#a70f57fbad3e7df42d40124e64583577a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad156d10b494ea747d7c2a8776c02ca42">Segments</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aefb141f259f039ab6207a184ca74dd4d">VNInfoList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eb4aa155c41e60dff42f4e741a0dcf0">valnos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="#a48b28ef05db480eb6428eca80a67ec14">SegmentSet</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a626da1d721d44f0fb48c580213d4386c">segmentSet</a></td>
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

<p>This class represents the liveness of a register, stack slot, etc.</p>


<p>It manages an ordered list of <a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a> objects. The <a href="#ad156d10b494ea747d7c2a8776c02ca42">Segments</a> are organized in a static single assignment form: At places where a new value is defined or different values reach a CFG join a new segment with a new value number is used.</p>


<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a3fc869c7f6d53c3fbb4e572b7821dd05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveRange::const_iterator =  Segments::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### const\_vni\_iterator {#ade5d926ff67db0c0e9f873c13003bebc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveRange::const_vni_iterator =  VNInfoList::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### iterator {#a143c1fcb6066cb301f828ec4c18d79f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveRange::iterator =  Segments::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### Segments {#ad156d10b494ea747d7c2a8776c02ca42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveRange::Segments =  SmallVector&lt;Segment, 2&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### SegmentSet {#a48b28ef05db480eb6428eca80a67ec14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveRange::SegmentSet =  std::set&lt;Segment&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### vni\_iterator {#a1d39c8cfe85b466b9e7e2e65706733fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveRange::vni_iterator =  VNInfoList::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

### VNInfoList {#aefb141f259f039ab6207a184ca74dd4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveRange::VNInfoList =  SmallVector&lt;VNInfo *, 2&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### LiveRangeUpdater {#a92d79994c676d5d28a2f765b7e6dfd9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/liverangeupdater">LiveRangeUpdater</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a92d79994c676d5d28a2f765b7e6dfd9d">LiveRangeUpdater</a>.</p>


<p>Referenced by <a href="#a2b10543d5f749956dd408fd7ebb3c552">join</a>, <a href="#a92d79994c676d5d28a2f765b7e6dfd9d">LiveRangeUpdater</a>, <a href="#aae51d91c7cb4dc1a4ffabbfd1b7be9a1">MergeSegmentsInAsValue</a> and <a href="#a325a4ec9c33a3dead9ff01c9e70fd534">MergeValueInAsValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LiveRange() {#a00e0b8f47bc603934f5954cd117af178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveRange::LiveRange (bool UseSegmentSet=false)</td>
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

<p>Constructs a new <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> object.</p>

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a626da1d721d44f0fb48c580213d4386c">segmentSet</a>.</p>


<p>Referenced by <a href="#ae7eb95d6c78b269fe03ed9c78cf2c33f">assign</a>, <a href="#a5c2526062a291ca7d78fe98bbf66edb7">covers</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a8104005914e3dfed73608d0d8961b822">llvm::LiveInterval::createSubRangeFrom</a>, <a href="#a4c0d1740405c9223c998127f7a8e27a0">find</a>, <a href="#a2b10543d5f749956dd408fd7ebb3c552">join</a>, <a href="#a3d54b859f7cec2b9d7e0e6a06b2f81ad">LiveRange</a>, <a href="#aae51d91c7cb4dc1a4ffabbfd1b7be9a1">MergeSegmentsInAsValue</a>, <a href="#a325a4ec9c33a3dead9ff01c9e70fd534">MergeValueInAsValue</a>, <a href="#aefd338315367c7476ba86002655d3c12">operator&lt;</a>, <a href="#a69ef19ea9e324373a8f6d2cadfd1dad3">overlaps</a>, <a href="#af4d61431580966063160f1cc3fdc1d2e">overlaps</a>, <a href="#a6bd7e5014a81b162dccedd9330615546">overlapsFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/subrange/#a246b06f349a8c6ace86f2a3b080dc58a">llvm::LiveInterval::SubRange::print</a> and <a href="/web-llvm/docs/api/classes/llvm/liveinterval/subrange/#af45ba13fe28f95278e407bf423f3d3c7">llvm::LiveInterval::SubRange::SubRange</a>.</p>

</div>
</div>

### LiveRange() {#a3d54b859f7cec2b9d7e0e6a06b2f81ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveRange::LiveRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; Other, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator)</td>
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

<p>Constructs a new <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> object by copying segments and valnos from another <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a>.</p>

<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp/#ad5d00e1d77644d95847b9bf8da12b759">Allocator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae7eb95d6c78b269fe03ed9c78cf2c33f">assign</a>, <a href="#a00e0b8f47bc603934f5954cd117af178">LiveRange</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;() {#aefd338315367c7476ba86002655d3c12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRange::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; other)</td>
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



<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#a9b4b2c1bb443279588bd6582ad6a86b2">beginIndex</a> and <a href="#a00e0b8f47bc603934f5954cd117af178">LiveRange</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSegment() {#a0b73c8d5ae32ca13dd02ddde86ffd0a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRange::iterator LiveRange::addSegment (<a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the specified <a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a> to this range, merging segments as appropriate.</p>


<p>This returns an iterator to the inserted segment (which may have grown since it was inserted).</p>


<p>Declaration at line 480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-liveinterval-cpp-/calcliverangeutilbase/#a865f64acaeffe1157bb42b90eb532370">anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; ImplT, IteratorT, CollectionT &gt;::addSegment</a>, <a href="#a757fd6afba0f531db70e78e057d147c6">end</a> and <a href="#a626da1d721d44f0fb48c580213d4386c">segmentSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#ab9e855199959852351ae2761ae4302be">llvm::LiveRegMatrix::checkInterference</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#afc6ed60b40c5c63149c23ba327a77c23">llvm::LiveRegMatrix::checkInterferenceLanes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp/#ac46976013d5526a5d1430256b4007b6b">createSegmentsForValues</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>.</p>

</div>
</div>

### advanceTo() {#a60203ad10397a7340f8a0e44ac25368d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::LiveRange::advanceTo (<a href="#a143c1fcb6066cb301f828ec4c18d79f4">iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Pos)</td>
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

<p>advanceTo - Advance the specified iterator to point to the <a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a> containing the specified position, or <a href="#a757fd6afba0f531db70e78e057d147c6">end()</a> if the position is past the end of the range.</p>


<p>If no <a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a> contains this position, but the position is in a hole, this method returns an iterator pointing to the <a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a> immediately after the hole.</p>


<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a757fd6afba0f531db70e78e057d147c6">end</a>, <a href="#aa1bc5510e870a77ebe055b1524d9fd26">endIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6e3886e9084257e74b5db4a8951d36e0">llvm::LiveIntervals::addKillFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/splitanalysis/#a6b3f9616a4146e9a88336afcaf92835e">llvm::SplitAnalysis::countLiveBlocks</a>, <a href="#a5c2526062a291ca7d78fe98bbf66edb7">covers</a> and <a href="#a4e12c0cb71a44b8822c5a35cbbe5c731">isLiveAtIndexes</a>.</p>

</div>
</div>

### advanceTo() {#a3c5f46066435ccdbcc893d51b5a2ad31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::LiveRange::advanceTo (<a href="#a3fc869c7f6d53c3fbb4e572b7821dd05">const_iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Pos)</td>
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



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a757fd6afba0f531db70e78e057d147c6">end</a>, <a href="#aa1bc5510e870a77ebe055b1524d9fd26">endIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### assign() {#ae7eb95d6c78b269fe03ed9c78cf2c33f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveRange::assign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; Other, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator)</td>
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

<p>Copies values numbers and live segments from <span class="doxyComputerOutput">Other</span> into this range.</p>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp/#ad5d00e1d77644d95847b9bf8da12b759">Allocator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3e577095d60431acbf1416db9bb8ec78">createValueCopy</a>, <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#afe8e59ffc86cb1736116e4dc8b86e26f">llvm::LiveRange::Segment::end</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ad989a0c1b26066308798f4d11a0e69df">llvm::VNInfo::id</a>, <a href="#a00e0b8f47bc603934f5954cd117af178">LiveRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a>, <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#a85f7bf79596d84273b5b3b9b490bc2ec">llvm::LiveRange::Segment::start</a>, <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#ac3d1b43d371bc68742232ec51d4a6321">llvm::LiveRange::Segment::valno</a> and <a href="#a9eb4aa155c41e60dff42f4e741a0dcf0">valnos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inlinespiller-cpp-/hoistspillhelper/#a802b241b8cfc1f00f85b1d4da7eeed73">anonymous{InlineSpiller.cpp}::HoistSpillHelper::addToMergeableSpills</a> and <a href="#a3d54b859f7cec2b9d7e0e6a06b2f81ad">LiveRange</a>.</p>

</div>
</div>

### begin() {#a9a5e7c523f12f9f164b786769de1ca47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::LiveRange::begin ()</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6e3886e9084257e74b5db4a8951d36e0">llvm::LiveIntervals::addKillFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a26c99fa2411ae509e9eb030f8aefb4e8">llvm::LiveIntervals::checkRegMaskInterference</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/splitanalysis/#a6b3f9616a4146e9a88336afcaf92835e">llvm::SplitAnalysis::countLiveBlocks</a>, <a href="#a5c2526062a291ca7d78fe98bbf66edb7">covers</a>, <a href="/web-llvm/docs/api/classes/llvm/splitanalysis/#a6b388f6ec0c78d81a2d54efaac443691">llvm::SplitAnalysis::isOriginalEndpoint</a>, <a href="#a2b10543d5f749956dd408fd7ebb3c552">join</a>, <a href="#a92e17326c2170e889ae4390c56878b77">MergeValueNumberInto</a>, <a href="#a69ef19ea9e324373a8f6d2cadfd1dad3">overlaps</a>, <a href="#ad099290f57deba5658668df9518605bb">overlaps</a>, <a href="#a6bd7e5014a81b162dccedd9330615546">overlapsFrom</a>, <a href="#a84d7fba74d57269f494283490fd93439">verify</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a0c8281afcc693674f4ff5c0d2198c770">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRange</a>.</p>

</div>
</div>

### begin() {#a4e1217331523ec239d385d5117b6bfed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::LiveRange::begin ()</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a>.</p>

</div>
</div>

### beginIndex() {#a9b4b2c1bb443279588bd6582ad6a86b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::LiveRange::beginIndex ()</td>
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

<p>beginIndex - Return the lowest numbered slot covered.</p>

<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a66ff664a97cd3c30de7e873335a0c075">empty</a> and <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#abc913cf0bab81b94548cd3c8eeb33117">llvm::LiveIntervals::intervalIsInOneMBB</a>, <a href="#ae17e7d305505cddb57d8093ee934c387">isLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9cd5b6e093b1239921099f108e8eaabb">llvm::LiveInterval::operator&lt;</a>, <a href="#aefd338315367c7476ba86002655d3c12">operator&lt;</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnnsareassign-cpp-/gcnnsareassign/#a98d8aaed2e429cfec371c300cb8244c2">anonymous{GCNNSAReassign.cpp}::GCNNSAReassign::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#ade724427f9c92b975072767cdcfd45ec">llvm::SystemZRegisterInfo::shouldCoalesce</a>.</p>

</div>
</div>

### clear() {#aa1555194b9f176612b04fbd38f49b40d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveRange::clear ()</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a> and <a href="#a9eb4aa155c41e60dff42f4e741a0dcf0">valnos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#ad67d6b7f9f91a2d5852b0f9aebfe542a">llvm::LiveIntervalCalc::calculate</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/query/#ae8729ee921fdf522087d928c9bb38af4">llvm::LiveIntervalUnion::Query::reset</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#ac9e57447ee6550f3ffcb4a432bd3dbab">llvm::RegPressureTracker::reset</a> and <a href="/web-llvm/docs/api/classes/liveintervals/hmeditor/#aa060d1bdca0620ff13d49456dccf9303">llvm::LiveIntervals::HMEditor::updateAllRanges</a>.</p>

</div>
</div>

### containsOneValue() {#ac5db2ca7684625ebf424170b9e98f404}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRange::containsOneValue ()</td>
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



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a9eb4aa155c41e60dff42f4e741a0dcf0">valnos</a>.</p>

</div>
</div>

### containsValue() {#a5c036680263adf0032709cd2e7c3c9c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRange::containsValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * VNI)</td>
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

<p>containsValue - Returns true if VNI belongs to this range.</p>

<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#a93450063916ca1ab1f11bf3304a6ad03">getNumValNums</a>, <a href="#a060100d6b75129bdef5516fac8f89a55">getValNumInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ad989a0c1b26066308798f4d11a0e69df">llvm::VNInfo::id</a>.</p>

</div>
</div>

### covers() {#a5c2526062a291ca7d78fe98bbf66edb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRange::covers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if all segments of the <span class="doxyComputerOutput">Other</span> live range are completely covered by this live range.</p>


<p>Adjacent live ranges do not affect the covering:the liverange [1,5](5,10] covers (3,7].</p>


<p>Declaration at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="#a60203ad10397a7340f8a0e44ac25368d">advanceTo</a>, <a href="#a9a5e7c523f12f9f164b786769de1ca47">begin</a>, <a href="#a66ff664a97cd3c30de7e873335a0c075">empty</a>, <a href="#a757fd6afba0f531db70e78e057d147c6">end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="#a00e0b8f47bc603934f5954cd117af178">LiveRange</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/liveintervals/hmeditor/#aa060d1bdca0620ff13d49456dccf9303">llvm::LiveIntervals::HMEditor::updateAllRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#aa0bc12f607db8709e37e7819756ae9a2">llvm::LiveInterval::verify</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a787f3f4287374d61c5f0657dd83acbb4">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveInterval</a>.</p>

</div>
</div>

### createDeadDef() {#a4258d794235c7a408b3f52e5e4ef7159}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo * LiveRange::createDeadDef (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Def, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#aa750a7f159760b9c378d930deb6a9837">VNInfo::Allocator</a> &amp; VNIAlloc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>createDeadDef - Make sure the range has a value defined at Def.</p>


<p>If one already exists, return it. Otherwise allocate a new value and add liveness for a dead def.</p>


<p>Declaration at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-liveinterval-cpp-/calcliverangeutilbase/#acc30e10385342c3caf14a3bf391bc72b">anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; ImplT, IteratorT, CollectionT &gt;::createDeadDef</a> and <a href="#a626da1d721d44f0fb48c580213d4386c">segmentSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#af5198110c0058e3d60524eecf500ee51">llvm::LiveIntervalCalc::constructMainRangeFromSubranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalcalc-cpp/#a70e2de8376b84c468e8a5762fda4c419">createDeadDef</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>.</p>

</div>
</div>

### createDeadDef() {#adbfe0544c5d2588941c44827f801e64b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo * LiveRange::createDeadDef (<a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * VNI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a def of value <span class="doxyComputerOutput">VNI</span>.</p>


<p>Return <span class="doxyComputerOutput">VNI</span>. If there already exists a definition at VNI-&gt;def, the value defined there must be <span class="doxyComputerOutput">VNI</span>.</p>


<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-liveinterval-cpp-/calcliverangeutilbase/#acc30e10385342c3caf14a3bf391bc72b">anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; ImplT, IteratorT, CollectionT &gt;::createDeadDef</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a> and <a href="#a626da1d721d44f0fb48c580213d4386c">segmentSet</a>.</p>

</div>
</div>

### createValueCopy() {#a3e577095d60431acbf1416db9bb8ec78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo * llvm::LiveRange::createValueCopy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * orig, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#aa750a7f159760b9c378d930deb6a9837">VNInfo::Allocator</a> &amp; VNInfoAllocator)</td>
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

<p>Create a copy of the given value.</p>


<p>The new value will be identical except for the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> number.</p>


<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a9eb4aa155c41e60dff42f4e741a0dcf0">valnos</a>.</p>


<p>Referenced by <a href="#ae7eb95d6c78b269fe03ed9c78cf2c33f">assign</a>.</p>

</div>
</div>

### dump() {#aee80ffb31cdad64c9ef4dbd42e794b68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void LiveRange::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 1044 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

### empty() {#a66ff664a97cd3c30de7e873335a0c075}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRange::empty ()</td>
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



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6e3886e9084257e74b5db4a8951d36e0">llvm::LiveIntervals::addKillFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#ac35fef2aafb20ef4b079d0819394e87d">llvm::RegAllocBase::allocatePhysRegs</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/interference/#a1fe585bae928f642b4e3b2de11d717b4">anonymous{RegAllocPBQP.cpp}::Interference::apply</a>, <a href="#a9b4b2c1bb443279588bd6582ad6a86b2">beginIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#ad67d6b7f9f91a2d5852b0f9aebfe542a">llvm::LiveIntervalCalc::calculate</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#ad064f1e4af82a7f4251434afde29b0b5">llvm::LiveRegMatrix::checkInterference</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#aa2b8ab3df737c2492c7967447e7abac9">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLiveness</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a26c99fa2411ae509e9eb030f8aefb4e8">llvm::LiveIntervals::checkRegMaskInterference</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#ad08d47c88b8af3c45df94d19ccc6e679">llvm::LiveRegMatrix::checkRegUnitInterference</a>, <a href="/web-llvm/docs/api/classes/llvm/splitanalysis/#a6b3f9616a4146e9a88336afcaf92835e">llvm::SplitAnalysis::countLiveBlocks</a>, <a href="#a5c2526062a291ca7d78fe98bbf66edb7">covers</a>, <a href="#aa1bc5510e870a77ebe055b1524d9fd26">endIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#abc913cf0bab81b94548cd3c8eeb33117">llvm::LiveIntervals::intervalIsInOneMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/splitanalysis/#a6b388f6ec0c78d81a2d54efaac443691">llvm::SplitAnalysis::isOriginalEndpoint</a>, <a href="#a2b10543d5f749956dd408fd7ebb3c552">join</a>, <a href="#a69ef19ea9e324373a8f6d2cadfd1dad3">overlaps</a>, <a href="#af4d61431580966063160f1cc3fdc1d2e">overlaps</a>, <a href="#a6bd7e5014a81b162dccedd9330615546">overlapsFrom</a>, <a href="#af62a3dfb9ce9b78c94e7b910a02b28cf">print</a>, <a href="#a63176e601338dbe403676b86e78c7203">removeValNo</a>, <a href="/web-llvm/docs/api/classes/anonymous-stackcoloring-cpp-/stackcoloring/#a97d6b0d6fae6fc47e5e354e6c3382938">anonymous{StackColoring.cpp}::StackColoring::run</a> and <a href="/web-llvm/docs/api/classes/anonymous-gcnnsareassign-cpp-/gcnnsareassign/#a98d8aaed2e429cfec371c300cb8244c2">anonymous{GCNNSAReassign.cpp}::GCNNSAReassign::runOnMachineFunction</a>.</p>

</div>
</div>

### end() {#a757fd6afba0f531db70e78e057d147c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::LiveRange::end ()</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liverangeupdater/#aecdfedd0173a7d04cd7d06d4538dc7bc">llvm::LiveRangeUpdater::add</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6e3886e9084257e74b5db4a8951d36e0">llvm::LiveIntervals::addKillFlags</a>, <a href="#a0b73c8d5ae32ca13dd02ddde86ffd0a2">addSegment</a>, <a href="#a3c5f46066435ccdbcc893d51b5a2ad31">advanceTo</a>, <a href="#a60203ad10397a7340f8a0e44ac25368d">advanceTo</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a26c99fa2411ae509e9eb030f8aefb4e8">llvm::LiveIntervals::checkRegMaskInterference</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/splitanalysis/#a6b3f9616a4146e9a88336afcaf92835e">llvm::SplitAnalysis::countLiveBlocks</a>, <a href="#a5c2526062a291ca7d78fe98bbf66edb7">covers</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a1659a196eabbdd653b9a5d529ccfcb6e">anonymous{RegisterCoalescer.cpp}::JoinVals::eraseInstrs</a>, <a href="#ae6eab1035db7ba328354fa739be090f0">FindSegmentContaining</a>, <a href="#a17255219eb93e6a7f59c1ff32f79f544">FindSegmentContaining</a>, <a href="#ab2f1d4a3bccca2391d35fb1391ebf287">getSegmentContaining</a>, <a href="#a1cde3a312b39ac23baecfce5fee662f7">getSegmentContaining</a>, <a href="#afe7daa73e4cee4edb9f137a8008dfb73">getVNInfoAt</a>, <a href="#a7e1ec6260b229b2f5913405b758bc146">getVNInfoBefore</a>, <a href="#a4e12c0cb71a44b8822c5a35cbbe5c731">isLiveAtIndexes</a>, <a href="/web-llvm/docs/api/classes/llvm/splitanalysis/#a6b388f6ec0c78d81a2d54efaac443691">llvm::SplitAnalysis::isOriginalEndpoint</a>, <a href="#a2b10543d5f749956dd408fd7ebb3c552">join</a>, <a href="#a400c0b88110521ad1de258a7885d9038">liveAt</a>, <a href="#a92e17326c2170e889ae4390c56878b77">MergeValueNumberInto</a>, <a href="#af4d61431580966063160f1cc3fdc1d2e">overlaps</a>, <a href="#ad099290f57deba5658668df9518605bb">overlaps</a>, <a href="#a6bd7e5014a81b162dccedd9330615546">overlapsFrom</a>, <a href="#a6eb0e49d283729a5f8b99d4efa1be7c1">Query</a>, <a href="#ae8bd4b098d55a431c12cfba2a11c94bb">removeSegment</a>, <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/ldvimpl/#ae012de319b29d9d8ef18bf3c2995f679">llvm::LiveDebugVariables::LDVImpl::splitPHIRegister</a>, <a href="#a84d7fba74d57269f494283490fd93439">verify</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a0c8281afcc693674f4ff5c0d2198c770">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRange</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a>.</p>

</div>
</div>

### end() {#a9cf54954ea6cbc5ff4895e3f7f7ca1af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::LiveRange::end ()</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a>.</p>

</div>
</div>

### endIndex() {#aa1bc5510e870a77ebe055b1524d9fd26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::LiveRange::endIndex ()</td>
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

<p>endNumber - return the maximum point of the range of the whole, exclusive.</p>

<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a66ff664a97cd3c30de7e873335a0c075">empty</a> and <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a>.</p>


<p>Referenced by <a href="#a3c5f46066435ccdbcc893d51b5a2ad31">advanceTo</a>, <a href="#a60203ad10397a7340f8a0e44ac25368d">advanceTo</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a26c99fa2411ae509e9eb030f8aefb4e8">llvm::LiveIntervals::checkRegMaskInterference</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="#a847f686bd17a148675f6659c99b96019">expiredAt</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#abc913cf0bab81b94548cd3c8eeb33117">llvm::LiveIntervals::intervalIsInOneMBB</a>, <a href="#ae17e7d305505cddb57d8093ee934c387">isLocal</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnnsareassign-cpp-/gcnnsareassign/#a98d8aaed2e429cfec371c300cb8244c2">anonymous{GCNNSAReassign.cpp}::GCNNSAReassign::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#ade724427f9c92b975072767cdcfd45ec">llvm::SystemZRegisterInfo::shouldCoalesce</a>.</p>

</div>
</div>

### expiredAt() {#a847f686bd17a148675f6659c99b96019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRange::expiredAt (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> index)</td>
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



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#aa1bc5510e870a77ebe055b1524d9fd26">endIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pbqpregalloc-cpp/#ae89b6939795782712cc032bf425fd584">regJustKilledBefore</a>.</p>

</div>
</div>

### extendInBlock() {#a81f9d3d0b958e57c0c0f24982230885d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; VNInfo *, bool &gt; LiveRange::extendInBlock (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt; Undefs, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> StartIdx, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Kill)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to extend a value defined after <span class="doxyComputerOutput">StartIdx</span> to include <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span>.</p>


<p>Both <span class="doxyComputerOutput">StartIdx</span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span> should be in the same basic block. In case of subranges, an extension could be prevented by an explicit "undef" caused by a &lt;def,read-undef&gt; on a non-overlapping lane. The list of location of such "undefs" should be provided in <span class="doxyComputerOutput">Undefs</span>. The return value is a pair: the first element is <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> of the value that was extended (possibly nullptr), the second is a boolean value indicating whether an "undef" was encountered. If this range is live before <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span> in the basic block that starts at <span class="doxyComputerOutput">StartIdx</span>, and there is no intervening "undef", extend it to be live up to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span>, and return the pair {value, false}. If there is no segment before <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span> and there is no "undef" between <span class="doxyComputerOutput">StartIdx</span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span>, return {nullptr, false}. If there is an "undef" before <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span>, return {nullptr, true}.</p>


<p>Declaration at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-liveinterval-cpp-/calcliverangeutilbase/#a410add664cc1a9f7e755a2403d98be2d">anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; ImplT, IteratorT, CollectionT &gt;::extendInBlock</a> and <a href="#a626da1d721d44f0fb48c580213d4386c">segmentSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liverangecalc/#ad445a5028efdf094173a202811f003e3">llvm::LiveRangeCalc::extend</a> and <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a>.</p>

</div>
</div>

### extendInBlock() {#acc063bb08668434f0df98f4230901d10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo * LiveRange::extendInBlock (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> StartIdx, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Kill)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Simplified version of the above "extendInBlock", which assumes that no register lanes are undefined by &lt;def,read-undef&gt; operands.</p>


<p>If this range is live before <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span> in the basic block that starts at <span class="doxyComputerOutput">StartIdx</span>, extend it to be live up to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span>, and return the value. If there is no segment before <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span>, return nullptr.</p>


<p>Declaration at line 504 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-liveinterval-cpp-/calcliverangeutilbase/#a410add664cc1a9f7e755a2403d98be2d">anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; ImplT, IteratorT, CollectionT &gt;::extendInBlock</a> and <a href="#a626da1d721d44f0fb48c580213d4386c">segmentSet</a>.</p>

</div>
</div>

### find() {#afeb00b9049a2391c990df15692caef63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRange::iterator LiveRange::find (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>find - Return an iterator pointing to the first segment that ends after Pos, or <a href="#a757fd6afba0f531db70e78e057d147c6">end()</a>.</p>


<p>This is the same as advanceTo(begin(), Pos), but faster when searching large ranges.</p>


<p>If Pos is contained in a <a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a>, that segment is returned. If Pos is in a hole, the following <a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a> is returned. If Pos is beyond endIndex, <a href="#a757fd6afba0f531db70e78e057d147c6">end()</a> is returned.</p>


<p>Declaration at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="#afeb00b9049a2391c990df15692caef63">find</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a327a399b9f6ef414a29ddeffba934d26">llvm::partition_point</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6e3886e9084257e74b5db4a8951d36e0">llvm::LiveIntervals::addKillFlags</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a1659a196eabbdd653b9a5d529ccfcb6e">anonymous{RegisterCoalescer.cpp}::JoinVals::eraseInstrs</a>, <a href="#afeb00b9049a2391c990df15692caef63">find</a>, <a href="#a4c0d1740405c9223c998127f7a8e27a0">find</a>, <a href="#ae6eab1035db7ba328354fa739be090f0">FindSegmentContaining</a>, <a href="#a17255219eb93e6a7f59c1ff32f79f544">FindSegmentContaining</a>, <a href="#a4e12c0cb71a44b8822c5a35cbbe5c731">isLiveAtIndexes</a>, <a href="/web-llvm/docs/api/classes/llvm/splitanalysis/#a6b388f6ec0c78d81a2d54efaac443691">llvm::SplitAnalysis::isOriginalEndpoint</a>, <a href="#a400c0b88110521ad1de258a7885d9038">liveAt</a>, <a href="#af4d61431580966063160f1cc3fdc1d2e">overlaps</a>, <a href="#a6eb0e49d283729a5f8b99d4efa1be7c1">Query</a>, <a href="#ae8bd4b098d55a431c12cfba2a11c94bb">removeSegment</a> and <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/ldvimpl/#ae012de319b29d9d8ef18bf3c2995f679">llvm::LiveDebugVariables::LDVImpl::splitPHIRegister</a>.</p>

</div>
</div>

### find() {#a4c0d1740405c9223c998127f7a8e27a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::LiveRange::find (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Pos)</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#afeb00b9049a2391c990df15692caef63">find</a> and <a href="#a00e0b8f47bc603934f5954cd117af178">LiveRange</a>.</p>

</div>
</div>

### findIndexesLiveAt() {#a76906231c2b079d1b909ddae48ef6e14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Range, typename OutputIt&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRange::findIndexesLiveAt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> &amp;&amp; R, OutputIt O)</td>
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

<p>Stores indexes from the input index sequence R at which this <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> is live to the output O iterator.</p>


<p>R is a range of <em>ascending sorted</em> <em>random</em> access iterators to the input indexes. Indexes stored at O are ascending sorted so it can be used directly in the subsequent search (for example for subranges). Returns true if found at least one index.</p>


<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a864e071375fea140a5441a243372ff81">llvm::is_sorted</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a>.</p>

</div>
</div>

### FindSegmentContaining() {#ae6eab1035db7ba328354fa739be090f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::LiveRange::FindSegmentContaining (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx)</td>
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

<p>Return an iterator to the segment that contains the specified index, or <a href="#a757fd6afba0f531db70e78e057d147c6">end()</a> if there is none.</p>

<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#a757fd6afba0f531db70e78e057d147c6">end</a>, <a href="#afeb00b9049a2391c990df15692caef63">find</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#ab2f1d4a3bccca2391d35fb1391ebf287">getSegmentContaining</a>, <a href="#a1cde3a312b39ac23baecfce5fee662f7">getSegmentContaining</a>, <a href="#afe7daa73e4cee4edb9f137a8008dfb73">getVNInfoAt</a>, <a href="#a7e1ec6260b229b2f5913405b758bc146">getVNInfoBefore</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#ad7ed3a1e19bd5b3c4ea5a74413371900">moveAndTeeForMultiUse</a>.</p>

</div>
</div>

### FindSegmentContaining() {#a17255219eb93e6a7f59c1ff32f79f544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::LiveRange::FindSegmentContaining (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx)</td>
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



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#a757fd6afba0f531db70e78e057d147c6">end</a>, <a href="#afeb00b9049a2391c990df15692caef63">find</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### flushSegmentSet() {#afb60ddfb929ff4265623f2aa4f39a83e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRange::flushSegmentSet ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flush segment set into the regular segment vector.</p>


<p>The method is to be called after the live range has been created, if use of the segment set was activated in the constructor of the live range.</p>


<p>Declaration at line 619 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 793 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a>, <a href="#a626da1d721d44f0fb48c580213d4386c">segmentSet</a> and <a href="#a84d7fba74d57269f494283490fd93439">verify</a>.</p>

</div>
</div>

### getNextValue() {#ae609c36884142cbc16989cdf3bec4dad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo * llvm::LiveRange::getNextValue (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Def, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#aa750a7f159760b9c378d930deb6a9837">VNInfo::Allocator</a> &amp; VNInfoAllocator)</td>
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

<p>getNextValue - Create a new value number and return it.</p>


<p><span class="doxyComputerOutput">Def</span> is the index of instruction that defines the value number.</p>


<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a9eb4aa155c41e60dff42f4e741a0dcf0">valnos</a>.</p>

</div>
</div>

### getNumValNums() {#a93450063916ca1ab1f11bf3304a6ad03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LiveRange::getNumValNums ()</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a9eb4aa155c41e60dff42f4e741a0dcf0">valnos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#ab075ccec6878e16419fca5e423c7ddad">llvm::ConnectedVNInfoEqClasses::Classify</a>, <a href="#a5c036680263adf0032709cd2e7c3c9c3">containsValue</a>, <a href="#a2b10543d5f749956dd408fd7ebb3c552">join</a>, <a href="#af62a3dfb9ce9b78c94e7b910a02b28cf">print</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a>.</p>

</div>
</div>

### getSegmentContaining() {#a1cde3a312b39ac23baecfce5fee662f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Segment * llvm::LiveRange::getSegmentContaining (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx)</td>
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

<p>Return the segment that contains the specified index, or null if there is none.</p>

<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#a757fd6afba0f531db70e78e057d147c6">end</a>, <a href="#ae6eab1035db7ba328354fa739be090f0">FindSegmentContaining</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf40b35a88eb365bc4f4047a03bb1ece">llvm::X86InstrInfo::classifyLEAReg</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a061f47e0bf17eed5f4fb190668a20858">llvm::RISCVInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a1066c542d3ccd99d3e740ad91aed49de">anonymous{LiveDebugVariables.cpp}::UserValue::extendDef</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#ad8b14ec0777ac642d3403470e0753533">llvm::RegPressureTracker::getLiveThroughAt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp/#a5d107951e5df0e107a1269647a484f2f">removeDeadSegment</a> and <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a42083019e0bdb164e55da49ab9f4d717">llvm::LiveIntervals::shrinkToUses</a>.</p>

</div>
</div>

### getSegmentContaining() {#ab2f1d4a3bccca2391d35fb1391ebf287}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Segment * llvm::LiveRange::getSegmentContaining (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx)</td>
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

<p>Return the live segment that contains the specified index, or null if there is none.</p>

<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#a757fd6afba0f531db70e78e057d147c6">end</a>, <a href="#ae6eab1035db7ba328354fa739be090f0">FindSegmentContaining</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getValNumInfo() {#a060100d6b75129bdef5516fac8f89a55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo * llvm::LiveRange::getValNumInfo (unsigned ValNo)</td>
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

<p>getValNumInfo - Returns pointer to the specified val#.</p>

<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a9eb4aa155c41e60dff42f4e741a0dcf0">valnos</a>.</p>


<p>Referenced by <a href="#a5c036680263adf0032709cd2e7c3c9c3">containsValue</a>, <a href="#a2b10543d5f749956dd408fd7ebb3c552">join</a>, <a href="#af62a3dfb9ce9b78c94e7b910a02b28cf">print</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a>.</p>

</div>
</div>

### getValNumInfo() {#a9b4b1397b800d411d5e89bd09cde5b2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VNInfo * llvm::LiveRange::getValNumInfo (unsigned ValNo)</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a9eb4aa155c41e60dff42f4e741a0dcf0">valnos</a>.</p>

</div>
</div>

### getVNInfoAt() {#afe7daa73e4cee4edb9f137a8008dfb73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo * llvm::LiveRange::getVNInfoAt (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx)</td>
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

<p>getVNInfoAt - Return the <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> that is live at Idx, or NULL.</p>

<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#a757fd6afba0f531db70e78e057d147c6">end</a>, <a href="#ae6eab1035db7ba328354fa739be090f0">FindSegmentContaining</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#ac0a0c1bb8dc69992e326ead7f5faf286">anonymous{LiveDebugVariables.cpp}::UserValue::addDefsFromCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#ad930b47a8263b4fcc37e6209e387b897">llvm::LiveRangeEdit::allUsesAvailableAt</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a4d40a357c884c36942205713e7bf3244">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLivenessAtDef</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a5addc8b01ca0cce0a572d5fe3ef86654">anonymous{LiveDebugVariables.cpp}::UserValue::computeIntervals</a>, <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#a5d79e4d110e15056182588d168ac6b2f">llvm::ConnectedVNInfoEqClasses::Distribute</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a96cdbab4e65a936880975a58e0dde922">llvm::SIRegisterInfo::findReachingDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a881b49c730ea9d71536df2bf6847f4d0">hasOneNonDBGUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#ad7ed3a1e19bd5b3c4ea5a74413371900">moveAndTeeForMultiUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ae9f0ff5f13bf6cb4567247a39f7756e3">llvm::LiveIntervals::removePhysRegDefAt</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac332ca27d85adc8d21edd708be55dfe3">llvm::LiveIntervals::removeVRegDefAt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymemintrinsicresults-cpp/#abd14b1720a6213a3a1251afdbd671c62">replaceDominatedUses</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a38cfbca05868eacdc315641e8ed182d4">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeValue</a>.</p>

</div>
</div>

### getVNInfoBefore() {#a7e1ec6260b229b2f5913405b758bc146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo * llvm::LiveRange::getVNInfoBefore (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx)</td>
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

<p>getVNInfoBefore - Return the <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> that is live up to but not necessarily including Idx, or NULL.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> this to find the reaching def used by an instruction at this <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> position.</p>


<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#a757fd6afba0f531db70e78e057d147c6">end</a>, <a href="#ae6eab1035db7ba328354fa739be090f0">FindSegmentContaining</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ac832da130f4d71a4533a69d98315fb19">llvm::SlotIndex::getPrevSlot</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#ab075ccec6878e16419fca5e423c7ddad">llvm::ConnectedVNInfoEqClasses::Classify</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a7bb19d3e5b68421bc97c3c4b524e7888">llvm::ScheduleDAGMILive::computeCyclicCriticalPath</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a43d14ce45443d02b378ac4aab0dec9d4">getVRegDef</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a1b6e5f6033c80dff3f9b4c6fb40499c2">llvm::LiveIntervals::hasPHIKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#adbc2dabbd1e76342acf894af01937c8a">oneUseDominatesOtherUses</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a91251ec06d557b21578095955b7b7fa7">llvm::ScheduleDAGMILive::updatePressureDiffs</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a>.</p>

</div>
</div>

### hasAtLeastOneValue() {#ace8519cea9fa2e688a052df670afe41e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRange::hasAtLeastOneValue ()</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a9eb4aa155c41e60dff42f4e741a0dcf0">valnos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a0d7e0d23a0453390a4c1e9a61afccdca">llvm::LiveIntervals::repairIntervalsInRange</a>.</p>

</div>
</div>

### isLiveAtIndexes() {#a4e12c0cb71a44b8822c5a35cbbe5c731}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRange::isLiveAtIndexes (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt; Slots)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 598 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 803 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="#a60203ad10397a7340f8a0e44ac25368d">advanceTo</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="#a757fd6afba0f531db70e78e057d147c6">end</a> and <a href="#afeb00b9049a2391c990df15692caef63">find</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-stackcoloring-cpp-/stackcoloring/#a97d6b0d6fae6fc47e5e354e6c3382938">anonymous{StackColoring.cpp}::StackColoring::run</a> and <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a137403167e291d2e011441ce02d51898">llvm::VirtRegAuxInfo::weightCalcHelper</a>.</p>

</div>
</div>

### isLocal() {#ae17e7d305505cddb57d8093ee934c387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRange::isLocal (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Start, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> End)</td>
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

<p>True iff this segment is a single segment that lies between the specified boundaries, exclusively.</p>


<p>Vregs live across a backedge are not considered local. The boundaries are expected to lie within an extended basic block, so vregs that are not live out should contain no holes.</p>


<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#a9b4b2c1bb443279588bd6582ad6a86b2">beginIndex</a>, <a href="#aa1bc5510e870a77ebe055b1524d9fd26">endIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a9ee9e2030e830feecf0a2c27c6f3c09f">llvm::SlotIndex::getBoundaryIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>.</p>

</div>
</div>

### isUndefIn() {#ab78d2b1052d3be8da6bba690bce9336f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRange::isUndefIn (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt; Undefs, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Begin, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> End)</td>
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

<p>Returns true if there is an explicit "undef" between <span class="doxyComputerOutput">Begin</span> <span class="doxyComputerOutput">End</span>.</p>

<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>.</p>

</div>
</div>

### isZeroLength() {#a61f530037a29a00a48799b14104a68d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRange::isZeroLength (<a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> * Indexes)</td>
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

<p>Returns true if the live range is zero length, i.e.</p>


<p>no live segments span instructions. It doesn't pay to spill such a range.</p>


<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/slotindex/#aa94e57689dd16c1c4de909511f1b2ea8">llvm::SlotIndex::getBaseIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#a7ac607fdc1b84333c84cc74903c352a4">llvm::SlotIndexes::getNextNonNullIndex</a> and <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a137403167e291d2e011441ce02d51898">llvm::VirtRegAuxInfo::weightCalcHelper</a>.</p>

</div>
</div>

### join() {#a2b10543d5f749956dd408fd7ebb3c552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRange::join (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; Other, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int * ValNoAssignments, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int * RHSValNoAssignments, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * &gt; &amp; NewVNInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>join - Join two live ranges (this, and other) together.</p>


<p>This applies mappings to the value numbers in the LHS/RHS ranges as specified. If the ranges are not joinable, this aborts.</p>


<p>Declaration at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liverangeupdater/#aecdfedd0173a7d04cd7d06d4538dc7bc">llvm::LiveRangeUpdater::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9a5e7c523f12f9f164b786769de1ca47">begin</a>, <a href="#a66ff664a97cd3c30de7e873335a0c075">empty</a>, <a href="#a757fd6afba0f531db70e78e057d147c6">end</a>, <a href="#a93450063916ca1ab1f11bf3304a6ad03">getNumValNums</a>, <a href="#a060100d6b75129bdef5516fac8f89a55">getValNumInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ad989a0c1b26066308798f4d11a0e69df">llvm::VNInfo::id</a>, <a href="#a00e0b8f47bc603934f5954cd117af178">LiveRange</a>, <a href="#a92d79994c676d5d28a2f765b7e6dfd9d">LiveRangeUpdater</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#ac3d1b43d371bc68742232ec51d4a6321">llvm::LiveRange::Segment::valno</a>, <a href="#a9eb4aa155c41e60dff42f4e741a0dcf0">valnos</a> and <a href="#a84d7fba74d57269f494283490fd93439">verify</a>.</p>

</div>
</div>

### liveAt() {#a400c0b88110521ad1de258a7885d9038}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRange::liveAt (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> index)</td>
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



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#a757fd6afba0f531db70e78e057d147c6">end</a> and <a href="#afeb00b9049a2391c990df15692caef63">find</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a222d514d23098e92ecbd53e36b3c5084">llvm::GCNDownwardRPTracker::advanceBeforeNext</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a563b8ed395be414427b56ade51afb784">llvm::getLiveLaneMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a9a34eb3ae4410e27d2af2562436e6734">getLiveLanesAt</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a9551d47c4a9bc95eec03d02f11dfef3b">llvm::RegPressureTracker::getLiveLanesAt</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#af47f5ea0e633ac96943c6937e724ae4a">llvm::LiveIntervals::isLiveInToMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ae7bb8fbc54f0001e556e3ab13a5b6ba5">llvm::LiveIntervals::isLiveOutOfMBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a2281004fe6686c5e3700682448b77f90">rematerializeCheapDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymemintrinsicresults-cpp/#abd14b1720a6213a3a1251afdbd671c62">replaceDominatedUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-siformmemoryclauses-cpp-/siformmemoryclauses/#a3b412b093194b8e66d1d42d1cc79d692">anonymous{SIFormMemoryClauses.cpp}::SIFormMemoryClauses::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/renameindependentsubregs-cpp/#ad2f4f6c15691383c1db014fa225c6c36">subRangeLiveAt</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### MergeSegmentsInAsValue() {#aae51d91c7cb4dc1a4ffabbfd1b7be9a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRange::MergeSegmentsInAsValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * LHSValNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge all of the live segments of a specific val# in RHS into this live range as the specified value number.</p>


<p>Merge all of the segments in RHS into this live range as the specified value number.</p>


<p>The segments in RHS are allowed to overlap with segments in the current range, it will replace the value numbers of the overlaped live segments with the specified value number.</p>


<p>The segments in RHS are allowed to overlap with segments in the current range, but only if the overlapping segments have the specified value number.</p>


<p>Declaration at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 713 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liverangeupdater/#aecdfedd0173a7d04cd7d06d4538dc7bc">llvm::LiveRangeUpdater::add</a>, <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#afe8e59ffc86cb1736116e4dc8b86e26f">llvm::LiveRange::Segment::end</a>, <a href="#a00e0b8f47bc603934f5954cd117af178">LiveRange</a>, <a href="#a92d79994c676d5d28a2f765b7e6dfd9d">LiveRangeUpdater</a> and <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#a85f7bf79596d84273b5b3b9b490bc2ec">llvm::LiveRange::Segment::start</a>.</p>

</div>
</div>

### MergeValueInAsValue() {#a325a4ec9c33a3dead9ff01c9e70fd534}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRange::MergeValueInAsValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * RHSValNo, <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * LHSValNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MergeValueInAsValue - Merge all of the segments of a specific val# in RHS into this live range as the specified value number.</p>


<p>MergeValueInAsValue - Merge all of the live segments of a specific val# in RHS into this live range as the specified value number.</p>


<p>The segments in RHS are allowed to overlap with segments in the current range, but only if the overlapping segments have the specified value number.</p>


<p>The segments in RHS are allowed to overlap with segments in the current range, it will replace the value numbers of the overlaped segments with the specified value number.</p>


<p>Declaration at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liverangeupdater/#aecdfedd0173a7d04cd7d06d4538dc7bc">llvm::LiveRangeUpdater::add</a>, <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#afe8e59ffc86cb1736116e4dc8b86e26f">llvm::LiveRange::Segment::end</a>, <a href="#a00e0b8f47bc603934f5954cd117af178">LiveRange</a>, <a href="#a92d79994c676d5d28a2f765b7e6dfd9d">LiveRangeUpdater</a>, <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#a85f7bf79596d84273b5b3b9b490bc2ec">llvm::LiveRange::Segment::start</a> and <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#ac3d1b43d371bc68742232ec51d4a6321">llvm::LiveRange::Segment::valno</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inlinespiller-cpp-/hoistspillhelper/#a597bb5d7ef9a22f44dbe867d8eaa7fd6">anonymous{InlineSpiller.cpp}::HoistSpillHelper::hoistAllSpills</a>.</p>

</div>
</div>

### MergeValueNumberInto() {#a92e17326c2170e889ae4390c56878b77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo * LiveRange::MergeValueNumberInto (<a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * V2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MergeValueNumberInto - This method is called when two value numbers are found to be equivalent.</p>


<p>MergeValueNumberInto - This method is called when two value nubmers are found to be equivalent.</p>


<p>This eliminates V1, replacing all segments with the V1 value number with the V2 value number. This can cause merging of V1/V2 values numbers and compaction of the value space.</p>


<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 738 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9a5e7c523f12f9f164b786769de1ca47">begin</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#a075960d0135f97b5df867eeaf30215f2">llvm::VNInfo::copyFrom</a>, <a href="#a757fd6afba0f531db70e78e057d147c6">end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ad989a0c1b26066308798f4d11a0e69df">llvm::VNInfo::id</a>, <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### overlaps() {#a69ef19ea9e324373a8f6d2cadfd1dad3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRange::overlaps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; other)</td>
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

<p>overlaps - Return true if the intersection of the two live ranges is not empty.</p>

<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="#a9a5e7c523f12f9f164b786769de1ca47">begin</a>, <a href="#a66ff664a97cd3c30de7e873335a0c075">empty</a>, <a href="#a00e0b8f47bc603934f5954cd117af178">LiveRange</a> and <a href="#a6bd7e5014a81b162dccedd9330615546">overlapsFrom</a>.</p>

</div>
</div>

### overlaps() {#af4d61431580966063160f1cc3fdc1d2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRange::overlaps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; Other, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/coalescerpair">CoalescerPair</a> &amp; CP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> &amp; Indexes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>overlaps - Return true if the two ranges have overlapping segments that are not coalescable according to CP.</p>


<p>Overlapping segments where one range is defined by a coalescable copy are allowed.</p>


<p>Declaration at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a66ff664a97cd3c30de7e873335a0c075">empty</a>, <a href="#a757fd6afba0f531db70e78e057d147c6">end</a>, <a href="#afeb00b9049a2391c990df15692caef63">find</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#af454bfc85311cf45162476f6b4e5dee8">llvm::SlotIndexes::getInstructionFromIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a00e0b8f47bc603934f5954cd117af178">LiveRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### overlaps() {#ad099290f57deba5658668df9518605bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRange::overlaps (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Start, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>overlaps - Return true if the live range overlaps an interval specified by [Start, End).</p>

<p>Declaration at line 464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9a5e7c523f12f9f164b786769de1ca47">begin</a>, <a href="#a757fd6afba0f531db70e78e057d147c6">end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>.</p>

</div>
</div>

### overlapsFrom() {#a6bd7e5014a81b162dccedd9330615546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRange::overlapsFrom (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; Other, <a href="#a3fc869c7f6d53c3fbb4e572b7821dd05">const_iterator</a> StartPos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>overlapsFrom - Return true if the intersection of the two live ranges is not empty.</p>


<p>The specified iterator is a hint that we can begin scanning the Other range starting at I.</p>


<p>Declaration at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9a5e7c523f12f9f164b786769de1ca47">begin</a>, <a href="#a66ff664a97cd3c30de7e873335a0c075">empty</a>, <a href="#a757fd6afba0f531db70e78e057d147c6">end</a>, <a href="#a00e0b8f47bc603934f5954cd117af178">LiveRange</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#a69ef19ea9e324373a8f6d2cadfd1dad3">overlaps</a>.</p>

</div>
</div>

### print() {#af62a3dfb9ce9b78c94e7b910a02b28cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRange::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 658 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 999 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="#a66ff664a97cd3c30de7e873335a0c075">empty</a>, <a href="#a93450063916ca1ab1f11bf3304a6ad03">getNumValNums</a>, <a href="#a060100d6b75129bdef5516fac8f89a55">getValNumInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae72fbcf51be7574c84817cde814df07e">llvm::VNInfo::isPHIDef</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ab72366fd538f240cbb53dac39368cdfc">llvm::VNInfo::isUnused</a>, <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a>, <a href="#a5fb099e2afb74f4c922f32894b30b279">vni_begin</a> and <a href="#aca7b7d6f329690e6bd5b5e1c83db7c1e">vni_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liverangeupdater/#a99dba5518021b799c8eb62367b225919">llvm::LiveRangeUpdater::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad36d30a891ef34e6e5320033a8413150">llvm::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#ab2b5b2c40dff9929de640b4522b97714">llvm::LiveInterval::print</a>.</p>

</div>
</div>

### Query() {#a6eb0e49d283729a5f8b99d4efa1be7c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveQueryResult llvm::LiveRange::Query (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx)</td>
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

<p>Query Liveness at Idx.</p>


<p>The sub-instruction slot of Idx doesn't matter, only the instruction it refers to is considered.</p>


<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a757fd6afba0f531db70e78e057d147c6">end</a>, <a href="#afeb00b9049a2391c990df15692caef63">find</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#aa94e57689dd16c1c4de909511f1b2ea8">llvm::SlotIndex::getBaseIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a19695ead28a0fbdcea66c6253aebc44f">llvm::SlotIndex::isEarlierInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a0b73244049319d841fd11a238f35b5d1">llvm::SlotIndex::isSameInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a4d40a357c884c36942205713e7bf3244">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLivenessAtDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a185de6f70a894f044801931c4956150d">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLivenessAtUse</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a7bb19d3e5b68421bc97c3c4b524e7888">llvm::ScheduleDAGMILive::computeCyclicCriticalPath</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#acee6dacd4d30da478f3ad67f7fc27142">llvm::RegisterOperands::detectDeadDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#a5d79e4d110e15056182588d168ac6b2f">llvm::ConnectedVNInfoEqClasses::Distribute</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#aa1a6fbdf0a3311c7b9602dd67e46fef9">llvm::LiveIntervals::handleMoveIntoNewBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a881b49c730ea9d71536df2bf6847f4d0">hasOneNonDBGUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#ab52ab15874c8fda9ecc6bae0bcd42444">isDefBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#a557a8b6ef8191908ae0c534f76b9f782">isDefInSubRange</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a9e4d1b2ff6c306576d8ffa9922fa8ba3">llvm::VirtRegAuxInfo::isRematerializable</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a94cf1c59ca73ea330872deb639013cb9">llvm::LiveIntervals::pruneValue</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac7446b2819c44bf459763351b5bcc29b">llvm::LiveIntervals::shrinkToUses</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a42083019e0bdb164e55da49ab9f4d717">llvm::LiveIntervals::shrinkToUses</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a91251ec06d557b21578095955b7b7fa7">llvm::ScheduleDAGMILive::updatePressureDiffs</a>.</p>

</div>
</div>

### removeSegment() {#ae8bd4b098d55a431c12cfba2a11c94bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRange::removeSegment (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Start, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> End, bool RemoveDeadValNo=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the specified interval from this live range.</p>


<p>Does nothing if interval is not part of this live range. Note that the interval must be within a single <a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a> in its entirety.</p>


<p>Declaration at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a757fd6afba0f531db70e78e057d147c6">end</a>, <a href="#afeb00b9049a2391c990df15692caef63">find</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aea1f4a9101ccc20faa0e67fdef1e5086">removeValNoIfDead</a> and <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a9317ef8571eae8a49591ed8912c4d102">moveForSingleUse</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a94cf1c59ca73ea330872deb639013cb9">llvm::LiveIntervals::pruneValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp/#a5d107951e5df0e107a1269647a484f2f">removeDeadSegment</a>, <a href="#aedd2a145f951aba2dc5ee491dfdbfceb">removeSegment</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a42083019e0bdb164e55da49ab9f4d717">llvm::LiveIntervals::shrinkToUses</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>.</p>

</div>
</div>

### removeSegment() {#aedd2a145f951aba2dc5ee491dfdbfceb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveRange::removeSegment (<a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a> S, bool RemoveDeadValNo=false)</td>
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



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#afe8e59ffc86cb1736116e4dc8b86e26f">llvm::LiveRange::Segment::end</a>, <a href="#ae8bd4b098d55a431c12cfba2a11c94bb">removeSegment</a> and <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#a85f7bf79596d84273b5b3b9b490bc2ec">llvm::LiveRange::Segment::start</a>.</p>

</div>
</div>

### removeSegment() {#acea134ac1ed40b2215b8a1065a176d96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRange::iterator LiveRange::removeSegment (<a href="#a143c1fcb6066cb301f828ec4c18d79f4">iterator</a> I, bool RemoveDeadValNo=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove segment pointed to by iterator <span class="doxyComputerOutput">I</span> from this range.</p>

<p>Declaration at line 534 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aea1f4a9101ccc20faa0e67fdef1e5086">removeValNoIfDead</a> and <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a>.</p>

</div>
</div>

### removeValNo() {#a63176e601338dbe403676b86e78c7203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRange::removeValNo (<a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * ValNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removeValNo - Remove all the segments defined by the specified value#.</p>


<p>Also remove the value# from value# list.</p>


<p>Declaration at line 583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="#a66ff664a97cd3c30de7e873335a0c075">empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a7de5a04920954ac964059cfc428ad">llvm::erase_if</a>, <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a> and <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#ac3d1b43d371bc68742232ec51d4a6321">llvm::LiveRange::Segment::valno</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ae9f0ff5f13bf6cb4567247a39f7756e3">llvm::LiveIntervals::removePhysRegDefAt</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac332ca27d85adc8d21edd708be55dfe3">llvm::LiveIntervals::removeVRegDefAt</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp/#aeb309e71b02f8298a437ec465645fe99">stripValuesNotDefiningMask</a>.</p>

</div>
</div>

### removeValNoIfDead() {#aea1f4a9101ccc20faa0e67fdef1e5086}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRange::removeValNoIfDead (<a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * ValNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark <span class="doxyComputerOutput">ValNo</span> for deletion if no segments in this range use it.</p>

<p>Declaration at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 614 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a> and <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#ac3d1b43d371bc68742232ec51d4a6321">llvm::LiveRange::Segment::valno</a>.</p>


<p>Referenced by <a href="#acea134ac1ed40b2215b8a1065a176d96">removeSegment</a> and <a href="#ae8bd4b098d55a431c12cfba2a11c94bb">removeSegment</a>.</p>

</div>
</div>

### RenumberValues() {#a687cab1756967efc8f0ce66105531755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRange::RenumberValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RenumberValues - Renumber all values in order of appearance and remove unused values.</p>


<p>RenumberValues - Renumber all values in order of appearance and delete the remaining unused values.</p>


<p>Declaration at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ad989a0c1b26066308798f4d11a0e69df">llvm::VNInfo::id</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ab72366fd538f240cbb53dac39368cdfc">llvm::VNInfo::isUnused</a>, <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a> and <a href="#a9eb4aa155c41e60dff42f4e741a0dcf0">valnos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#add47e6d974ce584ea3fa3fc80ee34259">llvm::LiveRangeEdit::eliminateDeadDefs</a> and <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a98fa413da7a0053bf635119e74970219">llvm::SplitEditor::finish</a>.</p>

</div>
</div>

### size() {#ac80c04546dae620bf4dca9d6137d6a61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::LiveRange::size ()</td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a1ee36ec6dd22cf058ebb96f2a7ef0108">llvm::TargetRegisterInfo::shouldRegionSplitForVirtReg</a>.</p>

</div>
</div>

### verify() {#a84d7fba74d57269f494283490fd93439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRange::verify ()</td>
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

<p>Walk the range and assert if any invariants fail to hold.</p>


<p>Note that this is a no-op when asserts are disabled.</p>


<p>Declaration at line 667 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 1058 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="#a9a5e7c523f12f9f164b786769de1ca47">begin</a>, <a href="#a757fd6afba0f531db70e78e057d147c6">end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a9eb4aa155c41e60dff42f4e741a0dcf0">valnos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a4d40a357c884c36942205713e7bf3244">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLivenessAtDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a185de6f70a894f044801931c4956150d">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLivenessAtUse</a>, <a href="#afb60ddfb929ff4265623f2aa4f39a83e">flushSegmentSet</a>, <a href="#a2b10543d5f749956dd408fd7ebb3c552">join</a> and <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#aa0bc12f607db8709e37e7819756ae9a2">llvm::LiveInterval::verify</a>.</p>

</div>
</div>

### vni\_begin() {#a5fb099e2afb74f4c922f32894b30b279}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vni_iterator llvm::LiveRange::vni_begin ()</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a9eb4aa155c41e60dff42f4e741a0dcf0">valnos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a9e4d1b2ff6c306576d8ffa9922fa8ba3">llvm::VirtRegAuxInfo::isRematerializable</a>, <a href="#af62a3dfb9ce9b78c94e7b910a02b28cf">print</a>, <a href="#a3524c5585af87a1c875f60fe849d241f">vnis</a> and <a href="#a01f43c892ce74d401d4d7380fc2d176c">vnis</a>.</p>

</div>
</div>

### vni\_begin() {#a64661635fc0bf729d6e39b2dfa8a965e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_vni_iterator llvm::LiveRange::vni_begin ()</td>
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



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a9eb4aa155c41e60dff42f4e741a0dcf0">valnos</a>.</p>

</div>
</div>

### vni\_end() {#aca7b7d6f329690e6bd5b5e1c83db7c1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vni_iterator llvm::LiveRange::vni_end ()</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a9eb4aa155c41e60dff42f4e741a0dcf0">valnos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a9e4d1b2ff6c306576d8ffa9922fa8ba3">llvm::VirtRegAuxInfo::isRematerializable</a>, <a href="#af62a3dfb9ce9b78c94e7b910a02b28cf">print</a>, <a href="#a3524c5585af87a1c875f60fe849d241f">vnis</a> and <a href="#a01f43c892ce74d401d4d7380fc2d176c">vnis</a>.</p>

</div>
</div>

### vni\_end() {#a812e5c85e99795c3985efdd87946edf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_vni_iterator llvm::LiveRange::vni_end ()</td>
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



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Reference <a href="#a9eb4aa155c41e60dff42f4e741a0dcf0">valnos</a>.</p>

</div>
</div>

### vnis() {#a3524c5585af87a1c875f60fe849d241f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; vni_iterator &gt; llvm::LiveRange::vnis ()</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a5fb099e2afb74f4c922f32894b30b279">vni_begin</a> and <a href="#aca7b7d6f329690e6bd5b5e1c83db7c1e">vni_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac7446b2819c44bf459763351b5bcc29b">llvm::LiveIntervals::shrinkToUses</a> and <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a42083019e0bdb164e55da49ab9f4d717">llvm::LiveIntervals::shrinkToUses</a>.</p>

</div>
</div>

### vnis() {#a01f43c892ce74d401d4d7380fc2d176c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_vni_iterator &gt; llvm::LiveRange::vnis ()</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a5fb099e2afb74f4c922f32894b30b279">vni_begin</a> and <a href="#aca7b7d6f329690e6bd5b5e1c83db7c1e">vni_end</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### append() {#a8fc86da696e49b67827c940045434c4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRange::append (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/liverange/segment">LiveRange::Segment</a> S)</td>
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

<p>Append a segment to the list of segments.</p>

<p>Declaration at line 672 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9c628b400be67b6adb4fa07e84a96a82">segments</a> and <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#a85f7bf79596d84273b5b3b9b490bc2ec">llvm::LiveRange::Segment::start</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addSegmentToSet() {#aa34a887f9079608a6d196af2389b9683}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRange::addSegmentToSet (<a href="/web-llvm/docs/api/structs/llvm/liverange/segment">Segment</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>

</div>
</div>

### markValNoForDeletion() {#a70f57fbad3e7df42d40124e64583577a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRange::markValNoForDeletion (<a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * ValNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ValNo is dead, remove it.</p>


<p>If it is the largest value number, just nuke it (and any other deleted values neighboring it), otherwise mark it as ~1U so it can be nuked later.</p>


<p>Declaration at line 677 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>, definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### segments {#a9c628b400be67b6adb4fa07e84a96a82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Segments llvm::LiveRange::segments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="#a8fc86da696e49b67827c940045434c4b">append</a>, <a href="#ae7eb95d6c78b269fe03ed9c78cf2c33f">assign</a>, <a href="#a9a5e7c523f12f9f164b786769de1ca47">begin</a>, <a href="#a4e1217331523ec239d385d5117b6bfed">begin</a>, <a href="#a9b4b2c1bb443279588bd6582ad6a86b2">beginIndex</a>, <a href="#aa1555194b9f176612b04fbd38f49b40d">clear</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#af5198110c0058e3d60524eecf500ee51">llvm::LiveIntervalCalc::constructMainRangeFromSubranges</a>, <a href="#a66ff664a97cd3c30de7e873335a0c075">empty</a>, <a href="#a757fd6afba0f531db70e78e057d147c6">end</a>, <a href="#a9cf54954ea6cbc5ff4895e3f7f7ca1af">end</a>, <a href="#aa1bc5510e870a77ebe055b1524d9fd26">endIndex</a>, <a href="#a76906231c2b079d1b909ddae48ef6e14">findIndexesLiveAt</a>, <a href="#afb60ddfb929ff4265623f2aa4f39a83e">flushSegmentSet</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a5d81038ff196d7a9495ff9f7266d667c">llvm::LiveInterval::getSize</a>, <a href="#a61f530037a29a00a48799b14104a68d1">isZeroLength</a>, <a href="#a2b10543d5f749956dd408fd7ebb3c552">join</a>, <a href="#a92e17326c2170e889ae4390c56878b77">MergeValueNumberInto</a>, <a href="#af62a3dfb9ce9b78c94e7b910a02b28cf">print</a>, <a href="#acea134ac1ed40b2215b8a1065a176d96">removeSegment</a>, <a href="#ae8bd4b098d55a431c12cfba2a11c94bb">removeSegment</a>, <a href="#a63176e601338dbe403676b86e78c7203">removeValNo</a>, <a href="#a687cab1756967efc8f0ce66105531755">RenumberValues</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac7446b2819c44bf459763351b5bcc29b">llvm::LiveIntervals::shrinkToUses</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a42083019e0bdb164e55da49ab9f4d717">llvm::LiveIntervals::shrinkToUses</a> and <a href="#ac80c04546dae620bf4dca9d6137d6a61">size</a>.</p>

</div>
</div>

### segmentSet {#a626da1d721d44f0fb48c580213d4386c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SegmentSet&gt; llvm::LiveRange::segmentSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="#a0b73c8d5ae32ca13dd02ddde86ffd0a2">addSegment</a>, <a href="#a4258d794235c7a408b3f52e5e4ef7159">createDeadDef</a>, <a href="#adbfe0544c5d2588941c44827f801e64b">createDeadDef</a>, <a href="#a81f9d3d0b958e57c0c0f24982230885d">extendInBlock</a>, <a href="#acc063bb08668434f0df98f4230901d10">extendInBlock</a>, <a href="#afb60ddfb929ff4265623f2aa4f39a83e">flushSegmentSet</a> and <a href="#a00e0b8f47bc603934f5954cd117af178">LiveRange</a>.</p>

</div>
</div>

### valnos {#a9eb4aa155c41e60dff42f4e741a0dcf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfoList llvm::LiveRange::valnos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveinterval-h">LiveInterval.h</a>.</p>


<p>Referenced by <a href="#ae7eb95d6c78b269fe03ed9c78cf2c33f">assign</a>, <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#ab075ccec6878e16419fca5e423c7ddad">llvm::ConnectedVNInfoEqClasses::Classify</a>, <a href="#aa1555194b9f176612b04fbd38f49b40d">clear</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#af5198110c0058e3d60524eecf500ee51">llvm::LiveIntervalCalc::constructMainRangeFromSubranges</a>, <a href="#ac5db2ca7684625ebf424170b9e98f404">containsOneValue</a>, <a href="#a3e577095d60431acbf1416db9bb8ec78">createValueCopy</a>, <a href="#ae609c36884142cbc16989cdf3bec4dad">getNextValue</a>, <a href="#a93450063916ca1ab1f11bf3304a6ad03">getNumValNums</a>, <a href="#a060100d6b75129bdef5516fac8f89a55">getValNumInfo</a>, <a href="#a9b4b1397b800d411d5e89bd09cde5b2a">getValNumInfo</a>, <a href="#ace8519cea9fa2e688a052df670afe41e">hasAtLeastOneValue</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a1b6e5f6033c80dff3f9b4c6fb40499c2">llvm::LiveIntervals::hasPHIKill</a>, <a href="#a2b10543d5f749956dd408fd7ebb3c552">join</a>, <a href="#a687cab1756967efc8f0ce66105531755">RenumberValues</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a42083019e0bdb164e55da49ab9f4d717">llvm::LiveIntervals::shrinkToUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp/#aeb309e71b02f8298a437ec465645fe99">stripValuesNotDefiningMask</a>, <a href="#a84d7fba74d57269f494283490fd93439">verify</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a787f3f4287374d61c5f0657dd83acbb4">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveInterval</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a0c8281afcc693674f4ff5c0d2198c770">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRange</a>, <a href="#a5fb099e2afb74f4c922f32894b30b279">vni_begin</a>, <a href="#a64661635fc0bf729d6e39b2dfa8a965e">vni_begin</a>, <a href="#aca7b7d6f329690e6bd5b5e1c83db7c1e">vni_end</a> and <a href="#a812e5c85e99795c3985efdd87946edf5">vni_end</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
