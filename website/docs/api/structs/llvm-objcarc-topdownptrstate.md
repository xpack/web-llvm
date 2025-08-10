---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/objcarc/topdownptrstate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `TopDownPtrState` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::objcarc::TopDownPtrState { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">Transforms/ObjCARC/PtrState.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate">PtrState</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class summarizes several per-pointer runtime properties which are propagated through the flow graph. <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135a2b5f248a6de8c47b00dd60db359e">TopDownPtrState</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e7821981d45cb3fada161fbd0b5b3ae">InitTopDown</a> (ARCInstKind Kind, Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>(Re-)Initialize this bottom up pointer returning true if we detected a pointer with nested releases. <a href="#a5e7821981d45cb3fada161fbd0b5b3ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58e7f78b0c740eb2f30b8a24ee170f7a">MatchWithRelease</a> (ARCMDKindCache &amp;Cache, Instruction *Release)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this set of retains can be paired with the given release. <a href="#a58e7f78b0c740eb2f30b8a24ee170f7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0da3c507a530abd23de4894502b3199">HandlePotentialUse</a> (Instruction *Inst, const Value *Ptr, ProvenanceAnalysis &amp;PA, ARCInstKind Class)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf48e56d2e2614373b53f03c5bd3c4b8">HandlePotentialAlterRefCount</a> (Instruction *Inst, const Value *Ptr, ProvenanceAnalysis &amp;PA, ARCInstKind Class, const BundledRetainClaimRVs &amp;BundledRVs)</td>
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


<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TopDownPtrState() {#a135a2b5f248a6de8c47b00dd60db359e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::objcarc::TopDownPtrState::TopDownPtrState ()</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2ab8e7b465df7c5979dc731d06e84ce2cf">llvm::objcarc::Release</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### HandlePotentialAlterRefCount() {#acf48e56d2e2614373b53f03c5bd3c4b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TopDownPtrState::HandlePotentialAlterRefCount (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/objcarc/provenanceanalysis">ProvenanceAnalysis</a> &amp; PA, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2">ARCInstKind</a> Class, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/objcarc/bundledretainclaimrvs">BundledRetainClaimRVs</a> &amp; BundledRVs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>, definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-cpp">PtrState.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#abe87d9f746abfb2ed0b6d08434d57abf">llvm::objcarc::CanDecrementRefCount</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#a75b7969d370fa510130319080bc10426">llvm::objcarc::PtrState::ClearKnownPositiveRefCount</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/bundledretainclaimrvs/#a2a3a24ed0274c01b34ef418b446bbfd8">llvm::objcarc::BundledRetainClaimRVs::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#a1488167d90017e45843bfae0b00aaf49">llvm::objcarc::PtrState::GetSeq</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#a4a3ce7e4e153b91ea5d72f2df4cb023a">llvm::objcarc::PtrState::HasReverseInsertPts</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#a49bf7d95cbf4a5edc394634d53a42ba0">llvm::objcarc::PtrState::InsertReverseInsertPt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2af635fed4a9fb967d38c264ed1106844f">llvm::objcarc::IntrinsicUser</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306da8902051603b385fb4587620a0650b4f7">llvm::objcarc::S_CanRelease</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306daff34dfb06d8316048c533bac105bfbe6">llvm::objcarc::S_MovableRelease</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306da6e431a7ec0fee74cc2ae9a79bd965122">llvm::objcarc::S_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306daac10e4a5d85a196bcb2578c2700f3ff3">llvm::objcarc::S_Retain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306daadd43d88dff4dfb5f9620f2151822b64">llvm::objcarc::S_Stop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306da8e1b337cadca1fc899129d307df7d68e">llvm::objcarc::S_Use</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#a11a0f02bf705457f683e5607b1fd3e29">llvm::objcarc::PtrState::SetCFGHazardAfflicted</a> and <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#ad14c921bb46309b6b0ef0439c44737b8">llvm::objcarc::PtrState::SetSeq</a>.</p>

</div>
</div>

### HandlePotentialUse() {#ad0da3c507a530abd23de4894502b3199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TopDownPtrState::HandlePotentialUse (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/objcarc/provenanceanalysis">ProvenanceAnalysis</a> &amp; PA, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2">ARCInstKind</a> Class)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>, definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-cpp">PtrState.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#af467748c4e634ace0c19cbbeb0af5fee">llvm::objcarc::CanUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#a1488167d90017e45843bfae0b00aaf49">llvm::objcarc::PtrState::GetSeq</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306da8902051603b385fb4587620a0650b4f7">llvm::objcarc::S_CanRelease</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306daff34dfb06d8316048c533bac105bfbe6">llvm::objcarc::S_MovableRelease</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306da6e431a7ec0fee74cc2ae9a79bd965122">llvm::objcarc::S_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306daac10e4a5d85a196bcb2578c2700f3ff3">llvm::objcarc::S_Retain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306daadd43d88dff4dfb5f9620f2151822b64">llvm::objcarc::S_Stop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306da8e1b337cadca1fc899129d307df7d68e">llvm::objcarc::S_Use</a> and <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#ad14c921bb46309b6b0ef0439c44737b8">llvm::objcarc::PtrState::SetSeq</a>.</p>

</div>
</div>

### InitTopDown() {#a5e7821981d45cb3fada161fbd0b5b3ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TopDownPtrState::InitTopDown (<a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2">ARCInstKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>(Re-)Initialize this bottom up pointer returning true if we detected a pointer with nested releases.</p>

<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>, definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-cpp">PtrState.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#a1488167d90017e45843bfae0b00aaf49">llvm::objcarc::PtrState::GetSeq</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#a41ec3c64229bf8508e9f019eea5d129b">llvm::objcarc::PtrState::HasKnownPositiveRefCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#ac34dc93e26f9d0d026d6f493beec9ca8">llvm::objcarc::PtrState::InsertCall</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#ac3996894452fd20d95e7135ff0b01f30">llvm::objcarc::PtrState::ResetSequenceProgress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2aa1226b5450384ce6ea5ed47c317303ee">llvm::objcarc::RetainRV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306daac10e4a5d85a196bcb2578c2700f3ff3">llvm::objcarc::S_Retain</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#a1f7d5f6394d44b1dca0c23d13625c9c0">llvm::objcarc::PtrState::SetKnownPositiveRefCount</a> and <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#ad5bc7cf4cad8226dd41ea81c0946b074">llvm::objcarc::PtrState::SetKnownSafe</a>.</p>

</div>
</div>

### MatchWithRelease() {#a58e7f78b0c740eb2f30b8a24ee170f7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TopDownPtrState::MatchWithRelease (<a href="/web-llvm/docs/api/classes/llvm/objcarc/arcmdkindcache">ARCMDKindCache</a> &amp; Cache, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Release)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this set of retains can be paired with the given release.</p>


<p>Modifies state appropriately to reflect that the matching occurred.</p>


<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a>, definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-cpp">PtrState.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#a75b7969d370fa510130319080bc10426">llvm::objcarc::PtrState::ClearKnownPositiveRefCount</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#a1e8374268ff00721371c4e0927510d88">llvm::objcarc::PtrState::ClearReverseInsertPts</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#a1488167d90017e45843bfae0b00aaf49">llvm::objcarc::PtrState::GetSeq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a749ec59e4812b00a3cf7e7036fb39c06ab1ec2e3fd61b7a763d9173e07016906c">llvm::objcarc::ImpreciseRelease</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a494b44abeacdfac8bb26d3203571d1c2ab8e7b465df7c5979dc731d06e84ce2cf">llvm::objcarc::Release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306da8902051603b385fb4587620a0650b4f7">llvm::objcarc::S_CanRelease</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306daff34dfb06d8316048c533bac105bfbe6">llvm::objcarc::S_MovableRelease</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306da6e431a7ec0fee74cc2ae9a79bd965122">llvm::objcarc::S_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306daac10e4a5d85a196bcb2578c2700f3ff3">llvm::objcarc::S_Retain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306daadd43d88dff4dfb5f9620f2151822b64">llvm::objcarc::S_Stop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a845b8f76f8bd22e4e2eb851121db306da8e1b337cadca1fc899129d307df7d68e">llvm::objcarc::S_Use</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#ab98722f336af2fea28476dd2c480c8f9">llvm::objcarc::PtrState::SetReleaseMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/objcarc/ptrstate/#a68e4d18a484c49f0cdcab93b7af5fe96">llvm::objcarc::PtrState::SetTailCallRelease</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-cpp">PtrState.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/ptrstate-h">PtrState.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
