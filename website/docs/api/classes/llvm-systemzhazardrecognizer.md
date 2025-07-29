---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/systemzhazardrecognizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SystemZHazardRecognizer` Class

<p><a href="/web-llvm/docs/api/classes/llvm/systemzhazardrecognizer">SystemZHazardRecognizer</a> maintains the state for one MBB during scheduling. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SystemZHazardRecognizer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">Target/SystemZ/SystemZHazardRecognizer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer">ScheduleHazardRecognizer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HazardRecognizer - This determines whether or not an instruction can be issued this cycle, and whether or not a noop needs to be inserted to handle the hazard. <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9591637d45b2fd9b6af0d7ad576b2e7">SystemZHazardRecognizer</a> (const SystemZInstrInfo *tii, const TargetSchedModel *SM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a9bec0e329b12bbc503d08db497d43267">HazardType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93f9e5c48a726c5f26603735a3e0a08e">getHazardType</a> (SUnit *SU, int Stalls=0) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getHazardType - Return the hazard type of emitting this node. <a href="#a93f9e5c48a726c5f26603735a3e0a08e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f2640beef5b132e6c14d9db42e06dd1">Reset</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset - This callback is invoked when a new block of instructions is about to be schedule. <a href="#a5f2640beef5b132e6c14d9db42e06dd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8b6eb92a49f95a3bc79199f0768de4a">EmitInstruction</a> (SUnit *SU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitInstruction - This callback is invoked when an instruction is emitted, to advance the hazard state. <a href="#ae8b6eb92a49f95a3bc79199f0768de4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a0f2858cdd379056abfa2531e7da961">getSchedClass</a> (SUnit *SU) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resolves and cache a resolved scheduling class for an <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>. <a href="#a4a0f2858cdd379056abfa2531e7da961">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47377e7e9aaf5a00affe4f4d8ec61f3e">emitInstruction</a> (MachineInstr *MI, bool TakenBranch=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrap a non-scheduled instruction in an SU and emit it. <a href="#a47377e7e9aaf5a00affe4f4d8ec61f3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fdaca7e15aaaa6d903d0498220b8cc1">groupingCost</a> (SUnit *SU) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cost of decoder grouping for SU. <a href="#a0fdaca7e15aaaa6d903d0498220b8cc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab727fc0077d4f6ff1ad7b34cc5d2f069">resourcesCost</a> (SUnit *SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cost of SU in regards to processor resources usage. <a href="#ab727fc0077d4f6ff1ad7b34cc5d2f069">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a2ae56dfdc087ade919e8712369134a">dumpSU</a> (SUnit *SU, raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab00ec78da7d69f1c482ceaa59c677fa0">dumpCurrGroup</a> (std::string Msg="") const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fe3df1038d3bb4ac86cb76e6b5649fe">dumpProcResourceCounters</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0f9d37195903c86ebbb9119e9e26fc0">dumpState</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7b41e365774a047ff8decb963b72033">getLastEmittedMI</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55f00177f4ea5d09fa4d4d88ee3cbc2b">copyState</a> (SystemZHazardRecognizer *Incoming)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy counters from end of single predecessor. <a href="#a55f00177f4ea5d09fa4d4d88ee3cbc2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cd673a97fe8746af526c05f03154849">getNumDecoderSlots</a> (SUnit *SU) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of decoder slots MI requires. <a href="#a4cd673a97fe8746af526c05f03154849">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9e1a00841b526c5dd7592cf1aa9db5f">fitsIntoCurrentGroup</a> (SUnit *SU) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if MI fits into current decoder group. <a href="#ab9e1a00841b526c5dd7592cf1aa9db5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada7467f520d9b075d7f5d3115369cc1d">has4RegOps</a> (const MachineInstr *MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction has four register operands. <a href="#ada7467f520d9b075d7f5d3115369cc1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4e535f0aa753fa6102e686d1fc03d2a">getCurrCycleIdx</a> (SUnit *SU=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Two decoder groups per cycle are formed (for z13), meaning 2x3 instructions. <a href="#ad4e535f0aa753fa6102e686d1fc03d2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad44d438949333878af469740467a5800">getCurrGroupSize</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7b58504cc9b3d03e08a966a00dbe830">nextGroup</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start next decoder group. <a href="#ae7b58504cc9b3d03e08a966a00dbe830">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e629e6b3fc64e9e58991888cc261e97">clearProcResCounters</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear all counters for processor resources. <a href="#a7e629e6b3fc64e9e58991888cc261e97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84b599fcbdefc8f76b236a35cdd6847e">isFPdOpPreferred_distance</a> (SUnit *SU) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>With the goal of alternating processor sides for stalling (FPd) ops, return true if it seems good to schedule an FPd op next. <a href="#a84b599fcbdefc8f76b236a35cdd6847e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3166d0d38a2703ccf2c03230c12df70">CurGroupDbg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo">SystemZInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4a429442fab944d9d737027ea5f6d81">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8069310005736745d95dd603f8ae459">SchedModel</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab439539e4d60f2f1a209431de606b951">CurrGroupSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of the number of decoder slots used in the current decoder group. <a href="#ab439539e4d60f2f1a209431de606b951">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb87b55493fd0fad87a147643bf3fec9">CurrGroupHas4RegOps</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if an instruction with four reg operands have been scheduled into the current decoder group. <a href="#adb87b55493fd0fad87a147643bf3fec9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa26f64ed9c85aded2324baf7a3cf9749">ProcResourceCounters</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The tracking of resources here are quite similar to the common code use of a critical resource. <a href="#aa26f64ed9c85aded2324baf7a3cf9749">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9de0b11a4016bc65d42441c9846aae78">CriticalResourceIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the resource with the greatest queue, which the scheduler tries to avoid. <a href="#a9de0b11a4016bc65d42441c9846aae78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37ba805975fb51a310d1675a887548c7">LastFPdOpCycleIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LastFPdOpCycleIdx stores the numbeer returned by getCurrCycleIdx() when a stalling operation is scheduled (which uses the FPd resource). <a href="#a37ba805975fb51a310d1675a887548c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a580bd67c37b922dff8c7b04403b0ae55">GrpCount</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A counter of decoder groups scheduled. <a href="#a580bd67c37b922dff8c7b04403b0ae55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3de114d1fd3003d0aae841f14bb83a45">LastEmittedMI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Last emitted instruction or nullptr. <a href="#a3de114d1fd3003d0aae841f14bb83a45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/systemzhazardrecognizer">SystemZHazardRecognizer</a> maintains the state for one MBB during scheduling.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SystemZHazardRecognizer() {#af9591637d45b2fd9b6af0d7ad576b2e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SystemZHazardRecognizer::SystemZHazardRecognizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo">SystemZInstrInfo</a> * tii, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> * SM)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>.</p>


<p>Reference <a href="#a5f2640beef5b132e6c14d9db42e06dd1">Reset</a>.</p>


<p>Referenced by <a href="#a55f00177f4ea5d09fa4d4d88ee3cbc2b">copyState</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### copyState() {#a55f00177f4ea5d09fa4d4d88ee3cbc2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZHazardRecognizer::copyState (<a href="/web-llvm/docs/api/classes/llvm/systemzhazardrecognizer">SystemZHazardRecognizer</a> * Incoming)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copy counters from end of single predecessor.</p>

<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>, definition at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp">SystemZHazardRecognizer.cpp</a>.</p>


<p>References <a href="#ad3166d0d38a2703ccf2c03230c12df70">CurGroupDbg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#af9591637d45b2fd9b6af0d7ad576b2e7">SystemZHazardRecognizer</a>.</p>

</div>
</div>

### dumpCurrGroup() {#ab00ec78da7d69f1c482ceaa59c677fa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZHazardRecognizer::dumpCurrGroup (std::string Msg="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp">SystemZHazardRecognizer.cpp</a>.</p>


<p>References <a href="#ad3166d0d38a2703ccf2c03230c12df70">CurGroupDbg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>.</p>


<p>Referenced by <a href="#ad0f9d37195903c86ebbb9119e9e26fc0">dumpState</a> and <a href="#ae8b6eb92a49f95a3bc79199f0768de4a">EmitInstruction</a>.</p>

</div>
</div>

### dumpProcResourceCounters() {#a0fe3df1038d3bb4ac86cb76e6b5649fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZHazardRecognizer::dumpProcResourceCounters ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>, definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp">SystemZHazardRecognizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>.</p>


<p>Referenced by <a href="#ad0f9d37195903c86ebbb9119e9e26fc0">dumpState</a>.</p>

</div>
</div>

### dumpState() {#ad0f9d37195903c86ebbb9119e9e26fc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZHazardRecognizer::dumpState ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp">SystemZHazardRecognizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ab00ec78da7d69f1c482ceaa59c677fa0">dumpCurrGroup</a> and <a href="#a0fe3df1038d3bb4ac86cb76e6b5649fe">dumpProcResourceCounters</a>.</p>

</div>
</div>

### dumpSU() {#a8a2ae56dfdc087ade919e8712369134a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZHazardRecognizer::dumpSU (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>, definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp">SystemZHazardRecognizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="#a4a0f2858cdd379056abfa2531e7da961">getSchedClass</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a4ac4d36cb59a4bbf5d93513dad0ff0e9">llvm::SUnit::isUnbuffered</a>, <a href="/web-llvm/docs/api/structs/llvm/mcprocresourcedesc/#a51dc4747a7d39650884bcf19daaf5f54">llvm::MCProcResourceDesc::Name</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>.</p>


<p>Referenced by <a href="#ae8b6eb92a49f95a3bc79199f0768de4a">EmitInstruction</a>.</p>

</div>
</div>

### emitInstruction() {#a47377e7e9aaf5a00affe4f4d8ec61f3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZHazardRecognizer::emitInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, bool TakenBranch=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Wrap a non-scheduled instruction in an SU and emit it.</p>

<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>, definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp">SystemZHazardRecognizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae8b6eb92a49f95a3bc79199f0768de4a">EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ab76e4a602699ddc57019efaba62a92b6">llvm::SUnit::hasReservedResource</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp/#a542f07d77adca7a09ec232fb9d8b512b">isBranchRetTrap</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a0be1f84d53e90c247d75f2ed63636761">llvm::SUnit::isCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a4ac4d36cb59a4bbf5d93513dad0ff0e9">llvm::SUnit::isUnbuffered</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### EmitInstruction() {#ae8b6eb92a49f95a3bc79199f0768de4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZHazardRecognizer::EmitInstruction (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *)</td>
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

<p>EmitInstruction - This callback is invoked when an instruction is emitted, to advance the hazard state.</p>

<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>, definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp">SystemZHazardRecognizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad3166d0d38a2703ccf2c03230c12df70">CurGroupDbg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ab00ec78da7d69f1c482ceaa59c677fa0">dumpCurrGroup</a>, <a href="#a8a2ae56dfdc087ade919e8712369134a">dumpSU</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="#a4a0f2858cdd379056abfa2531e7da961">getSchedClass</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a0be1f84d53e90c247d75f2ed63636761">llvm::SUnit::isCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a4ac4d36cb59a4bbf5d93513dad0ff0e9">llvm::SUnit::isUnbuffered</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp/#add988a82ac573f98a34f87d2029aba06">ProcResCostLim</a> and <a href="#a5f2640beef5b132e6c14d9db42e06dd1">Reset</a>.</p>


<p>Referenced by <a href="#a47377e7e9aaf5a00affe4f4d8ec61f3e">emitInstruction</a>.</p>

</div>
</div>

### getHazardType() {#a93f9e5c48a726c5f26603735a3e0a08e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer::HazardType SystemZHazardRecognizer::getHazardType (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *, int Stalls=0)</td>
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

<p>getHazardType - Return the hazard type of emitting this node.</p>


<p>There are three possible results. Either:</p>


<ul class="doxyList ">
<li>NoHazard: it is legal to issue this instruction on this cycle.</li>
<li>Hazard: issuing this instruction would stall the machine. If some other instruction is available, issue it first.</li>
<li>NoopHazard: issuing this instruction would break the program. If some other instruction can be issued, do so, otherwise issue a noop.</li>
</ul>

<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp">SystemZHazardRecognizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a9bec0e329b12bbc503d08db497d43267aad25e3975650edcc9c6fb2917a61dd37">llvm::ScheduleHazardRecognizer::Hazard</a> and <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a9bec0e329b12bbc503d08db497d43267a4e42ac50bfd060349e49904842121cf1">llvm::ScheduleHazardRecognizer::NoHazard</a>.</p>

</div>
</div>

### getLastEmittedMI() {#aa7b41e365774a047ff8decb963b72033}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::SystemZHazardRecognizer::getLastEmittedMI ()</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>.</p>

</div>
</div>

### getSchedClass() {#a4a0f2858cdd379056abfa2531e7da961}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSchedClassDesc * llvm::SystemZHazardRecognizer::getSchedClass (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>Resolves and cache a resolved scheduling class for an <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a2b2c6049e5141829267f4f9193b475d4">llvm::SUnit::SchedClass</a>.</p>


<p>Referenced by <a href="#a8a2ae56dfdc087ade919e8712369134a">dumpSU</a>, <a href="#ae8b6eb92a49f95a3bc79199f0768de4a">EmitInstruction</a>, <a href="#a0fdaca7e15aaaa6d903d0498220b8cc1">groupingCost</a> and <a href="#ab727fc0077d4f6ff1ad7b34cc5d2f069">resourcesCost</a>.</p>

</div>
</div>

### groupingCost() {#a0fdaca7e15aaaa6d903d0498220b8cc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int SystemZHazardRecognizer::groupingCost (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the cost of decoder grouping for SU.</p>


<p>If SU must start a new decoder group, this is negative if this fits the schedule or positive if it would mean ending a group prematurely. For normal instructions this returns 0.</p>


<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>, definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp">SystemZHazardRecognizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a> and <a href="#a4a0f2858cdd379056abfa2531e7da961">getSchedClass</a>.</p>

</div>
</div>

### Reset() {#a5f2640beef5b132e6c14d9db42e06dd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZHazardRecognizer::Reset ()</td>
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

<p>Reset - This callback is invoked when a new block of instructions is about to be schedule.</p>


<p>The hazard state should be set to an initialized state.</p>


<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp">SystemZHazardRecognizer.cpp</a>.</p>


<p>References <a href="#ad3166d0d38a2703ccf2c03230c12df70">CurGroupDbg</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#ae8b6eb92a49f95a3bc79199f0768de4a">EmitInstruction</a> and <a href="#af9591637d45b2fd9b6af0d7ad576b2e7">SystemZHazardRecognizer</a>.</p>

</div>
</div>

### resourcesCost() {#ab727fc0077d4f6ff1ad7b34cc5d2f069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int SystemZHazardRecognizer::resourcesCost (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the cost of SU in regards to processor resources usage.</p>


<p>A positive value means it would be better to wait with SU, while a negative value means it would be good to schedule SU next.</p>


<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>, definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp">SystemZHazardRecognizer.cpp</a>.</p>


<p>References <a href="#a4a0f2858cdd379056abfa2531e7da961">getSchedClass</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a4ac4d36cb59a4bbf5d93513dad0ff0e9">llvm::SUnit::isUnbuffered</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### clearProcResCounters() {#a7e629e6b3fc64e9e58991888cc261e97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZHazardRecognizer::clearProcResCounters ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clear all counters for processor resources.</p>

<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp">SystemZHazardRecognizer.cpp</a>.</p>

</div>
</div>

### fitsIntoCurrentGroup() {#ab9e1a00841b526c5dd7592cf1aa9db5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SystemZHazardRecognizer::fitsIntoCurrentGroup (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if MI fits into current decoder group.</p>

<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp">SystemZHazardRecognizer.cpp</a>.</p>

</div>
</div>

### getCurrCycleIdx() {#ad4e535f0aa753fa6102e686d1fc03d2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SystemZHazardRecognizer::getCurrCycleIdx (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Two decoder groups per cycle are formed (for z13), meaning 2x3 instructions.</p>


<p>This function returns a number between 0 and 5, representing the current decoder slot of the current cycle. If an SU is passed which will begin a new decoder group, the returned value is the cycle index of the next group.</p>


<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp">SystemZHazardRecognizer.cpp</a>.</p>

</div>
</div>

### getCurrGroupSize() {#ad44d438949333878af469740467a5800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SystemZHazardRecognizer::getCurrGroupSize ()</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>.</p>

</div>
</div>

### getNumDecoderSlots() {#a4cd673a97fe8746af526c05f03154849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SystemZHazardRecognizer::getNumDecoderSlots (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>Return the number of decoder slots MI requires.</p>

<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp">SystemZHazardRecognizer.cpp</a>.</p>

</div>
</div>

### has4RegOps() {#ada7467f520d9b075d7f5d3115369cc1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SystemZHazardRecognizer::has4RegOps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this instruction has four register operands.</p>

<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp">SystemZHazardRecognizer.cpp</a>.</p>

</div>
</div>

### isFPdOpPreferred\_distance() {#a84b599fcbdefc8f76b236a35cdd6847e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SystemZHazardRecognizer::isFPdOpPreferred_distance (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>With the goal of alternating processor sides for stalling (FPd) ops, return true if it seems good to schedule an FPd op next.</p>

<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>, definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp">SystemZHazardRecognizer.cpp</a>.</p>

</div>
</div>

### nextGroup() {#ae7b58504cc9b3d03e08a966a00dbe830}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SystemZHazardRecognizer::nextGroup ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Start next decoder group.</p>

<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp">SystemZHazardRecognizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CurGroupDbg {#ad3166d0d38a2703ccf2c03230c12df70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::SystemZHazardRecognizer::CurGroupDbg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>.</p>


<p>Referenced by <a href="#a55f00177f4ea5d09fa4d4d88ee3cbc2b">copyState</a>, <a href="#ab00ec78da7d69f1c482ceaa59c677fa0">dumpCurrGroup</a>, <a href="#ae8b6eb92a49f95a3bc79199f0768de4a">EmitInstruction</a> and <a href="#a5f2640beef5b132e6c14d9db42e06dd1">Reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CriticalResourceIdx {#a9de0b11a4016bc65d42441c9846aae78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SystemZHazardRecognizer::CriticalResourceIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the resource with the greatest queue, which the scheduler tries to avoid.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>.</p>

</div>
</div>

### CurrGroupHas4RegOps {#adb87b55493fd0fad87a147643bf3fec9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SystemZHazardRecognizer::CurrGroupHas4RegOps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if an instruction with four reg operands have been scheduled into the current decoder group.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>.</p>

</div>
</div>

### CurrGroupSize {#ab439539e4d60f2f1a209431de606b951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SystemZHazardRecognizer::CurrGroupSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of the number of decoder slots used in the current decoder group.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>.</p>

</div>
</div>

### GrpCount {#a580bd67c37b922dff8c7b04403b0ae55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SystemZHazardRecognizer::GrpCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A counter of decoder groups scheduled.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>.</p>

</div>
</div>

### LastEmittedMI {#a3de114d1fd3003d0aae841f14bb83a45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* llvm::SystemZHazardRecognizer::LastEmittedMI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Last emitted instruction or nullptr.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>.</p>

</div>
</div>

### LastFPdOpCycleIdx {#a37ba805975fb51a310d1675a887548c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SystemZHazardRecognizer::LastFPdOpCycleIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LastFPdOpCycleIdx stores the numbeer returned by getCurrCycleIdx() when a stalling operation is scheduled (which uses the FPd resource).</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>.</p>

</div>
</div>

### ProcResourceCounters {#aa26f64ed9c85aded2324baf7a3cf9749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;int, 0&gt; llvm::SystemZHazardRecognizer::ProcResourceCounters</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The tracking of resources here are quite similar to the common code use of a critical resource.</p>


<p>However, z13 differs in the way that it has two processor sides which may be interesting to model in the future (a work in progress). Counters for the number of uops scheduled per processor resource.</p>


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>.</p>

</div>
</div>

### SchedModel {#ae8069310005736745d95dd603f8ae459}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetSchedModel* llvm::SystemZHazardRecognizer::SchedModel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>.</p>

</div>
</div>

### TII {#aa4a429442fab944d9d737027ea5f6d81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SystemZInstrInfo* llvm::SystemZHazardRecognizer::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-cpp">SystemZHazardRecognizer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzhazardrecognizer-h">SystemZHazardRecognizer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
