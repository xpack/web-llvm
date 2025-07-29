---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/oprofilewrapper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `OProfileWrapper` Class



## Declaration

<div class="doxyDeclaration">
class llvm::OProfileWrapper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">llvm/ExecutionEngine/OProfileWrapper.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">op_agent_t(* <a href="#a75500a74b6aede9091e827266323edad">op_open_agent_ptr_t</a>)()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">int(* <a href="#ac8adf0973fede17edc3aca93293e4166">op_close_agent_ptr_t</a>)(op_agent_t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">int(* <a href="#acad45a7f0979f7adcfc9baebe3a29980">op_write_native_code_ptr_t</a>)(op_agent_t, const char *, uint64_t, void const *, const unsigned int)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">int(* <a href="#aa7a59283014492ebc2854c9278f551e6">op_write_debug_line_info_ptr_t</a>)(op_agent_t, void const *, size_t, struct debug_line_info const *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">int(* <a href="#a0b9238754b47e4e5272152924336f8ed">op_unload_native_code_ptr_t</a>)(op_agent_t, uint64_t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">int(* <a href="#ac51dbddff6da81e6b37a1b5c368315a7">op_major_version_ptr_t</a>)()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">bool(* <a href="#a92d45a86bc126d23397da2a003a49720">IsOProfileRunningPtrT</a>)()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c1eb099fa26c019fa3f5e3c30a09b67">OProfileWrapper</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab55220d896b5ef2850bc4e5abf721113">OProfileWrapper</a> (op_open_agent_ptr_t OpenAgentImpl, op_close_agent_ptr_t CloseAgentImpl, op_write_native_code_ptr_t WriteNativeCodeImpl, op_write_debug_line_info_ptr_t WriteDebugLineInfoImpl, op_unload_native_code_ptr_t UnloadNativeCodeImpl, op_major_version_ptr_t MajorVersionImpl, op_major_version_ptr_t MinorVersionImpl, IsOProfileRunningPtrT MockIsOProfileRunningImpl=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5429b9da01b158fac3e5da48a72010bc">op_open_agent</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b250a24143710b280bb480210a31bcf">op_close_agent</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24f0da9d90ea20da52b527394d248aab">op_write_native_code</a> (const char *name, uint64_t addr, void const *code, const unsigned int size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf54432b7e558fe9cc479ce12abfa249">op_write_debug_line_info</a> (void const *code, size_t num_entries, struct debug_line_info const *info)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dbe6059e3d02647966bd2e6e54a9aba">op_unload_native_code</a> (uint64_t addr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad73d8440953a2a32714c7e99151b5cc9">op_major_version</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad56a244a605b066fd37756f8bcf5e2f9">op_minor_version</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77fbdf212dbb6035c0a77d98c8d74224">isAgentAvailable</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31ac4f17a7d15f2424b2b7886d046f3f">initialize</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af79d15964c70bf3e0ffcfbbe67a979bb">checkForOProfileProcEntry</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad01b21bd64e604d4d1e8ad396d9d192a">isOProfileRunning</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">op_agent_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0c3e2996fb063e41570b5db236fcb8b">Agent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">op_open_agent_ptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82024a02f9dc69caa63867832f406983">OpenAgentFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">op_close_agent_ptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac99eb1737bdcb68a02ca0a4916745ec0">CloseAgentFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">op_write_native_code_ptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec57eb3cd98e34cbc74926a4c0d1d9a">WriteNativeCodeFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">op_write_debug_line_info_ptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25f69e3b596799c34d49f8fcf81f5b2f">WriteDebugLineInfoFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">op_unload_native_code_ptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a433d5769b183a2f118fa17633470e763">UnloadNativeCodeFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">op_major_version_ptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab5f22542fabe6aa754b9049f97c9bd5">MajorVersionFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">op_major_version_ptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a602d515bf1707f315662de43f046b868">MinorVersionFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">IsOProfileRunningPtrT</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5608372ed6e9bfd7b10eb64a0794822">IsOProfileRunningFunc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68236d44819263af6eddcf377ba88cfc">Initialized</a></td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### IsOProfileRunningPtrT {#a92d45a86bc126d23397da2a003a49720}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef bool(* llvm::OProfileWrapper::IsOProfileRunningPtrT) ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>.</p>

</div>
</div>

### op\_close\_agent\_ptr\_t {#ac8adf0973fede17edc3aca93293e4166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef int(* llvm::OProfileWrapper::op_close_agent_ptr_t) (op_agent_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>.</p>

</div>
</div>

### op\_major\_version\_ptr\_t {#ac51dbddff6da81e6b37a1b5c368315a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef int(* llvm::OProfileWrapper::op_major_version_ptr_t) ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>.</p>

</div>
</div>

### op\_open\_agent\_ptr\_t {#a75500a74b6aede9091e827266323edad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef op_agent_t(* llvm::OProfileWrapper::op_open_agent_ptr_t) ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>.</p>

</div>
</div>

### op\_unload\_native\_code\_ptr\_t {#a0b9238754b47e4e5272152924336f8ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef int(* llvm::OProfileWrapper::op_unload_native_code_ptr_t) (op_agent_t, uint64_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>.</p>

</div>
</div>

### op\_write\_debug\_line\_info\_ptr\_t {#aa7a59283014492ebc2854c9278f551e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef int(* llvm::OProfileWrapper::op_write_debug_line_info_ptr_t) (op_agent_t, void const  *, size_t, struct debug_line_info const  *)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>.</p>

</div>
</div>

### op\_write\_native\_code\_ptr\_t {#acad45a7f0979f7adcfc9baebe3a29980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef int(* llvm::OProfileWrapper::op_write_native_code_ptr_t) (op_agent_t, const char *, uint64_t, void const  *, const unsigned int)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### OProfileWrapper() {#a0c1eb099fa26c019fa3f5e3c30a09b67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OProfileWrapper::OProfileWrapper ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/oprofilejit/oprofilewrapper-cpp">OProfileWrapper.cpp</a>.</p>

</div>
</div>

### OProfileWrapper() {#ab55220d896b5ef2850bc4e5abf721113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OProfileWrapper::OProfileWrapper (op_open_agent_ptr_t OpenAgentImpl, op_close_agent_ptr_t CloseAgentImpl, op_write_native_code_ptr_t WriteNativeCodeImpl, op_write_debug_line_info_ptr_t WriteDebugLineInfoImpl, op_unload_native_code_ptr_t UnloadNativeCodeImpl, op_major_version_ptr_t MajorVersionImpl, op_major_version_ptr_t MinorVersionImpl, IsOProfileRunningPtrT MockIsOProfileRunningImpl=0)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isAgentAvailable() {#a77fbdf212dbb6035c0a77d98c8d74224}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OProfileWrapper::isAgentAvailable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/oprofilejit/oprofilewrapper-cpp">OProfileWrapper.cpp</a>.</p>

</div>
</div>

### op\_close\_agent() {#a8b250a24143710b280bb480210a31bcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::OProfileWrapper::op_close_agent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>, definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/oprofilejit/oprofilewrapper-cpp">OProfileWrapper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">initialize</a>.</p>

</div>
</div>

### op\_major\_version() {#ad73d8440953a2a32714c7e99151b5cc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::OProfileWrapper::op_major_version ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>, definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/oprofilejit/oprofilewrapper-cpp">OProfileWrapper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">initialize</a>.</p>

</div>
</div>

### op\_minor\_version() {#ad56a244a605b066fd37756f8bcf5e2f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::OProfileWrapper::op_minor_version ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>, definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/oprofilejit/oprofilewrapper-cpp">OProfileWrapper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">initialize</a>.</p>

</div>
</div>

### op\_open\_agent() {#a5429b9da01b158fac3e5da48a72010bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OProfileWrapper::op_open_agent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/oprofilejit/oprofilewrapper-cpp">OProfileWrapper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">initialize</a>.</p>

</div>
</div>

### op\_unload\_native\_code() {#a6dbe6059e3d02647966bd2e6e54a9aba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::OProfileWrapper::op_unload_native_code (uint64_t addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>, definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/oprofilejit/oprofilewrapper-cpp">OProfileWrapper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">initialize</a>.</p>

</div>
</div>

### op\_write\_debug\_line\_info() {#abf54432b7e558fe9cc479ce12abfa249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::OProfileWrapper::op_write_debug_line_info (void <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * code, size_t num_entries, struct debug_line_info <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>, definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/oprofilejit/oprofilewrapper-cpp">OProfileWrapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">initialize</a>.</p>

</div>
</div>

### op\_write\_native\_code() {#a24f0da9d90ea20da52b527394d248aab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::OProfileWrapper::op_write_native_code (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * name, uint64_t addr, void <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * code, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned int size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>, definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/oprofilejit/oprofilewrapper-cpp">OProfileWrapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">initialize</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### checkForOProfileProcEntry() {#af79d15964c70bf3e0ffcfbbe67a979bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OProfileWrapper::checkForOProfileProcEntry ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/oprofilejit/oprofilewrapper-cpp">OProfileWrapper.cpp</a>.</p>

</div>
</div>

### initialize() {#a31ac4f17a7d15f2424b2b7886d046f3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OProfileWrapper::initialize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/oprofilejit/oprofilewrapper-cpp">OProfileWrapper.cpp</a>.</p>

</div>
</div>

### isOProfileRunning() {#ad01b21bd64e604d4d1e8ad396d9d192a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OProfileWrapper::isOProfileRunning ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/oprofilejit/oprofilewrapper-cpp">OProfileWrapper.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Agent {#ac0c3e2996fb063e41570b5db236fcb8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_agent_t llvm::OProfileWrapper::Agent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>.</p>

</div>
</div>

### CloseAgentFunc {#ac99eb1737bdcb68a02ca0a4916745ec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_close_agent_ptr_t llvm::OProfileWrapper::CloseAgentFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>.</p>

</div>
</div>

### Initialized {#a68236d44819263af6eddcf377ba88cfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OProfileWrapper::Initialized</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>.</p>

</div>
</div>

### IsOProfileRunningFunc {#aa5608372ed6e9bfd7b10eb64a0794822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IsOProfileRunningPtrT llvm::OProfileWrapper::IsOProfileRunningFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>.</p>

</div>
</div>

### MajorVersionFunc {#aab5f22542fabe6aa754b9049f97c9bd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_major_version_ptr_t llvm::OProfileWrapper::MajorVersionFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>.</p>

</div>
</div>

### MinorVersionFunc {#a602d515bf1707f315662de43f046b868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_major_version_ptr_t llvm::OProfileWrapper::MinorVersionFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>.</p>

</div>
</div>

### OpenAgentFunc {#a82024a02f9dc69caa63867832f406983}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_open_agent_ptr_t llvm::OProfileWrapper::OpenAgentFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>.</p>

</div>
</div>

### UnloadNativeCodeFunc {#a433d5769b183a2f118fa17633470e763}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_unload_native_code_ptr_t llvm::OProfileWrapper::UnloadNativeCodeFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>.</p>

</div>
</div>

### WriteDebugLineInfoFunc {#a25f69e3b596799c34d49f8fcf81f5b2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_write_debug_line_info_ptr_t llvm::OProfileWrapper::WriteDebugLineInfoFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>.</p>

</div>
</div>

### WriteNativeCodeFunc {#a1ec57eb3cd98e34cbc74926a4c0d1d9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_write_native_code_ptr_t llvm::OProfileWrapper::WriteNativeCodeFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/oprofilewrapper-h">OProfileWrapper.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/oprofilejit/oprofilewrapper-cpp">OProfileWrapper.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
