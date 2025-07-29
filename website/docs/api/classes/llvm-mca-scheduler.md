---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/scheduler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Scheduler` Class

<p>Class <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler">Scheduler</a> is responsible for issuing instructions to pipeline resources. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::mca::Scheduler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">llvm/MCA/HardwareUnits/Scheduler.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/hardwareunit">HardwareUnit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Status { <a href="#a00e7e6b87078e432076de80b74dc6251">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae42ebb9684748fdf5df711463c869c0a">Scheduler</a> (const MCSchedModel &amp;Model, LSUnitBase &amp;Lsu)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6d565e1a69b6c026f59da8f5b610d17">Scheduler</a> (const MCSchedModel &amp;Model, LSUnitBase &amp;Lsu, std::unique_ptr&lt; SchedulerStrategy &gt; SelectStrategy)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4902b46730048e0d34c9e7056dbcda86">Scheduler</a> (std::unique_ptr&lt; ResourceManager &gt; RM, LSUnitBase &amp;Lsu, std::unique_ptr&lt; SchedulerStrategy &gt; SelectStrategy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a00e7e6b87078e432076de80b74dc6251">Status</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5edfbe268d597c17c00c74ccc1cf59c4">isAvailable</a> (const InstRef &amp;IR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the instruction in 'IR' can be dispatched during this cycle. <a href="#a5edfbe268d597c17c00c74ccc1cf59c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab72375182cfa0b8e37b997b861e35208">dispatch</a> (InstRef &amp;IR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reserves buffer and <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit">LSUnit</a> queue resources that are necessary to issue this instruction. <a href="#ab72375182cfa0b8e37b997b861e35208">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a216ffefe6fe4a2b566a72228c0bd763d">issueInstruction</a> (InstRef &amp;IR, SmallVectorImpl&lt; std::pair&lt; ResourceRef, ReleaseAtCycles &gt; &gt; &amp;Used, SmallVectorImpl&lt; InstRef &gt; &amp;Pending, SmallVectorImpl&lt; InstRef &gt; &amp;Ready)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Issue an instruction and populates a vector of used pipeline resources, and a vector of instructions that transitioned to the ready state as a result of this event. <a href="#a216ffefe6fe4a2b566a72228c0bd763d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8e4d85b5f90fc2efe108d87e78e9a87">mustIssueImmediately</a> (const InstRef &amp;IR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if IR has to be issued immediately, or if IR is a zero latency instruction. <a href="#ab8e4d85b5f90fc2efe108d87e78e9a87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab88715985e19d51a306fb8be0cf857f3">cycleEvent</a> (SmallVectorImpl&lt; ResourceRef &gt; &amp;Freed, SmallVectorImpl&lt; InstRef &gt; &amp;Executed, SmallVectorImpl&lt; InstRef &gt; &amp;Pending, SmallVectorImpl&lt; InstRef &gt; &amp;Ready)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This routine notifies the <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler">Scheduler</a> that a new cycle just started. <a href="#ab88715985e19d51a306fb8be0cf857f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06f0458c240c7f93993b487406362dd4">getResourceID</a> (uint64_t Mask) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert a resource mask into a valid llvm processor resource identifier. <a href="#a06f0458c240c7f93993b487406362dd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0113fd8e2f25ac69b90b9ac8ded672f6">select</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select the next instruction to issue from the ReadySet. <a href="#a0113fd8e2f25ac69b90b9ac8ded672f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acca87ed9660ca7a49875aef56eec7300">isReadySetEmpty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa3f9288bed373eeec8105217c9bfd4e">isWaitSetEmpty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9651d447561aa0aea1b3171eee94152c">analyzeDataDependencies</a> (SmallVectorImpl&lt; InstRef &gt; &amp;RegDeps, SmallVectorImpl&lt; InstRef &gt; &amp;MemDeps)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called by the <a href="/web-llvm/docs/api/classes/llvm/mca/executestage">ExecuteStage</a> at the end of each cycle to identify bottlenecks caused by data dependencies. <a href="#a9651d447561aa0aea1b3171eee94152c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc287c6713c7cc1096138c314440b5c9">analyzeResourcePressure</a> (SmallVectorImpl&lt; InstRef &gt; &amp;Insts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a mask of busy resources, and populates vector Insts with instructions that could not be issued to the underlying pipelines because not all pipeline resources were available. <a href="#abc287c6713c7cc1096138c314440b5c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9e624cddbeb545e5eded5202948ec34">hadTokenStall</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3b463eb7a35c82d80ad92090f8d7a13">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2e95803b97c6de37b0d99d390102494">instructionCheck</a> (const InstRef &amp;IR) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92c8333a4d65255a264f7848329a762d">initializeStrategy</a> (std::unique_ptr&lt; SchedulerStrategy &gt; S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the given selection strategy and set the Strategy member accordingly. <a href="#a92c8333a4d65255a264f7848329a762d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a105e62424e6f2b5d3014f3f0dbfa650c">issueInstructionImpl</a> (InstRef &amp;IR, SmallVectorImpl&lt; std::pair&lt; ResourceRef, ReleaseAtCycles &gt; &gt; &amp;Pipes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Issue an instruction without updating the ready queue. <a href="#a105e62424e6f2b5d3014f3f0dbfa650c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c4229a84bffdd9db3fbf74f3ceddbb4">updateIssuedSet</a> (SmallVectorImpl&lt; InstRef &gt; &amp;Executed)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa272db3d43261c8bdfacf8384b41726e">promoteToReadySet</a> (SmallVectorImpl&lt; InstRef &gt; &amp;Ready)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6664b17dae151df74b62bb7640dc29b4">promoteToPendingSet</a> (SmallVectorImpl&lt; InstRef &gt; &amp;Pending)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase">LSUnitBase</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d7dad48677919600908deb5fe6cef71">LSU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/schedulerstrategy">SchedulerStrategy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d3720aa55395a263394cca0301fcc10">Strategy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager">ResourceManager</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82b7c80dbc0b04cde1e897da32e33f84">Resources</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49fa73fd3dbb64f5c1673d0f3a9cefa0">WaitSet</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a28c976a592b71d3122009efd7e3d44">PendingSet</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1494329e19bfae43a2fefca73aedd82">ReadySet</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac25de4d1ea08b5ea1884b3baee17e15e">IssuedSet</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4d16f621aa30e898979d32b6a37b55d">BusyResourceUnits</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a454718dc2d0b550627914512c8975c2c">NumDispatchedToThePendingSet</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafc3db08796f08ab004dffaf54e785f0">HadTokenStall</a></td>
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

<p>Class <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler">Scheduler</a> is responsible for issuing instructions to pipeline resources.</p>


<p>Internally, it delegates to a <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager">ResourceManager</a> the management of processor resources. This class is also responsible for tracking the progress of instructions from the dispatch stage, until the write-back stage.</p>


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Status {#a00e7e6b87078e432076de80b74dc6251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::mca::Scheduler::Status </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SC_AVAILABLE<a id="a00e7e6b87078e432076de80b74dc6251a30471692f55d488e4f76cf1d3f34e6d7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SC_LOAD_QUEUE_FULL<a id="a00e7e6b87078e432076de80b74dc6251a079edf3c8469d81f403046bcb58ba8a9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SC_STORE_QUEUE_FULL<a id="a00e7e6b87078e432076de80b74dc6251a5260919cd474bd3101720c9ad53ce962"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SC_BUFFERS_FULL<a id="a00e7e6b87078e432076de80b74dc6251ac32c3257dbcf2b454cc6a5e9fa4e8add"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SC_DISPATCH_GROUP_STALL<a id="a00e7e6b87078e432076de80b74dc6251aaa61622c14b5d6d866d685a5d0ca1cf3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Scheduler() {#ae42ebb9684748fdf5df711463c869c0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::Scheduler::Scheduler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a> &amp; Model, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase">LSUnitBase</a> &amp; Lsu)</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>


<p>Reference <a href="#ae42ebb9684748fdf5df711463c869c0a">Scheduler</a>.</p>


<p>Referenced by <a href="#ae42ebb9684748fdf5df711463c869c0a">Scheduler</a> and <a href="#aa6d565e1a69b6c026f59da8f5b610d17">Scheduler</a>.</p>

</div>
</div>

### Scheduler() {#aa6d565e1a69b6c026f59da8f5b610d17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::Scheduler::Scheduler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a> &amp; Model, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase">LSUnitBase</a> &amp; Lsu, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/schedulerstrategy">SchedulerStrategy</a> &gt; SelectStrategy)</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#ae42ebb9684748fdf5df711463c869c0a">Scheduler</a>.</p>

</div>
</div>

### Scheduler() {#a4902b46730048e0d34c9e7056dbcda86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::Scheduler::Scheduler (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager">ResourceManager</a> &gt; RM, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase">LSUnitBase</a> &amp; Lsu, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/schedulerstrategy">SchedulerStrategy</a> &gt; SelectStrategy)</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### analyzeDataDependencies() {#a9651d447561aa0aea1b3171eee94152c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Scheduler::analyzeDataDependencies (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt; &amp; RegDeps, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt; &amp; MemDeps)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method is called by the <a href="/web-llvm/docs/api/classes/llvm/mca/executestage">ExecuteStage</a> at the end of each cycle to identify bottlenecks caused by data dependencies.</p>


<p>Vector RegDeps is populated by instructions that were not issued because of unsolved register dependencies. Vector MemDeps is populated by instructions that were not issued because of unsolved memory dependencies.</p>


<p>Declaration at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>, definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/scheduler-cpp">Scheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a4598f230fe63b5811a5a9b01bc613c90">llvm::mca::InstructionBase::getDesc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a67c179f1b0e96ef53a03966e4ee831fe">llvm::mca::InstructionBase::isMemOp</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instruction/#aed04cdcdcafe3907e7cc831734e0c945">llvm::mca::Instruction::isPending</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### analyzeResourcePressure() {#abc287c6713c7cc1096138c314440b5c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::Scheduler::analyzeResourcePressure (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt; &amp; Insts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a mask of busy resources, and populates vector Insts with instructions that could not be issued to the underlying pipelines because not all pipeline resources were available.</p>

<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/scheduler-cpp">Scheduler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>.</p>

</div>
</div>

### cycleEvent() {#ab88715985e19d51a306fb8be0cf857f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Scheduler::cycleEvent (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/mca/#aa013ffaca9bcaadec118afaede71ab29">ResourceRef</a> &gt; &amp; Freed, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt; &amp; Executed, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt; &amp; Pending, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt; &amp; Ready)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This routine notifies the <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler">Scheduler</a> that a new cycle just started.</p>


<p>It notifies the underlying <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager">ResourceManager</a> that a new cycle just started. Vector <span class="doxyComputerOutput">Freed</span> is populated with resourceRef related to resources that have changed in state, and that are now available to new instructions. Instructions executed are added to vector Executed, while vector Ready is populated with instructions that have become ready in this new cycle. Vector Pending is popluated by instructions that have transitioned through the pending stat during this cycle. The Pending and Ready sets may not be disjoint. An instruction is allowed to transition from the WAIT state to the READY state (going through the PENDING state) within a single cycle. That means, instructions may appear in both the Pending and Ready set.</p>


<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>, definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/scheduler-cpp">Scheduler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>

</div>
</div>

### dispatch() {#ab72375182cfa0b8e37b997b861e35208}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::Scheduler::dispatch (<a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reserves buffer and <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit">LSUnit</a> queue resources that are necessary to issue this instruction.</p>


<p>Returns true if instruction IR is ready to be issued to the underlying pipelines. Note that this operation cannot fail; it assumes that a previous call to method <span class="doxyComputerOutput">isAvailable(IR)</span> returned <span class="doxyComputerOutput">SC_AVAILABLE</span>.</p>


<p>If IR is a memory operation, then the <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler">Scheduler</a> queries the LS unit to obtain a LS token. An LS token is used internally to track memory dependencies.</p>


<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>, definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/scheduler-cpp">Scheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instruction/#ade5871926e9ec2af4e3f5151764ac934">llvm::mca::Instruction::getUsedBuffers</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instruction/#a07eee271c4520e38fdbf53c45e0b343f">llvm::mca::Instruction::isDispatched</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a67c179f1b0e96ef53a03966e4ee831fe">llvm::mca::InstructionBase::isMemOp</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instruction/#aed04cdcdcafe3907e7cc831734e0c945">llvm::mca::Instruction::isPending</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instruction/#a8bb47a248d88005ef524178ebfc9b47a">llvm::mca::Instruction::isReady</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ab8e4d85b5f90fc2efe108d87e78e9a87">mustIssueImmediately</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/instruction/#abb66d9fd67e0ee7d09dec5b097683144">llvm::mca::Instruction::setLSUTokenID</a>.</p>

</div>
</div>

### dump() {#ad3b463eb7a35c82d80ad92090f8d7a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Scheduler::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/scheduler-cpp">Scheduler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>.</p>

</div>
</div>

### getResourceID() {#a06f0458c240c7f93993b487406362dd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::Scheduler::getResourceID (uint64_t Mask)</td>
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

<p>Convert a resource mask into a valid llvm processor resource identifier.</p>


<p>Only the most significant bit of the Mask is used by this method to identify the processor resource.</p>


<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>

</div>
</div>

### hadTokenStall() {#af9e624cddbeb545e5eded5202948ec34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::Scheduler::hadTokenStall ()</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>

</div>
</div>

### instructionCheck() {#ae2e95803b97c6de37b0d99d390102494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Scheduler::instructionCheck (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>

</div>
</div>

### isAvailable() {#a5edfbe268d597c17c00c74ccc1cf59c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Scheduler::Status llvm::mca::Scheduler::isAvailable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the instruction in 'IR' can be dispatched during this cycle.</p>


<p>Return SC_AVAILABLE if both scheduler and LS resources are available.</p>


<p>This method is also responsible for setting field HadTokenStall if IR cannot be dispatched to the <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler">Scheduler</a> due to unavailable resources.</p>


<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/scheduler-cpp">Scheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#aaa2955db8dc3f1104bd78c37f6d883cda9ba5f0372dc81f2346c57d6871fd61ec">llvm::mca::LSUnitBase::LSU_AVAILABLE</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#aaa2955db8dc3f1104bd78c37f6d883cda7307bc1f313d256cd75ae3490beb69b0">llvm::mca::LSUnitBase::LSU_LQUEUE_FULL</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#aaa2955db8dc3f1104bd78c37f6d883cdab78bfd357a2c1a359c120ca260e45878">llvm::mca::LSUnitBase::LSU_SQUEUE_FULL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a75e277a81194898f20f1c3613af0072aa3f746cb41f05bc7d2405d8f261ad3b53">llvm::mca::RS_BUFFER_AVAILABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a75e277a81194898f20f1c3613af0072aa31d38f37314ff7269028574355831c80">llvm::mca::RS_BUFFER_UNAVAILABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a75e277a81194898f20f1c3613af0072aadc0c2c76e3c6a9189f1c720ed16abd2f">llvm::mca::RS_RESERVED</a>, <a href="#a00e7e6b87078e432076de80b74dc6251a30471692f55d488e4f76cf1d3f34e6d7">SC_AVAILABLE</a>, <a href="#a00e7e6b87078e432076de80b74dc6251ac32c3257dbcf2b454cc6a5e9fa4e8add">SC_BUFFERS_FULL</a>, <a href="#a00e7e6b87078e432076de80b74dc6251aaa61622c14b5d6d866d685a5d0ca1cf3">SC_DISPATCH_GROUP_STALL</a>, <a href="#a00e7e6b87078e432076de80b74dc6251a079edf3c8469d81f403046bcb58ba8a9">SC_LOAD_QUEUE_FULL</a> and <a href="#a00e7e6b87078e432076de80b74dc6251a5260919cd474bd3101720c9ad53ce962">SC_STORE_QUEUE_FULL</a>.</p>

</div>
</div>

### isReadySetEmpty() {#acca87ed9660ca7a49875aef56eec7300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::Scheduler::isReadySetEmpty ()</td>
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



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>

</div>
</div>

### issueInstruction() {#a216ffefe6fe4a2b566a72228c0bd763d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Scheduler::issueInstruction (<a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/mca/#aa013ffaca9bcaadec118afaede71ab29">ResourceRef</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/releaseatcycles">ReleaseAtCycles</a> &gt; &gt; &amp; Used, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt; &amp; Pending, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt; &amp; Ready)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Issue an instruction and populates a vector of used pipeline resources, and a vector of instructions that transitioned to the ready state as a result of this event.</p>

<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>, definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/scheduler-cpp">Scheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mca/instruction/#ade5871926e9ec2af4e3f5151764ac934">llvm::mca::Instruction::getUsedBuffers</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a519b94a853bacce216d3be59b5e717d3">llvm::mca::InstructionBase::hasDependentUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a67c179f1b0e96ef53a03966e4ee831fe">llvm::mca::InstructionBase::isMemOp</a>.</p>

</div>
</div>

### isWaitSetEmpty() {#afa3f9288bed373eeec8105217c9bfd4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::Scheduler::isWaitSetEmpty ()</td>
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



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>

</div>
</div>

### mustIssueImmediately() {#ab8e4d85b5f90fc2efe108d87e78e9a87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::Scheduler::mustIssueImmediately (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if IR has to be issued immediately, or if IR is a zero latency instruction.</p>

<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>, definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/scheduler-cpp">Scheduler.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>


<p>Referenced by <a href="#ab72375182cfa0b8e37b997b861e35208">dispatch</a>.</p>

</div>
</div>

### select() {#a0113fd8e2f25ac69b90b9ac8ded672f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstRef llvm::mca::Scheduler::select ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Select the next instruction to issue from the ReadySet.</p>


<p>Returns an invalid instruction reference if there are no ready instructions, or if processor resources are not available.</p>


<p>Declaration at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>, definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/scheduler-cpp">Scheduler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructionbase/#a4598f230fe63b5811a5a9b01bc613c90">llvm::mca::InstructionBase::getDesc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instruction/#a814fb55571cfb4880954cd744816c34a">llvm::mca::Instruction::setCriticalResourceMask</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### initializeStrategy() {#a92c8333a4d65255a264f7848329a762d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Scheduler::initializeStrategy (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/schedulerstrategy">SchedulerStrategy</a> &gt; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify the given selection strategy and set the Strategy member accordingly.</p>


<p>If no strategy is provided, the <a href="/web-llvm/docs/api/classes/llvm/mca/defaultschedulerstrategy">DefaultSchedulerStrategy</a> is used.</p>


<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/scheduler-cpp">Scheduler.cpp</a>.</p>

</div>
</div>

### issueInstructionImpl() {#a105e62424e6f2b5d3014f3f0dbfa650c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Scheduler::issueInstructionImpl (<a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/mca/#aa013ffaca9bcaadec118afaede71ab29">ResourceRef</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/releaseatcycles">ReleaseAtCycles</a> &gt; &gt; &amp; Pipes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Issue an instruction without updating the ready queue.</p>

<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/scheduler-cpp">Scheduler.cpp</a>.</p>

</div>
</div>

### promoteToPendingSet() {#a6664b17dae151df74b62bb7640dc29b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::Scheduler::promoteToPendingSet (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt; &amp; Pending)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/scheduler-cpp">Scheduler.cpp</a>.</p>

</div>
</div>

### promoteToReadySet() {#aa272db3d43261c8bdfacf8384b41726e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::Scheduler::promoteToReadySet (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt; &amp; Ready)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/scheduler-cpp">Scheduler.cpp</a>.</p>

</div>
</div>

### updateIssuedSet() {#a9c4229a84bffdd9db3fbf74f3ceddbb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Scheduler::updateIssuedSet (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt; &amp; Executed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>, definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/scheduler-cpp">Scheduler.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BusyResourceUnits {#aa4d16f621aa30e898979d32b6a37b55d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::mca::Scheduler::BusyResourceUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>

</div>
</div>

### HadTokenStall {#aafc3db08796f08ab004dffaf54e785f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::Scheduler::HadTokenStall</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>

</div>
</div>

### IssuedSet {#ac25de4d1ea08b5ea1884b3baee17e15e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;InstRef&gt; llvm::mca::Scheduler::IssuedSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>

</div>
</div>

### LSU {#a7d7dad48677919600908deb5fe6cef71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LSUnitBase&amp; llvm::mca::Scheduler::LSU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>

</div>
</div>

### NumDispatchedToThePendingSet {#a454718dc2d0b550627914512c8975c2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::Scheduler::NumDispatchedToThePendingSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>

</div>
</div>

### PendingSet {#a6a28c976a592b71d3122009efd7e3d44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;InstRef&gt; llvm::mca::Scheduler::PendingSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>

</div>
</div>

### ReadySet {#ac1494329e19bfae43a2fefca73aedd82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;InstRef&gt; llvm::mca::Scheduler::ReadySet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>

</div>
</div>

### Resources {#a82b7c80dbc0b04cde1e897da32e33f84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ResourceManager&gt; llvm::mca::Scheduler::Resources</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>

</div>
</div>

### Strategy {#a0d3720aa55395a263394cca0301fcc10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SchedulerStrategy&gt; llvm::mca::Scheduler::Strategy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>

</div>
</div>

### WaitSet {#a49fa73fd3dbb64f5c1673d0f3a9cefa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;InstRef&gt; llvm::mca::Scheduler::WaitSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/include/llvm/mca/hardwareunits/scheduler-h">Scheduler.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mca/lib/mca/hardwareunits/scheduler-cpp">Scheduler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
