---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/targetsubtargetinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TargetSubtargetInfo` Class

<p><a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> - Generic base class for all target subtargets. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::TargetSubtargetInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generic base class for all target subtargets. <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20310fa71bf28c3b31d0eb7ec699d21b">AntiDepBreakMode</a> = enum { ANTIDEP_NONE, ANTIDEP_CRITICAL, ANTIDEP_ALL }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24e0be4e8e0875ea7cf4dd3d20c11662">RegClassVector</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec9ab6801759237bf7686788919afdd4">TargetSubtargetInfo</a> ()=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dcc67e69eb59bda015cba5764f1091a">TargetSubtargetInfo</a> (const TargetSubtargetInfo &amp;)=delete</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7850b7517ef8d967cbda198d068f2c0e">TargetSubtargetInfo</a> (const Triple &amp;TT, StringRef CPU, StringRef TuneCPU, StringRef FS, ArrayRef&lt; StringRef &gt; PN, ArrayRef&lt; SubtargetFeatureKV &gt; PF, ArrayRef&lt; SubtargetSubTypeKV &gt; PD, const MCWriteProcResEntry *WPR, const MCWriteLatencyEntry *WL, const MCReadAdvanceEntry *RA, const InstrStage *IS, const unsigned *OC, const unsigned *FP)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16f5fc5b50a25526ccc86154ee2274a9">~TargetSubtargetInfo</a> () override</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefedf8107aca8dd85688d3d658b4833a">operator=</a> (const TargetSubtargetInfo &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9546854031006fe46295d6430e170861">isXRaySupported</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd858ed72f11db9444617740c3622608">getInstrInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetframelowering">TargetFrameLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac83b44e69c9f9f4f9d60be2d72f4a5df">getFrameLowering</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade3f0d8b35d67c43df9425bb730a9a7c">getTargetLowering</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectiondagtargetinfo">SelectionDAGTargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3182b054aa29b9217d2a8cb49da7d0ce">getSelectionDAGInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/calllowering">CallLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9263ace85b7b15b4c903861b1f95e070">getCallLowering</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering">InlineAsmLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4341b7e26ad29a79755ada4880ad2a61">getInlineAsmLowering</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructionselector">InstructionSelector</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa155e32874c34aa7b0a547992467074c">getInstructionSelector</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/registerscheduler/#a8fdd27818bcec505142aad630a5f05bf">RegisterScheduler::FunctionPassCtor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d190c7d762432bbd9cfd0614e70c7bd">getDAGScheduler</a> (CodeGenOptLevel) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> can subclass this hook to select a different DAG scheduler. <a href="#a7d190c7d762432bbd9cfd0614e70c7bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc4d15552b6f7e8b121a84146a69aa59">getLegalizerInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43c530c830206ecf5ad3359364634c75">getRegisterInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getRegisterInfo - If register information is available, return it. <a href="#a43c530c830206ecf5ad3359364634c75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9768b8e3c00648b38189b95d6603729b">getRegBankInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the information for the register banks is available, return it. <a href="#a9768b8e3c00648b38189b95d6603729b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1f9b65239ddc3a0662b679817e477d3">getInstrItineraryData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getInstrItineraryData - Returns instruction itinerary data for the target or specific subtarget. <a href="#ae1f9b65239ddc3a0662b679817e477d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7cda8924c60f445e822e54c32c42314">resolveSchedClass</a> (unsigned SchedClass, const MachineInstr *MI, const TargetSchedModel *SchedModel) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resolve a SchedClass at runtime, where SchedClass identifies an <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> with the isVariant property. <a href="#ae7cda8924c60f445e822e54c32c42314">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfcd25a347c1a8e63210e7b2c6ee8910">isZeroIdiom</a> (const MachineInstr *MI, APInt &amp;Mask) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if MI is a dependency breaking zero-idiom instruction for the subtarget. <a href="#acfcd25a347c1a8e63210e7b2c6ee8910">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86428c2c5b7e83ae2ca900eee58b3cb7">isDependencyBreaking</a> (const MachineInstr *MI, APInt &amp;Mask) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if MI is a dependency breaking instruction for the subtarget. <a href="#a86428c2c5b7e83ae2ca900eee58b3cb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd3542c354313777c3eaf1af365604d2">isOptimizableRegisterMove</a> (const MachineInstr *MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if MI is a candidate for move elimination. <a href="#acd3542c354313777c3eaf1af365604d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73d86eabd25d4e6a05310e1b0d445d0a">enableMachineScheduler</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the subtarget should run MachineScheduler after aggressive coalescing. <a href="#a73d86eabd25d4e6a05310e1b0d445d0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2b45ae427a9b2704c82e120d1a94e09">enableMachineSchedDefaultSched</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the machine scheduler should disable the TLI preference for preRA scheduling with the source level scheduler. <a href="#ad2b45ae427a9b2704c82e120d1a94e09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab66dcbfe4b57f7aca196b4c438265f33">enableMachinePipeliner</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the subtarget should run <a href="/web-llvm/docs/api/classes/llvm/machinepipeliner">MachinePipeliner</a>. <a href="#ab66dcbfe4b57f7aca196b4c438265f33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa41488f6e5ff65d6b07002bb75bf3fbc">enableWindowScheduler</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the subtarget should run <a href="/web-llvm/docs/api/classes/llvm/windowscheduler">WindowScheduler</a>. <a href="#aa41488f6e5ff65d6b07002bb75bf3fbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1322687bebc99c66aa3e9ed55b4e384d">enableJoinGlobalCopies</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the subtarget should enable joining global copies. <a href="#a1322687bebc99c66aa3e9ed55b4e384d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8d442c18b35ab8bc3468c1e9de23791">enablePostRAScheduler</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the subtarget should run a scheduler after register allocation. <a href="#ad8d442c18b35ab8bc3468c1e9de23791">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4787adecfc77e72db225098a27e902f">enablePostRAMachineScheduler</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the subtarget should run a machine scheduler after register allocation. <a href="#ab4787adecfc77e72db225098a27e902f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5533c55bedcb5ac86e6820a33fb1c54">enableAtomicExpand</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the subtarget should run the atomic expansion pass. <a href="#ab5533c55bedcb5ac86e6820a33fb1c54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a2a680f3fb5e79a36b487875c32b28e">enableIndirectBrExpand</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the subtarget should run the indirectbr expansion pass. <a href="#a1a2a680f3fb5e79a36b487875c32b28e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cd7c54e0bb13cc01c4e2a4133a40ee4">overrideSchedPolicy</a> (MachineSchedPolicy &amp;Policy, unsigned NumRegionInstrs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Override generic scheduling policy within a region. <a href="#a9cd7c54e0bb13cc01c4e2a4133a40ee4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a960319789166bad30f214270de5cbadc">overridePostRASchedPolicy</a> (MachineSchedPolicy &amp;Policy, unsigned NumRegionInstrs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Override generic post-ra scheduling policy within a region. <a href="#a960319789166bad30f214270de5cbadc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf5c4a8fcde1c8d68eb146f5a54a2b6e">adjustSchedDependency</a> (SUnit *Def, int DefOpIdx, SUnit *Use, int UseOpIdx, SDep &amp;Dep, const TargetSchedModel *SchedModel) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a20310fa71bf28c3b31d0eb7ec699d21b">AntiDepBreakMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa227d641b2159afa4daf982ce65bc2e3">getAntiDepBreakMode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72693146cc01946f26dd28429813dd60">getCriticalPathRCs</a> (RegClassVector &amp;CriticalPathRCs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa483766fca31e32c897fe8f80f74dc99">getPostRAMutations</a> (std::vector&lt; std::unique_ptr&lt; ScheduleDAGMutation &gt; &gt; &amp;Mutations) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8880b0b91cfcde86e7a0bc1eb6f76c3">getSMSMutations</a> (std::vector&lt; std::unique_ptr&lt; ScheduleDAGMutation &gt; &gt; &amp;Mutations) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdc20e43d0f27d58b009b63f13e77d13">useDFAforSMS</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default to DFA for resource management, return false when target will use ProcResource in InstrSchedModel instead. <a href="#abdc20e43d0f27d58b009b63f13e77d13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7482dee387d6747dd3568405c23a6ca2">getOptLevelToEnablePostRAScheduler</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cf770b7582a2f3b2c94beb494411300">enableRALocalReassignment</a> (CodeGenOptLevel OptLevel) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the subtarget should run the local reassignment heuristic of the register allocator. <a href="#a2cf770b7582a2f3b2c94beb494411300">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97ec020f20d345ae76e9b1ff450b4ffa">useAA</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable use of alias analysis during code generation (during MI scheduling, DAGCombine, etc.). <a href="#a97ec020f20d345ae76e9b1ff450b4ffa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adea7a4bec1046f6dd5631da25567a5b7">addrSinkUsingGEPs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sink addresses into blocks using GEP instructions rather than pointer casts and arithmetic. <a href="#adea7a4bec1046f6dd5631da25567a5b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe6b98d9295d887d7fcb20f3de92517b">enableEarlyIfConversion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable the use of the early if conversion pass. <a href="#afe6b98d9295d887d7fcb20f3de92517b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/pbqpraconstraint">PBQPRAConstraint</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ff3040546aa8fcdf80dea4034a60d96">getCustomPBQPConstraints</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return PBQPConstraint(s) for the target. <a href="#a5ff3040546aa8fcdf80dea4034a60d96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada8a311babe7128c11eaf0ad96547ae6">enableSubRegLiveness</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable tracking of subregister liveness in register allocator. <a href="#ada8a311babe7128c11eaf0ad96547ae6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e6de090b178b663c02bc8aa8fe70226">mirFileLoaded</a> (MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is called after a .mir file was loaded. <a href="#a9e6de090b178b663c02bc8aa8fe70226">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab386dc282b4697d60f1b18ce4fcd9ebf">ignoreCSRForAllocationOrder</a> (const MachineFunction &amp;MF, MCRegister PhysReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the register allocator should use the allocation orders exactly as written in the tablegen descriptions, false if it should allocate the specified physical register later if is it callee-saved. <a href="#ab386dc282b4697d60f1b18ce4fcd9ebf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06ed906f1e155330fa9285701f72699c">classifyGlobalFunctionReference</a> (const GlobalValue *GV) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Classify a global function reference. <a href="#a06ed906f1e155330fa9285701f72699c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e3393909f8a847b514c6f58aa9eaf78">enableSpillageCopyElimination</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable spillage copy elimination in MachineCopyPropagation pass. <a href="#a7e3393909f8a847b514c6f58aa9eaf78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#ac5568be97a1abc55d2f87879b25b6c94">MacroFusionPredTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b74e2ebb235e247397d5d87df776e66">getMacroFusions</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the list of MacroFusion predicates. <a href="#a2b74e2ebb235e247397d5d87df776e66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aaf1fab9cff75e1a6cd2ead43d55503">requiresDisjointEarlyClobberAndUndef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the target has instructions where an early-clobber result operand cannot overlap with an undef input operand. <a href="#a0aaf1fab9cff75e1a6cd2ead43d55503">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f331edcb998d10d8fb1608935eb6c7e">isRegisterReservedByUser</a> (Register R) const</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> - Generic base class for all target subtargets.</p>


<p>All Target-specific options that control code generation and printing should be exposed through a TargetSubtargetInfo-derived class.</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### AntiDepBreakMode {#a20310fa71bf28c3b31d0eb7ec699d21b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::TargetSubtargetInfo::AntiDepBreakMode =  enum { ANTIDEP_NONE, ANTIDEP_CRITICAL, ANTIDEP_ALL }</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>

</div>
</div>

### RegClassVector {#a24e0be4e8e0875ea7cf4dd3d20c11662}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::TargetSubtargetInfo::RegClassVector =  SmallVectorImpl&lt;const TargetRegisterClass *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TargetSubtargetInfo() {#aec9ab6801759237bf7686788919afdd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetSubtargetInfo::TargetSubtargetInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>

</div>
</div>

### TargetSubtargetInfo() {#a9dcc67e69eb59bda015cba5764f1091a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetSubtargetInfo::TargetSubtargetInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Reference <a href="#a7850b7517ef8d967cbda198d068f2c0e">TargetSubtargetInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### TargetSubtargetInfo() {#a7850b7517ef8d967cbda198d068f2c0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetSubtargetInfo::TargetSubtargetInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; PN, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/subtargetfeaturekv">SubtargetFeatureKV</a> &gt; PF, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/subtargetsubtypekv">SubtargetSubTypeKV</a> &gt; PD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcwriteprocresentry">MCWriteProcResEntry</a> * WPR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcwritelatencyentry">MCWriteLatencyEntry</a> * WL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcreadadvanceentry">MCReadAdvanceEntry</a> * RA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/instrstage">InstrStage</a> * IS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned * OC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned * FP)</td>
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



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetsubtargetinfo-cpp">TargetSubtargetInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">FP</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#acd6b8a57e9cc0d8ccf8e91a08937bbdf">llvm::MCSubtargetInfo::MCSubtargetInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a>.</p>


<p>Referenced by <a href="#aefedf8107aca8dd85688d3d658b4833a">operator=</a> and <a href="#a9dcc67e69eb59bda015cba5764f1091a">TargetSubtargetInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~TargetSubtargetInfo() {#a16f5fc5b50a25526ccc86154ee2274a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetSubtargetInfo::~TargetSubtargetInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#aefedf8107aca8dd85688d3d658b4833a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetSubtargetInfo &amp; llvm::TargetSubtargetInfo::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Reference <a href="#a7850b7517ef8d967cbda198d068f2c0e">TargetSubtargetInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addrSinkUsingGEPs() {#adea7a4bec1046f6dd5631da25567a5b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetSubtargetInfo::addrSinkUsingGEPs ()</td>
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

<p>Sink addresses into blocks using GEP instructions rather than pointer casts and arithmetic.</p>

<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Reference <a href="#a97ec020f20d345ae76e9b1ff450b4ffa">useAA</a>.</p>

</div>
</div>

### adjustSchedDependency() {#abf5c4a8fcde1c8d68eb146f5a54a2b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetSubtargetInfo::adjustSchedDependency (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * Def, int DefOpIdx, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * Use, int UseOpIdx, <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; Dep, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> * SchedModel)</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>

</div>
</div>

### classifyGlobalFunctionReference() {#a06ed906f1e155330fa9285701f72699c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned char llvm::TargetSubtargetInfo::classifyGlobalFunctionReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
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

<p>Classify a global function reference.</p>


<p>This mainly used to fetch target special flags for lowering a function address. For example mark a function call should be plt or pc-related addressing.</p>


<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>

</div>
</div>

### enableAtomicExpand() {#ab5533c55bedcb5ac86e6820a33fb1c54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetSubtargetInfo::enableAtomicExpand ()</td>
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

<p>True if the subtarget should run the atomic expansion pass.</p>

<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetsubtargetinfo-cpp">TargetSubtargetInfo.cpp</a>.</p>

</div>
</div>

### enableEarlyIfConversion() {#afe6b98d9295d887d7fcb20f3de92517b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetSubtargetInfo::enableEarlyIfConversion ()</td>
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

<p>Enable the use of the early if conversion pass.</p>

<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/earlyifconverter/#a0275a0186010a2c4472194dc40f10f01">anonymous{EarlyIfConversion.cpp}::EarlyIfConverter::run</a>.</p>

</div>
</div>

### enableIndirectBrExpand() {#a1a2a680f3fb5e79a36b487875c32b28e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetSubtargetInfo::enableIndirectBrExpand ()</td>
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

<p>True if the subtarget should run the indirectbr expansion pass.</p>

<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetsubtargetinfo-cpp">TargetSubtargetInfo.cpp</a>.</p>

</div>
</div>

### enableJoinGlobalCopies() {#a1322687bebc99c66aa3e9ed55b4e384d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetSubtargetInfo::enableJoinGlobalCopies ()</td>
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

<p>True if the subtarget should enable joining global copies.</p>


<p>By default this is enabled if the machine scheduler is enabled, but can be overridden.</p>


<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetsubtargetinfo-cpp">TargetSubtargetInfo.cpp</a>.</p>


<p>Reference <a href="#a73d86eabd25d4e6a05310e1b0d445d0a">enableMachineScheduler</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/registercoalescer/#aa408ab9747b8ce0bd0a81465c10e8f29">anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::runOnMachineFunction</a>.</p>

</div>
</div>

### enableMachinePipeliner() {#ab66dcbfe4b57f7aca196b4c438265f33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetSubtargetInfo::enableMachinePipeliner ()</td>
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

<p>True if the subtarget should run <a href="/web-llvm/docs/api/classes/llvm/machinepipeliner">MachinePipeliner</a>.</p>

<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>

</div>
</div>

### enableMachineSchedDefaultSched() {#ad2b45ae427a9b2704c82e120d1a94e09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetSubtargetInfo::enableMachineSchedDefaultSched ()</td>
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

<p>True if the machine scheduler should disable the TLI preference for preRA scheduling with the source level scheduler.</p>

<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>

</div>
</div>

### enableMachineScheduler() {#a73d86eabd25d4e6a05310e1b0d445d0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetSubtargetInfo::enableMachineScheduler ()</td>
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

<p>True if the subtarget should run MachineScheduler after aggressive coalescing.</p>


<p>This currently replaces the <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> scheduler with the "source" order scheduler (though see below for an option to turn this off and use the <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> preference). It does not yet disable the postRA scheduler.</p>


<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetsubtargetinfo-cpp">TargetSubtargetInfo.cpp</a>.</p>


<p>Referenced by <a href="#a1322687bebc99c66aa3e9ed55b4e384d">enableJoinGlobalCopies</a>, <a href="#ab4787adecfc77e72db225098a27e902f">enablePostRAMachineScheduler</a> and <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machinescheduler/#a8539983d1d0a8b07d92b91c16b9f7a5a">anonymous{MachineScheduler.cpp}::MachineScheduler::runOnMachineFunction</a>.</p>

</div>
</div>

### enablePostRAMachineScheduler() {#ab4787adecfc77e72db225098a27e902f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetSubtargetInfo::enablePostRAMachineScheduler ()</td>
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

<p>True if the subtarget should run a machine scheduler after register allocation.</p>

<p>Declaration at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetsubtargetinfo-cpp">TargetSubtargetInfo.cpp</a>.</p>


<p>References <a href="#a73d86eabd25d4e6a05310e1b0d445d0a">enableMachineScheduler</a> and <a href="#ad8d442c18b35ab8bc3468c1e9de23791">enablePostRAScheduler</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/postmachinescheduler/#ab1dc85fd08ff7aa2a4057683e7a4dc8f">anonymous{MachineScheduler.cpp}::PostMachineScheduler::runOnMachineFunction</a>.</p>

</div>
</div>

### enablePostRAScheduler() {#ad8d442c18b35ab8bc3468c1e9de23791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetSubtargetInfo::enablePostRAScheduler ()</td>
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

<p>True if the subtarget should run a scheduler after register allocation.</p>


<p>By default this queries the PostRAScheduling bit in the scheduling model which is the preferred way to influence this.</p>


<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetsubtargetinfo-cpp">TargetSubtargetInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#af907ecc18c1f4f0bce8a9e2eb449ffb8">llvm::MCSubtargetInfo::getSchedModel</a> and <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#a217252d2d49715e81f43a0d313e4f646">llvm::MCSchedModel::PostRAScheduler</a>.</p>


<p>Referenced by <a href="#ab4787adecfc77e72db225098a27e902f">enablePostRAMachineScheduler</a>.</p>

</div>
</div>

### enableRALocalReassignment() {#a2cf770b7582a2f3b2c94beb494411300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetSubtargetInfo::enableRALocalReassignment (<a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OptLevel)</td>
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

<p>True if the subtarget should run the local reassignment heuristic of the register allocator.</p>


<p>This heuristic may be compile time intensive, <span class="doxyComputerOutput">OptLevel</span> provides a finer grain to tune the register allocator.</p>


<p>Declaration at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetsubtargetinfo-cpp">TargetSubtargetInfo.cpp</a>.</p>

</div>
</div>

### enableSpillageCopyElimination() {#a7e3393909f8a847b514c6f58aa9eaf78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetSubtargetInfo::enableSpillageCopyElimination ()</td>
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

<p>Enable spillage copy elimination in MachineCopyPropagation pass.</p>


<p>This helps removing redundant copies generated by register allocator when handling complex eviction chains.</p>


<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/machinecopypropagation/#ace511b0e422442acff30e6a5fac22488">anonymous{MachineCopyPropagation.cpp}::MachineCopyPropagation::runOnMachineFunction</a>.</p>

</div>
</div>

### enableSubRegLiveness() {#ada8a311babe7128c11eaf0ad96547ae6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetSubtargetInfo::enableSubRegLiveness ()</td>
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

<p>Enable tracking of subregister liveness in register allocator.</p>


<p>Please use <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a48ad9eedacb98923ab00074ec4760db2">MachineRegisterInfo::subRegLivenessEnabled()</a> instead where possible.</p>


<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>

</div>
</div>

### enableWindowScheduler() {#aa41488f6e5ff65d6b07002bb75bf3fbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetSubtargetInfo::enableWindowScheduler ()</td>
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

<p>True if the subtarget should run <a href="/web-llvm/docs/api/classes/llvm/windowscheduler">WindowScheduler</a>.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>

</div>
</div>

### getAntiDepBreakMode() {#aa227d641b2159afa4daf982ce65bc2e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual AntiDepBreakMode llvm::TargetSubtargetInfo::getAntiDepBreakMode ()</td>
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



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>

</div>
</div>

### getCallLowering() {#a9263ace85b7b15b4c903861b1f95e070}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const CallLowering * llvm::TargetSubtargetInfo::getCallLowering ()</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aa386a0afb3210b56c30181f93a434ed3">createAtomicLibcall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8829536a23c01dcd3a6017dccb148c90">llvm::createLibcall</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a524d3d59c93afc0f68256056ba5bfa0b">llvm::createMemLibcall</a>.</p>

</div>
</div>

### getCriticalPathRCs() {#a72693146cc01946f26dd28429813dd60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetSubtargetInfo::getCriticalPathRCs (<a href="#a24e0be4e8e0875ea7cf4dd3d20c11662">RegClassVector</a> &amp; CriticalPathRCs)</td>
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



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>.</p>

</div>
</div>

### getCustomPBQPConstraints() {#a5ff3040546aa8fcdf80dea4034a60d96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::unique_ptr&lt; PBQPRAConstraint &gt; llvm::TargetSubtargetInfo::getCustomPBQPConstraints ()</td>
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

<p>Return PBQPConstraint(s) for the target.</p>


<p>Override to provide custom <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> constraints.</p>


<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/regallocpbqp/#a82bfae004546453f47c217784928e0a5">anonymous{RegAllocPBQP.cpp}::RegAllocPBQP::runOnMachineFunction</a>.</p>

</div>
</div>

### getDAGScheduler() {#a7d190c7d762432bbd9cfd0614e70c7bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual RegisterScheduler::FunctionPassCtor llvm::TargetSubtargetInfo::getDAGScheduler (<a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a>)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> can subclass this hook to select a different DAG scheduler.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>

</div>
</div>

### getFrameLowering() {#ac83b44e69c9f9f4f9d60be2d72f4a5df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const TargetFrameLowering * llvm::TargetSubtargetInfo::getFrameLowering ()</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a12d8c4c294b19351dbee6ab588676012">checkNumAlignedDPRCS2Regs</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfocollector-cpp-/regusageinfocollector/#abbb1f7665085c8f50fab2ceac4304d91">anonymous{RegUsageInfoCollector.cpp}::RegUsageInfoCollector::computeCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a88b438423c0bb502e843c7dae099b7f4">computeFPBPAlignmentGap</a>, <a href="/web-llvm/docs/api/structs/llvm/lanairegisterinfo/#acd4d1d9eb28b9bca2ca401487bdf529e">llvm::LanaiRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/loongarchregisterinfo/#a14277e449886ad06b196b805fad006ec">llvm::LoongArchRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a0207059cc31ba2a73d1d7bc1ce62663f">emitDebugValueComment</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/#a69dafe1f45af554b1b82bcde2503a3c4">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::emitStackFrameLayoutRemarks</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a66046fdf8661d5276f951337b0cf892d">llvm::MachineFrameInfo::estimateStackSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a94b8d8925deffd735f51d36b77d3f9ca">getAddressForMemoryInput</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp/#a3728fd7e6329d634ed9a9a820f24fa0e">getFnStackAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/avrregisterinfo/#aa058d085dffef3bc3031d34059383794">llvm::AVRRegisterInfo::getFrameRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kregisterinfo/#a49621b5c9c3b0112614e13a1b34f8bc9">llvm::M68kRegisterInfo::getFrameRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaregisterinfo/#ab9f1ea8cb72630373bd0c84533b9d979">llvm::XtensaRegisterInfo::getFrameRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#a456c98e104fefc660add08150cc6c794">llvm::MipsRegisterInfo::getRegPressureLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaregisterinfo/#adbb50b5a30ff514499b94b7e29524fef">llvm::XtensaRegisterInfo::getReservedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a1e4f8b28a8543924e7e3e566a847e691">llvm::TargetInstrInfo::getSPAdjust</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ab6432ebba31ce9e456ad54b2b277d678">llvm::X86InstrInfo::getSPAdjust</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowersgprspills-cpp/#a3c627e9f404e8f9cf66e5a4a27860347">insertCSRRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a04bc45ddbc56deb8b54dacaeea86df8f">insertCSRRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a61e27cf21f938d341d13395bb4e17493">insertCSRSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#abe37f7fd8489575acc84929596ba4ead">mayCombineMisaligned</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ab49a74c3c0e9f35a453eb0db340424e7">llvm::MachineFrameInfo::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfocollector-cpp-/regusageinfocollector/#a20589df6cd2c2e12e77a1741a0e4223e">anonymous{RegUsageInfoCollector.cpp}::RegUsageInfoCollector::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptxprologepilogpass-cpp-/nvptxprologepilogpass/#a58c45f00a8ce8f9282ad2bbcfbd08cde">anonymous{NVPTXPrologEpilogPass.cpp}::NVPTXPrologEpilogPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a8677f120f60c9ac2cdc36759298a94b2">anonymous{PrologEpilogInserter.cpp}::PEI::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-registerscavenging-cpp-/scavengertest/#a4cea3e94b35ea3fccf713cc36a603e83">anonymous{RegisterScavenging.cpp}::ScavengerTest::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/cfifixup/#a7d1808859a4351ab820d5fa17a0e2685">llvm::CFIFixup::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a068e9d1fd54621ae340f26c41d170a1a">llvm::X86FrameLowering::spillFPBP</a>.</p>

</div>
</div>

### getInlineAsmLowering() {#a4341b7e26ad29a79755ada4880ad2a61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const InlineAsmLowering * llvm::TargetSubtargetInfo::getInlineAsmLowering ()</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>

</div>
</div>

### getInstrInfo() {#acd858ed72f11db9444617740c3622608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const TargetInstrInfo * llvm::TargetSubtargetInfo::getInstrInfo ()</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a9bd7c04e374ad15665430a243dd30d80">llvm::MachineBasicBlock::addLiveIn</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#a09842318dc1064ae48b19d91e2cb11aa">anonymous{BasicBlockPathCloning.cpp}::ApplyCloning</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#ab07fa640d6b044c04371e8cc8bde6a02">attemptDebugCopyProp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad42ea8aa2115313dc7f1b793b049e0b1">llvm::avoidZeroOffsetLandingPad</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#a6ae5e1ec2093c40fa0e3211bd043057b">llvm::DwarfDebug::beginInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d3e4802f0929af81173430c0786d52a">llvm::calculateRegAllocScore</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae32dc74389a52cbb83e6a016274142f5">llvm::MachineBasicBlock::canSplitCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a35be28e9754ada1081edc62f6efc0878">combineFPFusedMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a12da92f702a20d5337a5258038968d09">llvm::MachineFrameInfo::computeMaxCallFrameSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a145f77473f4a050a8e1bf0dd7e2a34fa">llvm::createBURRListDAGScheduler</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#a087b8382e9e76fa52c0c473b14f7d37d">createDedicatedExit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a24fb0e850aa86095101c2cd7110aa32b">llvm::createHybridListDAGScheduler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac2c88a3ebea5ca10491d30d01274c96d">llvm::createILPListDAGScheduler</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwresourcemodel/#a63d0e9315e9e0aba0008b5028a6c2044">llvm::VLIWResourceModel::createPacketizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a22444fb95050a5bef1c689e5bc9b064e">createPHIsForCMOVsInSinkBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a3c4c42f79d79638f6b67532d3f81df58">createPHIsForSelects</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa743cb95ae4e26544366fb66fa23f4dc">llvm::createSourceListDAGScheduler</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6885e40448874565521daac98e11f50d">llvm::TargetInstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/bpfregisterinfo/#a849e9ef6e1cc9fdb4a18b27bf6eadef7">llvm::BPFRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/lanairegisterinfo/#acd4d1d9eb28b9bca2ca401487bdf529e">llvm::LanaiRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430registerinfo/#a1ae0b9564ca66a61628084c4bb858ea8">llvm::MSP430RegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a2d8b50ff5c8dad758eb8d36c4d98bcaf">emitAlignedDPRCS2Restores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a3046f0367b644d6feafcc16f8da39967">emitAlignedDPRCS2Spills</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04f5dec5b43c7deebd3c243317240d95">emitBuildPairF64Pseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a035d6de6da7186bb6a0a180c617c8a83">emitCalleeSavedRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a98f815de250b90a65a5f83503fc7b288">emitComments</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#ac190f0cf5627568bd97cf1e5b24ce57d">llvm::BPFTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a948d164566e4b5aca48cf71cbf3a9ee3">llvm::MSP430TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a5e4563cae7f10b41cdff9a61f1f6aaab">llvm::ARMBaseRegisterInfo::emitLoadConstPool</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxframelowering/#aad707aff5fcbdc8180deb9e6695f0c32">llvm::NVPTXFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a055df59820235c32c403d7c78de5494b">emitQuietFCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae20aef7ab8c13752bc5663fb0e6cbb1c">emitReadCounterWidePseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a8e39c98d41d74a2147127a17c9800c7d">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aaf673a1e44074d7088008437112159fa">emitSplitF64Pseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumbregisterinfo-cpp/#a8a9cca3d1c6515fbf780f033644ace85">emitThumb2LoadConstPool</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab0a615cb68b545ea3a9c88243a0ab4d9">emitVFROUND_NOEXCEPT_MASK</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad865338e071057b5d2a249902281063a">llvm::MachineFunction::estimateFunctionSizeInBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a077981b5798a5d7a95cec16ece863aeb">llvm::finalizeBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a5bce8dbd0e078a0ea0821917ab1f4873">llvm::MachineFunction::finalizeDebugInstrRefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a541bb79da42e4b8f77617678e7f47d83">findPrologueEndLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a605515c2c4d676bb83888309fdaf1af0">llvm::AArch64InstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a731ca5cdf4cb5c12baa91590b3923d51">genIndexedMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a488ce2dad0d4f44659a655e17e0ae184">genShXAddAddShift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afa141935f9c9a1ad9c785d7b6200b119">llvm::getEHScopeMembership</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a31aa2680ec79198a4c94f35b3a1ad97e">llvm::MachineBasicBlock::getFallThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#af5535a05921d5db8486cc4ce527b066f">llvm::RegisterBankInfo::getInstrMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#a7d0ea970ec4a5d5cb4e1d1391a2bc7af">llvm::MSP430InstrInfo::getInstSizeInBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a138bc82a9943aa3008ab86bec2d2c91a">getOrCreateFrameHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#ae1be3a2fc5dfa3281d32b6fb4e4ea6dd">getSchedRegions</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a23060980870dd18a2719ac5468af3faf">getTargetIndexName</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/ssaifconv/#af3aabd84356a278f0f3c9c91e17a7ad6">anonymous{EarlyIfConversion.cpp}::SSAIfConv::init</a>, <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#ab357b39c47df52a19882a831feda1b6f">llvm::TargetSchedModel::init</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#ace182ca668404b3d23cae8329d941ba4">llvm::MipsFunctionInfo::initGlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#aef655ef720977fd68fbd4bf24b5ab3d8">llvm::ConvergingVLIWScheduler::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#a1974019840857f5ae10aa6b4edc5317d">llvm::TailDuplicator::initMF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowersgprspills-cpp/#a3c627e9f404e8f9cf66e5a4a27860347">insertCSRRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a04bc45ddbc56deb8b54dacaeea86df8f">insertCSRRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a61e27cf21f938d341d13395bb4e17493">insertCSRSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a75f3e392bd9cff57dcd444d521d7fd94">insertDivByZeroTrap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad64501a368789645f6f80afbce82da90">llvm::insertMultibyteShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfifixup-cpp/#a313dff6a75b3ae9c5c5d6802f3007a56">insertRememberRestorePair</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a88d50bb943ed6d9b7bf0a34367d018af">interpretValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp/#a466674860524a217292797476e9ce371">jumpTableHasOtherUses</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#a699fa07bf5290218677fc2a1e69e0781">llvm::X86CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#ac02c01e89c0ac7acc53bb50aeac772ac">llvm::ARMBaseRegisterInfo::materializeFrameBaseRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a497ba80da227001f952a7d30cfe0552f">llvm::RISCVRegisterInfo::materializeFrameBaseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a3da773a37ef4e3325379dd6718317b74">llvm::MachineInstr::mayAlias</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a1ac412f2e4cc981d3b9d3f6cf6d5988a">anonymous{MachineOutliner.cpp}::MachineOutliner::outline</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#ac2358bb1fa4721b99f88e2149d6d127d">anonymous{MachineOutliner.cpp}::MachineOutliner::populateMapper</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a5a4302f4590a281bb84e08b30c80591c">llvm::MachineBasicBlock::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab419785650ef9728b5305d220179017c">llvm::MachineInstr::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3bdc6bcbf7eec4329ba1b6c91ff776d8">llvm::MachineOperand::printTargetFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a9462cc875c5c343ff7ae9b3d68ce6305">llvm::AArch64FrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcregisterinfo-cpp/#a0c88fcf3221639302fa4045777473205">replaceFI</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64cleanuplocaldynamictlspass-cpp-/ldtlscleanup/#aa83e2f2005213b888f0f3aa096ad086e">anonymous{AArch64CleanupLocalDynamicTLSPass.cpp}::LDTLSCleanup::replaceTLSBaseAddrCall</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a16fbd46e51c3d60b6bb29c18ea546aa7">llvm::ResourcePriorityQueue::ResourcePriorityQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a3fc78aa19b9e30af7cb534f1a58e22de">llvm::AArch64FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a7c89ea904b5a33a2c24357c301e4ea21">llvm::CSKYFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#ad8f2dd732e11ab2eed0563516a0128e8">llvm::MSP430FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a6658cff9efc100c5b2751bed442d5a9b">llvm::RISCVFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a15d74c0d6159ac707f99c91219d0c6a5">llvm::SystemZELFFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#a88fe1478dc92f6e9310051316749f031">llvm::XCoreFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/earlyifconverter/#a0275a0186010a2c4472194dc40f10f01">anonymous{EarlyIfConversion.cpp}::EarlyIfConverter::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecse-cpp-/machinecseimpl/#a1d1df964f1ed506609c9920060dd99b2">anonymous{MachineCSE.cpp}::MachineCSEImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-optimizephis-cpp-/optimizephis/#a84f1822dce1d5363a4cbc32c0401e52e">anonymous{OptimizePHIs.cpp}::OptimizePHIs::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizer/#ae6c94cc4b29dfbcc1cc39b73e871ec2a">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizer::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/finalizeisel-cpp/#a6395b072c4fb781dca4789de8aba1f55">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64advsimdscalarpass-cpp-/aarch64advsimdscalar/#aeec06e4911b1bf8a25e08f5026641876">anonymous{AArch64AdvSIMDScalarPass.cpp}::AArch64AdvSIMDScalar::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionalcompares-cpp-/aarch64conditionalcompares/#af7b7982c58340c2b9b066e30a4fd558f">anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#a1ee52a66badadfe0d31d88d614305f41">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64deadregisterdefinitionspass-cpp-/aarch64deadregisterdefinitions/#a0a2d9af1b55ae47405481d60f08d1bd4">anonymous{AArch64DeadRegisterDefinitionsPass.cpp}::AArch64DeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#a9ab07fceeb056e44371448f9650b9ae5">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64speculationhardening-cpp-/aarch64speculationhardening/#af74e0cf10108e72a325bb16d56926dec">anonymous{AArch64SpeculationHardening.cpp}::AArch64SpeculationHardening::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/earlyifpredicator/#aa90706243c94cf284f209044cce20578">anonymous{EarlyIfConversion.cpp}::EarlyIfPredicator::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandpostrapseudos-cpp-/expandpostra/#a0f81cba1afc1321374d0a5599420f17f">anonymous{ExpandPostRAPseudos.cpp}::ExpandPostRA::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-fentryinserter-cpp-/fentryinserter/#ae3c9ad9123c1338bda3254b781eb08fc">anonymous{FEntryInserter.cpp}::FEntryInserter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnrewritepartialreguses-cpp-/gcnrewritepartialreguses/#adf18d032626767c9b0590624712d3ac1">anonymous{GCNRewritePartialRegUses.cpp}::GCNRewritePartialRegUses::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/gcmachinecodeanalysis/#a82b0862f6017d073489a4971d43ecf3a">anonymous{GCRootLowering.cpp}::GCMachineCodeAnalysis::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-implicitnullchecks-cpp-/implicitnullchecks/#adfa9682269920db0fdac767478243124">anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-kcfi-cpp-/kcfi/#a52015a7e0851334318eafd219c0412ba">anonymous{KCFI.cpp}::KCFI::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-liverangeshrink-cpp-/liverangeshrink/#ab45325824e5e6352ef04ee2d7bc639fb">anonymous{LiveRangeShrink.cpp}::LiveRangeShrink::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdeadregisterdefinitions-cpp-/loongarchdeadregisterdefinitions/#a045d88b2cc0eb3d853b24e0f6a5904b2">anonymous{LoongArchDeadRegisterDefinitions.cpp}::LoongArchDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacement/#a1f0291b83febf5c94491d76bf5236799">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecombiner-cpp-/machinecombiner/#aaee7889b0d1357a4eb765cecb57fdf92">anonymous{MachineCombiner.cpp}::MachineCombiner::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/machinecopypropagation/#ace511b0e422442acff30e6a5fac22488">anonymous{MachineCopyPropagation.cpp}::MachineCopyPropagation::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinefunctionsplitter-cpp-/machinefunctionsplitter/#a9f05c8e7366bb0f541cdc6c03b929ddd">anonymous{MachineFunctionSplitter.cpp}::MachineFunctionSplitter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinesink-cpp-/machinesinking/#af56efb8509ab5b039fe9dcf0c4f5eccd">anonymous{MachineSink.cpp}::MachineSinking::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinesink-cpp-/postramachinesinking/#a1f860254ea2183299eecbd087f61d405">anonymous{MachineSink.cpp}::PostRAMachineSinking::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-patchablefunction-cpp-/patchablefunction/#a11d99203cc91bbd49c59f32943541747">anonymous{PatchableFunction.cpp}::PatchableFunction::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#a93f0e6a8ab3a0e240422fdbd8696b4ec">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-processimplicitdefs-cpp-/processimplicitdefs/#a375e242755149e6709f30e1b8f30b0e2">anonymous{ProcessImplicitDefs.cpp}::ProcessImplicitDefs::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-pseudoprobeinserter-cpp-/pseudoprobeinserter/#acf62b36239ac36c52ffc9a58a18332ab">anonymous{PseudoProbeInserter.cpp}::PseudoProbeInserter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocfast-cpp-/regallocfastimpl/#acc7ba17c073b2d0a80ca229f3166b6a9">anonymous{RegAllocFast.cpp}::RegAllocFastImpl::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/registercoalescer/#aa408ab9747b8ce0bd0a81465c10e8f29">anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-renameindependentsubregs-cpp-/renameindependentsubregs/#a5a7168c10662c11aea9894ec2b7481bb">anonymous{RenameIndependentSubregs.cpp}::RenameIndependentSubregs::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvdeadregisterdefinitions-cpp-/riscvdeadregisterdefinitions/#ac2ca3a8531c6bdb17cc3908e3fbf10c4">anonymous{RISCVDeadRegisterDefinitions.cpp}::RISCVDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvredundantcopyelimination-cpp-/riscvredundantcopyelimination/#a40702a35ec28b1bfe35a08045af1f7ec">anonymous{RISCVRedundantCopyElimination.cpp}::RISCVRedundantCopyElimination::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-stackslotcoloring-cpp-/stackslotcoloring/#ad072a4f9fd33459ffa629f881b707cd2">anonymous{StackSlotColoring.cpp}::StackSlotColoring::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86cmovconversion-cpp-/x86cmovconverterpass/#a2b90fb87402f7118da2019ae5b84f0b1">anonymous{X86CmovConversion.cpp}::X86CmovConverterPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fasttileconfig-cpp-/x86fasttileconfig/#a2c6c9f435696b32a7d51ca66f8af9d19">anonymous{X86FastTileConfig.cpp}::X86FastTileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86floatingpoint-cpp-/fps/#aaf871b359dfbd7ec0d35819bf8d089a1">anonymous{X86FloatingPoint.cpp}::FPS::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winfixupbuffersecuritycheck-cpp-/x86winfixupbuffersecuritycheckpass/#a72a62fe526ad0cd3c24cfe003d363df0">anonymous{X86WinFixupBufferSecurityCheck.cpp}::X86WinFixupBufferSecurityCheckPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-xrayinstrumentation-cpp-/xrayinstrumentation/#a4fb91ea8621a93ca73b483592ac6b061">anonymous{XRayInstrumentation.cpp}::XRayInstrumentation::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/breakfalsedeps/#ad21a053369c2ee6c4adef784d6af900e">llvm::BreakFalseDeps::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/executiondomainfix/#aa90dd7f08ca467a5d6dc3215fb98ee51">llvm::ExecutionDomainFix::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/#a9f1a58845384add66455538dc8725392">llvm::RAGreedy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/scheduledagrrlist/#a2ddd224f4d981bb2a8ceb7d5c977f392">anonymous{ScheduleDAGRRList.cpp}::ScheduleDAGRRList::ScheduleDAGRRList</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagvliw-cpp-/scheduledagvliw/#a7dc43d4af0801e27b6c6273882f2e417">anonymous{ScheduleDAGVLIW.cpp}::ScheduleDAGVLIW::ScheduleDAGVLIW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsoptimizepiccall-cpp/#a0a6245fa36ea8b128eec6555f2ab52bb">setCallTargetReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af0d9669bbadd4d5e1d75c3c833c8d5ac">llvm::MachineIRBuilder::setMF</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64cleanuplocaldynamictlspass-cpp-/ldtlscleanup/#ae3b597ed71cdeef406aed84ce2e04f52">anonymous{AArch64CleanupLocalDynamicTLSPass.cpp}::LDTLSCleanup::setRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a1ee36ec6dd22cf058ebb96f2a7ef0108">llvm::TargetRegisterInfo::shouldRegionSplitForVirtReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3be7d94076d328797ab57ce09cefab33">llvm::MachineBasicBlock::SkipPHIsAndLabels</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a5d8a45757c9861d499cba1a0d54e2c1e">llvm::MachineBasicBlock::SkipPHIsLabelsAndDebug</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a38d361ba1ba79b6217929ada0dd69cb6">llvm::AArch64FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#af57354b85b1bb51bd0d56651205786a9">llvm::CSKYFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a6d7492a7a948b4a2d3bb8fd69395503d">llvm::LoongArchFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a4d6b288488bfee7d307b78a36e230986">llvm::MSP430FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a2d66c6615f09ca15ca384387a5d0eb3e">llvm::RISCVFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ac0e549bf3d7f691714f73696c1df480c">llvm::SystemZELFFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#acc16e0a256c156ca27db8e17d37cceab">llvm::XCoreFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a77dea00ee37a964ad5edf6072fb35071">UpdateOperandRegClass</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a5803a49facae20ca4b002dcba6f1d03e">llvm::MachineBasicBlock::updateTerminator</a>.</p>

</div>
</div>

### getInstrItineraryData() {#ae1f9b65239ddc3a0662b679817e477d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const InstrItineraryData * llvm::TargetSubtargetInfo::getInstrItineraryData ()</td>
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

<p>getInstrItineraryData - Returns instruction itinerary data for the target or specific subtarget.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#aa71123e6a62b9e23438e1be940306e2a">llvm::HexagonInstrInfo::CreateTargetScheduleState</a> and <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a74e6aef88dec63b3e87ab2a3fc6f9c78">llvm::R600InstrInfo::CreateTargetScheduleState</a>.</p>

</div>
</div>

### getInstructionSelector() {#aa155e32874c34aa7b0a547992467074c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual InstructionSelector * llvm::TargetSubtargetInfo::getInstructionSelector ()</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a98e4a98a0db786235d78fce93ad4a72f">llvm::InstructionSelect::runOnMachineFunction</a>.</p>

</div>
</div>

### getLegalizerInfo() {#abc4d15552b6f7e8b121a84146a69aa59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const LegalizerInfo * llvm::TargetSubtargetInfo::getLegalizerInfo ()</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipsregisterbankinfo/#a1e12ed6a5b2d3f3dd790e2c48f7d7906">llvm::MipsRegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a86d5a37f432a0567b98815a74f54dd1e">llvm::machineFunctionIsIllegal</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a356f9de405c2904f7ad73659a2f378a0">llvm::Legalizer::runOnMachineFunction</a>.</p>

</div>
</div>

### getMacroFusions() {#a2b74e2ebb235e247397d5d87df776e66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::vector&lt; MacroFusionPredTy &gt; llvm::TargetSubtargetInfo::getMacroFusions ()</td>
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

<p>Get the list of MacroFusion predicates.</p>

<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5365898dd1deb10d065e288a2babd511">llvm::createGenericSchedLive</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa2f0c2f2a077d67dc0bcb24bc31e3b05">llvm::createGenericSchedPostRA</a>.</p>

</div>
</div>

### getOptLevelToEnablePostRAScheduler() {#a7482dee387d6747dd3568405c23a6ca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual CodeGenOptLevel llvm::TargetSubtargetInfo::getOptLevelToEnablePostRAScheduler ()</td>
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



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>.</p>

</div>
</div>

### getPostRAMutations() {#aa483766fca31e32c897fe8f80f74dc99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetSubtargetInfo::getPostRAMutations (std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/scheduledagmutation">ScheduleDAGMutation</a> &gt; &gt; &amp; Mutations)</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>

</div>
</div>

### getRegBankInfo() {#a9768b8e3c00648b38189b95d6603729b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const RegisterBankInfo * llvm::TargetSubtargetInfo::getRegBankInfo ()</td>
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

<p>If the information for the register banks is available, return it.</p>


<p>Otherwise return nullptr.</p>


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a6f7e57c8c003253b7da93520af8ef8c2">llvm::RegBankSelect::init</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#a699fa07bf5290218677fc2a1e69e0781">llvm::X86CallLowering::lowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping/#a89e479535d719fb4ec8904104ec1e8ae">llvm::RegisterBankInfo::InstructionMapping::verify</a>.</p>

</div>
</div>

### getRegisterInfo() {#a43c530c830206ecf5ad3359364634c75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const TargetRegisterInfo * llvm::TargetSubtargetInfo::getRegisterInfo ()</td>
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

<p>getRegisterInfo - If register information is available, return it.</p>


<p>If not, return null.</p>


<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp/#a239e4eab401a0f791e5042a89c66dc84">addLiveInRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6cba8c24b1495a6caff37e5e6df77aa2">llvm::MachineFunction::allocateRegMask</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a251859cb890a0bfde6bed13d7d844494">llvm::TargetFrameLowering::allocateScavengingFrameIndexesNearIncomingSP</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocpbqp-cpp-/coalescing/#a68a07c5954404c20c6abe9a6791f19c2">anonymous{RegAllocPBQP.cpp}::Coalescing::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/a57chainingconstraint/#af022d8d0187b3df267d3e7754cb4b80b">llvm::A57ChainingConstraint::apply</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/callmutation/#a6cd9122ce8216f80dd0921f844f7b7e1">llvm::HexagonSubtarget::CallMutation::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5a0c9359d4e969f68a7c7643fc3fcb5c">llvm::RISCVFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#af5f0f04b137494bbf8fb56286dea2762">buildAnyextOrCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9b0a622dbae74cb8a4b9b87a8b559b25">llvm::AArch64InstrInfo::buildOutlinedFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#a6c15e4226ea85c6c5ffdb7b907023b85">llvm::LiveRangeEdit::calculateRegClassAndHint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a05c04a32ecd794f1e86cfb753ed1f5c2">cannotInsertTailCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a12d8c4c294b19351dbee6ab588676012">checkNumAlignedDPRCS2Regs</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfocollector-cpp-/regusageinfocollector/#abbb1f7665085c8f50fab2ceac4304d91">anonymous{RegUsageInfoCollector.cpp}::RegUsageInfoCollector::computeCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a88b438423c0bb502e843c7dae099b7f4">computeFPBPAlignmentGap</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a3fb8c57a2275283cbb376004421318da">computeLiveOuts</a>, <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#a5a00ff1e3eb19fe4001d742d93f8fade">llvm::TargetSchedModel::computeOutputLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aa43a432a700f337af56c8f2d1db9fe0b">llvm::MIRPrinter::convertCallSiteObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aa02f64dd0aa867287b5ad17200de097a">llvm::MIRPrinter::convertEntryValueObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a145f77473f4a050a8e1bf0dd7e2a34fa">llvm::createBURRListDAGScheduler</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#abc6950c9642cee4a3149ee5e1afbf5fe">llvm::MipsFunctionInfo::createEhDataRegsFI</a>, <a href="/web-llvm/docs/api/classes/llvm/xcorefunctioninfo/#a3ed9b1830a33b388d26b73a324b8503f">llvm::XCoreFunctionInfo::createEHSpillSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xcorefunctioninfo/#aaf7ccbc0c4ee11882e3e2835d84b90d2">llvm::XCoreFunctionInfo::createFPSpillSlot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a24fb0e850aa86095101c2cd7110aa32b">llvm::createHybridListDAGScheduler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac2c88a3ebea5ca10491d30d01274c96d">llvm::createILPListDAGScheduler</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#ae45b4d95be1f419bfa32ece88b82ed6f">llvm::MipsFunctionInfo::createISRRegFI</a>, <a href="/web-llvm/docs/api/classes/llvm/xcorefunctioninfo/#a75dfee78519833f2ad7e210c5e471f5d">llvm::XCoreFunctionInfo::createLRSpillSlot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa743cb95ae4e26544366fb66fa23f4dc">llvm::createSourceListDAGScheduler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#afb7df659747f14484e642788c2fe6788">createTuple</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a7a1bb4352b705901de9836f44ad326f4">llvm::AArch64InstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#ac9fa612919367a702574336b92a242d2">llvm::MipsInstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6885e40448874565521daac98e11f50d">llvm::TargetInstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#af2f88cb2b4134972392e4efa778596d6">llvm::ARMFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a058c4d3a1147ae3ec1098c3031fe32cb">llvm::CSKYFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#a27b8c40891bfea8db2ad3b9fa25cba0f">llvm::MipsSEFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a9eb6f3247260b906218068229b8d5b67">llvm::SystemZELFFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a2f26766f4dcfa6457ba405584a34d5c3">llvm::TargetFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04f5dec5b43c7deebd3c243317240d95">emitBuildPairF64Pseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a035d6de6da7186bb6a0a180c617c8a83">emitCalleeSavedRestores</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aa441f906c99d29f50a64369799d8f737">llvm::DwarfDebug::emitDebugLocValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a0207059cc31ba2a73d1d7bc1ce62663f">emitDebugValueComment</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a51c3d43bee1dec655ecaec65afc94c82">llvm::ARMFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a297d9aa8e26c1d3497ef90fc8ea95be2">emitFakeUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#aea02c3c9f298ea50ec11bb7c8201525a">emitFrameOffsetAdj</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#aa0d00a1b6833bc76147cf38dd23ecf97">emitKill</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a80326c86cd0c224fcea6c5b654870747">llvm::CSKYFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#afc48ca3b84128ca1b9ab1701d4f30b8c">llvm::XCoreFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aaf673a1e44074d7088008437112159fa">emitSplitF64Pseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab0a615cb68b545ea3a9c88243a0ab4d9">emitVFROUND_NOEXCEPT_MASK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#aa1ef43d8b6e30020194591f4e5a914ac">emitVGSaveRestore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a1a011d7a55ad214720e5e6765df6cf9d">estimateRSStackSizeLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a66046fdf8661d5276f951337b0cf892d">llvm::MachineFrameInfo::estimateStackSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a077981b5798a5d7a95cec16ece863aeb">llvm::finalizeBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6a733ae5364b0de2225af33223f383a5">llvm::TargetInstrInfo::foldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a64505b70265bcadc4993631d532a5fd5">llvm::AArch64InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aec4538d6aec6f79de5c3b56115fd2c78">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a647fbf2c5d5bb2fe4f4b5b9af7e0ab00">llvm::TargetFrameLowering::getCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a67cf1d94afd29ba3f7fa7a05241c43ae">llvm::TargetFrameLowering::getDwarfFrameBase</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#aca49f4bdff5eb8f32e4b650f33d6f98e">llvm::X86FrameLowering::getDwarfFrameBase</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a317f0fab04ed40f94b6d80d68370fe43">llvm::CSKYFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a0f71a92dc6f774b7059d9490a29d52ad">llvm::LoongArchFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a9258a9f50df17d6b3c064af9bf06c2bf">llvm::RISCVFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#af88a8f2328543f94aea3ba85d954fafa">llvm::TargetFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ad6591055c1ba6d0a1033510f7a4eab65">llvm::AArch64FrameLowering::getFrameIndexReferencePreferSP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#a3f4bf9736903f31820c978bdb1b6810f">llvm::AArch64RegisterBankInfo::getInstrAlternativeMappings</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerbankinfo/#a513e6961f1f77e1fb018daaad0b43157">llvm::X86RegisterBankInfo::getInstrAlternativeMappings</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#ab3d2615f7c9c9159d1e883ba8dd8eab7">llvm::AArch64RegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterbankinfo/#aece2fca4cd44244cdd43227c3d530368">llvm::PPCRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvregisterbankinfo/#a9a34245bb11e89a64a45063a8fc9e201">llvm::RISCVRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerbankinfo/#ab84d39303f3dab27a9cf03cd488b23c6">llvm::X86RegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#af5535a05921d5db8486cc4ce527b066f">llvm::RegisterBankInfo::getInstrMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/avrregisterinfo/#a161f481971cacf2cf192725cf68390f6">llvm::AVRRegisterInfo::getLargestLegalSuperClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a623eef1675bd2f33cfacc50b2fec0c71">getMemmoveLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#a4354515685ca31a2583e246f54977aee">llvm::MipsFunctionInfo::getMoveF64ViaSpillFI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aa42c3828ac3f788f2ef3ff6fa46e4926">llvm::MachineFrameInfo::getPristineRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#a43762e6a22fd0e7b98b8115946fc87b6">getRegistersForValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#aa2b5a0a0f6bf1b5480337a01257df8b6">getRegistersForValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsoptimizepiccall-cpp/#ad12ad3638ef83e9281c5cab4a99f60b0">getRegTy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a5cf58df95b00905950bdfee515cd5e9d">llvm::TargetInstrInfo::getStackSlotRange</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a52626eda66484fc0cadb0d956483888b">llvm::AArch64FrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#a3ca8ff16a3bd8d5f7c682180151eb3fc">llvm::ARCFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a895b02ce6ba256348e2eef839e1ef780">llvm::ARMFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a57e521638750a8eafb3e5b985cad6cb2">llvm::CSKYFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#adae83dd896dd68667b344defbc9c5381">llvm::LoongArchFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5a6257e7a03156ea3018b555f0aff4b2">llvm::RISCVFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#aa1d1f569ffb5db8f2cbb0bc8fdf7515c">llvm::VEFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/ssaifconv/#af3aabd84356a278f0f3c9c91e17a7ad6">anonymous{EarlyIfConversion.cpp}::SSAIfConv::init</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#ac1907c90bcd96c06c880601406ce946c">llvm::LiveRegMatrix::init</a>, <a href="/web-llvm/docs/api/classes/llvm/livestacks/#af0bf32332fb80b5892bd7b128638105c">llvm::LiveStacks::init</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a6f7e57c8c003253b7da93520af8ef8c2">llvm::RegBankSelect::init</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a5d044b599a2e3a1007e31a120105c9d7">llvm::RegPressureTracker::init</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowersgprspills-cpp/#a3c627e9f404e8f9cf66e5a4a27860347">insertCSRRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a04bc45ddbc56deb8b54dacaeea86df8f">insertCSRRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a61e27cf21f938d341d13395bb4e17493">insertCSRSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a7a51fbf2432530ad72f0a3996b993a7f">llvm::LoongArchInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a63b280c848f7c74e68e3a6f45ffb4a85">llvm::RISCVInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a88d50bb943ed6d9b7bf0a34367d018af">interpretValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#abed37e9eeb67324751569d54ac13c0ef">isNonFoldablePartialRegisterLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ad071e937f4986e51fd3fd54b10888894">llvm::TargetInstrInfo::isSchedulingBoundary</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a5ec1b0ffb0fbbbc5d74381b0b1d38ae1">patchMatchingInput</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a5a4302f4590a281bb84e08b30c80591c">llvm::MachineBasicBlock::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad9c9c8915579c517eff56e638c1a643c">llvm::MachineFunction::print</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#a230b654eb7319d9e7a6d9d62afa2d5f8">llvm::ARCFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#ad1c7f63bd41f376ebc594e3f8440d1ad">llvm::XCoreFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a16fbd46e51c3d60b6bb29c18ea546aa7">llvm::ResourcePriorityQueue::ResourcePriorityQueue</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/earlyifconverter/#a0275a0186010a2c4472194dc40f10f01">anonymous{EarlyIfConversion.cpp}::EarlyIfConverter::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecse-cpp-/machinecseimpl/#a1d1df964f1ed506609c9920060dd99b2">anonymous{MachineCSE.cpp}::MachineCSEImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizer/#ae6c94cc4b29dfbcc1cc39b73e871ec2a">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizer::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfocollector-cpp-/regusageinfocollector/#a20589df6cd2c2e12e77a1741a0e4223e">anonymous{RegUsageInfoCollector.cpp}::RegUsageInfoCollector::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64condbrtuning-cpp-/aarch64condbrtuning/#a3f2d376e9233d0fcb1dc2c5543fb3065">anonymous{AArch64CondBrTuning.cpp}::AArch64CondBrTuning::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionalcompares-cpp-/aarch64conditionalcompares/#af7b7982c58340c2b9b066e30a4fd558f">anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64deadregisterdefinitionspass-cpp-/aarch64deadregisterdefinitions/#a0a2d9af1b55ae47405481d60f08d1bd4">anonymous{AArch64DeadRegisterDefinitionsPass.cpp}::AArch64DeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64redundantcopyelimination-cpp-/aarch64redundantcopyelimination/#a4023f87727ff6428309476588c4a2a86">anonymous{AArch64RedundantCopyElimination.cpp}::AArch64RedundantCopyElimination::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64speculationhardening-cpp-/aarch64speculationhardening/#af74e0cf10108e72a325bb16d56926dec">anonymous{AArch64SpeculationHardening.cpp}::AArch64SpeculationHardening::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/earlyifpredicator/#aa90706243c94cf284f209044cce20578">anonymous{EarlyIfConversion.cpp}::EarlyIfPredicator::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandpostrapseudos-cpp-/expandpostra/#a0f81cba1afc1321374d0a5599420f17f">anonymous{ExpandPostRAPseudos.cpp}::ExpandPostRA::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/gcmachinecodeanalysis/#a82b0862f6017d073489a4971d43ecf3a">anonymous{GCRootLowering.cpp}::GCMachineCodeAnalysis::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonexpandcondsets-cpp-/hexagonexpandcondsets/#a4552c648a6db6ec6bff6ed09de4136d7">anonymous{HexagonExpandCondsets.cpp}::HexagonExpandCondsets::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonoptaddrmode-cpp-/hexagonoptaddrmode/#ad07a6a329e102fb53ef087cbba07c002">anonymous{HexagonOptAddrMode.cpp}::HexagonOptAddrMode::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdeadregisterdefinitions-cpp-/loongarchdeadregisterdefinitions/#a045d88b2cc0eb3d853b24e0f6a5904b2">anonymous{LoongArchDeadRegisterDefinitions.cpp}::LoongArchDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacement/#a1f0291b83febf5c94491d76bf5236799">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/machinecopypropagation/#ace511b0e422442acff30e6a5fac22488">anonymous{MachineCopyPropagation.cpp}::MachineCopyPropagation::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinesink-cpp-/postramachinesinking/#a1f860254ea2183299eecbd087f61d405">anonymous{MachineSink.cpp}::PostRAMachineSinking::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-mlxexpansionpass-cpp-/mlxexpansion/#a097b0b80206a11244f399de6de333399">anonymous{MLxExpansionPass.cpp}::MLxExpansion::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptxprologepilogpass-cpp-/nvptxprologepilogpass/#a58c45f00a8ce8f9282ad2bbcfbd08cde">anonymous{NVPTXPrologEpilogPass.cpp}::NVPTXPrologEpilogPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#accbe3daa3b618020c7f900a4ca110f91">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-processimplicitdefs-cpp-/processimplicitdefs/#a375e242755149e6709f30e1b8f30b0e2">anonymous{ProcessImplicitDefs.cpp}::ProcessImplicitDefs::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a8677f120f60c9ac2cdc36759298a94b2">anonymous{PrologEpilogInserter.cpp}::PEI::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocfast-cpp-/regallocfastimpl/#acc7ba17c073b2d0a80ca229f3166b6a9">anonymous{RegAllocFast.cpp}::RegAllocFastImpl::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/registercoalescer/#aa408ab9747b8ce0bd0a81465c10e8f29">anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvdeadregisterdefinitions-cpp-/riscvdeadregisterdefinitions/#ac2ca3a8531c6bdb17cc3908e3fbf10c4">anonymous{RISCVDeadRegisterDefinitions.cpp}::RISCVDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvredundantcopyelimination-cpp-/riscvredundantcopyelimination/#a40702a35ec28b1bfe35a08045af1f7ec">anonymous{RISCVRedundantCopyElimination.cpp}::RISCVRedundantCopyElimination::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-shrinkwrap-cpp-/shrinkwrap/#a0b77b3bd867840460e8de5e83245240e">anonymous{ShrinkWrap.cpp}::ShrinkWrap::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-stackmaplivenessanalysis-cpp-/stackmapliveness/#ab6f8a5390b954d2509fa4c304344eb53">anonymous{StackMapLivenessAnalysis.cpp}::StackMapLiveness::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-virtregmap-cpp-/virtregrewriter/#a4268652d87bd14a2b124f863ead3025f">anonymous{VirtRegMap.cpp}::VirtRegRewriter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86cmovconversion-cpp-/x86cmovconverterpass/#a2b90fb87402f7118da2019ae5b84f0b1">anonymous{X86CmovConversion.cpp}::X86CmovConverterPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/ldvimpl/#a4e5a4f513cd277250d246664b49e066b">llvm::LiveDebugVariables::LDVImpl::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#af7d89916d0369e37e6cbfbca7219cbb6">llvm::ReachingDefAnalysis::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a07f4133008c7c11a0154735071ffcc19">llvm::InstructionSelect::selectMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseframelowering-cpp/#a8058af7f16d3ab91b5a51f5102843b96">setAliasRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a0909a505055aae0cb9dee8e5730b3724">llvm::MIRParserImpl::setupRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ac0bfa894f538166cb476b439a2cb0aea">llvm::MachineBasicBlock::splitAt</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a755fb78188a206380ebf96d5211b1696">llvm::X86InstrInfo::unfoldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a768c85ec7c5044117192b9fc18395231">llvm::X86InstrInfo::unfoldMemoryOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a6c1da13a967ff01e9076c55b0b6d158c">updateLiveIn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a77dea00ee37a964ad5edf6072fb35071">UpdateOperandRegClass</a> and <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping/#a89e479535d719fb4ec8904104ec1e8ae">llvm::RegisterBankInfo::InstructionMapping::verify</a>.</p>

</div>
</div>

### getSelectionDAGInfo() {#a3182b054aa29b9217d2a8cb49da7d0ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const SelectionDAGTargetInfo * llvm::TargetSubtargetInfo::getSelectionDAGInfo ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aebf2552377f8da597377c682a1d11977">llvm::SelectionDAG::init</a>.</p>

</div>
</div>

### getSMSMutations() {#aa8880b0b91cfcde86e7a0bc1eb6f76c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetSubtargetInfo::getSMSMutations (std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/scheduledagmutation">ScheduleDAGMutation</a> &gt; &gt; &amp; Mutations)</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>

</div>
</div>

### getTargetLowering() {#ade3f0d8b35d67c43df9425bb730a9a7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const TargetLowering * llvm::TargetSubtargetInfo::getTargetLowering ()</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a060616c6385361df8bd72cde315d4267">llvm::MachineIRBuilder::buildBoolExtInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a7e58ecea881b2ea06fee315563860e39">llvm::MachineIRBuilder::buildExtractVectorElementConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c5e19523172e41e6a320be6fd748e17">llvm::calculateDbgEntityHistory</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aa386a0afb3210b56c30181f93a434ed3">createAtomicLibcall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b8fc31cace25c498444cd6853de598a">llvm::createLibcall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a524d3d59c93afc0f68256056ba5bfa0b">llvm::createMemLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#a756acce5a5adef291dc50593ce6d56a4">llvm::XCoreFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a734b1c5c857eaef57158e8ceefb5b5ce">llvm::SystemZELFFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#afc48ca3b84128ca1b9ab1701d4f30b8c">llvm::XCoreFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonselectiondaginfo/#a10a0dbb2ae8f208929d1f453d84cb101">llvm::HexagonSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreselectiondaginfo/#af87dbf9e0c8190963043ea6154532c25">llvm::XCoreSelectionDAGInfo::EmitTargetCodeForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a5aafc4bc2c28b6cb5d9aeb319b186d11">llvm::MachineIRBuilder::getBoolExtOp</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfregisters/#a948f65c38b613d36deb501eb8b8476c8">llvm::SystemZELFRegisters::getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfregisters/#af9a3f20abd67b17fdb105aa2fe63e08d">llvm::SystemZELFRegisters::getCallPreservedMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#a43762e6a22fd0e7b98b8115946fc87b6">getRegistersForValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aebf2552377f8da597377c682a1d11977">llvm::SelectionDAG::init</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ac8e2225e71c3b7d40575a2ab9bfffc78">llvm::GenericScheduler::initPolicy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a88d50bb943ed6d9b7bf0a34367d018af">interpretValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp/#a33f3613fb6558bae2f0d2bdd87e18dfa">isRegOtherThanSPAndFP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ad071e937f4986e51fd3fd54b10888894">llvm::TargetInstrInfo::isSchedulingBoundary</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa13f60350a3e19e1791fd628b694da36">llvm::MachineBasicBlock::liveout_begin</a>, <a href="/web-llvm/docs/api/classes/anonymous-typepromotion-cpp-/typepromotionimpl/#a2ff692eefcb74ae2bbd96ff5f9241287">anonymous{TypePromotion.cpp}::TypePromotionImpl::run</a>, <a href="/web-llvm/docs/api/classes/llvm/expandlargedivrempass/#ab3c55956a41284798a17daed1f2d3de2">llvm::ExpandLargeDivRemPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/expandlargefpconvertpass/#ac98aeadd0bb290c908220397e777c556">llvm::ExpandLargeFpConvertPass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/finalizeisel-cpp/#a6395b072c4fb781dca4789de8aba1f55">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-safestack-cpp-/safestacklegacypass/#a7cac2bf189a71c58d1514aaaac25414a">anonymous{SafeStack.cpp}::SafeStackLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacement/#a1f0291b83febf5c94491d76bf5236799">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacement::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a07f4133008c7c11a0154735071ffcc19">llvm::InstructionSelect::selectMachineFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64giselutils/#a9922ec95e157a3432c8ccd4a8a6a2653">llvm::AArch64GISelUtils::tryEmitBZero</a>.</p>

</div>
</div>

### ignoreCSRForAllocationOrder() {#ab386dc282b4697d60f1b18ce4fcd9ebf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetSubtargetInfo::ignoreCSRForAllocationOrder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
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

<p>True if the register allocator should use the allocation orders exactly as written in the tablegen descriptions, false if it should allocate the specified physical register later if is it callee-saved.</p>

<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>

</div>
</div>

### isDependencyBreaking() {#a86428c2c5b7e83ae2ca900eee58b3cb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetSubtargetInfo::isDependencyBreaking (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Mask)</td>
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

<p>Returns true if MI is a dependency breaking instruction for the subtarget.</p>


<p>Similar in behavior to <span class="doxyComputerOutput">isZeroIdiom</span>. However, it knows how to identify all dependency breaking instructions (i.e. not just zero-idioms).</p>


<p>As for <span class="doxyComputerOutput">isZeroIdiom</span>, this method returns a mask of "broken" dependencies. (See method <span class="doxyComputerOutput">isZeroIdiom</span> for a detailed description of Mask).</p>


<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>References <a href="#acfcd25a347c1a8e63210e7b2c6ee8910">isZeroIdiom</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isOptimizableRegisterMove() {#acd3542c354313777c3eaf1af365604d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetSubtargetInfo::isOptimizableRegisterMove (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Returns true if MI is a candidate for move elimination.</p>


<p>A candidate for move elimination may be optimized out at register renaming stage. Subtargets can specify the set of optimizable moves by instantiating tablegen class <span class="doxyComputerOutput">IsOptimizableRegisterMove</span> (see llvm/Target/TargetInstrPredicate.td).</p>


<p>SubtargetEmitter is responsible for processing all the definitions of class IsOptimizableRegisterMove, and auto-generate an override for this method.</p>


<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isRegisterReservedByUser() {#a5f331edcb998d10d8fb1608935eb6c7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetSubtargetInfo::isRegisterReservedByUser (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R)</td>
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



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#ab249b9c1f964160b8283b88d89524e87">llvm::RISCVRegisterInfo::isAsmClobberable</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>.</p>

</div>
</div>

### isXRaySupported() {#a9546854031006fe46295d6430e170861}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetSubtargetInfo::isXRaySupported ()</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-xrayinstrumentation-cpp-/xrayinstrumentation/#a4fb91ea8621a93ca73b483592ac6b061">anonymous{XRayInstrumentation.cpp}::XRayInstrumentation::runOnMachineFunction</a>.</p>

</div>
</div>

### isZeroIdiom() {#acfcd25a347c1a8e63210e7b2c6ee8910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetSubtargetInfo::isZeroIdiom (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Mask)</td>
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

<p>Returns true if MI is a dependency breaking zero-idiom instruction for the subtarget.</p>


<p>This function also sets bits in Mask related to input operands that are not in a data dependency relationship. There is one bit for each machine operand; implicit operands follow explicit operands in the bit representation used for Mask. An empty (i.e. a mask with all bits cleared) means: data dependencies are "broken" for all the explicit input machine operands of MI.</p>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a86428c2c5b7e83ae2ca900eee58b3cb7">isDependencyBreaking</a>.</p>

</div>
</div>

### mirFileLoaded() {#a9e6de090b178b663c02bc8aa8fe70226}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetSubtargetInfo::mirFileLoaded (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>This is called after a .mir file was loaded.</p>

<p>Declaration at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetsubtargetinfo-cpp">TargetSubtargetInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>.</p>

</div>
</div>

### overridePostRASchedPolicy() {#a960319789166bad30f214270de5cbadc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetSubtargetInfo::overridePostRASchedPolicy (<a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy">MachineSchedPolicy</a> &amp; Policy, unsigned NumRegionInstrs)</td>
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

<p>Override generic post-ra scheduling policy within a region.</p>


<p>This is a convenient way for targets that don't provide any custom scheduling heuristics (no custom <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a>) to make changes to the generic post-ra scheduling policy. Note that some options like tracking register pressure won't take effect in post-ra scheduling.</p>


<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/postgenericscheduler/#a04711828471ee40bed1b0e0ae8584cf4">llvm::PostGenericScheduler::initPolicy</a>.</p>

</div>
</div>

### overrideSchedPolicy() {#a9cd7c54e0bb13cc01c4e2a4133a40ee4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::TargetSubtargetInfo::overrideSchedPolicy (<a href="/web-llvm/docs/api/structs/llvm/machineschedpolicy">MachineSchedPolicy</a> &amp; Policy, unsigned NumRegionInstrs)</td>
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

<p>Override generic scheduling policy within a region.</p>


<p>This is a convenient way for targets that don't provide any custom scheduling heuristics (no custom <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a>) to make changes to the generic scheduling policy.</p>


<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ac8e2225e71c3b7d40575a2ab9bfffc78">llvm::GenericScheduler::initPolicy</a>.</p>

</div>
</div>

### requiresDisjointEarlyClobberAndUndef() {#a0aaf1fab9cff75e1a6cd2ead43d55503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetSubtargetInfo::requiresDisjointEarlyClobberAndUndef ()</td>
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

<p>Whether the target has instructions where an early-clobber result operand cannot overlap with an undef input operand.</p>

<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>

</div>
</div>

### resolveSchedClass() {#ae7cda8924c60f445e822e54c32c42314}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::TargetSubtargetInfo::resolveSchedClass (unsigned SchedClass, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a> * SchedModel)</td>
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

<p>Resolve a SchedClass at runtime, where SchedClass identifies an <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> with the isVariant property.</p>


<p>This may return the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of another variant SchedClass, but repeated invocation must quickly terminate in a nonvariant SchedClass.</p>


<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### useAA() {#a97ec020f20d345ae76e9b1ff450b4ffa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetSubtargetInfo::useAA ()</td>
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

<p>Enable use of alias analysis during code generation (during MI scheduling, DAGCombine, etc.).</p>

<p>Declaration at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetsubtargetinfo-cpp">TargetSubtargetInfo.cpp</a>.</p>


<p>Referenced by <a href="#adea7a4bec1046f6dd5631da25567a5b7">addrSinkUsingGEPs</a>.</p>

</div>
</div>

### useDFAforSMS() {#abdc20e43d0f27d58b009b63f13e77d13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::TargetSubtargetInfo::useDFAforSMS ()</td>
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

<p>Default to DFA for resource management, return false when target will use ProcResource in InstrSchedModel instead.</p>

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">TargetSubtargetInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/targetsubtargetinfo-cpp">TargetSubtargetInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
