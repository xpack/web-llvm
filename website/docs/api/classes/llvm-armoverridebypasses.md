---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/armoverridebypasses
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ARMOverrideBypasses` Class

<p>Post-process the DAG to create cluster edges between instrs that may be fused by the processor into a single operation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ARMOverrideBypasses { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-h">Target/ARM/ARMLatencyMutations.h</a>"
</div>

## Base class

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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm55overrides">CortexM55Overrides</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides">CortexM7Overrides</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides">M85Overrides</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70ed30ab8952716898ca9d9e14a8f246">ARMOverrideBypasses</a> (const ARMBaseInstrInfo *t, AAResults *a)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad05686602c5ba519cd9fdaf2dad9bed8">apply</a> (ScheduleDAGInstrs *DAGInstrs) override</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1ced720461881db2f1371e0f30ff744">makeBundleAssumptions</a> (SUnit &amp;ISU, SDep &amp;Dep)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a120fc86306882eb2bd3c27c9f4063fd6">memoryRAWHazard</a> (SUnit &amp;ISU, SDep &amp;Dep, unsigned latency)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c441dbc6e430a28833a0a294200c450">modifyBypasses</a> (SUnit &amp;)=0</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo">ARMBaseInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add6b418eb10002354b7cd2142e5c3cfc">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eda110dc2311dfffbb42309251b6295">AA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45a5dee29db3f48cf227187b023cafab">DAG</a> = nullptr</td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a252bd3038d4cc84ade6e24b656bd4655">setBidirLatencies</a> (SUnit &amp;SrcSU, SDep &amp;SrcDep, unsigned latency)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab897f62e9a1641091f3bc53d82883440">zeroOutputDependences</a> (SUnit &amp;ISU, SDep &amp;Dep)</td>
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

<p>Post-process the DAG to create cluster edges between instrs that may be fused by the processor into a single operation.</p>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-h">ARMLatencyMutations.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ARMOverrideBypasses() {#a70ed30ab8952716898ca9d9e14a8f246}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ARMOverrideBypasses::ARMOverrideBypasses (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo">ARMBaseInstrInfo</a> * t, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> * a)</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-h">ARMLatencyMutations.h</a>.</p>


<p>References <a href="#a6eda110dc2311dfffbb42309251b6295">AA</a> and <a href="#add6b418eb10002354b7cd2142e5c3cfc">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm55overrides/#ae6bae6ec4765a0eb03d526274ea167d0">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM55Overrides::CortexM55Overrides</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#afb4a6bcebb1c4ab3baf4e844510154b1">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::CortexM7Overrides</a> and <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#ae55dcd5eec10ddb739ce258addb4148a">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::M85Overrides</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### apply() {#ad05686602c5ba519cd9fdaf2dad9bed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ARMOverrideBypasses::apply (<a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> * DAGInstrs)</td>
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



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-h">ARMLatencyMutations.h</a>, definition at line 953 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>References <a href="#a45a5dee29db3f48cf227187b023cafab">DAG</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#af81f734d7fb268c95c1c63c399a7c4a6">llvm::ScheduleDAG::ExitSU</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a7406c398c67e53ee3937bf2b6df1c64e">llvm::SUnit::isBoundaryNode</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a3d5aacd5fc7d6a739ce913974ed1e53d">llvm::ScheduleDAG::SUnits</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### makeBundleAssumptions() {#ad1ced720461881db2f1371e0f30ff744}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ARMOverrideBypasses::makeBundleAssumptions (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &amp; ISU, <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; Dep)</td>
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



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-h">ARMLatencyMutations.h</a>, definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a8b51361656ac436c2c02a20e6196cff1">llvm::SDep::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a6c89ab9b69b3bcaa536702845fd9542d">llvm::SDep::isAssignedRegDep</a>, <a href="#a252bd3038d4cc84ade6e24b656bd4655">setBidirLatencies</a> and <a href="#add6b418eb10002354b7cd2142e5c3cfc">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#a4bb20a752a698ed16d84ddbc8abde037">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::modifyBypasses</a> and <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#a32fabf22f4eddbf43f775ba273dde96e">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses</a>.</p>

</div>
</div>

### memoryRAWHazard() {#a120fc86306882eb2bd3c27c9f4063fd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMOverrideBypasses::memoryRAWHazard (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &amp; ISU, <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; Dep, unsigned latency)</td>
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



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-h">ARMLatencyMutations.h</a>, definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>References <a href="#a6eda110dc2311dfffbb42309251b6295">AA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue/#a9959ffdc41bc31cf2211b8824f79259eaf38d1857511c3f0404c95f65664b36ab">llvm::PseudoSourceValue::FixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a74e4e5c8f7ea14d79ea03006d33dc393">llvm::SDep::isNormalMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab37075d621acbbfc96ef2662f2e29883">llvm::MachineInstr::memoperands</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57ac1a99a1af9a4778a61e5cc3e1d622180">llvm::AliasResult::MustAlias</a> and <a href="#a252bd3038d4cc84ade6e24b656bd4655">setBidirLatencies</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#a4bb20a752a698ed16d84ddbc8abde037">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::modifyBypasses</a> and <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#a32fabf22f4eddbf43f775ba273dde96e">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### modifyBypasses() {#a1c441dbc6e430a28833a0a294200c450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::ARMOverrideBypasses::modifyBypasses (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-h">ARMLatencyMutations.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AA {#a6eda110dc2311dfffbb42309251b6295}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAResults* llvm::ARMOverrideBypasses::AA</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-h">ARMLatencyMutations.h</a>.</p>


<p>Referenced by <a href="#a70ed30ab8952716898ca9d9e14a8f246">ARMOverrideBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm55overrides/#ae6bae6ec4765a0eb03d526274ea167d0">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM55Overrides::CortexM55Overrides</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#afb4a6bcebb1c4ab3baf4e844510154b1">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::CortexM7Overrides</a> and <a href="#a120fc86306882eb2bd3c27c9f4063fd6">memoryRAWHazard</a>.</p>

</div>
</div>

### DAG {#a45a5dee29db3f48cf227187b023cafab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGInstrs* llvm::ARMOverrideBypasses::DAG = nullptr</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-h">ARMLatencyMutations.h</a>.</p>


<p>Referenced by <a href="#ad05686602c5ba519cd9fdaf2dad9bed8">apply</a> and <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#a32fabf22f4eddbf43f775ba273dde96e">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses</a>.</p>

</div>
</div>

### TII {#add6b418eb10002354b7cd2142e5c3cfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ARMBaseInstrInfo* llvm::ARMOverrideBypasses::TII</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-h">ARMLatencyMutations.h</a>.</p>


<p>Referenced by <a href="#a70ed30ab8952716898ca9d9e14a8f246">ARMOverrideBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm55overrides/#ae6bae6ec4765a0eb03d526274ea167d0">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM55Overrides::CortexM55Overrides</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#afb4a6bcebb1c4ab3baf4e844510154b1">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::CortexM7Overrides</a>, <a href="#ad1ced720461881db2f1371e0f30ff744">makeBundleAssumptions</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#a4bb20a752a698ed16d84ddbc8abde037">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::modifyBypasses</a> and <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#a32fabf22f4eddbf43f775ba273dde96e">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### setBidirLatencies() {#a252bd3038d4cc84ade6e24b656bd4655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ARMOverrideBypasses::setBidirLatencies (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &amp; SrcSU, <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; SrcDep, unsigned latency)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-h">ARMLatencyMutations.h</a>, definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eafa67f115c1fddc4ce1aeb1c754001585bc">llvm::Reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#addb1364902bd813841491d91970ce02b">llvm::SUnit::setDepthDirty</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a5ba3791568e29a8d9214ec7dad855a56">llvm::SUnit::setHeightDirty</a> and <a href="/web-llvm/docs/api/classes/llvm/sdep/#a148b76c8f993d4a3d95ac19c60e2ebe0">llvm::SDep::setLatency</a>.</p>


<p>Referenced by <a href="#ad1ced720461881db2f1371e0f30ff744">makeBundleAssumptions</a>, <a href="#a120fc86306882eb2bd3c27c9f4063fd6">memoryRAWHazard</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm55overrides/#a6c67a87b5b8b7338e197f5bb29767019">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM55Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#a4bb20a752a698ed16d84ddbc8abde037">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#a32fabf22f4eddbf43f775ba273dde96e">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses</a> and <a href="#ab897f62e9a1641091f3bc53d82883440">zeroOutputDependences</a>.</p>

</div>
</div>

### zeroOutputDependences() {#ab897f62e9a1641091f3bc53d82883440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMOverrideBypasses::zeroOutputDependences (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &amp; ISU, <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; Dep)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-h">ARMLatencyMutations.h</a>, definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdep/#a055c65558a3e0f7d48f1ed3dde061199">llvm::SDep::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732a011a1d87822a7f70efee9e430a7ccc36">llvm::SDep::Output</a> and <a href="#a252bd3038d4cc84ade6e24b656bd4655">setBidirLatencies</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#a4bb20a752a698ed16d84ddbc8abde037">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::modifyBypasses</a> and <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#a32fabf22f4eddbf43f775ba273dde96e">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-h">ARMLatencyMutations.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
