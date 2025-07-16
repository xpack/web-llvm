---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `M85Overrides` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses">ARMOverrideBypasses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Post-process the DAG to create cluster edges between instrs that may be fused by the processor into a single operation. <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae55dcd5eec10ddb739ce258addb4148a">M85Overrides</a> (const ARMBaseInstrInfo *t, AAResults *a)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32fabf22f4eddbf43f775ba273dde96e">modifyBypasses</a> (SUnit &amp;) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38476911502b9ac68f84a8d38d238620">computeBypassStage</a> (const MCSchedClassDesc *SCD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">signed</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbeeb9cd632b9891b5ba6b246ed3bb03">modifyMixedWidthFP</a> (const MachineInstr *SrcMI, const MachineInstr *DstMI, unsigned RegID, const MCSchedClassDesc *SCD)</td>
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


<p>Definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### M85Overrides() {#ae55dcd5eec10ddb739ce258addb4148a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::M85Overrides (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo">ARMBaseInstrInfo</a> * t, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> * a)</td>
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



<p>Definition at line 710 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#a70ed30ab8952716898ca9d9e14a8f246">llvm::ARMOverrideBypasses::ARMOverrideBypasses</a> and <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-armlatencymutations-cpp-/#aad74310eae5cdbc08f8db4d142d18552">llvm::anonymous{ARMLatencyMutations.cpp}::II</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### modifyBypasses() {#a32fabf22f4eddbf43f775ba273dde96e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &amp; ISU)</td>
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



<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#a45a5dee29db3f48cf227187b023cafab">llvm::ARMOverrideBypasses::DAG</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a055c65558a3e0f7d48f1ed3dde061199">llvm::SDep::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a5eca2019521fd47b79fe5ef66d02fd43">llvm::SDep::getLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a8b51361656ac436c2c02a20e6196cff1">llvm::SDep::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad343c12ac2d5c5b1e25402627439c74">llvm::hasImplicitCPSRUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-armlatencymutations-cpp-/#aad74310eae5cdbc08f8db4d142d18552">llvm::anonymous{ARMLatencyMutations.cpp}::II</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a6c89ab9b69b3bcaa536702845fd9542d">llvm::SDep::isAssignedRegDep</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a7406c398c67e53ee3937bf2b6df1c64e">llvm::SUnit::isBoundaryNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a735c62288cb6fa5004403bb643ce5679">llvm::isMVEVectorInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#ad1ced720461881db2f1371e0f30ff744">llvm::ARMOverrideBypasses::makeBundleAssumptions</a>, <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#a120fc86306882eb2bd3c27c9f4063fd6">llvm::ARMOverrideBypasses::memoryRAWHazard</a>, <a href="#a32fabf22f4eddbf43f775ba273dde96e">modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#a252bd3038d4cc84ade6e24b656bd4655">llvm::ARMOverrideBypasses::setBidirLatencies</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#aab4a86c51e6b126c9c6ef58dbb574431">llvm::SUnit::Succs</a>, <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#add6b418eb10002354b7cd2142e5c3cfc">llvm::ARMOverrideBypasses::TII</a> and <a href="/web-llvm/docs/api/classes/llvm/armoverridebypasses/#ab897f62e9a1641091f3bc53d82883440">llvm::ARMOverrideBypasses::zeroOutputDependences</a>.</p>


<p>Referenced by <a href="#a32fabf22f4eddbf43f775ba273dde96e">modifyBypasses</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeBypassStage() {#a38476911502b9ac68f84a8d38d238620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::computeBypassStage (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> * SCD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>

</div>
</div>

### modifyMixedWidthFP() {#adbeeb9cd632b9891b5ba6b246ed3bb03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">signed llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyMixedWidthFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * SrcMI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * DstMI, unsigned RegID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> * SCD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
