---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/orc/tpctypes/sharedmemorysegfinalizerequest
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SharedMemorySegFinalizeRequest` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::orc::tpctypes::SharedMemorySegFinalizeRequest { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">llvm/ExecutionEngine/Orc/Shared/TargetProcessControlTypes.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/remoteallocgroup">RemoteAllocGroup</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8722c220368ae6ec29f1659a9db656d">RAG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a291bd7c0717557dd244547b23c8c7c41">Addr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a285451feed03fc082fba2259ac6f1f2d">Size</a></td>
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


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Addr {#a291bd7c0717557dd244547b23c8c7c41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::tpctypes::SharedMemorySegFinalizeRequest::Addr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-c4c9d06010351644bf0ec9c5d491d476/#a52ac62a1372408f79dd7e686eeb99729">llvm::orc::shared::SPSSerializationTraits&lt; SPSSharedMemorySegFinalizeRequest, tpctypes::SharedMemorySegFinalizeRequest &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/sharedmemorymapper/#a6776668e9d06d4ffccc140a13cd25095">llvm::orc::SharedMemoryMapper::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-c4c9d06010351644bf0ec9c5d491d476/#a81036c9028f35e0288e852a8728a2819">llvm::orc::shared::SPSSerializationTraits&lt; SPSSharedMemorySegFinalizeRequest, tpctypes::SharedMemorySegFinalizeRequest &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-c4c9d06010351644bf0ec9c5d491d476/#a902bb30f743033e6dd8f526e98718e3f">llvm::orc::shared::SPSSerializationTraits&lt; SPSSharedMemorySegFinalizeRequest, tpctypes::SharedMemorySegFinalizeRequest &gt;::size</a>.</p>

</div>
</div>

### RAG {#af8722c220368ae6ec29f1659a9db656d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RemoteAllocGroup llvm::orc::tpctypes::SharedMemorySegFinalizeRequest::RAG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-c4c9d06010351644bf0ec9c5d491d476/#a52ac62a1372408f79dd7e686eeb99729">llvm::orc::shared::SPSSerializationTraits&lt; SPSSharedMemorySegFinalizeRequest, tpctypes::SharedMemorySegFinalizeRequest &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/sharedmemorymapper/#a6776668e9d06d4ffccc140a13cd25095">llvm::orc::SharedMemoryMapper::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-c4c9d06010351644bf0ec9c5d491d476/#a81036c9028f35e0288e852a8728a2819">llvm::orc::shared::SPSSerializationTraits&lt; SPSSharedMemorySegFinalizeRequest, tpctypes::SharedMemorySegFinalizeRequest &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-c4c9d06010351644bf0ec9c5d491d476/#a902bb30f743033e6dd8f526e98718e3f">llvm::orc::shared::SPSSerializationTraits&lt; SPSSharedMemorySegFinalizeRequest, tpctypes::SharedMemorySegFinalizeRequest &gt;::size</a>.</p>

</div>
</div>

### Size {#a285451feed03fc082fba2259ac6f1f2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::orc::tpctypes::SharedMemorySegFinalizeRequest::Size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-c4c9d06010351644bf0ec9c5d491d476/#a52ac62a1372408f79dd7e686eeb99729">llvm::orc::shared::SPSSerializationTraits&lt; SPSSharedMemorySegFinalizeRequest, tpctypes::SharedMemorySegFinalizeRequest &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/sharedmemorymapper/#a6776668e9d06d4ffccc140a13cd25095">llvm::orc::SharedMemoryMapper::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-c4c9d06010351644bf0ec9c5d491d476/#a81036c9028f35e0288e852a8728a2819">llvm::orc::shared::SPSSerializationTraits&lt; SPSSharedMemorySegFinalizeRequest, tpctypes::SharedMemorySegFinalizeRequest &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-c4c9d06010351644bf0ec9c5d491d476/#a902bb30f743033e6dd8f526e98718e3f">llvm::orc::shared::SPSSerializationTraits&lt; SPSSharedMemorySegFinalizeRequest, tpctypes::SharedMemorySegFinalizeRequest &gt;::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
