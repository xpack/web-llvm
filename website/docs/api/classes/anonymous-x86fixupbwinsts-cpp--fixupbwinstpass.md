---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86fixupbwinsts-cpp-/fixupbwinstpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FixupBWInstPass` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{X86FixupBWInsts.cpp}::FixupBWInstPass { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a> - This class adapts the <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> interface to allow convenient creation of passes that operate on the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> representation. <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a510c5ba2b8108db367b50684a96aab50">FixupBWInstPass</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee425fab3143fd1e0cdc4605e73b7f8a">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#aee425fab3143fd1e0cdc4605e73b7f8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a096bbbc9c6acbaab809a2369153f7545">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a096bbbc9c6acbaab809a2369153f7545">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d249baaf63b718978cd27d27731a57b">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> over all of the basic blocks, replacing byte and word instructions by equivalent 32 bit instructions where performance or code size can be improved. <a href="#a6d249baaf63b718978cd27d27731a57b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2f8f35a6671c8b081cb647487a544ec">getRequiredProperties</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75fd223b051e4c54821e2f405f420bc8">processBasicBlock</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> over all of the instructions in the basic block replacing applicable byte or word instructions with better alternatives. <a href="#a75fd223b051e4c54821e2f405f420bc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada7c98d96b2704e903620a0085af1fb8">getSuperRegDestIfDead</a> (MachineInstr *OrigMI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This returns the 32 bit super reg of the original destination register of the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> passed in, if that super register is dead just prior to <span class="doxyComputerOutput">OrigMI</span>. <a href="#ada7c98d96b2704e903620a0085af1fb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97cac6548cb040791b2765a68ea38589">tryReplaceLoad</a> (unsigned New32BitOpcode, MachineInstr *MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> <span class="doxyComputerOutput">MI</span> into the equivalent extending load to 32 bit register if it is safe to do so. <a href="#a97cac6548cb040791b2765a68ea38589">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af72ea8b759fb9cdbcdae50601412c06c">tryReplaceCopy</a> (MachineInstr *MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> <span class="doxyComputerOutput">MI</span> into the equivalent 32-bit copy if it is safe to do so. <a href="#af72ea8b759fb9cdbcdae50601412c06c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a174d25718d5c9b3e30d2c8ac34c52e6b">tryReplaceExtend</a> (unsigned New32BitOpcode, MachineInstr *MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> <span class="doxyComputerOutput">MI</span> into the equivalent extend to 32 bit register if it is safe to do so. <a href="#a174d25718d5c9b3e30d2c8ac34c52e6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa04d2a3c77df62ff92936f6dc6f403bc">tryReplaceInstr</a> (MachineInstr *MI, MachineBasicBlock &amp;MBB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07c7764e7bc42e943cc8eb4631f3ee43">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo">X86InstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d2682c02cfd3f066954dca00d4736ee">TII</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Machine instruction info used throughout the class. <a href="#a4d2682c02cfd3f066954dca00d4736ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7249366b6ea8880161898b992250e67">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f4686a3ab9af8c5c3a3a5e0b568c258">OptForSize</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Local member for function's OptForSize attribute. <a href="#a5f4686a3ab9af8c5c3a3a5e0b568c258">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveregunits">LiveRegUnits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a702c7b540f4009cbeb9c2542d03be4e6">LiveUnits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Liveness information after the current instruction. <a href="#a702c7b540f4009cbeb9c2542d03be4e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7393c86368ccae13ad3c4fb0d35d3c03">PSI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa964a46ff2f584e330e853da8a7317ae">MBFI</a> = nullptr</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa562aa2a8b4edd4404361ed9baaffe14">ID</a> = 0</td>
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


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FixupBWInstPass() {#a510c5ba2b8108db367b50684a96aab50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86FixupBWInsts.cpp}::FixupBWInstPass::FixupBWInstPass ()</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>


<p>References <a href="#aa562aa2a8b4edd4404361ed9baaffe14">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a35a6bc20dd68076af458d8277d7147f2">llvm::createX86FixupBWInsts</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a096bbbc9c6acbaab809a2369153f7545}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{X86FixupBWInsts.cpp}::FixupBWInstPass::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a>.</p>

</div>
</div>

### getPassName() {#aee425fab3143fd1e0cdc4605e73b7f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{X86FixupBWInsts.cpp}::FixupBWInstPass::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp/#a6f0c6e2d31735d29f955d4f69c42ec53">FIXUPBW_DESC</a>.</p>

</div>
</div>

### getRequiredProperties() {#ac2f8f35a6671c8b081cb647487a544ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties anonymous{X86FixupBWInsts.cpp}::FixupBWInstPass::getRequiredProperties ()</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a72f7d830dd5ddb30f06d8e9639558ac3">llvm::MachineFunctionProperties::NoVRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a6d249baaf63b718978cd27d27731a57b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FixupBWInstPass::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> over all of the basic blocks, replacing byte and word instructions by equivalent 32 bit instructions where performance or code size can be improved.</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp/#a4ec8f4ae1f01adcae392bd14002e19ec">FixupBWInsts</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/classes/llvm/functionpass/#af9f5f511d75e16f09a5520cb9444cfa8">llvm::FunctionPass::skipFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getSuperRegDestIfDead() {#ada7c98d96b2704e903620a0085af1fb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FixupBWInstPass::getSuperRegDestIfDead (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * OrigMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This returns the 32 bit super reg of the original destination register of the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> passed in, if that super register is dead just prior to <span class="doxyComputerOutput">OrigMI</span>.</p>


<p>Check if after <span class="doxyComputerOutput">OrigMI</span> the only portion of super register of the destination register of <span class="doxyComputerOutput">OrigMI</span> that is alive is that destination register.</p>


<p>Otherwise it returns <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register()</a>.</p>


<p>If so, return that super register in <span class="doxyComputerOutput">SuperDestReg</span>.</p>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>

</div>
</div>

### processBasicBlock() {#a75fd223b051e4c54821e2f405f420bc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FixupBWInstPass::processBasicBlock (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> over all of the instructions in the basic block replacing applicable byte or word instructions with better alternatives.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>

</div>
</div>

### tryReplaceCopy() {#af72ea8b759fb9cdbcdae50601412c06c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * FixupBWInstPass::tryReplaceCopy (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Change the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> <span class="doxyComputerOutput">MI</span> into the equivalent 32-bit copy if it is safe to do so.</p>


<p>Return the replacement instruction if OK, otherwise return nullptr.</p>


<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>

</div>
</div>

### tryReplaceExtend() {#a174d25718d5c9b3e30d2c8ac34c52e6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * FixupBWInstPass::tryReplaceExtend (unsigned New32BitOpcode, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Change the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> <span class="doxyComputerOutput">MI</span> into the equivalent extend to 32 bit register if it is safe to do so.</p>


<p>Return the replacement instruction if OK, otherwise return nullptr.</p>


<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>

</div>
</div>

### tryReplaceInstr() {#aa04d2a3c77df62ff92936f6dc6f403bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * FixupBWInstPass::tryReplaceInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>

</div>
</div>

### tryReplaceLoad() {#a97cac6548cb040791b2765a68ea38589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * FixupBWInstPass::tryReplaceLoad (unsigned New32BitOpcode, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Change the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> <span class="doxyComputerOutput">MI</span> into the equivalent extending load to 32 bit register if it is safe to do so.</p>


<p>Return the replacement instruction if OK, otherwise return nullptr.</p>


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LiveUnits {#a702c7b540f4009cbeb9c2542d03be4e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRegUnits anonymous{X86FixupBWInsts.cpp}::FixupBWInstPass::LiveUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Liveness information after the current instruction.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>

</div>
</div>

### MBFI {#aa964a46ff2f584e330e853da8a7317ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBlockFrequencyInfo* anonymous{X86FixupBWInsts.cpp}::FixupBWInstPass::MBFI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>

</div>
</div>

### MF {#a07c7764e7bc42e943cc8eb4631f3ee43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* anonymous{X86FixupBWInsts.cpp}::FixupBWInstPass::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>

</div>
</div>

### OptForSize {#a5f4686a3ab9af8c5c3a3a5e0b568c258}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86FixupBWInsts.cpp}::FixupBWInstPass::OptForSize = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Local member for function's OptForSize attribute.</p>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>

</div>
</div>

### PSI {#a7393c86368ccae13ad3c4fb0d35d3c03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfileSummaryInfo* anonymous{X86FixupBWInsts.cpp}::FixupBWInstPass::PSI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>

</div>
</div>

### TII {#a4d2682c02cfd3f066954dca00d4736ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86InstrInfo* anonymous{X86FixupBWInsts.cpp}::FixupBWInstPass::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Machine instruction info used throughout the class.</p>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>

</div>
</div>

### TRI {#ad7249366b6ea8880161898b992250e67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* anonymous{X86FixupBWInsts.cpp}::FixupBWInstPass::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#aa562aa2a8b4edd4404361ed9baaffe14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char anonymous{X86FixupBWInsts.cpp}::FixupBWInstPass::ID = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a>.</p>


<p>Referenced by <a href="#a510c5ba2b8108db367b50684a96aab50">FixupBWInstPass</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupbwinsts-cpp">X86FixupBWInsts.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
