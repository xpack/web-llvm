---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86iselloweringcall-cpp-/varargsloweringhelper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VarArgsLoweringHelper` Class

<p>This is a helper class for lowering variable arguments parameters. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{X86ISelLoweringCall.cpp}::VarArgsLoweringHelper { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a892127092365a3dbd1c7e0514e06f0d5">VarArgsLoweringHelper</a> (X86MachineFunctionInfo *FuncInfo, const SDLoc &amp;Loc, SelectionDAG &amp;DAG, const X86Subtarget &amp;Subtarget, CallingConv::ID CallConv, CCState &amp;CCInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a054ed75936f0e0b897c5f877bf2a798a">lowerVarArgsParameters</a> (SDValue &amp;Chain, unsigned StackSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a931f775e2622635b853311466a221fdf">createVarArgAreaAndStoreRegisters</a> (SDValue &amp;Chain, unsigned StackSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e7ef5c24cce0c134fcb1d53132a3ee2">forwardMustTailParameters</a> (SDValue &amp;Chain)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b8c2ff4afa6dd37747cd4b79a962915">is64Bit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf7b152c8398a0b4b9ef36bd77500d20">isWin64</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo">X86MachineFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaddfed0115ff57bdca7c0ff5b91c5282">FuncInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76a846538d4ca623b7b29f3220aab50e">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3967b948f885bdef7ba13b00102a1ba3">DAG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad39a3be31a27729f132dc56bda268a77">Subtarget</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef13994c75a17b2fb63043510cb4f6dd">TheMachineFunction</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5189541dccb214624758a5534155285">TheFunction</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1add926aefea776e5e94272bce1dd11">FrameInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetframelowering">TargetFrameLowering</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a689983aae6a99a2c58fa8457a73a3823">FrameLowering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48c6d1ab6bb46f5764887f60b343b644">TargLowering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">CallingConv::ID</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31a008fe4f8158a2a13bd52f73e6812e">CallConv</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ac512b0734d07eae9155b0f186c15b2">CCInfo</a></td>
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

<p>This is a helper class for lowering variable arguments parameters.</p>

<p>Definition at line 1473 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VarArgsLoweringHelper() {#a892127092365a3dbd1c7e0514e06f0d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86ISelLoweringCall.cpp}::VarArgsLoweringHelper::VarArgsLoweringHelper (<a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo">X86MachineFunctionInfo</a> * FuncInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> &amp; Subtarget, CallingConv::ID CallConv, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; CCInfo)</td>
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



<p>Definition at line 1475 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/evaluator-cpp/#a92efb02157b6836e1232c577d34678d6">getFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### lowerVarArgsParameters() {#a054ed75936f0e0b897c5f877bf2a798a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarArgsLoweringHelper::lowerVarArgsParameters (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain, unsigned StackSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1487 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createVarArgAreaAndStoreRegisters() {#a931f775e2622635b853311466a221fdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarArgsLoweringHelper::createVarArgAreaAndStoreRegisters (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain, unsigned StackSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1490 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### forwardMustTailParameters() {#a4e7ef5c24cce0c134fcb1d53132a3ee2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VarArgsLoweringHelper::forwardMustTailParameters (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1492 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### is64Bit() {#a8b8c2ff4afa6dd37747cd4b79a962915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86ISelLoweringCall.cpp}::VarArgsLoweringHelper::is64Bit ()</td>
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



<p>Definition at line 1494 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### isWin64() {#aaf7b152c8398a0b4b9ef36bd77500d20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86ISelLoweringCall.cpp}::VarArgsLoweringHelper::isWin64 ()</td>
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



<p>Definition at line 1495 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CallConv {#a31a008fe4f8158a2a13bd52f73e6812e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallingConv::ID anonymous{X86ISelLoweringCall.cpp}::VarArgsLoweringHelper::CallConv</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1506 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### CCInfo {#a5ac512b0734d07eae9155b0f186c15b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CCState&amp; anonymous{X86ISelLoweringCall.cpp}::VarArgsLoweringHelper::CCInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1507 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### DAG {#a3967b948f885bdef7ba13b00102a1ba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectionDAG&amp; anonymous{X86ISelLoweringCall.cpp}::VarArgsLoweringHelper::DAG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1499 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### DL {#a76a846538d4ca623b7b29f3220aab50e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SDLoc&amp; anonymous{X86ISelLoweringCall.cpp}::VarArgsLoweringHelper::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1498 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### FrameInfo {#af1add926aefea776e5e94272bce1dd11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFrameInfo&amp; anonymous{X86ISelLoweringCall.cpp}::VarArgsLoweringHelper::FrameInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1503 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### FrameLowering {#a689983aae6a99a2c58fa8457a73a3823}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetFrameLowering&amp; anonymous{X86ISelLoweringCall.cpp}::VarArgsLoweringHelper::FrameLowering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1504 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### FuncInfo {#aaddfed0115ff57bdca7c0ff5b91c5282}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86MachineFunctionInfo* anonymous{X86ISelLoweringCall.cpp}::VarArgsLoweringHelper::FuncInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1497 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### Subtarget {#ad39a3be31a27729f132dc56bda268a77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86Subtarget&amp; anonymous{X86ISelLoweringCall.cpp}::VarArgsLoweringHelper::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1500 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### TargLowering {#a48c6d1ab6bb46f5764887f60b343b644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLowering&amp; anonymous{X86ISelLoweringCall.cpp}::VarArgsLoweringHelper::TargLowering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1505 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### TheFunction {#aa5189541dccb214624758a5534155285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function&amp; anonymous{X86ISelLoweringCall.cpp}::VarArgsLoweringHelper::TheFunction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1502 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

### TheMachineFunction {#aef13994c75a17b2fb63043510cb4f6dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; anonymous{X86ISelLoweringCall.cpp}::VarArgsLoweringHelper::TheMachineFunction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1501 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
