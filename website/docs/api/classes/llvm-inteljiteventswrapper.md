---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/inteljiteventswrapper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `IntelJITEventsWrapper` Class



## Declaration

<div class="doxyDeclaration">
class llvm::IntelJITEventsWrapper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">ExecutionEngine/IntelJITProfiling/IntelJITEventsWrapper.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">int(* <a href="#aee20e6512cbaf6fd7f2cf730d2e094cf">NotifyEventPtr</a>)(iJIT_JVM_EVENT, void *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">int(* <a href="#a5beb6a29928dab4382531981adf45534">IttnotifyInfoPtr</a>)(IttEventType, const char *, unsigned int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">void(* <a href="#a4e32194570f68ddd0de55d66df2d77b2">RegisterCallbackExPtr</a>)(void *, iJIT_ModeChangedEx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#ae2ce670f3109150b2efb12d226c860f5">iJIT_IsProfilingActiveFlags</a>(* <a href="#a4dd22ef9df781c9fc5788f055dcf058e">IsProfilingActivePtr</a>)(void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">void(* <a href="#a66df26b88f6ea2c4a4d6ef35934e9a1d">FinalizeThreadPtr</a>)(void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">void(* <a href="#a68c8178cd12f04d8986cb58e286a66f3">FinalizeProcessPtr</a>)(void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">unsigned int(* <a href="#a5126325fe62df4c38f0fb61940133b94">GetNewMethodIDPtr</a>)(void)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ce833383f57f30f785e56b868aed3fb">IntelJITEventsWrapper</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89593b9f883d95832af3362c52d87ce5">IntelJITEventsWrapper</a> (NotifyEventPtr NotifyEventImpl, IttnotifyInfoPtr IttnotifyInfoImpl, RegisterCallbackExPtr RegisterCallbackExImpl, IsProfilingActivePtr IsProfilingActiveImpl, FinalizeThreadPtr FinalizeThreadImpl, FinalizeProcessPtr FinalizeProcessImpl, GetNewMethodIDPtr GetNewMethodIDImpl)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aa77793cbdbbea88f90848769a1258f">isAmplifierRunning</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe60f00b9e149fcf0da28a67f6f3b99e">iJIT_NotifyEvent</a> (iJIT_JVM_EVENT EventType, void *EventSpecificData)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cbdf3c1836bb52618979e9eee28c91a">iJitIttNotifyInfo</a> (IttEventType EventType, const char *Name, unsigned int Size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32ae9f570cf8c48702fe65528ce670e4">iJIT_RegisterCallbackEx</a> (void *UserData, iJIT_ModeChangedEx NewModeCallBackFuncEx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#ae2ce670f3109150b2efb12d226c860f5">iJIT_IsProfilingActiveFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5bffee3ddefdca3064a05d7d0745280">iJIT_IsProfilingActive</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95749bba7428b736cd8a118e7938b3e0">iJIT_GetNewMethodID</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">NotifyEventPtr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac958a24d17ca97b2d947ff040d9536c0">NotifyEventFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">IttnotifyInfoPtr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a953103863f808fb5509da769307834bd">IttnotifyInfoFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RegisterCallbackExPtr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a679fa533798f070b5a24ced7e7016069">RegisterCallbackExFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">IsProfilingActivePtr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f4b3780107bf00e55fd0a10fc5dcd20">IsProfilingActiveFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">GetNewMethodIDPtr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeb62392e3c6d5c4512d2ea0dd301fce">GetNewMethodIDFunc</a></td>
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


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### FinalizeProcessPtr {#a68c8178cd12f04d8986cb58e286a66f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef void(* llvm::IntelJITEventsWrapper::FinalizeProcessPtr) (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>

</div>
</div>

### FinalizeThreadPtr {#a66df26b88f6ea2c4a4d6ef35934e9a1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef void(* llvm::IntelJITEventsWrapper::FinalizeThreadPtr) (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>

</div>
</div>

### GetNewMethodIDPtr {#a5126325fe62df4c38f0fb61940133b94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef unsigned int(* llvm::IntelJITEventsWrapper::GetNewMethodIDPtr) (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>

</div>
</div>

### IsProfilingActivePtr {#a4dd22ef9df781c9fc5788f055dcf058e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef iJIT_IsProfilingActiveFlags(* llvm::IntelJITEventsWrapper::IsProfilingActivePtr) (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>

</div>
</div>

### IttnotifyInfoPtr {#a5beb6a29928dab4382531981adf45534}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef int(* llvm::IntelJITEventsWrapper::IttnotifyInfoPtr) (IttEventType, const char *, unsigned int)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>

</div>
</div>

### NotifyEventPtr {#aee20e6512cbaf6fd7f2cf730d2e094cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef int(* llvm::IntelJITEventsWrapper::NotifyEventPtr) (iJIT_JVM_EVENT, void *)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>

</div>
</div>

### RegisterCallbackExPtr {#a4e32194570f68ddd0de55d66df2d77b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef void(* llvm::IntelJITEventsWrapper::RegisterCallbackExPtr) (void *, iJIT_ModeChangedEx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IntelJITEventsWrapper() {#a1ce833383f57f30f785e56b868aed3fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IntelJITEventsWrapper::IntelJITEventsWrapper ()</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>


<p>References <a href="#a95749bba7428b736cd8a118e7938b3e0">iJIT_GetNewMethodID</a>, <a href="#ab5bffee3ddefdca3064a05d7d0745280">iJIT_IsProfilingActive</a>, <a href="#abe60f00b9e149fcf0da28a67f6f3b99e">iJIT_NotifyEvent</a> and <a href="#a32ae9f570cf8c48702fe65528ce670e4">iJIT_RegisterCallbackEx</a>.</p>

</div>
</div>

### IntelJITEventsWrapper() {#a89593b9f883d95832af3362c52d87ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IntelJITEventsWrapper::IntelJITEventsWrapper (NotifyEventPtr NotifyEventImpl, IttnotifyInfoPtr IttnotifyInfoImpl, RegisterCallbackExPtr RegisterCallbackExImpl, IsProfilingActivePtr IsProfilingActiveImpl, FinalizeThreadPtr FinalizeThreadImpl, FinalizeProcessPtr FinalizeProcessImpl, GetNewMethodIDPtr GetNewMethodIDImpl)</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### iJIT\_GetNewMethodID() {#a95749bba7428b736cd8a118e7938b3e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::IntelJITEventsWrapper::iJIT_GetNewMethodID (void)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>


<p>Referenced by <a href="#a1ce833383f57f30f785e56b868aed3fb">IntelJITEventsWrapper</a>.</p>

</div>
</div>

### iJIT\_IsProfilingActive() {#ab5bffee3ddefdca3064a05d7d0745280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iJIT_IsProfilingActiveFlags llvm::IntelJITEventsWrapper::iJIT_IsProfilingActive (void)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a8f99ee9301a1b9fbef2522371a7a276ea003d5ada43d84de71c8794f89d642322">iJIT_NOTHING_RUNNING</a>.</p>


<p>Referenced by <a href="#a1ce833383f57f30f785e56b868aed3fb">IntelJITEventsWrapper</a> and <a href="#a4aa77793cbdbbea88f90848769a1258f">isAmplifierRunning</a>.</p>

</div>
</div>

### iJIT\_NotifyEvent() {#abe60f00b9e149fcf0da28a67f6f3b99e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::IntelJITEventsWrapper::iJIT_NotifyEvent (<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#ad89eccbfeaaaff0a0c323b734bfaaaca">iJIT_JVM_EVENT</a> EventType, void * EventSpecificData)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>


<p>Referenced by <a href="#a1ce833383f57f30f785e56b868aed3fb">IntelJITEventsWrapper</a>.</p>

</div>
</div>

### iJIT\_RegisterCallbackEx() {#a32ae9f570cf8c48702fe65528ce670e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntelJITEventsWrapper::iJIT_RegisterCallbackEx (void * UserData, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a8a9e9423a22e5b74f4aba216bc54d6f7">iJIT_ModeChangedEx</a> NewModeCallBackFuncEx)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>


<p>Referenced by <a href="#a1ce833383f57f30f785e56b868aed3fb">IntelJITEventsWrapper</a>.</p>

</div>
</div>

### iJitIttNotifyInfo() {#a6cbdf3c1836bb52618979e9eee28c91a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::IntelJITEventsWrapper::iJitIttNotifyInfo (<a href="/web-llvm/docs/api/namespaces/llvm/#a1e9832c872d8a59daf3b982a6d4f7782">IttEventType</a> EventType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, unsigned int Size)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### isAmplifierRunning() {#a4aa77793cbdbbea88f90848769a1258f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntelJITEventsWrapper::isAmplifierRunning ()</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>


<p>References <a href="#ab5bffee3ddefdca3064a05d7d0745280">iJIT_IsProfilingActive</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a8f99ee9301a1b9fbef2522371a7a276ea2bcc500a1cfac50a96374384c2e32ac9">iJIT_SAMPLING_ON</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### GetNewMethodIDFunc {#aaeb62392e3c6d5c4512d2ea0dd301fce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GetNewMethodIDPtr llvm::IntelJITEventsWrapper::GetNewMethodIDFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>

</div>
</div>

### IsProfilingActiveFunc {#a2f4b3780107bf00e55fd0a10fc5dcd20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IsProfilingActivePtr llvm::IntelJITEventsWrapper::IsProfilingActiveFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>

</div>
</div>

### IttnotifyInfoFunc {#a953103863f808fb5509da769307834bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IttnotifyInfoPtr llvm::IntelJITEventsWrapper::IttnotifyInfoFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>

</div>
</div>

### NotifyEventFunc {#ac958a24d17ca97b2d947ff040d9536c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NotifyEventPtr llvm::IntelJITEventsWrapper::NotifyEventFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>

</div>
</div>

### RegisterCallbackExFunc {#a679fa533798f070b5a24ced7e7016069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterCallbackExPtr llvm::IntelJITEventsWrapper::RegisterCallbackExFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/inteljiteventswrapper-h">IntelJITEventsWrapper.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
