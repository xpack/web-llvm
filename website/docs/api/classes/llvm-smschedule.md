---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/smschedule
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SMSchedule` Class Reference

<p>This class represents the scheduled code. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SMSchedule { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">llvm/CodeGen/MachinePipeliner.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab877357d6d4a96d113e83608fe92fdc8">sched_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, std::deque&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt; &gt;::iterator</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterators for the cycle to instruction map. <a href="#ab877357d6d4a96d113e83608fe92fdc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa25193b314a77b502f4efead3ee4d4a">const_sched_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, std::deque&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt; &gt;::const_iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb1ca08e3e0b9e280451db1aefa88151">SMSchedule</a> (MachineFunction *mf, SwingSchedulerDAG *DAG)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a6c2e22bb2e65d31a2243ce5d5e9312">reset</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1440bb5da603e25ae674b89a6e377ac6">setInitiationInterval</a> (int ii)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the initiation interval for this schedule. <a href="#a1440bb5da603e25ae674b89a6e377ac6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f75d2f072df591f38aa1af42b78dacf">getInitiationInterval</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the initiation interval for this schedule. <a href="#a7f75d2f072df591f38aa1af42b78dacf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9cf7f8bcf9a31775f99c732ad69e907">getFirstCycle</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the first cycle in the completed schedule. <a href="#aa9cf7f8bcf9a31775f99c732ad69e907">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af238533c2437443030e5fa4a710094c5">getFinalCycle</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the last cycle in the finalized schedule. <a href="#af238533c2437443030e5fa4a710094c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a326b69bb87197af5c7e9398da090d754">earliestCycleInChain</a> (const SwingSchedulerDDGEdge &amp;Dep, const SwingSchedulerDDG *DDG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cycle of the earliest scheduled instruction in the dependence chain. <a href="#a326b69bb87197af5c7e9398da090d754">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7d28b348c77e17419b65d3f3d7d55a4">latestCycleInChain</a> (const SwingSchedulerDDGEdge &amp;Dep, const SwingSchedulerDDG *DDG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cycle of the latest scheduled instruction in the dependence chain. <a href="#ae7d28b348c77e17419b65d3f3d7d55a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfd4efd1c9f1a0174bd6f3942238c51b">computeStart</a> (SUnit *SU, int *MaxEarlyStart, int *MinLateStart, int II, SwingSchedulerDAG *DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the scheduling start slot for the instruction. <a href="#acfd4efd1c9f1a0174bd6f3942238c51b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eff58d9105525f19d5cbe2fa6969d6e">insert</a> (SUnit *SU, int StartCycle, int EndCycle, int II)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to schedule the node at the specified StartCycle and continue until the node is schedule or the EndCycle is reached. <a href="#a2eff58d9105525f19d5cbe2fa6969d6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6455dfea4b357536881c7df8d7ca46d1">isScheduledAtStage</a> (SUnit *SU, unsigned StageNum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is scheduled at the specified stage. <a href="#a6455dfea4b357536881c7df8d7ca46d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64379c9a0436bfd06da2e854c7fc9c33">stageScheduled</a> (SUnit *SU) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the stage for a scheduled instruction. <a href="#a64379c9a0436bfd06da2e854c7fc9c33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2afdd571841c61dc8f980fe3d6f4885">cycleScheduled</a> (SUnit *SU) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cycle for a scheduled instruction. <a href="#ac2afdd571841c61dc8f980fe3d6f4885">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a336ecf423257d7f3b529f5817d9598c9">getMaxStageCount</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the maximum stage count needed for this schedule. <a href="#a336ecf423257d7f3b529f5817d9598c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::deque&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d33c5d7d0efea61cb68e2ce82f693ce">getInstructions</a> (int cycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the instructions that are scheduled at the specified cycle. <a href="#a9d33c5d7d0efea61cb68e2ce82f693ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23d6b914952799027040a351f501a0ad">computeUnpipelineableNodes</a> (SwingSchedulerDAG *SSD, TargetInstrInfo::PipelinerLoopInfo *PLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine transitive dependences of unpipelineable instructions. <a href="#a23d6b914952799027040a351f501a0ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::deque&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02320b2fe86927bf0dc6486f7c7faffa">reorderInstructions</a> (const SwingSchedulerDAG *SSD, const std::deque&lt; SUnit * &gt; &amp;Instrs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae26138aceef07cf5465c2840b437e1d8">normalizeNonPipelinedInstructions</a> (SwingSchedulerDAG *SSD, TargetInstrInfo::PipelinerLoopInfo *PLI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c7d5ab8d9814b721a1844a867ef948a">isValidSchedule</a> (SwingSchedulerDAG *SSD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff7649124c08f77b72e5d539f2f8afdf">finalizeSchedule</a> (SwingSchedulerDAG *SSD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>After the schedule has been formed, call this function to combine the instructions from the different stages/cycles. <a href="#aff7649124c08f77b72e5d539f2f8afdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70c8219e8d9627e2373f281be45f96ae">orderDependence</a> (const SwingSchedulerDAG *SSD, SUnit *SU, std::deque&lt; SUnit * &gt; &amp;Insts) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Order the instructions within a cycle so that the definitions occur before the uses. <a href="#a70c8219e8d9627e2373f281be45f96ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6911f11b05121e2c0deb7e45a6de110">isLoopCarried</a> (const SwingSchedulerDAG *SSD, MachineInstr &amp;Phi) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the scheduled Phi has a loop carried operand. <a href="#ae6911f11b05121e2c0deb7e45a6de110">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab34a636a3a33052e76df78342c72627e">isLoopCarriedDefOfUse</a> (const SwingSchedulerDAG *SSD, MachineInstr *Def, MachineOperand &amp;MO) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is a definition that is loop carried and defines the use on the next iteration. <a href="#ab34a636a3a33052e76df78342c72627e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dbd10ef0657470e3bd9f6fb48cf2307">onlyHasLoopCarriedOutputOrOrderPreds</a> (SUnit *SU, const SwingSchedulerDDG *DDG) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all scheduled predecessors are loop-carried output/order dependencies. <a href="#a4dbd10ef0657470e3bd9f6fb48cf2307">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3460671809bfea01d71388f2e45c3c50">print</a> (raw_ostream &amp;os) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the schedule information to the given output. <a href="#a3460671809bfea01d71388f2e45c3c50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28f3076bd731bbacde0d9b9655481b35">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility function used for debugging to print the schedule. <a href="#a28f3076bd731bbacde0d9b9655481b35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, std::deque&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab65d59ce3f12076e476667e1cd371e49">ScheduledInstrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from execution cycle to instructions. <a href="#ab65d59ce3f12076e476667e1cd371e49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef2984d9673a825e94cf9a7fcda4ac8d">InstrToCycle</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from instruction to execution cycle. <a href="#aef2984d9673a825e94cf9a7fcda4ac8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d279095143efe833a10ba776bd0675a">FirstCycle</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of the first cycle value in the schedule. <a href="#a9d279095143efe833a10ba776bd0675a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4be7d01746ed69272aabba2ac5a0ce7">LastCycle</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of the last cycle value in the schedule. <a href="#ae4be7d01746ed69272aabba2ac5a0ce7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b78a739115948bd9fcfc5d8d34f861e">InitiationInterval</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The initiation interval (II) for the schedule. <a href="#a4b78a739115948bd9fcfc5d8d34f861e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a13d7a701fbc5d1ba6dd965925dfe7b">ST</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> machine information. <a href="#a3a13d7a701fbc5d1ba6dd965925dfe7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57db64a62726b1a73c1d68ef98d770a1">MRI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Virtual register information. <a href="#a57db64a62726b1a73c1d68ef98d770a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/resourcemanager">ResourceManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa772983fe7f113fb0444714a3914bf67">ProcItinResources</a></td>
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

<p>This class represents the scheduled code.</p>


<p>The main data structure is a map from scheduled cycle to instructions. During scheduling, the data structure explicitly represents all stages/iterations. When the algorithm finshes, the schedule is collapsed into a single stage, which represents instructions from different loop iterations.</p>


<p>The SMS algorithm allows negative values for cycles, so the first cycle in the schedule is the smallest cycle value.</p>


<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_sched\_iterator {#aaa25193b314a77b502f4efead3ee4d4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SMSchedule::const_sched_iterator = 
      DenseMap&lt;int, std::deque&lt;SUnit *&gt;&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 741 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### sched\_iterator {#ab877357d6d4a96d113e83608fe92fdc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SMSchedule::sched_iterator =  DenseMap&lt;int, std::deque&lt;SUnit *&gt;&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterators for the cycle to instruction map.</p>

<p>Definition at line 740 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SMSchedule() {#adb1ca08e3e0b9e280451db1aefa88151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SMSchedule::SMSchedule (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * mf, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag">SwingSchedulerDAG</a> * DAG)</td>
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



<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### computeStart() {#acfd4efd1c9f1a0174bd6f3942238c51b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SMSchedule::computeStart (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, int * MaxEarlyStart, int * MinLateStart, int II, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag">SwingSchedulerDAG</a> * DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the scheduling start slot for the instruction.</p>


<p>The start slot depends on any predecessor or successor nodes scheduled already.</p>


<p>Declaration at line 735 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 2875 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>References <a href="#a326b69bb87197af5c7e9398da090d754">earliestCycleInChain</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a461d411e76e02e7a4ec0ca56098540aa">llvm::SwingSchedulerDAG::getDDG</a>, <a href="#aa9cf7f8bcf9a31775f99c732ad69e907">getFirstCycle</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddg/#ac155300b317b84aef98c8f6b5381c193">llvm::SwingSchedulerDDG::getInEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="#a9d33c5d7d0efea61cb68e2ce82f693ce">getInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddg/#afbd6cd25113b672fb9e9ec1339355d82">llvm::SwingSchedulerDDG::getOutEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a78e274f7aa81fdeddac470d645c3c6e8">llvm::SwingSchedulerDAG::isLoopCarriedDep</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad43bf1af480830a4d6604e969e3f38e9">llvm::MachineInstr::isPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a6fe37a9ed7e3ddc88a91b16aa3f83d14">llvm::SUnit::isPred</a>, <a href="#ae7d28b348c77e17419b65d3f3d7d55a4">latestCycleInChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#af6df1639af84a974f3bdcd4b93c32c2f">multipleIterations</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a>.</p>

</div>
</div>

### computeUnpipelineableNodes() {#a23d6b914952799027040a351f501a0ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSet&lt; SUnit *, 8 &gt; SMSchedule::computeUnpipelineableNodes (<a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag">SwingSchedulerDAG</a> * SSD, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/pipelinerloopinfo">TargetInstrInfo::PipelinerLoopInfo</a> * PLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine transitive dependences of unpipelineable instructions.</p>

<p>Declaration at line 777 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3116 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallset/#a2a98f19750ba941ce791b75ca6d77e48">llvm::SmallSet&lt; T, N, C &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a461d411e76e02e7a4ec0ca56098540aa">llvm::SwingSchedulerDAG::getDDG</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddg/#ac155300b317b84aef98c8f6b5381c193">llvm::SwingSchedulerDDG::getInEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddg/#afbd6cd25113b672fb9e9ec1339355d82">llvm::SwingSchedulerDDG::getOutEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a274909b1f31ad2d3d3379de55467d377">llvm::SUnit::isInstr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/pipelinerloopinfo/#a60ab2da004401c41428ea89e043ae9c5">llvm::TargetInstrInfo::PipelinerLoopInfo::shouldIgnoreForPipelining</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>.</p>


<p>Referenced by <a href="#ae26138aceef07cf5465c2840b437e1d8">normalizeNonPipelinedInstructions</a>.</p>

</div>
</div>

### cycleScheduled() {#ac2afdd571841c61dc8f980fe3d6f4885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SMSchedule::cycleScheduled (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>Return the cycle for a scheduled instruction.</p>


<p>This function normalizes the first cycle to be 0.</p>


<p>Definition at line 760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a3fa089137317e93276cab5774d4bf11f">llvm::SwingSchedulerDAG::applyInstrChange</a>, <a href="#ae6911f11b05121e2c0deb7e45a6de110">isLoopCarried</a> and <a href="#a70c8219e8d9627e2373f281be45f96ae">orderDependence</a>.</p>

</div>
</div>

### dump() {#a28f3076bd731bbacde0d9b9655481b35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SMSchedule::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Utility function used for debugging to print the schedule.</p>

<p>Declaration at line 798 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3442 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf746ca1858c0e272e3a802fc27942">llvm::print</a>.</p>

</div>
</div>

### earliestCycleInChain() {#a326b69bb87197af5c7e9398da090d754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int SMSchedule::earliestCycleInChain (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddgedge">SwingSchedulerDDGEdge</a> &amp; Dep, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddg">SwingSchedulerDDG</a> * DDG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the cycle of the earliest scheduled instruction in the dependence chain.</p>

<p>Declaration at line 727 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 2814 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddg/#ac155300b317b84aef98c8f6b5381c193">llvm::SwingSchedulerDDG::getInEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddgedge/#ad81995fff228b0618a43adce97ba17a0">llvm::SwingSchedulerDDGEdge::getSrc</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#acfd4efd1c9f1a0174bd6f3942238c51b">computeStart</a>.</p>

</div>
</div>

### finalizeSchedule() {#aff7649124c08f77b72e5d539f2f8afdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SMSchedule::finalizeSchedule (<a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag">SwingSchedulerDAG</a> * SSD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>After the schedule has been formed, call this function to combine the instructions from the different stages/cycles.</p>


<p>That is, this function creates a schedule that represents a single iteration.</p>


<p>Declaration at line 788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3384 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a3fa089137317e93276cab5774d4bf11f">llvm::SwingSchedulerDAG::applyInstrChange</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#aea2d4ef1e00ee834ab155abd18a560e4">llvm::ScheduleDAGInstrs::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a51bda1806219d879123625c8d4ae3fbc">llvm::SwingSchedulerDAG::fixupRegisterOverlaps</a>, <a href="#af238533c2437443030e5fa4a710094c5">getFinalCycle</a>, <a href="#aa9cf7f8bcf9a31775f99c732ad69e907">getFirstCycle</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="#a336ecf423257d7f3b529f5817d9598c9">getMaxStageCount</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a02320b2fe86927bf0dc6486f7c7faffa">reorderInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>.</p>

</div>
</div>

### getFinalCycle() {#af238533c2437443030e5fa4a710094c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SMSchedule::getFinalCycle ()</td>
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

<p>Return the last cycle in the finalized schedule.</p>

<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a4923617d2f897074725d389de4f450de">computeScheduledInsts</a>, <a href="#aff7649124c08f77b72e5d539f2f8afdf">finalizeSchedule</a>, <a href="#a3460671809bfea01d71388f2e45c3c50">print</a> and <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a87416d44c85818861fe0152759e9acb1">llvm::SwingSchedulerDAG::schedule</a>.</p>

</div>
</div>

### getFirstCycle() {#aa9cf7f8bcf9a31775f99c732ad69e907}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SMSchedule::getFirstCycle ()</td>
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

<p>Return the first cycle in the completed schedule.</p>


<p>This can be a negative value.</p>


<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a4923617d2f897074725d389de4f450de">computeScheduledInsts</a>, <a href="#acfd4efd1c9f1a0174bd6f3942238c51b">computeStart</a>, <a href="#aff7649124c08f77b72e5d539f2f8afdf">finalizeSchedule</a>, <a href="#ae26138aceef07cf5465c2840b437e1d8">normalizeNonPipelinedInstructions</a>, <a href="#a3460671809bfea01d71388f2e45c3c50">print</a> and <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a87416d44c85818861fe0152759e9acb1">llvm::SwingSchedulerDAG::schedule</a>.</p>

</div>
</div>

### getInitiationInterval() {#a7f75d2f072df591f38aa1af42b78dacf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SMSchedule::getInitiationInterval ()</td>
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

<p>Return the initiation interval for this schedule.</p>

<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a4923617d2f897074725d389de4f450de">computeScheduledInsts</a>.</p>

</div>
</div>

### getInstructions() {#a9d33c5d7d0efea61cb68e2ce82f693ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::deque&lt; SUnit * &gt; &amp; llvm::SMSchedule::getInstructions (int cycle)</td>
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

<p>Return the instructions that are scheduled at the specified cycle.</p>

<p>Definition at line 772 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a4923617d2f897074725d389de4f450de">computeScheduledInsts</a>, <a href="#acfd4efd1c9f1a0174bd6f3942238c51b">computeStart</a>, <a href="#ae26138aceef07cf5465c2840b437e1d8">normalizeNonPipelinedInstructions</a> and <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a87416d44c85818861fe0152759e9acb1">llvm::SwingSchedulerDAG::schedule</a>.</p>

</div>
</div>

### getMaxStageCount() {#a336ecf423257d7f3b529f5817d9598c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SMSchedule::getMaxStageCount ()</td>
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

<p>Return the maximum stage count needed for this schedule.</p>

<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a4923617d2f897074725d389de4f450de">computeScheduledInsts</a>, <a href="#aff7649124c08f77b72e5d539f2f8afdf">finalizeSchedule</a> and <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a87416d44c85818861fe0152759e9acb1">llvm::SwingSchedulerDAG::schedule</a>.</p>

</div>
</div>

### insert() {#a2eff58d9105525f19d5cbe2fa6969d6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SMSchedule::insert (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, int StartCycle, int EndCycle, int II)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to schedule the node at the specified StartCycle and continue until the node is schedule or the EndCycle is reached.</p>


<p>This function returns true if the node is scheduled. This routine may search either forward or backward for a place to insert the instruction based upon the relative values of StartCycle and EndCycle.</p>


<p>Declaration at line 737 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 2774 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#accc60d2019e9dff57bb0918a94422ebb">llvm::MachineInstr::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### isLoopCarried() {#ae6911f11b05121e2c0deb7e45a6de110}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SMSchedule::isLoopCarried (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag">SwingSchedulerDAG</a> * SSD, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Phi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the scheduled Phi has a loop carried operand.</p>

<p>Declaration at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3056 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac2afdd571841c61dc8f980fe3d6f4885">cycleScheduled</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#ad4cf8c8e4e2cc5bf94656e979ed629b4">getPhiRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab75cd37a7a0319d5a4c77189cca106ec">llvm::ScheduleDAGInstrs::getSUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad43bf1af480830a4d6604e969e3f38e9">llvm::MachineInstr::isPHI</a> and <a href="#a64379c9a0436bfd06da2e854c7fc9c33">stageScheduled</a>.</p>


<p>Referenced by <a href="#ab34a636a3a33052e76df78342c72627e">isLoopCarriedDefOfUse</a>.</p>

</div>
</div>

### isLoopCarriedDefOfUse() {#ab34a636a3a33052e76df78342c72627e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SMSchedule::isLoopCarriedDefOfUse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag">SwingSchedulerDAG</a> * SSD, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * Def, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the instruction is a definition that is loop carried and defines the use on the next iteration.</p>


<p>v1 = phi(v2, v3) (Def) v3 = op v1 (MO) = v1 If MO appears before Def, then v1 and v3 may get assigned to the same register.</p>


<p>Declaration at line 792 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3085 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a8c6faeaacd5c214d9ebeeecfe5900706">getLoopPhiReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#ae6911f11b05121e2c0deb7e45a6de110">isLoopCarried</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>.</p>


<p>Referenced by <a href="#a70c8219e8d9627e2373f281be45f96ae">orderDependence</a>.</p>

</div>
</div>

### isScheduledAtStage() {#a6455dfea4b357536881c7df8d7ca46d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SMSchedule::isScheduledAtStage (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, unsigned StageNum)</td>
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

<p>Return true if the instruction is scheduled at the specified stage.</p>

<p>Definition at line 745 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<p>Reference <a href="#a64379c9a0436bfd06da2e854c7fc9c33">stageScheduled</a>.</p>

</div>
</div>

### isValidSchedule() {#a7c7d5ab8d9814b721a1844a867ef948a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SMSchedule::isValidSchedule (<a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag">SwingSchedulerDAG</a> * SSD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3195 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a461d411e76e02e7a4ec0ca56098540aa">llvm::SwingSchedulerDAG::getDDG</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddg/#afbd6cd25113b672fb9e9ec1339355d82">llvm::SwingSchedulerDDG::getOutEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a9d9a8b8d5225f85cecbbada4ce4406b0">llvm::SUnit::hasPhysRegDefs</a>, <a href="#a64379c9a0436bfd06da2e854c7fc9c33">stageScheduled</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>.</p>

</div>
</div>

### latestCycleInChain() {#ae7d28b348c77e17419b65d3f3d7d55a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int SMSchedule::latestCycleInChain (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddgedge">SwingSchedulerDDGEdge</a> &amp; Dep, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddg">SwingSchedulerDDG</a> * DDG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the cycle of the latest scheduled instruction in the dependence chain.</p>

<p>Declaration at line 732 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 2838 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddgedge/#a0aefcbe2a86ca46fe2922647b8fe59d3">llvm::SwingSchedulerDDGEdge::getDst</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddg/#afbd6cd25113b672fb9e9ec1339355d82">llvm::SwingSchedulerDDG::getOutEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a7406c398c67e53ee3937bf2b6df1c64e">llvm::SUnit::isBoundaryNode</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#acfd4efd1c9f1a0174bd6f3942238c51b">computeStart</a>.</p>

</div>
</div>

### normalizeNonPipelinedInstructions() {#ae26138aceef07cf5465c2840b437e1d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SMSchedule::normalizeNonPipelinedInstructions (<a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag">SwingSchedulerDAG</a> * SSD, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/pipelinerloopinfo">TargetInstrInfo::PipelinerLoopInfo</a> * PLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 785 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>References <a href="#a23d6b914952799027040a351f501a0ad">computeUnpipelineableNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#ae04ad615dfdd885e85cbddda146787c6">llvm::SmallSet&lt; T, N, C &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a60a348350395aef11d68f58111bcf499">llvm::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a461d411e76e02e7a4ec0ca56098540aa">llvm::SwingSchedulerDAG::getDDG</a>, <a href="#aa9cf7f8bcf9a31775f99c732ad69e907">getFirstCycle</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddg/#ac155300b317b84aef98c8f6b5381c193">llvm::SwingSchedulerDDG::getInEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="#a9d33c5d7d0efea61cb68e2ce82f693ce">getInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddg/#afbd6cd25113b672fb9e9ec1339355d82">llvm::SwingSchedulerDDG::getOutEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a274909b1f31ad2d3d3379de55467d377">llvm::SUnit::isInstr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="#a64379c9a0436bfd06da2e854c7fc9c33">stageScheduled</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>.</p>

</div>
</div>

### onlyHasLoopCarriedOutputOrOrderPreds() {#a4dbd10ef0657470e3bd9f6fb48cf2307}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SMSchedule::onlyHasLoopCarriedOutputOrOrderPreds (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddg">SwingSchedulerDDG</a> * DDG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if all scheduled predecessors are loop-carried output/order dependencies.</p>

<p>Declaration at line 795 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3107 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddg/#ac155300b317b84aef98c8f6b5381c193">llvm::SwingSchedulerDDG::getInEdges</a>.</p>

</div>
</div>

### orderDependence() {#a70c8219e8d9627e2373f281be45f96ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SMSchedule::orderDependence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag">SwingSchedulerDAG</a> * SSD, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, std::deque&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt; &amp; Insts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Order the instructions within a cycle so that the definitions occur before the uses.</p>


<p>Returns true if the instruction is added to the start of the list, or false if added to the end.</p>


<p>Declaration at line 789 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 2925 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>References <a href="#ac2afdd571841c61dc8f980fe3d6f4885">cycleScheduled</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a461d411e76e02e7a4ec0ca56098540aa">llvm::SwingSchedulerDAG::getDDG</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddg/#ac155300b317b84aef98c8f6b5381c193">llvm::SwingSchedulerDDG::getInEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a1fe621a53bd3086e49d01cc0a3dcfd40">llvm::SwingSchedulerDAG::getInstrBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerddg/#afbd6cd25113b672fb9e9ec1339355d82">llvm::SwingSchedulerDDG::getOutEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ab34a636a3a33052e76df78342c72627e">isLoopCarriedDefOfUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a70c8219e8d9627e2373f281be45f96ae">orderDependence</a> and <a href="#a64379c9a0436bfd06da2e854c7fc9c33">stageScheduled</a>.</p>


<p>Referenced by <a href="#a70c8219e8d9627e2373f281be45f96ae">orderDependence</a> and <a href="#a02320b2fe86927bf0dc6486f7c7faffa">reorderInstructions</a>.</p>

</div>
</div>

### print() {#a3460671809bfea01d71388f2e45c3c50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SMSchedule::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; os)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the schedule information to the given output.</p>

<p>Declaration at line 797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3427 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>References <a href="#af238533c2437443030e5fa4a710094c5">getFinalCycle</a>, <a href="#aa9cf7f8bcf9a31775f99c732ad69e907">getFirstCycle</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab419785650ef9728b5305d220179017c">llvm::MachineInstr::print</a> and <a href="#a64379c9a0436bfd06da2e854c7fc9c33">stageScheduled</a>.</p>

</div>
</div>

### reorderInstructions() {#a02320b2fe86927bf0dc6486f7c7faffa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::deque&lt; SUnit * &gt; SMSchedule::reorderInstructions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag">SwingSchedulerDAG</a> * SSD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::deque&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt; &amp; Instrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 781 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3365 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad43bf1af480830a4d6604e969e3f38e9">llvm::MachineInstr::isPHI</a> and <a href="#a70c8219e8d9627e2373f281be45f96ae">orderDependence</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a4923617d2f897074725d389de4f450de">computeScheduledInsts</a> and <a href="#aff7649124c08f77b72e5d539f2f8afdf">finalizeSchedule</a>.</p>

</div>
</div>

### reset() {#a4a6c2e22bb2e65d31a2243ce5d5e9312}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SMSchedule::reset ()</td>
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



<p>Definition at line 701 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### setInitiationInterval() {#a1440bb5da603e25ae674b89a6e377ac6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SMSchedule::setInitiationInterval (int ii)</td>
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

<p>Set the initiation interval for this schedule.</p>

<p>Definition at line 710 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### stageScheduled() {#a64379c9a0436bfd06da2e854c7fc9c33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SMSchedule::stageScheduled (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>Return the stage for a scheduled instruction.</p>


<p>Return -1 if the instruction has not been scheduled.</p>


<p>Definition at line 751 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a3fa089137317e93276cab5774d4bf11f">llvm::SwingSchedulerDAG::applyInstrChange</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a4923617d2f897074725d389de4f450de">computeScheduledInsts</a>, <a href="#ae6911f11b05121e2c0deb7e45a6de110">isLoopCarried</a>, <a href="#a6455dfea4b357536881c7df8d7ca46d1">isScheduledAtStage</a>, <a href="#a7c7d5ab8d9814b721a1844a867ef948a">isValidSchedule</a>, <a href="#ae26138aceef07cf5465c2840b437e1d8">normalizeNonPipelinedInstructions</a>, <a href="#a70c8219e8d9627e2373f281be45f96ae">orderDependence</a>, <a href="#a3460671809bfea01d71388f2e45c3c50">print</a> and <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a87416d44c85818861fe0152759e9acb1">llvm::SwingSchedulerDAG::schedule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FirstCycle {#a9d279095143efe833a10ba776bd0675a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SMSchedule::FirstCycle = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of the first cycle value in the schedule.</p>


<p>It starts as zero, but the algorithm allows negative values.</p>


<p>Definition at line 680 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### InitiationInterval {#a4b78a739115948bd9fcfc5d8d34f861e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SMSchedule::InitiationInterval = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The initiation interval (II) for the schedule.</p>

<p>Definition at line 686 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### InstrToCycle {#aef2984d9673a825e94cf9a7fcda4ac8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;SUnit *, int&gt; llvm::SMSchedule::InstrToCycle</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from instruction to execution cycle.</p>

<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### LastCycle {#ae4be7d01746ed69272aabba2ac5a0ce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SMSchedule::LastCycle = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of the last cycle value in the schedule.</p>

<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### MRI {#a57db64a62726b1a73c1d68ef98d770a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; llvm::SMSchedule::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Virtual register information.</p>

<p>Definition at line 692 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### ProcItinResources {#aa772983fe7f113fb0444714a3914bf67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourceManager llvm::SMSchedule::ProcItinResources</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 694 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### ScheduledInstrs {#ab65d59ce3f12076e476667e1cd371e49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;int, std::deque&lt;SUnit *&gt; &gt; llvm::SMSchedule::ScheduledInstrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from execution cycle to instructions.</p>

<p>Definition at line 673 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### ST {#a3a13d7a701fbc5d1ba6dd965925dfe7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetSubtargetInfo&amp; llvm::SMSchedule::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> machine information.</p>

<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
