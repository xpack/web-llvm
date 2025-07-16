---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gcnhazardrecognizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GCNHazardRecognizer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::GCNHazardRecognizer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">Target/AMDGPU/GCNHazardRecognizer.h</a>"
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;)&gt; <a href="#a7927e5acc9828ba4a34fe435c4f37ddd">IsHazardFn</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad92622f105161d0e67720e71e171891c">GCNHazardRecognizer</a> (const MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af88156b7343529b71f1f9eca67805251">atIssueLimit</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>atIssueLimit - Return true if no more instructions may be issued in this cycle. <a href="#af88156b7343529b71f1f9eca67805251">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7752890a080ddcf0671bdab4a9e3241e">EmitInstruction</a> (SUnit *SU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitInstruction - This callback is invoked when an instruction is emitted, to advance the hazard state. <a href="#a7752890a080ddcf0671bdab4a9e3241e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38642e0368a567c10682ecebe34f776b">EmitInstruction</a> (MachineInstr *MI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This overload will be used when the hazard recognizer is being used by a non-scheduling pass, which does not use SUnits. <a href="#a38642e0368a567c10682ecebe34f776b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a9bec0e329b12bbc503d08db497d43267">HazardType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad798e3928656e87abcacbf5f7dd47dbe">getHazardType</a> (SUnit *SU, int Stalls) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getHazardType - Return the hazard type of emitting this node. <a href="#ad798e3928656e87abcacbf5f7dd47dbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a441eaa1d314b850d169305bfd9e22737">EmitNoop</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitNoop - This callback is invoked when a noop was added to the instruction stream. <a href="#a441eaa1d314b850d169305bfd9e22737">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a689fbd2e7e21f8d8c851465bb66830a7">PreEmitNoops</a> (MachineInstr *) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This overload will be used when the hazard recognizer is being used by a non-scheduling pass, which does not use SUnits. <a href="#a689fbd2e7e21f8d8c851465bb66830a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b16457758ae332c79a7f276f68d2c17">PreEmitNoopsCommon</a> (MachineInstr *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7941cd9d835501582ba89f8352863bba">AdvanceCycle</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AdvanceCycle - This callback is invoked whenever the next top-down instruction to be scheduled cannot issue in the current cycle, either because of latency or resource conflicts. <a href="#a7941cd9d835501582ba89f8352863bba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed068d2980aff5b2a37d6254e6791c11">RecedeCycle</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RecedeCycle - This callback is invoked whenever the next bottom-up instruction to be scheduled cannot issue in the current cycle, either because of latency or resource conflicts. <a href="#aed068d2980aff5b2a37d6254e6791c11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accfcd00e03bf4fddc4d3b32657c3e291">ShouldPreferAnother</a> (SUnit *SU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ShouldPreferAnother - This callback may be invoked if getHazardType returns NoHazard. <a href="#accfcd00e03bf4fddc4d3b32657c3e291">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6069b449b7409a82dca2739f80dc2943">Reset</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset - This callback is invoked when a new block of instructions is about to be schedule. <a href="#a6069b449b7409a82dca2739f80dc2943">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafbdfa04e0804a88a2e030789a12caed">resetClause</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fba1460ee46e0d936b9bda5960fed7b">addClauseInst</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9dc4099a4969c8112d94ce9fa7bce6a">getMFMAPipelineWaitStates</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac86cd98dd51541213a1a84a13d1e0d76">processBundle</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4f6f501d71cfebb0a4ec85e0f3d1a7c">runOnInstruction</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62720f23dfe3563270785b06c2b9de89">getWaitStatesSince</a> (IsHazardFn IsHazard, int Limit)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3466993251e5d319a9af26dfb112fe9c">getWaitStatesSinceDef</a> (unsigned Reg, IsHazardFn IsHazardDef, int Limit)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0ddcf90ab69764b53680fcb99396cbb">getWaitStatesSinceSetReg</a> (IsHazardFn IsHazard, int Limit)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae13a65ba523b2fbaf753df418a7dfd96">checkSoftClauseHazards</a> (MachineInstr *SMEM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a23c58deb0a5938af2363d54110bf8c">checkSMRDHazards</a> (MachineInstr *SMRD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ea029de8448adab49a0cc4cd70c4a8d">checkVMEMHazards</a> (MachineInstr *VMEM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3a66bc705d82839394b8a1ee55a16d6">checkDPPHazards</a> (MachineInstr *DPP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab164bf2773a47168a54efd2126f01978">checkDivFMasHazards</a> (MachineInstr *DivFMas)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a024e74531ee57c932b6c17168fc2b4bf">checkGetRegHazards</a> (MachineInstr *GetRegInstr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9465aa460716fec006db06339c7737b6">checkSetRegHazards</a> (MachineInstr *SetRegInstr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fe98f66ae6ffdd4efa6664e52e25807">createsVALUHazard</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a725b2cc1b0889d5b4c6730f57af1bb74">checkVALUHazards</a> (MachineInstr *VALU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02a919d5d455561834f3749e877d94c1">checkVALUHazardsHelper</a> (const MachineOperand &amp;Def, const MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75a70f852b2179320aee963b7e87e488">checkRWLaneHazards</a> (MachineInstr *RWLane)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fb1c33810034d784109f8ead44658ee">checkRFEHazards</a> (MachineInstr *RFE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb0379941d2826d07b8c1985d775b2c9">checkInlineAsmHazards</a> (MachineInstr *IA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cc60bf7e92d29f03d0d97083593daf9">checkReadM0Hazards</a> (MachineInstr *SMovRel)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91829de971631f8655aa934cfb97fffc">checkNSAtoVMEMHazard</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33deb9946243490bcc4581439b50a104">checkFPAtomicToDenormModeHazard</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa9fc83f306e08ba3ccbcc94fe107d0f">fixHazards</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e68a89dc2305f024deac6d9463723ff">fixVcmpxPermlaneHazards</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc4341d752796207b556ab6af682141c">fixVMEMtoScalarWriteHazards</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad02107aef8be46b34328b8f3ce0a212b">fixSMEMtoVectorWriteHazards</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af32d940bf9a1836b0558ba3726e6d1d8">fixVcmpxExecWARHazard</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a93a1bd29acf37f29fa1e2ee7292967">fixLdsBranchVmemWARHazard</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9d2783ac77d2225ae09de7efc235767">fixLdsDirectVALUHazard</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcaba542833f428af170308e01e3c0f6">fixLdsDirectVMEMHazard</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84b0e78902e2e220d3c4e2d6de2135a0">fixVALUPartialForwardingHazard</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63ae3d5013964a753bf8ff01f203ff61">fixVALUTransUseHazard</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08c8317bcbbdd3a153f102af3236ddea">fixWMMAHazards</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb20cedf8327f65fc99cc4faa1309d1b">fixShift64HighRegBug</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3db6eab373b949aadac2e8681b9fb210">fixVALUMaskWriteHazard</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4979230fe7277c53beca2caf66fb6f9b">computeVALUHazardSGPRs</a> (MachineFunction *MMF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a022b19b3afcd78cfde5ccf8318571600">fixVALUReadSGPRHazard</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a434efe6106ada5eee3c145c4889689ed">fixRequiredExportPriority</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a667394ede0d4895edbf89ff3d60f1b67">checkMAIHazards</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a987dc43b660d5119e5a895d7f479fae9">checkMAIHazards908</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89d53ec9575b838f76a84fba3a97d6e3">checkMAIHazards90A</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ad87b82e14deb07a81035f2ad992858">checkMFMAPadding</a> (MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pad the latency between neighboring MFMA instructions with s_nops. <a href="#a4ad87b82e14deb07a81035f2ad992858">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46d081655493b9fd5219ee549272892d">checkMAIVALUHazards</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11dfdb1fec5cdb55727ce5bc36427c2f">checkMAILdStHazards</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6783e8c7a936fe63f89ad53c8d7eba94">checkPermlaneHazards</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b60ae0c53c4c5ef7a87b322531d0cb">IsHazardRecognizerMode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f68a2fc891ae4ef007af303318b6ff9">CurrCycleInstr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::list&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a117ebb888e61a7dfbc3f037a3fa25ec0">EmittedInstrs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b62d472a54f0afae997f91f6139df3f">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04771e74b94a31a212afe3ad45784fa0">ST</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c86127a5322689ccee05246bd7a2f6d">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a056bcba55cafe536e509c70a46b0ecd7">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ff9963b4567ed339eb3b49ee7625cee">TSchedModel</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2a7539ec13590f52c16d695360ea344">RunLdsBranchVmemWARHazardFixup</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34a4ce89441cef94cf15e03c67749ff4">VALUReadHazardSGPRs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bb7076234d162e31b7c36ce006ed65c">UseVALUReadHazardExhaustiveSearch</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58b4ec303a03b09239a62c3ce25c6f9c">ClauseUses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RegUnits of uses in the current soft memory clause. <a href="#a58b4ec303a03b09239a62c3ce25c6f9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace0f92e6a4212fcf0f2a8110e5a8bddd">ClauseDefs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RegUnits of defs in the current soft memory clause. <a href="#ace0f92e6a4212fcf0f2a8110e5a8bddd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### IsHazardFn {#a7927e5acc9828ba4a34fe435c4f37ddd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef function_ref&lt;bool(const MachineInstr &amp;)&gt; llvm::GCNHazardRecognizer::IsHazardFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GCNHazardRecognizer() {#ad92622f105161d0e67720e71e171891c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNHazardRecognizer::GCNHazardRecognizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a6acf461721a59cf5cf404b80b5f57f86">llvm::ScheduleHazardRecognizer::MaxLookAhead</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a0673f88d21e33d7a42a66e19328fab3b">shouldRunLdsBranchVmemWARHazardFixup</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AdvanceCycle() {#a7941cd9d835501582ba89f8352863bba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNHazardRecognizer::AdvanceCycle ()</td>
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


<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a01f781fc999200779e9b3d56da7e759a">llvm::ScheduleHazardRecognizer::getMaxLookAhead</a>.</p>

</div>
</div>

### atIssueLimit() {#af88156b7343529b71f1f9eca67805251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNHazardRecognizer::atIssueLimit ()</td>
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

<p>atIssueLimit - Return true if no more instructions may be issued in this cycle.</p>


<p>FIXME: remove this once MachineScheduler is the only client.</p>


<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>.</p>

</div>
</div>

### EmitInstruction() {#a7752890a080ddcf0671bdab4a9e3241e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNHazardRecognizer::EmitInstruction (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *)</td>
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

<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>


<p>References <a href="#a7752890a080ddcf0671bdab4a9e3241e">EmitInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>.</p>


<p>Referenced by <a href="#a7752890a080ddcf0671bdab4a9e3241e">EmitInstruction</a>.</p>

</div>
</div>

### EmitInstruction() {#a38642e0368a567c10682ecebe34f776b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNHazardRecognizer::EmitInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *)</td>
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

<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### EmitNoop() {#a441eaa1d314b850d169305bfd9e22737}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNHazardRecognizer::EmitNoop ()</td>
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

<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### getHazardType() {#ad798e3928656e87abcacbf5f7dd47dbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleHazardRecognizer::HazardType GCNHazardRecognizer::getHazardType (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *, int Stalls)</td>
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

<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a9bec0e329b12bbc503d08db497d43267aad25e3975650edcc9c6fb2917a61dd37">llvm::ScheduleHazardRecognizer::Hazard</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a7f1e88c371c54f3af00f7958a95972f7">isDivFMas</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a960996ed89167b7ad321c647644d8dfb">llvm::SIInstrInfo::isDPP</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a08b60e6be6801b1f90d723990ef68009">llvm::SIInstrInfo::isDS</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a2d40ab246e329190bbf36cd93fd88e83">llvm::SIInstrInfo::isEXP</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#adc3333d2d5974f4068df84f8706fc7d2">llvm::SIInstrInfo::isFLAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a1f84fc794016facc8c5127ef79b740f2">isLdsDma</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0605f773275c0461756eae0fb2321fa0">llvm::SIInstrInfo::isMAI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a21aecd99e0b902bb237b5d9a817a5562">isRFE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a269b53c1da092ceaa58fddaf6bfa8082">isRWLane</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#ad3ccf5de9dd2fcff9820f0fb2a67a543">isSendMsgTraceDataOrGDS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a15c7cc93774401903012694a4e145758">isSGetReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a2d60a621c5d63e58da8fd30a1d67c707">isSMovRel</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a1c990a34866f377751f50f112cef61bc">llvm::SIInstrInfo::isSMRD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a582b27649f99e47a406f3306f8bec192">isSSetReg</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ade8d533000b775c514d9ac189b66c3a5">llvm::SIInstrInfo::isVALU</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a08b830059090a1bb27b14e1e524fdb46">llvm::SIInstrInfo::isVMEM</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a9bec0e329b12bbc503d08db497d43267a4e42ac50bfd060349e49904842121cf1">llvm::ScheduleHazardRecognizer::NoHazard</a> and <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a9bec0e329b12bbc503d08db497d43267a578b582cca14a34e75b2afc3a1cd00a5">llvm::ScheduleHazardRecognizer::NoopHazard</a>.</p>

</div>
</div>

### PreEmitNoops() {#a689fbd2e7e21f8d8c851465bb66830a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNHazardRecognizer::PreEmitNoops (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *)</td>
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

<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a8b16457758ae332c79a7f276f68d2c17">PreEmitNoopsCommon</a>.</p>

</div>
</div>

### PreEmitNoopsCommon() {#a8b16457758ae332c79a7f276f68d2c17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNHazardRecognizer::PreEmitNoopsCommon (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a7f1e88c371c54f3af00f7958a95972f7">isDivFMas</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a960996ed89167b7ad321c647644d8dfb">llvm::SIInstrInfo::isDPP</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a08b60e6be6801b1f90d723990ef68009">llvm::SIInstrInfo::isDS</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a2d40ab246e329190bbf36cd93fd88e83">llvm::SIInstrInfo::isEXP</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#adc3333d2d5974f4068df84f8706fc7d2">llvm::SIInstrInfo::isFLAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a1f84fc794016facc8c5127ef79b740f2">isLdsDma</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0605f773275c0461756eae0fb2321fa0">llvm::SIInstrInfo::isMAI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#af079bafbc8a51905948f6c0937ce75e4">isPermlane</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a21aecd99e0b902bb237b5d9a817a5562">isRFE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a269b53c1da092ceaa58fddaf6bfa8082">isRWLane</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#ad3ccf5de9dd2fcff9820f0fb2a67a543">isSendMsgTraceDataOrGDS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a15c7cc93774401903012694a4e145758">isSGetReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a2d60a621c5d63e58da8fd30a1d67c707">isSMovRel</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a1c990a34866f377751f50f112cef61bc">llvm::SIInstrInfo::isSMRD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a582b27649f99e47a406f3306f8bec192">isSSetReg</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ade8d533000b775c514d9ac189b66c3a5">llvm::SIInstrInfo::isVALU</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a08b830059090a1bb27b14e1e524fdb46">llvm::SIInstrInfo::isVMEM</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a689fbd2e7e21f8d8c851465bb66830a7">PreEmitNoops</a>.</p>

</div>
</div>

### RecedeCycle() {#aed068d2980aff5b2a37d6254e6791c11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNHazardRecognizer::RecedeCycle ()</td>
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

<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### Reset() {#a6069b449b7409a82dca2739f80dc2943}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNHazardRecognizer::Reset ()</td>
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


<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### ShouldPreferAnother() {#accfcd00e03bf4fddc4d3b32657c3e291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNHazardRecognizer::ShouldPreferAnother (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *)</td>
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


<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 2935 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a274909b1f31ad2d3d3379de55467d377">llvm::SUnit::isInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a96ebcd476b7e0bf9c549c423546b18dc">llvm::SIInstrInfo::isMFMA</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addClauseInst() {#a1fba1460ee46e0d936b9bda5960fed7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNHazardRecognizer::addClauseInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkDivFMasHazards() {#ab164bf2773a47168a54efd2126f01978}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkDivFMasHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * DivFMas)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 780 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkDPPHazards() {#ad3a66bc705d82839394b8a1ee55a16d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkDPPHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * DPP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 749 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkFPAtomicToDenormModeHazard() {#a33deb9946243490bcc4581439b50a104}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkFPAtomicToDenormModeHazard (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 2021 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkGetRegHazards() {#a024e74531ee57c932b6c17168fc2b4bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkGetRegHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * GetRegInstr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 795 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkInlineAsmHazards() {#afb0379941d2826d07b8c1985d775b2c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkInlineAsmHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * IA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 1101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkMAIHazards() {#a667394ede0d4895edbf89ff3d60f1b67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkMAIHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 2060 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkMAIHazards908() {#a987dc43b660d5119e5a895d7f479fae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkMAIHazards908 (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 2096 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkMAIHazards90A() {#a89d53ec9575b838f76a84fba3a97d6e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkMAIHazards90A (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 2310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkMAILdStHazards() {#a11dfdb1fec5cdb55727ce5bc36427c2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkMAILdStHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 2513 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkMAIVALUHazards() {#a46d081655493b9fd5219ee549272892d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkMAIVALUHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 2636 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkMFMAPadding() {#a4ad87b82e14deb07a81035f2ad992858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkMFMAPadding (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pad the latency between neighboring MFMA instructions with s_nops.</p>


<p>The percentage of wait states to fill with s_nops is specified by the command line option '-amdgpu-mfma-padding-ratio'.</p>


<p>For example, with '-amdgpu-mfma-padding-ratio=100':</p>


<p>2 pass MFMA instructions have a latency of 2 wait states. Therefore, a 'S_NOP 1' will be added between sequential MFMA instructions.</p>


<p>V_MFMA_F32_4X4X1F32 V_MFMA_F32_4X4X1F32 --&gt; V_MFMA_F32_4X4X1F32 S_NOP 1 V_MFMA_F32_4X4X1F32</p>


<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 2066 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkNSAtoVMEMHazard() {#a91829de971631f8655aa934cfb97fffc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkNSAtoVMEMHazard (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 1996 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkPermlaneHazards() {#a6783e8c7a936fe63f89ad53c8d7eba94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkPermlaneHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 2560 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkReadM0Hazards() {#a3cc60bf7e92d29f03d0d97083593daf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkReadM0Hazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * SMovRel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 1197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkRFEHazards() {#a5fb1c33810034d784109f8ead44658ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkRFEHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * RFE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 1182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkRWLaneHazards() {#a75a70f852b2179320aee963b7e87e488}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkRWLaneHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * RWLane)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 1162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkSetRegHazards() {#a9465aa460716fec006db06339c7737b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkSetRegHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * SetRegInstr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 808 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkSMRDHazards() {#a3a23c58deb0a5938af2363d54110bf8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkSMRDHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * SMRD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 677 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkSoftClauseHazards() {#ae13a65ba523b2fbaf753df418a7dfd96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkSoftClauseHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * SMEM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkVALUHazards() {#a725b2cc1b0889d5b4c6730f57af1bb74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkVALUHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * VALU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 972 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkVALUHazardsHelper() {#a02a919d5d455561834f3749e877d94c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkVALUHazardsHelper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Def, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 873 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### checkVMEMHazards() {#a5ea029de8448adab49a0cc4cd70c4a8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::checkVMEMHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * VMEM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### computeVALUHazardSGPRs() {#a4979230fe7277c53beca2caf66fb6f9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNHazardRecognizer::computeVALUHazardSGPRs (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MMF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 3139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### createsVALUHazard() {#a1fe98f66ae6ffdd4efa6664e52e25807}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::createsVALUHazard (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 820 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### fixHazards() {#aaa9fc83f306e08ba3ccbcc94fe107d0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNHazardRecognizer::fixHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 1205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### fixLdsBranchVmemWARHazard() {#a9a93a1bd29acf37f29fa1e2ee7292967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNHazardRecognizer::fixLdsBranchVmemWARHazard (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 1469 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### fixLdsDirectVALUHazard() {#ad9d2783ac77d2225ae09de7efc235767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNHazardRecognizer::fixLdsDirectVALUHazard (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 1526 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### fixLdsDirectVMEMHazard() {#afcaba542833f428af170308e01e3c0f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNHazardRecognizer::fixLdsDirectVMEMHazard (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 1570 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### fixRequiredExportPriority() {#a434efe6106ada5eee3c145c4889689ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNHazardRecognizer::fixRequiredExportPriority (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 3400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### fixShift64HighRegBug() {#acb20cedf8327f65fc99cc4faa1309d1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNHazardRecognizer::fixShift64HighRegBug (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 1893 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### fixSMEMtoVectorWriteHazards() {#ad02107aef8be46b34328b8f3ce0a212b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNHazardRecognizer::fixSMEMtoVectorWriteHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 1312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### fixVALUMaskWriteHazard() {#a3db6eab373b949aadac2e8681b9fb210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNHazardRecognizer::fixVALUMaskWriteHazard (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 2990 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### fixVALUPartialForwardingHazard() {#a84b0e78902e2e220d3c4e2d6de2135a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNHazardRecognizer::fixVALUPartialForwardingHazard (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 1610 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### fixVALUReadSGPRHazard() {#a022b19b3afcd78cfde5ccf8318571600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNHazardRecognizer::fixVALUReadSGPRHazard (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 3210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### fixVALUTransUseHazard() {#a63ae3d5013964a753bf8ff01f203ff61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNHazardRecognizer::fixVALUTransUseHazard (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 1759 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### fixVcmpxExecWARHazard() {#af32d940bf9a1836b0558ba3726e6d1d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNHazardRecognizer::fixVcmpxExecWARHazard (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 1399 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### fixVcmpxPermlaneHazards() {#a6e68a89dc2305f024deac6d9463723ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNHazardRecognizer::fixVcmpxPermlaneHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 1231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### fixVMEMtoScalarWriteHazards() {#afc4341d752796207b556ab6af682141c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNHazardRecognizer::fixVMEMtoScalarWriteHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 1265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### fixWMMAHazards() {#a08c8317bcbbdd3a153f102af3236ddea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNHazardRecognizer::fixWMMAHazards (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 1839 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### getMFMAPipelineWaitStates() {#ae9dc4099a4969c8112d94ce9fa7bce6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCNHazardRecognizer::getMFMAPipelineWaitStates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the number of wait states before another MFMA instruction can be issued after <span class="doxyComputerOutput">MI</span>.</p></dd>
</dl>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### getWaitStatesSince() {#a62720f23dfe3563270785b06c2b9de89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::getWaitStatesSince (<a href="#a7927e5acc9828ba4a34fe435c4f37ddd">IsHazardFn</a> IsHazard, int Limit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### getWaitStatesSinceDef() {#a3466993251e5d319a9af26dfb112fe9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::getWaitStatesSinceDef (unsigned Reg, <a href="#a7927e5acc9828ba4a34fe435c4f37ddd">IsHazardFn</a> IsHazardDef, int Limit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### getWaitStatesSinceSetReg() {#ad0ddcf90ab69764b53680fcb99396cbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int GCNHazardRecognizer::getWaitStatesSinceSetReg (<a href="#a7927e5acc9828ba4a34fe435c4f37ddd">IsHazardFn</a> IsHazard, int Limit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### processBundle() {#ac86cd98dd51541213a1a84a13d1e0d76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNHazardRecognizer::processBundle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

### resetClause() {#aafbdfa04e0804a88a2e030789a12caed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GCNHazardRecognizer::resetClause ()</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>.</p>

</div>
</div>

### runOnInstruction() {#ad4f6f501d71cfebb0a4ec85e0f3d1a7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNHazardRecognizer::runOnInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>, definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ClauseDefs {#ace0f92e6a4212fcf0f2a8110e5a8bddd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::GCNHazardRecognizer::ClauseDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RegUnits of defs in the current soft memory clause.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>.</p>

</div>
</div>

### ClauseUses {#a58b4ec303a03b09239a62c3ce25c6f9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::GCNHazardRecognizer::ClauseUses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RegUnits of uses in the current soft memory clause.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>.</p>

</div>
</div>

### CurrCycleInstr {#a6f68a2fc891ae4ef007af303318b6ff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* llvm::GCNHazardRecognizer::CurrCycleInstr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>.</p>

</div>
</div>

### EmittedInstrs {#a117ebb888e61a7dfbc3f037a3fa25ec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::list&lt;MachineInstr*&gt; llvm::GCNHazardRecognizer::EmittedInstrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>.</p>

</div>
</div>

### IsHazardRecognizerMode {#a08b60ae0c53c4c5ef7a87b322531d0cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNHazardRecognizer::IsHazardRecognizerMode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>.</p>

</div>
</div>

### MF {#a5b62d472a54f0afae997f91f6139df3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction&amp; llvm::GCNHazardRecognizer::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>.</p>

</div>
</div>

### RunLdsBranchVmemWARHazardFixup {#af2a7539ec13590f52c16d695360ea344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNHazardRecognizer::RunLdsBranchVmemWARHazardFixup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>.</p>

</div>
</div>

### ST {#a04771e74b94a31a212afe3ad45784fa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget&amp; llvm::GCNHazardRecognizer::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>.</p>

</div>
</div>

### TII {#a1c86127a5322689ccee05246bd7a2f6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIInstrInfo&amp; llvm::GCNHazardRecognizer::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>.</p>

</div>
</div>

### TRI {#a056bcba55cafe536e509c70a46b0ecd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIRegisterInfo&amp; llvm::GCNHazardRecognizer::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>.</p>

</div>
</div>

### TSchedModel {#a6ff9963b4567ed339eb3b49ee7625cee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetSchedModel&amp; llvm::GCNHazardRecognizer::TSchedModel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>.</p>

</div>
</div>

### UseVALUReadHazardExhaustiveSearch {#a7bb7076234d162e31b7c36ce006ed65c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNHazardRecognizer::UseVALUReadHazardExhaustiveSearch</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>.</p>

</div>
</div>

### VALUReadHazardSGPRs {#a34a4ce89441cef94cf15e03c67749ff4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::GCNHazardRecognizer::VALUReadHazardSGPRs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp">GCNHazardRecognizer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-h">GCNHazardRecognizer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
