---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/hexagonsubtarget/bankconflictmutation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BankConflictMutation` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::HexagonSubtarget::BankConflictMutation { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">Target/Hexagon/HexagonSubtarget.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledagmutation">ScheduleDAGMutation</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mutate the DAG as a postpass after normal DAG building. <a href="/web-llvm/docs/api/classes/llvm/scheduledagmutation/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a336138bbbfacbbb4be8c56d41f08b0c2">apply</a> (ScheduleDAGInstrs *DAG) override</td>
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


<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### apply() {#a336138bbbfacbbb4be8c56d41f08b0c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonSubtarget::BankConflictMutation::apply (<a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> * DAG)</td>
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



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>, definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a551060cb0333d9d0cfdacd2576d817b9a8afafe9e6f4c2fb9744242a6b369a0f1">llvm::SDep::Artificial</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#aee75e70da0fb5b84ea847ab7daf9429bafb1e2614f7998a319eed3dad0f6c26dc">llvm::HexagonII::BaseImmOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp/#a0d0e6275fa68552b04de7ce54110912a">EnableCheckBankConflict</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a3f9468f2e297b7f870241b8298006fc7">llvm::HexagonInstrInfo::getAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad4a416f1e734b334b8868c3b728baaf4">llvm::HexagonInstrInfo::getBaseAndOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a0b0401973fc9567440717a5d32a8eb8d">llvm::LocationSize::hasValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a682028ac4a06c9e3550fa8e6e1909fa9">llvm::MachineInstr::mayLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab96f3235c18e659758517d0532d606c9">llvm::MachineInstr::mayStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a348590624c488b04d0f9e227e6c3960e">llvm::ScheduleDAG::TII</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp">HexagonSubtarget.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
