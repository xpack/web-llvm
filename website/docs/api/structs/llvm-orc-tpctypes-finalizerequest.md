---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/orc/tpctypes/finalizerequest
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FinalizeRequest` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::orc::tpctypes::FinalizeRequest { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">llvm/ExecutionEngine/Orc/Shared/TargetProcessControlTypes.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/segfinalizerequest">SegFinalizeRequest</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7cb8653a6dc958e3aaf84d92fc08b69">Segments</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/#a6da0b5cb8e68a6cc791a183d9d38aae0">shared::AllocActions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa85c28825544c150ba63349d9c0cb7ce">Actions</a></td>
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


<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Actions {#aa85c28825544c150ba63349d9c0cb7ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">shared::AllocActions llvm::orc::tpctypes::FinalizeRequest::Actions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-8d961f7519b494fe7911b7456b62b5bc/#a88fb584a3a76ad2c298aec39a40bf2ec">llvm::orc::shared::SPSSerializationTraits&lt; SPSFinalizeRequest, tpctypes::FinalizeRequest &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericjitlinkmemorymanager/inflightalloc/#a00e3aa5ba4f76b3dc2a0c9bd4077ab11">llvm::orc::EPCGenericJITLinkMemoryManager::InFlightAlloc::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutormemorymanager/#a0c3a2679314fcbd29c249386447c8ba4">llvm::orc::rt_bootstrap::SimpleExecutorMemoryManager::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager/#a0db7d447f814afaee65a64c0419805dd">llvm::orc::EPCGenericRTDyldMemoryManager::finalizeMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-8d961f7519b494fe7911b7456b62b5bc/#a76c8094920cc7d11e8df6129e54ce253">llvm::orc::shared::SPSSerializationTraits&lt; SPSFinalizeRequest, tpctypes::FinalizeRequest &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-8d961f7519b494fe7911b7456b62b5bc/#a3449b5ad5ebfab04f26624577acf3e40">llvm::orc::shared::SPSSerializationTraits&lt; SPSFinalizeRequest, tpctypes::FinalizeRequest &gt;::size</a>.</p>

</div>
</div>

### Segments {#aa7cb8653a6dc958e3aaf84d92fc08b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SegFinalizeRequest&gt; llvm::orc::tpctypes::FinalizeRequest::Segments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-8d961f7519b494fe7911b7456b62b5bc/#a88fb584a3a76ad2c298aec39a40bf2ec">llvm::orc::shared::SPSSerializationTraits&lt; SPSFinalizeRequest, tpctypes::FinalizeRequest &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericjitlinkmemorymanager/inflightalloc/#a00e3aa5ba4f76b3dc2a0c9bd4077ab11">llvm::orc::EPCGenericJITLinkMemoryManager::InFlightAlloc::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutormemorymanager/#a0c3a2679314fcbd29c249386447c8ba4">llvm::orc::rt_bootstrap::SimpleExecutorMemoryManager::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/epcgenericrtdyldmemorymanager/#a0db7d447f814afaee65a64c0419805dd">llvm::orc::EPCGenericRTDyldMemoryManager::finalizeMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-8d961f7519b494fe7911b7456b62b5bc/#a76c8094920cc7d11e8df6129e54ce253">llvm::orc::shared::SPSSerializationTraits&lt; SPSFinalizeRequest, tpctypes::FinalizeRequest &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-8d961f7519b494fe7911b7456b62b5bc/#a3449b5ad5ebfab04f26624577acf3e40">llvm::orc::shared::SPSSerializationTraits&lt; SPSFinalizeRequest, tpctypes::FinalizeRequest &gt;::size</a>.</p>

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
