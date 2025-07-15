---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/spliteditor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SplitEditor` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/spliteditor">SplitEditor</a> - Edit machine code and <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> for live range splitting. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SplitEditor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">CodeGen/SplitKit.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cde5d11cb61e7fc959fb30985b16553">RegAssignMap</a> = <a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a>, unsigned &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa77ec59d512f1087c5d1425eff4e0121">ValueForcePair</a> = <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *, 1 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d1c528cdd1719047ab434e34a1190c2">ValueMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; unsigned, unsigned &gt;, <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">ValueForcePair</a> &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ComplementSpillMode { <a href="#ad485b75a455867847a669a3f942cbcb7">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#ad485b75a455867847a669a3f942cbcb7">ComplementSpillMode</a> - Select how the complement live range should be created. <a href="#ad485b75a455867847a669a3f942cbcb7">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a6b060244db6c0da73f9ba4ec523559">SplitEditor</a> (SplitAnalysis &amp;SA, LiveIntervals &amp;LIS, VirtRegMap &amp;VRM, MachineDominatorTree &amp;MDT, MachineBlockFrequencyInfo &amp;MBFI, VirtRegAuxInfo &amp;VRAI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/spliteditor">SplitEditor</a> for editing the <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> analyzed by SA. <a href="#a4a6b060244db6c0da73f9ba4ec523559">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a907ca723e22613a6cfa9845d69f3eda6">reset</a> (LiveRangeEdit &amp;, ComplementSpillMode=SM_Partition)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reset - Prepare for a new split. <a href="#a907ca723e22613a6cfa9845d69f3eda6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45631ddcb7da79035271c3e491d6dc33">openIntv</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new virtual register and live interval. <a href="#a45631ddcb7da79035271c3e491d6dc33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bfb61fc98c72d3fb6bd00bd2d069e04">currentIntv</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>currentIntv - Return the current interval index. <a href="#a4bfb61fc98c72d3fb6bd00bd2d069e04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6c3837b7fc8ef9d70ddea519de3e06b">selectIntv</a> (unsigned Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>selectIntv - Select a previously opened interval index. <a href="#ad6c3837b7fc8ef9d70ddea519de3e06b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88924909b2d83abe8eb4ba2ac84eec6c">enterIntvBefore</a> (SlotIndex Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>enterIntvBefore - Enter the open interval before the instruction at Idx. <a href="#a88924909b2d83abe8eb4ba2ac84eec6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8808112c59febd729a9964ac6509d7d4">enterIntvAfter</a> (SlotIndex Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>enterIntvAfter - Enter the open interval after the instruction at Idx. <a href="#a8808112c59febd729a9964ac6509d7d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94fd41d857393a092523f88b19d1bef3">enterIntvAtEnd</a> (MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>enterIntvAtEnd - Enter the open interval at the end of MBB. <a href="#a94fd41d857393a092523f88b19d1bef3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88c7b413f0bb3edf821661f04cc6a5c7">useIntv</a> (const MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>useIntv - indicate that all instructions in MBB should use OpenLI. <a href="#a88c7b413f0bb3edf821661f04cc6a5c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd53356e2f1d5c95a058671c2daec939">useIntv</a> (SlotIndex Start, SlotIndex End)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>useIntv - indicate that all instructions in range should use OpenLI. <a href="#acd53356e2f1d5c95a058671c2daec939">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ab989120222d67308b4e03b2772fb6a">leaveIntvAfter</a> (SlotIndex Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>leaveIntvAfter - Leave the open interval after the instruction at Idx. <a href="#a8ab989120222d67308b4e03b2772fb6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9899a3945a73e70c7bb2800ef3865017">leaveIntvBefore</a> (SlotIndex Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>leaveIntvBefore - Leave the open interval before the instruction at Idx. <a href="#a9899a3945a73e70c7bb2800ef3865017">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98785a9cb443380b8f700cb764a6fd84">leaveIntvAtTop</a> (MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>leaveIntvAtTop - Leave the interval at the top of MBB. <a href="#a98785a9cb443380b8f700cb764a6fd84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a061a8d1b2719e16851521dddcd1a73cc">overlapIntv</a> (SlotIndex Start, SlotIndex End)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>overlapIntv - Indicate that all instructions in range should use the open interval if End does not have tied-def usage of the register and in this case complement interval is used. <a href="#a061a8d1b2719e16851521dddcd1a73cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98fa413da7a0053bf635119e74970219">finish</a> (SmallVectorImpl&lt; unsigned &gt; *LRMap=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>finish - after all the new live ranges have been created, compute the remaining live range, and rewrite instructions to use the new registers. <a href="#a98fa413da7a0053bf635119e74970219">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af56a81de61d43765dd1352743fd0bfc3">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>dump - print the current interval mapping to <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a>. <a href="#af56a81de61d43765dd1352743fd0bfc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5f72acf075c54b8f8ca8783a5683b63">splitSingleBlock</a> (const SplitAnalysis::BlockInfo &amp;BI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>splitSingleBlock - Split CurLI into a separate live interval around the uses in a single block. <a href="#ae5f72acf075c54b8f8ca8783a5683b63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab181eb57b4d30c914d782ad60b8d913f">splitLiveThroughBlock</a> (unsigned MBBNum, unsigned IntvIn, SlotIndex LeaveBefore, unsigned IntvOut, SlotIndex EnterAfter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>splitLiveThroughBlock - Split CurLI in the given block such that it enters the block in IntvIn and leaves it in IntvOut. <a href="#ab181eb57b4d30c914d782ad60b8d913f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d2296ecca42f33ce641b7341fde67d9">splitRegInBlock</a> (const SplitAnalysis::BlockInfo &amp;BI, unsigned IntvIn, SlotIndex LeaveBefore)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>splitRegInBlock - Split CurLI in the given block such that it enters the block in IntvIn and leaves it on the stack (or not at all). <a href="#a9d2296ecca42f33ce641b7341fde67d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8534c37f85077c1dd9fc3468f70d4618">splitRegOutBlock</a> (const SplitAnalysis::BlockInfo &amp;BI, unsigned IntvOut, SlotIndex EnterAfter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>splitRegOutBlock - Split CurLI in the given block such that it enters the block on the stack (or isn't live-in at all) and leaves it in IntvOut. <a href="#a8534c37f85077c1dd9fc3468f70d4618">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc">LiveIntervalCalc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abafe679e1c3ff6c96fe940bb30b0b072">getLICalc</a> (unsigned RegIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getLICalc - Return the LICalc to use for RegIdx. <a href="#abafe679e1c3ff6c96fe940bb30b0b072">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4f8cecf24bb124e9cbb61c48a772053">addDeadDef</a> (LiveInterval &amp;LI, VNInfo *VNI, bool Original)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a segment to the interval LI for the value number VNI. <a href="#ae4f8cecf24bb124e9cbb61c48a772053">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02eceeafe7df8ca55a1b97241081894e">defValue</a> (unsigned RegIdx, const VNInfo *ParentVNI, SlotIndex Idx, bool Original)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>defValue - define a value in RegIdx from ParentVNI at Idx. <a href="#a02eceeafe7df8ca55a1b97241081894e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cb3c1a4e898c47bcdb1606ed6254a8c">forceRecompute</a> (unsigned RegIdx, const VNInfo &amp;ParentVNI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>forceRecompute - Force the live range of ParentVNI in RegIdx to be recomputed by <a href="/web-llvm/docs/api/classes/llvm/liverangecalc/#ad445a5028efdf094173a202811f003e3">LiveRangeCalc::extend</a> regardless of the number of defs. <a href="#a2cb3c1a4e898c47bcdb1606ed6254a8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e4d174ae791fc6cf6f08c02fa1fe181">forceRecomputeVNI</a> (const VNInfo &amp;ParentVNI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calls forceRecompute() on any affected regidx and on ParentVNI predecessors in case of a phi definition. <a href="#a2e4d174ae791fc6cf6f08c02fa1fe181">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dbc84524bec861941b157f247bdccba">defFromParent</a> (unsigned RegIdx, const VNInfo *ParentVNI, SlotIndex UseIdx, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>defFromParent - Define Reg from ParentVNI at UseIdx using either rematerialization or a COPY from parent. <a href="#a6dbc84524bec861941b157f247bdccba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade6f19155581fbb8e3e1b9f7b22cddda">removeBackCopies</a> (SmallVectorImpl&lt; VNInfo * &gt; &amp;Copies)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeBackCopies - Remove the copy instructions that defines the values in the vector in the complement interval. <a href="#ade6f19155581fbb8e3e1b9f7b22cddda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1bff60ae7d5fdb9af4959de42842ceb">findShallowDominator</a> (MachineBasicBlock *MBB, MachineBasicBlock *DefMBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getShallowDominator - Returns the least busy dominator of MBB that is also dominated by DefMBB. <a href="#ad1bff60ae7d5fdb9af4959de42842ceb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac32ce98741d2fe166e1cf6ce87a6343d">computeRedundantBackCopies</a> (DenseSet&lt; unsigned &gt; &amp;NotToHoistSet, SmallVectorImpl&lt; VNInfo * &gt; &amp;BackCopies)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find out all the backCopies dominated by others. <a href="#ac32ce98741d2fe166e1cf6ce87a6343d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a591700f4798fd0ce99310f3009760902">hoistCopies</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hoist back-copies to the complement interval. <a href="#a591700f4798fd0ce99310f3009760902">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1844eb4ca3e778959b10046057e4ab3">transferValues</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>transferValues - Transfer values to the new ranges. <a href="#ab1844eb4ca3e778959b10046057e4ab3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaac345aa89eae6ea7fb4bfdff840c5a4">extendPHIRange</a> (MachineBasicBlock &amp;B, LiveIntervalCalc &amp;LIC, LiveRange &amp;LR, LaneBitmask LM, ArrayRef&lt; SlotIndex &gt; Undefs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Live range <span class="doxyComputerOutput">LR</span> corresponding to the lane Mask <span class="doxyComputerOutput">LM</span> has a live PHI def at the beginning of block <span class="doxyComputerOutput">B</span>. <a href="#aaac345aa89eae6ea7fb4bfdff840c5a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1f75bb4062af6ca2e997ba2c4a944af">extendPHIKillRanges</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>extendPHIKillRanges - Extend the ranges of all values killed by original parent PHIDefs. <a href="#ac1f75bb4062af6ca2e997ba2c4a944af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53ba2647d07a01eeec5eade25fcfae62">rewriteAssigned</a> (bool ExtendRanges)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>rewriteAssigned - Rewrite all uses of Edit.getReg() to assigned registers. <a href="#a53ba2647d07a01eeec5eade25fcfae62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a203d60333fab9cc88a7bef59e3f03667">deleteRematVictims</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>deleteRematVictims - Delete defs that are dead after rematerializing. <a href="#a203d60333fab9cc88a7bef59e3f03667">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb8af7b3025b4a04cd0e183e7cfa7e1d">buildCopy</a> (Register FromReg, Register ToReg, LaneBitmask LaneMask, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator InsertBefore, bool Late, unsigned RegIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a copy instruction copying <span class="doxyComputerOutput">FromReg</span> to <span class="doxyComputerOutput">ToReg</span> before <span class="doxyComputerOutput">InsertBefore</span>. <a href="#afb8af7b3025b4a04cd0e183e7cfa7e1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54735b4f676b8ebf230c26c77309c017">buildSingleSubRegCopy</a> (Register FromReg, Register ToReg, MachineBasicBlock &amp;MB, MachineBasicBlock::iterator InsertBefore, unsigned SubIdx, LiveInterval &amp;DestLI, bool Late, SlotIndex Def, const MCInstrDesc &amp;Desc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/splitanalysis">SplitAnalysis</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d7dd983067f4fc39792f4ce3f865bbe">SA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6177fa47480387b122339f41ddc5fc5">LIS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eabce8fe69f487935fcd52aac109dfd">VRM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac90ea728407bfca42f773e50bdc686f3">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a270cf16e10e7f48c6846d309ebb166f0">MDT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60516d327cd65cd7ee7242f504168833">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63b690fef0af1e15782f26a4f082458e">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af65fd601f555507907e4014bfbf48a47">MBFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo">VirtRegAuxInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f4cd81ad99f034ed597f9bf76a966b9">VRAI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverangeedit">LiveRangeEdit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a827db82edde9d55520777d811065888f">Edit</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Edit - The current parent register and new intervals created. <a href="#a827db82edde9d55520777d811065888f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c141b97bd3525fa05aa2e506c61a4d0">OpenIdx</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Index into Edit of the currently open interval. <a href="#a6c141b97bd3525fa05aa2e506c61a4d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad485b75a455867847a669a3f942cbcb7">ComplementSpillMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeaa3364b5db5e356754263ca5bfd6a1">SpillMode</a> = <a href="#ad485b75a455867847a669a3f942cbcb7a5cd5c6b9f5402366a8e7a28a55925720">SM_Partition</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current spill mode, selected by <a href="#a907ca723e22613a6cfa9845d69f3eda6">reset()</a>. <a href="#aaeaa3364b5db5e356754263ca5bfd6a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap/#a6b645fcc5ae44b9a8e2fef275890ae4b">RegAssignMap::Allocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbfd535403078e58f232de108093e18e">Allocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocator for the interval map. <a href="#adbfd535403078e58f232de108093e18e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmap">RegAssignMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8086e21908bf518853877f7ae6a912fe">RegAssign</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RegAssign - Map of the assigned register indexes. <a href="#a8086e21908bf518853877f7ae6a912fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">ValueMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5028b17a5a28f99ec554c098396c6bba">Values</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Values - keep track of the mapping from parent values to values in the new intervals. <a href="#a5028b17a5a28f99ec554c098396c6bba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc">LiveIntervalCalc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafacd34b35d67ddacc6754ee055c3609">LICalc</a>[2]</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LICalc - Cache for computing live ranges and SSA update. <a href="#aafacd34b35d67ddacc6754ee055c3609">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/spliteditor">SplitEditor</a> - Edit machine code and <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> for live range splitting.</p>


<ul class="doxyList ">
<li>Create a <a href="/web-llvm/docs/api/classes/llvm/spliteditor">SplitEditor</a> from a <a href="/web-llvm/docs/api/classes/llvm/splitanalysis">SplitAnalysis</a>.</li>
<li>Start a new live interval with openIntv.</li>
<li>Mark the places where the new interval is entered using enterIntv*</li>
<li>Mark the ranges where the new interval is used with useIntv*</li>
<li>Mark the places where the interval is exited with exitIntv*.</li>
<li>Finish the current interval with closeIntv and repeat from 2.</li>
<li>Rewrite instructions with <a href="#a98fa413da7a0053bf635119e74970219">finish()</a>.</li>
</ul>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### RegAssignMap {#a8cde5d11cb61e7fc959fb30985b16553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SplitEditor::RegAssignMap =  IntervalMap&lt;SlotIndex, unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### ValueForcePair {#aa77ec59d512f1087c5d1425eff4e0121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SplitEditor::ValueForcePair =  PointerIntPair&lt;VNInfo *, 1&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### ValueMap {#a0d1c528cdd1719047ab434e34a1190c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SplitEditor::ValueMap =  DenseMap&lt;std::pair&lt;unsigned, unsigned&gt;, ValueForcePair&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### ComplementSpillMode {#ad485b75a455867847a669a3f942cbcb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::SplitEditor::ComplementSpillMode </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#ad485b75a455867847a669a3f942cbcb7">ComplementSpillMode</a> - Select how the complement live range should be created.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SM_Partition<a id="ad485b75a455867847a669a3f942cbcb7a5cd5c6b9f5402366a8e7a28a55925720"></a></td>
<td class="doxyEnumItemDescription"><a href="#ad485b75a455867847a669a3f942cbcb7a5cd5c6b9f5402366a8e7a28a55925720">SM_Partition(Default)</a> - Try to create the complement interval so it doesn't overlap any other intervals, and the original interval is partitioned</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SM_Size<a id="ad485b75a455867847a669a3f942cbcb7ade36d2a249a7f767c968e8667190bc11"></a></td>
<td class="doxyEnumItemDescription">SM_Size - Overlap intervals to minimize the number of inserted COPY instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SM_Speed<a id="ad485b75a455867847a669a3f942cbcb7a7bfb05c8742572ff98fd4f226bb0aede"></a></td>
<td class="doxyEnumItemDescription">SM_Speed - Overlap intervals to minimize the expected execution frequency of the inserted copies</td>
</tr>

</table>
</dd>
</dl>


<p><a href="/web-llvm/docs/api/classes/llvm/spliteditor">SplitEditor</a> automatically creates interval 0 to contain anything that isn't added to another interval. This complement interval can get quite complicated, and it can sometimes be an advantage to allow it to overlap the other intervals. If it is going to spill anyway, no registers are wasted by keeping a value in two places at the same time.</p>


<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SplitEditor() {#a4a6b060244db6c0da73f9ba4ec523559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SplitEditor::SplitEditor (<a href="/web-llvm/docs/api/classes/llvm/splitanalysis">SplitAnalysis</a> &amp; SA, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS, <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> &amp; VRM, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> &amp; MDT, <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> &amp; MBFI, <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo">VirtRegAuxInfo</a> &amp; VRAI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/spliteditor">SplitEditor</a> for editing the <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> analyzed by SA.</p>


<p>Newly created intervals will be appended to newIntervals.</p>


<p>Declaration at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### currentIntv() {#a4bfb61fc98c72d3fb6bd00bd2d069e04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SplitEditor::currentIntv ()</td>
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

<p>currentIntv - Return the current interval index.</p>

<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### dump() {#af56a81de61d43765dd1352743fd0bfc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SplitEditor::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>dump - print the current interval mapping to <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a>.</p>

<p>Declaration at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>


<p>Referenced by <a href="#a94fd41d857393a092523f88b19d1bef3">enterIntvAtEnd</a>, <a href="#a98785a9cb443380b8f700cb764a6fd84">leaveIntvAtTop</a>, <a href="#a061a8d1b2719e16851521dddcd1a73cc">overlapIntv</a> and <a href="#acd53356e2f1d5c95a058671c2daec939">useIntv</a>.</p>

</div>
</div>

### enterIntvAfter() {#a8808112c59febd729a9964ac6509d7d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex SplitEditor::enterIntvAfter (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>enterIntvAfter - Enter the open interval after the instruction at Idx.</p>


<p>Return the beginning of the new live range.</p>


<p>Declaration at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 680 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a9ee9e2030e830feecf0a2c27c6f3c09f">llvm::SlotIndex::getBoundaryIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ad989a0c1b26066308798f4d11a0e69df">llvm::VNInfo::id</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ab181eb57b4d30c914d782ad60b8d913f">splitLiveThroughBlock</a> and <a href="#a8534c37f85077c1dd9fc3468f70d4618">splitRegOutBlock</a>.</p>

</div>
</div>

### enterIntvAtEnd() {#a94fd41d857393a092523f88b19d1bef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex SplitEditor::enterIntvAtEnd (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>enterIntvAtEnd - Enter the open interval at the end of MBB.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the open interval from the inserted copy to the MBB end. Return the beginning of the new live range.</p>


<p>Declaration at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 698 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="#af56a81de61d43765dd1352743fd0bfc3">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ac832da130f4d71a4533a69d98315fb19">llvm::SlotIndex::getPrevSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ad989a0c1b26066308798f4d11a0e69df">llvm::VNInfo::id</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>.</p>


<p>Referenced by <a href="#ab181eb57b4d30c914d782ad60b8d913f">splitLiveThroughBlock</a>.</p>

</div>
</div>

### enterIntvBefore() {#a88924909b2d83abe8eb4ba2ac84eec6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex SplitEditor::enterIntvBefore (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>enterIntvBefore - Enter the open interval before the instruction at Idx.</p>


<p>If the parent interval is not live before Idx, a COPY is not inserted. Return the beginning of the new live range.</p>


<p>Declaration at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#aa94e57689dd16c1c4de909511f1b2ea8">llvm::SlotIndex::getBaseIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ad989a0c1b26066308798f4d11a0e69df">llvm::VNInfo::id</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ab181eb57b4d30c914d782ad60b8d913f">splitLiveThroughBlock</a>, <a href="#a9d2296ecca42f33ce641b7341fde67d9">splitRegInBlock</a>, <a href="#a8534c37f85077c1dd9fc3468f70d4618">splitRegOutBlock</a> and <a href="#ae5f72acf075c54b8f8ca8783a5683b63">splitSingleBlock</a>.</p>

</div>
</div>

### finish() {#a98fa413da7a0053bf635119e74970219}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::finish (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; * LRMap=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>finish - after all the new live ranges have been created, compute the remaining live range, and rewrite instructions to use the new registers.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">LRMap</td>
<td class="doxyParamItemDescription"><p>When not null, this vector will map each live range in Edit back to the indices returned by openIntv. There may be extra indices created by dead code elimination.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 1502 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a38c50aa8e3e9588f4f968c2e03a0cee0">llvm::SmallVectorImpl&lt; T &gt;::assign</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ab72366fd538f240cbb53dac39368cdfc">llvm::VNInfo::isUnused</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a0aac3ef1eadaa206a70b767730ef3c5b">llvm::LiveInterval::removeEmptySubRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a687cab1756967efc8f0ce66105531755">llvm::LiveRange::RenumberValues</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#ad485b75a455867847a669a3f942cbcb7a5cd5c6b9f5402366a8e7a28a55925720">SM_Partition</a>, <a href="#ad485b75a455867847a669a3f942cbcb7ade36d2a249a7f767c968e8667190bc11">SM_Size</a> and <a href="#ad485b75a455867847a669a3f942cbcb7a7bfb05c8742572ff98fd4f226bb0aede">SM_Speed</a>.</p>

</div>
</div>

### leaveIntvAfter() {#a8ab989120222d67308b4e03b2772fb6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex SplitEditor::leaveIntvAfter (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>leaveIntvAfter - Leave the open interval after the instruction at Idx.</p>


<p>Return the end of the live range.</p>


<p>Declaration at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 746 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a9ee9e2030e830feecf0a2c27c6f3c09f">llvm::SlotIndex::getBoundaryIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ac3782d262b2a58da44d43c6d995aef9d">llvm::SlotIndex::getNextSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ad989a0c1b26066308798f4d11a0e69df">llvm::VNInfo::id</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a0b73244049319d841fd11a238f35b5d1">llvm::SlotIndex::isSameInstr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a9d2296ecca42f33ce641b7341fde67d9">splitRegInBlock</a> and <a href="#ae5f72acf075c54b8f8ca8783a5683b63">splitSingleBlock</a>.</p>

</div>
</div>

### leaveIntvAtTop() {#a98785a9cb443380b8f700cb764a6fd84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex SplitEditor::leaveIntvAtTop (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>leaveIntvAtTop - Leave the interval at the top of MBB.</p>


<p>Add liveness from the MBB top to the copy. Return the end of the live range.</p>


<p>Declaration at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 796 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="#af56a81de61d43765dd1352743fd0bfc3">dump</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>.</p>


<p>Referenced by <a href="#ab181eb57b4d30c914d782ad60b8d913f">splitLiveThroughBlock</a>.</p>

</div>
</div>

### leaveIntvBefore() {#a9899a3945a73e70c7bb2800ef3865017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex SplitEditor::leaveIntvBefore (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>leaveIntvBefore - Leave the open interval before the instruction at Idx.</p>


<p>Return the end of the live range.</p>


<p>Declaration at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 777 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#aa94e57689dd16c1c4de909511f1b2ea8">llvm::SlotIndex::getBaseIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ac3782d262b2a58da44d43c6d995aef9d">llvm::SlotIndex::getNextSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ad989a0c1b26066308798f4d11a0e69df">llvm::VNInfo::id</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ab181eb57b4d30c914d782ad60b8d913f">splitLiveThroughBlock</a>, <a href="#a9d2296ecca42f33ce641b7341fde67d9">splitRegInBlock</a> and <a href="#ae5f72acf075c54b8f8ca8783a5683b63">splitSingleBlock</a>.</p>

</div>
</div>

### openIntv() {#a45631ddcb7da79035271c3e491d6dc33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SplitEditor::openIntv ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new virtual register and live interval.</p>


<p>Return the interval index, starting from 1. <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp/#a4ab9bd667f674c16b2cee01ab8823644">Interval</a> index 0 is the implicit complement interval.</p>


<p>Declaration at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>Referenced by <a href="#a9d2296ecca42f33ce641b7341fde67d9">splitRegInBlock</a>, <a href="#a8534c37f85077c1dd9fc3468f70d4618">splitRegOutBlock</a> and <a href="#ae5f72acf075c54b8f8ca8783a5683b63">splitSingleBlock</a>.</p>

</div>
</div>

### overlapIntv() {#a061a8d1b2719e16851521dddcd1a73cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::overlapIntv (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Start, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>overlapIntv - Indicate that all instructions in range should use the open interval if End does not have tied-def usage of the register and in this case complement interval is used.</p>


<p>Let the complement interval be live.</p>


<p>This doubles the register pressure, but is sometimes required to deal with register uses after the last valid split point.</p>


<p>The Start index should be a return value from a leaveIntv* call, and End should be in the same basic block. The parent interval must have the same value across the range.</p>


<p>Declaration at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 823 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#af56a81de61d43765dd1352743fd0bfc3">dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp/#a5cf70104d9aee77d3e009f270354e7ad">hasTiedUseOf</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a9d2296ecca42f33ce641b7341fde67d9">splitRegInBlock</a> and <a href="#ae5f72acf075c54b8f8ca8783a5683b63">splitSingleBlock</a>.</p>

</div>
</div>

### reset() {#a907ca723e22613a6cfa9845d69f3eda6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::reset (<a href="/web-llvm/docs/api/classes/llvm/liverangeedit">LiveRangeEdit</a> &amp; LRE, <a href="#ad485b75a455867847a669a3f942cbcb7">ComplementSpillMode</a> SM=<a href="#ad485b75a455867847a669a3f942cbcb7a5cd5c6b9f5402366a8e7a28a55925720">SM_Partition</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>reset - Prepare for a new split.</p>

<p>Declaration at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

### selectIntv() {#ad6c3837b7fc8ef9d70ddea519de3e06b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::selectIntv (unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>selectIntv - Select a previously opened interval index.</p>

<p>Declaration at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 656 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="#ab181eb57b4d30c914d782ad60b8d913f">splitLiveThroughBlock</a>, <a href="#a9d2296ecca42f33ce641b7341fde67d9">splitRegInBlock</a> and <a href="#a8534c37f85077c1dd9fc3468f70d4618">splitRegOutBlock</a>.</p>

</div>
</div>

### splitLiveThroughBlock() {#ab181eb57b4d30c914d782ad60b8d913f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::splitLiveThroughBlock (unsigned MBBNum, unsigned IntvIn, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> LeaveBefore, unsigned IntvOut, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> EnterAfter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>splitLiveThroughBlock - Split CurLI in the given block such that it enters the block in IntvIn and leaves it in IntvOut.</p>


<p>There may be uses in the block, but they will be ignored when placing split points.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MBBNum</td>
<td class="doxyParamItemDescription"><p>Block number.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IntvIn</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp/#a4ab9bd667f674c16b2cee01ab8823644">Interval</a> index entering the block.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LeaveBefore</td>
<td class="doxyParamItemDescription"><p>When set, leave IntvIn before this point.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IntvOut</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp/#a4ab9bd667f674c16b2cee01ab8823644">Interval</a> index leaving the block.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EnterAfter</td>
<td class="doxyParamItemDescription"><p>When set, enter IntvOut after this point.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 1633 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a8808112c59febd729a9964ac6509d7d4">enterIntvAfter</a>, <a href="#a94fd41d857393a092523f88b19d1bef3">enterIntvAtEnd</a>, <a href="#a88924909b2d83abe8eb4ba2ac84eec6c">enterIntvBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#aa94e57689dd16c1c4de909511f1b2ea8">llvm::SlotIndex::getBaseIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a9ee9e2030e830feecf0a2c27c6f3c09f">llvm::SlotIndex::getBoundaryIndex</a>, <a href="#a98785a9cb443380b8f700cb764a6fd84">leaveIntvAtTop</a>, <a href="#a9899a3945a73e70c7bb2800ef3865017">leaveIntvBefore</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#ad6c3837b7fc8ef9d70ddea519de3e06b">selectIntv</a> and <a href="#a88c7b413f0bb3edf821661f04cc6a5c7">useIntv</a>.</p>

</div>
</div>

### splitRegInBlock() {#a9d2296ecca42f33ce641b7341fde67d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::splitRegInBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo">SplitAnalysis::BlockInfo</a> &amp; BI, unsigned IntvIn, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> LeaveBefore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>splitRegInBlock - Split CurLI in the given block such that it enters the block in IntvIn and leaves it on the stack (or not at all).</p>


<p>Split points are placed in a way that avoids putting uses in the stack interval. This may require creating a local interval when there is interference.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BI</td>
<td class="doxyParamItemDescription"><p>Block descriptor.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IntvIn</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp/#a4ab9bd667f674c16b2cee01ab8823644">Interval</a> index entering the block. Not 0.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LeaveBefore</td>
<td class="doxyParamItemDescription"><p>When set, leave IntvIn before this point.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 1736 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a88924909b2d83abe8eb4ba2ac84eec6c">enterIntvBefore</a>, <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo/#afc1d576ff2321f8f3a604808be1b6f5b">llvm::SplitAnalysis::BlockInfo::FirstInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a9ee9e2030e830feecf0a2c27c6f3c09f">llvm::SlotIndex::getBoundaryIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo/#abaae5e7f00635019260dd4d2506e2b58">llvm::SplitAnalysis::BlockInfo::LastInstr</a>, <a href="#a8ab989120222d67308b4e03b2772fb6a">leaveIntvAfter</a>, <a href="#a9899a3945a73e70c7bb2800ef3865017">leaveIntvBefore</a>, <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo/#a4c7b9375634dd9b55f130ae4c428475c">llvm::SplitAnalysis::BlockInfo::LiveIn</a>, <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo/#a42e9b38c4f9bc0c0aca6f0c8c5cd1f80">llvm::SplitAnalysis::BlockInfo::LiveOut</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo/#a6d25ab70a5fda1310dad85ddb8ecaa22">llvm::SplitAnalysis::BlockInfo::MBB</a>, <a href="#a45631ddcb7da79035271c3e491d6dc33">openIntv</a>, <a href="#a061a8d1b2719e16851521dddcd1a73cc">overlapIntv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="#ad6c3837b7fc8ef9d70ddea519de3e06b">selectIntv</a> and <a href="#a88c7b413f0bb3edf821661f04cc6a5c7">useIntv</a>.</p>

</div>
</div>

### splitRegOutBlock() {#a8534c37f85077c1dd9fc3468f70d4618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::splitRegOutBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo">SplitAnalysis::BlockInfo</a> &amp; BI, unsigned IntvOut, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> EnterAfter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>splitRegOutBlock - Split CurLI in the given block such that it enters the block on the stack (or isn't live-in at all) and leaves it in IntvOut.</p>


<p>Split points are placed to avoid interference and such that the uses are not in the stack interval. This may require creating a local interval when there is interference.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BI</td>
<td class="doxyParamItemDescription"><p>Block descriptor.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IntvOut</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/msf/mappedblockstream-cpp/#a4ab9bd667f674c16b2cee01ab8823644">Interval</a> index leaving the block.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EnterAfter</td>
<td class="doxyParamItemDescription"><p>When set, enter IntvOut after this point.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 560 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 1829 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a8808112c59febd729a9964ac6509d7d4">enterIntvAfter</a>, <a href="#a88924909b2d83abe8eb4ba2ac84eec6c">enterIntvBefore</a>, <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo/#afc1d576ff2321f8f3a604808be1b6f5b">llvm::SplitAnalysis::BlockInfo::FirstInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#aa94e57689dd16c1c4de909511f1b2ea8">llvm::SlotIndex::getBaseIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo/#abaae5e7f00635019260dd4d2506e2b58">llvm::SplitAnalysis::BlockInfo::LastInstr</a>, <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo/#a4c7b9375634dd9b55f130ae4c428475c">llvm::SplitAnalysis::BlockInfo::LiveIn</a>, <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo/#a42e9b38c4f9bc0c0aca6f0c8c5cd1f80">llvm::SplitAnalysis::BlockInfo::LiveOut</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo/#a6d25ab70a5fda1310dad85ddb8ecaa22">llvm::SplitAnalysis::BlockInfo::MBB</a>, <a href="#a45631ddcb7da79035271c3e491d6dc33">openIntv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="#ad6c3837b7fc8ef9d70ddea519de3e06b">selectIntv</a> and <a href="#a88c7b413f0bb3edf821661f04cc6a5c7">useIntv</a>.</p>

</div>
</div>

### splitSingleBlock() {#ae5f72acf075c54b8f8ca8783a5683b63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::splitSingleBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo">SplitAnalysis::BlockInfo</a> &amp; BI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>splitSingleBlock - Split CurLI into a separate live interval around the uses in a single block.</p>


<p>This is intended to be used as part of a larger split, and doesn't call <a href="#a98fa413da7a0053bf635119e74970219">finish()</a>.</p>


<p>Declaration at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 1607 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="#a88924909b2d83abe8eb4ba2ac84eec6c">enterIntvBefore</a>, <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo/#afc1d576ff2321f8f3a604808be1b6f5b">llvm::SplitAnalysis::BlockInfo::FirstInstr</a>, <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo/#abaae5e7f00635019260dd4d2506e2b58">llvm::SplitAnalysis::BlockInfo::LastInstr</a>, <a href="#a8ab989120222d67308b4e03b2772fb6a">leaveIntvAfter</a>, <a href="#a9899a3945a73e70c7bb2800ef3865017">leaveIntvBefore</a>, <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo/#a42e9b38c4f9bc0c0aca6f0c8c5cd1f80">llvm::SplitAnalysis::BlockInfo::LiveOut</a>, <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo/#a6d25ab70a5fda1310dad85ddb8ecaa22">llvm::SplitAnalysis::BlockInfo::MBB</a>, <a href="#a45631ddcb7da79035271c3e491d6dc33">openIntv</a>, <a href="#a061a8d1b2719e16851521dddcd1a73cc">overlapIntv</a> and <a href="#a88c7b413f0bb3edf821661f04cc6a5c7">useIntv</a>.</p>

</div>
</div>

### useIntv() {#a88c7b413f0bb3edf821661f04cc6a5c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::useIntv (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>useIntv - indicate that all instructions in MBB should use OpenLI.</p>

<p>Declaration at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 735 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#a88c7b413f0bb3edf821661f04cc6a5c7">useIntv</a>.</p>


<p>Referenced by <a href="#ab181eb57b4d30c914d782ad60b8d913f">splitLiveThroughBlock</a>, <a href="#a9d2296ecca42f33ce641b7341fde67d9">splitRegInBlock</a>, <a href="#a8534c37f85077c1dd9fc3468f70d4618">splitRegOutBlock</a>, <a href="#ae5f72acf075c54b8f8ca8783a5683b63">splitSingleBlock</a> and <a href="#a88c7b413f0bb3edf821661f04cc6a5c7">useIntv</a>.</p>

</div>
</div>

### useIntv() {#acd53356e2f1d5c95a058671c2daec939}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::useIntv (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Start, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>useIntv - indicate that all instructions in range should use OpenLI.</p>

<p>Declaration at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 739 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#af56a81de61d43765dd1352743fd0bfc3">dump</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addDeadDef() {#ae4f8cecf24bb124e9cbb61c48a772053}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::addDeadDef (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * VNI, bool Original)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a segment to the interval LI for the value number VNI.</p>


<p>If LI has subranges, corresponding segments will be added to them as well, but with newly created value numbers. If Original is true, dead def will only be added a subrange of LI if the corresponding subrange of the original interval has a def at this index. Otherwise, all subranges of LI will be updated.</p>


<p>Declaration at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

### buildCopy() {#afb8af7b3025b4a04cd0e183e7cfa7e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex SplitEditor::buildCopy (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> FromReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ToReg, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsertBefore, bool Late, unsigned RegIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a copy instruction copying <span class="doxyComputerOutput">FromReg</span> to <span class="doxyComputerOutput">ToReg</span> before <span class="doxyComputerOutput">InsertBefore</span>.</p>


<p>This can be invoked with a <span class="doxyComputerOutput">LaneMask</span> which may make it necessary to construct a sequence of copies to cover it exactly.</p>


<p>Declaration at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

### buildSingleSubRegCopy() {#a54735b4f676b8ebf230c26c77309c017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex SplitEditor::buildSingleSubRegCopy (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> FromReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ToReg, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsertBefore, unsigned SubIdx, <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; DestLI, bool Late, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Def, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; Desc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

### computeRedundantBackCopies() {#ac32ce98741d2fe166e1cf6ce87a6343d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::computeRedundantBackCopies (<a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt; &amp; NotToHoistSet, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * &gt; &amp; BackCopies)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find out all the backCopies dominated by others.</p>

<p>Declaration at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 959 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

### defFromParent() {#a6dbc84524bec861941b157f247bdccba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo * SplitEditor::defFromParent (unsigned RegIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * ParentVNI, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> UseIdx, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>defFromParent - Define Reg from ParentVNI at UseIdx using either rematerialization or a COPY from parent.</p>


<p>Return the new value.</p>


<p>Declaration at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

### defValue() {#a02eceeafe7df8ca55a1b97241081894e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo * SplitEditor::defValue (unsigned RegIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * ParentVNI, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx, bool Original)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>defValue - define a value in RegIdx from ParentVNI at Idx.</p>


<p>Idx does not have to be ParentVNI-&gt;def, but it must be contained within ParentVNI's live range in ParentLI. The new value is added to the value map. The value being defined may either come from rematerialization (or an inserted copy), or it may be coming from the original interval. The parameter Original should be true in the latter case, otherwise it should be false. Return the new LI value.</p>


<p>Declaration at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

### deleteRematVictims() {#a203d60333fab9cc88a7bef59e3f03667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::deleteRematVictims ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>deleteRematVictims - Delete defs that are dead after rematerializing.</p>

<p>Declaration at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 1439 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

### extendPHIKillRanges() {#ac1f75bb4062af6ca2e997ba2c4a944af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::extendPHIKillRanges ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>extendPHIKillRanges - Extend the ranges of all values killed by original parent PHIDefs.</p>

<p>Declaration at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 1272 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

### extendPHIRange() {#aaac345aa89eae6ea7fb4bfdff840c5a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::extendPHIRange (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc">LiveIntervalCalc</a> &amp; LIC, <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LM, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt; Undefs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Live range <span class="doxyComputerOutput">LR</span> corresponding to the lane Mask <span class="doxyComputerOutput">LM</span> has a live PHI def at the beginning of block <span class="doxyComputerOutput">B</span>.</p>


<p>Extend the range <span class="doxyComputerOutput">LR</span> of all predecessor values that reach this def. If <span class="doxyComputerOutput">LR</span> is a subrange, the array <span class="doxyComputerOutput">Undefs</span> is the set of all locations where it is undefined via &lt;def,read-undef&gt; in other subranges for the same register.</p>


<p>Declaration at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 1254 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

### findShallowDominator() {#ad1bff60ae7d5fdb9af4959de42842ceb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * SplitEditor::findShallowDominator (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DefMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getShallowDominator - Returns the least busy dominator of MBB that is also dominated by DefMBB.</p>


<p>Busy is measured by loop depth.</p>


<p>Declaration at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 903 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

### forceRecompute() {#a2cb3c1a4e898c47bcdb1606ed6254a8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::forceRecompute (unsigned RegIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> &amp; ParentVNI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>forceRecompute - Force the live range of ParentVNI in RegIdx to be recomputed by <a href="/web-llvm/docs/api/classes/llvm/liverangecalc/#ad445a5028efdf094173a202811f003e3">LiveRangeCalc::extend</a> regardless of the number of defs.</p>


<p>This is used for values whose live range doesn't match RegAssign exactly. They could have rematerialized, or back-copies may have been moved.</p>


<p>Declaration at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

### forceRecomputeVNI() {#a2e4d174ae791fc6cf6f08c02fa1fe181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::forceRecomputeVNI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> &amp; ParentVNI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calls forceRecompute() on any affected regidx and on ParentVNI predecessors in case of a phi definition.</p>

<p>Declaration at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 1467 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

### getLICalc() {#abafe679e1c3ff6c96fe940bb30b0b072}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervalCalc &amp; llvm::SplitEditor::getLICalc (unsigned RegIdx)</td>
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

<p>getLICalc - Return the LICalc to use for RegIdx.</p>


<p>In spill mode, the complement interval can overlap the other intervals, so it gets its own LICalc instance. When not in spill mode, all intervals can share one.</p>


<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### hoistCopies() {#a591700f4798fd0ce99310f3009760902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::hoistCopies ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hoist back-copies to the complement interval.</p>


<p>For SM_Size mode, find a common dominator for all the back-copies for the same ParentVNI and hoist the backcopies to the dominator BB.</p>


<p>It tries to hoist all the back-copies to one BB if it is beneficial, or else simply remove redundant backcopies dominated by others.</p>


<p>For SM_Speed mode, if the common dominator is hot and it is not beneficial to do the hoisting, simply remove the dominated backcopies for the same ParentVNI.</p>


<p>Declaration at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 1012 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

### removeBackCopies() {#ade6f19155581fbb8e3e1b9f7b22cddda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::removeBackCopies (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * &gt; &amp; Copies)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removeBackCopies - Remove the copy instructions that defines the values in the vector in the complement interval.</p>

<p>Declaration at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 853 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

### rewriteAssigned() {#a53ba2647d07a01eeec5eade25fcfae62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SplitEditor::rewriteAssigned (bool ExtendRanges)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>rewriteAssigned - Rewrite all uses of Edit.getReg() to assigned registers.</p>


<p>rewriteAssigned - Rewrite all uses of Edit-&gt;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg()</a>.</p>


<p>Declaration at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 1316 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

### transferValues() {#ab1844eb4ca3e778959b10046057e4ab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SplitEditor::transferValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>transferValues - Transfer values to the new ranges.</p>


<p>transferValues - Transfer all possible values to the new live ranges.</p>


<p>Return true if any ranges were skipped.</p>


<p>Values that were rematerialized are left alone, they need LICalc.extend().</p>


<p>Declaration at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>, definition at line 1135 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp">SplitKit.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allocator {#adbfd535403078e58f232de108093e18e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegAssignMap::Allocator llvm::SplitEditor::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocator for the interval map.</p>


<p>This will eventually be shared with <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> and <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a>.</p>


<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### Edit {#a827db82edde9d55520777d811065888f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRangeEdit* llvm::SplitEditor::Edit = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Edit - The current parent register and new intervals created.</p>

<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### LICalc {#aafacd34b35d67ddacc6754ee055c3609}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervalCalc llvm::SplitEditor::LICalc[2]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LICalc - Cache for computing live ranges and SSA update.</p>


<p>Each instance can only handle non-overlapping live ranges, so use a separate <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc">LiveIntervalCalc</a> instance for the complement interval when in spill mode.</p>


<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### LIS {#aa6177fa47480387b122339f41ddc5fc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals&amp; llvm::SplitEditor::LIS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### MBFI {#af65fd601f555507907e4014bfbf48a47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBlockFrequencyInfo&amp; llvm::SplitEditor::MBFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### MDT {#a270cf16e10e7f48c6846d309ebb166f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineDominatorTree&amp; llvm::SplitEditor::MDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### MRI {#ac90ea728407bfca42f773e50bdc686f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; llvm::SplitEditor::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### OpenIdx {#a6c141b97bd3525fa05aa2e506c61a4d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SplitEditor::OpenIdx = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Index into Edit of the currently open interval.</p>


<p>The index 0 is used for the complement, so the first interval started by openIntv will be 1.</p>


<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### RegAssign {#a8086e21908bf518853877f7ae6a912fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegAssignMap llvm::SplitEditor::RegAssign</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RegAssign - Map of the assigned register indexes.</p>


<p>Edit.get(RegAssign.lookup(Idx)) is the register that should be live at Idx.</p>


<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### SA {#a1d7dd983067f4fc39792f4ce3f865bbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SplitAnalysis&amp; llvm::SplitEditor::SA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### SpillMode {#aaeaa3364b5db5e356754263ca5bfd6a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComplementSpillMode llvm::SplitEditor::SpillMode = <a href="#ad485b75a455867847a669a3f942cbcb7a5cd5c6b9f5402366a8e7a28a55925720">SM_Partition</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The current spill mode, selected by <a href="#a907ca723e22613a6cfa9845d69f3eda6">reset()</a>.</p>

<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### TII {#a60516d327cd65cd7ee7242f504168833}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo&amp; llvm::SplitEditor::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### TRI {#a63b690fef0af1e15782f26a4f082458e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo&amp; llvm::SplitEditor::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### Values {#a5028b17a5a28f99ec554c098396c6bba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueMap llvm::SplitEditor::Values</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Values - keep track of the mapping from parent values to values in the new intervals.</p>


<p>Given a pair (RegIdx, ParentVNI-&gt;id), Values contains:</p>


<ol class="doxyList" type="1">
<li>No entry - the value is not mapped to Edit.get(RegIdx).</li>
<li>(Null, false) - the value is mapped to multiple values in Edit.get(RegIdx). Each value is represented by a minimal live range at its def. The full live range can be inferred exactly from the range of RegIdx in RegAssign.</li>
<li>(Null, true). As above, but the ranges in RegAssign are too large, and the live range must be recomputed using ::extend().</li>
<li>(VNI, false) The value is mapped to a single new value. The new value has no live ranges anywhere.</li>
</ol>

<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### VRAI {#a1f4cd81ad99f034ed597f9bf76a966b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VirtRegAuxInfo&amp; llvm::SplitEditor::VRAI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

</div>
</div>

### VRM {#a5eabce8fe69f487935fcd52aac109dfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VirtRegMap&amp; llvm::SplitEditor::VRM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-h">SplitKit.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
