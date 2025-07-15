---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `jitprofiling.c` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/ittnotify-config-h">ittnotify_config.h</a>"
#include &lt;windows.h&gt;
#include &lt;stdlib.h&gt;
#include "<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/threadstack">ThreadStack</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">unsigned int(* <a href="#a8a0daee844b67e1f29bf160d165763d8">TPInitialize</a>)(void)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">unsigned int(* <a href="#a0d3edc030f9e8d548e4da8d6fa7e47b0">TPNotify</a>)(unsigned int, void *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">struct <a href="/web-llvm/docs/api/structs/threadstack">ThreadStack</a> * <a href="#a4bbc4ac8ebdbbe1dc5524881da79cbd4">pThreadStack</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8807a1a83ceb9d9b919ee053279c2eb1">loadiJIT_Funcs</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/ittnotify-config-h/#a75bd05b58b95269fd7ec2733d198bb5c">ITT_EXTERN_C</a> int <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7876453425913dbb7c7495333d1a1670">iJIT_NotifyEvent</a> (iJIT_JVM_EVENT event_type, void *EventSpecificData)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/ittnotify-config-h/#a75bd05b58b95269fd7ec2733d198bb5c">ITT_EXTERN_C</a> void <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24f33968dcb98c8b1d2bba20fb313708">iJIT_RegisterCallbackEx</a> (void *userdata, iJIT_ModeChangedEx NewModeCallBackFuncEx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/ittnotify-config-h/#a75bd05b58b95269fd7ec2733d198bb5c">ITT_EXTERN_C</a> <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#ae2ce670f3109150b2efb12d226c860f5">iJIT_IsProfilingActiveFlags</a> <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e9a58025c5ff17f235cc116ae1c2d93">iJIT_IsProfilingActive</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/ittnotify-config-h/#a75bd05b58b95269fd7ec2733d198bb5c">ITT_EXTERN_C</a> void <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28a99f7211f61c71087d7eb8a911e977">FinalizeThread</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/ittnotify-config-h/#a75bd05b58b95269fd7ec2733d198bb5c">ITT_EXTERN_C</a> void <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad348849099cc0c7403485c04aea9429f">FinalizeProcess</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/ittnotify-config-h/#a75bd05b58b95269fd7ec2733d198bb5c">ITT_EXTERN_C</a> unsigned int <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19cfacf238fbb0cdebdc1e7ce6639d81">iJIT_GetNewMethodID</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69f59503b72db9ae6ac36f5f5deaeb80">rcsid</a>[] = "\n@(#) $Revision: 243501 $\n"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">HINSTANCE</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3a9d294b5778b3c976158ce5b4f4fd1">m_libHandle</a> = NULL</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a8a0daee844b67e1f29bf160d165763d8">TPInitialize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68d3a174939daf9b21297cdd199115b2">FUNC_Initialize</a> =NULL</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a0d3edc030f9e8d548e4da8d6fa7e47b0">TPNotify</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f2e5cae63a4eafe49691dde6106c3c6">FUNC_NotifyEvent</a> =NULL</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#ae2ce670f3109150b2efb12d226c860f5">iJIT_IsProfilingActiveFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa761e140d407061f7109247508a627d6">executionMode</a> = <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a8f99ee9301a1b9fbef2522371a7a276ea003d5ada43d84de71c8794f89d642322">iJIT_NOTHING_RUNNING</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e49f23ff7e2149fe7a4563a922ebb19">iJIT_DLL_is_missing</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static DWORD</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c633f61dd4522f6460d32573d597012">threadLocalStorageHandle</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9e826deed651f200060bf115005bed6">DLL_ENVIRONMENT_VAR</a>&nbsp;&nbsp;&nbsp;"VS_PROFILER"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93438cb389b5d6a5d89e96c86d1effb9">NEW_DLL_ENVIRONMENT_VAR</a>&nbsp;&nbsp;&nbsp;"INTEL_JIT_PROFILER32"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27bdde8c416038c61f7bcbc2d34eeaad">DEFAULT_DLLNAME</a>&nbsp;&nbsp;&nbsp;"JitPI.dll"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a014a59181ea2ebcd3472c7bb342424b4">ANDROID_JIT_AGENT_PATH</a>&nbsp;&nbsp;&nbsp;"/data/intel/libittnotify.so"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2792b04f28d4dc2019f59879a8fc1a77">INIT_TOP_Stack</a>&nbsp;&nbsp;&nbsp;10000</td>
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

## Typedefs

### pThreadStack {#a4bbc4ac8ebdbbe1dc5524881da79cbd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef  struct ThreadStack * pThreadStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>

</div>
</div>

### TPInitialize {#a8a0daee844b67e1f29bf160d165763d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef unsigned int(* TPInitialize) (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>

</div>
</div>

### TPNotify {#a0d3edc030f9e8d548e4da8d6fa7e47b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef unsigned int(* TPNotify) (unsigned int, void *)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### FinalizeProcess() {#ad348849099cc0c7403485c04aea9429f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ITT_EXTERN_C void JITAPI FinalizeProcess (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/ittnotify-config-h/#a75bd05b58b95269fd7ec2733d198bb5c">ITT_EXTERN_C</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a>, <a href="#ae3a9d294b5778b3c976158ce5b4f4fd1">m_libHandle</a> and <a href="#a4c633f61dd4522f6460d32573d597012">threadLocalStorageHandle</a>.</p>

</div>
</div>

### FinalizeThread() {#a28a99f7211f61c71087d7eb8a911e977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ITT_EXTERN_C void JITAPI FinalizeThread (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/ittnotify-config-h/#a75bd05b58b95269fd7ec2733d198bb5c">ITT_EXTERN_C</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a> and <a href="#a4c633f61dd4522f6460d32573d597012">threadLocalStorageHandle</a>.</p>

</div>
</div>

### iJIT\_GetNewMethodID() {#a19cfacf238fbb0cdebdc1e7ce6639d81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ITT_EXTERN_C unsigned int JITAPI iJIT_GetNewMethodID (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/ittnotify-config-h/#a75bd05b58b95269fd7ec2733d198bb5c">ITT_EXTERN_C</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a>.</p>

</div>
</div>

### iJIT\_IsProfilingActive() {#a4e9a58025c5ff17f235cc116ae1c2d93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ITT_EXTERN_C iJIT_IsProfilingActiveFlags JITAPI iJIT_IsProfilingActive (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>References <a href="#aa761e140d407061f7109247508a627d6">executionMode</a>, <a href="#a6e49f23ff7e2149fe7a4563a922ebb19">iJIT_DLL_is_missing</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/ittnotify-config-h/#a75bd05b58b95269fd7ec2733d198bb5c">ITT_EXTERN_C</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a> and <a href="#a8807a1a83ceb9d9b919ee053279c2eb1">loadiJIT_Funcs</a>.</p>

</div>
</div>

### iJIT\_NotifyEvent() {#a7876453425913dbb7c7495333d1a1670}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ITT_EXTERN_C int JITAPI iJIT_NotifyEvent (<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#ad89eccbfeaaaff0a0c323b734bfaaaca">iJIT_JVM_EVENT</a> event_type, void * EventSpecificData)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/threadstack/#af7885747136b2ac6f58da881307e72b4">ThreadStack::CurrentStack</a>, <a href="#aa761e140d407061f7109247508a627d6">executionMode</a>, <a href="#a6f2e5cae63a4eafe49691dde6106c3c6">FUNC_NotifyEvent</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a8f99ee9301a1b9fbef2522371a7a276ea85719f2ac63a67bca4e81dcc4fba3efb">iJIT_CALLGRAPH_ON</a>, <a href="#a6e49f23ff7e2149fe7a4563a922ebb19">iJIT_DLL_is_missing</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a199e5cfae34a345dd07c5da4db615318a1b667d42213ffe00228fb5cd5c29bc4e">iJVM_EVENT_TYPE_ENTER_NIDS</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a199e5cfae34a345dd07c5da4db615318a45dd237764e9e20cf5b911fe7f9c0715">iJVM_EVENT_TYPE_LEAVE_NIDS</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a199e5cfae34a345dd07c5da4db615318aace21abae9888611f9fb6e6cf1922b20">iJVM_EVENT_TYPE_METHOD_LOAD_FINISHED</a>, <a href="#a2792b04f28d4dc2019f59879a8fc1a77">INIT_TOP_Stack</a>, <a href="#a8807a1a83ceb9d9b919ee053279c2eb1">loadiJIT_Funcs</a>, <a href="#a4c633f61dd4522f6460d32573d597012">threadLocalStorageHandle</a> and <a href="/web-llvm/docs/api/structs/threadstack/#a04b1a308e0995dfb38ab967929a0fc5f">ThreadStack::TopStack</a>.</p>

</div>
</div>

### iJIT\_RegisterCallbackEx() {#a24f33968dcb98c8b1d2bba20fb313708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ITT_EXTERN_C void JITAPI iJIT_RegisterCallbackEx (void * userdata, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a8a9e9423a22e5b74f4aba216bc54d6f7">iJIT_ModeChangedEx</a> NewModeCallBackFuncEx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>References <a href="#a6e49f23ff7e2149fe7a4563a922ebb19">iJIT_DLL_is_missing</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a5780b47887a514653abfb07c9e5205f2af77bf094413590702ed9b78f9db2a6e5">iJIT_NO_NOTIFICATIONS</a> and <a href="#a8807a1a83ceb9d9b919ee053279c2eb1">loadiJIT_Funcs</a>.</p>

</div>
</div>

### loadiJIT\_Funcs() {#a8807a1a83ceb9d9b919ee053279c2eb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int loadiJIT_Funcs (void)</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>References <a href="#a014a59181ea2ebcd3472c7bb342424b4">ANDROID_JIT_AGENT_PATH</a>, <a href="#a27bdde8c416038c61f7bcbc2d34eeaad">DEFAULT_DLLNAME</a>, <a href="#aa9e826deed651f200060bf115005bed6">DLL_ENVIRONMENT_VAR</a>, <a href="#aa761e140d407061f7109247508a627d6">executionMode</a>, <a href="#a68d3a174939daf9b21297cdd199115b2">FUNC_Initialize</a>, <a href="#a6f2e5cae63a4eafe49691dde6106c3c6">FUNC_NotifyEvent</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a8f99ee9301a1b9fbef2522371a7a276ea85719f2ac63a67bca4e81dcc4fba3efb">iJIT_CALLGRAPH_ON</a>, <a href="#a6e49f23ff7e2149fe7a4563a922ebb19">iJIT_DLL_is_missing</a>, <a href="#ae3a9d294b5778b3c976158ce5b4f4fd1">m_libHandle</a>, <a href="#a93438cb389b5d6a5d89e96c86d1effb9">NEW_DLL_ENVIRONMENT_VAR</a>, <a href="#a69f59503b72db9ae6ac36f5f5deaeb80">rcsid</a> and <a href="#a4c633f61dd4522f6460d32573d597012">threadLocalStorageHandle</a>.</p>


<p>Referenced by <a href="#a4e9a58025c5ff17f235cc116ae1c2d93">iJIT_IsProfilingActive</a>, <a href="#a7876453425913dbb7c7495333d1a1670">iJIT_NotifyEvent</a> and <a href="#a24f33968dcb98c8b1d2bba20fb313708">iJIT_RegisterCallbackEx</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### executionMode {#aa761e140d407061f7109247508a627d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iJIT_IsProfilingActiveFlags executionMode = <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a8f99ee9301a1b9fbef2522371a7a276ea003d5ada43d84de71c8794f89d642322">iJIT_NOTHING_RUNNING</a></td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>Referenced by <a href="#a4e9a58025c5ff17f235cc116ae1c2d93">iJIT_IsProfilingActive</a>, <a href="#a7876453425913dbb7c7495333d1a1670">iJIT_NotifyEvent</a> and <a href="#a8807a1a83ceb9d9b919ee053279c2eb1">loadiJIT_Funcs</a>.</p>

</div>
</div>

### FUNC\_Initialize {#a68d3a174939daf9b21297cdd199115b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TPInitialize FUNC_Initialize =NULL</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>Referenced by <a href="#a8807a1a83ceb9d9b919ee053279c2eb1">loadiJIT_Funcs</a>.</p>

</div>
</div>

### FUNC\_NotifyEvent {#a6f2e5cae63a4eafe49691dde6106c3c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TPNotify FUNC_NotifyEvent =NULL</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>Referenced by <a href="#a7876453425913dbb7c7495333d1a1670">iJIT_NotifyEvent</a> and <a href="#a8807a1a83ceb9d9b919ee053279c2eb1">loadiJIT_Funcs</a>.</p>

</div>
</div>

### iJIT\_DLL\_is\_missing {#a6e49f23ff7e2149fe7a4563a922ebb19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int iJIT_DLL_is_missing = 0</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>Referenced by <a href="#a4e9a58025c5ff17f235cc116ae1c2d93">iJIT_IsProfilingActive</a>, <a href="#a7876453425913dbb7c7495333d1a1670">iJIT_NotifyEvent</a>, <a href="#a24f33968dcb98c8b1d2bba20fb313708">iJIT_RegisterCallbackEx</a> and <a href="#a8807a1a83ceb9d9b919ee053279c2eb1">loadiJIT_Funcs</a>.</p>

</div>
</div>

### m\_libHandle {#ae3a9d294b5778b3c976158ce5b4f4fd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HINSTANCE m_libHandle = NULL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>Referenced by <a href="#ad348849099cc0c7403485c04aea9429f">FinalizeProcess</a> and <a href="#a8807a1a83ceb9d9b919ee053279c2eb1">loadiJIT_Funcs</a>.</p>

</div>
</div>

### rcsid {#a69f59503b72db9ae6ac36f5f5deaeb80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char rcsid[] = "\n@(#) $Revision: 243501 $\n"</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>Referenced by <a href="#a8807a1a83ceb9d9b919ee053279c2eb1">loadiJIT_Funcs</a>.</p>

</div>
</div>

### threadLocalStorageHandle {#a4c633f61dd4522f6460d32573d597012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWORD threadLocalStorageHandle = 0</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>Referenced by <a href="#ad348849099cc0c7403485c04aea9429f">FinalizeProcess</a>, <a href="#a28a99f7211f61c71087d7eb8a911e977">FinalizeThread</a>, <a href="#a7876453425913dbb7c7495333d1a1670">iJIT_NotifyEvent</a> and <a href="#a8807a1a83ceb9d9b919ee053279c2eb1">loadiJIT_Funcs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ANDROID\_JIT\_AGENT\_PATH {#a014a59181ea2ebcd3472c7bb342424b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ANDROID_JIT_AGENT_PATH&nbsp;&nbsp;&nbsp;"/data/intel/libittnotify.so"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>Referenced by <a href="#a8807a1a83ceb9d9b919ee053279c2eb1">loadiJIT_Funcs</a>.</p>

</div>
</div>

### DEFAULT\_DLLNAME {#a27bdde8c416038c61f7bcbc2d34eeaad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEFAULT_DLLNAME&nbsp;&nbsp;&nbsp;"JitPI.dll"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>Referenced by <a href="#a8807a1a83ceb9d9b919ee053279c2eb1">loadiJIT_Funcs</a>.</p>

</div>
</div>

### DLL\_ENVIRONMENT\_VAR {#aa9e826deed651f200060bf115005bed6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DLL_ENVIRONMENT_VAR&nbsp;&nbsp;&nbsp;"VS_PROFILER"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>Referenced by <a href="#a8807a1a83ceb9d9b919ee053279c2eb1">loadiJIT_Funcs</a>.</p>

</div>
</div>

### INIT\_TOP\_Stack {#a2792b04f28d4dc2019f59879a8fc1a77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INIT_TOP_Stack&nbsp;&nbsp;&nbsp;10000</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>Referenced by <a href="#a7876453425913dbb7c7495333d1a1670">iJIT_NotifyEvent</a>.</p>

</div>
</div>

### NEW\_DLL\_ENVIRONMENT\_VAR {#a93438cb389b5d6a5d89e96c86d1effb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define NEW_DLL_ENVIRONMENT_VAR&nbsp;&nbsp;&nbsp;"INTEL_JIT_PROFILER32"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>Referenced by <a href="#a8807a1a83ceb9d9b919ee053279c2eb1">loadiJIT_Funcs</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
