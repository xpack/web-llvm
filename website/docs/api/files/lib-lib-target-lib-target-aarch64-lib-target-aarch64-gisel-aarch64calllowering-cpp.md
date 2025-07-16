---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AArch64CallLowering.cpp` File Reference

<p>This file implements the lowering of LLVM calls to machine code calls for GlobalISel. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">AArch64CallLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64globaliselutils-h">AArch64GlobalISelUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-h">AArch64ISelLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">Utils/AArch64SMEAttributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcutil-h">llvm/Analysis/ObjCARCUtil.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/analysis-h">llvm/CodeGen/Analysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">llvm/CodeGen/CallingConvLower.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">llvm/CodeGen/FunctionLoweringInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">llvm/CodeGen/GlobalISel/MachineIRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/utils-h">llvm/CodeGen/GlobalISel/Utils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lowleveltypeutils-h">llvm/CodeGen/LowLevelTypeUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">llvm/CodeGen/MachineMemOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">llvm/CodeGen/ValueTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/machinevaluetype-h">llvm/CodeGenTypes/MachineValueType.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">llvm/IR/Argument.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-aarch64calllowering-cpp-">anonymous{AArch64CallLowering.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/aarch64incomingvalueassigner">AArch64IncomingValueAssigner</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/aarch64outgoingvalueassigner">AArch64OutgoingValueAssigner</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/incomingarghandler">IncomingArgHandler</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/formalarghandler">FormalArgHandler</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/callreturnhandler">CallReturnHandler</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/returnedargcallreturnhandler">ReturnedArgCallReturnHandler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A special return arg handler for "returned" attribute arg calls. <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/returnedargcallreturnhandler/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler">OutgoingArgHandler</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a1ffccd0b7e439109060f4d29334142">applyStackPassedSmallTypeDAGHack</a> (EVT OrigVT, MVT &amp;ValVT, MVT &amp;LocVT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77c170f4c52ebc0ecaeaae4a2b660916">getStackValueStoreTypeHack</a> (const CCValAssign &amp;VA)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abebd7e1cdc2e5773df3b63580c2b359a">doesCalleeRestoreStack</a> (CallingConv::ID CallConv, bool TailCallOpt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a133ddcbd001fd6de4f055542a6a95595">handleMustTailForwardedRegisters</a> (MachineIRBuilder &amp;MIRBuilder, CCAssignFn *AssignFn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to compute forwarded registers for musttail calls. <a href="#a133ddcbd001fd6de4f055542a6a95595">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbf41e18f7132ffe3bccbcfc61bbd8cf">canGuaranteeTCO</a> (CallingConv::ID CC, bool GuaranteeTailCalls)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the calling convention is one that we can guarantee TCO for. <a href="#adbf41e18f7132ffe3bccbcfc61bbd8cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae812d40144fafed6fd7c00cffb790504">mayTailCallThisCC</a> (CallingConv::ID CC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we might ever do TCO for calls with this calling convention. <a href="#ae812d40144fafed6fd7c00cffb790504">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; CCAssignFn *, CCAssignFn * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa990c8b0771ccafcaded5c6ebb3cbc20">getAssignFnsForCC</a> (CallingConv::ID CC, const AArch64TargetLowering &amp;TLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pair containing the fixed <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> and the vararg <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> for CC. <a href="#aa990c8b0771ccafcaded5c6ebb3cbc20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a633cc7cd1478a82c1a99e2e27829ce04">getCallOpcode</a> (const MachineFunction &amp;CallerF, bool IsIndirect, bool IsTailCall, std::optional&lt; CallLowering::PtrAuthInfo &gt; &amp;PAI, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79d70fa60cedff640ded089e56149d24">getMaskForArgs</a> (SmallVectorImpl&lt; AArch64CallLowering::ArgInfo &gt; &amp;OutArgs, AArch64CallLowering::CallLoweringInfo &amp;Info, const AArch64RegisterInfo &amp;TRI, MachineFunction &amp;MF)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ee380f80cf8e9ba2b9b1e905d4d32b8">EnableSVEGISel</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"aarch64-call-lowering"</td>
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

<p>This file implements the lowering of LLVM calls to machine code calls for GlobalISel.</p>

<div class="doxySectionDef">

## Functions

### applyStackPassedSmallTypeDAGHack() {#a9a1ffccd0b7e439109060f4d29334142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void applyStackPassedSmallTypeDAGHack (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> OrigVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; LocVT)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/aarch64incomingvalueassigner/#ab3273cbfc9062af3ad87335857ad782f">anonymous{AArch64CallLowering.cpp}::AArch64IncomingValueAssigner::assignArg</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/aarch64outgoingvalueassigner/#a4e31012ae290be156077d90c19f46432">anonymous{AArch64CallLowering.cpp}::AArch64OutgoingValueAssigner::assignArg</a>.</p>

</div>
</div>

### canGuaranteeTCO() {#adbf41e18f7132ffe3bccbcfc61bbd8cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canGuaranteeTCO (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, bool GuaranteeTailCalls)</td>
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

<p>Return true if the calling convention is one that we can guarantee TCO for.</p>

<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae64b7afe33922c60d78fea3c08697daa">llvm::CallingConv::SwiftTail</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad6e9c0ff694f0fca0222e79e772b647e">llvm::CallingConv::Tail</a>.</p>

</div>
</div>

### doesCalleeRestoreStack() {#abebd7e1cdc2e5773df3b63580c2b359a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool doesCalleeRestoreStack (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallConv, bool TailCallOpt)</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae64b7afe33922c60d78fea3c08697daa">llvm::CallingConv::SwiftTail</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad6e9c0ff694f0fca0222e79e772b647e">llvm::CallingConv::Tail</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#af647b791a2c24c4f48aa11d1a77a5bc5">llvm::AArch64CallLowering::lowerFormalArguments</a>.</p>

</div>
</div>

### getAssignFnsForCC() {#aa990c8b0771ccafcaded5c6ebb3cbc20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; CCAssignFn *, CCAssignFn * &gt; getAssignFnsForCC (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering">AArch64TargetLowering</a> &amp; TLI)</td>
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

<p>Returns a pair containing the fixed <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> and the vararg <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> for CC.</p>

<p>Definition at line 806 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a52a3cbd48589c37855abca181342ccb7">llvm::AArch64TargetLowering::CCAssignFnForCall</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a8b1432c767e3cc50f7cb6900285d003f">llvm::AMDGPUCallLowering::areCalleeOutgoingArgsTailCallable</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ae513c203a406e1186d2342cbdbf95765">llvm::AMDGPUCallLowering::doCallerAndCalleePassArgsTheSameWay</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ae1eb226b5600f7802dc31d1903a5040e">llvm::AMDGPUCallLowering::lowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a0c3beb54f8fa06f2fd8074561a5a515c">llvm::AMDGPUCallLowering::lowerTailCall</a>.</p>

</div>
</div>

### getCallOpcode() {#a633cc7cd1478a82c1a99e2e27829ce04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getCallOpcode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; CallerF, bool IsIndirect, bool IsTailCall, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/calllowering/ptrauthinfo">CallLowering::PtrAuthInfo</a> &gt; &amp; PAI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 1022 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a91375dbee36ddeeee15b974e39782c">llvm::getBLRCallOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46aaf2ff1a10f3f3b211d7781a33e4c1e05">llvm::AArch64PACKey::IA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64packey/#abf4394f452bde3f544999858d71e4b46a438dbcc76b79fb10acb447ec5d141287">llvm::AArch64PACKey::IB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ae1eb226b5600f7802dc31d1903a5040e">llvm::AMDGPUCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/armcalllowering/#af3fdfad8a2951ca4c86fd64560c550a7">llvm::ARMCallLowering::lowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a0c3beb54f8fa06f2fd8074561a5a515c">llvm::AMDGPUCallLowering::lowerTailCall</a>.</p>

</div>
</div>

### getMaskForArgs() {#a79d70fa60cedff640ded089e56149d24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * getMaskForArgs (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; AArch64CallLowering::ArgInfo &gt; &amp; OutArgs, AArch64CallLowering::CallLoweringInfo &amp; Info, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo">AArch64RegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 1064 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>.</p>

</div>
</div>

### getStackValueStoreTypeHack() {#a77c170f4c52ebc0ecaeaae4a2b660916}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT getStackValueStoreTypeHack (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#ab7c2e47e51795ce2f60500846109d5a7">llvm::CCValAssign::getLocVT</a> and <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a5972ab02a98f9b5ce46e7f55fd711982">llvm::CCValAssign::getValVT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/incomingarghandler/#ad743c42316a13699646a3ed402aab910">anonymous{AArch64CallLowering.cpp}::IncomingArgHandler::getStackValueStoreType</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#a2ac99436d5d4df441878ecb554975338">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::getStackValueStoreType</a>.</p>

</div>
</div>

### handleMustTailForwardedRegisters() {#a133ddcbd001fd6de4f055542a6a95595}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void handleMustTailForwardedRegisters (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, CCAssignFn * AssignFn)</td>
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

<p>Helper function to compute forwarded registers for musttail calls.</p>


<p>Computes the forwarded registers, sets MBB liveness, and emits COPY instructions that can be used to save + restore registers later.</p>


<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac9cfa172b885cad0eba3d7c9527568ad">llvm::MachineFunction::addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a1c90a7c05cf18d20a847ded8bc3f0dc8">llvm::CCState::analyzeMustTailForwardedRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ae32b6e2213ad3119a124e6e0673a5898">llvm::MachineIRBuilder::buildCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ac8f6c5b9180bd630c92e1126877d0b08">llvm::MachineIRBuilder::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a7819a781e436c677ed1613c7739ee53e">llvm::MachineFrameInfo::hasMustTailInVarArgFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#ae175b31af8d3499f652b5658c385af9c">llvm::CCState::isAllocated</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#af647b791a2c24c4f48aa11d1a77a5bc5">llvm::AArch64CallLowering::lowerFormalArguments</a>.</p>

</div>
</div>

### mayTailCallThisCC() {#ae812d40144fafed6fd7c00cffb790504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool mayTailCallThisCC (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC)</td>
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

<p>Return true if we might ever do TCO for calls with this calling convention.</p>

<p>Definition at line 787 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca9f6ac05d37c2fbf197de42295c23fd6e">llvm::CallingConv::PreserveAll</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca4eeb29fe27dc20afa4f443765f45f9a5">llvm::CallingConv::PreserveMost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad5385f408f537fc279d485c77d2463ce">llvm::CallingConv::PreserveNone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca2740493172a4ce246941c8cff95e0f83">llvm::CallingConv::Swift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae64b7afe33922c60d78fea3c08697daa">llvm::CallingConv::SwiftTail</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad6e9c0ff694f0fca0222e79e772b647e">llvm::CallingConv::Tail</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### EnableSVEGISel {#a4ee380f80cf8e9ba2b9b1e905d4d32b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt;bool&gt; EnableSVEGISel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"aarch64-call-lowering"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
