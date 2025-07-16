---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/instructioncost
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InstructionCost` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::InstructionCost { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">llvm/Support/InstructionCost.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dbf65370a0656ea05a0aa97380c15cc">CostType</a> = int64_t</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CostState { <a href="#a964cfda478e11c52ec46d73eb3185029">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a964cfda478e11c52ec46d73eb3185029">CostState</a> describes the state of a cost. <a href="#a964cfda478e11c52ec46d73eb3185029">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae83a2e8bde83d82502d21fe35c28890">InstructionCost</a> (CostState)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0da62f1c1214dbd0e0705be9c0e374b">InstructionCost</a> (CostType Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79829a95fb4e733a459c2d65ced4a293">operator+=</a> (const InstructionCost &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For all of the arithmetic operators provided here any invalid state is perpetuated and cannot be removed. <a href="#a79829a95fb4e733a459c2d65ced4a293">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eb2c1aeae46e9c414e94547740e1025">operator+=</a> (const CostType RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a946cb586f14f0ea44db84f2a920fa82b">operator-=</a> (const InstructionCost &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a629687062186d9089f363a4776d9b572">operator-=</a> (const CostType RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a317301c54ee5c9803a693b1e72e66ff0">operator*=</a> (const InstructionCost &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3f1470be741fb01f922da764c8b85da">operator*=</a> (const CostType RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a064ce8195a488d5c68ca0774d447c6">operator/=</a> (const InstructionCost &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe527986cc2bbf98dfb03cea32c9584a">operator/=</a> (const CostType RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a417a141153532fe0f14002a76d2c623f">operator++</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ee5fc78e76c246cd3a10b773a9ccb92">operator++</a> (int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39a5d770d01c0b085760a7d6ae116edc">operator--</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6becb31e3eec25b6e2cbb41a93e1e89d">operator--</a> (int)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0e99b0b79a9c06dc6dd0547a4f83cea">operator&lt;</a> (const InstructionCost &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the comparison operators we have chosen to use lexicographical ordering where valid costs are always considered to be less than invalid costs. <a href="#aa0e99b0b79a9c06dc6dd0547a4f83cea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c3c6ca97f6864d50e2d3b81a4cb9ff2">operator==</a> (const InstructionCost &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9197c084b530b9f4c7d01cb6b6b3b1a0">operator!=</a> (const InstructionCost &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf0ca45e36e2ddf2685e072893b8fbfe">operator==</a> (const CostType RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b38258080d11d8b171b809c8e87116a">operator!=</a> (const CostType RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b4329af60e2f4e144d5fff118006dc2">operator&gt;</a> (const InstructionCost &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd40f2f151a4a6ad7195934de16390a3">operator&lt;=</a> (const InstructionCost &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fbd9ec0cd6937982861d39f400f7a07">operator&gt;=</a> (const InstructionCost &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abebda5b4d1c727363ba5b5d02a700523">operator&lt;</a> (const CostType RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0ff072adb9816c274c8bf9c58b20398">operator&gt;</a> (const CostType RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aeb8715cf72d5add6734a3d859d16c8">operator&lt;=</a> (const CostType RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fe3f9404337688cd5aa4d092730febd">operator&gt;=</a> (const CostType RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae01c5ced9fe2fe50f421ae121483ef04">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a914b19fed88b441570be70455efd195c">setValid</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e2de49134b2835ec083cd3d15dfa2a5">setInvalid</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a964cfda478e11c52ec46d73eb3185029">CostState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada2193d3ec8ed244d636c20c8f17b2d1">getState</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="#a5dbf65370a0656ea05a0aa97380c15cc">CostType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b642067999075ba996ecdee40b52b68">getValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function is intended to be used as sparingly as possible, since the class provides the full range of operator support required for arithmetic and comparisons. <a href="#a9b642067999075ba996ecdee40b52b68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a0b7d0565cbdb80fcc368365bf86c9c">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Function&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3371d78e8a89bf16ff333af1f383eb4b">map</a> (const Function &amp;F) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a590bf4189d307d8bc4fd9e6151e28a05">propagateState</a> (const InstructionCost &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5dbf65370a0656ea05a0aa97380c15cc">CostType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa58bc3a667079c0d8b6e817c32aa0e9d">Value</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a964cfda478e11c52ec46d73eb3185029">CostState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26f48d4776e6441674f73c4fffc7f3bb">State</a> = <a href="#a964cfda478e11c52ec46d73eb3185029af2a8117cfe9e0f4b0aa8e9897fed80a7">Valid</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de26b938774385a0a4fb0d0b2a32d48">getMax</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44fe7c0339c1a7550cd1e0b7bf505e87">getMin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57207993e2fe6ec98912e8072e4600bc">getInvalid</a> (CostType Val=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a5dbf65370a0656ea05a0aa97380c15cc">CostType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5015fe9ff731561c11e54d6a25676a8a">getMaxValue</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a5dbf65370a0656ea05a0aa97380c15cc">CostType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f820375be61bf234f25bf8ab89e19bd">getMinValue</a> ()</td>
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


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CostType {#a5dbf65370a0656ea05a0aa97380c15cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InstructionCost::CostType =  int64_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### CostState {#a964cfda478e11c52ec46d73eb3185029}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::InstructionCost::CostState </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a964cfda478e11c52ec46d73eb3185029">CostState</a> describes the state of a cost.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Valid<a id="a964cfda478e11c52ec46d73eb3185029af2a8117cfe9e0f4b0aa8e9897fed80a7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Invalid<a id="a964cfda478e11c52ec46d73eb3185029a30cd573b546b4b6ec8a46680544db2c3"></a></td>
<td class="doxyEnumItemDescription">&lt; The cost value represents a valid cost, even when the cost-value is large</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InstructionCost() {#ae38a6fdb26e43b2354add8d313b5df2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstructionCost::InstructionCost ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>Referenced by <a href="#a57207993e2fe6ec98912e8072e4600bc">getInvalid</a>, <a href="#a6de26b938774385a0a4fb0d0b2a32d48">getMax</a>, <a href="#a44fe7c0339c1a7550cd1e0b7bf505e87">getMin</a>, <a href="#a3371d78e8a89bf16ff333af1f383eb4b">map</a>, <a href="#a9197c084b530b9f4c7d01cb6b6b3b1a0">operator!=</a>, <a href="#aa3f1470be741fb01f922da764c8b85da">operator*=</a>, <a href="#a317301c54ee5c9803a693b1e72e66ff0">operator*=</a>, <a href="#a417a141153532fe0f14002a76d2c623f">operator++</a>, <a href="#a4ee5fc78e76c246cd3a10b773a9ccb92">operator++</a>, <a href="#a0eb2c1aeae46e9c414e94547740e1025">operator+=</a>, <a href="#a79829a95fb4e733a459c2d65ced4a293">operator+=</a>, <a href="#a39a5d770d01c0b085760a7d6ae116edc">operator--</a>, <a href="#a6becb31e3eec25b6e2cbb41a93e1e89d">operator--</a>, <a href="#a629687062186d9089f363a4776d9b572">operator-=</a>, <a href="#a946cb586f14f0ea44db84f2a920fa82b">operator-=</a>, <a href="#afe527986cc2bbf98dfb03cea32c9584a">operator/=</a>, <a href="#a9a064ce8195a488d5c68ca0774d447c6">operator/=</a>, <a href="#abebda5b4d1c727363ba5b5d02a700523">operator&lt;</a>, <a href="#aa0e99b0b79a9c06dc6dd0547a4f83cea">operator&lt;</a>, <a href="#a8aeb8715cf72d5add6734a3d859d16c8">operator&lt;=</a>, <a href="#abd40f2f151a4a6ad7195934de16390a3">operator&lt;=</a>, <a href="#aaf0ca45e36e2ddf2685e072893b8fbfe">operator==</a>, <a href="#a2c3c6ca97f6864d50e2d3b81a4cb9ff2">operator==</a>, <a href="#ac0ff072adb9816c274c8bf9c58b20398">operator&gt;</a>, <a href="#a6b4329af60e2f4e144d5fff118006dc2">operator&gt;</a>, <a href="#a7fe3f9404337688cd5aa4d092730febd">operator&gt;=</a> and <a href="#a9fbd9ec0cd6937982861d39f400f7a07">operator&gt;=</a>.</p>

</div>
</div>

### InstructionCost() {#aae83a2e8bde83d82502d21fe35c28890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstructionCost::InstructionCost (<a href="#a964cfda478e11c52ec46d73eb3185029">CostState</a>)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>

</div>
</div>

### InstructionCost() {#aa0da62f1c1214dbd0e0705be9c0e374b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstructionCost::InstructionCost (<a href="#a5dbf65370a0656ea05a0aa97380c15cc">CostType</a> Val)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>Reference <a href="#a964cfda478e11c52ec46d73eb3185029af2a8117cfe9e0f4b0aa8e9897fed80a7">Valid</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator--() {#a39a5d770d01c0b085760a7d6ae116edc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost &amp; llvm::InstructionCost::operator-- ()</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>Reference <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a>.</p>

</div>
</div>

### operator--() {#a6becb31e3eec25b6e2cbb41a93e1e89d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::InstructionCost::operator-- (int)</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>Reference <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a>.</p>

</div>
</div>

### operator-=() {#a946cb586f14f0ea44db84f2a920fa82b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost &amp; llvm::InstructionCost::operator-= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp; RHS)</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add3b47639a79f68bc108a2c491f579f8">llvm::SubOverflow</a>.</p>

</div>
</div>

### operator-=() {#a629687062186d9089f363a4776d9b572}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost &amp; llvm::InstructionCost::operator-= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5dbf65370a0656ea05a0aa97380c15cc">CostType</a> RHS)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator!=() {#a9197c084b530b9f4c7d01cb6b6b3b1a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstructionCost::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp; RHS)</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator!=() {#a2b38258080d11d8b171b809c8e87116a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstructionCost::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5dbf65370a0656ea05a0aa97380c15cc">CostType</a> RHS)</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator\*=() {#a317301c54ee5c9803a693b1e72e66ff0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost &amp; llvm::InstructionCost::operator*= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp; RHS)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a073e9e9c9d16980286268ddb7cf3e2d9">llvm::MulOverflow</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator\*=() {#aa3f1470be741fb01f922da764c8b85da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost &amp; llvm::InstructionCost::operator*= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5dbf65370a0656ea05a0aa97380c15cc">CostType</a> RHS)</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator/=() {#a9a064ce8195a488d5c68ca0774d447c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost &amp; llvm::InstructionCost::operator/= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp; RHS)</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator/=() {#afe527986cc2bbf98dfb03cea32c9584a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost &amp; llvm::InstructionCost::operator/= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5dbf65370a0656ea05a0aa97380c15cc">CostType</a> RHS)</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator++() {#a417a141153532fe0f14002a76d2c623f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost &amp; llvm::InstructionCost::operator++ ()</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>Reference <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a>.</p>

</div>
</div>

### operator++() {#a4ee5fc78e76c246cd3a10b773a9ccb92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::InstructionCost::operator++ (int)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>Reference <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a>.</p>

</div>
</div>

### operator+=() {#a79829a95fb4e733a459c2d65ced4a293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost &amp; llvm::InstructionCost::operator+= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp; RHS)</td>
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

<p>For all of the arithmetic operators provided here any invalid state is perpetuated and cannot be removed.</p>


<p>Once a cost becomes invalid it stays invalid, and it also inherits any invalid state from the RHS. Arithmetic work on the actual values is implemented with saturation, to avoid overflow when using more extreme cost values.</p>


<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad67c6622d517b525fc5d420330d8b3f2">llvm::AddOverflow</a>, <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator+=() {#a0eb2c1aeae46e9c414e94547740e1025}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost &amp; llvm::InstructionCost::operator+= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5dbf65370a0656ea05a0aa97380c15cc">CostType</a> RHS)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt;() {#aa0e99b0b79a9c06dc6dd0547a4f83cea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstructionCost::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp; RHS)</td>
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

<p>For the comparison operators we have chosen to use lexicographical ordering where valid costs are always considered to be less than invalid costs.</p>


<p>This avoids having to add asserts to the comparison operators that the states are valid and users can test for validity of the cost explicitly.</p>


<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt;() {#abebda5b4d1c727363ba5b5d02a700523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstructionCost::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5dbf65370a0656ea05a0aa97380c15cc">CostType</a> RHS)</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt;=() {#abd40f2f151a4a6ad7195934de16390a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstructionCost::operator&lt;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp; RHS)</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt;=() {#a8aeb8715cf72d5add6734a3d859d16c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstructionCost::operator&lt;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5dbf65370a0656ea05a0aa97380c15cc">CostType</a> RHS)</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#a2c3c6ca97f6864d50e2d3b81a4cb9ff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstructionCost::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp; RHS)</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#aaf0ca45e36e2ddf2685e072893b8fbfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstructionCost::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5dbf65370a0656ea05a0aa97380c15cc">CostType</a> RHS)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt;() {#a6b4329af60e2f4e144d5fff118006dc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstructionCost::operator&gt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp; RHS)</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt;() {#ac0ff072adb9816c274c8bf9c58b20398}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstructionCost::operator&gt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5dbf65370a0656ea05a0aa97380c15cc">CostType</a> RHS)</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt;=() {#a9fbd9ec0cd6937982861d39f400f7a07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstructionCost::operator&gt;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp; RHS)</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt;=() {#a7fe3f9404337688cd5aa4d092730febd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstructionCost::operator&gt;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a5dbf65370a0656ea05a0aa97380c15cc">CostType</a> RHS)</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getState() {#ada2193d3ec8ed244d636c20c8f17b2d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CostState llvm::InstructionCost::getState ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>

</div>
</div>

### getValue() {#a9b642067999075ba996ecdee40b52b68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CostType &gt; llvm::InstructionCost::getValue ()</td>
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

<p>This function is intended to be used as sparingly as possible, since the class provides the full range of operator support required for arithmetic and comparisons.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>Reference <a href="#ae01c5ced9fe2fe50f421ae121483ef04">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp/#a490938b206738261d5984fe958a872ad">adjustInliningThresholdUsingCallee</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a76ff59dafad74689cfe1966b0ed9fa3c">analyzeLoopUnrollCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a362f793f3254317c698e3560548788a5">areRuntimeChecksProfitable</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks/#ad7b44d9befce70f070d4355d10ffc419">anonymous{LoopVectorize.cpp}::GeneratedRTChecks::getCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a671590a0e2685f1038479bd7c00b920a">llvm::X86TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a99733e87982c752be1218b2d87e592b9">llvm::SystemZTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/cost/#abd90406531e76ab0007b8cf6ebe8b34d">anonymous{LoopStrengthReduce.cpp}::Cost::RateFormula</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#af9f62350ccdebd24858be552f3fc051c">llvm::LoopVectorizationCostModel::selectInterleaveCount</a>.</p>

</div>
</div>

### isValid() {#ae01c5ced9fe2fe50f421ae121483ef04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstructionCost::isValid ()</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>Reference <a href="#a964cfda478e11c52ec46d73eb3185029af2a8117cfe9e0f4b0aa8e9897fed80a7">Valid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a76ff59dafad74689cfe1966b0ed9fa3c">analyzeLoopUnrollCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a362f793f3254317c698e3560548788a5">areRuntimeChecksProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#ac84a2bc6b484c5d3a03e80ce40f0a14c">llvm::VPRecipeBase::cost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a35de5712aacf900ec00d1817008eeed1">llvm::PPCTTIImpl::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#aa96045bfcd00b9908c624a5626b2c05c">llvm::PPCTTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a228a182df5d1f649d5b9f6dc8be75011">llvm::PPCTTIImpl::getCmpSelInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#afffe3207f30907d3ca4800ba3d26c9f0">llvm::PPCTTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a9ab346ad59b02578a3fc143c77397761">llvm::PPCTTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a4e307866e6d65e87d1e6884b0d13306c">llvm::LoopVectorizationCostModel::getReductionPatternCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a3cbf7279944dc2f0f99a6896501277f9">getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a2933bd38a4062250af0ebb41af0caa10">llvm::PPCTTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a671590a0e2685f1038479bd7c00b920a">llvm::X86TTIImpl::getShuffleCost</a>, <a href="#a9b642067999075ba996ecdee40b52b68">getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a513e1873d7e7760f5e0241cc47a9aaca">llvm::PPCTTIImpl::getVectorInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#ae2dcbf9f4bf17b489bfdebc4187d25d4">llvm::PPCTTIImpl::getVPMemoryOpCost</a>, <a href="#a3371d78e8a89bf16ff333af1f383eb4b">map</a>, <a href="#a7a0b7d0565cbdb80fcc368365bf86c9c">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/cost/#abd90406531e76ab0007b8cf6ebe8b34d">anonymous{LoopStrengthReduce.cpp}::Cost::RateFormula</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#af9f62350ccdebd24858be552f3fc051c">llvm::LoopVectorizationCostModel::selectInterleaveCount</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a885ad9ea73b97e3154433e5c37fefa99">llvm::LoopVectorizationCostModel::selectUserVectorizationFactor</a>.</p>

</div>
</div>

### map() {#a3371d78e8a89bf16ff333af1f383eb4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Function&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::InstructionCost::map (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a57207993e2fe6ec98912e8072e4600bc">getInvalid</a>, <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> and <a href="#ae01c5ced9fe2fe50f421ae121483ef04">isValid</a>.</p>

</div>
</div>

### print() {#a7a0b7d0565cbdb80fcc368365bf86c9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Cost::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/support/instructioncost-cpp">InstructionCost.cpp</a>.</p>


<p>Reference <a href="#ae01c5ced9fe2fe50f421ae121483ef04">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/cost/#ab9ff5264fbc3faf5b26768f683a43e59">anonymous{LoopStrengthReduce.cpp}::Cost::dump</a>.</p>

</div>
</div>

### setInvalid() {#a0e2de49134b2835ec083cd3d15dfa2a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstructionCost::setInvalid ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>Reference <a href="#a964cfda478e11c52ec46d73eb3185029a30cd573b546b4b6ec8a46680544db2c3">Invalid</a>.</p>


<p>Referenced by <a href="#a57207993e2fe6ec98912e8072e4600bc">getInvalid</a>.</p>

</div>
</div>

### setValid() {#a914b19fed88b441570be70455efd195c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstructionCost::setValid ()</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>Reference <a href="#a964cfda478e11c52ec46d73eb3185029af2a8117cfe9e0f4b0aa8e9897fed80a7">Valid</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### propagateState() {#a590bf4189d307d8bc4fd9e6151e28a05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstructionCost::propagateState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp; RHS)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### State {#a26f48d4776e6441674f73c4fffc7f3bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CostState llvm::InstructionCost::State = <a href="#a964cfda478e11c52ec46d73eb3185029af2a8117cfe9e0f4b0aa8e9897fed80a7">Valid</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>

</div>
</div>

### Value {#aa58bc3a667079c0d8b6e817c32aa0e9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CostType llvm::InstructionCost::Value = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getInvalid() {#a57207993e2fe6ec98912e8072e4600bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::InstructionCost::getInvalid (<a href="#a5dbf65370a0656ea05a0aa97380c15cc">CostType</a> Val=0)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>References <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a> and <a href="#a0e2de49134b2835ec083cd3d15dfa2a5">setInvalid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vpfirstorderrecurrencephirecipe/#a465d0006e51f34ba35fccf2cb3f72f89">llvm::VPFirstOrderRecurrencePHIRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedreference/#a0182cdf55f9bfbdd904e3f5e6802316a">llvm::IndexedReference::computeRefCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee2e01f96c805b5a96eba720d4eb880b">llvm::ComputeSpeculationCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#aa948ba905ff37c533b3c85068f94fd24">llvm::VPRegionBlock::cost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#af789f2112e21a8c039b186e90cc811a8">llvm::TargetTransformInfoImplBase::getAltInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a0f637a0e145cbc99df0a5c41b51e90b6">llvm::X86TTIImpl::getAltInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#aae70ddddbfd05ed5831918fa1836b947">llvm::AArch64TTIImpl::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24fb14e02fa8e4a261838b46074e42fa">llvm::AArch64TTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a38dd0562fe8267823b87ef5c3bacc264">llvm::AArch64TTIImpl::getArithmeticReductionCostSVE</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ad0c9ac06022884eb218dc8f8c4056e43">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ad8398a35cd187d6a75b460fcf54b5236">llvm::LoopVectorizationCostModel::getDivRemSpeculationCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#aa47f57320f9f28895b6df6b5eb0f9dfa">llvm::AArch64TTIImpl::getGatherScatterOpCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a8a65916cd3a5fe149b7cee7a978a80eb">getHistogramCost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a3b08e9ad2a315e50f4b0189d9755deed">llvm::AArch64TTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a09ac3c26a04fdf36e4bcc0e725fca41e">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#affbb031405865e13b46411b934814a83">llvm::RISCVTTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a8965f79b48ae37911f82bc71e1433131">llvm::RISCVTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a4eaac4d2c1c7ce1ac8be447338a6e7e5">llvm::TargetTransformInfoImplBase::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a601135659272829d63f02580f4559995">llvm::RISCVTargetLowering::getLMULCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a0ed0459656c8a2378156bf244c7e2087">llvm::AArch64TTIImpl::getMaskedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a6c8d73add4e552328f931ce1681c494f">llvm::AArch64TTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#adb7e05c95393c231260785fc1ce4700b">llvm::AArch64TTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a4b5cc16bea89163600c002e89334a82e">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a22615a6ebaa0232be4b70be555bf0690">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getOrderedReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a252df3516bdd18a47c638e745bcd01f4">llvm::AArch64TTIImpl::getPartialReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a99ef92b3ecac3ce293aaae0f0a4a3611">llvm::TargetTransformInfoImplBase::getPartialReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#aae63a6d9d535be11dc640352ea48b6ed">llvm::AArch64TTIImpl::getScalarizationOverhead</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a925361ad88aa02b69d20adaaab9f4f33">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getScalarizationOverhead</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#aa50ff21994f2f42d5336fbea8a4ecf06">llvm::RISCVTTIImpl::getScalarizationOverhead</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a005211a6c7f26317af98d088c06f0f64">llvm::AArch64TTIImpl::getSpliceCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a5bfac53f25d38d17febbe2ff84d2e15a">llvm::TargetTransformInfoImplBase::getStridedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a2c1b9368972e15e3602d4279f9988584">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTreeReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ae2b0b2a1ae237432c1c272406a8b4667">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTypeBasedIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ab192bc3b4b8ccaa71341acf20e6ac335">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTypeLegalizationCost</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#ab3118e33ed28deca370645b8b909fa5a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::lowerDotProduct</a>, <a href="#a3371d78e8a89bf16ff333af1f383eb4b">map</a>, <a href="/web-llvm/docs/api/classes/llvm/costmodelprinterpass/#a6685ffe146df7448fc95cd7fcec89e55">llvm::CostModelPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ae8d11752355845a0e271111de7be7d3a">llvm::LoopVectorizationCostModel::setCostBasedWideningDecision</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a8178cc5e49d5251d7ca3413b8a434f8f">llvm::LoopVectorizationCostModel::setVectorizedCallDecision</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a40003c9aae5f4e1d9cf4b042db0b0c13">llvm::PPCTTIImpl::vectorCostAdjustmentFactor</a>.</p>

</div>
</div>

### getMax() {#a6de26b938774385a0a4fb0d0b2a32d48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::InstructionCost::getMax ()</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>Reference <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a3884c27912d0714a0f475680f6324b3d">llvm::anonymous{AMDGPUSplitModule.cpp}::calculateFunctionCosts</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a4adc69fc8f74164e990cce6afc1e061b">llvm::LoopVectorizationPlanner::computeBestVF</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#ad7ba1c452de730eb7097066c418ca601">llvm::HexagonTTIImpl::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a35de5712aacf900ec00d1817008eeed1">llvm::PPCTTIImpl::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#a094857314ef83a5c1a71e2941a00e795">llvm::HexagonTTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#aa96045bfcd00b9908c624a5626b2c05c">llvm::PPCTTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#ac3fc391aec3ded7732a0715fea1cf4e7">llvm::HexagonTTIImpl::getCmpSelInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a228a182df5d1f649d5b9f6dc8be75011">llvm::PPCTTIImpl::getCmpSelInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#afffe3207f30907d3ca4800ba3d26c9f0">llvm::PPCTTIImpl::getInterleavedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a9ab346ad59b02578a3fc143c77397761">llvm::PPCTTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a2933bd38a4062250af0ebb41af0caa10">llvm::PPCTTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a513e1873d7e7760f5e0241cc47a9aaca">llvm::PPCTTIImpl::getVectorInstrCost</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#ae2dcbf9f4bf17b489bfdebc4187d25d4">llvm::PPCTTIImpl::getVPMemoryOpCost</a>.</p>

</div>
</div>

### getMin() {#a44fe7c0339c1a7550cd1e0b7bf505e87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::InstructionCost::getMin ()</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>


<p>Reference <a href="#ae38a6fdb26e43b2354add8d313b5df2a">InstructionCost</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getMaxValue() {#a5015fe9ff731561c11e54d6a25676a8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CostType llvm::InstructionCost::getMaxValue ()</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>

</div>
</div>

### getMinValue() {#a6f820375be61bf234f25bf8ab89e19bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CostType llvm::InstructionCost::getMinValue ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">InstructionCost.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/instructioncost-cpp">InstructionCost.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
