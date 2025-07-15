---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-objcarcopts-cpp-/bbstate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BBState` Class Reference

<p>Per-BasicBlock state. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{ObjCARCOpts.cpp}::BBState { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ce3f5b5a04add97c07dc88f808a4d40">top_down_ptr_iterator</a> = decltype(PerPtrTopDown)<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa3c2c44d6e9e852d0a9ce5061227c23">const_top_down_ptr_iterator</a> = decltype(PerPtrTopDown)<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">::const_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8a067a8a3e9b76687a1fe2489b5112f">bottom_up_ptr_iterator</a> = decltype(PerPtrBottomUp)<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af513739f27cb96666f62883d17b488b5">const_bottom_up_ptr_iterator</a> = decltype(PerPtrBottomUp)<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">::const_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a535a25253435b7af798da77f854d5cc3">edge_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt;<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">::const_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bef84b7e585b367ff9881b532552560">BBState</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2ce3f5b5a04add97c07dc88f808a4d40">top_down_ptr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24ad33e93faa865233c3742130a7e821">top_down_ptr_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2ce3f5b5a04add97c07dc88f808a4d40">top_down_ptr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d6b6a78cf25b2f70736f9f3873aa2e5">top_down_ptr_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aaa3c2c44d6e9e852d0a9ce5061227c23">const_top_down_ptr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21dbee30031c6b2ace1822f68ace1c64">top_down_ptr_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aaa3c2c44d6e9e852d0a9ce5061227c23">const_top_down_ptr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a267de37110bfa333b34162bc28a5fa4a">top_down_ptr_end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23f111de43f140e5cc4263292d8bc3b2">hasTopDownPtrs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7643bad194aea53c864780d1cad3d932">top_down_ptr_list_size</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad8a067a8a3e9b76687a1fe2489b5112f">bottom_up_ptr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44b4ed3c4f497a6de469679cb3848ebd">bottom_up_ptr_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad8a067a8a3e9b76687a1fe2489b5112f">bottom_up_ptr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5ac0d8664a0a0c00d452f4f9b662817">bottom_up_ptr_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af513739f27cb96666f62883d17b488b5">const_bottom_up_ptr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabe24534e9b4869b0c742ac432b2d381">bottom_up_ptr_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af513739f27cb96666f62883d17b488b5">const_bottom_up_ptr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77716e8423e3c3df2153c8f4709b7d8e">bottom_up_ptr_end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80573fc9db8d96d586e71cb492d6bd20">hasBottomUpPtrs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a022ec5629a502cd9e9c83b0f30eb4191">bottom_up_ptr_list_size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80aef00081f07599de8a859c96ff8e29">SetAsEntry</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark this block as being an entry block, which has one path from the entry by definition. <a href="#a80aef00081f07599de8a859c96ff8e29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac93e3d82e2f6680f6fe50172c2f0e7d2">SetAsExit</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark this block as being an exit block, which has one path to an exit by definition. <a href="#ac93e3d82e2f6680f6fe50172c2f0e7d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate">TopDownPtrState</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42276c8fcda0e12cd7fd25b90eb1a1d8">getPtrTopDownState</a> (const Value *Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to find the <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate">PtrState</a> object describing the top down state for pointer Arg. <a href="#a42276c8fcda0e12cd7fd25b90eb1a1d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate">BottomUpPtrState</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6dd134ba25f16cbabcee9775ba42368">getPtrBottomUpState</a> (const Value *Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to find the <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate">PtrState</a> object describing the bottom up state for pointer Arg. <a href="#ae6dd134ba25f16cbabcee9775ba42368">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad8a067a8a3e9b76687a1fe2489b5112f">bottom_up_ptr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82483bea0981a0e53587a61730a89a72">findPtrBottomUpState</a> (const Value *Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to find the <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate">PtrState</a> object describing the bottom up state for pointer Arg. <a href="#a82483bea0981a0e53587a61730a89a72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac93dcc8299d4d4527b33b8961ea717fa">clearBottomUpPointers</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3641e7dbe4fa8121bf99c1ea7a8049ca">clearTopDownPointers</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affacfb81e5c97a55889323f5e6f5aacf">GetAllPathCountWithOverflow</a> (unsigned &amp;PathCount) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the number of possible unique paths from an entry to an exit which pass through this block. <a href="#affacfb81e5c97a55889323f5e6f5aacf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a535a25253435b7af798da77f854d5cc3">edge_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ca41414437da0262a799ea0d91eea6">pred_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a535a25253435b7af798da77f854d5cc3">edge_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d362fec63555f74b19daeb03745e848">pred_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a535a25253435b7af798da77f854d5cc3">edge_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac54467fda18cd54fca9f14f1d0992ee6">succ_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a535a25253435b7af798da77f854d5cc3">edge_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f9b4be7b81002bd6cc42be2a71c19c8">succ_end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed2c0df9216eab3bef23b02901a58919">addSucc</a> (BasicBlock *Succ)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf56f09ced8f685a4fa522b02e44e544">addPred</a> (BasicBlock *Pred)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a079a33bcf8b5c214f74bbffbc8f3dbf1">isExit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#ga9346e283861508359c876cda13cfd7d8">InitFromPred</a> (const BBState &amp;Other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#ga00e90d16c74d3fe8f597efab1f0d1104">InitFromSucc</a> (const BBState &amp;Other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#ga43bdfa3a92d9eaff97326d0756b88379">MergePred</a> (const BBState &amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The top-down traversal uses this to merge information about predecessors to form the initial state for a new block. <a href="/web-llvm/docs/api/groups/arcopt/#ga43bdfa3a92d9eaff97326d0756b88379">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#gacf2e521ed66ec3e1c4292beb27bdb696">MergeSucc</a> (const BBState &amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The bottom-up traversal uses this to merge information about successors to form the initial state for a new block. <a href="/web-llvm/docs/api/groups/arcopt/#gacf2e521ed66ec3e1c4292beb27bdb696">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a831d27e199283bc21e1330957859ace6">TopDownPathCount</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of unique control paths from the entry which can reach this block. <a href="#a831d27e199283bc21e1330957859ace6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5af3618b9b1d845ab7f8430a415a2da1">BottomUpPathCount</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of unique control paths to exits from this block. <a href="#a5af3618b9b1d845ab7f8430a415a2da1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blotmapvector">BlotMapVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate">TopDownPtrState</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cec4dee0866baed839505009e16853e">PerPtrTopDown</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The top-down traversal uses this to record information known about a pointer at the bottom of each block. <a href="#a2cec4dee0866baed839505009e16853e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blotmapvector">BlotMapVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate">BottomUpPtrState</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83dc354d03265f234c057ff8c1313646">PerPtrBottomUp</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The bottom-up traversal uses this to record information known about a pointer at the top of each block. <a href="#a83dc354d03265f234c057ff8c1313646">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b589e1f3b0f45d3d6f346bff4074978">Preds</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Effective predecessors of the current block ignoring ignorable edges and ignored backedges. <a href="#a5b589e1f3b0f45d3d6f346bff4074978">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0b91a347d5a9a32b9a9d652f9e3a61e">Succs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Effective successors of the current block ignoring ignorable edges and ignored backedges. <a href="#aa0b91a347d5a9a32b9a9d652f9e3a61e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/arcopt/#gaf049222c368a7cbc12109fbc79ce8f34">OverflowOccurredValue</a> = 0xffffffff</td>
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

<p>Per-BasicBlock state.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### bottom\_up\_ptr\_iterator {#ad8a067a8a3e9b76687a1fe2489b5112f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{ObjCARCOpts.cpp}::BBState::bottom_up_ptr_iterator =  decltype(PerPtrBottomUp)::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### const\_bottom\_up\_ptr\_iterator {#af513739f27cb96666f62883d17b488b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{ObjCARCOpts.cpp}::BBState::const_bottom_up_ptr_iterator = 
        decltype(PerPtrBottomUp)::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### const\_top\_down\_ptr\_iterator {#aaa3c2c44d6e9e852d0a9ce5061227c23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{ObjCARCOpts.cpp}::BBState::const_top_down_ptr_iterator =  decltype(PerPtrTopDown)::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### edge\_iterator {#a535a25253435b7af798da77f854d5cc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{ObjCARCOpts.cpp}::BBState::edge_iterator =  SmallVectorImpl&lt;BasicBlock *&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### top\_down\_ptr\_iterator {#a2ce3f5b5a04add97c07dc88f808a4d40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{ObjCARCOpts.cpp}::BBState::top_down_ptr_iterator =  decltype(PerPtrTopDown)::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BBState() {#a5bef84b7e585b367ff9881b532552560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ObjCARCOpts.cpp}::BBState::BBState ()</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/arcopt/#gac3778bafa67cdae223698e5bba785a76">ComputePostOrders</a>, <a href="/web-llvm/docs/api/groups/arcopt/#ga9346e283861508359c876cda13cfd7d8">InitFromPred</a>, <a href="/web-llvm/docs/api/groups/arcopt/#ga00e90d16c74d3fe8f597efab1f0d1104">InitFromSucc</a>, <a href="/web-llvm/docs/api/groups/arcopt/#ga43bdfa3a92d9eaff97326d0756b88379">MergePred</a> and <a href="/web-llvm/docs/api/groups/arcopt/#gacf2e521ed66ec3e1c4292beb27bdb696">MergeSucc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addPred() {#abf56f09ced8f685a4fa522b02e44e544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ObjCARCOpts.cpp}::BBState::addPred (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Pred)</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### addSucc() {#aed2c0df9216eab3bef23b02901a58919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ObjCARCOpts.cpp}::BBState::addSucc (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Succ)</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### bottom\_up\_ptr\_begin() {#a44b4ed3c4f497a6de469679cb3848ebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bottom_up_ptr_iterator anonymous{ObjCARCOpts.cpp}::BBState::bottom_up_ptr_begin ()</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>


<p>Referenced by <a href="#a022ec5629a502cd9e9c83b0f30eb4191">bottom_up_ptr_list_size</a> and <a href="/web-llvm/docs/api/groups/arcopt/#gacf2e521ed66ec3e1c4292beb27bdb696">MergeSucc</a>.</p>

</div>
</div>

### bottom\_up\_ptr\_begin() {#aabe24534e9b4869b0c742ac432b2d381}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_bottom_up_ptr_iterator anonymous{ObjCARCOpts.cpp}::BBState::bottom_up_ptr_begin ()</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### bottom\_up\_ptr\_end() {#aa5ac0d8664a0a0c00d452f4f9b662817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bottom_up_ptr_iterator anonymous{ObjCARCOpts.cpp}::BBState::bottom_up_ptr_end ()</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>


<p>Referenced by <a href="#a022ec5629a502cd9e9c83b0f30eb4191">bottom_up_ptr_list_size</a> and <a href="/web-llvm/docs/api/groups/arcopt/#gacf2e521ed66ec3e1c4292beb27bdb696">MergeSucc</a>.</p>

</div>
</div>

### bottom\_up\_ptr\_end() {#a77716e8423e3c3df2153c8f4709b7d8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_bottom_up_ptr_iterator anonymous{ObjCARCOpts.cpp}::BBState::bottom_up_ptr_end ()</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### bottom\_up\_ptr\_list\_size() {#a022ec5629a502cd9e9c83b0f30eb4191}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ObjCARCOpts.cpp}::BBState::bottom_up_ptr_list_size ()</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>


<p>References <a href="#a44b4ed3c4f497a6de469679cb3848ebd">bottom_up_ptr_begin</a> and <a href="#aa5ac0d8664a0a0c00d452f4f9b662817">bottom_up_ptr_end</a>.</p>

</div>
</div>

### clearBottomUpPointers() {#ac93dcc8299d4d4527b33b8961ea717fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ObjCARCOpts.cpp}::BBState::clearBottomUpPointers ()</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/arcopt/#gacf2e521ed66ec3e1c4292beb27bdb696">MergeSucc</a>.</p>

</div>
</div>

### clearTopDownPointers() {#a3641e7dbe4fa8121bf99c1ea7a8049ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ObjCARCOpts.cpp}::BBState::clearTopDownPointers ()</td>
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



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/arcopt/#ga43bdfa3a92d9eaff97326d0756b88379">MergePred</a>.</p>

</div>
</div>

### findPtrBottomUpState() {#a82483bea0981a0e53587a61730a89a72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bottom_up_ptr_iterator anonymous{ObjCARCOpts.cpp}::BBState::findPtrBottomUpState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Arg)</td>
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

<p>Attempt to find the <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate">PtrState</a> object describing the bottom up state for pointer Arg.</p>

<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### GetAllPathCountWithOverflow() {#affacfb81e5c97a55889323f5e6f5aacf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ObjCARCOpts.cpp}::BBState::GetAllPathCountWithOverflow (unsigned &amp; PathCount)</td>
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

<p>Compute the number of possible unique paths from an entry to an exit which pass through this block.</p>


<p>This is only valid after both the top-down and bottom-up traversals are complete.</p>


<p>Returns true if overflow occurred. Returns false if overflow did not occur.</p>


<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/groups/arcopt/#gaf049222c368a7cbc12109fbc79ce8f34">OverflowOccurredValue</a>.</p>

</div>
</div>

### getPtrBottomUpState() {#ae6dd134ba25f16cbabcee9775ba42368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BottomUpPtrState &amp; anonymous{ObjCARCOpts.cpp}::BBState::getPtrBottomUpState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Arg)</td>
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

<p>Attempt to find the <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate">PtrState</a> object describing the bottom up state for pointer Arg.</p>


<p>Return a new initialized <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate">PtrState</a> describing the bottom up state for Arg if we do not find one.</p>


<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### getPtrTopDownState() {#a42276c8fcda0e12cd7fd25b90eb1a1d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TopDownPtrState &amp; anonymous{ObjCARCOpts.cpp}::BBState::getPtrTopDownState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Arg)</td>
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

<p>Attempt to find the <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate">PtrState</a> object describing the top down state for pointer Arg.</p>


<p>Return a new initialized <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate">PtrState</a> describing the top down state for Arg if we do not find one.</p>


<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### hasBottomUpPtrs() {#a80573fc9db8d96d586e71cb492d6bd20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ObjCARCOpts.cpp}::BBState::hasBottomUpPtrs ()</td>
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



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### hasTopDownPtrs() {#a23f111de43f140e5cc4263292d8bc3b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ObjCARCOpts.cpp}::BBState::hasTopDownPtrs ()</td>
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



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### isExit() {#a079a33bcf8b5c214f74bbffbc8f3dbf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ObjCARCOpts.cpp}::BBState::isExit ()</td>
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



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### pred\_begin() {#af9ca41414437da0262a799ea0d91eea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">edge_iterator anonymous{ObjCARCOpts.cpp}::BBState::pred_begin ()</td>
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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/arcopt/#gac3778bafa67cdae223698e5bba785a76">ComputePostOrders</a>.</p>

</div>
</div>

### pred\_end() {#a9d362fec63555f74b19daeb03745e848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">edge_iterator anonymous{ObjCARCOpts.cpp}::BBState::pred_end ()</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### SetAsEntry() {#a80aef00081f07599de8a859c96ff8e29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ObjCARCOpts.cpp}::BBState::SetAsEntry ()</td>
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

<p>Mark this block as being an entry block, which has one path from the entry by definition.</p>

<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### SetAsExit() {#ac93e3d82e2f6680f6fe50172c2f0e7d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ObjCARCOpts.cpp}::BBState::SetAsExit ()</td>
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

<p>Mark this block as being an exit block, which has one path to an exit by definition.</p>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### succ\_begin() {#ac54467fda18cd54fca9f14f1d0992ee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">edge_iterator anonymous{ObjCARCOpts.cpp}::BBState::succ_begin ()</td>
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



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### succ\_end() {#a0f9b4be7b81002bd6cc42be2a71c19c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">edge_iterator anonymous{ObjCARCOpts.cpp}::BBState::succ_end ()</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### top\_down\_ptr\_begin() {#a24ad33e93faa865233c3742130a7e821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">top_down_ptr_iterator anonymous{ObjCARCOpts.cpp}::BBState::top_down_ptr_begin ()</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/arcopt/#ga43bdfa3a92d9eaff97326d0756b88379">MergePred</a> and <a href="#a7643bad194aea53c864780d1cad3d932">top_down_ptr_list_size</a>.</p>

</div>
</div>

### top\_down\_ptr\_begin() {#a21dbee30031c6b2ace1822f68ace1c64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_top_down_ptr_iterator anonymous{ObjCARCOpts.cpp}::BBState::top_down_ptr_begin ()</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### top\_down\_ptr\_end() {#a5d6b6a78cf25b2f70736f9f3873aa2e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">top_down_ptr_iterator anonymous{ObjCARCOpts.cpp}::BBState::top_down_ptr_end ()</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/arcopt/#ga43bdfa3a92d9eaff97326d0756b88379">MergePred</a> and <a href="#a7643bad194aea53c864780d1cad3d932">top_down_ptr_list_size</a>.</p>

</div>
</div>

### top\_down\_ptr\_end() {#a267de37110bfa333b34162bc28a5fa4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_top_down_ptr_iterator anonymous{ObjCARCOpts.cpp}::BBState::top_down_ptr_end ()</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### top\_down\_ptr\_list\_size() {#a7643bad194aea53c864780d1cad3d932}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ObjCARCOpts.cpp}::BBState::top_down_ptr_list_size ()</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>


<p>References <a href="#a24ad33e93faa865233c3742130a7e821">top_down_ptr_begin</a> and <a href="#a5d6b6a78cf25b2f70736f9f3873aa2e5">top_down_ptr_end</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BottomUpPathCount {#a5af3618b9b1d845ab7f8430a415a2da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ObjCARCOpts.cpp}::BBState::BottomUpPathCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of unique control paths to exits from this block.</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### PerPtrBottomUp {#a83dc354d03265f234c057ff8c1313646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlotMapVector&lt;const Value *, BottomUpPtrState&gt; anonymous{ObjCARCOpts.cpp}::BBState::PerPtrBottomUp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The bottom-up traversal uses this to record information known about a pointer at the top of each block.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### PerPtrTopDown {#a2cec4dee0866baed839505009e16853e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlotMapVector&lt;const Value *, TopDownPtrState&gt; anonymous{ObjCARCOpts.cpp}::BBState::PerPtrTopDown</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The top-down traversal uses this to record information known about a pointer at the bottom of each block.</p>

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### Preds {#a5b589e1f3b0f45d3d6f346bff4074978}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;BasicBlock *, 2&gt; anonymous{ObjCARCOpts.cpp}::BBState::Preds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Effective predecessors of the current block ignoring ignorable edges and ignored backedges.</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### Succs {#aa0b91a347d5a9a32b9a9d652f9e3a61e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;BasicBlock *, 2&gt; anonymous{ObjCARCOpts.cpp}::BBState::Succs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Effective successors of the current block ignoring ignorable edges and ignored backedges.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

### TopDownPathCount {#a831d27e199283bc21e1330957859ace6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ObjCARCOpts.cpp}::BBState::TopDownPathCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of unique control paths from the entry which can reach this block.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/objcarcopts-cpp">ObjCARCOpts.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
