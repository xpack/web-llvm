---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ppchazardrecognizer970
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PPCHazardRecognizer970` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/ppchazardrecognizer970">PPCHazardRecognizer970</a> - This class defines a finite state automata that models the dispatch logic on the PowerPC 970 (aka G5) processor. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PPCHazardRecognizer970 { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">Target/PowerPC/PPCHazardRecognizers.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64f6635ee2148d5abf526f462a0c0890">PPCHazardRecognizer970</a> (const ScheduleDAG &amp;DAG)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a930f5688f2bff088096f72a68000c94e">getHazardType</a> (SUnit *SU, int Stalls) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getHazardType - We return hazard for any non-branch instruction that would terminate the dispatch group. <a href="#a930f5688f2bff088096f72a68000c94e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe71af95c1e795a56d13e488898d58f5">EmitInstruction</a> (SUnit *SU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitInstruction - This callback is invoked when an instruction is emitted, to advance the hazard state. <a href="#afe71af95c1e795a56d13e488898d58f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a753e31908cc070fa8a7f138bb81978">AdvanceCycle</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AdvanceCycle - This callback is invoked whenever the next top-down instruction to be scheduled cannot issue in the current cycle, either because of latency or resource conflicts. <a href="#a3a753e31908cc070fa8a7f138bb81978">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac699570c6ef79d075d59be2dfda8bc84">Reset</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset - This callback is invoked when a new block of instructions is about to be schedule. <a href="#ac699570c6ef79d075d59be2dfda8bc84">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fa0bb0d81e9bf34f69e8e9a8003ac9c">EndDispatchGroup</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EndDispatchGroup - Called when we are finishing a new dispatch group. <a href="#a0fa0bb0d81e9bf34f69e8e9a8003ac9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#aebfd14c5a918997e894a9698f27c58e6">PPCII::PPC970_Unit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51575fcdf5823adc21e8a1517508c9df">GetInstrType</a> (unsigned Opcode, bool &amp;isFirst, bool &amp;isSingle, bool &amp;isCracked, bool &amp;isLoad, bool &amp;isStore)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetInstrType - Classify the specified powerpc opcode according to its pipeline. <a href="#a51575fcdf5823adc21e8a1517508c9df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74b85d3c2fe147414186ceab8dd29bbb">isLoadOfStoredAddress</a> (uint64_t LoadSize, int64_t LoadOffset, const Value *LoadValue) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isLoadOfStoredAddress - If we have a load from the previously stored pointer as indicated by StorePtr1/StorePtr2/StoreSize, return true. <a href="#a74b85d3c2fe147414186ceab8dd29bbb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae953c0e291da9ad77518ba7369fe6e88">DAG</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77faf50f58b51bc8dedd6049cd9e0acb">NumIssued</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68aacb73faf2afe83f210ffbbdd5ffc1">HasCTRSet</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67ef5e19cd597a24ded21ca6fd71916b">StoreValue</a>[4]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addcd1d4c0dcb5a8e6d07bcd0490c07d2">StoreOffset</a>[4]</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab302c2d14d1be8f9def41826d6f9a836">StoreSize</a>[4]</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac26d304b5f515d51f2c1e138129744de">NumStores</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/ppchazardrecognizer970">PPCHazardRecognizer970</a> - This class defines a finite state automata that models the dispatch logic on the PowerPC 970 (aka G5) processor.</p>


<p>This promotes good dispatch group formation and implements noop insertion to avoid structural hazards that cause significant performance penalties (e.g. setting the CTR register then branching through it within a dispatch group), or storing then loading from the same address within a dispatch group.</p>


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PPCHazardRecognizer970() {#a64f6635ee2148d5abf526f462a0c0890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCHazardRecognizer970::PPCHazardRecognizer970 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a> &amp; DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>, definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AdvanceCycle() {#a3a753e31908cc070fa8a7f138bb81978}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCHazardRecognizer970::AdvanceCycle ()</td>
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


<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>, definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### EmitInstruction() {#afe71af95c1e795a56d13e488898d58f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCHazardRecognizer970::EmitInstruction (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *)</td>
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

<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>, definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#afa0fb135809edd33ea2b3d0497aa610c">llvm::MachineMemOperand::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a0ffa31699dee0349f9b9ae1d3ccb21f1">llvm::MachineMemOperand::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#add9e6ff8fe1923cb64757a6dbcd61676">llvm::MachineMemOperand::getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#a6b0daf17b9f0011e9a4c4c8f00644c12">isLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#aab5329eaa9a958adfa2c8de4d24e16cc">isStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#aebfd14c5a918997e894a9698f27c58e6ad3d339fe9c9bdedb6a7c90a2c58f4fad">llvm::PPCII::PPC970_BRU</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#aebfd14c5a918997e894a9698f27c58e6ad2c577175ece5487d0aa1cba0f3f21cf">llvm::PPCII::PPC970_Pseudo</a>.</p>

</div>
</div>

### getHazardType() {#a930f5688f2bff088096f72a68000c94e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer::HazardType PPCHazardRecognizer970::getHazardType (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, int Stalls)</td>
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

<p>getHazardType - We return hazard for any non-branch instruction that would terminate the dispatch group.</p>


<p>We turn NoopHazard for any instructions that wouldn't terminate the dispatch group that would cause a pipeline flush.</p>


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>, definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#afa0fb135809edd33ea2b3d0497aa610c">llvm::MachineMemOperand::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a0ffa31699dee0349f9b9ae1d3ccb21f1">llvm::MachineMemOperand::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#add9e6ff8fe1923cb64757a6dbcd61676">llvm::MachineMemOperand::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a0b0401973fc9567440717a5d32a8eb8d">llvm::LocationSize::hasValue</a>, <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a9bec0e329b12bbc503d08db497d43267aad25e3975650edcc9c6fb2917a61dd37">llvm::ScheduleHazardRecognizer::Hazard</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#a6b0daf17b9f0011e9a4c4c8f00644c12">isLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#aab5329eaa9a958adfa2c8de4d24e16cc">isStore</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a9bec0e329b12bbc503d08db497d43267a4e42ac50bfd060349e49904842121cf1">llvm::ScheduleHazardRecognizer::NoHazard</a>, <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a9bec0e329b12bbc503d08db497d43267a578b582cca14a34e75b2afc3a1cd00a5">llvm::ScheduleHazardRecognizer::NoopHazard</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#aebfd14c5a918997e894a9698f27c58e6ad3d339fe9c9bdedb6a7c90a2c58f4fad">llvm::PPCII::PPC970_BRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#aebfd14c5a918997e894a9698f27c58e6ad81768864759a838d64839c7b75d958c">llvm::PPCII::PPC970_CRU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#aebfd14c5a918997e894a9698f27c58e6a8fd98b2e3c101aa85bbc07409022b6ed">llvm::PPCII::PPC970_FPU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#aebfd14c5a918997e894a9698f27c58e6ab2e7d507b6cb4772d11fcc18fed5f80f">llvm::PPCII::PPC970_FXU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#aebfd14c5a918997e894a9698f27c58e6a2a7334a88276120f2238e6d4d1a7a51e">llvm::PPCII::PPC970_LSU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#aebfd14c5a918997e894a9698f27c58e6ad2c577175ece5487d0aa1cba0f3f21cf">llvm::PPCII::PPC970_Pseudo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#aebfd14c5a918997e894a9698f27c58e6a48b808627be5e642a62d9cca1d68dd7e">llvm::PPCII::PPC970_VALU</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#aebfd14c5a918997e894a9698f27c58e6a4b7f050b44fba7f1b01e3a0df85f0138">llvm::PPCII::PPC970_VPERM</a>.</p>

</div>
</div>

### Reset() {#ac699570c6ef79d075d59be2dfda8bc84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCHazardRecognizer970::Reset ()</td>
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


<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>, definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### EndDispatchGroup() {#a0fa0bb0d81e9bf34f69e8e9a8003ac9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCHazardRecognizer970::EndDispatchGroup ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EndDispatchGroup - Called when we are finishing a new dispatch group.</p>

<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>, definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>

</div>
</div>

### GetInstrType() {#a51575fcdf5823adc21e8a1517508c9df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCII::PPC970_Unit PPCHazardRecognizer970::GetInstrType (unsigned Opcode, bool &amp; isFirst, bool &amp; isSingle, bool &amp; isCracked, bool &amp; isLoad, bool &amp; isStore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GetInstrType - Classify the specified powerpc opcode according to its pipeline.</p>

<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>

</div>
</div>

### isLoadOfStoredAddress() {#a74b85d3c2fe147414186ceab8dd29bbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCHazardRecognizer970::isLoadOfStoredAddress (uint64_t LoadSize, int64_t LoadOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LoadValue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isLoadOfStoredAddress - If we have a load from the previously stored pointer as indicated by StorePtr1/StorePtr2/StoreSize, return true.</p>

<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>, definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-cpp">PPCHazardRecognizers.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DAG {#ae953c0e291da9ad77518ba7369fe6e88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ScheduleDAG&amp; llvm::PPCHazardRecognizer970::DAG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>.</p>

</div>
</div>

### HasCTRSet {#a68aacb73faf2afe83f210ffbbdd5ffc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PPCHazardRecognizer970::HasCTRSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>.</p>

</div>
</div>

### NumIssued {#a77faf50f58b51bc8dedd6049cd9e0acb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PPCHazardRecognizer970::NumIssued</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>.</p>

</div>
</div>

### NumStores {#ac26d304b5f515d51f2c1e138129744de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PPCHazardRecognizer970::NumStores</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>.</p>

</div>
</div>

### StoreOffset {#addcd1d4c0dcb5a8e6d07bcd0490c07d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::PPCHazardRecognizer970::StoreOffset[4]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>.</p>

</div>
</div>

### StoreSize {#ab302c2d14d1be8f9def41826d6f9a836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::PPCHazardRecognizer970::StoreSize[4]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>.</p>

</div>
</div>

### StoreValue {#a67ef5e19cd597a24ded21ca6fd71916b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value* llvm::PPCHazardRecognizer970::StoreValue[4]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppchazardrecognizers-h">PPCHazardRecognizers.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
