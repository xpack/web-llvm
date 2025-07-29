---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-loopdistribute-cpp-/instpartition
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InstPartition` Class

<p>Maintains the set of instructions of the loop for a partition before cloning. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{LoopDistribute.cpp}::InstPartition { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0addfeaf7b4303cbd6679820dff00e2">InstructionSet</a> = <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 8 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4018f5126e9b720c3a3df67658c9bd92">InstPartition</a> (Instruction *I, Loop *L, bool DepCycle=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeb509283a6536d2be76571811dab8a5">hasDepCycle</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether this partition contains a dependence cycle. <a href="#aaeb509283a6536d2be76571811dab8a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4981789d0671fdfece0abf2e2835344">add</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds an instruction to this partition. <a href="#ad4981789d0671fdfece0abf2e2835344">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector/#a813fd00ac7e5e3261ffe67f9322a5480">InstructionSet::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41382e166d2164b6dd6dc41af211e134">begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection accessors. <a href="#a41382e166d2164b6dd6dc41af211e134">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector/#a813fd00ac7e5e3261ffe67f9322a5480">InstructionSet::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e39e2dbb853f99b979776d65c8a1ae0">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector/#a954de16c021e57fb3c8e8143bdb428ca">InstructionSet::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a231b55d3e91aab76989441ebf3da0759">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector/#a954de16c021e57fb3c8e8143bdb428ca">InstructionSet::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b4bcac53f76449dddca26726671b490">end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0191c583a8884d82e8fe06f824b57ff">empty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3d80464e8b58bfa4f67b63e0800e725">moveTo</a> (InstPartition &amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Moves this partition into <span class="doxyComputerOutput">Other</span>. <a href="#aa3d80464e8b58bfa4f67b63e0800e725">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9feb888b40cb5010ca125c921f15c0f8">populateUsedSet</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populates the partition with a transitive closure of all the instructions that the seeded instructions dependent on. <a href="#a9feb888b40cb5010ca125c921f15c0f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2041884c5740bd6521ce7cc9c4257138">cloneLoopWithPreheader</a> (BasicBlock *InsertBefore, BasicBlock *LoopDomBB, unsigned Index, LoopInfo *LI, DominatorTree *DT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clones the original loop. <a href="#a2041884c5740bd6521ce7cc9c4257138">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecfaea1aebe353f0afc2d5eba61bf07c">getClonedLoop</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cloned loop. <a href="#aecfaea1aebe353f0afc2d5eba61bf07c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8398bc50fc5d03357ea78c2fc25c9faa">getDistributedLoop</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the loop where this partition ends up after distribution. <a href="#a8398bc50fc5d03357ea78c2fc25c9faa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ef4ac8492590f6a779e50b937cf754c">getVMap</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The VMap that is populated by cloning and then used in remapinstruction to remap the cloned instructions. <a href="#a3ef4ac8492590f6a779e50b937cf754c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0986ffee1c43aa696231ecef3c9b99cc">remapInstructions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remaps the cloned instructions using VMap. <a href="#a0986ffee1c43aa696231ecef3c9b99cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f5acddf8fa1936f68b72eed3a1de362">removeUnusedInsts</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Based on the set of instructions selected for this partition, removes the unnecessary ones. <a href="#a0f5acddf8fa1936f68b72eed3a1de362">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cf8163e1d057378e8391a25fb12907a">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0393474c5bb44e65544a4bc6fcb8498c">printBlocks</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">InstructionSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee19cf9f0790b5c0629a7083f1af0483">Set</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instructions from OrigLoop selected for this partition. <a href="#aee19cf9f0790b5c0629a7083f1af0483">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee5b6ca9a0b656a0a51e0ab7c9c79057">DepCycle</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this partition contains a dependence cycle. <a href="#aee5b6ca9a0b656a0a51e0ab7c9c79057">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a931e5a80d9dad95339107092f7c107c8">OrigLoop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The original loop. <a href="#a931e5a80d9dad95339107092f7c107c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a956bfd9fbf3f5ca77a8bbe625881d875">ClonedLoop</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cloned loop. <a href="#a956bfd9fbf3f5ca77a8bbe625881d875">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b9ea060ce132378efff6ab317a4487a">ClonedLoopBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The blocks of ClonedLoop including the preheader. <a href="#a9b9ea060ce132378efff6ab317a4487a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcbc82e054e2d335c7a5eefa831e236f">VMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These gets populated once the set of instructions have been finalized. <a href="#afcbc82e054e2d335c7a5eefa831e236f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Maintains the set of instructions of the loop for a partition before cloning.</p>


<p>After cloning, it hosts the new loop.</p>


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### InstructionSet {#af0addfeaf7b4303cbd6679820dff00e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{LoopDistribute.cpp}::InstPartition::InstructionSet =  SmallSetVector&lt;Instruction *, 8&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InstPartition() {#a4018f5126e9b720c3a3df67658c9bd92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopDistribute.cpp}::InstPartition::InstPartition (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, bool DepCycle=false)</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#aa3d80464e8b58bfa4f67b63e0800e725">moveTo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#ad4981789d0671fdfece0abf2e2835344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartition::add (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Adds an instruction to this partition.</p>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### begin() {#a41382e166d2164b6dd6dc41af211e134}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSet::iterator anonymous{LoopDistribute.cpp}::InstPartition::begin ()</td>
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

<p>Collection accessors.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### begin() {#a231b55d3e91aab76989441ebf3da0759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSet::const_iterator anonymous{LoopDistribute.cpp}::InstPartition::begin ()</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### cloneLoopWithPreheader() {#a2041884c5740bd6521ce7cc9c4257138}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop * anonymous{LoopDistribute.cpp}::InstPartition::cloneLoopWithPreheader (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * InsertBefore, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * LoopDomBB, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT)</td>
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

<p>Clones the original loop.</p>


<p>Updates <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> using the information that block <span class="doxyComputerOutput">LoopDomBB</span> dominates the loop.</p>


<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a6f244e1d6d34701da1f29d3a762974fd">llvm::cloneLoopWithPreheader</a>.</p>

</div>
</div>

### empty() {#ad0191c583a8884d82e8fe06f824b57ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopDistribute.cpp}::InstPartition::empty ()</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### end() {#a6e39e2dbb853f99b979776d65c8a1ae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSet::iterator anonymous{LoopDistribute.cpp}::InstPartition::end ()</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### end() {#a6b4bcac53f76449dddca26726671b490}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSet::const_iterator anonymous{LoopDistribute.cpp}::InstPartition::end ()</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### getClonedLoop() {#aecfaea1aebe353f0afc2d5eba61bf07c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Loop * anonymous{LoopDistribute.cpp}::InstPartition::getClonedLoop ()</td>
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

<p>The cloned loop.</p>


<p>If this partition is mapped to the original loop, this is null.</p>


<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### getDistributedLoop() {#a8398bc50fc5d03357ea78c2fc25c9faa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop * anonymous{LoopDistribute.cpp}::InstPartition::getDistributedLoop ()</td>
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

<p>Returns the loop where this partition ends up after distribution.</p>


<p>If this partition is mapped to the original loop then use the block from the loop.</p>


<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>Referenced by <a href="#a0393474c5bb44e65544a4bc6fcb8498c">printBlocks</a>.</p>

</div>
</div>

### getVMap() {#a3ef4ac8492590f6a779e50b937cf754c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueToValueMapTy &amp; anonymous{LoopDistribute.cpp}::InstPartition::getVMap ()</td>
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

<p>The VMap that is populated by cloning and then used in remapinstruction to remap the cloned instructions.</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### hasDepCycle() {#aaeb509283a6536d2be76571811dab8a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopDistribute.cpp}::InstPartition::hasDepCycle ()</td>
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

<p>Returns whether this partition contains a dependence cycle.</p>

<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### moveTo() {#aa3d80464e8b58bfa4f67b63e0800e725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartition::moveTo (<a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartition">InstPartition</a> &amp; Other)</td>
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

<p>Moves this partition into <span class="doxyComputerOutput">Other</span>.</p>


<p>This partition becomes empty after this.</p>


<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>References <a href="#a4018f5126e9b720c3a3df67658c9bd92">InstPartition</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### populateUsedSet() {#a9feb888b40cb5010ca125c921f15c0f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartition::populateUsedSet ()</td>
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

<p>Populates the partition with a transitive closure of all the instructions that the seeded instructions dependent on.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### print() {#a7cf8163e1d057378e8391a25fb12907a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartition::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### printBlocks() {#a0393474c5bb44e65544a4bc6fcb8498c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartition::printBlocks (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>Reference <a href="#a8398bc50fc5d03357ea78c2fc25c9faa">getDistributedLoop</a>.</p>

</div>
</div>

### remapInstructions() {#a0986ffee1c43aa696231ecef3c9b99cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartition::remapInstructions ()</td>
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

<p>Remaps the cloned instructions using VMap.</p>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab8ec5c940fbc440c992716fbe4a48636">llvm::remapInstructionsInBlocks</a>.</p>

</div>
</div>

### removeUnusedInsts() {#a0f5acddf8fa1936f68b72eed3a1de362}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartition::removeUnusedInsts ()</td>
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

<p>Based on the set of instructions selected for this partition, removes the unnecessary ones.</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ClonedLoop {#a956bfd9fbf3f5ca77a8bbe625881d875}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* anonymous{LoopDistribute.cpp}::InstPartition::ClonedLoop = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cloned loop.</p>


<p>If this partition is mapped to the original loop, this is null.</p>


<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### ClonedLoopBlocks {#a9b9ea060ce132378efff6ab317a4487a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;BasicBlock *, 8&gt; anonymous{LoopDistribute.cpp}::InstPartition::ClonedLoopBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The blocks of ClonedLoop including the preheader.</p>


<p>If this partition is mapped to the original loop, this is empty.</p>


<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### DepCycle {#aee5b6ca9a0b656a0a51e0ab7c9c79057}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopDistribute.cpp}::InstPartition::DepCycle</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether this partition contains a dependence cycle.</p>

<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### OrigLoop {#a931e5a80d9dad95339107092f7c107c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* anonymous{LoopDistribute.cpp}::InstPartition::OrigLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The original loop.</p>

<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### Set {#aee19cf9f0790b5c0629a7083f1af0483}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionSet anonymous{LoopDistribute.cpp}::InstPartition::Set</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Instructions from OrigLoop selected for this partition.</p>

<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### VMap {#afcbc82e054e2d335c7a5eefa831e236f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueToValueMapTy anonymous{LoopDistribute.cpp}::InstPartition::VMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>These gets populated once the set of instructions have been finalized.</p>


<p>If this partition is mapped to the original loop, these are not set.</p>


<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
