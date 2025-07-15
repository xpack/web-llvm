---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/scoreboardhazardrecognizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ScoreboardHazardRecognizer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::ScoreboardHazardRecognizer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scoreboardhazardrecognizer-h">llvm/CodeGen/ScoreboardHazardRecognizer.h</a>"
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ppcdispatchgroupsbhazardrecognizer">PPCDispatchGroupSBHazardRecognizer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/ppcdispatchgroupsbhazardrecognizer">PPCDispatchGroupSBHazardRecognizer</a> - This class implements a scoreboard-based hazard recognizer for <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> ooo processors with dispatch-group hazards. <a href="/web-llvm/docs/api/classes/llvm/ppcdispatchgroupsbhazardrecognizer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaed3ade868f57d3ccbdc61cb33b88c8a">ScoreboardHazardRecognizer</a> (const InstrItineraryData *II, const ScheduleDAG *DAG, const char *ParentDebugType="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf123a1135fb5aaf6505c367fc1d5fe9">atIssueLimit</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>atIssueLimit - Return true if no more instructions may be issued in this cycle. <a href="#abf123a1135fb5aaf6505c367fc1d5fe9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a9bec0e329b12bbc503d08db497d43267">HazardType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bf3deda3f11f3e49a4e3d735450c69e">getHazardType</a> (SUnit *SU, int Stalls) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getHazardType - Return the hazard type of emitting this node. <a href="#a8bf3deda3f11f3e49a4e3d735450c69e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a059770a7aafc9643d09c5d9e836b1137">Reset</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset - This callback is invoked when a new block of instructions is about to be schedule. <a href="#a059770a7aafc9643d09c5d9e836b1137">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c7714e5d1be43bce0fdcf57217e4414">EmitInstruction</a> (SUnit *SU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitInstruction - This callback is invoked when an instruction is emitted, to advance the hazard state. <a href="#a2c7714e5d1be43bce0fdcf57217e4414">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad16524a56b4cc6839dd8cf8de66ec28b">AdvanceCycle</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AdvanceCycle - This callback is invoked whenever the next top-down instruction to be scheduled cannot issue in the current cycle, either because of latency or resource conflicts. <a href="#ad16524a56b4cc6839dd8cf8de66ec28b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a4ebd25c7fd29c185a1436f39e8aae6">RecedeCycle</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RecedeCycle - This callback is invoked whenever the next bottom-up instruction to be scheduled cannot issue in the current cycle, either because of latency or resource conflicts. <a href="#a4a4ebd25c7fd29c185a1436f39e8aae6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad309ade4f0b4d440d1f5b1e745ead720">DebugType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcec87026b6adc9e1221c2e777d24704">ItinData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa541f686dfe3df3eab06ef5a06d0310">DAG</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad29e68d8305d63b9e065c619a2ca0c86">IssueWidth</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IssueWidth - Max issue per cycle. 0=Unknown. <a href="#ad29e68d8305d63b9e065c619a2ca0c86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab24d12d997f98a798238fc2e91e4ac92">IssueCount</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IssueCount - Count instructions issued in this cycle. <a href="#ab24d12d997f98a798238fc2e91e4ac92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Scoreboard</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4518544a7c74d795ce79240a67fb5a8">ReservedScoreboard</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Scoreboard</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7be9f4f17ae1c8da87a827d5a4f5fa3b">RequiredScoreboard</a></td>
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


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scoreboardhazardrecognizer-h">ScoreboardHazardRecognizer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ScoreboardHazardRecognizer() {#aaed3ade868f57d3ccbdc61cb33b88c8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScoreboardHazardRecognizer::ScoreboardHazardRecognizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * II, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> * DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ParentDebugType="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scoreboardhazardrecognizer-h">ScoreboardHazardRecognizer.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scoreboardhazardrecognizer-cpp">ScoreboardHazardRecognizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcdispatchgroupsbhazardrecognizer/#ae58571459d6d2583ba9ae321ebb64975">llvm::PPCDispatchGroupSBHazardRecognizer::PPCDispatchGroupSBHazardRecognizer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AdvanceCycle() {#ad16524a56b4cc6839dd8cf8de66ec28b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScoreboardHazardRecognizer::AdvanceCycle ()</td>
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

<p>AdvanceCycle - This callback is invoked whenever the next top-down instruction to be scheduled cannot issue in the current cycle, either because of latency or resource conflicts.</p>


<p>This should increment the internal state of the hazard recognizer so that previously "Hazard" instructions will now not be hazards.</p>


<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scoreboardhazardrecognizer-h">ScoreboardHazardRecognizer.h</a>, definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scoreboardhazardrecognizer-cpp">ScoreboardHazardRecognizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcdispatchgroupsbhazardrecognizer/#a1d7b282cd08932b958837df304ab9862">llvm::PPCDispatchGroupSBHazardRecognizer::AdvanceCycle</a>.</p>

</div>
</div>

### atIssueLimit() {#abf123a1135fb5aaf6505c367fc1d5fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScoreboardHazardRecognizer::atIssueLimit ()</td>
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

<p>atIssueLimit - Return true if no more instructions may be issued in this cycle.</p>

<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scoreboardhazardrecognizer-h">ScoreboardHazardRecognizer.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scoreboardhazardrecognizer-cpp">ScoreboardHazardRecognizer.cpp</a>.</p>

</div>
</div>

### EmitInstruction() {#a2c7714e5d1be43bce0fdcf57217e4414}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScoreboardHazardRecognizer::EmitInstruction (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *)</td>
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

<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scoreboardhazardrecognizer-h">ScoreboardHazardRecognizer.h</a>, definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scoreboardhazardrecognizer-cpp">ScoreboardHazardRecognizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/instrstage/#a0c36089f8d92b1bcb9c0a582d42aa106a7774578153e4ca5a7299d1f42395ae6e">llvm::InstrStage::Required</a> and <a href="/web-llvm/docs/api/structs/llvm/instrstage/#a0c36089f8d92b1bcb9c0a582d42aa106adb675fc15885dfb7a1666cc046ac7ba5">llvm::InstrStage::Reserved</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcdispatchgroupsbhazardrecognizer/#afddde8a0bcf92ed759085b411b2238f5">llvm::PPCDispatchGroupSBHazardRecognizer::EmitInstruction</a>.</p>

</div>
</div>

### getHazardType() {#a8bf3deda3f11f3e49a4e3d735450c69e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer::HazardType ScoreboardHazardRecognizer::getHazardType (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *, int Stalls)</td>
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

<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scoreboardhazardrecognizer-h">ScoreboardHazardRecognizer.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scoreboardhazardrecognizer-cpp">ScoreboardHazardRecognizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a9bec0e329b12bbc503d08db497d43267aad25e3975650edcc9c6fb2917a61dd37">llvm::ScheduleHazardRecognizer::Hazard</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a9bec0e329b12bbc503d08db497d43267a4e42ac50bfd060349e49904842121cf1">llvm::ScheduleHazardRecognizer::NoHazard</a>, <a href="/web-llvm/docs/api/structs/llvm/instrstage/#a0c36089f8d92b1bcb9c0a582d42aa106a7774578153e4ca5a7299d1f42395ae6e">llvm::InstrStage::Required</a> and <a href="/web-llvm/docs/api/structs/llvm/instrstage/#a0c36089f8d92b1bcb9c0a582d42aa106adb675fc15885dfb7a1666cc046ac7ba5">llvm::InstrStage::Reserved</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcdispatchgroupsbhazardrecognizer/#a12ecb2c77f447a61153a3037607f2dee">llvm::PPCDispatchGroupSBHazardRecognizer::getHazardType</a>.</p>

</div>
</div>

### RecedeCycle() {#a4a4ebd25c7fd29c185a1436f39e8aae6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScoreboardHazardRecognizer::RecedeCycle ()</td>
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

<p>RecedeCycle - This callback is invoked whenever the next bottom-up instruction to be scheduled cannot issue in the current cycle, either because of latency or resource conflicts.</p>

<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scoreboardhazardrecognizer-h">ScoreboardHazardRecognizer.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scoreboardhazardrecognizer-cpp">ScoreboardHazardRecognizer.cpp</a>.</p>

</div>
</div>

### Reset() {#a059770a7aafc9643d09c5d9e836b1137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScoreboardHazardRecognizer::Reset ()</td>
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


<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scoreboardhazardrecognizer-h">ScoreboardHazardRecognizer.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scoreboardhazardrecognizer-cpp">ScoreboardHazardRecognizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcdispatchgroupsbhazardrecognizer/#af10ef678b8075734a77485c640b1e0e9">llvm::PPCDispatchGroupSBHazardRecognizer::Reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DAG {#aaa541f686dfe3df3eab06ef5a06d0310}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ScheduleDAG* llvm::ScoreboardHazardRecognizer::DAG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scoreboardhazardrecognizer-h">ScoreboardHazardRecognizer.h</a>.</p>

</div>
</div>

### DebugType {#ad309ade4f0b4d440d1f5b1e745ead720}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::ScoreboardHazardRecognizer::DebugType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scoreboardhazardrecognizer-h">ScoreboardHazardRecognizer.h</a>.</p>

</div>
</div>

### IssueCount {#ab24d12d997f98a798238fc2e91e4ac92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ScoreboardHazardRecognizer::IssueCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IssueCount - Count instructions issued in this cycle.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scoreboardhazardrecognizer-h">ScoreboardHazardRecognizer.h</a>.</p>

</div>
</div>

### IssueWidth {#ad29e68d8305d63b9e065c619a2ca0c86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ScoreboardHazardRecognizer::IssueWidth = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IssueWidth - Max issue per cycle. 0=Unknown.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scoreboardhazardrecognizer-h">ScoreboardHazardRecognizer.h</a>.</p>

</div>
</div>

### ItinData {#abcec87026b6adc9e1221c2e777d24704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstrItineraryData* llvm::ScoreboardHazardRecognizer::ItinData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scoreboardhazardrecognizer-h">ScoreboardHazardRecognizer.h</a>.</p>

</div>
</div>

### RequiredScoreboard {#a7be9f4f17ae1c8da87a827d5a4f5fa3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Scoreboard llvm::ScoreboardHazardRecognizer::RequiredScoreboard</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scoreboardhazardrecognizer-h">ScoreboardHazardRecognizer.h</a>.</p>

</div>
</div>

### ReservedScoreboard {#af4518544a7c74d795ce79240a67fb5a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Scoreboard llvm::ScoreboardHazardRecognizer::ReservedScoreboard</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scoreboardhazardrecognizer-h">ScoreboardHazardRecognizer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scoreboardhazardrecognizer-h">ScoreboardHazardRecognizer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/scoreboardhazardrecognizer-cpp">ScoreboardHazardRecognizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
