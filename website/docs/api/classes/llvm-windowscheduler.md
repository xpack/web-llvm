---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/windowscheduler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `WindowScheduler` Class Reference

<p>The main class in the implementation of the target independent window scheduler. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::WindowScheduler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">llvm/CodeGen/WindowScheduler.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9bebcba4bcb359f1223392d9ff1e035">WindowScheduler</a> (MachineSchedContext *C, MachineLoop &amp;ML)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fd87a1ebb61604c4f63a0d7fe299931">~WindowScheduler</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40308f28207edf04d70fd884039d0b81">run</a> ()</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e34e8c324a6219e5840b893ba7f2de8">createMachineScheduler</a> (bool OnlyBuildGraph=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Two types of ScheduleDAGs are needed, one for creating dependency graphs only, and the other for list scheduling as determined by the target. <a href="#a0e34e8c324a6219e5840b893ba7f2de8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af02c395926a140c8121e0e7d16e1dfe1">initialize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initializes the algorithm and determines if it can be executed. <a href="#af02c395926a140c8121e0e7d16e1dfe1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30d5756e44d33e166ca0506802e578ef">preProcess</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add some related processing before running window scheduling. <a href="#a30d5756e44d33e166ca0506802e578ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49b94106b0a74702c0cf8337eb8a6adb">postProcess</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add some related processing after running window scheduling. <a href="#a49b94106b0a74702c0cf8337eb8a6adb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7519a939200f107386d3267bcd00c1c6">backupMBB</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Back up the MIs in the original MBB and remove them from MBB. <a href="#a7519a939200f107386d3267bcd00c1c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af94dd7df8db8b546ca9c8d29c0b31a95">restoreMBB</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase the MIs in current MBB and restore the original MIs. <a href="#af94dd7df8db8b546ca9c8d29c0b31a95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9105d71f7a1c253dcb1afe7d120237e">generateTripleMBB</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make three copies of the original MBB to generate a new TripleMBB. <a href="#ad9105d71f7a1c253dcb1afe7d120237e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a425a27a184e7f9e226b7ba72870b19fe">restoreTripleMBB</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Restore the order of MIs in TripleMBB after each list scheduling. <a href="#a425a27a184e7f9e226b7ba72870b19fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af78f1d6e142343589981887d2a200d84">getSearchIndexes</a> (unsigned SearchNum, unsigned SearchRatio)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Give the folding position in the window algorithm, where different heuristics can be used. <a href="#af78f1d6e142343589981887d2a200d84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5722fabe6420b0f87a3eb1160979e5f7">calculateMaxCycle</a> (ScheduleDAGInstrs &amp;DAG, unsigned Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate MIs execution cycle after list scheduling. <a href="#a5722fabe6420b0f87a3eb1160979e5f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae803ffd4decdd48471010ae2cb76d20d">calculateStallCycle</a> (unsigned Offset, int MaxCycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the stall cycle between two trips after list scheduling. <a href="#ae803ffd4decdd48471010ae2cb76d20d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8c6acf329b4804c26c294903ae015de">analyseII</a> (ScheduleDAGInstrs &amp;DAG, unsigned Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyzes the II value after each list scheduling. <a href="#ac8c6acf329b4804c26c294903ae015de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab595a02e4a2cbfc15add4253f222d3f1">schedulePhi</a> (int Offset, unsigned &amp;II)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Phis are scheduled separately after each list scheduling. <a href="#ab595a02e4a2cbfc15add4253f222d3f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8be84df2dea9e89e29f856c0456ae0c3">getIssueOrder</a> (unsigned Offset, unsigned II)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the final issue order of all scheduled MIs including phis. <a href="#a8be84df2dea9e89e29f856c0456ae0c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec0f8a381dfe9925ec5cef351d20edb1">updateScheduleResult</a> (unsigned Offset, unsigned II)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the scheduling result after each list scheduling. <a href="#aec0f8a381dfe9925ec5cef351d20edb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adebaba35161e4995df328d169355e3a8">isScheduleValid</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the final result of window scheduling is valid. <a href="#adebaba35161e4995df328d169355e3a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b546fe78d24f8c9f7d440957a37a801">expand</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Using the scheduling infrastructure to expand the results of window scheduling. <a href="#a8b546fe78d24f8c9f7d440957a37a801">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94fa9430a250a99da03c75e55f605349">updateLiveIntervals</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the live intervals for all registers used within MBB. <a href="#a94fa9430a250a99da03c75e55f605349">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b0679e70ea74a5f5f3a7fe8060a86e6">getEstimatedII</a> (ScheduleDAGInstrs &amp;DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Estimate a II value at which all MIs will be scheduled successfully. <a href="#a8b0679e70ea74a5f5f3a7fe8060a86e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbdaac6e396c3d1dae6cee75cb2fee1f">getScheduleRange</a> (unsigned Offset, unsigned Num)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the iterator range of MIs in the scheduling window. <a href="#adbdaac6e396c3d1dae6cee75cb2fee1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0494bc6a8f8231640ccc225d7a86847">getOriCycle</a> (MachineInstr *NewMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the issue cycle of the new MI based on the cycle of the original MI. <a href="#ad0494bc6a8f8231640ccc225d7a86847">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09475eec526bdf8626b3a02adad1fa28">getOriMI</a> (MachineInstr *NewMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the original MI from which the new MI is cloned. <a href="#a09475eec526bdf8626b3a02adad1fa28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f7e5d546027dc8ca8bb67c8b3f1b0cc">getOriStage</a> (MachineInstr *OriMI, unsigned Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the scheduling stage, where the stage of the new MI is identical to the original MI. <a href="#a8f7e5d546027dc8ca8bb67c8b3f1b0cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d55f2013c2e95d424a903ff919e8fa5">getAntiRegister</a> (MachineInstr *Phi)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the register in phi which is generated from the current MBB. <a href="#a8d55f2013c2e95d424a903ff919e8fa5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a2b84c75a614343c26e3764aab963a9">Context</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf97c807c56e072eec16eadaa1dc74e2">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a690d8e3b14e796b870f58d3d8f7e2a77">MBB</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c23e1051609c44baa4ba0e78a432139">Loop</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99f029742c003f8a0e5db1538d07988e">Subtarget</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8a9c20c5c819e59cd32906f691fbc2c">TII</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9301a41a35d6aa7367def5ea6fd78db7">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a588faf8e1f126dc258d357b045595407">MRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabfa4ddad621932351b720f8162030e8">TripleDAG</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>To innovatively identify the dependencies between MIs across two trips, we construct a DAG for a new MBB, which is created by copying the original MBB three times. <a href="#aabfa4ddad621932351b720f8162030e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed4001b80ceaef38d700764e9934e054">OriMIs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OriMIs keeps the MIs removed from the original MBB. <a href="#aed4001b80ceaef38d700764e9934e054">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbe266c442e9313e05ebffb703c2bd36">TriMIs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TriMIs keeps the MIs of TripleMBB, which is used to restore TripleMBB. <a href="#afbe266c442e9313e05ebffb703c2bd36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e8c400b0b728b6ec230f0b487c6af44">TriToOri</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TriToOri keeps the mappings between the MI clones in TripleMBB and their original MI. <a href="#a7e8c400b0b728b6ec230f0b487c6af44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54d52175d63bed9f3b0bd9f6317e023e">OriToCycle</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OriToCycle keeps the mappings between the original MI and its issue cycle. <a href="#a54d52175d63bed9f3b0bd9f6317e023e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, int, int, int &gt;, 256 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3f7938e6818ec29f907451091b7fdad">SchedResult</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SchedResult keeps the result of each list scheduling, and the format of the tuple is &lt;MI pointer, <a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a>, Stage, Order <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>&gt;. <a href="#af3f7938e6818ec29f907451091b7fdad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eade05b9c131318e2b1b8141cf3ef53">SchedPhiNum</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SchedPhiNum records the number of phi in the original MBB, and the scheduling starts with MI after phis. <a href="#a1eade05b9c131318e2b1b8141cf3ef53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4542ab1cab20715a2bc58b001a42e4b">SchedInstrNum</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SchedInstrNum records the MIs involved in scheduling in the original MBB, excluding debug instructions. <a href="#ad4542ab1cab20715a2bc58b001a42e4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fba85773a0cf15056c4263ac69dbc80">BestII</a> = UINT_MAX</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BestII and BestOffset record the characteristics of the best scheduling result and are used together with SchedResult as the final window scheduling result. <a href="#a6fba85773a0cf15056c4263ac69dbc80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67690feca344d36167d2f65f71653f4e">BestOffset</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaffbb1654d149fc4b75f0793c03cd398">BaseII</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BaseII is the II obtained when the window offset is SchedPhiNum. <a href="#aaffbb1654d149fc4b75f0793c03cd398">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The main class in the implementation of the target independent window scheduler.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WindowScheduler() {#af9bebcba4bcb359f1223392d9ff1e035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WindowScheduler::WindowScheduler (<a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C, <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> &amp; ML)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a3a2b84c75a614343c26e3764aab963a9">Context</a>, <a href="#a0e34e8c324a6219e5840b893ba7f2de8">createMachineScheduler</a>, <a href="#a7c23e1051609c44baa4ba0e78a432139">Loop</a>, <a href="#a690d8e3b14e796b870f58d3d8f7e2a77">MBB</a>, <a href="#abf97c807c56e072eec16eadaa1dc74e2">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3ad01fd9b01e9dde8bd3dc247afbfb7218">ML</a>, <a href="#a588faf8e1f126dc258d357b045595407">MRI</a>, <a href="#a99f029742c003f8a0e5db1538d07988e">Subtarget</a>, <a href="#ad8a9c20c5c819e59cd32906f691fbc2c">TII</a>, <a href="#a9301a41a35d6aa7367def5ea6fd78db7">TRI</a> and <a href="#aabfa4ddad621932351b720f8162030e8">TripleDAG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~WindowScheduler() {#a7fd87a1ebb61604c4f63a0d7fe299931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::WindowScheduler::~WindowScheduler ()</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a40308f28207edf04d70fd884039d0b81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WindowScheduler::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="#ac8c6acf329b4804c26c294903ae015de">analyseII</a>, <a href="#a6fba85773a0cf15056c4263ac69dbc80">BestII</a>, <a href="#a67690feca344d36167d2f65f71653f4e">BestOffset</a>, <a href="#a0e34e8c324a6219e5840b893ba7f2de8">createMachineScheduler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a8b546fe78d24f8c9f7d440957a37a801">expand</a>, <a href="#adbdaac6e396c3d1dae6cee75cb2fee1f">getScheduleRange</a>, <a href="#af78f1d6e142343589981887d2a200d84">getSearchIndexes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#af02c395926a140c8121e0e7d16e1dfe1">initialize</a>, <a href="#adebaba35161e4995df328d169355e3a8">isScheduleValid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a690d8e3b14e796b870f58d3d8f7e2a77">MBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a54d52175d63bed9f3b0bd9f6317e023e">OriToCycle</a>, <a href="#a49b94106b0a74702c0cf8337eb8a6adb">postProcess</a>, <a href="#a30d5756e44d33e166ca0506802e578ef">preProcess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="#a425a27a184e7f9e226b7ba72870b19fe">restoreTripleMBB</a>, <a href="#ad4542ab1cab20715a2bc58b001a42e4b">SchedInstrNum</a>, <a href="#a1eade05b9c131318e2b1b8141cf3ef53">SchedPhiNum</a>, <a href="#ab595a02e4a2cbfc15add4253f222d3f1">schedulePhi</a>, <a href="#aec0f8a381dfe9925ec5cef351d20edb1">updateScheduleResult</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp/#aff75f05d43156623f0a46d6599927f6b">WindowIILimit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### analyseII() {#ac8c6acf329b4804c26c294903ae015de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned WindowScheduler::analyseII (<a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> &amp; DAG, unsigned Offset)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyzes the II value after each list scheduling.</p>

<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="#a5722fabe6420b0f87a3eb1160979e5f7">calculateMaxCycle</a>, <a href="#ae803ffd4decdd48471010ae2cb76d20d">calculateStallCycle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp/#aff75f05d43156623f0a46d6599927f6b">WindowIILimit</a>.</p>


<p>Referenced by <a href="#a40308f28207edf04d70fd884039d0b81">run</a>.</p>

</div>
</div>

### backupMBB() {#a7519a939200f107386d3267bcd00c1c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WindowScheduler::backupMBB ()</td>
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

<p>Back up the MIs in the original MBB and remove them from MBB.</p>

<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="#a3a2b84c75a614343c26e3764aab963a9">Context</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="#a690d8e3b14e796b870f58d3d8f7e2a77">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#aed4001b80ceaef38d700764e9934e054">OriMIs</a>.</p>


<p>Referenced by <a href="#a30d5756e44d33e166ca0506802e578ef">preProcess</a>.</p>

</div>
</div>

### calculateMaxCycle() {#a5722fabe6420b0f87a3eb1160979e5f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int WindowScheduler::calculateMaxCycle (<a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> &amp; DAG, unsigned Offset)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate MIs execution cycle after list scheduling.</p>

<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a8b0679e70ea74a5f5f3a7fe8060a86e6">getEstimatedII</a>, <a href="#ad0494bc6a8f8231640ccc225d7a86847">getOriCycle</a>, <a href="#a09475eec526bdf8626b3a02adad1fa28">getOriMI</a>, <a href="#a8f7e5d546027dc8ca8bb67c8b3f1b0cc">getOriStage</a>, <a href="#adbdaac6e396c3d1dae6cee75cb2fee1f">getScheduleRange</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab75cd37a7a0319d5a4c77189cca106ec">llvm::ScheduleDAGInstrs::getSUnit</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a54d52175d63bed9f3b0bd9f6317e023e">OriToCycle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="#ad4542ab1cab20715a2bc58b001a42e4b">SchedInstrNum</a>, <a href="#a99f029742c003f8a0e5db1538d07988e">Subtarget</a>, <a href="#ad8a9c20c5c819e59cd32906f691fbc2c">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp/#aff75f05d43156623f0a46d6599927f6b">WindowIILimit</a>.</p>


<p>Referenced by <a href="#ac8c6acf329b4804c26c294903ae015de">analyseII</a>.</p>

</div>
</div>

### calculateStallCycle() {#ae803ffd4decdd48471010ae2cb76d20d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int WindowScheduler::calculateStallCycle (unsigned Offset, int MaxCycle)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate the stall cycle between two trips after list scheduling.</p>

<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ad0494bc6a8f8231640ccc225d7a86847">getOriCycle</a>, <a href="#adbdaac6e396c3d1dae6cee75cb2fee1f">getScheduleRange</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="#ad4542ab1cab20715a2bc58b001a42e4b">SchedInstrNum</a>, <a href="#aabfa4ddad621932351b720f8162030e8">TripleDAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp/#aff75f05d43156623f0a46d6599927f6b">WindowIILimit</a>.</p>


<p>Referenced by <a href="#ac8c6acf329b4804c26c294903ae015de">analyseII</a>.</p>

</div>
</div>

### createMachineScheduler() {#a0e34e8c324a6219e5840b893ba7f2de8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGInstrs * WindowScheduler::createMachineScheduler (bool OnlyBuildGraph=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Two types of ScheduleDAGs are needed, one for creating dependency graphs only, and the other for list scheduling as determined by the target.</p>

<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>Reference <a href="#a3a2b84c75a614343c26e3764aab963a9">Context</a>.</p>


<p>Referenced by <a href="#a40308f28207edf04d70fd884039d0b81">run</a> and <a href="#af9bebcba4bcb359f1223392d9ff1e035">WindowScheduler</a>.</p>

</div>
</div>

### expand() {#a8b546fe78d24f8c9f7d440957a37a801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WindowScheduler::expand ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Using the scheduling infrastructure to expand the results of window scheduling.</p>


<p>It is usually necessary to add prologue and epilogue MBBs.</p>


<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/moduloscheduleexpander/#a1e6babf78504a9699ed219fab9ce3460">llvm::ModuloScheduleExpander::cleanup</a>, <a href="#a3a2b84c75a614343c26e3764aab963a9">Context</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/moduloscheduleexpander/#a772c336d26015c2e6fb5efc62cf166be">llvm::ModuloScheduleExpander::expand</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a7c23e1051609c44baa4ba0e78a432139">Loop</a>, <a href="#abf97c807c56e072eec16eadaa1dc74e2">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#af3f7938e6818ec29f907451091b7fdad">SchedResult</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>.</p>


<p>Referenced by <a href="#a40308f28207edf04d70fd884039d0b81">run</a>.</p>

</div>
</div>

### generateTripleMBB() {#ad9105d71f7a1c253dcb1afe7d120237e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WindowScheduler::generateTripleMBB ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make three copies of the original MBB to generate a new TripleMBB.</p>

<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8d55f2013c2e95d424a903ff919e8fa5">getAntiRegister</a>, <a href="#a690d8e3b14e796b870f58d3d8f7e2a77">MBB</a>, <a href="#abf97c807c56e072eec16eadaa1dc74e2">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a588faf8e1f126dc258d357b045595407">MRI</a>, <a href="#aed4001b80ceaef38d700764e9934e054">OriMIs</a>, <a href="#a9301a41a35d6aa7367def5ea6fd78db7">TRI</a>, <a href="#afbe266c442e9313e05ebffb703c2bd36">TriMIs</a>, <a href="#a7e8c400b0b728b6ec230f0b487c6af44">TriToOri</a> and <a href="#a94fa9430a250a99da03c75e55f605349">updateLiveIntervals</a>.</p>


<p>Referenced by <a href="#a30d5756e44d33e166ca0506802e578ef">preProcess</a>.</p>

</div>
</div>

### getAntiRegister() {#a8d55f2013c2e95d424a903ff919e8fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register WindowScheduler::getAntiRegister (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * Phi)</td>
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

<p>Gets the register in phi which is generated from the current MBB.</p>

<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 699 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a690d8e3b14e796b870f58d3d8f7e2a77">MBB</a>.</p>


<p>Referenced by <a href="#ad9105d71f7a1c253dcb1afe7d120237e">generateTripleMBB</a> and <a href="#ab595a02e4a2cbfc15add4253f222d3f1">schedulePhi</a>.</p>

</div>
</div>

### getEstimatedII() {#a8b0679e70ea74a5f5f3a7fe8060a86e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int WindowScheduler::getEstimatedII (<a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> &amp; DAG)</td>
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

<p>Estimate a II value at which all MIs will be scheduled successfully.</p>

<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>.</p>


<p>Referenced by <a href="#a5722fabe6420b0f87a3eb1160979e5f7">calculateMaxCycle</a>.</p>

</div>
</div>

### getIssueOrder() {#a8be84df2dea9e89e29f856c0456ae0c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; MachineInstr *, int &gt; WindowScheduler::getIssueOrder (unsigned Offset, unsigned II)</td>
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

<p>Get the final issue order of all scheduled MIs including phis.</p>

<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a53408c95a7bfb5443b43fb2134c3eb23">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::count</a>, <a href="#ad0494bc6a8f8231640ccc225d7a86847">getOriCycle</a>, <a href="#a09475eec526bdf8626b3a02adad1fa28">getOriMI</a>, <a href="#adbdaac6e396c3d1dae6cee75cb2fee1f">getScheduleRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#a690d8e3b14e796b870f58d3d8f7e2a77">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="#ad4542ab1cab20715a2bc58b001a42e4b">SchedInstrNum</a>.</p>


<p>Referenced by <a href="#aec0f8a381dfe9925ec5cef351d20edb1">updateScheduleResult</a>.</p>

</div>
</div>

### getOriCycle() {#ad0494bc6a8f8231640ccc225d7a86847}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int WindowScheduler::getOriCycle (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * NewMI)</td>
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

<p>Get the issue cycle of the new MI based on the cycle of the original MI.</p>

<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 668 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a54d52175d63bed9f3b0bd9f6317e023e">OriToCycle</a> and <a href="#a7e8c400b0b728b6ec230f0b487c6af44">TriToOri</a>.</p>


<p>Referenced by <a href="#a5722fabe6420b0f87a3eb1160979e5f7">calculateMaxCycle</a>, <a href="#ae803ffd4decdd48471010ae2cb76d20d">calculateStallCycle</a>, <a href="#a8be84df2dea9e89e29f856c0456ae0c3">getIssueOrder</a> and <a href="#ab595a02e4a2cbfc15add4253f222d3f1">schedulePhi</a>.</p>

</div>
</div>

### getOriMI() {#a09475eec526bdf8626b3a02adad1fa28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * WindowScheduler::getOriMI (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * NewMI)</td>
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

<p>Get the original MI from which the new MI is cloned.</p>

<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7e8c400b0b728b6ec230f0b487c6af44">TriToOri</a>.</p>


<p>Referenced by <a href="#a5722fabe6420b0f87a3eb1160979e5f7">calculateMaxCycle</a>, <a href="#a8be84df2dea9e89e29f856c0456ae0c3">getIssueOrder</a> and <a href="#ab595a02e4a2cbfc15add4253f222d3f1">schedulePhi</a>.</p>

</div>
</div>

### getOriStage() {#a8f7e5d546027dc8ca8bb67c8b3f1b0cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned WindowScheduler::getOriStage (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * OriMI, unsigned Offset)</td>
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

<p>Get the scheduling stage, where the stage of the new MI is identical to the original MI.</p>

<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 680 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#aed4001b80ceaef38d700764e9934e054">OriMIs</a> and <a href="#a1eade05b9c131318e2b1b8141cf3ef53">SchedPhiNum</a>.</p>


<p>Referenced by <a href="#a5722fabe6420b0f87a3eb1160979e5f7">calculateMaxCycle</a>, <a href="#ab595a02e4a2cbfc15add4253f222d3f1">schedulePhi</a> and <a href="#aec0f8a381dfe9925ec5cef351d20edb1">updateScheduleResult</a>.</p>

</div>
</div>

### getScheduleRange() {#adbdaac6e396c3d1dae6cee75cb2fee1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; MachineBasicBlock::iterator &gt; WindowScheduler::getScheduleRange (unsigned Offset, unsigned Num)</td>
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

<p>Gets the iterator range of MIs in the scheduling window.</p>

<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a690d8e3b14e796b870f58d3d8f7e2a77">MBB</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a5722fabe6420b0f87a3eb1160979e5f7">calculateMaxCycle</a>, <a href="#ae803ffd4decdd48471010ae2cb76d20d">calculateStallCycle</a>, <a href="#a8be84df2dea9e89e29f856c0456ae0c3">getIssueOrder</a> and <a href="#a40308f28207edf04d70fd884039d0b81">run</a>.</p>

</div>
</div>

### getSearchIndexes() {#af78f1d6e142343589981887d2a200d84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; unsigned &gt; WindowScheduler::getSearchIndexes (unsigned SearchNum, unsigned SearchRatio)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Give the folding position in the window algorithm, where different heuristics can be used.</p>


<p>It determines the performance and compilation time of the algorithm.</p>


<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#ad4542ab1cab20715a2bc58b001a42e4b">SchedInstrNum</a>.</p>


<p>Referenced by <a href="#a40308f28207edf04d70fd884039d0b81">run</a>.</p>

</div>
</div>

### initialize() {#af02c395926a140c8121e0e7d16e1dfe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WindowScheduler::initialize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initializes the algorithm and determines if it can be executed.</p>

<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="#aaffbb1654d149fc4b75f0793c03cd398">BaseII</a>, <a href="#a6fba85773a0cf15056c4263ac69dbc80">BestII</a>, <a href="#a67690feca344d36167d2f65f71653f4e">BestOffset</a>, <a href="#a3a2b84c75a614343c26e3764aab963a9">Context</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#a2a98f19750ba941ce791b75ca6d77e48">llvm::SmallSet&lt; T, N, C &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a690d8e3b14e796b870f58d3d8f7e2a77">MBB</a>, <a href="#abf97c807c56e072eec16eadaa1dc74e2">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#aed4001b80ceaef38d700764e9934e054">OriMIs</a>, <a href="#a54d52175d63bed9f3b0bd9f6317e023e">OriToCycle</a>, <a href="#ad4542ab1cab20715a2bc58b001a42e4b">SchedInstrNum</a>, <a href="#a1eade05b9c131318e2b1b8141cf3ef53">SchedPhiNum</a>, <a href="#af3f7938e6818ec29f907451091b7fdad">SchedResult</a>, <a href="#a99f029742c003f8a0e5db1538d07988e">Subtarget</a>, <a href="#ad8a9c20c5c819e59cd32906f691fbc2c">TII</a>, <a href="#afbe266c442e9313e05ebffb703c2bd36">TriMIs</a> and <a href="#a7e8c400b0b728b6ec230f0b487c6af44">TriToOri</a>.</p>


<p>Referenced by <a href="#a40308f28207edf04d70fd884039d0b81">run</a>.</p>

</div>
</div>

### isScheduleValid() {#adebaba35161e4995df328d169355e3a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::WindowScheduler::isScheduleValid ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the final result of window scheduling is valid.</p>

<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>References <a href="#a67690feca344d36167d2f65f71653f4e">BestOffset</a> and <a href="#a1eade05b9c131318e2b1b8141cf3ef53">SchedPhiNum</a>.</p>


<p>Referenced by <a href="#a40308f28207edf04d70fd884039d0b81">run</a>.</p>

</div>
</div>

### postProcess() {#a49b94106b0a74702c0cf8337eb8a6adb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WindowScheduler::postProcess ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add some related processing after running window scheduling.</p>

<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="#af94dd7df8db8b546ca9c8d29c0b31a95">restoreMBB</a> and <a href="#aabfa4ddad621932351b720f8162030e8">TripleDAG</a>.</p>


<p>Referenced by <a href="#a40308f28207edf04d70fd884039d0b81">run</a>.</p>

</div>
</div>

### preProcess() {#a30d5756e44d33e166ca0506802e578ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WindowScheduler::preProcess ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add some related processing before running window scheduling.</p>

<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="#a7519a939200f107386d3267bcd00c1c6">backupMBB</a>, <a href="#a3a2b84c75a614343c26e3764aab963a9">Context</a>, <a href="#ad9105d71f7a1c253dcb1afe7d120237e">generateTripleMBB</a>, <a href="#a690d8e3b14e796b870f58d3d8f7e2a77">MBB</a> and <a href="#aabfa4ddad621932351b720f8162030e8">TripleDAG</a>.</p>


<p>Referenced by <a href="#a40308f28207edf04d70fd884039d0b81">run</a>.</p>

</div>
</div>

### restoreMBB() {#af94dd7df8db8b546ca9c8d29c0b31a95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WindowScheduler::restoreMBB ()</td>
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

<p>Erase the MIs in current MBB and restore the original MIs.</p>

<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="#a3a2b84c75a614343c26e3764aab963a9">Context</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="#a690d8e3b14e796b870f58d3d8f7e2a77">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#aed4001b80ceaef38d700764e9934e054">OriMIs</a> and <a href="#a94fa9430a250a99da03c75e55f605349">updateLiveIntervals</a>.</p>


<p>Referenced by <a href="#a49b94106b0a74702c0cf8337eb8a6adb">postProcess</a>.</p>

</div>
</div>

### restoreTripleMBB() {#a425a27a184e7f9e226b7ba72870b19fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WindowScheduler::restoreTripleMBB ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Restore the order of MIs in TripleMBB after each list scheduling.</p>

<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="#a3a2b84c75a614343c26e3764aab963a9">Context</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a690d8e3b14e796b870f58d3d8f7e2a77">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#afbe266c442e9313e05ebffb703c2bd36">TriMIs</a>.</p>


<p>Referenced by <a href="#a40308f28207edf04d70fd884039d0b81">run</a>.</p>

</div>
</div>

### schedulePhi() {#ab595a02e4a2cbfc15add4253f222d3f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WindowScheduler::schedulePhi (int Offset, unsigned &amp; II)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Phis are scheduled separately after each list scheduling.</p>

<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a8d55f2013c2e95d424a903ff919e8fa5">getAntiRegister</a>, <a href="#ad0494bc6a8f8231640ccc225d7a86847">getOriCycle</a>, <a href="#a09475eec526bdf8626b3a02adad1fa28">getOriMI</a>, <a href="#a8f7e5d546027dc8ca8bb67c8b3f1b0cc">getOriStage</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a690d8e3b14e796b870f58d3d8f7e2a77">MBB</a>, <a href="#a588faf8e1f126dc258d357b045595407">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a54d52175d63bed9f3b0bd9f6317e023e">OriToCycle</a> and <a href="#aabfa4ddad621932351b720f8162030e8">TripleDAG</a>.</p>


<p>Referenced by <a href="#a40308f28207edf04d70fd884039d0b81">run</a>.</p>

</div>
</div>

### updateLiveIntervals() {#a94fa9430a250a99da03c75e55f605349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WindowScheduler::updateLiveIntervals ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the live intervals for all registers used within MBB.</p>

<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="#a3a2b84c75a614343c26e3764aab963a9">Context</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="#a690d8e3b14e796b870f58d3d8f7e2a77">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#ad9105d71f7a1c253dcb1afe7d120237e">generateTripleMBB</a> and <a href="#af94dd7df8db8b546ca9c8d29c0b31a95">restoreMBB</a>.</p>

</div>
</div>

### updateScheduleResult() {#aec0f8a381dfe9925ec5cef351d20edb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WindowScheduler::updateScheduleResult (unsigned Offset, unsigned II)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the scheduling result after each list scheduling.</p>

<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>, definition at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aaffbb1654d149fc4b75f0793c03cd398">BaseII</a>, <a href="#a6fba85773a0cf15056c4263ac69dbc80">BestII</a>, <a href="#a67690feca344d36167d2f65f71653f4e">BestOffset</a>, <a href="#a8be84df2dea9e89e29f856c0456ae0c3">getIssueOrder</a>, <a href="#a8f7e5d546027dc8ca8bb67c8b3f1b0cc">getOriStage</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a54d52175d63bed9f3b0bd9f6317e023e">OriToCycle</a>, <a href="#a1eade05b9c131318e2b1b8141cf3ef53">SchedPhiNum</a> and <a href="#af3f7938e6818ec29f907451091b7fdad">SchedResult</a>.</p>


<p>Referenced by <a href="#a40308f28207edf04d70fd884039d0b81">run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### BaseII {#aaffbb1654d149fc4b75f0793c03cd398}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::WindowScheduler::BaseII = 0</td>
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

<p>BaseII is the II obtained when the window offset is SchedPhiNum.</p>


<p>This offset is the initial position of the sliding window.</p>


<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>Referenced by <a href="#af02c395926a140c8121e0e7d16e1dfe1">initialize</a> and <a href="#aec0f8a381dfe9925ec5cef351d20edb1">updateScheduleResult</a>.</p>

</div>
</div>

### BestII {#a6fba85773a0cf15056c4263ac69dbc80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::WindowScheduler::BestII = UINT_MAX</td>
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

<p>BestII and BestOffset record the characteristics of the best scheduling result and are used together with SchedResult as the final window scheduling result.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>Referenced by <a href="#af02c395926a140c8121e0e7d16e1dfe1">initialize</a>, <a href="#a40308f28207edf04d70fd884039d0b81">run</a> and <a href="#aec0f8a381dfe9925ec5cef351d20edb1">updateScheduleResult</a>.</p>

</div>
</div>

### BestOffset {#a67690feca344d36167d2f65f71653f4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::WindowScheduler::BestOffset = 0</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>Referenced by <a href="#af02c395926a140c8121e0e7d16e1dfe1">initialize</a>, <a href="#adebaba35161e4995df328d169355e3a8">isScheduleValid</a>, <a href="#a40308f28207edf04d70fd884039d0b81">run</a> and <a href="#aec0f8a381dfe9925ec5cef351d20edb1">updateScheduleResult</a>.</p>

</div>
</div>

### Context {#a3a2b84c75a614343c26e3764aab963a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineSchedContext* llvm::WindowScheduler::Context = nullptr</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>Referenced by <a href="#a7519a939200f107386d3267bcd00c1c6">backupMBB</a>, <a href="#a0e34e8c324a6219e5840b893ba7f2de8">createMachineScheduler</a>, <a href="#a8b546fe78d24f8c9f7d440957a37a801">expand</a>, <a href="#af02c395926a140c8121e0e7d16e1dfe1">initialize</a>, <a href="#a30d5756e44d33e166ca0506802e578ef">preProcess</a>, <a href="#af94dd7df8db8b546ca9c8d29c0b31a95">restoreMBB</a>, <a href="#a425a27a184e7f9e226b7ba72870b19fe">restoreTripleMBB</a>, <a href="#a94fa9430a250a99da03c75e55f605349">updateLiveIntervals</a> and <a href="#af9bebcba4bcb359f1223392d9ff1e035">WindowScheduler</a>.</p>

</div>
</div>

### Loop {#a7c23e1051609c44baa4ba0e78a432139}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineLoop&amp; llvm::WindowScheduler::Loop</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>Referenced by <a href="#a8b546fe78d24f8c9f7d440957a37a801">expand</a> and <a href="#af9bebcba4bcb359f1223392d9ff1e035">WindowScheduler</a>.</p>

</div>
</div>

### MBB {#a690d8e3b14e796b870f58d3d8f7e2a77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::WindowScheduler::MBB = nullptr</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>Referenced by <a href="#a7519a939200f107386d3267bcd00c1c6">backupMBB</a>, <a href="#ad9105d71f7a1c253dcb1afe7d120237e">generateTripleMBB</a>, <a href="#a8d55f2013c2e95d424a903ff919e8fa5">getAntiRegister</a>, <a href="#a8be84df2dea9e89e29f856c0456ae0c3">getIssueOrder</a>, <a href="#adbdaac6e396c3d1dae6cee75cb2fee1f">getScheduleRange</a>, <a href="#af02c395926a140c8121e0e7d16e1dfe1">initialize</a>, <a href="#a30d5756e44d33e166ca0506802e578ef">preProcess</a>, <a href="#af94dd7df8db8b546ca9c8d29c0b31a95">restoreMBB</a>, <a href="#a425a27a184e7f9e226b7ba72870b19fe">restoreTripleMBB</a>, <a href="#a40308f28207edf04d70fd884039d0b81">run</a>, <a href="#ab595a02e4a2cbfc15add4253f222d3f1">schedulePhi</a>, <a href="#a94fa9430a250a99da03c75e55f605349">updateLiveIntervals</a> and <a href="#af9bebcba4bcb359f1223392d9ff1e035">WindowScheduler</a>.</p>

</div>
</div>

### MF {#abf97c807c56e072eec16eadaa1dc74e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::WindowScheduler::MF = nullptr</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>Referenced by <a href="#a8b546fe78d24f8c9f7d440957a37a801">expand</a>, <a href="#ad9105d71f7a1c253dcb1afe7d120237e">generateTripleMBB</a>, <a href="#af02c395926a140c8121e0e7d16e1dfe1">initialize</a> and <a href="#af9bebcba4bcb359f1223392d9ff1e035">WindowScheduler</a>.</p>

</div>
</div>

### MRI {#a588faf8e1f126dc258d357b045595407}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* llvm::WindowScheduler::MRI = nullptr</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>Referenced by <a href="#ad9105d71f7a1c253dcb1afe7d120237e">generateTripleMBB</a>, <a href="#ab595a02e4a2cbfc15add4253f222d3f1">schedulePhi</a> and <a href="#af9bebcba4bcb359f1223392d9ff1e035">WindowScheduler</a>.</p>

</div>
</div>

### OriMIs {#aed4001b80ceaef38d700764e9934e054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineInstr *&gt; llvm::WindowScheduler::OriMIs</td>
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

<p>OriMIs keeps the MIs removed from the original MBB.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>Referenced by <a href="#a7519a939200f107386d3267bcd00c1c6">backupMBB</a>, <a href="#ad9105d71f7a1c253dcb1afe7d120237e">generateTripleMBB</a>, <a href="#a8f7e5d546027dc8ca8bb67c8b3f1b0cc">getOriStage</a>, <a href="#af02c395926a140c8121e0e7d16e1dfe1">initialize</a> and <a href="#af94dd7df8db8b546ca9c8d29c0b31a95">restoreMBB</a>.</p>

</div>
</div>

### OriToCycle {#a54d52175d63bed9f3b0bd9f6317e023e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineInstr *, int&gt; llvm::WindowScheduler::OriToCycle</td>
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

<p>OriToCycle keeps the mappings between the original MI and its issue cycle.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>Referenced by <a href="#a5722fabe6420b0f87a3eb1160979e5f7">calculateMaxCycle</a>, <a href="#ad0494bc6a8f8231640ccc225d7a86847">getOriCycle</a>, <a href="#af02c395926a140c8121e0e7d16e1dfe1">initialize</a>, <a href="#a40308f28207edf04d70fd884039d0b81">run</a>, <a href="#ab595a02e4a2cbfc15add4253f222d3f1">schedulePhi</a> and <a href="#aec0f8a381dfe9925ec5cef351d20edb1">updateScheduleResult</a>.</p>

</div>
</div>

### SchedInstrNum {#ad4542ab1cab20715a2bc58b001a42e4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::WindowScheduler::SchedInstrNum = 0</td>
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

<p>SchedInstrNum records the MIs involved in scheduling in the original MBB, excluding debug instructions.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>Referenced by <a href="#a5722fabe6420b0f87a3eb1160979e5f7">calculateMaxCycle</a>, <a href="#ae803ffd4decdd48471010ae2cb76d20d">calculateStallCycle</a>, <a href="#a8be84df2dea9e89e29f856c0456ae0c3">getIssueOrder</a>, <a href="#af78f1d6e142343589981887d2a200d84">getSearchIndexes</a>, <a href="#af02c395926a140c8121e0e7d16e1dfe1">initialize</a> and <a href="#a40308f28207edf04d70fd884039d0b81">run</a>.</p>

</div>
</div>

### SchedPhiNum {#a1eade05b9c131318e2b1b8141cf3ef53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::WindowScheduler::SchedPhiNum = 0</td>
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

<p>SchedPhiNum records the number of phi in the original MBB, and the scheduling starts with MI after phis.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>Referenced by <a href="#a8f7e5d546027dc8ca8bb67c8b3f1b0cc">getOriStage</a>, <a href="#af02c395926a140c8121e0e7d16e1dfe1">initialize</a>, <a href="#adebaba35161e4995df328d169355e3a8">isScheduleValid</a>, <a href="#a40308f28207edf04d70fd884039d0b81">run</a> and <a href="#aec0f8a381dfe9925ec5cef351d20edb1">updateScheduleResult</a>.</p>

</div>
</div>

### SchedResult {#af3f7938e6818ec29f907451091b7fdad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::tuple&lt;MachineInstr *, int, int, int&gt;, 256&gt; llvm::WindowScheduler::SchedResult</td>
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

<p>SchedResult keeps the result of each list scheduling, and the format of the tuple is &lt;MI pointer, <a href="/web-llvm/docs/api/namespaces/llvm/#a60dc5ae8be8d73033ce099677e645b9b">Cycle</a>, Stage, Order <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>&gt;.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>Referenced by <a href="#a8b546fe78d24f8c9f7d440957a37a801">expand</a>, <a href="#af02c395926a140c8121e0e7d16e1dfe1">initialize</a> and <a href="#aec0f8a381dfe9925ec5cef351d20edb1">updateScheduleResult</a>.</p>

</div>
</div>

### Subtarget {#a99f029742c003f8a0e5db1538d07988e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetSubtargetInfo* llvm::WindowScheduler::Subtarget = nullptr</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>Referenced by <a href="#a5722fabe6420b0f87a3eb1160979e5f7">calculateMaxCycle</a>, <a href="#af02c395926a140c8121e0e7d16e1dfe1">initialize</a> and <a href="#af9bebcba4bcb359f1223392d9ff1e035">WindowScheduler</a>.</p>

</div>
</div>

### TII {#ad8a9c20c5c819e59cd32906f691fbc2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* llvm::WindowScheduler::TII = nullptr</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>Referenced by <a href="#a5722fabe6420b0f87a3eb1160979e5f7">calculateMaxCycle</a>, <a href="#af02c395926a140c8121e0e7d16e1dfe1">initialize</a> and <a href="#af9bebcba4bcb359f1223392d9ff1e035">WindowScheduler</a>.</p>

</div>
</div>

### TRI {#a9301a41a35d6aa7367def5ea6fd78db7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::WindowScheduler::TRI = nullptr</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>Referenced by <a href="#ad9105d71f7a1c253dcb1afe7d120237e">generateTripleMBB</a> and <a href="#af9bebcba4bcb359f1223392d9ff1e035">WindowScheduler</a>.</p>

</div>
</div>

### TriMIs {#afbe266c442e9313e05ebffb703c2bd36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineInstr *&gt; llvm::WindowScheduler::TriMIs</td>
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

<p>TriMIs keeps the MIs of TripleMBB, which is used to restore TripleMBB.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>Referenced by <a href="#ad9105d71f7a1c253dcb1afe7d120237e">generateTripleMBB</a>, <a href="#af02c395926a140c8121e0e7d16e1dfe1">initialize</a> and <a href="#a425a27a184e7f9e226b7ba72870b19fe">restoreTripleMBB</a>.</p>

</div>
</div>

### TripleDAG {#aabfa4ddad621932351b720f8162030e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ScheduleDAGInstrs&gt; llvm::WindowScheduler::TripleDAG</td>
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

<p>To innovatively identify the dependencies between MIs across two trips, we construct a DAG for a new MBB, which is created by copying the original MBB three times.</p>


<p>We refer to this new MBB as 'TripleMBB' and the corresponding DAG as 'TripleDAG'. If the dependencies are more than two trips, we avoid applying window algorithm by identifying successive phis in the old MBB.</p>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>Referenced by <a href="#ae803ffd4decdd48471010ae2cb76d20d">calculateStallCycle</a>, <a href="#a49b94106b0a74702c0cf8337eb8a6adb">postProcess</a>, <a href="#a30d5756e44d33e166ca0506802e578ef">preProcess</a>, <a href="#ab595a02e4a2cbfc15add4253f222d3f1">schedulePhi</a> and <a href="#af9bebcba4bcb359f1223392d9ff1e035">WindowScheduler</a>.</p>

</div>
</div>

### TriToOri {#a7e8c400b0b728b6ec230f0b487c6af44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineInstr *, MachineInstr *&gt; llvm::WindowScheduler::TriToOri</td>
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

<p>TriToOri keeps the mappings between the MI clones in TripleMBB and their original MI.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a>.</p>


<p>Referenced by <a href="#ad9105d71f7a1c253dcb1afe7d120237e">generateTripleMBB</a>, <a href="#ad0494bc6a8f8231640ccc225d7a86847">getOriCycle</a>, <a href="#a09475eec526bdf8626b3a02adad1fa28">getOriMI</a> and <a href="#af02c395926a140c8121e0e7d16e1dfe1">initialize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/windowscheduler-h">WindowScheduler.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/windowscheduler-cpp">WindowScheduler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
