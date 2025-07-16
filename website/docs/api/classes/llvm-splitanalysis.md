---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/splitanalysis
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SplitAnalysis` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/splitanalysis">SplitAnalysis</a> - Analyze a <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a>, looking for live range splitting opportunities. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SplitAnalysis { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">CodeGen/SplitKit.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bb4710b60743b1d563cb13ada1368b2">BlockPtrSet</a> = <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 16 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a027186766ff82f05b729d087baf9a25f">SplitAnalysis</a> (const VirtRegMap &amp;vrm, const LiveIntervals &amp;lis, const MachineLoopInfo &amp;mli)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1e3d133ed73597d0c21e0a5d11fa31f">analyze</a> (const LiveInterval *li)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>analyze - set CurLI to the specified interval, and analyze how it may be split. <a href="#aa1e3d133ed73597d0c21e0a5d11fa31f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab21a191f8cdb8f76d22d0bae3089e1c5">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clear - clear all data structures so <a href="/web-llvm/docs/api/classes/llvm/splitanalysis">SplitAnalysis</a> is ready to analyze a new interval. <a href="#ab21a191f8cdb8f76d22d0bae3089e1c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a790e91aa1f3fdca6d9e7c39d13f6d3f6">getParent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getParent - Return the last analyzed interval. <a href="#a790e91aa1f3fdca6d9e7c39d13f6d3f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b388f6ec0c78d81a2d54efaac443691">isOriginalEndpoint</a> (SlotIndex Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isOriginalEndpoint - Return true if the original live range was killed or (re-)defined at Idx. <a href="#a6b388f6ec0c78d81a2d54efaac443691">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59ea17ee48fc0e6e45506b633556acc9">getUseSlots</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getUseSlots - Return an array of <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> of instructions using CurLI. <a href="#a59ea17ee48fc0e6e45506b633556acc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo">BlockInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cc231c4663974cb5b2a78d94a44b64d">getUseBlocks</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getUseBlocks - Return an array of <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo">BlockInfo</a> objects for the basic blocks where CurLI has uses. <a href="#a4cc231c4663974cb5b2a78d94a44b64d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70482f0c8168c894fce2bd14fffe6a95">getNumThroughBlocks</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getNumThroughBlocks - Return the number of through blocks. <a href="#a70482f0c8168c894fce2bd14fffe6a95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee6b2ae8e7ef8d354dce1dd815b9b7c1">isThroughBlock</a> (unsigned MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isThroughBlock - Return true if CurLI is live through MBB without uses. <a href="#aee6b2ae8e7ef8d354dce1dd815b9b7c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5836148f63cbfcd1ebe9facebf3c24b">getThroughBlocks</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getThroughBlocks - Return the set of through blocks. <a href="#aa5836148f63cbfcd1ebe9facebf3c24b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8280ad8ed267ed1fe319addf617dbd8">getNumLiveBlocks</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getNumLiveBlocks - Return the number of blocks where CurLI is live. <a href="#ac8280ad8ed267ed1fe319addf617dbd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a816a5b68a0407596872701a245ff51ae">looksLikeLoopIV</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b3f9616a4146e9a88336afcaf92835e">countLiveBlocks</a> (const LiveInterval *li) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>countLiveBlocks - Return the number of blocks where li is live. <a href="#a6b3f9616a4146e9a88336afcaf92835e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3bf010ee796ca57e04c495963fd49b7">shouldSplitSingleBlock</a> (const BlockInfo &amp;BI, bool SingleInstrs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>shouldSplitSingleBlock - Returns true if it would help to create a local live range for the instructions in BI. <a href="#af3bf010ee796ca57e04c495963fd49b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a723a443c171be9909a0f101c7b84333e">getLastSplitPoint</a> (unsigned Num)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad85ff77c8654c9001b781788d5aac661">getLastSplitPoint</a> (MachineBasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ed260204c6f152115206858258866b2">getLastSplitPointIter</a> (MachineBasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8004c65ffc7336951db96a4a670bb48">getFirstSplitPoint</a> (unsigned Num)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2bf77b2c1703bd3bba2b63c8c712534">analyzeUses</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>analyzeUses - Count instructions, basic blocks, and loops using CurLI. <a href="#aa2bf77b2c1703bd3bba2b63c8c712534">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1efea12880d546dc986832c05d09ceab">calcLiveBlockInfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>calcLiveBlockInfo - Compute per-block information about CurLI. <a href="#a1efea12880d546dc986832c05d09ceab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a192ed636858339b1ad1fbaa98d2f5d7d">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae922fe27fed5647d4fe22789a6c61683">VRM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e4649f48b911935d6604bde06468788">LIS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4478598c0a88b09a259c89aead763c5">Loops</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab56d031a917d10b407904c964bbb9083">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1283500f144aec69f1d7880d456a7c9">CurLI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/insertpointanalysis">InsertPointAnalysis</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dfe4237f9b9db5925a938574f9f4794">IPA</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert Point Analysis. <a href="#a5dfe4237f9b9db5925a938574f9f4794">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0fe53d6540ec8de76f6e5167dfd3c25">UseSlots</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo">BlockInfo</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58cea558f432d3c9c75eaf2529ac4f36">UseBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>UseBlocks - Blocks where CurLI has uses. <a href="#a58cea558f432d3c9c75eaf2529ac4f36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fb52ea1b4a3eaa3713dc79afd41d360">NumGapBlocks</a> = 0u</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NumGapBlocks - Number of duplicate entries in UseBlocks for blocks where the live range has a gap. <a href="#a2fb52ea1b4a3eaa3713dc79afd41d360">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9de691301365945a466e6fae810a8fc6">ThroughBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ThroughBlocks - Block numbers where CurLI is live through without uses. <a href="#a9de691301365945a466e6fae810a8fc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accfa0bda726ab829a6ee83598ac5e5de">NumThroughBlocks</a> = 0u</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NumThroughBlocks - Number of live-through blocks. <a href="#accfa0bda726ab829a6ee83598ac5e5de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8d8ffd1cda13fda000ed857e58c5aa6">LooksLikeLoopIV</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LooksLikeLoopIV - The variable defines what looks like it could be a loop IV, where it defs a variable in the latch. <a href="#ac8d8ffd1cda13fda000ed857e58c5aa6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/splitanalysis">SplitAnalysis</a> - Analyze a <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a>, looking for live range splitting opportunities.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BlockPtrSet {#a9bb4710b60743b1d563cb13ada1368b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SplitAnalysis::BlockPtrSet =  SmallPtrSet&lt;const MachineBasicBlock *, 16&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SplitAnalysis() {#a027186766ff82f05b729d087baf9a25f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SplitAnalysis::SplitAnalysis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> &amp; vrm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; lis, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> &amp; mli)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="#a8e4649f48b911935d6604bde06468788">LIS</a>, <a href="#ab4478598c0a88b09a259c89aead763c5">Loops</a>, <a href="#a192ed636858339b1ad1fbaa98d2f5d7d">MF</a>, <a href="#ab56d031a917d10b407904c964bbb9083">TII</a> and <a href="#ae922fe27fed5647d4fe22789a6c61683">VRM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### analyze() {#aa1e3d133ed73597d0c21e0a5d11fa31f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitAnalysis::analyze (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> * li)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>analyze - set CurLI to the specified interval, and analyze how it may be split.</p>

<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>Reference <a href="#ab21a191f8cdb8f76d22d0bae3089e1c5">clear</a>.</p>

</div>
</div>

### clear() {#ab21a191f8cdb8f76d22d0bae3089e1c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitAnalysis::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>clear - clear all data structures so <a href="/web-llvm/docs/api/classes/llvm/splitanalysis">SplitAnalysis</a> is ready to analyze a new interval.</p>

<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>Referenced by <a href="#aa1e3d133ed73597d0c21e0a5d11fa31f">analyze</a>.</p>

</div>
</div>

### countLiveBlocks() {#a6b3f9616a4146e9a88336afcaf92835e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SplitAnalysis::countLiveBlocks (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> * li)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>countLiveBlocks - Return the number of blocks where li is live.</p>


<p>This is guaranteed to return the same number as <a href="#ac8280ad8ed267ed1fe319addf617dbd8">getNumLiveBlocks()</a> after calling analyze(li).</p>


<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liverange/#a60203ad10397a7340f8a0e44ac25368d">llvm::LiveRange::advanceTo</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a9a5e7c523f12f9f164b786769de1ca47">llvm::LiveRange::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a66ff664a97cd3c30de7e873335a0c075">llvm::LiveRange::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a757fd6afba0f531db70e78e057d147c6">llvm::LiveRange::end</a> and <a href="#a8e4649f48b911935d6604bde06468788">LIS</a>.</p>

</div>
</div>

### getFirstSplitPoint() {#af8004c65ffc7336951db96a4a670bb48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SplitAnalysis::getFirstSplitPoint (unsigned Num)</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<p>Reference <a href="#a192ed636858339b1ad1fbaa98d2f5d7d">MF</a>.</p>

</div>
</div>

### getLastSplitPoint() {#a723a443c171be9909a0f101c7b84333e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SplitAnalysis::getLastSplitPoint (unsigned Num)</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<p>Reference <a href="#a192ed636858339b1ad1fbaa98d2f5d7d">MF</a>.</p>

</div>
</div>

### getLastSplitPoint() {#ad85ff77c8654c9001b781788d5aac661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SplitAnalysis::getLastSplitPoint (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### getLastSplitPointIter() {#a2ed260204c6f152115206858258866b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::SplitAnalysis::getLastSplitPointIter (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
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



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### getNumLiveBlocks() {#ac8280ad8ed267ed1fe319addf617dbd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SplitAnalysis::getNumLiveBlocks ()</td>
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

<p>getNumLiveBlocks - Return the number of blocks where CurLI is live.</p>

<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<p>References <a href="#a70482f0c8168c894fce2bd14fffe6a95">getNumThroughBlocks</a> and <a href="#a4cc231c4663974cb5b2a78d94a44b64d">getUseBlocks</a>.</p>

</div>
</div>

### getNumThroughBlocks() {#a70482f0c8168c894fce2bd14fffe6a95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SplitAnalysis::getNumThroughBlocks ()</td>
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

<p>getNumThroughBlocks - Return the number of through blocks.</p>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<p>Referenced by <a href="#ac8280ad8ed267ed1fe319addf617dbd8">getNumLiveBlocks</a>.</p>

</div>
</div>

### getParent() {#a790e91aa1f3fdca6d9e7c39d13f6d3f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LiveInterval &amp; llvm::SplitAnalysis::getParent ()</td>
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

<p>getParent - Return the last analyzed interval.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### getThroughBlocks() {#aa5836148f63cbfcd1ebe9facebf3c24b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BitVector &amp; llvm::SplitAnalysis::getThroughBlocks ()</td>
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

<p>getThroughBlocks - Return the set of through blocks.</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### getUseBlocks() {#a4cc231c4663974cb5b2a78d94a44b64d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; BlockInfo &gt; llvm::SplitAnalysis::getUseBlocks ()</td>
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

<p>getUseBlocks - Return an array of <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo">BlockInfo</a> objects for the basic blocks where CurLI has uses.</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<p>Referenced by <a href="#ac8280ad8ed267ed1fe319addf617dbd8">getNumLiveBlocks</a>.</p>

</div>
</div>

### getUseSlots() {#a59ea17ee48fc0e6e45506b633556acc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; SlotIndex &gt; llvm::SplitAnalysis::getUseSlots ()</td>
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

<p>getUseSlots - Return an array of <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> of instructions using CurLI.</p>


<p>This include both use and def operands, at most one entry per instruction.</p>


<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### isOriginalEndpoint() {#a6b388f6ec0c78d81a2d54efaac443691}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SplitAnalysis::isOriginalEndpoint (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isOriginalEndpoint - Return true if the original live range was killed or (re-)defined at Idx.</p>


<p>Idx should be the 'def' slot for a normal kill/def, and 'use' for an early-clobber def. This can be used to recognize code inserted by earlier live range splitting.</p>


<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a9a5e7c523f12f9f164b786769de1ca47">llvm::LiveRange::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a66ff664a97cd3c30de7e873335a0c075">llvm::LiveRange::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a757fd6afba0f531db70e78e057d147c6">llvm::LiveRange::end</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#afeb00b9049a2391c990df15692caef63">llvm::LiveRange::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a8e4649f48b911935d6604bde06468788">LIS</a> and <a href="#ae922fe27fed5647d4fe22789a6c61683">VRM</a>.</p>


<p>Referenced by <a href="#af3bf010ee796ca57e04c495963fd49b7">shouldSplitSingleBlock</a>.</p>

</div>
</div>

### isThroughBlock() {#aee6b2ae8e7ef8d354dce1dd815b9b7c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SplitAnalysis::isThroughBlock (unsigned MBB)</td>
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

<p>isThroughBlock - Return true if CurLI is live through MBB without uses.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### looksLikeLoopIV() {#a816a5b68a0407596872701a245ff51ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SplitAnalysis::looksLikeLoopIV ()</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### shouldSplitSingleBlock() {#af3bf010ee796ca57e04c495963fd49b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SplitAnalysis::shouldSplitSingleBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo">BlockInfo</a> &amp; BI, bool SingleInstrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>shouldSplitSingleBlock - Returns true if it would help to create a local live range for the instructions in BI.</p>


<p>There is normally no benefit to creating a live range for a single instruction, but it does enable register class inflation if the instruction has a restricted register class.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BI</td>
<td class="doxyParamItemDescription"><p>The block to be isolated.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SingleInstrs</td>
<td class="doxyParamItemDescription"><p>True when single instructions should be isolated.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 1587 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo/#afc1d576ff2321f8f3a604808be1b6f5b">llvm::SplitAnalysis::BlockInfo::FirstInstr</a>, <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo/#a5a04f02eff679552af69729e22e8f1a2">llvm::SplitAnalysis::BlockInfo::isOneInstr</a>, <a href="#a6b388f6ec0c78d81a2d54efaac443691">isOriginalEndpoint</a>, <a href="#a8e4649f48b911935d6604bde06468788">LIS</a>, <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo/#a4c7b9375634dd9b55f130ae4c428475c">llvm::SplitAnalysis::BlockInfo::LiveIn</a>, <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo/#a42e9b38c4f9bc0c0aca6f0c8c5cd1f80">llvm::SplitAnalysis::BlockInfo::LiveOut</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#ab56d031a917d10b407904c964bbb9083">TII</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### analyzeUses() {#aa2bf77b2c1703bd3bba2b63c8c712534}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitAnalysis::analyzeUses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>analyzeUses - Count instructions, basic blocks, and loops using CurLI.</p>

<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

### calcLiveBlockInfo() {#a1efea12880d546dc986832c05d09ceab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitAnalysis::calcLiveBlockInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>calcLiveBlockInfo - Compute per-block information about CurLI.</p>


<p>calcLiveBlockInfo - Fill the LiveBlocks array with information about blocks where CurLI is live.</p>


<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### LIS {#a8e4649f48b911935d6604bde06468788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LiveIntervals&amp; llvm::SplitAnalysis::LIS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<p>Referenced by <a href="#a6b3f9616a4146e9a88336afcaf92835e">countLiveBlocks</a>, <a href="#a6b388f6ec0c78d81a2d54efaac443691">isOriginalEndpoint</a>, <a href="#af3bf010ee796ca57e04c495963fd49b7">shouldSplitSingleBlock</a> and <a href="#a027186766ff82f05b729d087baf9a25f">SplitAnalysis</a>.</p>

</div>
</div>

### Loops {#ab4478598c0a88b09a259c89aead763c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineLoopInfo&amp; llvm::SplitAnalysis::Loops</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<p>Referenced by <a href="#a027186766ff82f05b729d087baf9a25f">SplitAnalysis</a>.</p>

</div>
</div>

### MF {#a192ed636858339b1ad1fbaa98d2f5d7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction&amp; llvm::SplitAnalysis::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<p>Referenced by <a href="#af8004c65ffc7336951db96a4a670bb48">getFirstSplitPoint</a>, <a href="#a723a443c171be9909a0f101c7b84333e">getLastSplitPoint</a> and <a href="#a027186766ff82f05b729d087baf9a25f">SplitAnalysis</a>.</p>

</div>
</div>

### TII {#ab56d031a917d10b407904c964bbb9083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo&amp; llvm::SplitAnalysis::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<p>Referenced by <a href="#af3bf010ee796ca57e04c495963fd49b7">shouldSplitSingleBlock</a> and <a href="#a027186766ff82f05b729d087baf9a25f">SplitAnalysis</a>.</p>

</div>
</div>

### VRM {#ae922fe27fed5647d4fe22789a6c61683}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VirtRegMap&amp; llvm::SplitAnalysis::VRM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<p>Referenced by <a href="#a6b388f6ec0c78d81a2d54efaac443691">isOriginalEndpoint</a> and <a href="#a027186766ff82f05b729d087baf9a25f">SplitAnalysis</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurLI {#ae1283500f144aec69f1d7880d456a7c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LiveInterval* llvm::SplitAnalysis::CurLI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### IPA {#a5dfe4237f9b9db5925a938574f9f4794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InsertPointAnalysis llvm::SplitAnalysis::IPA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert Point Analysis.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### LooksLikeLoopIV {#ac8d8ffd1cda13fda000ed857e58c5aa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SplitAnalysis::LooksLikeLoopIV = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LooksLikeLoopIV - The variable defines what looks like it could be a loop IV, where it defs a variable in the latch.</p>

<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### NumGapBlocks {#a2fb52ea1b4a3eaa3713dc79afd41d360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SplitAnalysis::NumGapBlocks = 0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NumGapBlocks - Number of duplicate entries in UseBlocks for blocks where the live range has a gap.</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### NumThroughBlocks {#accfa0bda726ab829a6ee83598ac5e5de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SplitAnalysis::NumThroughBlocks = 0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NumThroughBlocks - Number of live-through blocks.</p>

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### ThroughBlocks {#a9de691301365945a466e6fae810a8fc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::SplitAnalysis::ThroughBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ThroughBlocks - Block numbers where CurLI is live through without uses.</p>

<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### UseBlocks {#a58cea558f432d3c9c75eaf2529ac4f36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;BlockInfo, 8&gt; llvm::SplitAnalysis::UseBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>UseBlocks - Blocks where CurLI has uses.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### UseSlots {#ae0fe53d6540ec8de76f6e5167dfd3c25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SlotIndex, 8&gt; llvm::SplitAnalysis::UseSlots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
