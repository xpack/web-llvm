---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `jitprofiling.h` File



## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/-ijit-method-id">_iJIT_Method_Id</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/-ijit-method-nids">_iJIT_Method_NIDS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/-linenumberinfo">_LineNumberInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/-ijit-method-load">_iJIT_Method_Load</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">enum <a href="#a199e5cfae34a345dd07c5da4db615318">iJIT_jvm_event</a> <a href="#ad89eccbfeaaaff0a0c323b734bfaaaca">iJIT_JVM_EVENT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">enum <a href="#a5780b47887a514653abfb07c9e5205f2">_iJIT_ModeFlags</a> <a href="#a9fc5702ef48e9981c30a6390cf7d4102">iJIT_ModeFlags</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">enum <a href="#a8f99ee9301a1b9fbef2522371a7a276e">_iJIT_IsProfilingActiveFlags</a> <a href="#ae2ce670f3109150b2efb12d226c860f5">iJIT_IsProfilingActiveFlags</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">enum <a href="#a95ebe83a5829131400c97607ca80c3eb">_iJDEnvironmentType</a> <a href="#ac76adffb4deadb090af81e7c37d5ad59">iJDEnvironmentType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">struct <a href="/web-llvm/docs/api/structs/-ijit-method-id">_iJIT_Method_Id</a> * <a href="#acd1cb914df79a9e462cc26e4322981a8">piJIT_Method_Id</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">struct <a href="/web-llvm/docs/api/structs/-ijit-method-id">_iJIT_Method_Id</a> <a href="#af770d44031fa3080f6387d3a0528fa00">iJIT_Method_Id</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">struct <a href="/web-llvm/docs/api/structs/-ijit-method-nids">_iJIT_Method_NIDS</a> * <a href="#ae74ef2175e107d1da72c9020e98d9d2f">piJIT_Method_NIDS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">struct <a href="/web-llvm/docs/api/structs/-ijit-method-nids">_iJIT_Method_NIDS</a> <a href="#aadff65248454a357196d69a9f91a83e1">iJIT_Method_NIDS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">struct <a href="/web-llvm/docs/api/structs/-linenumberinfo">_LineNumberInfo</a> * <a href="#a14fb9f939b4c4ae910f347c8a2b94cf4">pLineNumberInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">struct <a href="/web-llvm/docs/api/structs/-linenumberinfo">_LineNumberInfo</a> <a href="#a9de37a123b4362809ea9d12abc877e2e">LineNumberInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">struct <a href="/web-llvm/docs/api/structs/-ijit-method-load">_iJIT_Method_Load</a> * <a href="#a50ee4919098ecf9377647514ba1377e1">piJIT_Method_Load</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">struct <a href="/web-llvm/docs/api/structs/-ijit-method-load">_iJIT_Method_Load</a> <a href="#adc57d106ae825b561c956511e6cd93b8">iJIT_Method_Load</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">void(* <a href="#a8a9e9423a22e5b74f4aba216bc54d6f7">iJIT_ModeChangedEx</a>)(void *UserData, iJIT_ModeFlags Flags)</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">iJIT_jvm_event { <a href="#a199e5cfae34a345dd07c5da4db615318">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">_iJIT_ModeFlags { <a href="#a5780b47887a514653abfb07c9e5205f2">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">_iJIT_IsProfilingActiveFlags { <a href="#a8f99ee9301a1b9fbef2522371a7a276e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">_iJDEnvironmentType { <a href="#a95ebe83a5829131400c97607ca80c3eb">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int <a href="#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16429a48f9effbd173e77f7b1fc05bbc">iJIT_NotifyEvent</a> (iJIT_JVM_EVENT event_type, void *EventSpecificData)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void <a href="#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6cd18fa90c18d98cdcd08c5341f0c36">iJIT_RegisterCallbackEx</a> (void *userdata, iJIT_ModeChangedEx NewModeCallBackFuncEx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae2ce670f3109150b2efb12d226c860f5">iJIT_IsProfilingActiveFlags</a> <a href="#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0f985e0b81991adccd02d38b5786f53">iJIT_IsProfilingActive</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void <a href="#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3280243e8668d8a9e4009ca8640641f">FinalizeThread</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void <a href="#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab51b33de33d9a67df6b6ca3c7c6eb72e">FinalizeProcess</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int <a href="#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ddb087cead0b7123f86acab667d3c75">iJIT_GetNewMethodID</a> (void)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01bfeee9d19b264d794d5afa46be9581">CDECL</a>&nbsp;&nbsp;&nbsp;__attribute__ ((cdecl))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a>&nbsp;&nbsp;&nbsp;<a href="#a01bfeee9d19b264d794d5afa46be9581">CDECL</a></td>
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

### iJDEnvironmentType {#ac76adffb4deadb090af81e7c37d5ad59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef enum _iJDEnvironmentType iJDEnvironmentType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>.</p>

</div>
</div>

### iJIT\_IsProfilingActiveFlags {#ae2ce670f3109150b2efb12d226c860f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef enum _iJIT_IsProfilingActiveFlags iJIT_IsProfilingActiveFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>.</p>

</div>
</div>

### iJIT\_JVM\_EVENT {#ad89eccbfeaaaff0a0c323b734bfaaaca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef enum iJIT_jvm_event iJIT_JVM_EVENT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>.</p>

</div>
</div>

### iJIT\_Method\_Id {#af770d44031fa3080f6387d3a0528fa00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct _iJIT_Method_Id iJIT_Method_Id</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>.</p>

</div>
</div>

### iJIT\_Method\_Load {#adc57d106ae825b561c956511e6cd93b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct _iJIT_Method_Load iJIT_Method_Load</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>.</p>

</div>
</div>

### iJIT\_Method\_NIDS {#aadff65248454a357196d69a9f91a83e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct _iJIT_Method_NIDS iJIT_Method_NIDS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>.</p>

</div>
</div>

### iJIT\_ModeChangedEx {#a8a9e9423a22e5b74f4aba216bc54d6f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef void(* iJIT_ModeChangedEx) (void *UserData, iJIT_ModeFlags Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>.</p>

</div>
</div>

### iJIT\_ModeFlags {#a9fc5702ef48e9981c30a6390cf7d4102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef enum _iJIT_ModeFlags iJIT_ModeFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>.</p>

</div>
</div>

### LineNumberInfo {#a9de37a123b4362809ea9d12abc877e2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct _LineNumberInfo LineNumberInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>.</p>

</div>
</div>

### piJIT\_Method\_Id {#acd1cb914df79a9e462cc26e4322981a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct _iJIT_Method_Id * piJIT_Method_Id</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>.</p>

</div>
</div>

### piJIT\_Method\_Load {#a50ee4919098ecf9377647514ba1377e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct _iJIT_Method_Load * piJIT_Method_Load</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>.</p>

</div>
</div>

### piJIT\_Method\_NIDS {#ae74ef2175e107d1da72c9020e98d9d2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct _iJIT_Method_NIDS * piJIT_Method_NIDS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>.</p>

</div>
</div>

### pLineNumberInfo {#a14fb9f939b4c4ae910f347c8a2b94cf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct _LineNumberInfo * pLineNumberInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### \_iJDEnvironmentType {#a95ebe83a5829131400c97607ca80c3eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum _iJDEnvironmentType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">iJDE_JittingAPI<a id="a95ebe83a5829131400c97607ca80c3eba5bdd71c0c65348e20edfde628c45e842"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>.</p>

</div>
</div>

### \_iJIT\_IsProfilingActiveFlags {#a8f99ee9301a1b9fbef2522371a7a276e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum _iJIT_IsProfilingActiveFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">iJIT_NOTHING_RUNNING<a id="a8f99ee9301a1b9fbef2522371a7a276ea003d5ada43d84de71c8794f89d642322"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">iJIT_SAMPLING_ON<a id="a8f99ee9301a1b9fbef2522371a7a276ea2bcc500a1cfac50a96374384c2e32ac9"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0001)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">iJIT_CALLGRAPH_ON<a id="a8f99ee9301a1b9fbef2522371a7a276ea85719f2ac63a67bca4e81dcc4fba3efb"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0002)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>.</p>

</div>
</div>

### \_iJIT\_ModeFlags {#a5780b47887a514653abfb07c9e5205f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum _iJIT_ModeFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">iJIT_NO_NOTIFICATIONS<a id="a5780b47887a514653abfb07c9e5205f2af77bf094413590702ed9b78f9db2a6e5"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">iJIT_BE_NOTIFY_ON_LOAD<a id="a5780b47887a514653abfb07c9e5205f2aed8222ab35ff01a262af0679b3194303"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0001)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">iJIT_BE_NOTIFY_ON_UNLOAD<a id="a5780b47887a514653abfb07c9e5205f2aa72013898109acd0d3d8e37f7b7cdcc3"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0002)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">iJIT_BE_NOTIFY_ON_METHOD_ENTRY<a id="a5780b47887a514653abfb07c9e5205f2a1e0b4723a0d1421d0d22842b3ba33b7c"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0004)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">iJIT_BE_NOTIFY_ON_METHOD_EXIT<a id="a5780b47887a514653abfb07c9e5205f2aa127cbd6e164e59b16b233080b375397"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0008)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>.</p>

</div>
</div>

### iJIT\_jvm\_event {#a199e5cfae34a345dd07c5da4db615318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum iJIT_jvm_event </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">iJVM_EVENT_TYPE_SHUTDOWN<a id="a199e5cfae34a345dd07c5da4db615318af363c1721239197cf2ffb8b031025894"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">iJVM_EVENT_TYPE_METHOD_LOAD_FINISHED<a id="a199e5cfae34a345dd07c5da4db615318aace21abae9888611f9fb6e6cf1922b20"></a></td>
<td class="doxyEnumItemDescription"> (=13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">iJVM_EVENT_TYPE_METHOD_UNLOAD_START<a id="a199e5cfae34a345dd07c5da4db615318abaeae040e439fd0de07f2b09b4ae99d5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">iJVM_EVENT_TYPE_ENTER_NIDS<a id="a199e5cfae34a345dd07c5da4db615318a1b667d42213ffe00228fb5cd5c29bc4e"></a></td>
<td class="doxyEnumItemDescription"> (= 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">iJVM_EVENT_TYPE_LEAVE_NIDS<a id="a199e5cfae34a345dd07c5da4db615318a45dd237764e9e20cf5b911fe7f9c0715"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### FinalizeProcess() {#ab51b33de33d9a67df6b6ca3c7c6eb72e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void JITAPI FinalizeProcess (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>, definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/ittnotify-config-h/#a75bd05b58b95269fd7ec2733d198bb5c">ITT_EXTERN_C</a>, <a href="#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c/#ae3a9d294b5778b3c976158ce5b4f4fd1">m_libHandle</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c/#a4c633f61dd4522f6460d32573d597012">threadLocalStorageHandle</a>.</p>

</div>
</div>

### FinalizeThread() {#ad3280243e8668d8a9e4009ca8640641f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void JITAPI FinalizeThread (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>, definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/ittnotify-config-h/#a75bd05b58b95269fd7ec2733d198bb5c">ITT_EXTERN_C</a>, <a href="#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c/#a4c633f61dd4522f6460d32573d597012">threadLocalStorageHandle</a>.</p>

</div>
</div>

### iJIT\_GetNewMethodID() {#a6ddb087cead0b7123f86acab667d3c75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int JITAPI iJIT_GetNewMethodID (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>, definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/ittnotify-config-h/#a75bd05b58b95269fd7ec2733d198bb5c">ITT_EXTERN_C</a> and <a href="#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a>.</p>

</div>
</div>

### iJIT\_IsProfilingActive() {#af0f985e0b81991adccd02d38b5786f53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iJIT_IsProfilingActiveFlags JITAPI iJIT_IsProfilingActive (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>, definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c/#aa761e140d407061f7109247508a627d6">executionMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c/#a6e49f23ff7e2149fe7a4563a922ebb19">iJIT_DLL_is_missing</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/ittnotify-config-h/#a75bd05b58b95269fd7ec2733d198bb5c">ITT_EXTERN_C</a>, <a href="#a92cbb0cf70e79bc468636cafa12959f7">JITAPI</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c/#a8807a1a83ceb9d9b919ee053279c2eb1">loadiJIT_Funcs</a>.</p>

</div>
</div>

### iJIT\_NotifyEvent() {#a16429a48f9effbd173e77f7b1fc05bbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int JITAPI iJIT_NotifyEvent (<a href="#ad89eccbfeaaaff0a0c323b734bfaaaca">iJIT_JVM_EVENT</a> event_type, void * EventSpecificData)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/threadstack/#af7885747136b2ac6f58da881307e72b4">ThreadStack::CurrentStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c/#aa761e140d407061f7109247508a627d6">executionMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c/#a6f2e5cae63a4eafe49691dde6106c3c6">FUNC_NotifyEvent</a>, <a href="#a8f99ee9301a1b9fbef2522371a7a276ea85719f2ac63a67bca4e81dcc4fba3efb">iJIT_CALLGRAPH_ON</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c/#a6e49f23ff7e2149fe7a4563a922ebb19">iJIT_DLL_is_missing</a>, <a href="#a199e5cfae34a345dd07c5da4db615318a1b667d42213ffe00228fb5cd5c29bc4e">iJVM_EVENT_TYPE_ENTER_NIDS</a>, <a href="#a199e5cfae34a345dd07c5da4db615318a45dd237764e9e20cf5b911fe7f9c0715">iJVM_EVENT_TYPE_LEAVE_NIDS</a>, <a href="#a199e5cfae34a345dd07c5da4db615318aace21abae9888611f9fb6e6cf1922b20">iJVM_EVENT_TYPE_METHOD_LOAD_FINISHED</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c/#a2792b04f28d4dc2019f59879a8fc1a77">INIT_TOP_Stack</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c/#a8807a1a83ceb9d9b919ee053279c2eb1">loadiJIT_Funcs</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c/#a4c633f61dd4522f6460d32573d597012">threadLocalStorageHandle</a> and <a href="/web-llvm/docs/api/structs/threadstack/#a04b1a308e0995dfb38ab967929a0fc5f">ThreadStack::TopStack</a>.</p>

</div>
</div>

### iJIT\_RegisterCallbackEx() {#ae6cd18fa90c18d98cdcd08c5341f0c36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void JITAPI iJIT_RegisterCallbackEx (void * userdata, <a href="#a8a9e9423a22e5b74f4aba216bc54d6f7">iJIT_ModeChangedEx</a> NewModeCallBackFuncEx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>, definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c">jitprofiling.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c/#a6e49f23ff7e2149fe7a4563a922ebb19">iJIT_DLL_is_missing</a>, <a href="#a5780b47887a514653abfb07c9e5205f2af77bf094413590702ed9b78f9db2a6e5">iJIT_NO_NOTIFICATIONS</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c/#a8807a1a83ceb9d9b919ee053279c2eb1">loadiJIT_Funcs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### CDECL {#a01bfeee9d19b264d794d5afa46be9581}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CDECL&nbsp;&nbsp;&nbsp;__attribute__ ((cdecl))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>.</p>

</div>
</div>

### JITAPI {#a92cbb0cf70e79bc468636cafa12959f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define JITAPI&nbsp;&nbsp;&nbsp;<a href="#a01bfeee9d19b264d794d5afa46be9581">CDECL</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h">jitprofiling.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c/#ad348849099cc0c7403485c04aea9429f">FinalizeProcess</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c/#a28a99f7211f61c71087d7eb8a911e977">FinalizeThread</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c/#a19cfacf238fbb0cdebdc1e7ce6639d81">iJIT_GetNewMethodID</a> and <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-c/#a4e9a58025c5ff17f235cc116ae1c2d93">iJIT_IsProfilingActive</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
