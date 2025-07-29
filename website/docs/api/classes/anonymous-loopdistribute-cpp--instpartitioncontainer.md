---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InstPartitionContainer` Class

<p>Holds the set of Partitions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{LoopDistribute.cpp}::InstPartitionContainer { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb93347d93eb07dfcbbb1d2d356bd786">InstToPartitionIdT</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, int &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a304229ba82dfda1f7aced7d9dfcccf33">PartitionContainerT</a> = std::list&lt; <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartition">InstPartition</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b43a1f86e01f9b5612d120810515754">operator&lt;&lt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea292bd317f59726a74055d0bcf89217">InstPartitionContainer</a> (Loop *L, LoopInfo *LI, DominatorTree *DT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea5fae58d0253105a0c4dc9001b8c50d">getSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of partitions. <a href="#aea5fae58d0253105a0c4dc9001b8c50d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3b1855aab0d6db5fca73b22ba442b50">addToCyclicPartition</a> (Instruction *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds <span class="doxyComputerOutput">Inst</span> into the current partition if that is marked to contain cycles. <a href="#ad3b1855aab0d6db5fca73b22ba442b50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2c300c4031c2ec4a11e3099f7997826">addToNewNonCyclicPartition</a> (Instruction *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds <span class="doxyComputerOutput">Inst</span> into a partition that is not marked to contain dependence cycles. <a href="#ae2c300c4031c2ec4a11e3099f7997826">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad74de3edd28eb2b13222a27d529d91b7">mergeAdjacentNonCyclic</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merges adjacent non-cyclic partitions. <a href="#ad74de3edd28eb2b13222a27d529d91b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a208d5ae0644e0733519a9a77a64f6eb0">mergeNonIfConvertible</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a partition contains only conditional stores, we won't vectorize it. <a href="#a208d5ae0644e0733519a9a77a64f6eb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad99eb06dcdc7a4ab5c404219aa0243ab">mergeBeforePopulating</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merges the partitions according to various heuristics. <a href="#ad99eb06dcdc7a4ab5c404219aa0243ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a154fa6f1a3465a4e2e103cf22d888a33">mergeToAvoidDuplicatedLoads</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merges partitions in order to ensure that no loads are duplicated. <a href="#a154fa6f1a3465a4e2e103cf22d888a33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0c3d2072470aea6c24a409f9995e177">setupPartitionIdOnInstructions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets up the mapping between instructions to partitions. <a href="#ab0c3d2072470aea6c24a409f9995e177">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6393b11eb9a82951bc6ee17d009d59b">populateUsedSet</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populates the partition with everything that the seeding instructions require. <a href="#aa6393b11eb9a82951bc6ee17d009d59b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36f7b9a37f452349ad02d4d7f7d33972">cloneLoops</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This performs the main chunk of the work of cloning the loops for the partitions. <a href="#a36f7b9a37f452349ad02d4d7f7d33972">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74d7b9265d85cb5468e8e3dc3893c0df">removeUnusedInsts</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes the dead instructions from the cloned loops. <a href="#a74d7b9265d85cb5468e8e3dc3893c0df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a223e50a7d4a7c2c8290b0697da780758">computePartitionSetForPointers</a> (const LoopAccessInfo &amp;LAI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For each memory pointer, it computes the partitionId the pointer is used in. <a href="#a223e50a7d4a7c2c8290b0697da780758">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c2d583775ad8206c34cbc294584e11f">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5747f9b95c42d8956f1894de1bef02dc">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2066acdcb85397ee8c9e420d2905eaf9">printBlocks</a> (raw_ostream &amp;OS) const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class UnaryPredicate&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afa859f9bc073fe3921853ecdb4418f4c">mergeAdjacentPartitionsIf</a> (UnaryPredicate Predicate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The control structure to merge adjacent partitions if both satisfy the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/predicate">Predicate</a></span>. <a href="#afa859f9bc073fe3921853ecdb4418f4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd1e7dfb1a6503a256a0e95ee3c01853">setNewLoopID</a> (MDNode *OrigLoopID, InstPartition *Part)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign new LoopIDs for the partition's cloned loop. <a href="#afd1e7dfb1a6503a256a0e95ee3c01853">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">PartitionContainerT</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39077f933e7b8aeee520aa8982593d27">PartitionContainer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of partitions. <a href="#a39077f933e7b8aeee520aa8982593d27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">InstToPartitionIdT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6309892d349abf45028f6e6b64bb2c1">InstToPartitionId</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping from <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to partition Id. <a href="#aa6309892d349abf45028f6e6b64bb2c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f0edc9dc4752b9a61b6c0b7fd4bad34">L</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b4a6c331643c2de9628e863d579b315">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e573d5a6ac59cf23f549b396eaccf0d">DT</a></td>
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

<p>Holds the set of Partitions.</p>


<p>It populates them, merges them and then clones the loops.</p>


<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### InstToPartitionIdT {#aeb93347d93eb07dfcbbb1d2d356bd786}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{LoopDistribute.cpp}::InstPartitionContainer::InstToPartitionIdT =  DenseMap&lt;Instruction *, int&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### PartitionContainerT {#a304229ba82dfda1f7aced7d9dfcccf33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{LoopDistribute.cpp}::InstPartitionContainer::PartitionContainerT =  std::list&lt;InstPartition&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 555 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### operator&lt;&lt; {#a8b43a1f86e01f9b5612d120810515754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer">InstPartitionContainer</a> &amp; Partitions</td>
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


<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>References <a href="#aea292bd317f59726a74055d0bcf89217">InstPartitionContainer</a> and <a href="#a8c2d583775ad8206c34cbc294584e11f">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InstPartitionContainer() {#aea292bd317f59726a74055d0bcf89217}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopDistribute.cpp}::InstPartitionContainer::InstPartitionContainer (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT)</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>Referenced by <a href="#a8b43a1f86e01f9b5612d120810515754">operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addToCyclicPartition() {#ad3b1855aab0d6db5fca73b22ba442b50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartitionContainer::addToCyclicPartition (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
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

<p>Adds <span class="doxyComputerOutput">Inst</span> into the current partition if that is marked to contain cycles.</p>


<p>Otherwise start a new partition for it.</p>


<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a>.</p>

</div>
</div>

### addToNewNonCyclicPartition() {#ae2c300c4031c2ec4a11e3099f7997826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartitionContainer::addToNewNonCyclicPartition (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
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

<p>Adds <span class="doxyComputerOutput">Inst</span> into a partition that is not marked to contain dependence cycles.</p>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a>.</p>

</div>
</div>

### cloneLoops() {#a36f7b9a37f452349ad02d4d7f7d33972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartitionContainer::cloneLoops ()</td>
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

<p>This performs the main chunk of the work of cloning the loops for the partitions.</p>

<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ac3280e7f76f955403fe17eacf126b90d">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a59fb91d1691350f7d1b8e8a114e3f2a4">llvm::BasicBlock::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensaasmbackend-cpp/#a13a0babfc55adc9b798c39e65ec9e8a3">getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a>.</p>

</div>
</div>

### computePartitionSetForPointers() {#a223e50a7d4a7c2c8290b0697da780758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; int, 8 &gt; anonymous{LoopDistribute.cpp}::InstPartitionContainer::computePartitionSetForPointers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo">LoopAccessInfo</a> &amp; LAI)</td>
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

<p>For each memory pointer, it computes the partitionId the pointer is used in.</p>


<p>This returns an array of int where the I-th entry corresponds to I-th entry in LAI.getRuntimePointerCheck(). If the pointer is used in multiple partitions its entry is set to -1.</p>


<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo/#aaed62fb48116f7d5d40a420a1268b28b">llvm::LoopAccessInfo::getInstructionsForAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo/#a3aedf5694dc5b1e81a79658b126a9b43">llvm::LoopAccessInfo::getRuntimePointerChecking</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking/#aa6ad96a1c2591e0a61c92e0be5776978">llvm::RuntimePointerChecking::Pointers</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a>.</p>

</div>
</div>

### dump() {#a5747f9b95c42d8956f1894de1bef02dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartitionContainer::dump ()</td>
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



<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>

</div>
</div>

### getSize() {#aea5fae58d0253105a0c4dc9001b8c50d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LoopDistribute.cpp}::InstPartitionContainer::getSize ()</td>
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

<p>Returns the number of partitions.</p>

<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a>.</p>

</div>
</div>

### mergeAdjacentNonCyclic() {#ad74de3edd28eb2b13222a27d529d91b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartitionContainer::mergeAdjacentNonCyclic ()</td>
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

<p>Merges adjacent non-cyclic partitions.</p>


<p>The idea is that we currently only want to isolate the non-vectorizable partition. We could later allow more distribution among these partition too.</p>


<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#ad99eb06dcdc7a4ab5c404219aa0243ab">mergeBeforePopulating</a>.</p>

</div>
</div>

### mergeBeforePopulating() {#ad99eb06dcdc7a4ab5c404219aa0243ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartitionContainer::mergeBeforePopulating ()</td>
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

<p>Merges the partitions according to various heuristics.</p>

<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp/#a1c7effc385e669eca3121e377c50d7dd">DistributeNonIfConvertible</a>, <a href="#ad74de3edd28eb2b13222a27d529d91b7">mergeAdjacentNonCyclic</a> and <a href="#a208d5ae0644e0733519a9a77a64f6eb0">mergeNonIfConvertible</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a>.</p>

</div>
</div>

### mergeNonIfConvertible() {#a208d5ae0644e0733519a9a77a64f6eb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartitionContainer::mergeNonIfConvertible ()</td>
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

<p>If a partition contains only conditional stores, we won't vectorize it.</p>


<p>Try to merge it with a previous cyclic partition.</p>


<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo/#aa67d22298695c49e80b79cb8a271928b">llvm::LoopAccessInfo::blockNeedsPredication</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#ad99eb06dcdc7a4ab5c404219aa0243ab">mergeBeforePopulating</a>.</p>

</div>
</div>

### mergeToAvoidDuplicatedLoads() {#a154fa6f1a3465a4e2e103cf22d888a33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopDistribute.cpp}::InstPartitionContainer::mergeToAvoidDuplicatedLoads ()</td>
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

<p>Merges partitions in order to ensure that no loads are duplicated.</p>


<p>We can't duplicate loads because that could potentially reorder them. <a href="/web-llvm/docs/api/classes/llvm/loopaccessanalysis">LoopAccessAnalysis</a> provides dependency information with the context that the order of memory operation is preserved.</p>


<p>Return if any partitions were merged.</p>


<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a>.</p>

</div>
</div>

### populateUsedSet() {#aa6393b11eb9a82951bc6ee17d009d59b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartitionContainer::populateUsedSet ()</td>
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

<p>Populates the partition with everything that the seeding instructions require.</p>

<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a>.</p>

</div>
</div>

### print() {#a8c2d583775ad8206c34cbc294584e11f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartitionContainer::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a8b43a1f86e01f9b5612d120810515754">operator&lt;&lt;</a>.</p>

</div>
</div>

### printBlocks() {#a2066acdcb85397ee8c9e420d2905eaf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartitionContainer::printBlocks (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a>.</p>

</div>
</div>

### removeUnusedInsts() {#a74d7b9265d85cb5468e8e3dc3893c0df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartitionContainer::removeUnusedInsts ()</td>
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

<p>Removes the dead instructions from the cloned loops.</p>

<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a>.</p>

</div>
</div>

### setupPartitionIdOnInstructions() {#ab0c3d2072470aea6c24a409f9995e177}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartitionContainer::setupPartitionIdOnInstructions ()</td>
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

<p>Sets up the mapping between instructions to partitions.</p>


<p>If the instruction is duplicated across multiple partitions, set the entry to -1.</p>


<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### mergeAdjacentPartitionsIf() {#afa859f9bc073fe3921853ecdb4418f4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class UnaryPredicate&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartitionContainer::mergeAdjacentPartitionsIf (UnaryPredicate Predicate)</td>
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

<p>The control structure to merge adjacent partitions if both satisfy the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/predicate">Predicate</a></span>.</p>

<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### setNewLoopID() {#afd1e7dfb1a6503a256a0e95ee3c01853}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopDistribute.cpp}::InstPartitionContainer::setNewLoopID (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * OrigLoopID, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartition">InstPartition</a> * Part)</td>
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

<p>Assign new LoopIDs for the partition's cloned loop.</p>

<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DT {#a6e573d5a6ac59cf23f549b396eaccf0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{LoopDistribute.cpp}::InstPartitionContainer::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### InstToPartitionId {#aa6309892d349abf45028f6e6b64bb2c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstToPartitionIdT anonymous{LoopDistribute.cpp}::InstPartitionContainer::InstToPartitionId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping from <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to partition Id.</p>


<p>If the instruction belongs to multiple partitions the entry contains -1.</p>


<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### L {#a9f0edc9dc4752b9a61b6c0b7fd4bad34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* anonymous{LoopDistribute.cpp}::InstPartitionContainer::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### LI {#a1b4a6c331643c2de9628e863d579b315}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* anonymous{LoopDistribute.cpp}::InstPartitionContainer::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

</div>
</div>

### PartitionContainer {#a39077f933e7b8aeee520aa8982593d27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PartitionContainerT anonymous{LoopDistribute.cpp}::InstPartitionContainer::PartitionContainer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of partitions.</p>

<p>Definition at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp">LoopDistribute.cpp</a>.</p>

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
