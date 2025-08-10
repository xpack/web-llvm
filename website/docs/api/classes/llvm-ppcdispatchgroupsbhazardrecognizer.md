---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ppcdispatchgroupsbhazardrecognizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PPCDispatchGroupSBHazardRecognizer` Class

<p><a href="/web-llvm/docs/api/classes/llvm/ppcdispatchgroupsbhazardrecognizer">PPCDispatchGroupSBHazardRecognizer</a> - This class implements a scoreboard-based hazard recognizer for <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> ooo processors with dispatch-group hazards. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PPCDispatchGroupSBHazardRecognizer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">Target/PowerPC/PPCHazardRecognizers.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scoreboardhazardrecognizer">ScoreboardHazardRecognizer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae58571459d6d2583ba9ae321ebb64975">PPCDispatchGroupSBHazardRecognizer</a> (const InstrItineraryData *ItinData, const ScheduleDAG *DAG_)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12ecb2c77f447a61153a3037607f2dee">getHazardType</a> (SUnit *SU, int Stalls) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getHazardType - Return the hazard type of emitting this node. <a href="#a12ecb2c77f447a61153a3037607f2dee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a747d30e23a3b40029d13eef9703dc9f7">ShouldPreferAnother</a> (SUnit *SU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ShouldPreferAnother - This callback may be invoked if getHazardType returns NoHazard. <a href="#a747d30e23a3b40029d13eef9703dc9f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57749af083c14fb007c14bd27ab53e8d">PreEmitNoops</a> (SUnit *SU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PreEmitNoops - This callback is invoked prior to emitting an instruction. <a href="#a57749af083c14fb007c14bd27ab53e8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afddde8a0bcf92ed759085b411b2238f5">EmitInstruction</a> (SUnit *SU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitInstruction - This callback is invoked when an instruction is emitted, to advance the hazard state. <a href="#afddde8a0bcf92ed759085b411b2238f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d7b282cd08932b958837df304ab9862">AdvanceCycle</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AdvanceCycle - This callback is invoked whenever the next top-down instruction to be scheduled cannot issue in the current cycle, either because of latency or resource conflicts. <a href="#a1d7b282cd08932b958837df304ab9862">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a37f926652da651355e009f5b33cc85">RecedeCycle</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RecedeCycle - This callback is invoked whenever the next bottom-up instruction to be scheduled cannot issue in the current cycle, either because of latency or resource conflicts. <a href="#a6a37f926652da651355e009f5b33cc85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af10ef678b8075734a77485c640b1e0e9">Reset</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset - This callback is invoked when a new block of instructions is about to be schedule. <a href="#af10ef678b8075734a77485c640b1e0e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3ba05e93144e92aaeb9cd99504d0147">EmitNoop</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitNoop - This callback is invoked when a noop was added to the instruction stream. <a href="#ae3ba05e93144e92aaeb9cd99504d0147">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92d0f51581163425bf76d956bf6dd632">isLoadAfterStore</a> (SUnit *SU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91460af17105aaadfbd3e128075e2cdc">isBCTRAfterSet</a> (SUnit *SU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0002833d82374fce9a289536e7843d8b">mustComeFirst</a> (const MCInstrDesc *MCID, unsigned &amp;NSlots)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e7d2e42649d0495269701bf0dae19aa">DAG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *, 7 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe5c1a52e421f78ed82a5d91c5654253">CurGroup</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d986f0478676f664dab046d7d954ebe">CurSlots</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a215eebf24b933377578bd604e9809efb">CurBranches</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/ppcdispatchgroupsbhazardrecognizer">PPCDispatchGroupSBHazardRecognizer</a> - This class implements a scoreboard-based hazard recognizer for <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> ooo processors with dispatch-group hazards.</p>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PPCDispatchGroupSBHazardRecognizer() {#ae58571459d6d2583ba9ae321ebb64975}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PPCDispatchGroupSBHazardRecognizer::PPCDispatchGroupSBHazardRecognizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> * DAG_)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scoreboardhazardrecognizer/#aaed3ade868f57d3ccbdc61cb33b88c8a">llvm::ScoreboardHazardRecognizer::ScoreboardHazardRecognizer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AdvanceCycle() {#a1d7b282cd08932b958837df304ab9862}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCDispatchGroupSBHazardRecognizer::AdvanceCycle ()</td>
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


<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>, definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scoreboardhazardrecognizer/#ad16524a56b4cc6839dd8cf8de66ec28b">llvm::ScoreboardHazardRecognizer::AdvanceCycle</a>.</p>

</div>
</div>

### EmitInstruction() {#afddde8a0bcf92ed759085b411b2238f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCDispatchGroupSBHazardRecognizer::EmitInstruction (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *)</td>
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

<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/scoreboardhazardrecognizer/#a2c7714e5d1be43bce0fdcf57217e4414">llvm::ScoreboardHazardRecognizer::EmitInstruction</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### EmitNoop() {#ae3ba05e93144e92aaeb9cd99504d0147}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCDispatchGroupSBHazardRecognizer::EmitNoop ()</td>
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

<p>EmitNoop - This callback is invoked when a noop was added to the instruction stream.</p>

<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>, definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34aa2b626cb4809ee8a3b3da9d475eabe05">llvm::PPC::DIR_PWR6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a0c8a5dd168df904e8c29520a47502a61">llvm::PPC::DIR_PWR7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34aa3de856d909c5b0166919bf6e4bd1a3d">llvm::PPC::DIR_PWR8</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a0a03bfd83c00f4d1edab975b7bfe7f36">llvm::PPC::DIR_PWR9</a>.</p>

</div>
</div>

### getHazardType() {#a12ecb2c77f447a61153a3037607f2dee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer::HazardType PPCDispatchGroupSBHazardRecognizer::getHazardType (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *, int Stalls)</td>
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

<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>, definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scoreboardhazardrecognizer/#a8bf3deda3f11f3e49a4e3d735450c69e">llvm::ScoreboardHazardRecognizer::getHazardType</a> and <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a9bec0e329b12bbc503d08db497d43267a578b582cca14a34e75b2afc3a1cd00a5">llvm::ScheduleHazardRecognizer::NoopHazard</a>.</p>

</div>
</div>

### PreEmitNoops() {#a57749af083c14fb007c14bd27ab53e8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned PPCDispatchGroupSBHazardRecognizer::PreEmitNoops (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *)</td>
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

<p>PreEmitNoops - This callback is invoked prior to emitting an instruction.</p>


<p>It should return the number of noops to emit prior to the provided instruction. Note: This is only used during PostRA scheduling. EmitNoop is not called for these noops.</p>


<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34aa2b626cb4809ee8a3b3da9d475eabe05">llvm::PPC::DIR_PWR6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a0c8a5dd168df904e8c29520a47502a61">llvm::PPC::DIR_PWR7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34aa3de856d909c5b0166919bf6e4bd1a3d">llvm::PPC::DIR_PWR8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#afabcc2ff4ea75ff845f97b0807e8de34a0a03bfd83c00f4d1edab975b7bfe7f36">llvm::PPC::DIR_PWR9</a> and <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#aea4423b99e356d0ad170024f736fb4f1">llvm::ScheduleHazardRecognizer::PreEmitNoops</a>.</p>

</div>
</div>

### RecedeCycle() {#a6a37f926652da651355e009f5b33cc85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCDispatchGroupSBHazardRecognizer::RecedeCycle ()</td>
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

<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### Reset() {#af10ef678b8075734a77485c640b1e0e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCDispatchGroupSBHazardRecognizer::Reset ()</td>
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


<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>, definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scoreboardhazardrecognizer/#a059770a7aafc9643d09c5d9e836b1137">llvm::ScoreboardHazardRecognizer::Reset</a>.</p>

</div>
</div>

### ShouldPreferAnother() {#a747d30e23a3b40029d13eef9703dc9f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDispatchGroupSBHazardRecognizer::ShouldPreferAnother (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *)</td>
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

<p>ShouldPreferAnother - This callback may be invoked if getHazardType returns NoHazard.</p>


<p>If, even though there is no hazard, it would be better to schedule another available instruction, this callback should return true.</p>


<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a8e1b9c34eac5882a1e8e6e834222d3be">llvm::ScheduleHazardRecognizer::ShouldPreferAnother</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### isBCTRAfterSet() {#a91460af17105aaadfbd3e128075e2cdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDispatchGroupSBHazardRecognizer::isBCTRAfterSet (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>

</div>
</div>

### isLoadAfterStore() {#a92d0f51581163425bf76d956bf6dd632}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDispatchGroupSBHazardRecognizer::isLoadAfterStore (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>

</div>
</div>

### mustComeFirst() {#a0002833d82374fce9a289536e7843d8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDispatchGroupSBHazardRecognizer::mustComeFirst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> * MCID, unsigned &amp; NSlots)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurBranches {#a215eebf24b933377578bd604e9809efb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PPCDispatchGroupSBHazardRecognizer::CurBranches</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>.</p>

</div>
</div>

### CurGroup {#afe5c1a52e421f78ed82a5d91c5654253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SUnit *, 7&gt; llvm::PPCDispatchGroupSBHazardRecognizer::CurGroup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>.</p>

</div>
</div>

### CurSlots {#a0d986f0478676f664dab046d7d954ebe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PPCDispatchGroupSBHazardRecognizer::CurSlots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>.</p>

</div>
</div>

### DAG {#a9e7d2e42649d0495269701bf0dae19aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ScheduleDAG* llvm::PPCDispatchGroupSBHazardRecognizer::DAG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
