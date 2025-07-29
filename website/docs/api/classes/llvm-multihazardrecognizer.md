---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/multihazardrecognizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MultiHazardRecognizer` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MultiHazardRecognizer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/multihazardrecognizer-h">llvm/CodeGen/MultiHazardRecognizer.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2bf05d64af5ddabb08d801b7ca6745e">MultiHazardRecognizer</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a618db508276a64a8834e47955553caed">AddHazardRecognizer</a> (std::unique_ptr&lt; ScheduleHazardRecognizer &gt; &amp;&amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6176bd5d9d866b3e015f85418ced4bc0">atIssueLimit</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>atIssueLimit - Return true if no more instructions may be issued in this cycle. <a href="#a6176bd5d9d866b3e015f85418ced4bc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a9bec0e329b12bbc503d08db497d43267">HazardType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abab51e03236d8e7faaac056950784049">getHazardType</a> (SUnit *, int Stalls=0) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getHazardType - Return the hazard type of emitting this node. <a href="#abab51e03236d8e7faaac056950784049">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b7e04e17914117170b71020ecfbbed4">Reset</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset - This callback is invoked when a new block of instructions is about to be schedule. <a href="#a7b7e04e17914117170b71020ecfbbed4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8f76703141fb3996dd9d7eb15a2a289">EmitInstruction</a> (SUnit *) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitInstruction - This callback is invoked when an instruction is emitted, to advance the hazard state. <a href="#aa8f76703141fb3996dd9d7eb15a2a289">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85fd35fcf55765b5ade4de52ac16396e">EmitInstruction</a> (MachineInstr *) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This overload will be used when the hazard recognizer is being used by a non-scheduling pass, which does not use SUnits. <a href="#a85fd35fcf55765b5ade4de52ac16396e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a077a1caaa75e2901d77a30d9ff63787f">PreEmitNoops</a> (SUnit *) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PreEmitNoops - This callback is invoked prior to emitting an instruction. <a href="#a077a1caaa75e2901d77a30d9ff63787f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4948f5bf36774dd76242143ba3f6d047">PreEmitNoops</a> (MachineInstr *) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This overload will be used when the hazard recognizer is being used by a non-scheduling pass, which does not use SUnits. <a href="#a4948f5bf36774dd76242143ba3f6d047">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4f50a6404b6303d0a55331d32216811">ShouldPreferAnother</a> (SUnit *) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ShouldPreferAnother - This callback may be invoked if getHazardType returns NoHazard. <a href="#ae4f50a6404b6303d0a55331d32216811">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae34064454abc953a7881915f25f7d724">AdvanceCycle</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AdvanceCycle - This callback is invoked whenever the next top-down instruction to be scheduled cannot issue in the current cycle, either because of latency or resource conflicts. <a href="#ae34064454abc953a7881915f25f7d724">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac91f78774c3b03186f20d566fed19282">RecedeCycle</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RecedeCycle - This callback is invoked whenever the next bottom-up instruction to be scheduled cannot issue in the current cycle, either because of latency or resource conflicts. <a href="#ac91f78774c3b03186f20d566fed19282">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22f7c50913c8449715bab579036208e6">EmitNoop</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitNoop - This callback is invoked when a noop was added to the instruction stream. <a href="#a22f7c50913c8449715bab579036208e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer">ScheduleHazardRecognizer</a> &gt;, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb521d57cf48e13b33c286ca13967768">Recognizers</a></td>
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


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/multihazardrecognizer-h">MultiHazardRecognizer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MultiHazardRecognizer() {#ae2bf05d64af5ddabb08d801b7ca6745e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MultiHazardRecognizer::MultiHazardRecognizer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/multihazardrecognizer-h">MultiHazardRecognizer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AddHazardRecognizer() {#a618db508276a64a8834e47955553caed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MultiHazardRecognizer::AddHazardRecognizer (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer">ScheduleHazardRecognizer</a> &gt; &amp;&amp; R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/multihazardrecognizer-h">MultiHazardRecognizer.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/multihazardrecognizer-cpp">MultiHazardRecognizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a6acf461721a59cf5cf404b80b5f57f86">llvm::ScheduleHazardRecognizer::MaxLookAhead</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a7e340b4e4b4412f6808ff4270bfa6999">llvm::ARMBaseInstrInfo::CreateTargetMIHazardRecognizer</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a624af1a09f6ec191f88dfd2b26c3e54a">llvm::ARMBaseInstrInfo::CreateTargetPostRAHazardRecognizer</a>.</p>

</div>
</div>

### AdvanceCycle() {#ae34064454abc953a7881915f25f7d724}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MultiHazardRecognizer::AdvanceCycle ()</td>
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


<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/multihazardrecognizer-h">MultiHazardRecognizer.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/multihazardrecognizer-cpp">MultiHazardRecognizer.cpp</a>.</p>

</div>
</div>

### atIssueLimit() {#a6176bd5d9d866b3e015f85418ced4bc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MultiHazardRecognizer::atIssueLimit ()</td>
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


<p>FIXME: remove this once MachineScheduler is the only client.</p>


<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/multihazardrecognizer-h">MultiHazardRecognizer.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/multihazardrecognizer-cpp">MultiHazardRecognizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a> and <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a8d57f996bd3d69e4f0674a54c5d62426">llvm::ScheduleHazardRecognizer::atIssueLimit</a>.</p>

</div>
</div>

### EmitInstruction() {#aa8f76703141fb3996dd9d7eb15a2a289}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MultiHazardRecognizer::EmitInstruction (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *)</td>
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

<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/multihazardrecognizer-h">MultiHazardRecognizer.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/multihazardrecognizer-cpp">MultiHazardRecognizer.cpp</a>.</p>

</div>
</div>

### EmitInstruction() {#a85fd35fcf55765b5ade4de52ac16396e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MultiHazardRecognizer::EmitInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *)</td>
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

<p>This overload will be used when the hazard recognizer is being used by a non-scheduling pass, which does not use SUnits.</p>

<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/multihazardrecognizer-h">MultiHazardRecognizer.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/multihazardrecognizer-cpp">MultiHazardRecognizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### EmitNoop() {#a22f7c50913c8449715bab579036208e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MultiHazardRecognizer::EmitNoop ()</td>
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

<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/multihazardrecognizer-h">MultiHazardRecognizer.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/multihazardrecognizer-cpp">MultiHazardRecognizer.cpp</a>.</p>

</div>
</div>

### getHazardType() {#abab51e03236d8e7faaac056950784049}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer::HazardType MultiHazardRecognizer::getHazardType (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *, int Stalls=0)</td>
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

<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/multihazardrecognizer-h">MultiHazardRecognizer.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/multihazardrecognizer-cpp">MultiHazardRecognizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a9bec0e329b12bbc503d08db497d43267a4e42ac50bfd060349e49904842121cf1">llvm::ScheduleHazardRecognizer::NoHazard</a>.</p>

</div>
</div>

### PreEmitNoops() {#a077a1caaa75e2901d77a30d9ff63787f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MultiHazardRecognizer::PreEmitNoops (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *)</td>
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


<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/multihazardrecognizer-h">MultiHazardRecognizer.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/multihazardrecognizer-cpp">MultiHazardRecognizer.cpp</a>.</p>

</div>
</div>

### PreEmitNoops() {#a4948f5bf36774dd76242143ba3f6d047}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MultiHazardRecognizer::PreEmitNoops (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *)</td>
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

<p>This overload will be used when the hazard recognizer is being used by a non-scheduling pass, which does not use SUnits.</p>

<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/multihazardrecognizer-h">MultiHazardRecognizer.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/multihazardrecognizer-cpp">MultiHazardRecognizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### RecedeCycle() {#ac91f78774c3b03186f20d566fed19282}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MultiHazardRecognizer::RecedeCycle ()</td>
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

<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/multihazardrecognizer-h">MultiHazardRecognizer.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/multihazardrecognizer-cpp">MultiHazardRecognizer.cpp</a>.</p>

</div>
</div>

### Reset() {#a7b7e04e17914117170b71020ecfbbed4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MultiHazardRecognizer::Reset ()</td>
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


<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/multihazardrecognizer-h">MultiHazardRecognizer.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/multihazardrecognizer-cpp">MultiHazardRecognizer.cpp</a>.</p>

</div>
</div>

### ShouldPreferAnother() {#ae4f50a6404b6303d0a55331d32216811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MultiHazardRecognizer::ShouldPreferAnother (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *)</td>
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


<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/multihazardrecognizer-h">MultiHazardRecognizer.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/multihazardrecognizer-cpp">MultiHazardRecognizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Recognizers {#adb521d57cf48e13b33c286ca13967768}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;ScheduleHazardRecognizer&gt;, 4&gt; llvm::MultiHazardRecognizer::Recognizers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/multihazardrecognizer-h">MultiHazardRecognizer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/multihazardrecognizer-h">MultiHazardRecognizer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/multihazardrecognizer-cpp">MultiHazardRecognizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
