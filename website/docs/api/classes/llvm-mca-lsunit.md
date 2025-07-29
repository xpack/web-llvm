---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/lsunit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LSUnit` Class

<p>Default Load/Store Unit (LS Unit) for simulated processors. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::mca::LSUnit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">llvm/MCA/HardwareUnits/LSUnit.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase">LSUnitBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract base interface for LS (load/store) units in llvm-mca. <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc6d000df5b9e7f37f240a2dea8eb807">LSUnit</a> (const MCSchedModel &amp;SM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae990133d773220ab1f285e9bde3c02ee">LSUnit</a> (const MCSchedModel &amp;SM, unsigned LQ, unsigned SQ)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d13168717a02a92e5d70b032a033f42">LSUnit</a> (const MCSchedModel &amp;SM, unsigned LQ, unsigned SQ, bool AssumeNoAlias)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#aaa2955db8dc3f1104bd78c37f6d883cd">Status</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12bbf977180dc8455fc617db14cef788">isAvailable</a> (const InstRef &amp;IR) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns LSU_AVAILABLE if there are enough load/store queue entries to accomodate instruction IR. <a href="#a12bbf977180dc8455fc617db14cef788">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a192996631c3d58d3c300c240a380ba1a">isReady</a> (const InstRef &amp;IR) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a peviously dispatched instruction IR is now ready for execution. <a href="#a192996631c3d58d3c300c240a380ba1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0df69663296c20af0947fb360969568f">isPending</a> (const InstRef &amp;IR) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if instruction IR only depends on memory instructions that are currently executing. <a href="#a0df69663296c20af0947fb360969568f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad2517356b24e7a39efa8f90aa36d39c">isWaiting</a> (const InstRef &amp;IR) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if instruction IR is still waiting on memory operations, and the wait time is still unknown. <a href="#aad2517356b24e7a39efa8f90aa36d39c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af68c0bcc1be9b7bb804bde87c0840009">hasDependentUsers</a> (const InstRef &amp;IR) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/criticaldependency">CriticalDependency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2bcb44611da7bb355bc5be2915f5f24">getCriticalPredecessor</a> (unsigned GroupId) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6a40d1885d6a63e525caab19137600d">dispatch</a> (const InstRef &amp;IR) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocates LS resources for instruction IR. <a href="#ac6a40d1885d6a63e525caab19137600d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51b3961e97dde2e7085c871c0c94cc92">onInstructionIssued</a> (const InstRef &amp;IR) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aada932f39510a67ca421c25782d87e5d">onInstructionRetired</a> (const InstRef &amp;IR) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8201f572ba1e14162d280b841cb461de">onInstructionExecuted</a> (const InstRef &amp;IR) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66870c20c27a8d0a1d1b08e6b6811574">cycleEvent</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b9033ae934d66cde6f48838e4da5fa6">dump</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab06a432cefa966a72db247d56f06ae8e">isValidGroupID</a> (unsigned Index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup">MemoryGroup</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fb12076188d04f7597f4ff00cf0be7b">getGroup</a> (unsigned Index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup">MemoryGroup</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac5434d3f12f9a4808b0d051c1104e74">getGroup</a> (unsigned Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05ef988fec47890db3618792fb28ac17">createMemoryGroup</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup">MemoryGroup</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ecb6a3f4704551b7c56b7d442600068">Groups</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to map group identifiers to MemoryGroups. <a href="#a1ecb6a3f4704551b7c56b7d442600068">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa818f0cc50c1374546e807394053453f">NextGroupID</a> = 1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bff04dcf417c98cfb86e44f8ae53c07">CurrentLoadGroupID</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a958f799088dee08c0febc6691db91e3c">CurrentLoadBarrierGroupID</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a93c58f217e92959c3a518f39eab9da">CurrentStoreGroupID</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae87a74d1259cd6d20ed0b34c9d2f22f1">CurrentStoreBarrierGroupID</a></td>
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

<p>Default Load/Store Unit (LS Unit) for simulated processors.</p>


<p>Each load (or store) consumes one entry in the load (or store) queue.</p>


<p>Rules are: 1) A younger load is allowed to pass an older load only if there are no stores nor barriers in between the two loads. 2) An younger store is not allowed to pass an older store. 3) A younger store is not allowed to pass an older load. 4) A younger load is allowed to pass an older store only if the load does not alias with the store.</p>


<p>This class optimistically assumes that loads don't alias store operations. Under this assumption, younger loads are always allowed to pass older stores (this would only affects rule 4). Essentially, this class doesn't perform any sort alias analysis to identify aliasing loads and stores.</p>


<p>To enforce aliasing between loads and stores, flag <span class="doxyComputerOutput">AssumeNoAlias</span> must be set to <span class="doxyComputerOutput">false</span> by the constructor of <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit">LSUnit</a>.</p>


<p>Note that this class doesn't know about the existence of different memory types for memory operations (example: write-through, write-combining, etc.). Derived classes are responsible for implementing that extra knowledge, and provide different sets of rules for loads and stores by overriding method <span class="doxyComputerOutput"><a href="#a192996631c3d58d3c300c240a380ba1a">isReady()</a></span>. To emulate a write-combining memory type, rule 2. must be relaxed in a derived class to enable the reordering of non-aliasing store operations.</p>


<p>No assumptions are made by this class on the size of the store buffer. This class doesn't know how to identify cases where store-to-load forwarding may occur.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/mca/lsunit">LSUnit</a> doesn't attempt to predict whether a load or store hits or misses the L1 cache. To be more specific, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit">LSUnit</a> doesn't know anything about cache hierarchy and memory types. It only knows if an instruction "mayLoad" and/or "mayStore". For loads, the scheduling model provides an "optimistic" load-to-use latency (which usually matches the load-to-use latency for when there is a hit in the L1D). Derived classes may expand this knowledge.</p>


<p>Class <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> in LLVM doesn't know about serializing operations, nor memory-barrier like instructions. <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit">LSUnit</a> conservatively assumes that an instruction which <span class="doxyComputerOutput">mayLoad</span> and has <span class="doxyComputerOutput">unmodeled side effects</span> behave like a "soft" load-barrier. That means, it serializes loads without forcing a flush of the load queue. Similarly, instructions that both <span class="doxyComputerOutput">mayStore</span> and have <span class="doxyComputerOutput">unmodeled side effects</span> are treated like store barriers. A full memory barrier is a 'mayLoad' and 'mayStore' instruction with unmodeled side effects. This is obviously inaccurate, but this is the best that we can do at the moment.</p>


<p>Each load/store barrier consumes one entry in the load/store queue. A load/store barrier enforces ordering of loads/stores:</p>


<ul class="doxyList ">
<li>A younger load cannot pass a load barrier.</li>
<li>A younger store cannot pass a store barrier.</li>
</ul>

<p>A younger load has to wait for the memory load barrier to execute. A load/store barrier is "executed" when it becomes the oldest entry in the load/store queue(s). That also means, all the older loads/stores have already been executed.</p>


<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LSUnit() {#afc6d000df5b9e7f37f240a2dea8eb807}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::LSUnit::LSUnit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a> &amp; SM)</td>
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



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>


<p>Reference <a href="#afc6d000df5b9e7f37f240a2dea8eb807">LSUnit</a>.</p>


<p>Referenced by <a href="#afc6d000df5b9e7f37f240a2dea8eb807">LSUnit</a> and <a href="#ae990133d773220ab1f285e9bde3c02ee">LSUnit</a>.</p>

</div>
</div>

### LSUnit() {#ae990133d773220ab1f285e9bde3c02ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::LSUnit::LSUnit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a> &amp; SM, unsigned LQ, unsigned SQ)</td>
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



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>


<p>Reference <a href="#afc6d000df5b9e7f37f240a2dea8eb807">LSUnit</a>.</p>

</div>
</div>

### LSUnit() {#a7d13168717a02a92e5d70b032a033f42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::LSUnit::LSUnit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a> &amp; SM, unsigned LQ, unsigned SQ, bool AssumeNoAlias)</td>
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



<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>


<p>References <a href="#a958f799088dee08c0febc6691db91e3c">CurrentLoadBarrierGroupID</a>, <a href="#a0bff04dcf417c98cfb86e44f8ae53c07">CurrentLoadGroupID</a>, <a href="#ae87a74d1259cd6d20ed0b34c9d2f22f1">CurrentStoreBarrierGroupID</a>, <a href="#a5a93c58f217e92959c3a518f39eab9da">CurrentStoreGroupID</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#ae26462941069e163c658782b4132b79d">llvm::mca::LSUnitBase::LSUnitBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### cycleEvent() {#a66870c20c27a8d0a1d1b08e6b6811574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::LSUnit::cycleEvent ()</td>
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



<p>Declaration at line 476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/lsunit-cpp">LSUnit.cpp</a>.</p>


<p>References <a href="#a66870c20c27a8d0a1d1b08e6b6811574">cycleEvent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="#a1ecb6a3f4704551b7c56b7d442600068">Groups</a>.</p>


<p>Referenced by <a href="#a66870c20c27a8d0a1d1b08e6b6811574">cycleEvent</a>.</p>

</div>
</div>

### dispatch() {#ac6a40d1885d6a63e525caab19137600d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::LSUnit::dispatch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
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

<p>Allocates LS resources for instruction IR.</p>


<p>This method assumes that a previous call to <span class="doxyComputerOutput">isAvailable(IR)</span> succeeded returning LSU_AVAILABLE.</p>


<p>Rules are: By default, rules are:</p>


<ol class="doxyList" type="1">
<li>A store may not pass a previous store.</li>
<li>A load may not pass a previous store unless flag 'NoAlias' is set.</li>
<li>A load may pass a previous load.</li>
<li>A store may not pass a previous load (regardless of flag 'NoAlias').</li>
<li>A load has to wait until an older load barrier is fully executed.</li>
<li>A store has to wait until an older store barrier is fully executed.</li>
</ol>

<p>Declaration at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/lsunit-cpp">LSUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#aea4e1c76e59784fcbbc8e704017ec52a">llvm::mca::LSUnitBase::acquireLQSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#a33c0faf073fd0f0bdeff814e4d486e85">llvm::mca::LSUnitBase::acquireSQSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup/#a1092ce29493a26df9148f7754bb3d2f5">llvm::mca::LSUnit::MemoryGroup::addInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup/#a755908a8693ddcd0451b4da97011003e">llvm::mca::LSUnit::MemoryGroup::addSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#a6b033843613bd76628bd139aa08b59b4">llvm::mca::LSUnitBase::assumeNoAlias</a>, <a href="#a958f799088dee08c0febc6691db91e3c">CurrentLoadBarrierGroupID</a>, <a href="#a0bff04dcf417c98cfb86e44f8ae53c07">CurrentLoadGroupID</a>, <a href="#ae87a74d1259cd6d20ed0b34c9d2f22f1">CurrentStoreBarrierGroupID</a>, <a href="#a5a93c58f217e92959c3a518f39eab9da">CurrentStoreGroupID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac6a40d1885d6a63e525caab19137600d">dispatch</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a7199990164d08ec4d05a8cd27c5e26e1">llvm::mca::InstructionBase::getMayLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a5d09368edd0f5643e14319d8c2381fc5">llvm::mca::InstructionBase::getMayStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#afd06075dee678fb37bf74165b57a9358">llvm::mca::InstructionBase::isALoadBarrier</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a1652a018222e84b552e96a8669da10d1">llvm::mca::InstructionBase::isAStoreBarrier</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#ac6a40d1885d6a63e525caab19137600d">dispatch</a>.</p>

</div>
</div>

### dump() {#a0b9033ae934d66cde6f48838e4da5fa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::LSUnit::dump ()</td>
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



<p>Declaration at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>, definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/lsunit-cpp">LSUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a0b9033ae934d66cde6f48838e4da5fa6">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#a9dda31ca1a953c27f5bed38e7174131f">llvm::mca::LSUnitBase::getLoadQueueSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup/#a788d18f8993b9491e52181e8da8d265a">llvm::mca::LSUnit::MemoryGroup::getNumExecuted</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup/#a968a4b37c2f3259293046443f8db8523">llvm::mca::LSUnit::MemoryGroup::getNumExecutedPredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup/#a282082e5059c427f27d7de99a5d4fa5e">llvm::mca::LSUnit::MemoryGroup::getNumExecuting</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup/#a0b0388697f594ae443e868456d1a46a7">llvm::mca::LSUnit::MemoryGroup::getNumExecutingPredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup/#a02cee8e4ae3371ca4e8404667d72096a">llvm::mca::LSUnit::MemoryGroup::getNumInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup/#a30a1c9da2276ad7b028cc4dea776c624">llvm::mca::LSUnit::MemoryGroup::getNumPredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#ae9bb4441b92aeeeec020405a28efcf07">llvm::mca::LSUnitBase::getStoreQueueSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#a6547cf381781145dd5374e4295a2959e">llvm::mca::LSUnitBase::getUsedLQEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#a21826da60bbacbd1d609014eb0c5fac8">llvm::mca::LSUnitBase::getUsedSQEntries</a> and <a href="#a1ecb6a3f4704551b7c56b7d442600068">Groups</a>.</p>


<p>Referenced by <a href="#a0b9033ae934d66cde6f48838e4da5fa6">dump</a>.</p>

</div>
</div>

### getCriticalPredecessor() {#af2bcb44611da7bb355bc5be2915f5f24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CriticalDependency llvm::mca::LSUnit::getCriticalPredecessor (unsigned GroupId)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup/#a709c6dc8cffce8d451fd85145e9da4dd">llvm::mca::LSUnit::MemoryGroup::getCriticalPredecessor</a>.</p>

</div>
</div>

### hasDependentUsers() {#af68c0bcc1be9b7bb804bde87c0840009}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::LSUnit::hasDependentUsers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup/#aba9478071acc2dc40303b34f5ef3bb7f">llvm::mca::LSUnit::MemoryGroup::getNumSuccessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup/#a4344aa0bc7f819f655d89d8095627681">llvm::mca::LSUnit::MemoryGroup::isExecuted</a>.</p>

</div>
</div>

### isAvailable() {#a12bbf977180dc8455fc617db14cef788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LSUnit::Status llvm::mca::LSUnit::isAvailable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
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

<p>Returns LSU_AVAILABLE if there are enough load/store queue entries to accomodate instruction IR.</p>

<p>Declaration at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/lsunit-cpp">LSUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a7199990164d08ec4d05a8cd27c5e26e1">llvm::mca::InstructionBase::getMayLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a5d09368edd0f5643e14319d8c2381fc5">llvm::mca::InstructionBase::getMayStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="#a12bbf977180dc8455fc617db14cef788">isAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#a202d27af27c3126fe79e010b8156da2f">llvm::mca::LSUnitBase::isLQFull</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#ab04ba9f06d2bc74d20c0b3bdb41c0d7e">llvm::mca::LSUnitBase::isSQFull</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#aaa2955db8dc3f1104bd78c37f6d883cda9ba5f0372dc81f2346c57d6871fd61ec">llvm::mca::LSUnitBase::LSU_AVAILABLE</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#aaa2955db8dc3f1104bd78c37f6d883cda7307bc1f313d256cd75ae3490beb69b0">llvm::mca::LSUnitBase::LSU_LQUEUE_FULL</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#aaa2955db8dc3f1104bd78c37f6d883cdab78bfd357a2c1a359c120ca260e45878">llvm::mca::LSUnitBase::LSU_SQUEUE_FULL</a>.</p>


<p>Referenced by <a href="#a12bbf977180dc8455fc617db14cef788">isAvailable</a>.</p>

</div>
</div>

### isPending() {#a0df69663296c20af0947fb360969568f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::LSUnit::isPending (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if instruction IR only depends on memory instructions that are currently executing.</p>

<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup/#a7472cedbaadb18cf0e30121f329d0b73">llvm::mca::LSUnit::MemoryGroup::isPending</a>.</p>

</div>
</div>

### isReady() {#a192996631c3d58d3c300c240a380ba1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::LSUnit::isReady (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a peviously dispatched instruction IR is now ready for execution.</p>

<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup/#aa5eb95bbc456dfc770ca1ddfe91b63f2">llvm::mca::LSUnit::MemoryGroup::isReady</a>.</p>

</div>
</div>

### isWaiting() {#aad2517356b24e7a39efa8f90aa36d39c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::LSUnit::isWaiting (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if instruction IR is still waiting on memory operations, and the wait time is still unknown.</p>

<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup/#a9276f1f6ccebe58ce0f81b11b3e872bb">llvm::mca::LSUnit::MemoryGroup::isWaiting</a>.</p>

</div>
</div>

### onInstructionExecuted() {#a8201f572ba1e14162d280b841cb461de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::LSUnit::onInstructionExecuted (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
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



<p>Declaration at line 474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>, definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/lsunit-cpp">LSUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a958f799088dee08c0febc6691db91e3c">CurrentLoadBarrierGroupID</a>, <a href="#a0bff04dcf417c98cfb86e44f8ae53c07">CurrentLoadGroupID</a>, <a href="#ae87a74d1259cd6d20ed0b34c9d2f22f1">CurrentStoreBarrierGroupID</a>, <a href="#a5a93c58f217e92959c3a518f39eab9da">CurrentStoreGroupID</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instruction/#af68b0a1cbe3a03b2011acbf400ffec68">llvm::mca::Instruction::getLSUTokenID</a>, <a href="#a1ecb6a3f4704551b7c56b7d442600068">Groups</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a67c179f1b0e96ef53a03966e4ee831fe">llvm::mca::InstructionBase::isMemOp</a> and <a href="#a8201f572ba1e14162d280b841cb461de">onInstructionExecuted</a>.</p>


<p>Referenced by <a href="#a8201f572ba1e14162d280b841cb461de">onInstructionExecuted</a>.</p>

</div>
</div>

### onInstructionIssued() {#a51b3961e97dde2e7085c871c0c94cc92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::mca::LSUnit::onInstructionIssued (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>


<p>References <a href="#a1ecb6a3f4704551b7c56b7d442600068">Groups</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>

</div>
</div>

### onInstructionRetired() {#aada932f39510a67ca421c25782d87e5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::LSUnit::onInstructionRetired (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
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



<p>Declaration at line 472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>, definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/lsunit-cpp">LSUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a7199990164d08ec4d05a8cd27c5e26e1">llvm::mca::InstructionBase::getMayLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a5d09368edd0f5643e14319d8c2381fc5">llvm::mca::InstructionBase::getMayStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aada932f39510a67ca421c25782d87e5d">onInstructionRetired</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#a447607ae8950017184b77c806b78bec9">llvm::mca::LSUnitBase::releaseLQSlot</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#afbeb4a136a4594261472807e309c6ee7">llvm::mca::LSUnitBase::releaseSQSlot</a>.</p>


<p>Referenced by <a href="#aada932f39510a67ca421c25782d87e5d">onInstructionRetired</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createMemoryGroup() {#a05ef988fec47890db3618792fb28ac17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::LSUnit::createMemoryGroup ()</td>
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



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>

</div>
</div>

### getGroup() {#a5fb12076188d04f7597f4ff00cf0be7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemoryGroup &amp; llvm::mca::LSUnit::getGroup (unsigned Index)</td>
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



<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>

</div>
</div>

### getGroup() {#aac5434d3f12f9a4808b0d051c1104e74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryGroup &amp; llvm::mca::LSUnit::getGroup (unsigned Index)</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>

</div>
</div>

### isValidGroupID() {#ab06a432cefa966a72db247d56f06ae8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::LSUnit::isValidGroupID (unsigned Index)</td>
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



<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### CurrentLoadBarrierGroupID {#a958f799088dee08c0febc6691db91e3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::LSUnit::CurrentLoadBarrierGroupID</td>
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



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>


<p>Referenced by <a href="#ac6a40d1885d6a63e525caab19137600d">dispatch</a>, <a href="#a7d13168717a02a92e5d70b032a033f42">LSUnit</a> and <a href="#a8201f572ba1e14162d280b841cb461de">onInstructionExecuted</a>.</p>

</div>
</div>

### CurrentLoadGroupID {#a0bff04dcf417c98cfb86e44f8ae53c07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::LSUnit::CurrentLoadGroupID</td>
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



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>


<p>Referenced by <a href="#ac6a40d1885d6a63e525caab19137600d">dispatch</a>, <a href="#a7d13168717a02a92e5d70b032a033f42">LSUnit</a> and <a href="#a8201f572ba1e14162d280b841cb461de">onInstructionExecuted</a>.</p>

</div>
</div>

### CurrentStoreBarrierGroupID {#ae87a74d1259cd6d20ed0b34c9d2f22f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::LSUnit::CurrentStoreBarrierGroupID</td>
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



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>


<p>Referenced by <a href="#ac6a40d1885d6a63e525caab19137600d">dispatch</a>, <a href="#a7d13168717a02a92e5d70b032a033f42">LSUnit</a> and <a href="#a8201f572ba1e14162d280b841cb461de">onInstructionExecuted</a>.</p>

</div>
</div>

### CurrentStoreGroupID {#a5a93c58f217e92959c3a518f39eab9da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::LSUnit::CurrentStoreGroupID</td>
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



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>


<p>Referenced by <a href="#ac6a40d1885d6a63e525caab19137600d">dispatch</a>, <a href="#a7d13168717a02a92e5d70b032a033f42">LSUnit</a> and <a href="#a8201f572ba1e14162d280b841cb461de">onInstructionExecuted</a>.</p>

</div>
</div>

### Groups {#a1ecb6a3f4704551b7c56b7d442600068}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, std::unique_ptr&lt;MemoryGroup&gt; &gt; llvm::mca::LSUnit::Groups</td>
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

<p>Used to map group identifiers to MemoryGroups.</p>

<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>


<p>Referenced by <a href="#a66870c20c27a8d0a1d1b08e6b6811574">cycleEvent</a>, <a href="#a0b9033ae934d66cde6f48838e4da5fa6">dump</a>, <a href="#a8201f572ba1e14162d280b841cb461de">onInstructionExecuted</a> and <a href="#a51b3961e97dde2e7085c871c0c94cc92">onInstructionIssued</a>.</p>

</div>
</div>

### NextGroupID {#aa818f0cc50c1374546e807394053453f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::LSUnit::NextGroupID = 1</td>
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



<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/lsunit-h">LSUnit.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/lsunit-cpp">LSUnit.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
