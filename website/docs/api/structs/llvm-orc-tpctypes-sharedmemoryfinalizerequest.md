---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/orc/tpctypes/sharedmemoryfinalizerequest
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SharedMemoryFinalizeRequest` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::orc::tpctypes::SharedMemoryFinalizeRequest { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">llvm/ExecutionEngine/Orc/Shared/TargetProcessControlTypes.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/sharedmemorysegfinalizerequest">SharedMemorySegFinalizeRequest</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cd77f9692f05fed6a1a9fa7b59da1e6">Segments</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac480f8342ad8500b7f9477ba74fd5ed2">Actions</a></td>
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


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Actions {#ac480f8342ad8500b7f9477ba74fd5ed2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">shared::AllocActions llvm::orc::tpctypes::SharedMemoryFinalizeRequest::Actions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-93eecca8a87e5b74adad0ef6c46c4f97/#a1224d736beea495933abab30e448ee0c">llvm::orc::shared::SPSSerializationTraits&lt; SPSSharedMemoryFinalizeRequest, tpctypes::SharedMemoryFinalizeRequest &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/executorsharedmemorymapperservice/#af7f72f04af2ffe1b66adfecb7f881b02">llvm::orc::rt_bootstrap::ExecutorSharedMemoryMapperService::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/sharedmemorymapper/#a6776668e9d06d4ffccc140a13cd25095">llvm::orc::SharedMemoryMapper::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-93eecca8a87e5b74adad0ef6c46c4f97/#a5d8a0b8f35fd38576ff9fed23dfc6383">llvm::orc::shared::SPSSerializationTraits&lt; SPSSharedMemoryFinalizeRequest, tpctypes::SharedMemoryFinalizeRequest &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-93eecca8a87e5b74adad0ef6c46c4f97/#a3eb848cbe7656cb6b44a95debad5d186">llvm::orc::shared::SPSSerializationTraits&lt; SPSSharedMemoryFinalizeRequest, tpctypes::SharedMemoryFinalizeRequest &gt;::size</a>.</p>

</div>
</div>

### Segments {#a1cd77f9692f05fed6a1a9fa7b59da1e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SharedMemorySegFinalizeRequest&gt; llvm::orc::tpctypes::SharedMemoryFinalizeRequest::Segments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-93eecca8a87e5b74adad0ef6c46c4f97/#a1224d736beea495933abab30e448ee0c">llvm::orc::shared::SPSSerializationTraits&lt; SPSSharedMemoryFinalizeRequest, tpctypes::SharedMemoryFinalizeRequest &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/executorsharedmemorymapperservice/#af7f72f04af2ffe1b66adfecb7f881b02">llvm::orc::rt_bootstrap::ExecutorSharedMemoryMapperService::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/sharedmemorymapper/#a6776668e9d06d4ffccc140a13cd25095">llvm::orc::SharedMemoryMapper::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-93eecca8a87e5b74adad0ef6c46c4f97/#a5d8a0b8f35fd38576ff9fed23dfc6383">llvm::orc::shared::SPSSerializationTraits&lt; SPSSharedMemoryFinalizeRequest, tpctypes::SharedMemoryFinalizeRequest &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-93eecca8a87e5b74adad0ef6c46c4f97/#a3eb848cbe7656cb6b44a95debad5d186">llvm::orc::shared::SPSSerializationTraits&lt; SPSSharedMemoryFinalizeRequest, tpctypes::SharedMemoryFinalizeRequest &gt;::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
