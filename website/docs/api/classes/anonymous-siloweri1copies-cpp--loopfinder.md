---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-siloweri1copies-cpp-/loopfinder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LoopFinder` Class

<p>Helper class that detects loops which require us to lower an i1 COPY into bitwise manipulation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{SILowerI1Copies.cpp}::LoopFinder { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5b0bdd3a466adacd81540baaa80f08d">LoopFinder</a> (MachineDominatorTree &amp;DT, MachinePostDominatorTree &amp;PDT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cf63cd3280918e038371b0ba86571cc">initialize</a> (MachineBasicBlock &amp;MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7e76dcb7cf9c36d512e2c8b2056f55e">findLoop</a> (MachineBasicBlock *PostDom)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check whether a backward edge can be reached without going through the given <span class="doxyComputerOutput">PostDom</span> of the def block. <a href="#ac7e76dcb7cf9c36d512e2c8b2056f55e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2386e395c05803dc5a92d85297b9d6a1">addLoopEntries</a> (unsigned LoopLevel, MachineSSAUpdater &amp;SSAUpdater, MachineRegisterInfo &amp;MRI, MachineRegisterInfo::VRegAttrs LaneMaskRegAttrs, ArrayRef&lt; Incoming &gt; Incomings={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add undef values dominating the loop and the optionally given additional blocks, so that the SSA updater doesn't have to search all the way to the function entry. <a href="#a2386e395c05803dc5a92d85297b9d6a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b7a778623494c0afe98322b9283e054">inLoopLevel</a> (MachineBasicBlock &amp;MBB, unsigned LoopLevel, ArrayRef&lt; Incoming &gt; Incomings) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bf1b587fc19e6fde3996d4a4b3bcc75">advanceLevel</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a944c8f48c0cb300b994e5de475d75598">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortree">MachinePostDominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33900ef461adfb0b0221dc2c285e40e8">PDT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2fc6959370f0573b882c11fef8ab517">Visited</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cf210b7619517b6b4467cdad6e415e6">CommonDominators</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61a2a79bd2338b63c44b94eb8fc8a394">VisitedPostDom</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1814e27d2a8faedc127db9eb1a1d81b">FoundLoopLevel</a> = ~0u</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bef895a483a3421950fcaebedb798a8">DefBlock</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8033d7b3af27799d4a5fb3be4421fb5a">Stack</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78e677e609d86787554e1ffb902e835e">NextLevel</a></td>
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

<p>Helper class that detects loops which require us to lower an i1 COPY into bitwise manipulation.</p>


<p>Unfortunately, we cannot use <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> because <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> does not distinguish between loops with the same header. Consider this example:</p>


<p>A-+-+ | | | B-+ | | | C—+</p>


<p>A is the header of a loop containing A, B, and C as far as <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> is concerned. However, an i1 COPY in B that is used in C must be lowered to bitwise operations to combine results from different loop iterations when B has a divergent branch (since by default we will compile this code such that threads in a wave are merged at the entry of C).</p>


<p>The following rule is implemented to determine whether bitwise operations are required: use the bitwise lowering for a def in block B if a backward edge to B is reachable without going through the nearest common post-dominator of B and all uses of the def.</p>


<p>TODO: This rule is conservative because it does not check whether the relevant branches are actually divergent.</p>


<p>The class is designed to cache the CFG traversal so that it can be re-used for multiple defs within the same basic block.</p>


<p>TODO: We could use region analysis to quickly skip over SESE regions during the traversal.</p>


<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoopFinder() {#ad5b0bdd3a466adacd81540baaa80f08d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SILowerI1Copies.cpp}::LoopFinder::LoopFinder (<a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortree">MachinePostDominatorTree</a> &amp; PDT)</td>
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



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addLoopEntries() {#a2386e395c05803dc5a92d85297b9d6a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SILowerI1Copies.cpp}::LoopFinder::addLoopEntries (unsigned LoopLevel, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater">MachineSSAUpdater</a> &amp; SSAUpdater, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/structs/llvm/machineregisterinfo/vregattrs">MachineRegisterInfo::VRegAttrs</a> LaneMaskRegAttrs, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/incoming">Incoming</a> &gt; Incomings={})</td>
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

<p>Add undef values dominating the loop and the optionally given additional blocks, so that the SSA updater doesn't have to search all the way to the function entry.</p>

<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#adaf0e50d1e23ce068ed74fe079552d51">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesToI1</a>.</p>

</div>
</div>

### findLoop() {#ac7e76dcb7cf9c36d512e2c8b2056f55e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SILowerI1Copies.cpp}::LoopFinder::findLoop (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * PostDom)</td>
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

<p>Check whether a backward edge can be reached without going through the given <span class="doxyComputerOutput">PostDom</span> of the def block.</p>


<p>Return the level of <span class="doxyComputerOutput">PostDom</span> if a loop was found, or 0 otherwise.</p>


<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#aab2bf365c9f4b976adc7479576dfd5bb">llvm::DomTreeNodeBase&lt; NodeT &gt;::getBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a453de62c2dadf7b4b8df04e89f6ab4e0">llvm::DomTreeNodeBase&lt; NodeT &gt;::getIDom</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#adaf0e50d1e23ce068ed74fe079552d51">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesToI1</a>.</p>

</div>
</div>

### initialize() {#a0cf63cd3280918e038371b0ba86571cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SILowerI1Copies.cpp}::LoopFinder::initialize (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#adaf0e50d1e23ce068ed74fe079552d51">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesToI1</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### advanceLevel() {#a5bf1b587fc19e6fde3996d4a4b3bcc75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SILowerI1Copies.cpp}::LoopFinder::advanceLevel ()</td>
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



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

### inLoopLevel() {#a8b7a778623494c0afe98322b9283e054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SILowerI1Copies.cpp}::LoopFinder::inLoopLevel (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, unsigned LoopLevel, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/incoming">Incoming</a> &gt; Incomings)</td>
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



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CommonDominators {#a7cf210b7619517b6b4467cdad6e415e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineBasicBlock *, 4&gt; anonymous{SILowerI1Copies.cpp}::LoopFinder::CommonDominators</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

### DefBlock {#a8bef895a483a3421950fcaebedb798a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* anonymous{SILowerI1Copies.cpp}::LoopFinder::DefBlock = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

### DT {#a944c8f48c0cb300b994e5de475d75598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineDominatorTree&amp; anonymous{SILowerI1Copies.cpp}::LoopFinder::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

### FoundLoopLevel {#ad1814e27d2a8faedc127db9eb1a1d81b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SILowerI1Copies.cpp}::LoopFinder::FoundLoopLevel = ~0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

### NextLevel {#a78e677e609d86787554e1ffb902e835e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineBasicBlock *, 4&gt; anonymous{SILowerI1Copies.cpp}::LoopFinder::NextLevel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

### PDT {#a33900ef461adfb0b0221dc2c285e40e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachinePostDominatorTree&amp; anonymous{SILowerI1Copies.cpp}::LoopFinder::PDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

### Stack {#a8033d7b3af27799d4a5fb3be4421fb5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineBasicBlock *, 4&gt; anonymous{SILowerI1Copies.cpp}::LoopFinder::Stack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

### Visited {#ae2fc6959370f0573b882c11fef8ab517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineBasicBlock *, unsigned&gt; anonymous{SILowerI1Copies.cpp}::LoopFinder::Visited</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

### VisitedPostDom {#a61a2a79bd2338b63c44b94eb8fc8a394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* anonymous{SILowerI1Copies.cpp}::LoopFinder::VisitedPostDom = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
