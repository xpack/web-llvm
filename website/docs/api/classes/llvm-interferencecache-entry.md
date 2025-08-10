---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/interferencecache/entry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Entry` Class

<p>Entry - A cache entry containing interference information for all aliases of PhysReg in all basic blocks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::InterferenceCache::Entry { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e62855f272c8b218f3bc45201fa4a4d">Entry</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a087e1e7ef0bbb5f7f1869bc340f5057b">clear</a> (MachineFunction *mf, SlotIndexes *indexes, LiveIntervals *lis)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a695e208b1e08f925eeb2c9a3cf625e15">getPhysReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e7c70d566fb6de4fa6a068167fcd6d7">addRef</a> (int Delta)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7f7adc6d6f4fdcf1d2dce88e66d44db">hasRefs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76d4d532a2dec4be86967f80c193641c">revalidate</a> (LiveIntervalUnion *LIUArray, const TargetRegisterInfo *TRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>revalidate - LIU contents have changed, update tags. <a href="#a76d4d532a2dec4be86967f80c193641c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e799d6af8540a948ace958404f181f8">valid</a> (LiveIntervalUnion *LIUArray, const TargetRegisterInfo *TRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>valid - Return true if this is a valid entry for physReg. <a href="#a7e799d6af8540a948ace958404f181f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99785f470ade2cc1182ceed92ae7e2eb">reset</a> (MCRegister physReg, LiveIntervalUnion *LIUArray, const TargetRegisterInfo *TRI, const MachineFunction *MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reset - Initialize entry to represent physReg's aliases. <a href="#a99785f470ade2cc1182ceed92ae7e2eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">BlockInterference *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a464c8df3a0960e61f286f246ac65b2">get</a> (unsigned MBBNum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>get - Return an up to date BlockInterference. <a href="#a5a464c8df3a0960e61f286f246ac65b2">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dfb41a1d55189869260c331db7c9418">update</a> (unsigned MBBNum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>update - Recompute Blocks[MBBNum] <a href="#a4dfb41a1d55189869260c331db7c9418">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80ef913f496c90ac969ed55be6ad9ab9">PhysReg</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PhysReg - The register currently represented. <a href="#a80ef913f496c90ac969ed55be6ad9ab9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84f6aa244299a3bcb89e284eb9d0cfed">Tag</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tag - Cache tag is changed when any of the underlying LiveIntervalUnions change. <a href="#a84f6aa244299a3bcb89e284eb9d0cfed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba72c5f0c1d1dd214fdac227a0655bbd">RefCount</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RefCount - The total number of <a href="/web-llvm/docs/api/classes/llvm/interferencecache/cursor">Cursor</a> instances referring to this Entry. <a href="#aba72c5f0c1d1dd214fdac227a0655bbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5400573f7b9e6ea07636e5b802159ff6">MF</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MF - The current function. <a href="#a5400573f7b9e6ea07636e5b802159ff6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6af3901cf723ad74a30d7eacac9ce42">Indexes</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indexes - Mapping block numbers to <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> ranges. <a href="#aa6af3901cf723ad74a30d7eacac9ce42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6f02a8bfb1f55390bc7939ad3cc817f">LIS</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LIS - Used for accessing register mask interference maps. <a href="#ae6f02a8bfb1f55390bc7939ad3cc817f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3219b6f55a99e5fbf136a05d43e23bb9">PrevPos</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PrevPos - The previous position the iterators were moved to. <a href="#a3219b6f55a99e5fbf136a05d43e23bb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; RegUnitInfo, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72a785d8686136afa1512a1aa2fe19f9">RegUnits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Info for each RegUnit in PhysReg. <a href="#a72a785d8686136afa1512a1aa2fe19f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; BlockInterference, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b6b09030b834c5bf0fbb2e0aa2f15a4">Blocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Blocks - Interference for each block in the function. <a href="#a5b6b09030b834c5bf0fbb2e0aa2f15a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Entry - A cache entry containing interference information for all aliases of PhysReg in all basic blocks.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Entry() {#a7e62855f272c8b218f3bc45201fa4a4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InterferenceCache::Entry::Entry ()</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addRef() {#a1e7c70d566fb6de4fa6a068167fcd6d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InterferenceCache::Entry::addRef (int Delta)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### clear() {#a087e1e7ef0bbb5f7f1869bc340f5057b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InterferenceCache::Entry::clear (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * mf, <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> * indexes, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * lis)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### get() {#a5a464c8df3a0960e61f286f246ac65b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockInterference * llvm::InterferenceCache::Entry::get (unsigned MBBNum)</td>
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

<p>get - Return an up to date BlockInterference.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### getPhysReg() {#a695e208b1e08f925eeb2c9a3cf625e15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::InterferenceCache::Entry::getPhysReg ()</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### hasRefs() {#ad7f7adc6d6f4fdcf1d2dce88e66d44db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InterferenceCache::Entry::hasRefs ()</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### reset() {#a99785f470ade2cc1182ceed92ae7e2eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InterferenceCache::Entry::reset (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> physReg, <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion">LiveIntervalUnion</a> * LIUArray, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>reset - Initialize entry to represent physReg's aliases.</p>

<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-cpp">InterferenceCache.cpp</a>.</p>

</div>
</div>

### revalidate() {#a76d4d532a2dec4be86967f80c193641c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InterferenceCache::Entry::revalidate (<a href="/web-llvm/docs/api/classes/llvm/liveintervalunion">LiveIntervalUnion</a> * LIUArray, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>revalidate - LIU contents have changed, update tags.</p>

<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>, definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-cpp">InterferenceCache.cpp</a>.</p>

</div>
</div>

### valid() {#a7e799d6af8540a948ace958404f181f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InterferenceCache::Entry::valid (<a href="/web-llvm/docs/api/classes/llvm/liveintervalunion">LiveIntervalUnion</a> * LIUArray, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>valid - Return true if this is a valid entry for physReg.</p>

<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>, definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-cpp">InterferenceCache.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### update() {#a4dfb41a1d55189869260c331db7c9418}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InterferenceCache::Entry::update (unsigned MBBNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>update - Recompute Blocks[MBBNum]</p>

<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-cpp">InterferenceCache.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Blocks {#a5b6b09030b834c5bf0fbb2e0aa2f15a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;BlockInterference, 8&gt; llvm::InterferenceCache::Entry::Blocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Blocks - Interference for each block in the function.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### Indexes {#aa6af3901cf723ad74a30d7eacac9ce42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndexes* llvm::InterferenceCache::Entry::Indexes = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indexes - Mapping block numbers to <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> ranges.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### LIS {#ae6f02a8bfb1f55390bc7939ad3cc817f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals* llvm::InterferenceCache::Entry::LIS = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LIS - Used for accessing register mask interference maps.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### MF {#a5400573f7b9e6ea07636e5b802159ff6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::InterferenceCache::Entry::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MF - The current function.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### PhysReg {#a80ef913f496c90ac969ed55be6ad9ab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::InterferenceCache::Entry::PhysReg = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PhysReg - The register currently represented.</p>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### PrevPos {#a3219b6f55a99e5fbf136a05d43e23bb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::InterferenceCache::Entry::PrevPos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PrevPos - The previous position the iterators were moved to.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### RefCount {#aba72c5f0c1d1dd214fdac227a0655bbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::InterferenceCache::Entry::RefCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RefCount - The total number of <a href="/web-llvm/docs/api/classes/llvm/interferencecache/cursor">Cursor</a> instances referring to this Entry.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### RegUnits {#a72a785d8686136afa1512a1aa2fe19f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;RegUnitInfo, 4&gt; llvm::InterferenceCache::Entry::RegUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Info for each RegUnit in PhysReg.</p>


<p>It is very rare ofr a PHysReg to have more than 4 RegUnits.</p>


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### Tag {#a84f6aa244299a3bcb89e284eb9d0cfed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::InterferenceCache::Entry::Tag = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tag - Cache tag is changed when any of the underlying LiveIntervalUnions change.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-cpp">InterferenceCache.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
