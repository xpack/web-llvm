---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/objcarc/ptrstate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PtrState` Class

<p>This class summarizes several per-pointer runtime properties which are propagated through the flow graph. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::objcarc::PtrState { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">Transforms/ObjCARC/PtrState.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate">BottomUpPtrState</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate">TopDownPtrState</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accbc43e52e5946ff04312f9d33a68ede">PtrState</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee65472e4d66de6d1d50f8e54fdcf54c">IsKnownSafe</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5bc7cf4cad8226dd41ea81c0946b074">SetKnownSafe</a> (const bool NewValue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a267963a0fff2a1cded48a777816254f0">IsTailCallRelease</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68e4d18a484c49f0cdcab93b7af5fe96">SetTailCallRelease</a> (const bool NewValue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe2f76eb6d73d645667ac26c93e874a4">IsTrackingImpreciseReleases</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab966cfbfc5803c2c9de8290f9c818067">GetReleaseMetadata</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab98722f336af2fea28476dd2c480c8f9">SetReleaseMetadata</a> (MDNode *NewValue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d23fc02a3b5aee419cb4ce3abcf537e">IsCFGHazardAfflicted</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11a0f02bf705457f683e5607b1fd3e29">SetCFGHazardAfflicted</a> (const bool NewValue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f7d5f6394d44b1dca0c23d13625c9c0">SetKnownPositiveRefCount</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75b7969d370fa510130319080bc10426">ClearKnownPositiveRefCount</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41ec3c64229bf8508e9f019eea5d129b">HasKnownPositiveRefCount</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad14c921bb46309b6b0ef0439c44737b8">SetSeq</a> (Sequence NewSeq)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306d">Sequence</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1488167d90017e45843bfae0b00aaf49">GetSeq</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5dabd431e08a0ca459d9d5ac9ef3709">ClearSequenceProgress</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3996894452fd20d95e7135ff0b01f30">ResetSequenceProgress</a> (Sequence NewSeq)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf8b72d488312f8c7229b2beee07e28d">Merge</a> (const PtrState &amp;Other, bool TopDown)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac34dc93e26f9d0d026d6f493beec9ca8">InsertCall</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49bf7d95cbf4a5edc394634d53a42ba0">InsertReverseInsertPt</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e8374268ff00721371c4e0927510d88">ClearReverseInsertPts</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a3ce7e4e153b91ea5d72f2df4cb023a">HasReverseInsertPts</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcarc/rrinfo">RRInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60e312a27952f9db561a969d47cf496b">GetRRInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09c5b919d9e1f9dcef809dee375c8d5f">KnownPositiveRefCount</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the reference count is known to be incremented. <a href="#a09c5b919d9e1f9dcef809dee375c8d5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6e88dbced93e1293da494b9a981b313">Partial</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if we've seen an opportunity for partial RR elimination, such as pushing calls into a CFG triangle or into one side of a CFG diamond. <a href="#af6e88dbced93e1293da494b9a981b313">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b687054dd0937d288747449fea1cb86">Seq</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current position in the sequence. <a href="#a0b687054dd0937d288747449fea1cb86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objcarc/rrinfo">RRInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dd5217efd31b0f4b30ab95d462dd816">RRI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unidirectional information about the current sequence. <a href="#a1dd5217efd31b0f4b30ab95d462dd816">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class summarizes several per-pointer runtime properties which are propagated through the flow graph.</p>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### PtrState() {#accbc43e52e5946ff04312f9d33a68ede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcarc::PtrState::PtrState ()</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306da6e431a7ec0fee74cc2ae9a79bd965122">llvm::objcarc::S_None</a> and <a href="#a0b687054dd0937d288747449fea1cb86">Seq</a>.</p>


<p>Referenced by <a href="#adf8b72d488312f8c7229b2beee07e28d">Merge</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### ClearKnownPositiveRefCount() {#a75b7969d370fa510130319080bc10426}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PtrState::ClearKnownPositiveRefCount ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-cpp">PtrState.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a09c5b919d9e1f9dcef809dee375c8d5f">KnownPositiveRefCount</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#acf48e56d2e2614373b53f03c5bd3c4b8">llvm::objcarc::TopDownPtrState::HandlePotentialAlterRefCount</a> and <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#a58e7f78b0c740eb2f30b8a24ee170f7a">llvm::objcarc::TopDownPtrState::MatchWithRelease</a>.</p>

</div>
</div>

### ClearReverseInsertPts() {#a1e8374268ff00721371c4e0927510d88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcarc::PtrState::ClearReverseInsertPts ()</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Reference <a href="#a1dd5217efd31b0f4b30ab95d462dd816">RRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#a58e7f78b0c740eb2f30b8a24ee170f7a">llvm::objcarc::TopDownPtrState::MatchWithRelease</a> and <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a91ef366645fbd66f709174e3b396fb92">llvm::objcarc::BottomUpPtrState::MatchWithRetain</a>.</p>

</div>
</div>

### ClearSequenceProgress() {#ae5dabd431e08a0ca459d9d5ac9ef3709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcarc::PtrState::ClearSequenceProgress ()</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>References <a href="#ac3996894452fd20d95e7135ff0b01f30">ResetSequenceProgress</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306da6e431a7ec0fee74cc2ae9a79bd965122">llvm::objcarc::S_None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/arcopt/#ga3a319b49d26b9794c0cf855627fc36fa">CheckForUseCFGHazard</a> and <a href="#adf8b72d488312f8c7229b2beee07e28d">Merge</a>.</p>

</div>
</div>

### GetReleaseMetadata() {#ab966cfbfc5803c2c9de8290f9c818067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MDNode * llvm::objcarc::PtrState::GetReleaseMetadata ()</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Reference <a href="#a1dd5217efd31b0f4b30ab95d462dd816">RRI</a>.</p>

</div>
</div>

### GetRRInfo() {#a60e312a27952f9db561a969d47cf496b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RRInfo &amp; llvm::objcarc::PtrState::GetRRInfo ()</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Reference <a href="#a1dd5217efd31b0f4b30ab95d462dd816">RRI</a>.</p>

</div>
</div>

### GetSeq() {#a1488167d90017e45843bfae0b00aaf49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Sequence llvm::objcarc::PtrState::GetSeq ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Reference <a href="#a0b687054dd0937d288747449fea1cb86">Seq</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a004bf866c0303839642a34b82e15eee5">llvm::objcarc::BottomUpPtrState::HandlePotentialAlterRefCount</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#acf48e56d2e2614373b53f03c5bd3c4b8">llvm::objcarc::TopDownPtrState::HandlePotentialAlterRefCount</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a92756d26ffe5c46811ee48f629857ba2">llvm::objcarc::BottomUpPtrState::HandlePotentialUse</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#ad0da3c507a530abd23de4894502b3199">llvm::objcarc::TopDownPtrState::HandlePotentialUse</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a0b6f153e14da3299ec487acbf39e22ae">llvm::objcarc::BottomUpPtrState::InitBottomUp</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#a5e7821981d45cb3fada161fbd0b5b3ae">llvm::objcarc::TopDownPtrState::InitTopDown</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#a58e7f78b0c740eb2f30b8a24ee170f7a">llvm::objcarc::TopDownPtrState::MatchWithRelease</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a91ef366645fbd66f709174e3b396fb92">llvm::objcarc::BottomUpPtrState::MatchWithRetain</a>, <a href="#adf8b72d488312f8c7229b2beee07e28d">Merge</a> and <a href="#ad14c921bb46309b6b0ef0439c44737b8">SetSeq</a>.</p>

</div>
</div>

### HasKnownPositiveRefCount() {#a41ec3c64229bf8508e9f019eea5d129b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcarc::PtrState::HasKnownPositiveRefCount ()</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Reference <a href="#a09c5b919d9e1f9dcef809dee375c8d5f">KnownPositiveRefCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a0b6f153e14da3299ec487acbf39e22ae">llvm::objcarc::BottomUpPtrState::InitBottomUp</a> and <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#a5e7821981d45cb3fada161fbd0b5b3ae">llvm::objcarc::TopDownPtrState::InitTopDown</a>.</p>

</div>
</div>

### HasReverseInsertPts() {#a4a3ce7e4e153b91ea5d72f2df4cb023a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcarc::PtrState::HasReverseInsertPts ()</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Reference <a href="#a1dd5217efd31b0f4b30ab95d462dd816">RRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#acf48e56d2e2614373b53f03c5bd3c4b8">llvm::objcarc::TopDownPtrState::HandlePotentialAlterRefCount</a> and <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a92756d26ffe5c46811ee48f629857ba2">llvm::objcarc::BottomUpPtrState::HandlePotentialUse</a>.</p>

</div>
</div>

### InsertCall() {#ac34dc93e26f9d0d026d6f493beec9ca8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcarc::PtrState::InsertCall (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a1dd5217efd31b0f4b30ab95d462dd816">RRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a0b6f153e14da3299ec487acbf39e22ae">llvm::objcarc::BottomUpPtrState::InitBottomUp</a> and <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#a5e7821981d45cb3fada161fbd0b5b3ae">llvm::objcarc::TopDownPtrState::InitTopDown</a>.</p>

</div>
</div>

### InsertReverseInsertPt() {#a49bf7d95cbf4a5edc394634d53a42ba0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcarc::PtrState::InsertReverseInsertPt (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a1dd5217efd31b0f4b30ab95d462dd816">RRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#acf48e56d2e2614373b53f03c5bd3c4b8">llvm::objcarc::TopDownPtrState::HandlePotentialAlterRefCount</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a92756d26ffe5c46811ee48f629857ba2">llvm::objcarc::BottomUpPtrState::HandlePotentialUse</a> and <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a0b6f153e14da3299ec487acbf39e22ae">llvm::objcarc::BottomUpPtrState::InitBottomUp</a>.</p>

</div>
</div>

### IsCFGHazardAfflicted() {#a8d23fc02a3b5aee419cb4ce3abcf537e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcarc::PtrState::IsCFGHazardAfflicted ()</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Reference <a href="#a1dd5217efd31b0f4b30ab95d462dd816">RRI</a>.</p>

</div>
</div>

### IsKnownSafe() {#aee65472e4d66de6d1d50f8e54fdcf54c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcarc::PtrState::IsKnownSafe ()</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Reference <a href="#a1dd5217efd31b0f4b30ab95d462dd816">RRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/arcopt/#ga5fd3f0408257b1a0df4a029c9b133d6c">CheckForCanReleaseCFGHazard</a> and <a href="/web-llvm/docs/api/groups/arcopt/#ga3a319b49d26b9794c0cf855627fc36fa">CheckForUseCFGHazard</a>.</p>

</div>
</div>

### IsTailCallRelease() {#a267963a0fff2a1cded48a777816254f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcarc::PtrState::IsTailCallRelease ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Reference <a href="#a1dd5217efd31b0f4b30ab95d462dd816">RRI</a>.</p>

</div>
</div>

### IsTrackingImpreciseReleases() {#afe2f76eb6d73d645667ac26c93e874a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcarc::PtrState::IsTrackingImpreciseReleases ()</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Reference <a href="#a1dd5217efd31b0f4b30ab95d462dd816">RRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a91ef366645fbd66f709174e3b396fb92">llvm::objcarc::BottomUpPtrState::MatchWithRetain</a>.</p>

</div>
</div>

### Merge() {#adf8b72d488312f8c7229b2beee07e28d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PtrState::Merge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate">PtrState</a> &amp; Other, bool TopDown)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>, definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-cpp">PtrState.cpp</a>.</p>


<p>References <a href="#ae5dabd431e08a0ca459d9d5ac9ef3709">ClearSequenceProgress</a>, <a href="#a1488167d90017e45843bfae0b00aaf49">GetSeq</a>, <a href="#a09c5b919d9e1f9dcef809dee375c8d5f">KnownPositiveRefCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-cpp/#a01c7014451484f9784e68d42412d1b9c">MergeSeqs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#af6e88dbced93e1293da494b9a981b313">Partial</a>, <a href="#accbc43e52e5946ff04312f9d33a68ede">PtrState</a>, <a href="#a1dd5217efd31b0f4b30ab95d462dd816">RRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306da6e431a7ec0fee74cc2ae9a79bd965122">llvm::objcarc::S_None</a> and <a href="#a0b687054dd0937d288747449fea1cb86">Seq</a>.</p>

</div>
</div>

### ResetSequenceProgress() {#ac3996894452fd20d95e7135ff0b01f30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PtrState::ResetSequenceProgress (<a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306d">Sequence</a> NewSeq)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-cpp">PtrState.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#af6e88dbced93e1293da494b9a981b313">Partial</a>, <a href="#a1dd5217efd31b0f4b30ab95d462dd816">RRI</a> and <a href="#ad14c921bb46309b6b0ef0439c44737b8">SetSeq</a>.</p>


<p>Referenced by <a href="#ae5dabd431e08a0ca459d9d5ac9ef3709">ClearSequenceProgress</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a0b6f153e14da3299ec487acbf39e22ae">llvm::objcarc::BottomUpPtrState::InitBottomUp</a> and <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#a5e7821981d45cb3fada161fbd0b5b3ae">llvm::objcarc::TopDownPtrState::InitTopDown</a>.</p>

</div>
</div>

### SetCFGHazardAfflicted() {#a11a0f02bf705457f683e5607b1fd3e29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcarc::PtrState::SetCFGHazardAfflicted (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool NewValue)</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Reference <a href="#a1dd5217efd31b0f4b30ab95d462dd816">RRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/arcopt/#ga3a319b49d26b9794c0cf855627fc36fa">CheckForUseCFGHazard</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#acf48e56d2e2614373b53f03c5bd3c4b8">llvm::objcarc::TopDownPtrState::HandlePotentialAlterRefCount</a> and <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a92756d26ffe5c46811ee48f629857ba2">llvm::objcarc::BottomUpPtrState::HandlePotentialUse</a>.</p>

</div>
</div>

### SetKnownPositiveRefCount() {#a1f7d5f6394d44b1dca0c23d13625c9c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PtrState::SetKnownPositiveRefCount ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-cpp">PtrState.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a09c5b919d9e1f9dcef809dee375c8d5f">KnownPositiveRefCount</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a0b6f153e14da3299ec487acbf39e22ae">llvm::objcarc::BottomUpPtrState::InitBottomUp</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#a5e7821981d45cb3fada161fbd0b5b3ae">llvm::objcarc::TopDownPtrState::InitTopDown</a> and <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a91ef366645fbd66f709174e3b396fb92">llvm::objcarc::BottomUpPtrState::MatchWithRetain</a>.</p>

</div>
</div>

### SetKnownSafe() {#ad5bc7cf4cad8226dd41ea81c0946b074}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcarc::PtrState::SetKnownSafe (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool NewValue)</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Reference <a href="#a1dd5217efd31b0f4b30ab95d462dd816">RRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a0b6f153e14da3299ec487acbf39e22ae">llvm::objcarc::BottomUpPtrState::InitBottomUp</a> and <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#a5e7821981d45cb3fada161fbd0b5b3ae">llvm::objcarc::TopDownPtrState::InitTopDown</a>.</p>

</div>
</div>

### SetReleaseMetadata() {#ab98722f336af2fea28476dd2c480c8f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcarc::PtrState::SetReleaseMetadata (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * NewValue)</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Reference <a href="#a1dd5217efd31b0f4b30ab95d462dd816">RRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a0b6f153e14da3299ec487acbf39e22ae">llvm::objcarc::BottomUpPtrState::InitBottomUp</a> and <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#a58e7f78b0c740eb2f30b8a24ee170f7a">llvm::objcarc::TopDownPtrState::MatchWithRelease</a>.</p>

</div>
</div>

### SetSeq() {#ad14c921bb46309b6b0ef0439c44737b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PtrState::SetSeq (<a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306d">Sequence</a> NewSeq)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-cpp">PtrState.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a1488167d90017e45843bfae0b00aaf49">GetSeq</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#a0b687054dd0937d288747449fea1cb86">Seq</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a004bf866c0303839642a34b82e15eee5">llvm::objcarc::BottomUpPtrState::HandlePotentialAlterRefCount</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#acf48e56d2e2614373b53f03c5bd3c4b8">llvm::objcarc::TopDownPtrState::HandlePotentialAlterRefCount</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a92756d26ffe5c46811ee48f629857ba2">llvm::objcarc::BottomUpPtrState::HandlePotentialUse</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#ad0da3c507a530abd23de4894502b3199">llvm::objcarc::TopDownPtrState::HandlePotentialUse</a> and <a href="#ac3996894452fd20d95e7135ff0b01f30">ResetSequenceProgress</a>.</p>

</div>
</div>

### SetTailCallRelease() {#a68e4d18a484c49f0cdcab93b7af5fe96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcarc::PtrState::SetTailCallRelease (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool NewValue)</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Reference <a href="#a1dd5217efd31b0f4b30ab95d462dd816">RRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a0b6f153e14da3299ec487acbf39e22ae">llvm::objcarc::BottomUpPtrState::InitBottomUp</a> and <a href="/web-llvm/docs/api/structs/llvm/objcarc/topdownptrstate/#a58e7f78b0c740eb2f30b8a24ee170f7a">llvm::objcarc::TopDownPtrState::MatchWithRelease</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### KnownPositiveRefCount {#a09c5b919d9e1f9dcef809dee375c8d5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcarc::PtrState::KnownPositiveRefCount = false</td>
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

<p>True if the reference count is known to be incremented.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Referenced by <a href="#a75b7969d370fa510130319080bc10426">ClearKnownPositiveRefCount</a>, <a href="#a41ec3c64229bf8508e9f019eea5d129b">HasKnownPositiveRefCount</a>, <a href="#adf8b72d488312f8c7229b2beee07e28d">Merge</a> and <a href="#a1f7d5f6394d44b1dca0c23d13625c9c0">SetKnownPositiveRefCount</a>.</p>

</div>
</div>

### Partial {#af6e88dbced93e1293da494b9a981b313}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcarc::PtrState::Partial = false</td>
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

<p>True if we've seen an opportunity for partial RR elimination, such as pushing calls into a CFG triangle or into one side of a CFG diamond.</p>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Referenced by <a href="#adf8b72d488312f8c7229b2beee07e28d">Merge</a> and <a href="#ac3996894452fd20d95e7135ff0b01f30">ResetSequenceProgress</a>.</p>

</div>
</div>

### RRI {#a1dd5217efd31b0f4b30ab95d462dd816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RRInfo llvm::objcarc::PtrState::RRI</td>
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

<p>Unidirectional information about the current sequence.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Referenced by <a href="#a1e8374268ff00721371c4e0927510d88">ClearReverseInsertPts</a>, <a href="#ab966cfbfc5803c2c9de8290f9c818067">GetReleaseMetadata</a>, <a href="#a60e312a27952f9db561a969d47cf496b">GetRRInfo</a>, <a href="#a4a3ce7e4e153b91ea5d72f2df4cb023a">HasReverseInsertPts</a>, <a href="#ac34dc93e26f9d0d026d6f493beec9ca8">InsertCall</a>, <a href="#a49bf7d95cbf4a5edc394634d53a42ba0">InsertReverseInsertPt</a>, <a href="#a8d23fc02a3b5aee419cb4ce3abcf537e">IsCFGHazardAfflicted</a>, <a href="#aee65472e4d66de6d1d50f8e54fdcf54c">IsKnownSafe</a>, <a href="#a267963a0fff2a1cded48a777816254f0">IsTailCallRelease</a>, <a href="#afe2f76eb6d73d645667ac26c93e874a4">IsTrackingImpreciseReleases</a>, <a href="#adf8b72d488312f8c7229b2beee07e28d">Merge</a>, <a href="#ac3996894452fd20d95e7135ff0b01f30">ResetSequenceProgress</a>, <a href="#a11a0f02bf705457f683e5607b1fd3e29">SetCFGHazardAfflicted</a>, <a href="#ad5bc7cf4cad8226dd41ea81c0946b074">SetKnownSafe</a>, <a href="#ab98722f336af2fea28476dd2c480c8f9">SetReleaseMetadata</a> and <a href="#a68e4d18a484c49f0cdcab93b7af5fe96">SetTailCallRelease</a>.</p>

</div>
</div>

### Seq {#a0b687054dd0937d288747449fea1cb86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::objcarc::PtrState::Seq</td>
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

<p>The current position in the sequence.</p>

<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>Referenced by <a href="#a1488167d90017e45843bfae0b00aaf49">GetSeq</a>, <a href="#adf8b72d488312f8c7229b2beee07e28d">Merge</a>, <a href="#accbc43e52e5946ff04312f9d33a68ede">PtrState</a> and <a href="#ad14c921bb46309b6b0ef0439c44737b8">SetSeq</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-cpp">PtrState.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
