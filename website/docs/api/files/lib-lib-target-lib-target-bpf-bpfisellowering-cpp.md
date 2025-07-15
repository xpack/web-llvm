---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `BPFISelLowering.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-h">BPFISelLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpf-h">BPF.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfsubtarget-h">BPFSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">llvm/CodeGen/CallingConvLower.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">llvm/CodeGen/TargetLoweringObjectFileImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">llvm/CodeGen/ValueTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticprinter-h">llvm/IR/DiagnosticPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "BPFGenCallingConv.inc"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab794ca855b323cdcfbf21f4a2205bdcf">fail</a> (const SDLoc &amp;DL, SelectionDAG &amp;DAG, const Twine &amp;Msg, SDValue Val={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac582a8ad2c8ee5589ed9251e0d86833a">resetRegMaskBit</a> (const TargetRegisterInfo *TRI, uint32_t *RegMask, MCRegister Reg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d7ae72cbefa48b3c446bbe0a0347010">regMaskFromTemplate</a> (const TargetRegisterInfo *TRI, MachineFunction &amp;MF, const uint32_t *BaseRegMask)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe5a99012f6bc8dc0089bfca05eb977a">NegateCC</a> (SDValue &amp;LHS, SDValue &amp;RHS, ISD::CondCode &amp;CC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f989f77f3be8d54ef9a019ebf91dc30">getTargetNode</a> (GlobalAddressSDNode *N, const SDLoc &amp;DL, EVT Ty, SelectionDAG &amp;DAG, unsigned Flags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a438c44a26a1f406a36ae3dea8efaeb2e">getTargetNode</a> (ConstantPoolSDNode *N, const SDLoc &amp;DL, EVT Ty, SelectionDAG &amp;DAG, unsigned Flags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b8c087a490f10055c3401307a857fab">BPFExpandMemcpyInOrder</a>("bpf-expand-memcpy-in-order", cl::Hidden, cl::init(false), cl::desc("Expand memcpy into load/store pairs in order"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"bpf-lower"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff7521dff7b86d6970cbfedfe2b25592">SET_NEWCC</a>(X, Y)&nbsp;&nbsp;&nbsp;...</td>
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


<div class="doxySectionDef">

## Functions

### fail() {#ab794ca855b323cdcfbf21f4a2205bdcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void fail (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Val={})</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp/#a7c623da681f3f332044b8dc9c02f0005">checkAsyncContextProjectFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp/#afab9b41ee90b1a38be566c582f290272">checkAsyncFuncPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp/#a394e27f50c3da62b86bfa0dbac5cf847">checkConstantInt</a>, <a href="/web-llvm/docs/api/classes/llvm/coroasyncendinst/#a38f76f44c524e7bbe9443b7d83c1e6ea">llvm::CoroAsyncEndInst::checkWellFormed</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp/#ad78e68905571b17d6714adb8b239fbec">checkWFAlloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp/#a08034766073114cf648d6755a8c6fff9">checkWFDealloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp/#a407e09d1f99eca22657b7525cb7f2f51">checkWFRetconPrototype</a> and <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a>.</p>

</div>
</div>

### getTargetNode() {#a0f989f77f3be8d54ef9a019ebf91dc30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue getTargetNode (<a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode">GlobalAddressSDNode</a> * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Flags)</td>
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



<p>Definition at line 724 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a05c0ae3eb411a8c53a6ce48b66c0d3f8">llvm::SelectionDAG::getTargetGlobalAddress</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getTargetNode() {#a438c44a26a1f406a36ae3dea8efaeb2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue getTargetNode (<a href="/web-llvm/docs/api/classes/llvm/constantpoolsdnode">ConstantPoolSDNode</a> * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, unsigned Flags)</td>
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



<p>Definition at line 729 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aeab75f932b62381e1db6624dff1c2636">llvm::SelectionDAG::getTargetConstantPool</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### NegateCC() {#afe5a99012f6bc8dc0089bfca05eb977a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NegateCC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; LHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; RHS, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> &amp; CC)</td>
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



<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a9cc23aed232ccdeadbd8648c349236a6">llvm::ISD::getSetCCSwappedOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ab49f81c2ecbbff3d0fbe55dd46353774">llvm::ISD::SETLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a6f05a09edb671910f85f8665981cbde9">llvm::ISD::SETLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ac538f0b432df970cbaaf6b81d777c6a7">llvm::ISD::SETULE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a473200f06bdd611fdbed43d908b84305">llvm::ISD::SETULT</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### regMaskFromTemplate() {#a0d7ae72cbefa48b3c446bbe0a0347010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t * regMaskFromTemplate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * BaseRegMask)</td>
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



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6cba8c24b1495a6caff37e5e6df77aa2">llvm::MachineFunction::allocateRegMask</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9fd1f4d5c1460886c4aa983a2027d944">llvm::MachineOperand::getRegMaskSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### resetRegMaskBit() {#ac582a8ad2c8ee5589ed9251e0d86833a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void resetRegMaskBit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, uint32_t * RegMask, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### BPFExpandMemcpyInOrder {#a4b8c087a490f10055c3401307a857fab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; BPFExpandMemcpyInOrder("bpf-expand-memcpy-in-order", cl::Hidden, cl::init(false), cl::desc("Expand memcpy into load/store pairs in order"))</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#a96722a41714a1c1b003e935c4e6c2133">llvm::BPFTargetLowering::BPFTargetLowering</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"bpf-lower"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>

</div>
</div>

### SET\_NEWCC {#aff7521dff7b86d6970cbfedfe2b25592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SET_NEWCC(X, Y)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case ISD::X: \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (is32BitCmp &amp;&amp; HasJmp32) \
      NewCC = isSelectRROp ? <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">BPF::Y</a>##_rr_32 : <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">BPF::Y</a>##_ri_32; \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a0544c3fe466e421738dae463968b70ba">else</a> \
      NewCC = isSelectRROp ? <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">BPF::Y</a>##_rr : <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">BPF::Y</a>##_ri; \
    <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-cpp/#a91cf6fbebedd86150a36e5ac3d5d3bfc">break</a>
</div>
</dd>
</dl>

<p>Definition at line 887 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp">BPFISelLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#ac190f0cf5627568bd97cf1e5b24ce57d">llvm::BPFTargetLowering::EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
