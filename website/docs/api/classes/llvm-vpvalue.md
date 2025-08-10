---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vpvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VPValue` Class



## Declaration

<div class="doxyDeclaration">
class llvm::VPValue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">Transforms/Vectorize/VPlanValue.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpsingledefrecipe">VPSingleDefRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>VPSingleDef is a base class for recipes for modeling a sequence of one or more output IR that define a single result <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>. <a href="/web-llvm/docs/api/classes/llvm/vpsingledefrecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe">VPWidenLoadEVLRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe for widening load operations with vector-predication intrinsics, using the address to load from, the explicit vector length and an optional mask. <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe">VPWidenLoadRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe for widening load operations, using the address to load from and an optional mask. <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> * &gt;::iterator <a href="#aa3400a81793bcbf03f3b30a7338c1580">user_iterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> * &gt;::const_iterator <a href="#a47fb4eb15b10b443df03c4c5847fe96b">const_user_iterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#aa3400a81793bcbf03f3b30a7338c1580">user_iterator</a> &gt; <a href="#aa9ce5a89b32d3258294f9a9fa95fe6a5">user_range</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a47fb4eb15b10b443df03c4c5847fe96b">const_user_iterator</a> &gt; <a href="#af5da4fda0a09d2395c65c43455527427">const_user_range</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a76d9dc21ea5c62699960a935401a75ed">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An enumeration for keeping track of the concrete subclass of <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> that are actually instantiated. <a href="#a76d9dc21ea5c62699960a935401a75ed">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cdd07e8c68f855062bbaed3fa51989e">VPBuilder</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5df20a1ac93f5dbd76b326af478e39a8">VPDef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adda6f42a86944ad693fb8b14902630db">VPDoubleValueDef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3feb4ab29b46ff2d493da56f4ee1e6e7">VPInstruction</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab887bf054f80c195baa3f08c529d1fbc">VPInterleaveRecipe</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa64450a51195abf0a0111a5ba037de0a">VPlanTransforms</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac76e9c96905e02edd628d201986c57f8">VPBasicBlock</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ad6082d75b9659537420825e6c9732d">VPInterleavedAccessInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12ceea61a3de5b2f0ff70850f66c5fdc">VPSlotTracker</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae90ca15347282ab58dae4da77c19ab6e">VPRecipeBase</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7d3e451ebdc58b7a1ae06950281e6d4">VPlan</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7221a0f8273926e66f6a99d908d6c31a">VPValue</a> (const VPValue &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f2e5c044b5e7aad2e59cda1f5eb8ca8">VPValue</a> (const unsigned char SC, Value *UV=nullptr, VPDef *Def=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a158b4257d3512747671d3226584548a3">VPValue</a> (Value *UV=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a live-in <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>. <a href="#a158b4257d3512747671d3226584548a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeb35c15d78e11c21695a4b3fc87139f">VPValue</a> (VPDef *Def, Value *UV=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> for a <span class="doxyComputerOutput">Def</span> which is a subclass of <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>. <a href="#abeb35c15d78e11c21695a4b3fc87139f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c693a626ee926183f3ed7bc29480901">VPValue</a> (Value *UV, VPDef *Def)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> for a <span class="doxyComputerOutput">Def</span> which defines multiple values. <a href="#a6c693a626ee926183f3ed7bc29480901">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa05eea4a3203720013826fc5005d6e2f">~VPValue</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73eb8691cf6ac0b34b4e25154c649d26">operator=</a> (const VPValue &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fe7dd2466300bd8747d81384a7ced5d">getUnderlyingValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the underlying <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> attached to this <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>. <a href="#a5fe7dd2466300bd8747d81384a7ced5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3594c25bd5133d4ebdae3b0ff37a86c0">getVPValueID</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fc47e93505e87044e0861e4142eca20">printAsOperand</a> (raw_ostream &amp;OS, VPSlotTracker &amp;Tracker) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6a4aab2235f2121edb807d1fb261c43">print</a> (raw_ostream &amp;OS, VPSlotTracker &amp;Tracker) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a799cc000e147de9394fa660a60c9b4c9">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the value to stderr (for debugging). <a href="#a799cc000e147de9394fa660a60c9b4c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3acda1aa682fbb8f8b95b0816eea879">getNumUsers</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a552567714f74a84ee150e906e8020c5a">addUser</a> (VPUser &amp;User)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44c1ae68f3e8c2570e1b1ffc8962c4f2">removeUser</a> (VPUser &amp;User)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a single <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/user">User</a></span> from the list of users. <a href="#a44c1ae68f3e8c2570e1b1ffc8962c4f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa3400a81793bcbf03f3b30a7338c1580">user_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1edef8decf10105d95e9d9679643e5b">user_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a47fb4eb15b10b443df03c4c5847fe96b">const_user_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eb38cba0f7f349041524415fca4ded2">user_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa3400a81793bcbf03f3b30a7338c1580">user_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78092033a17c1ba2ac36048f918b220">user_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a47fb4eb15b10b443df03c4c5847fe96b">const_user_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabf7ce5dc1f33680e2aa4d07d2ef4da5">user_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa9ce5a89b32d3258294f9a9fa95fe6a5">user_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0932bb43954178036c87ea2ee5f112c">users</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af5da4fda0a09d2395c65c43455527427">const_user_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dfe15601746d1e08fb1dfc56c8d673f">users</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55617754bef8dbf15bdc3a053f987592">hasMoreThanOneUniqueUser</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the value has more than one unique user. <a href="#a55617754bef8dbf15bdc3a053f987592">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaad22a81f7fa4ce5b60ec619ac14c37">replaceAllUsesWith</a> (VPValue *New)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3773dd8f9c831f0dde091319b2ff7d0">replaceUsesWithIf</a> (VPValue *New, llvm::function_ref&lt; bool(VPUser &amp;U, unsigned Idx)&gt; ShouldReplace)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Go through the uses list for this <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> and make each use point to <span class="doxyComputerOutput">New</span> if the callback ShouldReplace returns true for the given use specified by a pair of (<a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a>, the use index). <a href="#ae3773dd8f9c831f0dde091319b2ff7d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3be8d7833df422f3538ddb13af69bd70">getDefiningRecipe</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the recipe defining this <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> or nullptr if it is not defined by a recipe, i.e. <a href="#a3be8d7833df422f3538ddb13af69bd70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5344249bc3b9217704a061c64003f1b0">getDefiningRecipe</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12efb19adb90f6e29d21f089f36858f1">hasDefiningRecipe</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> is defined by a recipe. <a href="#a12efb19adb90f6e29d21f089f36858f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add6179d3564ac5ea4736366b93d23829">isLiveIn</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> is a live-in, i.e. defined outside the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>. <a href="#add6179d3564ac5ea4736366b93d23829">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6f0bd9ed63fe4a784697d73ae3b6fa0">getLiveInIRValue</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the underlying IR value, if this <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> is defined outside the scope of <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>. <a href="#ac6f0bd9ed63fe4a784697d73ae3b6fa0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a509b131fd99a369f60da8778715edd78">getLiveInIRValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26ee9845ed3014dd45095ff2493b51b6">isDefinedOutsideLoopRegions</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> is defined outside any loop region. <a href="#a26ee9845ed3014dd45095ff2493b51b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9739b6fa8242398fd51cb4e77a2447d7">setUnderlyingValue</a> (Value *Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a627c1770437a2bfe04bb3aa331bbb40e">UnderlyingVal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af11c09a3d0bd5aa08472a6be6e654056">Def</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to the <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a> that defines this <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>. <a href="#af11c09a3d0bd5aa08472a6be6e654056">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a681933024138d939ef31107f17818b83">SubclassID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subclass identifier (for isa/dyn_cast). <a href="#a681933024138d939ef31107f17818b83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> *, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67cfb52cfa7c1f6ac543ae89077e8c46">Users</a></td>
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


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_user\_iterator {#a47fb4eb15b10b443df03c4c5847fe96b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallVectorImpl&lt;VPUser*&gt;::const_iterator llvm::VPValue::const_user_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

### const\_user\_range {#af5da4fda0a09d2395c65c43455527427}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef iterator_range&lt;const_user_iterator&gt; llvm::VPValue::const_user_range</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

### user\_iterator {#aa3400a81793bcbf03f3b30a7338c1580}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef SmallVectorImpl&lt;VPUser*&gt;::iterator llvm::VPValue::user_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

### user\_range {#aa9ce5a89b32d3258294f9a9fa95fe6a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef iterator_range&lt;user_iterator&gt; llvm::VPValue::user_range</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a76d9dc21ea5c62699960a935401a75ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An enumeration for keeping track of the concrete subclass of <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> that are actually instantiated.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPValueSC<a id="a76d9dc21ea5c62699960a935401a75edaaf4f11355938be96aafdf7984e992aeb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VPVRecipeSC<a id="a76d9dc21ea5c62699960a935401a75eda642d6930398c4c4b60a0e94899b3ce99"></a></td>
<td class="doxyEnumItemDescription">A generic <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>, like live-in values or defined by a recipe that defines multiple values</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### VPBasicBlock {#ac76e9c96905e02edd628d201986c57f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#ac76e9c96905e02edd628d201986c57f8">VPBasicBlock</a>.</p>


<p>Referenced by <a href="#ac76e9c96905e02edd628d201986c57f8">VPBasicBlock</a>.</p>

</div>
</div>

### VPBuilder {#a8cdd07e8c68f855062bbaed3fa51989e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/vpbuilder">VPBuilder</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#a8cdd07e8c68f855062bbaed3fa51989e">VPBuilder</a>.</p>


<p>Referenced by <a href="#a8cdd07e8c68f855062bbaed3fa51989e">VPBuilder</a>.</p>

</div>
</div>

### VPDef {#a5df20a1ac93f5dbd76b326af478e39a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#a5df20a1ac93f5dbd76b326af478e39a8">VPDef</a>.</p>


<p>Referenced by <a href="#a5df20a1ac93f5dbd76b326af478e39a8">VPDef</a>, <a href="#a8f2e5c044b5e7aad2e59cda1f5eb8ca8">VPValue</a>, <a href="#a6c693a626ee926183f3ed7bc29480901">VPValue</a>, <a href="#abeb35c15d78e11c21695a4b3fc87139f">VPValue</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#ae123bdc95f3d36b528edae0a4ff321df">llvm::VPWidenLoadEVLRecipe::VPWidenLoadEVLRecipe</a> and <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a723d7043589bac799ae42c256c12a4e4">llvm::VPWidenLoadRecipe::VPWidenLoadRecipe</a>.</p>

</div>
</div>

### VPDoubleValueDef {#adda6f42a86944ad693fb8b14902630db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct VPDoubleValueDef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#adda6f42a86944ad693fb8b14902630db">VPDoubleValueDef</a>.</p>


<p>Referenced by <a href="#adda6f42a86944ad693fb8b14902630db">VPDoubleValueDef</a>.</p>

</div>
</div>

### VPInstruction {#a3feb4ab29b46ff2d493da56f4ee1e6e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#a3feb4ab29b46ff2d493da56f4ee1e6e7">VPInstruction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a4a5678fa8d469e9dd49b7e389c22d5c7">llvm::VPInstruction::clone</a> and <a href="#a3feb4ab29b46ff2d493da56f4ee1e6e7">VPInstruction</a>.</p>

</div>
</div>

### VPInterleavedAccessInfo {#a9ad6082d75b9659537420825e6c9732d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/vpinterleavedaccessinfo">VPInterleavedAccessInfo</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#a9ad6082d75b9659537420825e6c9732d">VPInterleavedAccessInfo</a>.</p>


<p>Referenced by <a href="#a9ad6082d75b9659537420825e6c9732d">VPInterleavedAccessInfo</a>.</p>

</div>
</div>

### VPInterleaveRecipe {#ab887bf054f80c195baa3f08c529d1fbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe">VPInterleaveRecipe</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#ab887bf054f80c195baa3f08c529d1fbc">VPInterleaveRecipe</a>.</p>


<p>Referenced by <a href="#ab887bf054f80c195baa3f08c529d1fbc">VPInterleaveRecipe</a>.</p>

</div>
</div>

### VPlan {#af7d3e451ebdc58b7a1ae06950281e6d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#af7d3e451ebdc58b7a1ae06950281e6d4">VPlan</a>.</p>


<p>Referenced by <a href="#af7d3e451ebdc58b7a1ae06950281e6d4">VPlan</a>.</p>

</div>
</div>

### VPlanTransforms {#aa64450a51195abf0a0111a5ba037de0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/vplantransforms">VPlanTransforms</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#aa64450a51195abf0a0111a5ba037de0a">VPlanTransforms</a>.</p>


<p>Referenced by <a href="#aa64450a51195abf0a0111a5ba037de0a">VPlanTransforms</a>.</p>

</div>
</div>

### VPRecipeBase {#ae90ca15347282ab58dae4da77c19ab6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#ae90ca15347282ab58dae4da77c19ab6e">VPRecipeBase</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpsingledefrecipe/#a1843cdf46b92e1b61066d98e754d3cbc">llvm::VPSingleDefRecipe::classof</a>, <a href="#a799cc000e147de9394fa660a60c9b4c9">dump</a>, <a href="#a3be8d7833df422f3538ddb13af69bd70">getDefiningRecipe</a>, <a href="#a5344249bc3b9217704a061c64003f1b0">getDefiningRecipe</a>, <a href="#ab6a4aab2235f2121edb807d1fb261c43">print</a> and <a href="#ae90ca15347282ab58dae4da77c19ab6e">VPRecipeBase</a>.</p>

</div>
</div>

### VPSlotTracker {#a12ceea61a3de5b2f0ff70850f66c5fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/vpslottracker">VPSlotTracker</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#a12ceea61a3de5b2f0ff70850f66c5fdc">VPSlotTracker</a>.</p>


<p>Referenced by <a href="#a799cc000e147de9394fa660a60c9b4c9">dump</a>, <a href="#ab6a4aab2235f2121edb807d1fb261c43">print</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a86fd40dcbb7bf4bd5c2765ff07353fef">llvm::VPWidenLoadEVLRecipe::print</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#ac293be3f7d76772b820f58925b6b14e1">llvm::VPWidenLoadRecipe::print</a>, <a href="#a3fc47e93505e87044e0861e4142eca20">printAsOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a04cd50581d6d587662f7e3e58042b37e">llvm::VPWidenLoadRecipe::VP_CLASSOF_IMPL</a> and <a href="#a12ceea61a3de5b2f0ff70850f66c5fdc">VPSlotTracker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VPValue() {#a7221a0f8273926e66f6a99d908d6c31a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPValue::VPValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> &amp;)</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#a8f2e5c044b5e7aad2e59cda1f5eb8ca8">VPValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### VPValue() {#a8f2e5c044b5e7aad2e59cda1f5eb8ca8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue::VPValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char SC, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * UV=nullptr, <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a> * Def=nullptr)</td>
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



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="#af11c09a3d0bd5aa08472a6be6e654056">Def</a>, <a href="#a627c1770437a2bfe04bb3aa331bbb40e">UnderlyingVal</a> and <a href="#a5df20a1ac93f5dbd76b326af478e39a8">VPDef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a16471f19bad1ca5212ccbd52c21b8b54">llvm::VPWidenLoadEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a6aa813347887ce533adf6f76c42c4bf0">llvm::VPWidenLoadEVLRecipe::getEVL</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#abed0bd6ee69b8083deba69aa189aebc3">llvm::VPWidenLoadEVLRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a769d05569a9befd640244f159ba7f82a">llvm::VPWidenLoadRecipe::onlyFirstLaneUsed</a>, <a href="#a73eb8691cf6ac0b34b4e25154c649d26">operator=</a>, <a href="#abaad22a81f7fa4ce5b60ec619ac14c37">replaceAllUsesWith</a>, <a href="#ae3773dd8f9c831f0dde091319b2ff7d0">replaceUsesWithIf</a>, <a href="#a7221a0f8273926e66f6a99d908d6c31a">VPValue</a>, <a href="#a6c693a626ee926183f3ed7bc29480901">VPValue</a>, <a href="#a158b4257d3512747671d3226584548a3">VPValue</a>, <a href="#abeb35c15d78e11c21695a4b3fc87139f">VPValue</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#ae123bdc95f3d36b528edae0a4ff321df">llvm::VPWidenLoadEVLRecipe::VPWidenLoadEVLRecipe</a> and <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a723d7043589bac799ae42c256c12a4e4">llvm::VPWidenLoadRecipe::VPWidenLoadRecipe</a>.</p>

</div>
</div>

### VPValue() {#a158b4257d3512747671d3226584548a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPValue::VPValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * UV=nullptr)</td>
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

<p>Create a live-in <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="#a8f2e5c044b5e7aad2e59cda1f5eb8ca8">VPValue</a> and <a href="#a76d9dc21ea5c62699960a935401a75edaaf4f11355938be96aafdf7984e992aeb">VPValueSC</a>.</p>

</div>
</div>

### VPValue() {#abeb35c15d78e11c21695a4b3fc87139f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPValue::VPValue (<a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a> * Def, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * UV=nullptr)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> for a <span class="doxyComputerOutput">Def</span> which is a subclass of <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="#af11c09a3d0bd5aa08472a6be6e654056">Def</a>, <a href="#a5df20a1ac93f5dbd76b326af478e39a8">VPDef</a>, <a href="#a8f2e5c044b5e7aad2e59cda1f5eb8ca8">VPValue</a> and <a href="#a76d9dc21ea5c62699960a935401a75eda642d6930398c4c4b60a0e94899b3ce99">VPVRecipeSC</a>.</p>

</div>
</div>

### VPValue() {#a6c693a626ee926183f3ed7bc29480901}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPValue::VPValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * UV, <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a> * Def)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> for a <span class="doxyComputerOutput">Def</span> which defines multiple values.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="#af11c09a3d0bd5aa08472a6be6e654056">Def</a>, <a href="#a5df20a1ac93f5dbd76b326af478e39a8">VPDef</a>, <a href="#a8f2e5c044b5e7aad2e59cda1f5eb8ca8">VPValue</a> and <a href="#a76d9dc21ea5c62699960a935401a75edaaf4f11355938be96aafdf7984e992aeb">VPValueSC</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VPValue() {#aa05eea4a3203720013826fc5005d6e2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue::~VPValue ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#af11c09a3d0bd5aa08472a6be6e654056">Def</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a73eb8691cf6ac0b34b4e25154c649d26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue &amp; llvm::VPValue::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> &amp;)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#a8f2e5c044b5e7aad2e59cda1f5eb8ca8">VPValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addUser() {#a552567714f74a84ee150e906e8020c5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPValue::addUser (<a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> &amp; User)</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpuser/#af4a3b471097ab37b1672a0d88869ea51">llvm::VPUser::addOperand</a>.</p>

</div>
</div>

### dump() {#a799cc000e147de9394fa660a60c9b4c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPValue::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the value to stderr (for debugging).</p>

<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>, definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#af11c09a3d0bd5aa08472a6be6e654056">Def</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#ab6a4aab2235f2121edb807d1fb261c43">print</a>, <a href="#ae90ca15347282ab58dae4da77c19ab6e">VPRecipeBase</a> and <a href="#a12ceea61a3de5b2f0ff70850f66c5fdc">VPSlotTracker</a>.</p>

</div>
</div>

### getDefiningRecipe() {#a3be8d7833df422f3538ddb13af69bd70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPRecipeBase * VPValue::getDefiningRecipe ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the recipe defining this <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> or nullptr if it is not defined by a recipe, i.e.</p>


<p>is a live-in.</p>


<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="#af11c09a3d0bd5aa08472a6be6e654056">Def</a> and <a href="#ae90ca15347282ab58dae4da77c19ab6e">VPRecipeBase</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vppartialreductionrecipe/#a66409a988f6c39ff0a8d9a5e64e612aa">llvm::VPPartialReductionRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#ac2e757808f897dbb866fac9b8ad2f045">llvm::VPWidenCastRecipe::computeCost</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aa88371693bc18186386b04e8c45a30e4">llvm::VPlanTransforms::createInterleaveGroups</a>, <a href="/web-llvm/docs/api/classes/llvm/vpheaderphirecipe/#ad0e7e250d23299e4e75f62c916bbf681">llvm::VPHeaderPHIRecipe::getBackedgeRecipe</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#aa35433def455d3f76738769247678052">getOptimizableIVOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a064976a6c7458b10c24021b7334cec2a">llvm::vputils::getOrCreateVPValueForSCEVExpr</a>, <a href="#a12efb19adb90f6e29d21f089f36858f1">hasDefiningRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#aebed30683f6b89d62f06d2a10786c2e3">llvm::VPWidenIntOrFpInductionRecipe::isCanonical</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#a50b9bc5e656f43fdb704a6847d679973">isDefinedInsideLoopRegions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a002a77cdbc23293b8f7a8458ffd0f905">llvm::vputils::isUniformAfterVectorization</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a13368acf4fbb5816c3d82099b11519b1">preparePlanForMainVectorLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#ab5d43362c1fefd60d9bfcc1e28ba4688">recursivelyDeleteDeadRecipes</a>.</p>

</div>
</div>

### getDefiningRecipe() {#a5344249bc3b9217704a061c64003f1b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VPRecipeBase * VPValue::getDefiningRecipe ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="#af11c09a3d0bd5aa08472a6be6e654056">Def</a> and <a href="#ae90ca15347282ab58dae4da77c19ab6e">VPRecipeBase</a>.</p>

</div>
</div>

### getLiveInIRValue() {#ac6f0bd9ed63fe4a784697d73ae3b6fa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::VPValue::getLiveInIRValue ()</td>
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

<p>Returns the underlying IR value, if this <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> is defined outside the scope of <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>.</p>


<p>Returns nullptr if the <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> is defined by a <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a> inside a <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>.</p>


<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5fe7dd2466300bd8747d81384a7ced5d">getUnderlyingValue</a> and <a href="#add6179d3564ac5ea4736366b93d23829">isLiveIn</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe/#a6def10381cc09d92342a6846fe1174e0">llvm::VPHistogramRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpderivedivrecipe/#a0f37fe11b57d14686c7ca5e7a3846174">llvm::VPDerivedIVRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#ad481483dac767c09d773266ba8b877e5">llvm::VPReductionPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#aa9790ed243f5fd6c42b4b95453401d84">llvm::VPWidenCallRecipe::getCalledScalarFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#aa35433def455d3f76738769247678052">getOptimizableIVOf</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#ac8744d8abf2a7ed185cc14f0a305cf8e">llvm::VPCanonicalIVPHIRecipe::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpderivedivrecipe/#a7cda2537b71f969625ba49ea583a70f4">llvm::VPDerivedIVRecipe::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#aebed30683f6b89d62f06d2a10786c2e3">llvm::VPWidenIntOrFpInductionRecipe::isCanonical</a>, <a href="/web-llvm/docs/api/structs/llvm/vplanpatternmatch/specific-intval/#afaa3726bf59f26e6b1040f80c99167aa">llvm::VPlanPatternMatch::specific_intval&lt; BitWidth &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a3a573419fed83f23b6bf70ac6731dbfa">llvm::VPlanTransforms::optimizeInductionExitUsers</a> and <a href="/web-llvm/docs/api/classes/anonymous-vplanunroll-cpp-/unrollstate/#a9965cb8e010ad82f02434a0762cddf1e">anonymous{VPlanUnroll.cpp}::UnrollState::unrollBlock</a>.</p>

</div>
</div>

### getLiveInIRValue() {#a509b131fd99a369f60da8778715edd78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * llvm::VPValue::getLiveInIRValue ()</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5fe7dd2466300bd8747d81384a7ced5d">getUnderlyingValue</a> and <a href="#add6179d3564ac5ea4736366b93d23829">isLiveIn</a>.</p>

</div>
</div>

### getNumUsers() {#ac3acda1aa682fbb8f8b95b0816eea879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VPValue::getNumUsers ()</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#ac2e757808f897dbb866fac9b8ad2f045">llvm::VPWidenCastRecipe::computeCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#ac967ad551e77554a15e20cac14877ac7">createReplicateRegion</a>, <a href="#a55617754bef8dbf15bdc3a053f987592">hasMoreThanOneUniqueUser</a>, <a href="#ae3773dd8f9c831f0dde091319b2ff7d0">replaceUsesWithIf</a> and <a href="/web-llvm/docs/api/classes/llvm/vplan/#a9bb77d906fd1ae7e241f0c95dcba094b">llvm::VPlan::resetTripCount</a>.</p>

</div>
</div>

### getUnderlyingValue() {#a5fe7dd2466300bd8747d81384a7ced5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::VPValue::getUnderlyingValue ()</td>
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

<p>Return the underlying <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> attached to this <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#a627c1770437a2bfe04bb3aa331bbb40e">UnderlyingVal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpblendrecipe/#ad05094de15d05295d9e769d815cd076d">llvm::VPBlendRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#a23c6cd965aca4e811f1d5b0e5b7eb204">llvm::VPWidenCallRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#aeeba8e3d6e6936847e0ca7ceffab9937">llvm::VPWidenCastRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#a5eac4b4a3d8c1941d57b6c10750e72d7">llvm::VPWidenIntrinsicRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a004ecf8ed4165883d4dfa06716dd72c9">llvm::VPInstruction::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#a4ae4aad7b718e68d4c42e2fde66934f4">llvm::VPReplicateRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#ac2e757808f897dbb866fac9b8ad2f045">llvm::VPWidenCastRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#ae8d6a4dd88f6b0c4ac0c4c8a46b024e0">llvm::VPWidenIntrinsicRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a0075161c54fc525d16130fa2e1891ad2">llvm::VPWidenRecipe::computeCost</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#a7805b21c1397d70002fd216481351f5e">llvm::VPWidenSelectRecipe::computeCost</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aa0f143b8d4693978b984f0639c90e508">llvm::VPlanTransforms::dropPoisonGeneratingRecipes</a>, <a href="/web-llvm/docs/api/classes/llvm/vppredinstphirecipe/#a3e63796e123d5ba9cbfa023983328c37">llvm::VPPredInstPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#acd93ffe413319e78d7c62688cc86eb6c">llvm::VPWidenCallRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#a9b432a2a53b6ec71e9290e6f9d7582ea">llvm::VPWidenCastRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a703a08e4f8a8f64b8be733d194070cd1">llvm::VPWidenEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#ad6ab589f9da183bfc7227344c30aab78">llvm::VPWidenIntrinsicRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a1217df326ed753111e60d3eaef272ded">llvm::VPWidenRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#a8ab6a201a32f4db51d8f030c5d3ba5c6">llvm::VPWidenSelectRecipe::execute</a>, <a href="#ac6f0bd9ed63fe4a784697d73ae3b6fa0">getLiveInIRValue</a>, <a href="#a509b131fd99a369f60da8778715edd78">getLiveInIRValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwideninductionrecipe/#a63ba76fa3f0c613d353a9b5e21545259">llvm::VPWidenInductionRecipe::getPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpsingledefrecipe/#a12b12fbdf160f2cf70973e09adbf97d4">llvm::VPSingleDefRecipe::getUnderlyingInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/vpsingledefrecipe/#a43da478ef007f34b64ed7692eb595dce">llvm::VPSingleDefRecipe::getUnderlyingInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenphirecipe/#a62f66120ee7769cdadceaaf593e365de">llvm::VPWidenPHIRecipe::print</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae61793492431f138869f097a5f31bd32">llvm::VPlanTransforms::truncateToMinimalBitwidths</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad210afaefb4884ac5008dd5fbaf1cbf8">llvm::VPlanTransforms::VPInstructionsToVPRecipes</a> and <a href="/web-llvm/docs/api/classes/llvm/vpreductionevlrecipe/#ad028e9af49070bb3368ec53b2cd816cd">llvm::VPReductionEVLRecipe::VPReductionEVLRecipe</a>.</p>

</div>
</div>

### getVPValueID() {#a3594c25bd5133d4ebdae3b0ff37a86c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VPValue::getVPValueID ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the concrete type of this object. This is used to implement the classof checks. This should not be used for any other purpose, as the values may change as LLVM evolves.</p></dd>
</dl>


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

### hasDefiningRecipe() {#a12efb19adb90f6e29d21f089f36858f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPValue::hasDefiningRecipe ()</td>
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

<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> is defined by a recipe.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#a3be8d7833df422f3538ddb13af69bd70">getDefiningRecipe</a>.</p>


<p>Referenced by <a href="#add6179d3564ac5ea4736366b93d23829">isLiveIn</a>.</p>

</div>
</div>

### hasMoreThanOneUniqueUser() {#a55617754bef8dbf15bdc3a053f987592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPValue::hasMoreThanOneUniqueUser ()</td>
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

<p>Returns true if the value has more than one unique user.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="#ac3acda1aa682fbb8f8b95b0816eea879">getNumUsers</a>, <a href="#ac1edef8decf10105d95e9d9679643e5b">user_begin</a> and <a href="#ad78092033a17c1ba2ac36048f918b220">user_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#ac2e757808f897dbb866fac9b8ad2f045">llvm::VPWidenCastRecipe::computeCost</a>.</p>

</div>
</div>

### isDefinedOutsideLoopRegions() {#a26ee9845ed3014dd45095ff2493b51b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPValue::isDefinedOutsideLoopRegions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> is defined outside any loop region.</p>

<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>, definition at line 1416 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#a50b9bc5e656f43fdb704a6847d679973">isDefinedInsideLoopRegions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a0075161c54fc525d16130fa2e1891ad2">llvm::VPWidenRecipe::computeCost</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#a7805b21c1397d70002fd216481351f5e">llvm::VPWidenSelectRecipe::computeCost</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#a00ce0b6e8acb6fcc3018746c7f4b77bf">llvm::VPWidenSelectRecipe::isInvariantCond</a> and <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a002a77cdbc23293b8f7a8458ffd0f905">llvm::vputils::isUniformAfterVectorization</a>.</p>

</div>
</div>

### isLiveIn() {#add6179d3564ac5ea4736366b93d23829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPValue::isLiveIn ()</td>
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

<p>Returns true if this <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> is a live-in, i.e. defined outside the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Reference <a href="#a12efb19adb90f6e29d21f089f36858f1">hasDefiningRecipe</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe/#a6def10381cc09d92342a6846fe1174e0">llvm::VPHistogramRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#ac2e757808f897dbb866fac9b8ad2f045">llvm::VPWidenCastRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#ad326bf7574f239b4177d077e513403aa">llvm::VPIRInstruction::extractLastLaneOfOperand</a>, <a href="#ac6f0bd9ed63fe4a784697d73ae3b6fa0">getLiveInIRValue</a>, <a href="#a509b131fd99a369f60da8778715edd78">getLiveInIRValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#aa35433def455d3f76738769247678052">getOptimizableIVOf</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ac38d49d70b5f78779e83abdf4dcb4be0">llvm::VPlan::getOrAddLiveIn</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ac2fcd61c17c94d7e9d10b24b718c812e">llvm::VPlanTransforms::handleUncountableEarlyExit</a> and <a href="/web-llvm/docs/api/structs/llvm/vplanpatternmatch/specific-intval/#afaa3726bf59f26e6b1040f80c99167aa">llvm::VPlanPatternMatch::specific_intval&lt; BitWidth &gt;::match</a>.</p>

</div>
</div>

### print() {#ab6a4aab2235f2121edb807d1fb261c43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPValue::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/vpslottracker">VPSlotTracker</a> &amp; Tracker)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="#af11c09a3d0bd5aa08472a6be6e654056">Def</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#a3fc47e93505e87044e0861e4142eca20">printAsOperand</a>, <a href="#ae90ca15347282ab58dae4da77c19ab6e">VPRecipeBase</a> and <a href="#a12ceea61a3de5b2f0ff70850f66c5fdc">VPSlotTracker</a>.</p>


<p>Referenced by <a href="#a799cc000e147de9394fa660a60c9b4c9">dump</a>.</p>

</div>
</div>

### printAsOperand() {#a3fc47e93505e87044e0861e4142eca20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPValue::printAsOperand (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/vpslottracker">VPSlotTracker</a> &amp; Tracker)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>, definition at line 1451 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpslottracker/#a5a7e7a1fc5386a94fa15cc6e157d7b79">llvm::VPSlotTracker::getOrCreateName</a> and <a href="#a12ceea61a3de5b2f0ff70850f66c5fdc">VPSlotTracker</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpactivelanemaskphirecipe/#af47ca872e4ed34916046cb05efe31520">llvm::VPActiveLaneMaskPHIRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblendrecipe/#a09354bbed6835f538ce6b7b995a02b46">llvm::VPBlendRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#aec4269de8eafb1f6c92c574dc294c4e7">llvm::VPCanonicalIVPHIRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpderivedivrecipe/#a26e4971aa029b70786933757974a302b">llvm::VPDerivedIVRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpevlbasedivphirecipe/#a5d5b65c20b3d92c79eb49194a6d14549">llvm::VPEVLBasedIVPHIRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpexpandscevrecipe/#acb774403458c549835dccf52917a0081">llvm::VPExpandSCEVRecipe::print</a>, <a href="/web-llvm/docs/api/structs/llvm/vpfirstorderrecurrencephirecipe/#ace0ce61d3eaf2f2269401946cea45402">llvm::VPFirstOrderRecurrencePHIRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe/#afc22e4ac9c148e2145862b17b9aa3f98">llvm::VPHistogramRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#aca839409ad4f4fb66241f6b97da6674f">llvm::VPInstruction::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#a942db1b770fa4cb70c66a2546d88cfb0">llvm::VPInterleaveRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vppartialreductionrecipe/#a547b8cb4c97345c9b9f78fbcd4b4da89">llvm::VPPartialReductionRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vppredinstphirecipe/#ac2926669bdf000e31cf50efdab898bac">llvm::VPPredInstPHIRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionevlrecipe/#aee1dbc25df0d2b70bd4eb984cd3be380">llvm::VPReductionEVLRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#ab8d22b8717052bd87b3d06329bc16313">llvm::VPReductionPHIRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a52161486f40f867a8767dc3fef77ee9d">llvm::VPReductionRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#a202af2dd775be9a857e92e8ca6190b4f">llvm::VPReplicateRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreversevectorpointerrecipe/#a9c7a98f9a6cf962c378e7e733295a009">llvm::VPReverseVectorPointerRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarcastrecipe/#a344cb72b5808ac915cbb3ca2ab53d6e1">llvm::VPScalarCastRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#a05c6e525343e482ff033cae3e624e752">llvm::VPScalarIVStepsRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarphirecipe/#a1857ef1592a73e3a1458f635fb407cc3">llvm::VPScalarPHIRecipe::print</a>, <a href="#ab6a4aab2235f2121edb807d1fb261c43">print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvectorpointerrecipe/#a240688a9252bdfe411b157159b5aaf69">llvm::VPVectorPointerRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#a039c5bd63f390c0b66e2548b69a372c5">llvm::VPWidenCallRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencanonicalivrecipe/#a249155094ad547ed977e3c3517b45fb8">llvm::VPWidenCanonicalIVRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#a30fd23ee3def3f12fad8496e85755c2a">llvm::VPWidenCastRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a64949951a81f6c67ecbd51ad90374828">llvm::VPWidenEVLRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidengeprecipe/#a0bc2944c24608efc8476b4bb1bc5606f">llvm::VPWidenGEPRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#aed59fc8e16abed2a289c006b347f354f">llvm::VPWidenIntOrFpInductionRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#a7a2ddcac88e22ed8328c1dfbdac24e06">llvm::VPWidenIntrinsicRecipe::print</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a86fd40dcbb7bf4bd5c2765ff07353fef">llvm::VPWidenLoadEVLRecipe::print</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#ac293be3f7d76772b820f58925b6b14e1">llvm::VPWidenLoadRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenphirecipe/#a62f66120ee7769cdadceaaf593e365de">llvm::VPWidenPHIRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#acb6e3f81767df2fcf8a7d2875cda28d4">llvm::VPWidenPointerInductionRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a5ad4e4df14b5a3c6905892a8f4bcb580">llvm::VPWidenRecipe::print</a> and <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#a75740005a7cfb534940606c60654527e">llvm::VPWidenSelectRecipe::print</a>.</p>

</div>
</div>

### removeUser() {#a44c1ae68f3e8c2570e1b1ffc8962c4f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPValue::removeUser (<a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> &amp; User)</td>
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

<p>Remove a single <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/user">User</a></span> from the list of users.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### replaceAllUsesWith() {#abaad22a81f7fa4ce5b60ec619ac14c37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPValue::replaceAllUsesWith (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * New)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>, definition at line 1419 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="#ae3773dd8f9c831f0dde091319b2ff7d0">replaceUsesWithIf</a> and <a href="#a8f2e5c044b5e7aad2e59cda1f5eb8ca8">VPValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae1d2d60cd9edd9f7ca98c50789747c95">llvm::VPlanTransforms::addActiveLaneMask</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aa88371693bc18186386b04e8c45a30e4">llvm::VPlanTransforms::createInterleaveGroups</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#ac967ad551e77554a15e20cac14877ac7">createReplicateRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6bc9d4e47e8a41e60f4bedae712f0c03">legalizeAndOptimizeInductions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aae23f7e6fc37b0f1bb756f938023512c">preparePlanForEpilogueVectorLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#aefd03ef5fc77c520e27fe794e8ec93e9">removeRedundantCanonicalIVs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a2ff7a57c84a06ee83b0a28763db85c3f">removeRedundantInductionCasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a842c12e686e91a515dfd30a4bf70d740">simplifyRecipe</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5f39858b5d6d72b92c138916c64c90ba">transformRecipestoEVLRecipes</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae61793492431f138869f097a5f31bd32">llvm::VPlanTransforms::truncateToMinimalBitwidths</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad210afaefb4884ac5008dd5fbaf1cbf8">llvm::VPlanTransforms::VPInstructionsToVPRecipes</a>.</p>

</div>
</div>

### replaceUsesWithIf() {#ae3773dd8f9c831f0dde091319b2ff7d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPValue::replaceUsesWithIf (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * New, <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> &amp;U, unsigned Idx)&gt; ShouldReplace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Go through the uses list for this <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> and make each use point to <span class="doxyComputerOutput">New</span> if the callback ShouldReplace returns true for the given use specified by a pair of (<a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a>, the use index).</p>

<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>, definition at line 1423 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="#ac3acda1aa682fbb8f8b95b0816eea879">getNumUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a5fa9b8e1842b354f64c1ba6be0a4a17f">llvm::User::setOperand</a> and <a href="#a8f2e5c044b5e7aad2e59cda1f5eb8ca8">VPValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a4b251734aba716917922f4ab216436c1">mergeReplicateRegionsIntoSuccessors</a>, <a href="#abaad22a81f7fa4ce5b60ec619ac14c37">replaceAllUsesWith</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a1536feae2abb3570ac032768a53ddd00">sinkScalarOperands</a>.</p>

</div>
</div>

### setUnderlyingValue() {#a9739b6fa8242398fd51cb4e77a2447d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPValue::setUnderlyingValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a627c1770437a2bfe04bb3aa331bbb40e">UnderlyingVal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#accbbcc76f9eb947b3804ad96beb2bbd2">llvm::VPBuilder::createNaryOp</a>.</p>

</div>
</div>

### user\_begin() {#ac1edef8decf10105d95e9d9679643e5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">user_iterator llvm::VPValue::user_begin ()</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#ac2e757808f897dbb866fac9b8ad2f045">llvm::VPWidenCastRecipe::computeCost</a>, <a href="#a55617754bef8dbf15bdc3a053f987592">hasMoreThanOneUniqueUser</a>, <a href="#af0932bb43954178036c87ea2ee5f112c">users</a> and <a href="#a6dfe15601746d1e08fb1dfc56c8d673f">users</a>.</p>

</div>
</div>

### user\_begin() {#a4eb38cba0f7f349041524415fca4ded2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_user_iterator llvm::VPValue::user_begin ()</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

### user\_end() {#ad78092033a17c1ba2ac36048f918b220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">user_iterator llvm::VPValue::user_end ()</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Referenced by <a href="#a55617754bef8dbf15bdc3a053f987592">hasMoreThanOneUniqueUser</a>, <a href="#af0932bb43954178036c87ea2ee5f112c">users</a> and <a href="#a6dfe15601746d1e08fb1dfc56c8d673f">users</a>.</p>

</div>
</div>

### user\_end() {#aabf7ce5dc1f33680e2aa4d07d2ef4da5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_user_iterator llvm::VPValue::user_end ()</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

### users() {#af0932bb43954178036c87ea2ee5f112c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">user_range llvm::VPValue::users ()</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="#ac1edef8decf10105d95e9d9679643e5b">user_begin</a> and <a href="#ad78092033a17c1ba2ac36048f918b220">user_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae1d2d60cd9edd9f7ca98c50789747c95">llvm::VPlanTransforms::addActiveLaneMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a8d0c6052d21638f0a385e226db3bd92f">collectAllHeaderMasks</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblendrecipe/#a0dc849c5a55d8fc876ea6deca991b264">llvm::VPBlendRecipe::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#aefd03ef5fc77c520e27fe794e8ec93e9">removeRedundantCanonicalIVs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a2ff7a57c84a06ee83b0a28763db85c3f">removeRedundantInductionCasts</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#af0ce1d62aef3b8e6a79ebe1703f5a7d2">llvm::VPReplicateRecipe::shouldPack</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a4a5b1db18197a65d0f6a487f2e236921">sinkRecurrenceUsersAfterPrevious</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a1536feae2abb3570ac032768a53ddd00">sinkScalarOperands</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5f39858b5d6d72b92c138916c64c90ba">transformRecipestoEVLRecipes</a>.</p>

</div>
</div>

### users() {#a6dfe15601746d1e08fb1dfc56c8d673f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_user_range llvm::VPValue::users ()</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>References <a href="#ac1edef8decf10105d95e9d9679643e5b">user_begin</a> and <a href="#ad78092033a17c1ba2ac36048f918b220">user_end</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Def {#af11c09a3d0bd5aa08472a6be6e654056}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPDef* llvm::VPValue::Def</td>
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

<p>Pointer to the <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a> that defines this <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>.</p>


<p>If it is nullptr, the <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> is not defined by any recipe modeled in <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>.</p>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Referenced by <a href="#a799cc000e147de9394fa660a60c9b4c9">dump</a>, <a href="#a3be8d7833df422f3538ddb13af69bd70">getDefiningRecipe</a>, <a href="#a5344249bc3b9217704a061c64003f1b0">getDefiningRecipe</a>, <a href="#ab6a4aab2235f2121edb807d1fb261c43">print</a>, <a href="#a8f2e5c044b5e7aad2e59cda1f5eb8ca8">VPValue</a>, <a href="#a6c693a626ee926183f3ed7bc29480901">VPValue</a>, <a href="#abeb35c15d78e11c21695a4b3fc87139f">VPValue</a> and <a href="#aa05eea4a3203720013826fc5005d6e2f">~VPValue</a>.</p>

</div>
</div>

### UnderlyingVal {#a627c1770437a2bfe04bb3aa331bbb40e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::VPValue::UnderlyingVal</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>


<p>Referenced by <a href="#a5fe7dd2466300bd8747d81384a7ced5d">getUnderlyingValue</a>, <a href="#a9739b6fa8242398fd51cb4e77a2447d7">setUnderlyingValue</a> and <a href="#a8f2e5c044b5e7aad2e59cda1f5eb8ca8">VPValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### SubclassID {#a681933024138d939ef31107f17818b83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned char llvm::VPValue::SubclassID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Subclass identifier (for isa/dyn_cast).</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

### Users {#a67cfb52cfa7c1f6ac543ae89077e8c46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;VPUser *, 1&gt; llvm::VPValue::Users</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp">VPlan.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
