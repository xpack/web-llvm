---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/aarch64calllowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AArch64CallLowering` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::AArch64CallLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">Target/AArch64/GISel/AArch64CallLowering.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/calllowering">CallLowering</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a540c8a1ed937881f5ac8358f2c906c88">RegHandler</a> = std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, unsigned, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp;)&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7716e18b3c825be66cca5545b2dd14d6">MemHandler</a> = std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp;, int, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1ec5e34e707cb712c79df954c11a057">AArch64CallLowering</a> (const AArch64TargetLowering &amp;TLI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a010cf32a5c68f9701c57d7a3172f1b3f">lowerReturn</a> (MachineIRBuilder &amp;MIRBuilder, const Value *Val, ArrayRef&lt; Register &gt; VRegs, FunctionLoweringInfo &amp;FLI, Register SwiftErrorVReg) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower outgoing return values, described by <span class="doxyComputerOutput">Val</span>, into the specified virtual registers <span class="doxyComputerOutput">VRegs</span>. <a href="#a010cf32a5c68f9701c57d7a3172f1b3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a018820d0fb56abe52c51565fb10c19ab">canLowerReturn</a> (MachineFunction &amp;MF, CallingConv::ID CallConv, SmallVectorImpl&lt; BaseArgInfo &gt; &amp;Outs, bool IsVarArg) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to check whether the return values described by <span class="doxyComputerOutput">Outs</span> can fit into the return registers. <a href="#a018820d0fb56abe52c51565fb10c19ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a832615bac3f93933420362ddc592704d">fallBackToDAGISel</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af647b791a2c24c4f48aa11d1a77a5bc5">lowerFormalArguments</a> (MachineIRBuilder &amp;MIRBuilder, const Function &amp;F, ArrayRef&lt; ArrayRef&lt; Register &gt; &gt; VRegs, FunctionLoweringInfo &amp;FLI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower the incoming (formal) arguments, described by <span class="doxyComputerOutput">VRegs</span>, for GlobalISel. <a href="#af647b791a2c24c4f48aa11d1a77a5bc5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad995047f82b555a8ceee0fba2af41899">lowerCall</a> (MachineIRBuilder &amp;MIRBuilder, CallLoweringInfo &amp;Info) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower the given call instruction, including argument and return value marshalling. <a href="#ad995047f82b555a8ceee0fba2af41899">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba8fa9d02ad8b557faaf41b37b714ba4">isEligibleForTailCallOptimization</a> (MachineIRBuilder &amp;MIRBuilder, CallLoweringInfo &amp;Info, SmallVectorImpl&lt; ArgInfo &gt; &amp;InArgs, SmallVectorImpl&lt; ArgInfo &gt; &amp;OutArgs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the call can be lowered as a tail call. <a href="#aba8fa9d02ad8b557faaf41b37b714ba4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad7abed85788794ecd6b41cac4c84096">supportSwiftError</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa832da21e429bb04e91f54ed4667dd0b">isTypeIsValidForThisReturn</a> (EVT Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For targets which support the "returned" parameter attribute, returns true if the given type is a valid one to use with "returned". <a href="#aa832da21e429bb04e91f54ed4667dd0b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ac765591c90b384c7857117c0cfe802">saveVarArgRegisters</a> (MachineIRBuilder &amp;MIRBuilder, CallLowering::IncomingValueHandler &amp;Handler, CCState &amp;CCInfo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5e81985d1a66e10574be63a8f9abd39">lowerTailCall</a> (MachineIRBuilder &amp;MIRBuilder, CallLoweringInfo &amp;Info, SmallVectorImpl&lt; ArgInfo &gt; &amp;OutArgs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af174278d463337987325c25619faf45a">doCallerAndCalleePassArgsTheSameWay</a> (CallLoweringInfo &amp;Info, MachineFunction &amp;MF, SmallVectorImpl&lt; ArgInfo &gt; &amp;InArgs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa13a1b39e44ae097330b1a0559e955ad">areCalleeOutgoingArgsTailCallable</a> (CallLoweringInfo &amp;Info, MachineFunction &amp;MF, SmallVectorImpl&lt; ArgInfo &gt; &amp;OutArgs) const</td>
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


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">AArch64CallLowering.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### MemHandler {#a7716e18b3c825be66cca5545b2dd14d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AArch64CallLowering::MemHandler = 
      std::function&lt;void(MachineIRBuilder &amp;, int, CCValAssign &amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">AArch64CallLowering.h</a>.</p>

</div>
</div>

### RegHandler {#a540c8a1ed937881f5ac8358f2c906c88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AArch64CallLowering::RegHandler =  std::function&lt;void(MachineIRBuilder &amp;, Type *, unsigned,
                                        CCValAssign &amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">AArch64CallLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AArch64CallLowering() {#ad1ec5e34e707cb712c79df954c11a057}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64CallLowering::AArch64CallLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering">AArch64TargetLowering</a> &amp; TLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">AArch64CallLowering.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/calllowering/#aceb7a26daf1242d77d983191579009db">llvm::CallLowering::CallLowering</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### canLowerReturn() {#a018820d0fb56abe52c51565fb10c19ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64CallLowering::canLowerReturn (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/calllowering/basearginfo">BaseArgInfo</a> &gt; &amp; Outs, bool IsVarArg)</td>
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

<p>This hook must be implemented to check whether the return values described by <span class="doxyComputerOutput">Outs</span> can fit into the return registers.</p>


<p>If false is returned, an sret-demotion is performed.</p>


<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">AArch64CallLowering.h</a>, definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/calllowering/#ac7e0c0d229fea8210c669337efd43e2a">llvm::CallLowering::checkReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/calllowering/#ae960af8a6cb8d7ec718c34dcd569d2ec">llvm::CallLowering::getTLI</a>.</p>

</div>
</div>

### fallBackToDAGISel() {#a832615bac3f93933420362ddc592704d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64CallLowering::fallBackToDAGISel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">AArch64CallLowering.h</a>, definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abb8d1b9b7c4af638307e2d5d62f87082">EnableSVEGISel</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### isEligibleForTailCallOptimization() {#aba8fa9d02ad8b557faaf41b37b714ba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64CallLowering::isEligibleForTailCallOptimization (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/structs/llvm/calllowering/callloweringinfo">CallLoweringInfo</a> &amp; Info, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo">ArgInfo</a> &gt; &amp; InArgs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo">ArgInfo</a> &gt; &amp; OutArgs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the call can be lowered as a tail call.</p>

<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">AArch64CallLowering.h</a>, definition at line 920 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a49e6c89ce42a55a93ddf38d21bbd198e">llvm::Function::args</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adbf41e18f7132ffe3bccbcfc61bbd8cf">canGuaranteeTCO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a33fe94054a904130a7c774f78423c8b7">llvm::TargetMachine::getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#ad54fc81a4ef7ab96137a9b6e78fdf838">llvm::TargetOptions::GuaranteedTailCallOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a51af265dc931258cdb8ffb37ee6decee">llvm::GlobalValue::hasExternalWeakLinkage</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae812d40144fafed6fd7c00cffb790504">mayTailCallThisCC</a> and <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a>.</p>


<p>Referenced by <a href="#ad995047f82b555a8ceee0fba2af41899">lowerCall</a>.</p>

</div>
</div>

### isTypeIsValidForThisReturn() {#aa832da21e429bb04e91f54ed4667dd0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64CallLowering::isTypeIsValidForThisReturn (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty)</td>
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

<p>For targets which support the "returned" parameter attribute, returns true if the given type is a valid one to use with "returned".</p>

<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">AArch64CallLowering.h</a>, definition at line 1470 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>

</div>
</div>

### lowerCall() {#ad995047f82b555a8ceee0fba2af41899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64CallLowering::lowerCall (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/structs/llvm/calllowering/callloweringinfo">CallLoweringInfo</a> &amp; Info)</td>
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

<p>This hook must be implemented to lower the given call instruction, including argument and return value marshalling.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the lowering succeeded, false otherwise.</p></dd>
</dl>


<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">AArch64CallLowering.h</a>, definition at line 1259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#a45141d649d02a2ed17b51b5419ee884d">llvm::DstOp::addDefToMIB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca047fefb5017b2873eb2e88f1a27fb14a">llvm::CallingConv::ARM64EC_Thunk_Native</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caf80cc3a71c40926e6c35a60ccdc6428e">llvm::CallingConv::ARM64EC_Thunk_X64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a13ec8ba54ec7daae44e617496a3f74d6">llvm::AArch64FunctionInfo::branchTargetEnforcement</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ae32b6e2213ad3119a124e6e0673a5898">llvm::MachineIRBuilder::buildCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ae04499daa8807ddb4d00e7ed18b1698f">llvm::MachineIRBuilder::buildInstrNoInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a44a49b5f4dd2932058e3fbe21c098655">llvm::MachineIRBuilder::buildZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0de00f38864016881b1182ebac4b7b30">llvm::constrainOperandRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a837dc9f535c4db3c1d4bc3cea1358651">llvm::CallLowering::determineAndHandleAssignments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#abebd7e1cdc2e5773df3b63580c2b359a">doesCalleeRestoreStack</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a44384f1a2c70a34d648ffb22d2c6bfb1">extractPtrauthBlendDiscriminators</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#aa990c8b0771ccafcaded5c6ebb3cbc20">getAssignFnsForCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aaa634580f5cb9e54209fa554bf8fb388">llvm::objcarc::getAttachedARCFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#a633cc7cd1478a82c1a99e2e27829ce04">getCallOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a36aaf68c65aa593a22066976ee02810a">llvm::AArch64Subtarget::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afd34773dd33963769279868ab39d5fdc">llvm::getLLTForType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#a79d70fa60cedff640ded089e56149d24">getMaskForArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a1c5fadb14ff1d77faad0cb58a43252ab">llvm::MachineInstrBuilder::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#af2f55f16e39b3b5b9047278790c2cb15">llvm::AArch64Subtarget::getRegBankInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a9768b8e3c00648b38189b95d6603729b">llvm::TargetSubtargetInfo::getRegBankInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a0c3ed7e8a5fa2d4df05bf0fdf51a6550">llvm::AArch64Subtarget::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#ae960af8a6cb8d7ec718c34dcd569d2ec">llvm::CallLowering::getTLI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#ad54fc81a4ef7ab96137a9b6e78fdf838">llvm::TargetOptions::GuaranteedTailCallOpt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aefba9af2f61452f20f4c947b4c2e5f4e">llvm::objcarc::hasAttachedCallOpBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#afd4bb75fec521c3addcd5ac9d85fdce1">llvm::AArch64Subtarget::hasCustomCallingConv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46aaf2ff1a10f3f3b211d7781a33e4c1e05">llvm::AArch64PACKey::IA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46a438dbcc76b79fb10acb447ec5d141287">llvm::AArch64PACKey::IB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a06dc2f24e1f4dea357bf6c646f5b2607">llvm::MachineIRBuilder::insertInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a33a30176a7fd636333a4e618ef109f57">llvm::CallLowering::insertSRetLoads</a>, <a href="#aba8fa9d02ad8b557faaf41b37b714ba4">isEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#ab11ed6ee239ab7c9328927b7327fc8f1">llvm::AArch64Subtarget::isWindowsArm64EC</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a4144c2ee93286fba09bd8f14fb11f27a">llvm::AArch64II::MO_GOT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo/#a15bd554291a003ec01a0f9e3cbfab8e5">llvm::CallLowering::ArgInfo::Regs</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a57d1263b6f2a16c765d594a59c2f8130">llvm::CallLowering::splitToValueTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/structs/llvm/calllowering/basearginfo/#a4d336cffc2826cb7f708f3228dbd7231">llvm::CallLowering::BaseArgInfo::Ty</a>.</p>

</div>
</div>

### lowerFormalArguments() {#af647b791a2c24c4f48aa11d1a77a5bc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64CallLowering::lowerFormalArguments (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &gt; VRegs, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; FLI)</td>
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

<p>This hook must be implemented to lower the incoming (formal) arguments, described by <span class="doxyComputerOutput">VRegs</span>, for GlobalISel.</p>


<p>Each argument must end up in the related virtual registers described by <span class="doxyComputerOutput">VRegs</span>. In other words, the first argument should end up in <span class="doxyComputerOutput">VRegs</span>[0], the second in <span class="doxyComputerOutput">VRegs</span>[1], and so on. For each argument, there will be one register for each non-aggregate type, as returned by <span class="doxyComputerOutput">computeValueLLTs</span>. <span class="doxyComputerOutput">MIRBuilder</span> is set to the proper insertion for the argument lowering. <span class="doxyComputerOutput">FLI</span> is required for sret demotion.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the lowering succeeded, false otherwise.</p></dd>
</dl>


<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">AArch64CallLowering.h</a>, definition at line 638 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca047fefb5017b2873eb2e88f1a27fb14a">llvm::CallingConv::ARM64EC_Thunk_Native</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caf80cc3a71c40926e6c35a60ccdc6428e">llvm::CallingConv::ARM64EC_Thunk_X64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a6b02e5030940984fb331116653635050">llvm::MachineIRBuilder::buildAssertZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#abf1763199cd36c9253c6f062fa5e973e">llvm::MachineIRBuilder::buildTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a03cf34252938b54f7e86c736f9fd7dc1">llvm::MachineFrameInfo::CreateFixedObject</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#ac6db7ce806dd7cbdce7f3c1b06dcd54e">llvm::CallLowering::determineAssignments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#abebd7e1cdc2e5773df3b63580c2b359a">doesCalleeRestoreStack</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">llvm::AttributeList::FirstArgIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/basearginfo/#a199d61df156e7d358ec1f18205615b1b">llvm::CallLowering::BaseArgInfo::Flags</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ac8f6c5b9180bd630c92e1126877d0b08">llvm::MachineIRBuilder::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a1c5fadb14ff1d77faad0cb58a43252ab">llvm::MachineInstrBuilder::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#ae960af8a6cb8d7ec718c34dcd569d2ec">llvm::CallLowering::getTLI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#ad54fc81a4ef7ab96137a9b6e78fdf838">llvm::TargetOptions::GuaranteedTailCallOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#a133ddcbd001fd6de4f055542a6a95595">handleMustTailForwardedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a78ca5c76a5ac76f5ad51ce5ced36fbb8">llvm::CallLowering::insertSRetIncomingArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo/#a15bd554291a003ec01a0f9e3cbfab8e5">llvm::CallLowering::ArgInfo::Regs</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af835582e4e7766298680c7d01947036e">llvm::CallLowering::setArgFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a4cac2a17ab11d53dd0a49871b80f5c7a">llvm::MachineIRBuilder::setInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#acd5c75a12ec8c12c35de46c60d18c699">llvm::MachineIRBuilder::setMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a57d1263b6f2a16c765d594a59c2f8130">llvm::CallLowering::splitToValueTypes</a> and <a href="/web-llvm/docs/api/structs/llvm/calllowering/basearginfo/#a4d336cffc2826cb7f708f3228dbd7231">llvm::CallLowering::BaseArgInfo::Ty</a>.</p>

</div>
</div>

### lowerReturn() {#a010cf32a5c68f9701c57d7a3172f1b3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64CallLowering::lowerReturn (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; VRegs, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; FLI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SwiftErrorVReg)</td>
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

<p>This hook must be implemented to lower outgoing return values, described by <span class="doxyComputerOutput">Val</span>, into the specified virtual registers <span class="doxyComputerOutput">VRegs</span>.</p>


<p>This hook is used by GlobalISel.</p>


<p><span class="doxyComputerOutput">FLI</span> is required for sret demotion.</p>


<p><span class="doxyComputerOutput">SwiftErrorVReg</span> is non-zero if the function has a swifterror parameter that needs to be implicitly returned.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the lowering succeeds, false otherwise.</p></dd>
</dl>


<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">AArch64CallLowering.h</a>, definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ae32b6e2213ad3119a124e6e0673a5898">llvm::MachineIRBuilder::buildCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ae04499daa8807ddb4d00e7ed18b1698f">llvm::MachineIRBuilder::buildInstrNoInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a901a49f9b5721ab01d9d371f96e4bcea">llvm::MachineIRBuilder::buildPadVectorWithUndefElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a44a49b5f4dd2932058e3fbe21c098655">llvm::MachineIRBuilder::buildZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab99618b3d8988b758a67f5a1a6071095">llvm::ComputeValueVTs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a837dc9f535c4db3c1d4bc3cea1358651">llvm::CallLowering::determineAndHandleAssignments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/basearginfo/#a199d61df156e7d358ec1f18205615b1b">llvm::CallLowering::BaseArgInfo::Flags</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afd34773dd33963769279868ab39d5fdc">llvm::getLLTForType</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a1c5fadb14ff1d77faad0cb58a43252ab">llvm::MachineInstrBuilder::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#ae960af8a6cb8d7ec718c34dcd569d2ec">llvm::CallLowering::getTLI</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ab0cfceeb37508e56f9c127e59766a668">llvm::EVT::getTypeForEVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a06dc2f24e1f4dea357bf6c646f5b2607">llvm::MachineIRBuilder::insertInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a852a45fa0766bf5cb65ea6010d32330a">llvm::CallLowering::insertSRetStores</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a425636b56fa037ed7b19ef7f9de30df9">llvm::MVT::isVector</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo/#a15bd554291a003ec01a0f9e3cbfab8e5">llvm::CallLowering::ArgInfo::Regs</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df">llvm::AttributeList::ReturnIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af835582e4e7766298680c7d01947036e">llvm::CallLowering::setArgFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a57d1263b6f2a16c765d594a59c2f8130">llvm::CallLowering::splitToValueTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a> and <a href="/web-llvm/docs/api/structs/llvm/calllowering/basearginfo/#a4d336cffc2826cb7f708f3228dbd7231">llvm::CallLowering::BaseArgInfo::Ty</a>.</p>

</div>
</div>

### supportSwiftError() {#aad7abed85788794ecd6b41cac4c84096}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AArch64CallLowering::supportSwiftError ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the target is capable of handling swifterror values that have been promoted to a specified register. The extended versions of lowerReturn and lowerCall should be implemented.</p></dd>
</dl>


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">AArch64CallLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### areCalleeOutgoingArgsTailCallable() {#aa13a1b39e44ae097330b1a0559e955ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64CallLowering::areCalleeOutgoingArgsTailCallable (<a href="/web-llvm/docs/api/structs/llvm/calllowering/callloweringinfo">CallLoweringInfo</a> &amp; Info, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo">ArgInfo</a> &gt; &amp; OutArgs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">AArch64CallLowering.h</a>, definition at line 853 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>

</div>
</div>

### doCallerAndCalleePassArgsTheSameWay() {#af174278d463337987325c25619faf45a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64CallLowering::doCallerAndCalleePassArgsTheSameWay (<a href="/web-llvm/docs/api/structs/llvm/calllowering/callloweringinfo">CallLoweringInfo</a> &amp; Info, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo">ArgInfo</a> &gt; &amp; InArgs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">AArch64CallLowering.h</a>, definition at line 810 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>

</div>
</div>

### lowerTailCall() {#ad5e81985d1a66e10574be63a8f9abd39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64CallLowering::lowerTailCall (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/structs/llvm/calllowering/callloweringinfo">CallLoweringInfo</a> &amp; Info, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo">ArgInfo</a> &gt; &amp; OutArgs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">AArch64CallLowering.h</a>, definition at line 1081 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>

</div>
</div>

### saveVarArgRegisters() {#a3ac765591c90b384c7857117c0cfe802}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64CallLowering::saveVarArgRegisters (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvaluehandler">CallLowering::IncomingValueHandler</a> &amp; Handler, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; CCInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">AArch64CallLowering.h</a>, definition at line 551 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">AArch64CallLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
