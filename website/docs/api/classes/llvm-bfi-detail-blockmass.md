---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/bfi-detail/blockmass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BlockMass` Class Reference

<p>Mass of a block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::bfi_detail::BlockMass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">llvm/Analysis/BlockFrequencyInfoImpl.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfdb00b2c71ac98e68da9a48c4e4f016">BlockMass</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a542ba189f3ea922222b703a4b345c1a8">BlockMass</a> (uint64_t Mass)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07e9c2c2d820ae6830cb200d9c127839">operator!</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bfi-detail/blockmass">BlockMass</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae147ad20e63a91b33aff8585bbe37a9f">operator+=</a> (BlockMass X)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add another mass. <a href="#ae147ad20e63a91b33aff8585bbe37a9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bfi-detail/blockmass">BlockMass</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a625caa14bc11574f2ac44c67a9474cb6">operator-=</a> (BlockMass X)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subtract another mass. <a href="#a625caa14bc11574f2ac44c67a9474cb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bfi-detail/blockmass">BlockMass</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2afbd73bd9870df1aec09a821b80b8d">operator*=</a> (BranchProbability P)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33f6df4d294d336376dc0f6f2b2078f5">operator==</a> (BlockMass X) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3a2d7c4fc82e84aa6823b9ec79bc7f5">operator!=</a> (BlockMass X) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b33c9f137ee70772de1927056d41fef">operator&lt;=</a> (BlockMass X) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedf9e705154fd4b0e99b6f11339f2ada">operator&gt;=</a> (BlockMass X) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07ad8547a841472e2087996e8a0754b6">operator&lt;</a> (BlockMass X) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fc6aab5a3de5a10eae97d30fdaa8430">operator&gt;</a> (BlockMass X) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a221f01eee80db0b0c4f4567c84b54fb5">getMass</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d943c4e8129a1812f0ddbe60766caf7">isFull</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3874be041c63e0b867d82331409a0de2">isEmpty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalednumber">ScaledNumber</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af48ed4af672b3ec628c6c79ac0746312">toScaled</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert to scaled number. <a href="#af48ed4af672b3ec628c6c79ac0746312">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ae944f41ccf807abef975067d634884">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d2eb10767a708e79d160dae4ebcd0a2">print</a> (raw_ostream &amp;OS) const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29da26a3bf8fb1280469ada404410ee3">Mass</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/bfi-detail/blockmass">BlockMass</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42dc56500d44820d4526a0863abc2943">getEmpty</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/bfi-detail/blockmass">BlockMass</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0e3f20571279f8b3896a687101d7151">getFull</a> ()</td>
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

<p>Mass of a block.</p>


<p>This class implements a sort of fixed-point fraction always between 0.0 and 1.0. <a href="#a221f01eee80db0b0c4f4567c84b54fb5">getMass()</a> == std::numeric_limits&lt;uint64_t&gt;::max() indicates a value of 1.0.</p>


<p>Masses can be added and subtracted. Simple saturation arithmetic is used, so arithmetic operations never overflow or underflow.</p>


<p>Masses can be multiplied. Multiplication treats full mass as 1.0 and uses an inexpensive floating-point algorithm that's off-by-one (almost, but not quite, maximum precision).</p>


<p>Masses can be scaled by <em><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></em> at maximum precision.</p>


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BlockMass() {#adfdb00b2c71ac98e68da9a48c4e4f016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::bfi_detail::BlockMass::BlockMass ()</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="#a42dc56500d44820d4526a0863abc2943">getEmpty</a>, <a href="#ac0e3f20571279f8b3896a687101d7151">getFull</a>, <a href="#ad3a2d7c4fc82e84aa6823b9ec79bc7f5">operator!=</a>, <a href="#ab2afbd73bd9870df1aec09a821b80b8d">operator*=</a>, <a href="#ae147ad20e63a91b33aff8585bbe37a9f">operator+=</a>, <a href="#a625caa14bc11574f2ac44c67a9474cb6">operator-=</a>, <a href="#a07ad8547a841472e2087996e8a0754b6">operator&lt;</a>, <a href="#a8b33c9f137ee70772de1927056d41fef">operator&lt;=</a>, <a href="#a33f6df4d294d336376dc0f6f2b2078f5">operator==</a>, <a href="#a0fc6aab5a3de5a10eae97d30fdaa8430">operator&gt;</a> and <a href="#aedf9e705154fd4b0e99b6f11339f2ada">operator&gt;=</a>.</p>

</div>
</div>

### BlockMass() {#a542ba189f3ea922222b703a4b345c1a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::bfi_detail::BlockMass::BlockMass (uint64_t Mass)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator-=() {#a625caa14bc11574f2ac44c67a9474cb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockMass &amp; llvm::bfi_detail::BlockMass::operator-= (<a href="/web-llvm/docs/api/classes/llvm/bfi-detail/blockmass">BlockMass</a> X)</td>
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

<p>Subtract another mass.</p>


<p>Subtracts another mass, saturating at <em><a href="#a3874be041c63e0b867d82331409a0de2">isEmpty()</a></em> rather than undeflowing.</p>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#adfdb00b2c71ac98e68da9a48c4e4f016">BlockMass</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### operator!() {#a07e9c2c2d820ae6830cb200d9c127839}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::bfi_detail::BlockMass::operator! ()</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Reference <a href="#a3874be041c63e0b867d82331409a0de2">isEmpty</a>.</p>

</div>
</div>

### operator!=() {#ad3a2d7c4fc82e84aa6823b9ec79bc7f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::bfi_detail::BlockMass::operator!= (<a href="/web-llvm/docs/api/classes/llvm/bfi-detail/blockmass">BlockMass</a> X)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#adfdb00b2c71ac98e68da9a48c4e4f016">BlockMass</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### operator\*=() {#ab2afbd73bd9870df1aec09a821b80b8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockMass &amp; llvm::bfi_detail::BlockMass::operator*= (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> P)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#adfdb00b2c71ac98e68da9a48c4e4f016">BlockMass</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### operator+=() {#ae147ad20e63a91b33aff8585bbe37a9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockMass &amp; llvm::bfi_detail::BlockMass::operator+= (<a href="/web-llvm/docs/api/classes/llvm/bfi-detail/blockmass">BlockMass</a> X)</td>
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

<p>Add another mass.</p>


<p>Adds another mass, saturating at <em><a href="#a3d943c4e8129a1812f0ddbe60766caf7">isFull()</a></em> rather than overflowing.</p>


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#adfdb00b2c71ac98e68da9a48c4e4f016">BlockMass</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### operator&lt;() {#a07ad8547a841472e2087996e8a0754b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::bfi_detail::BlockMass::operator&lt; (<a href="/web-llvm/docs/api/classes/llvm/bfi-detail/blockmass">BlockMass</a> X)</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#adfdb00b2c71ac98e68da9a48c4e4f016">BlockMass</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### operator&lt;=() {#a8b33c9f137ee70772de1927056d41fef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::bfi_detail::BlockMass::operator&lt;= (<a href="/web-llvm/docs/api/classes/llvm/bfi-detail/blockmass">BlockMass</a> X)</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#adfdb00b2c71ac98e68da9a48c4e4f016">BlockMass</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### operator==() {#a33f6df4d294d336376dc0f6f2b2078f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::bfi_detail::BlockMass::operator== (<a href="/web-llvm/docs/api/classes/llvm/bfi-detail/blockmass">BlockMass</a> X)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#adfdb00b2c71ac98e68da9a48c4e4f016">BlockMass</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### operator&gt;() {#a0fc6aab5a3de5a10eae97d30fdaa8430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::bfi_detail::BlockMass::operator&gt; (<a href="/web-llvm/docs/api/classes/llvm/bfi-detail/blockmass">BlockMass</a> X)</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#adfdb00b2c71ac98e68da9a48c4e4f016">BlockMass</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### operator&gt;=() {#aedf9e705154fd4b0e99b6f11339f2ada}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::bfi_detail::BlockMass::operator&gt;= (<a href="/web-llvm/docs/api/classes/llvm/bfi-detail/blockmass">BlockMass</a> X)</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#adfdb00b2c71ac98e68da9a48c4e4f016">BlockMass</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a5ae944f41ccf807abef975067d634884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void BlockMass::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp">BlockFrequencyInfoImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a2d2eb10767a708e79d160dae4ebcd0a2">print</a>.</p>

</div>
</div>

### getMass() {#a221f01eee80db0b0c4f4567c84b54fb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::bfi_detail::BlockMass::getMass ()</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="#af48ed4af672b3ec628c6c79ac0746312">toScaled</a>.</p>

</div>
</div>

### isEmpty() {#a3874be041c63e0b867d82331409a0de2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::bfi_detail::BlockMass::isEmpty ()</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#a6aca67ed248d1eb55621f38869372c65">llvm::BlockFrequencyInfoImplBase::computeLoopScale</a> and <a href="#a07e9c2c2d820ae6830cb200d9c127839">operator!</a>.</p>

</div>
</div>

### isFull() {#a3d943c4e8129a1812f0ddbe60766caf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::bfi_detail::BlockMass::isFull ()</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="#af48ed4af672b3ec628c6c79ac0746312">toScaled</a>.</p>

</div>
</div>

### print() {#a2d2eb10767a708e79d160dae4ebcd0a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; BlockMass::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp">BlockFrequencyInfoImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp/#a7c993766c71555883cf7cf7a2d98dd51">getHexDigit</a>.</p>


<p>Referenced by <a href="#a5ae944f41ccf807abef975067d634884">dump</a>.</p>

</div>
</div>

### toScaled() {#af48ed4af672b3ec628c6c79ac0746312}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScaledNumber&lt; uint64_t &gt; BlockMass::toScaled ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert to scaled number.</p>


<p>Convert to <em><a href="/web-llvm/docs/api/classes/llvm/scalednumber">ScaledNumber</a></em>. <em><a href="#a3d943c4e8129a1812f0ddbe60766caf7">isFull()</a></em> gives 1.0, while <em><a href="#a3874be041c63e0b867d82331409a0de2">isEmpty()</a></em> gives slightly above 0.0.</p>


<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp">BlockFrequencyInfoImpl.cpp</a>.</p>


<p>References <a href="#a221f01eee80db0b0c4f4567c84b54fb5">getMass</a> and <a href="#a3d943c4e8129a1812f0ddbe60766caf7">isFull</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#a6aca67ed248d1eb55621f38869372c65">llvm::BlockFrequencyInfoImplBase::computeLoopScale</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Mass {#a29da26a3bf8fb1280469ada404410ee3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::bfi_detail::BlockMass::Mass = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getEmpty() {#a42dc56500d44820d4526a0863abc2943}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockMass llvm::bfi_detail::BlockMass::getEmpty ()</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Reference <a href="#adfdb00b2c71ac98e68da9a48c4e4f016">BlockMass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bfi-detail/irreduciblegraph/#ad98ee11535062e1034345efac121ec05">llvm::bfi_detail::IrreducibleGraph::addNode</a> and <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#a8fcc33897ff2ea4ebc874792c49497ef">llvm::BlockFrequencyInfoImplBase::updateLoopWithIrreducible</a>.</p>

</div>
</div>

### getFull() {#ac0e3f20571279f8b3896a687101d7151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockMass llvm::bfi_detail::BlockMass::getFull ()</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Reference <a href="#adfdb00b2c71ac98e68da9a48c4e4f016">BlockMass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#af8aa6262fff3f09a8e2076d7a76e1628">llvm::BlockFrequencyInfoImplBase::adjustLoopHeaderMass</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#a6aca67ed248d1eb55621f38869372c65">llvm::BlockFrequencyInfoImplBase::computeLoopScale</a> and <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#aaa2c0a25aeaf519f9df55f422331f0db">llvm::BlockFrequencyInfoImplBase::distributeIrrLoopHeaderMass</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp">BlockFrequencyInfoImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
