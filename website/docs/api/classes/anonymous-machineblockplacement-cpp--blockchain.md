---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-machineblockplacement-cpp-/blockchain
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BlockChain` Class

<p>A chain of blocks which will be laid out contiguously. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{MachineBlockPlacement.cpp}::BlockChain { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac2485344159ae07cfd3aa75113f50f5">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterator over blocks within the chain. <a href="#aac2485344159ae07cfd3aa75113f50f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b69724989408455732d7e436d4da6be">const_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">::const_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab486c9a0a0c5124ad4709ca49b910ec9">BlockChain</a> (BlockToChainMapType &amp;BlockToChain, MachineBasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a new <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a>. <a href="#ab486c9a0a0c5124ad4709ca49b910ec9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aac2485344159ae07cfd3aa75113f50f5">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdac6ad64953988f2ba10ecc1df333c5">begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Beginning of blocks within the chain. <a href="#afdac6ad64953988f2ba10ecc1df333c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4b69724989408455732d7e436d4da6be">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c35917ea8f9b30658afaa6a5753048a">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aac2485344159ae07cfd3aa75113f50f5">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a273f25cc15e7c494d9e5dd29cb07a88b">end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>End of blocks within the chain. <a href="#a273f25cc15e7c494d9e5dd29cb07a88b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4b69724989408455732d7e436d4da6be">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25661224cb2e0ab5b2985319276fbfce">end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6a5128cead90f00a37234c186692340">remove</a> (MachineBasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a939be2486e7faed5e6e1fd9d02311273">merge</a> (MachineBasicBlock *BB, BlockChain *Chain)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge a block chain into this one. <a href="#a939be2486e7faed5e6e1fd9d02311273">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8b7b149176869053e12294206134631">dump</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the blocks in this chain. <a href="#aa8b7b149176869053e12294206134631">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e686b9f871a08ccedf4c9af685a2ee0">UnscheduledPredecessors</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Count of predecessors of any block within the chain which have not yet been scheduled. <a href="#a8e686b9f871a08ccedf4c9af685a2ee0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0f22d1ed699595388bae9f70b0bd58d">Blocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The sequence of blocks belonging to this chain. <a href="#ab0f22d1ed699595388bae9f70b0bd58d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-machineblockplacement-cpp-/#a2e9703f1f38a15be415246106144a16d">BlockToChainMapType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5982d61e9432e07f93482e515c4c6c55">BlockToChain</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A handle to the function-wide basic block to block chain mapping. <a href="#a5982d61e9432e07f93482e515c4c6c55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A chain of blocks which will be laid out contiguously.</p>


<p>This is the datastructure representing a chain of consecutive blocks that are profitable to layout together in order to maximize fallthrough probabilities and code locality. We also can use a block chain to represent a sequence of basic blocks which have some external (correctness) requirement for sequential layout.</p>


<p>Chains can be built around a single basic block and can be merged to grow them. They participate in a block-to-chain mapping, which is updated automatically as chains are merged together.</p>


<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a4b69724989408455732d7e436d4da6be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{MachineBlockPlacement.cpp}::BlockChain::const_iterator =  SmallVectorImpl&lt;MachineBasicBlock *&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### iterator {#aac2485344159ae07cfd3aa75113f50f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{MachineBlockPlacement.cpp}::BlockChain::iterator =  SmallVectorImpl&lt;MachineBasicBlock *&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterator over blocks within the chain.</p>

<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BlockChain() {#ab486c9a0a0c5124ad4709ca49b910ec9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MachineBlockPlacement.cpp}::BlockChain::BlockChain (<a href="/web-llvm/docs/api/namespaces/anonymous-machineblockplacement-cpp-/#a2e9703f1f38a15be415246106144a16d">BlockToChainMapType</a> &amp; BlockToChain, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
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

<p>Construct a new <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a>.</p>


<p>This builds a new block chain representing a single basic block in the function. It also registers itself as the chain that block participates in with the BlockToChain mapping.</p>


<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a939be2486e7faed5e6e1fd9d02311273">merge</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#afdac6ad64953988f2ba10ecc1df333c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator anonymous{MachineBlockPlacement.cpp}::BlockChain::begin ()</td>
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

<p>Beginning of blocks within the chain.</p>

<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>Referenced by <a href="#aa6a5128cead90f00a37234c186692340">remove</a>.</p>

</div>
</div>

### begin() {#a5c35917ea8f9b30658afaa6a5753048a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator anonymous{MachineBlockPlacement.cpp}::BlockChain::begin ()</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### dump() {#aa8b7b149176869053e12294206134631}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void anonymous{MachineBlockPlacement.cpp}::BlockChain::dump ()</td>
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

<p>Dump the blocks in this chain.</p>

<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### end() {#a273f25cc15e7c494d9e5dd29cb07a88b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator anonymous{MachineBlockPlacement.cpp}::BlockChain::end ()</td>
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

<p>End of blocks within the chain.</p>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>Referenced by <a href="#aa6a5128cead90f00a37234c186692340">remove</a>.</p>

</div>
</div>

### end() {#a25661224cb2e0ab5b2985319276fbfce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator anonymous{MachineBlockPlacement.cpp}::BlockChain::end ()</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### merge() {#a939be2486e7faed5e6e1fd9d02311273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MachineBlockPlacement.cpp}::BlockChain::merge (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain">BlockChain</a> * Chain)</td>
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

<p>Merge a block chain into this one.</p>


<p>This routine merges a block chain into this one. It takes care of forming a contiguous sequence of basic blocks, updating the edge list, and updating the block -&gt; chain mapping. It does not free or tear down the old chain, but the old chain's block list is no longer valid.</p>


<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="#ab486c9a0a0c5124ad4709ca49b910ec9">BlockChain</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>.</p>

</div>
</div>

### remove() {#aa6a5128cead90f00a37234c186692340}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachineBlockPlacement.cpp}::BlockChain::remove (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
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



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>


<p>References <a href="#afdac6ad64953988f2ba10ecc1df333c5">begin</a> and <a href="#a273f25cc15e7c494d9e5dd29cb07a88b">end</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### UnscheduledPredecessors {#a8e686b9f871a08ccedf4c9af685a2ee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MachineBlockPlacement.cpp}::BlockChain::UnscheduledPredecessors = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Count of predecessors of any block within the chain which have not yet been scheduled.</p>


<p>In general, we will delay scheduling this chain until those predecessors are scheduled (or we find a sufficiently good reason to override this heuristic.) Note that when forming loop chains, blocks outside the loop are ignored and treated as if they were already scheduled.</p>


<p>Note: This field is reinitialized multiple times - once for each loop, and then once for the function as a whole.</p>


<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Blocks {#ab0f22d1ed699595388bae9f70b0bd58d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineBasicBlock *, 4&gt; anonymous{MachineBlockPlacement.cpp}::BlockChain::Blocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The sequence of blocks belonging to this chain.</p>


<p>This is the sequence of blocks for a particular chain. These will be laid out in-order within the function.</p>


<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

### BlockToChain {#a5982d61e9432e07f93482e515c4c6c55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockToChainMapType&amp; anonymous{MachineBlockPlacement.cpp}::BlockChain::BlockToChain</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A handle to the function-wide basic block to block chain mapping.</p>


<p>This is retained in each block chain to simplify the computation of child block chains for SCC-formation and iteration. We store the edges to child basic blocks, and map them back to their associated chains using this structure.</p>


<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp">MachineBlockPlacement.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
