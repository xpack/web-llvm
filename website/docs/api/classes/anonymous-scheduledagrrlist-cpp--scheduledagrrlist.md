---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-scheduledagrrlist-cpp-/scheduledagrrlist
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ScheduleDAGRRList` Class Reference

<p><a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/scheduledagrrlist">ScheduleDAGRRList</a> - The actual register reduction list scheduler implementation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes">ScheduleDAGSDNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes">ScheduleDAGSDNodes</a> - A <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> for scheduling SDNode-based DAGs. <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f5967dcf2d7cc1aa0eda6cffffd8abd">LRegsMapT</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 4 &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ddd224f4d981bb2a8ceb7d5c977f392">ScheduleDAGRRList</a> (MachineFunction &amp;mf, bool needlatency, SchedulingPriorityQueue *availqueue, CodeGenOptLevel OptLevel)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3de1dee78b74e3a6d925d75bbc824772">~ScheduleDAGRRList</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f958f8f55c3516c1b509f9c49cb0923">Schedule</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Schedule - Schedule the DAG using list scheduling. <a href="#a9f958f8f55c3516c1b509f9c49cb0923">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer">ScheduleHazardRecognizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1feca63a87c6625122fdf74658a30566">getHazardRec</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff54d81ed97148c13cffefb6fee1265c">IsReachable</a> (const SUnit *SU, const SUnit *TargetSU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsReachable - Checks if SU is reachable from TargetSU. <a href="#aff54d81ed97148c13cffefb6fee1265c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e7e4a676407494f9cf7187b88afde67">WillCreateCycle</a> (SUnit *SU, SUnit *TargetSU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>WillCreateCycle - Returns true if adding an edge from SU to TargetSU will create a cycle. <a href="#a3e7e4a676407494f9cf7187b88afde67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0b0b9b17a48e53bd335408d459656f9">AddPredQueued</a> (SUnit *SU, const SDep &amp;D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddPredQueued - Queues and update to add a predecessor edge to <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> SU. <a href="#ab0b0b9b17a48e53bd335408d459656f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81edbd7ea9536622badd16797bb7fb9c">AddPred</a> (SUnit *SU, const SDep &amp;D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddPred - adds a predecessor edge to <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> SU. <a href="#a81edbd7ea9536622badd16797bb7fb9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a3d1204e84d95a7bf978e1f3bc1debe">RemovePred</a> (SUnit *SU, const SDep &amp;D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RemovePred - removes a predecessor edge from <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> SU. <a href="#a3a3d1204e84d95a7bf978e1f3bc1debe">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbcc438409af7c1f5a197ad089e88709">isReady</a> (SUnit *SU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b657c21d37ea4e6670c169f62104444">ReleasePred</a> (SUnit *SU, const SDep *PredEdge)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReleasePred - Decrement the NumSuccsLeft count of a predecessor. <a href="#a6b657c21d37ea4e6670c169f62104444">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71f9ee19c4785d50729582ff915ec6e9">ReleasePredecessors</a> (SUnit *SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call ReleasePred for each predecessor, then update register live def/gen. <a href="#a71f9ee19c4785d50729582ff915ec6e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aed47f4562fe7753e80220ab25e0dea">ReleasePending</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check to see if any of the pending instructions are ready to issue. <a href="#a9aed47f4562fe7753e80220ab25e0dea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1621d67a87ac92efc1906b5b8167825">AdvanceToCycle</a> (unsigned NextCycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move the scheduler state forward by the specified number of Cycles. <a href="#ad1621d67a87ac92efc1906b5b8167825">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4c2af672726658ea403713e17491483">AdvancePastStalls</a> (SUnit *SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move the scheduler state forward until the specified node's dependents are ready and can be scheduled with no resource conflicts. <a href="#ae4c2af672726658ea403713e17491483">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbb8b96518c5b89e76b69fafd1852d74">EmitNode</a> (SUnit *SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> this <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> in the HazardRecognizer. <a href="#acbb8b96518c5b89e76b69fafd1852d74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8260a8d300001afdd3e5672e2ba656be">ScheduleNodeBottomUp</a> (SUnit *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ScheduleNodeBottomUp - Add the node to the schedule. <a href="#a8260a8d300001afdd3e5672e2ba656be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a819e28314b950f85d9d628ef945c61ad">CapturePred</a> (SDep *PredEdge)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CapturePred - This does the opposite of ReleasePred. <a href="#a819e28314b950f85d9d628ef945c61ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a439188be2ce20d954b5e1cca6af44c4f">UnscheduleNodeBottomUp</a> (SUnit *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>UnscheduleNodeBottomUp - Remove the node from the schedule, update its and its predecessor states to reflect the change. <a href="#a439188be2ce20d954b5e1cca6af44c4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acabc52a663e09454e24b0b0e9452aba7">RestoreHazardCheckerBottomUp</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>After backtracking, the hazard checker needs to be restored to a state corresponding the current cycle. <a href="#acabc52a663e09454e24b0b0e9452aba7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a888942912054fc4d14b1aa2accb381eb">BacktrackBottomUp</a> (SUnit *, SUnit *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BacktrackBottomUp - Backtrack scheduling to a previous cycle specified in BTCycle in order to schedule a specific node. <a href="#a888942912054fc4d14b1aa2accb381eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8bac1915315894107f9b1ef3cc78d14">TryUnfoldSU</a> (SUnit *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TryUnfold - Attempt to unfold. <a href="#ac8bac1915315894107f9b1ef3cc78d14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8470761d2a1affcfe4ade9a792eb8687">CopyAndMoveSuccessors</a> (SUnit *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CopyAndMoveSuccessors - Clone the specified node and move its scheduled successors to the newly created node. <a href="#a8470761d2a1affcfe4ade9a792eb8687">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea41cbab319e5c468817bcf8f4bcc5df">InsertCopiesAndMoveSuccs</a> (SUnit *, unsigned, const TargetRegisterClass *, const TargetRegisterClass *, SmallVectorImpl&lt; SUnit * &gt; &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>InsertCopiesAndMoveSuccs - Insert register copies and move all scheduled successors of the given <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> to the last copy. <a href="#aea41cbab319e5c468817bcf8f4bcc5df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7290c1b4f8e316ccc3229d8edd1248c">DelayForLiveRegsBottomUp</a> (SUnit *, SmallVectorImpl&lt; unsigned &gt; &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DelayForLiveRegsBottomUp - Returns true if it is necessary to delay scheduling of the given node to satisfy live physical register dependencies. <a href="#ad7290c1b4f8e316ccc3229d8edd1248c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae774754e344e8d0e9f88fc3afc539282">releaseInterferences</a> (unsigned Reg=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a757fc93ce8f64d83757b560ba4e19be5">PickNodeToScheduleBottomUp</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a node that can be scheduled in this cycle. <a href="#a757fc93ce8f64d83757b560ba4e19be5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac00a500ceca90de69f13162113dcf316">ListScheduleBottomUp</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ListScheduleBottomUp - The main loop of list scheduling for bottom-up schedulers. <a href="#ac00a500ceca90de69f13162113dcf316">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0daae9d4a5734cabcc527cb9746603b">CreateNewSUnit</a> (SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CreateNewSUnit - Creates a new <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> and returns a pointer to it. <a href="#ac0daae9d4a5734cabcc527cb9746603b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c21a0982a87fb677decb94a2f19e8f6">CreateClone</a> (SUnit *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CreateClone - Creates a new <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> from an existing one. <a href="#a9c21a0982a87fb677decb94a2f19e8f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae26de31ad5fc73770ed9112c0871bc14">forceUnitLatencies</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>forceUnitLatencies - Register-pressure-reducing scheduling doesn't need actual latency information but the hybrid scheduler does. <a href="#ae26de31ad5fc73770ed9112c0871bc14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf12f22003b98e03f8a1aa2c86e4b4b2">NeedLatency</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NeedLatency - True if the scheduler will make use of latency information. <a href="#adf12f22003b98e03f8a1aa2c86e4b4b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulingpriorityqueue">SchedulingPriorityQueue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3716f1cf6af7da4a34fb0ad31ab84389">AvailableQueue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AvailableQueue - The priority queue to use for the available SUnits. <a href="#a3716f1cf6af7da4a34fb0ad31ab84389">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a781cf002d1e7b1cde375eb335c48089a">PendingQueue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PendingQueue - This contains all of the instructions whose operands have been issued, but their results are not ready yet (due to the latency of the operation). <a href="#a781cf002d1e7b1cde375eb335c48089a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer">ScheduleHazardRecognizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a169e0b3dc3b79970fd63f7eaf26cbc77">HazardRec</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HazardRec - The hazard recognizer to use. <a href="#a169e0b3dc3b79970fd63f7eaf26cbc77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b785d998cfbef3501bb6d43a3f50493">CurCycle</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CurCycle - The current scheduler state corresponds to this cycle. <a href="#a9b785d998cfbef3501bb6d43a3f50493">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01a0103daf695260127161f8866b69e5">MinAvailableCycle</a> = ~0u</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MinAvailableCycle - <a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a> of the soonest available instruction. <a href="#a01a0103daf695260127161f8866b69e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09bead3d68b728cd8e7ba7d734ead551">IssueCount</a> = 0u</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IssueCount - Count instructions issued in this cycle Currently valid only for bottom-up scheduling. <a href="#a09bead3d68b728cd8e7ba7d734ead551">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d268a56ccd3f8dcec37f15b4bfc8d9f">NumLiveRegs</a> = 0u</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LiveRegDefs - A set of physical registers and their definition that are "live". <a href="#a1d268a56ccd3f8dcec37f15b4bfc8d9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *[]&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2ebda7223ea0bbcd799e7982287e359">LiveRegDefs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *[]&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3695a27e0f679c21a8a8f89b3d8b912c">LiveRegGens</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbe7236a16ae6d79968bbd79a73fd3ac">Interferences</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">LRegsMapT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba5cb5c79fc18dd73c716642b2542a01">LRegsMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort">ScheduleDAGTopologicalSort</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7688b41495dc5ee9297682970dd36382">Topo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Topo - A topological ordering for SUnits which permits fast IsReachable and similar queries. <a href="#a7688b41495dc5ee9297682970dd36382">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a758b6694bd168ae4d50f4aee109efd97">CallSeqEndForStart</a></td>
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

<p><a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/scheduledagrrlist">ScheduleDAGRRList</a> - The actual register reduction list scheduler implementation.</p>


<p>This supports both top-down and bottom-up scheduling.</p>


<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### LRegsMapT {#a2f5967dcf2d7cc1aa0eda6cffffd8abd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::LRegsMapT =  DenseMap&lt;SUnit *, SmallVector&lt;unsigned, 4&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ScheduleDAGRRList() {#a2ddd224f4d981bb2a8ceb7d5c977f392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::ScheduleDAGRRList (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; mf, bool needlatency, <a href="/web-llvm/docs/api/classes/llvm/schedulingpriorityqueue">SchedulingPriorityQueue</a> * availqueue, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OptLevel)</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a10beddeded3621d5cca48dae7043f774">DisableSchedCycles</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ad73652eab6e03e092e32bde82040c8c7">llvm::ScheduleDAGSDNodes::ScheduleDAGSDNodes</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a145f77473f4a050a8e1bf0dd7e2a34fa">llvm::createBURRListDAGScheduler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a24fb0e850aa86095101c2cd7110aa32b">llvm::createHybridListDAGScheduler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac2c88a3ebea5ca10491d30d01274c96d">llvm::createILPListDAGScheduler</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa743cb95ae4e26544366fb66fa23f4dc">llvm::createSourceListDAGScheduler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ScheduleDAGRRList() {#a3de1dee78b74e3a6d925d75bbc824772}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::~ScheduleDAGRRList ()</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AddPred() {#a81edbd7ea9536622badd16797bb7fb9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::AddPred (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; D)</td>
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

<p>AddPred - adds a predecessor edge to <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> SU.</p>


<p>This returns true if this is a new predecessor. Updates the topological ordering if required.</p>


<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#af92bf49ed4846e026e68c380d74d7b15">llvm::SUnit::addPred</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>.</p>

</div>
</div>

### AddPredQueued() {#ab0b0b9b17a48e53bd335408d459656f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::AddPredQueued (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; D)</td>
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

<p>AddPredQueued - Queues and update to add a predecessor edge to <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> SU.</p>


<p>This returns true if this is a new predecessor. Does <em>NOT</em> update the topological ordering! It just queues an update.</p>


<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#af92bf49ed4846e026e68c380d74d7b15">llvm::SUnit::addPred</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>.</p>

</div>
</div>

### getHazardRec() {#a1feca63a87c6625122fdf74658a30566}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer * anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::getHazardRec ()</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### IsReachable() {#aff54d81ed97148c13cffefb6fee1265c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::IsReachable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * TargetSU)</td>
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

<p>IsReachable - Checks if SU is reachable from TargetSU.</p>

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### RemovePred() {#a3a3d1204e84d95a7bf978e1f3bc1debe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::RemovePred (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; D)</td>
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

<p>RemovePred - removes a predecessor edge from <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> SU.</p>


<p>This returns true if an edge was removed. Updates the topological ordering if required.</p>


<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a6d3233165db1e6be5c44060cd4a95461">llvm::SUnit::removePred</a>.</p>

</div>
</div>

### Schedule() {#a9f958f8f55c3516c1b509f9c49cb0923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGRRList::Schedule ()</td>
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

<p>Schedule - Schedule the DAG using list scheduling.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a9f718397926caadcb301ca1e00aaf68c">llvm::ScheduleDAGSDNodes::BB</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#aa88c65a5abb5774125c8d66a48d07adf">llvm::ScheduleDAGSDNodes::BuildSchedGraph</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a10beddeded3621d5cca48dae7043f774">DisableSchedCycles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a03503773241005f01b090b9862aad304">llvm::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ad8f08e38b6a51a322e450fc0cb6351f9">llvm::ScheduleDAGSDNodes::dumpSchedule</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a>.</p>

</div>
</div>

### WillCreateCycle() {#a3e7e4a676407494f9cf7187b88afde67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::WillCreateCycle (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * TargetSU)</td>
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

<p>WillCreateCycle - Returns true if adding an edge from SU to TargetSU will create a cycle.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AdvancePastStalls() {#ae4c2af672726658ea403713e17491483}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGRRList::AdvancePastStalls (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move the scheduler state forward until the specified node's dependents are ready and can be scheduled with no resource conflicts.</p>

<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### AdvanceToCycle() {#ad1621d67a87ac92efc1906b5b8167825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGRRList::AdvanceToCycle (unsigned NextCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move the scheduler state forward by the specified number of Cycles.</p>

<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### BacktrackBottomUp() {#a888942912054fc4d14b1aa2accb381eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGRRList::BacktrackBottomUp (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * BtSU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>BacktrackBottomUp - Backtrack scheduling to a previous cycle specified in BTCycle in order to schedule a specific node.</p>

<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### CapturePred() {#a819e28314b950f85d9d628ef945c61ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGRRList::CapturePred (<a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> * PredEdge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CapturePred - This does the opposite of ReleasePred.</p>


<p>Since SU is being unscheduled, increase the succ left count of its predecessors. Remove them from AvailableQueue if necessary.</p>


<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### CopyAndMoveSuccessors() {#a8470761d2a1affcfe4ade9a792eb8687}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * ScheduleDAGRRList::CopyAndMoveSuccessors (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CopyAndMoveSuccessors - Clone the specified node and move its scheduled successors to the newly created node.</p>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### CreateClone() {#a9c21a0982a87fb677decb94a2f19e8f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::CreateClone (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * N)</td>
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

<p>CreateClone - Creates a new <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> from an existing one.</p>

<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### CreateNewSUnit() {#ac0daae9d4a5734cabcc527cb9746603b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::CreateNewSUnit (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>CreateNewSUnit - Creates a new <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> and returns a pointer to it.</p>

<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### DelayForLiveRegsBottomUp() {#ad7290c1b4f8e316ccc3229d8edd1248c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScheduleDAGRRList::DelayForLiveRegsBottomUp (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; LRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DelayForLiveRegsBottomUp - Returns true if it is necessary to delay scheduling of the given node to satisfy live physical register dependencies.</p>


<p>If the specific node is the last one that's available to schedule, do whatever is necessary (i.e. backtracking or cloning) to make it possible.</p>


<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### EmitNode() {#acbb8b96518c5b89e76b69fafd1852d74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGRRList::EmitNode (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> this <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> in the HazardRecognizer.</p>


<p>Does not update CurCycle.</p>


<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### forceUnitLatencies() {#ae26de31ad5fc73770ed9112c0871bc14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::forceUnitLatencies ()</td>
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

<p>forceUnitLatencies - Register-pressure-reducing scheduling doesn't need actual latency information but the hybrid scheduler does.</p>

<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### InsertCopiesAndMoveSuccs() {#aea41cbab319e5c468817bcf8f4bcc5df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGRRList::InsertCopiesAndMoveSuccs (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, unsigned Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * DestRC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * SrcRC, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt; &amp; Copies)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>InsertCopiesAndMoveSuccs - Insert register copies and move all scheduled successors of the given <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> to the last copy.</p>

<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### isReady() {#abbcc438409af7c1f5a197ad089e88709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::isReady (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### ListScheduleBottomUp() {#ac00a500ceca90de69f13162113dcf316}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGRRList::ListScheduleBottomUp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ListScheduleBottomUp - The main loop of list scheduling for bottom-up schedulers.</p>

<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### PickNodeToScheduleBottomUp() {#a757fc93ce8f64d83757b560ba4e19be5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * ScheduleDAGRRList::PickNodeToScheduleBottomUp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a node that can be scheduled in this cycle.</p>


<p>Requirements: (1) Ready: latency has been satisfied (2) No Hazards: resources are available (3) No Interferences: may unschedule to break register interferences.</p>


<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### releaseInterferences() {#ae774754e344e8d0e9f88fc3afc539282}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGRRList::releaseInterferences (unsigned Reg=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### ReleasePending() {#a9aed47f4562fe7753e80220ab25e0dea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGRRList::ReleasePending ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check to see if any of the pending instructions are ready to issue.</p>


<p>If so, add them to the available queue.</p>


<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### ReleasePred() {#a6b657c21d37ea4e6670c169f62104444}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGRRList::ReleasePred (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> * PredEdge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ReleasePred - Decrement the NumSuccsLeft count of a predecessor.</p>


<p>Add it to the AvailableQueue if the count reaches zero. Also update its cycle bound.</p>


<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### ReleasePredecessors() {#a71f9ee19c4785d50729582ff915ec6e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGRRList::ReleasePredecessors (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Call ReleasePred for each predecessor, then update register live def/gen.</p>


<p>Always update LiveRegDefs for a register dependence even if the current SU also defines the register. This effectively create one large live range across a sequence of two-address node. This is important because the entire chain must be scheduled together. Example:</p>


<p>flags = (3) add flags = (2) addc flags flags = (1) addc flags</p>


<p>results in</p>


<p>LiveRegDefs[flags] = 3 LiveRegGens[flags] = 1</p>


<p>If (2) addc is unscheduled, then (1) addc must also be unscheduled to avoid interference on flags.</p>


<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### RestoreHazardCheckerBottomUp() {#acabc52a663e09454e24b0b0e9452aba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGRRList::RestoreHazardCheckerBottomUp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>After backtracking, the hazard checker needs to be restored to a state corresponding the current cycle.</p>

<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### ScheduleNodeBottomUp() {#a8260a8d300001afdd3e5672e2ba656be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGRRList::ScheduleNodeBottomUp (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ScheduleNodeBottomUp - Add the node to the schedule.</p>


<p>Decrement the pending count of its predecessors. If a predecessor pending count is zero, add it to the Available queue.</p>


<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### TryUnfoldSU() {#ac8bac1915315894107f9b1ef3cc78d14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit * ScheduleDAGRRList::TryUnfoldSU (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>TryUnfold - Attempt to unfold.</p>

<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### UnscheduleNodeBottomUp() {#a439188be2ce20d954b5e1cca6af44c4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGRRList::UnscheduleNodeBottomUp (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>UnscheduleNodeBottomUp - Remove the node from the schedule, update its and its predecessor states to reflect the change.</p>

<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AvailableQueue {#a3716f1cf6af7da4a34fb0ad31ab84389}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedulingPriorityQueue* anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::AvailableQueue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AvailableQueue - The priority queue to use for the available SUnits.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### CallSeqEndForStart {#a758b6694bd168ae4d50f4aee109efd97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;SUnit *, SUnit *, 16&gt; anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::CallSeqEndForStart</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### CurCycle {#a9b785d998cfbef3501bb6d43a3f50493}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::CurCycle = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CurCycle - The current scheduler state corresponds to this cycle.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### HazardRec {#a169e0b3dc3b79970fd63f7eaf26cbc77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer* anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::HazardRec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HazardRec - The hazard recognizer to use.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### Interferences {#afbe7236a16ae6d79968bbd79a73fd3ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SUnit*, 4&gt; anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::Interferences</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### IssueCount {#a09bead3d68b728cd8e7ba7d734ead551}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::IssueCount = 0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IssueCount - Count instructions issued in this cycle Currently valid only for bottom-up scheduling.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### LiveRegDefs {#ae2ebda7223ea0bbcd799e7982287e359}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SUnit*[]&gt; anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::LiveRegDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### LiveRegGens {#a3695a27e0f679c21a8a8f89b3d8b912c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SUnit*[]&gt; anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::LiveRegGens</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### LRegsMap {#aba5cb5c79fc18dd73c716642b2542a01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LRegsMapT anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::LRegsMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### MinAvailableCycle {#a01a0103daf695260127161f8866b69e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::MinAvailableCycle = ~0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MinAvailableCycle - <a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a> of the soonest available instruction.</p>

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### NeedLatency {#adf12f22003b98e03f8a1aa2c86e4b4b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::NeedLatency</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NeedLatency - True if the scheduler will make use of latency information.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### NumLiveRegs {#a1d268a56ccd3f8dcec37f15b4bfc8d9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::NumLiveRegs = 0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LiveRegDefs - A set of physical registers and their definition that are "live".</p>


<p>These nodes must be scheduled before any other nodes that modifies the registers can be scheduled.</p>


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### PendingQueue {#a781cf002d1e7b1cde375eb335c48089a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SUnit *&gt; anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::PendingQueue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PendingQueue - This contains all of the instructions whose operands have been issued, but their results are not ready yet (due to the latency of the operation).</p>


<p>Once the operands becomes available, the instruction is added to the AvailableQueue.</p>


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

### Topo {#a7688b41495dc5ee9297682970dd36382}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGTopologicalSort anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::Topo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Topo - A topological ordering for SUnits which permits fast IsReachable and similar queries.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
