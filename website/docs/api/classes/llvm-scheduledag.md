---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/scheduledag
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ScheduleDAG` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::ScheduleDAG { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">llvm/CodeGen/ScheduleDAG.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> for scheduling lists of <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bdf35180225e74794f7d23399a3db22">ScheduleDAG</a> (const ScheduleDAG &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2ebc23ff27164ec1d375d4bac6040de">ScheduleDAG</a> (MachineFunction &amp;mf)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40f40bf3808799abdd4411ba209215dc">~ScheduleDAG</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a6dac3959c6817445a767a848061ff7">operator=</a> (const ScheduleDAG &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20e10e20ded7655f844479a648aa0c66">clearDAG</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clears the DAG state (between regions). <a href="#a20e10e20ded7655f844479a648aa0c66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a100d476a583a34879b296908da01fdac">getInstrDesc</a> (const SUnit *SU) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> of this <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>. <a href="#a100d476a583a34879b296908da01fdac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a209b615edbcad3e1a7afd7411ce4eae2">viewGraph</a> (const Twine &amp;Name, const Twine &amp;Title)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pops up a GraphViz/gv window with the <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> rendered using 'dot'. <a href="#a209b615edbcad3e1a7afd7411ce4eae2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e726201ecf499acd7f87ac1d4ff610e">viewGraph</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Out-of-line implementation with no arguments is handy for gdb. <a href="#a7e726201ecf499acd7f87ac1d4ff610e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab76956099f6e90537cfde4b7762289fb">dumpNode</a> (const SUnit &amp;SU) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a782a4cf20870adb67a4c687ad380bbe7">dump</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac464b0883162724583f0f124c8be8157">dumpNodeName</a> (const SUnit &amp;SU) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a6534084b1d6332aeb1cf22cba39c2a">getGraphNodeLabel</a> (const SUnit *SU) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a label for an <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> node in a visualization of the <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a>. <a href="#a2a6534084b1d6332aeb1cf22cba39c2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36e088128012e4d48af65feb75f84c5c">getDAGName</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a label for the region of code covered by the DAG. <a href="#a36e088128012e4d48af65feb75f84c5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab73bd59791820601925b8535b61fba66">addCustomGraphFeatures</a> (GraphWriter&lt; ScheduleDAG * &gt; &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds custom features for a visualization of the <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a>. <a href="#ab73bd59791820601925b8535b61fba66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab464241184b77be167ff521aa2552e29">VerifyScheduledDAG</a> (bool isBottomUp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verifies that all SUnits were scheduled and that their state is consistent. <a href="#ab464241184b77be167ff521aa2552e29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a917f4d40ed0bbdaf4ab50e5df4de067b">dumpNodeAll</a> (const SUnit &amp;SU) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2ffde3e06cc3a83ade2e3261593bb15">getNodeDesc</a> (const SDNode *Node) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> of this <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> or NULL. <a href="#ad2ffde3e06cc3a83ade2e3261593bb15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aa31260fcd6b572eb34528673438c3c">TM</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> processor. <a href="#a9aa31260fcd6b572eb34528673438c3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a348590624c488b04d0f9e227e6c3960e">TII</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> instruction information. <a href="#a348590624c488b04d0f9e227e6c3960e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a418bc6d3f660325fa6d5b9fb269add62">TRI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> processor register info. <a href="#a418bc6d3f660325fa6d5b9fb269add62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a3d3d075a208011a24a0918b58d7daa">MF</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Machine function. <a href="#a5a3d3d075a208011a24a0918b58d7daa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b09f4d9c91e25f7bc2ac60b3b929d11">MRI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Virtual/real register map. <a href="#a1b09f4d9c91e25f7bc2ac60b3b929d11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d5aacd5fc7d6a739ce913974ed1e53d">SUnits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The scheduling units. <a href="#a3d5aacd5fc7d6a739ce913974ed1e53d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a521bf68518a92483130a58680716d153">EntrySU</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Special node for the region entry. <a href="#a521bf68518a92483130a58680716d153">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af81f734d7fb268c95c1c63c399a7c4a6">ExitSU</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Special node for the region exit. <a href="#af81f734d7fb268c95c1c63c399a7c4a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8de65d3a774ee7a23dc72e3d534e6ce6">StressSched</a></td>
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


<p>Definition at line 572 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ScheduleDAG() {#a8bdf35180225e74794f7d23399a3db22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ScheduleDAG::ScheduleDAG (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Reference <a href="#a8bdf35180225e74794f7d23399a3db22">ScheduleDAG</a>.</p>


<p>Referenced by <a href="#a6a6dac3959c6817445a767a848061ff7">operator=</a>, <a href="#a8bdf35180225e74794f7d23399a3db22">ScheduleDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a5bcb745a3e78c329d1431608b1f51c25">llvm::ScheduleDAGInstrs::ScheduleDAGInstrs</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ad73652eab6e03e092e32bde82040c8c7">llvm::ScheduleDAGSDNodes::ScheduleDAGSDNodes</a>.</p>

</div>
</div>

### ScheduleDAG() {#ae2ebc23ff27164ec1d375d4bac6040de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAG::ScheduleDAG (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; mf)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 598 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="#a5a3d3d075a208011a24a0918b58d7daa">MF</a>, <a href="#a1b09f4d9c91e25f7bc2ac60b3b929d11">MRI</a>, <a href="#a8de65d3a774ee7a23dc72e3d534e6ce6">StressSched</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp/#a43ba3e9c0e89d1ee16d4411e15c7e42b">StressSchedOpt</a>, <a href="#a348590624c488b04d0f9e227e6c3960e">TII</a>, <a href="#a9aa31260fcd6b572eb34528673438c3c">TM</a> and <a href="#a418bc6d3f660325fa6d5b9fb269add62">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ScheduleDAG() {#a40f40bf3808799abdd4411ba209215dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAG::~ScheduleDAG ()</td>
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



<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a6a6dac3959c6817445a767a848061ff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAG &amp; llvm::ScheduleDAG::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Reference <a href="#a8bdf35180225e74794f7d23399a3db22">ScheduleDAG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addCustomGraphFeatures() {#ab73bd59791820601925b8535b61fba66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ScheduleDAG::addCustomGraphFeatures (<a href="/web-llvm/docs/api/classes/llvm/graphwriter">GraphWriter</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> * &gt; &amp;)</td>
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

<p>Adds custom features for a visualization of the <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a>.</p>

<p>Definition at line 627 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### clearDAG() {#a20e10e20ded7655f844479a648aa0c66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAG::clearDAG ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clears the DAG state (between regions).</p>

<p>Declaration at line 603 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="#a521bf68518a92483130a58680716d153">EntrySU</a>, <a href="#af81f734d7fb268c95c1c63c399a7c4a6">ExitSU</a> and <a href="#a3d5aacd5fc7d6a739ce913974ed1e53d">SUnits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#aa00d73e05dee6c2701209bac3d7786b8">llvm::ScheduleDAGSDNodes::Run</a> and <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#a587988ffcc944147e5ba7da46bc77ef2">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::schedule</a>.</p>

</div>
</div>

### dump() {#a782a4cf20870adb67a4c687ad380bbe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ScheduleDAG::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### dumpNode() {#ab76956099f6e90537cfde4b7762289fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ScheduleDAG::dumpNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &amp; SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpriorityqueue/#ac71475df20b58e4c313134e73ed1ddad">anonymous{ScheduleDAGRRList.cpp}::RegReductionPriorityQueue&lt; bu_ls_rr_sort &gt;::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/latencypriorityqueue/#a58764f7a88212dcec140c041126b719d">llvm::LatencyPriorityQueue::dump</a>, <a href="#a917f4d40ed0bbdaf4ab50e5df4de067b">dumpNodeAll</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnilpsched-cpp-/gcnilpscheduler/#a701a79471c4c9a778d88f103f3bfdcbf">anonymous{GCNILPSched.cpp}::GCNILPScheduler::schedule</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnminregstrategy-cpp-/gcnminregscheduler/#a34030cdc12b8fc1216cb65aff94d8bab">anonymous{GCNMinRegStrategy.cpp}::GCNMinRegScheduler::schedule</a> and <a href="#ab464241184b77be167ff521aa2552e29">VerifyScheduledDAG</a>.</p>

</div>
</div>

### dumpNodeName() {#ac464b0883162724583f0f124c8be8157}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void ScheduleDAG::dumpNodeName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &amp; SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a521bf68518a92483130a58680716d153">EntrySU</a>, <a href="#af81f734d7fb268c95c1c63c399a7c4a6">ExitSU</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#aa5f22315c4064579fca6cd88fb36ea5a">llvm::ScheduleDAGInstrs::dumpNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ab34667f1d218ea0b6566dd8f861dfe93">llvm::ScheduleDAGSDNodes::dumpNode</a>, <a href="#a917f4d40ed0bbdaf4ab50e5df4de067b">dumpNodeAll</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a632225d89acaea2e95ea6f71b19d3ecf">llvm::fuseInstructionPair</a>.</p>

</div>
</div>

### getDAGName() {#a36e088128012e4d48af65feb75f84c5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::string llvm::ScheduleDAG::getDAGName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a label for the region of code covered by the DAG.</p>

<p>Definition at line 624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="#a7e726201ecf499acd7f87ac1d4ff610e">viewGraph</a>.</p>

</div>
</div>

### getGraphNodeLabel() {#a2a6534084b1d6332aeb1cf22cba39c2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::string llvm::ScheduleDAG::getGraphNodeLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a label for an <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> node in a visualization of the <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a>.</p>

<p>Definition at line 621 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### getInstrDesc() {#a100d476a583a34879b296908da01fdac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCInstrDesc * llvm::ScheduleDAG::getInstrDesc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> of this <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a>.</p>


<p>Returns NULL for SDNodes without a machine opcode.</p>


<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a75a5f7e3b3d4ec79610b4e556d2f35ce">llvm::MachineInstr::getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ac42c5c2e2899b5e891477e415a045503">llvm::SUnit::getNode</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a274909b1f31ad2d3d3379de55467d377">llvm::SUnit::isInstr</a>.</p>

</div>
</div>

### VerifyScheduledDAG() {#ab464241184b77be167ff521aa2552e29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ScheduleDAG::VerifyScheduledDAG (bool isBottomUp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verifies that all SUnits were scheduled and that their state is consistent.</p>


<p>Returns the number of scheduled SUnits.</p>


<p>Declaration at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ab76956099f6e90537cfde4b7762289fb">dumpNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8926b25df7254ba2730fa5d7ec139862">llvm::SUnit::getDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a582da862b28b876ef2235781392cffa6">llvm::SUnit::getHeight</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8c201d7a769bda1cd75d8d6788123068">llvm::SUnit::isScheduled</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a25329a072c76c185b8c5ff530c632762">llvm::SUnit::NumPreds</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a94f78042fbba3ea4cd1004353daa46aa">llvm::SUnit::NumPredsLeft</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a1a6c1a29019b8f3fd988359ec5dd3d2f">llvm::SUnit::NumSuccs</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a40c2dfbd170941dd4d20ee9b60c9d49d">llvm::SUnit::NumSuccsLeft</a> and <a href="#a3d5aacd5fc7d6a739ce913974ed1e53d">SUnits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a4b8c5a6f17aa50ecc8f64f74d4ba5e47">llvm::ScheduleDAGSDNodes::VerifyScheduledSequence</a>.</p>

</div>
</div>

### viewGraph() {#a209b615edbcad3e1a7afd7411ce4eae2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAG::viewGraph (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Title)</td>
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

<p>Pops up a GraphViz/gv window with the <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> rendered using 'dot'.</p>


<p>viewGraph - Pop up a ghostview window with the reachable parts of the DAG rendered using 'dot'.</p>


<p>Declaration at line 613 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledagprinter-cpp">ScheduleDAGPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab8635363d4287c93f64c55ad5567fcf0">llvm::ViewGraph</a>.</p>

</div>
</div>

### viewGraph() {#a7e726201ecf499acd7f87ac1d4ff610e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAG::viewGraph ()</td>
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

<p>Out-of-line implementation with no arguments is handy for gdb.</p>

<p>Declaration at line 614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledagprinter-cpp">ScheduleDAGPrinter.cpp</a>.</p>


<p>References <a href="#a36e088128012e4d48af65feb75f84c5c">getDAGName</a> and <a href="#a7e726201ecf499acd7f87ac1d4ff610e">viewGraph</a>.</p>


<p>Referenced by <a href="#a7e726201ecf499acd7f87ac1d4ff610e">viewGraph</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### dumpNodeAll() {#a917f4d40ed0bbdaf4ab50e5df4de067b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void ScheduleDAG::dumpNodeAll (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &amp; SU)</td>
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



<p>Declaration at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#ace1019e8cefb80490348369f12fe0a44">llvm::SDep::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#aab2e2064b4bde0d5487ddc0d0982f5b9">llvm::SUnit::dumpAttributes</a>, <a href="#ab76956099f6e90537cfde4b7762289fb">dumpNode</a>, <a href="#ac464b0883162724583f0f124c8be8157">dumpNodeName</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#aab4a86c51e6b126c9c6ef58dbb574431">llvm::SUnit::Succs</a> and <a href="#a418bc6d3f660325fa6d5b9fb269add62">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#aea2d4ef1e00ee834ab155abd18a560e4">llvm::ScheduleDAGInstrs::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#add5e3e74f2db8e669b830ae35edc8c02">llvm::ScheduleDAGMILive::dump</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#aacd9b18c4caf8c84e5bf1e9912f44022">llvm::ScheduleDAGSDNodes::dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getNodeDesc() {#ad2ffde3e06cc3a83ade2e3261593bb15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCInstrDesc * ScheduleDAG::getNodeDesc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> of this <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> or NULL.</p>

<p>Declaration at line 640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### EntrySU {#a521bf68518a92483130a58680716d153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit llvm::ScheduleDAG::EntrySU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Special node for the region entry.</p>

<p>Definition at line 580 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="#a20e10e20ded7655f844479a648aa0c66">clearDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#aea2d4ef1e00ee834ab155abd18a560e4">llvm::ScheduleDAGInstrs::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#add5e3e74f2db8e669b830ae35edc8c02">llvm::ScheduleDAGMILive::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#aacd9b18c4caf8c84e5bf1e9912f44022">llvm::ScheduleDAGSDNodes::dump</a>, <a href="#ac464b0883162724583f0f124c8be8157">dumpNodeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a632225d89acaea2e95ea6f71b19d3ecf">llvm::fuseInstructionPair</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a0eec08caac9b208bbb7bb95ed0e90f8f">llvm::SIScheduleDAGMI::getEntrySU</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#afbb37cc24abd3ed381b0fd496351bd17">llvm::ScheduleDAGInstrs::getGraphNodeLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a1f98694f104d052d71ed74ade38d69f0">llvm::ScheduleDAGMI::initQueues</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a1c51776d4e512a7f24d5b5d601c31016">llvm::ScheduleDAGMI::releasePred</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnminregstrategy-cpp-/gcnminregscheduler/#a34030cdc12b8fc1216cb65aff94d8bab">anonymous{GCNMinRegStrategy.cpp}::GCNMinRegScheduler::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a87416d44c85818861fe0152759e9acb1">llvm::SwingSchedulerDAG::schedule</a>.</p>

</div>
</div>

### ExitSU {#af81f734d7fb268c95c1c63c399a7c4a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit llvm::ScheduleDAG::ExitSU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Special node for the region exit.</p>

<p>Definition at line 581 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a86bfa4838cb7e42648615d27c94c8017">llvm::ScheduleDAGInstrs::addEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2e9425c046cf742bfbb9ebb96466d8e5">llvm::ScheduleDAGInstrs::addPhysRegDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ae8625c1e6c9bc82f2eaef39d3fff65a8">llvm::ScheduleDAGInstrs::addSchedBarrierDeps</a>, <a href="/web-llvm/docs/api/classes/anonymous-macrofusion-cpp-/macrofusion/#a0118b89885857d60368b7bdfe36f268d">anonymous{MacroFusion.cpp}::MacroFusion::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#ad05686602c5ba519cd9fdaf2dad9bed8">llvm::ARMOverrideBypasses::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ac384df17605ecce542a6d2567c7f1ee0">llvm::ScheduleDAGInstrs::canAddEdge</a>, <a href="#a20e10e20ded7655f844479a648aa0c66">clearDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a7bb19d3e5b68421bc97c3c4b524e7888">llvm::ScheduleDAGMILive::computeCyclicCriticalPath</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#aea2d4ef1e00ee834ab155abd18a560e4">llvm::ScheduleDAGInstrs::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#add5e3e74f2db8e669b830ae35edc8c02">llvm::ScheduleDAGMILive::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#aacd9b18c4caf8c84e5bf1e9912f44022">llvm::ScheduleDAGSDNodes::dump</a>, <a href="#ac464b0883162724583f0f124c8be8157">dumpNodeName</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a6d0a0b4903e8d4d12c98b0f43fe83878">llvm::ScheduleDAGMI::findRootsAndBiasEdges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a632225d89acaea2e95ea6f71b19d3ecf">llvm::fuseInstructionPair</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a9fb8e9a77f63588d8ab5136847bbd7fc">llvm::SIScheduleDAGMI::getExitSU</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#afbb37cc24abd3ed381b0fd496351bd17">llvm::ScheduleDAGInstrs::getGraphNodeLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a1f98694f104d052d71ed74ade38d69f0">llvm::ScheduleDAGMI::initQueues</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a90ffd918ef80c711049758b2064e15c4">llvm::ScheduleDAGMI::releaseSucc</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnilpsched-cpp-/gcnilpscheduler/#a701a79471c4c9a778d88f103f3bfdcbf">anonymous{GCNILPSched.cpp}::GCNILPScheduler::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a87416d44c85818861fe0152759e9acb1">llvm::SwingSchedulerDAG::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a5bcb745a3e78c329d1431608b1f51c25">llvm::ScheduleDAGInstrs::ScheduleDAGInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a682039af4aa49f562ba74775bc32b1c4">llvm::SwingSchedulerDAG::SwingSchedulerDAG</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a91251ec06d557b21578095955b7b7fa7">llvm::ScheduleDAGMILive::updatePressureDiffs</a>.</p>

</div>
</div>

### MF {#a5a3d3d075a208011a24a0918b58d7daa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; llvm::ScheduleDAG::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Machine function.</p>

<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a56fbc3f460289602ce8a51538ebc1e26">llvm::ScheduleDAGInstrs::addPhysRegDataDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2e9425c046cf742bfbb9ebb96466d8e5">llvm::ScheduleDAGInstrs::addPhysRegDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a10acc9310a21d9a8191d3d84916bdffb">llvm::ScheduleDAGInstrs::addVRegDefDeps</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/igrouplpdagmutation/#a80af98abec842dd9dd5261853ec76735">anonymous{AMDGPUIGroupLP.cpp}::IGroupLPDAGMutation::apply</a>, <a href="/web-llvm/docs/api/structs/anonymous-gcnvopdutils-cpp-/vopdpairingmutation/#a397f99588bac91a2e8776d2719fa97fc">anonymous{GCNVOPDUtils.cpp}::VOPDPairingMutation::apply</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/callmutation/#a6cd9122ce8216f80dd0921f844f7b7e1">llvm::HexagonSubtarget::CallMutation::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a3fa089137317e93276cab5774d4bf11f">llvm::SwingSchedulerDAG::applyInstrChange</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a4be5ffcd4f76d433cc753be146a872b7">llvm::ScheduleDAGMILive::buildDAGWithRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a3fb8c57a2275283cbb376004421318da">computeLiveOuts</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a4ab6232188433548694ea1a9a98d542f">llvm::SIInstrInfo::CreateTargetMIHazardRecognizer</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a63d1433613d2b51a9c6389a63ccd2cce">llvm::PPCInstrInfo::CreateTargetPostRAHazardRecognizer</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ab56dfc46c9da130d7a7e06d7d6588164">llvm::SIInstrInfo::CreateTargetPostRAHazardRecognizer</a>, <a href="/web-llvm/docs/api/classes/llvm/defaultvliwscheduler/#a7c1a62bfba2908fff478bff6b2242d23">llvm::DefaultVLIWScheduler::DefaultVLIWScheduler</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6f60ed03227dbeb711a3ae9b1f0238e9">llvm::ScheduleDAGSDNodes::EmitSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a47f63b6ab42a97ca3b5346b6c7093b09">llvm::SwingSchedulerDAG::finishBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a51bda1806219d879123625c8d4ae3fbc">llvm::SwingSchedulerDAG::fixupRegisterOverlaps</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnscheduledagmilive/#a586d595322e6cb11cc1663b937d9aca7">llvm::GCNScheduleDAGMILive::GCNScheduleDAGMILive</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a86daf2b1fb72fdd9a8785a4042ac1457">llvm::ScheduleDAGMILive::initRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#ab6c5bda21b39ff9494fc2661de4aa974">llvm::SIScheduleDAGMI::initRPTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a78e274f7aa81fdeddac470d645c3c6e8">llvm::SwingSchedulerDAG::isLoopCarriedDep</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#a70f01da7bffd10dc0686e3ca4286eac8">llvm::GCNIterativeScheduler::printRegions</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#a0cb97aff651ff2a97a061183a62dfc01">llvm::GCNIterativeScheduler::printSchedRP</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a87416d44c85818861fe0152759e9acb1">llvm::SwingSchedulerDAG::schedule</a>, <a href="#ae2ebc23ff27164ec1d375d4bac6040de">ScheduleDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a629982ca3ef5632e63f32b5682fde927">llvm::ScheduleDAGMI::ScheduleDAGMI</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagvliw-cpp-/scheduledagvliw/#a7dc43d4af0801e27b6c6273882f2e417">anonymous{ScheduleDAGVLIW.cpp}::ScheduleDAGVLIW::ScheduleDAGVLIW</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#a424a74f8852d22b010e48f8f6d0c748d">llvm::GCNIterativeScheduler::scheduleILP</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#a9d479174d357214e5ea495943b55fdd2">llvm::GCNIterativeScheduler::scheduleLegacyMaxOccupancy</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#ab7d457cdee60c23701eca3d110a4862f">llvm::GCNIterativeScheduler::scheduleMinReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#a66dc7adbddb415df7082c38835b96372">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::SchedulePostRATDList</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#ad899858c4b90e464815c32a7f9c4bb26">llvm::GCNIterativeScheduler::scheduleRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#a19e2ffc6c8269a09ca18d5255ec2345a">llvm::GCNIterativeScheduler::sortRegionsByPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a682039af4aa49f562ba74775bc32b1c4">llvm::SwingSchedulerDAG::SwingSchedulerDAG</a> and <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#a6fd0550f564608fec7c5d7f25817ddef">llvm::GCNIterativeScheduler::tryMaximizeOccupancy</a>.</p>

</div>
</div>

### MRI {#a1b09f4d9c91e25f7bc2ac60b3b929d11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; llvm::ScheduleDAG::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Virtual/real register map.</p>

<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2e9425c046cf742bfbb9ebb96466d8e5">llvm::ScheduleDAGInstrs::addPhysRegDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a10acc9310a21d9a8191d3d84916bdffb">llvm::ScheduleDAGInstrs::addVRegDefDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a65716b8ea88f6ffb38b7f87fe4ee23ab">llvm::SIScheduleDAGMI::fillVgprSgprCost</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a4dc06d4fb42d48a6ade1958f76334826">llvm::ScheduleDAGInstrs::fixupKills</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a643ff7dd8c287dd58e75cbe79556e74c">llvm::ScheduleDAGInstrs::getLaneMaskForMO</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a6c00bda859fc30b13be64312fd6cffc6">llvm::SIScheduleDAGMI::getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a86daf2b1fb72fdd9a8785a4042ac1457">llvm::ScheduleDAGMILive::initRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a78e274f7aa81fdeddac470d645c3c6e8">llvm::SwingSchedulerDAG::isLoopCarriedDep</a>, <a href="#ae2ebc23ff27164ec1d375d4bac6040de">ScheduleDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a04a2c04f918397dbac27a79e58807136">llvm::ScheduleDAGMILive::scheduleMI</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#ad899858c4b90e464815c32a7f9c4bb26">llvm::GCNIterativeScheduler::scheduleRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a91251ec06d557b21578095955b7b7fa7">llvm::ScheduleDAGMILive::updatePressureDiffs</a>.</p>

</div>
</div>

### StressSched {#a8de65d3a774ee7a23dc72e3d534e6ce6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScheduleDAG::StressSched</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-scheduledagrrlist-cpp-/#a96c546d93150af354156242010c94501">anonymous{ScheduleDAGRRList.cpp}::popFromQueue</a> and <a href="#ae2ebc23ff27164ec1d375d4bac6040de">ScheduleDAG</a>.</p>

</div>
</div>

### SUnits {#a3d5aacd5fc7d6a739ce913974ed1e53d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SUnit&gt; llvm::ScheduleDAG::SUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The scheduling units.</p>

<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuexportclustering-cpp-/exportclustering/#a3432dbdb86f0a5f40c9d3bcfd8633b28">anonymous{AMDGPUExportClustering.cpp}::ExportClustering::apply</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/igrouplpdagmutation/#a80af98abec842dd9dd5261853ec76735">anonymous{AMDGPUIGroupLP.cpp}::IGroupLPDAGMutation::apply</a>, <a href="/web-llvm/docs/api/structs/anonymous-gcnvopdutils-cpp-/vopdpairingmutation/#a397f99588bac91a2e8776d2719fa97fc">anonymous{GCNVOPDUtils.cpp}::VOPDPairingMutation::apply</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/basememopclustermutation/#a0c7442486454c55b94469e8b7c8ab468">anonymous{MachineScheduler.cpp}::BaseMemOpClusterMutation::apply</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#af6b0c8c54226e0aafa107e5e92c813a2">anonymous{MachineScheduler.cpp}::CopyConstrain::apply</a>, <a href="/web-llvm/docs/api/classes/anonymous-macrofusion-cpp-/macrofusion/#a0118b89885857d60368b7bdfe36f268d">anonymous{MacroFusion.cpp}::MacroFusion::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#ad05686602c5ba519cd9fdaf2dad9bed8">llvm::ARMOverrideBypasses::apply</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/bankconflictmutation/#a336138bbbfacbbb4be8c56d41f08b0c2">llvm::HexagonSubtarget::BankConflictMutation::apply</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/callmutation/#a6cd9122ce8216f80dd0921f844f7b7e1">llvm::HexagonSubtarget::CallMutation::apply</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/hvxmemlatencymutation/#a9c1fcebee584af05ce009b20aeab417b">llvm::HexagonSubtarget::HVXMemLatencyMutation::apply</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/usroverflowmutation/#af2918620aeda858e99c7fac5f1e9eb16">llvm::HexagonSubtarget::UsrOverflowMutation::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvvectormaskdagmutation/#aefb8f35660662022da36962fb6655058">llvm::RISCVVectorMaskDAGMutation::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="#a20e10e20ded7655f844479a648aa0c66">clearDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsresult/#a788b324b6deb10dfbafa68a351b11c79">llvm::SchedDFSResult::compute</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a21c7721fcb12ebb55872b86d33e61e27">llvm::ScheduleDAGMILive::computeDFSResult</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a23d6b914952799027040a351f501a0ad">llvm::SMSchedule::computeUnpipelineableNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#aea2d4ef1e00ee834ab155abd18a560e4">llvm::ScheduleDAGInstrs::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#add5e3e74f2db8e669b830ae35edc8c02">llvm::ScheduleDAGMILive::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#aacd9b18c4caf8c84e5bf1e9912f44022">llvm::ScheduleDAGSDNodes::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#aff7649124c08f77b72e5d539f2f8afdf">llvm::SMSchedule::finalizeSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a6d0a0b4903e8d4d12c98b0f43fe83878">llvm::ScheduleDAGMI::findRootsAndBiasEdges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a632225d89acaea2e95ea6f71b19d3ecf">llvm::fuseInstructionPair</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a0923f09dc063b0d957449c45c562ca08">llvm::ScheduleDAGSDNodes::getCustomGraphFeatures</a>, <a href="/web-llvm/docs/api/classes/llvm/windowscheduler/#a8b0679e70ea74a5f5f3a7fe8060a86e6">llvm::WindowScheduler::getEstimatedII</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/basememopclustermutation/#a456ce65cd7eb7154bc9a1460dcd3eb4a">anonymous{MachineScheduler.cpp}::BaseMemOpClusterMutation::groupMemOps</a>, <a href="/web-llvm/docs/api/structs/llvm/schedremainder/#a55cad625d59b0f4452d893b4a25c66b6">llvm::SchedRemainder::init</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a86daf2b1fb72fdd9a8785a4042ac1457">llvm::ScheduleDAGMILive::initRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a705a0975de8335b0b6bdbbae165e8f5c">llvm::ScheduleDAGInstrs::initSUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a7c7d5ab8d9814b721a1844a867ef948a">llvm::SMSchedule::isValidSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a6c497ec4b863f7d59aa3678740331c8e">llvm::ScheduleDAGInstrs::newSUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a15c0200b4b6e12b97d270fbea215443e">llvm::ScheduleDAGSDNodes::newSUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#ae26138aceef07cf5465c2840b437e1d8">llvm::SMSchedule::normalizeNonPipelinedInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2e28b826aaa73d2dacf89ba8f8c775d1">llvm::ScheduleDAGInstrs::reduceHugeMemNodeMaps</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a10557b7d33ea079f0523cac41ef279b8">llvm::SIScheduleDAGMI::restoreSULinksLeft</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/scheduledagrrlist/#a9f958f8f55c3516c1b509f9c49cb0923">anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::Schedule</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagvliw-cpp-/scheduledagvliw/#a8c7e5ab6f65268a493c98bdf5b7ada2f">anonymous{ScheduleDAGVLIW.cpp}::ScheduleDAGVLIW::Schedule</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnminregstrategy-cpp-/gcnminregscheduler/#a34030cdc12b8fc1216cb65aff94d8bab">anonymous{GCNMinRegStrategy.cpp}::GCNMinRegScheduler::schedule</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#a587988ffcc944147e5ba7da46bc77ef2">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a87416d44c85818861fe0152759e9acb1">llvm::SwingSchedulerDAG::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwmachinescheduler/#ad25e72e64bc7ed157b69c60e85b4061e">llvm::VLIWMachineScheduler::schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a5bcb745a3e78c329d1431608b1f51c25">llvm::ScheduleDAGInstrs::ScheduleDAGInstrs</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/scheduledagrrlist/#a2ddd224f4d981bb2a8ceb7d5c977f392">anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::ScheduleDAGRRList</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a682039af4aa49f562ba74775bc32b1c4">llvm::SwingSchedulerDAG::SwingSchedulerDAG</a> and <a href="#ab464241184b77be167ff521aa2552e29">VerifyScheduledDAG</a>.</p>

</div>
</div>

### TII {#a348590624c488b04d0f9e227e6c3960e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* llvm::ScheduleDAG::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> instruction information.</p>

<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuexportclustering-cpp-/exportclustering/#a3432dbdb86f0a5f40c9d3bcfd8633b28">anonymous{AMDGPUExportClustering.cpp}::ExportClustering::apply</a>, <a href="/web-llvm/docs/api/structs/anonymous-gcnvopdutils-cpp-/vopdpairingmutation/#a397f99588bac91a2e8776d2719fa97fc">anonymous{GCNVOPDUtils.cpp}::VOPDPairingMutation::apply</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/bankconflictmutation/#a336138bbbfacbbb4be8c56d41f08b0c2">llvm::HexagonSubtarget::BankConflictMutation::apply</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/hvxmemlatencymutation/#a9c1fcebee584af05ce009b20aeab417b">llvm::HexagonSubtarget::HVXMemLatencyMutation::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a3fa089137317e93276cab5774d4bf11f">llvm::SwingSchedulerDAG::applyInstrChange</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6ab45d1027ab01be9c371634c49d077b">llvm::ScheduleDAGSDNodes::computeLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ae7e825d2af275c631d66e063c4eff615">llvm::ScheduleDAGSDNodes::computeOperandLatency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5365898dd1deb10d065e288a2babd511">llvm::createGenericSchedLive</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#a407041e55fa1f623a4ffa56436b5606b">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::createMachineScheduler</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#abc91f335d0788469b44e409f15109585">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createPostMachineScheduler</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#a981486e15f588bdbce922588c8efc899">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::createPostMachineScheduler</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a63d1433613d2b51a9c6389a63ccd2cce">llvm::PPCInstrInfo::CreateTargetPostRAHazardRecognizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#aab77d912a7ea86c5c77bc6eacb9adca6">createVLIWMachineSched</a>, <a href="/web-llvm/docs/api/classes/anonymous-postraschedulerlist-cpp-/schedulepostratdlist/#ab9c7e76fda2b142c09da3ca892884acd">anonymous{PostRASchedulerList.cpp}::SchedulePostRATDList::EmitSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6f60ed03227dbeb711a3ae9b1f0238e9">llvm::ScheduleDAGSDNodes::EmitSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a51bda1806219d879123625c8d4ae3fbc">llvm::SwingSchedulerDAG::fixupRegisterOverlaps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a632225d89acaea2e95ea6f71b19d3ecf">llvm::fuseInstructionPair</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a78e274f7aa81fdeddac470d645c3c6e8">llvm::SwingSchedulerDAG::isLoopCarriedDep</a>, <a href="#ae2ebc23ff27164ec1d375d4bac6040de">ScheduleDAG</a> and <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a771c24fd27edfc5b9fdf7ae8422cc236">llvm::SIScheduleDAGMI::SIScheduleDAGMI</a>.</p>

</div>
</div>

### TM {#a9aa31260fcd6b572eb34528673438c3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetMachine&amp; llvm::ScheduleDAG::TM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> processor.</p>

<p>Definition at line 574 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="#ae2ebc23ff27164ec1d375d4bac6040de">ScheduleDAG</a>.</p>

</div>
</div>

### TRI {#a418bc6d3f660325fa6d5b9fb269add62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::ScheduleDAG::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> processor register info.</p>

<p>Definition at line 576 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a56fbc3f460289602ce8a51538ebc1e26">llvm::ScheduleDAGInstrs::addPhysRegDataDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2e9425c046cf742bfbb9ebb96466d8e5">llvm::ScheduleDAGInstrs::addPhysRegDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ae8625c1e6c9bc82f2eaef39d3fff65a8">llvm::ScheduleDAGInstrs::addSchedBarrierDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5365898dd1deb10d065e288a2babd511">llvm::createGenericSchedLive</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#a407041e55fa1f623a4ffa56436b5606b">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::createMachineScheduler</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#abc91f335d0788469b44e409f15109585">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createPostMachineScheduler</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#a981486e15f588bdbce922588c8efc899">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::createPostMachineScheduler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#aab77d912a7ea86c5c77bc6eacb9adca6">createVLIWMachineSched</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#add5e3e74f2db8e669b830ae35edc8c02">llvm::ScheduleDAGMILive::dump</a>, <a href="#a917f4d40ed0bbdaf4ab50e5df4de067b">dumpNodeAll</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a4dc06d4fb42d48a6ade1958f76334826">llvm::ScheduleDAGInstrs::fixupKills</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a643ff7dd8c287dd58e75cbe79556e74c">llvm::ScheduleDAGInstrs::getLaneMaskForMO</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#ae6da1408d8eb00d050466f094399b4b7">llvm::SIScheduleDAGMI::getTRI</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a86daf2b1fb72fdd9a8785a4042ac1457">llvm::ScheduleDAGMILive::initRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a78e274f7aa81fdeddac470d645c3c6e8">llvm::SwingSchedulerDAG::isLoopCarriedDep</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagfast-cpp-/scheduledagfast/#a9a28e48e75f92766aa6a1c3b628536c3">anonymous{ScheduleDAGFast.cpp}::ScheduleDAGFast::Schedule</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/scheduledagrrlist/#a9f958f8f55c3516c1b509f9c49cb0923">anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::Schedule</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a543aa30430f7e566cc4baa20b271f377">llvm::SIScheduleDAGMI::schedule</a>, <a href="#ae2ebc23ff27164ec1d375d4bac6040de">ScheduleDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a04a2c04f918397dbac27a79e58807136">llvm::ScheduleDAGMILive::scheduleMI</a>, <a href="/web-llvm/docs/api/classes/llvm/gcniterativescheduler/#ad899858c4b90e464815c32a7f9c4bb26">llvm::GCNIterativeScheduler::scheduleRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/sischeduledagmi/#a771c24fd27edfc5b9fdf7ae8422cc236">llvm::SIScheduleDAGMI::SIScheduleDAGMI</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a91251ec06d557b21578095955b7b7fa7">llvm::ScheduleDAGMILive::updatePressureDiffs</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a556d08e5789e4c99bb9c24aa4e226f9b">llvm::ScheduleDAGMILive::updateScheduledPressure</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledagprinter-cpp">ScheduleDAGPrinter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
