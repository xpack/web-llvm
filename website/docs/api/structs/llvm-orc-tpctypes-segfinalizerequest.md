---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/orc/tpctypes/segfinalizerequest
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SegFinalizeRequest` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::orc::tpctypes::SegFinalizeRequest { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">llvm/ExecutionEngine/Orc/Shared/TargetProcessControlTypes.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/remoteallocgroup">RemoteAllocGroup</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc86666c4219c9f050f3c30106f4a4e3">RAG</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63a7ca147b982a7206f3ca9b18923b94">Addr</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88bf55a6e833d2d04aca01c3e5e01615">Size</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20543fdb30035570b044c28008d9c42e">Content</a></td>
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


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Addr {#a63a7ca147b982a7206f3ca9b18923b94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::tpctypes::SegFinalizeRequest::Addr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-784a1bef17190e6ab41c561ff2b7a7b9/#a9f26566a1c21b25aa74e802028257708">llvm::orc::shared::SPSSerializationTraits&lt; SPSSegFinalizeRequest, tpctypes::SegFinalizeRequest &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-784a1bef17190e6ab41c561ff2b7a7b9/#aee5f3d5808154c2cd798394a195e5b73">llvm::orc::shared::SPSSerializationTraits&lt; SPSSegFinalizeRequest, tpctypes::SegFinalizeRequest &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-784a1bef17190e6ab41c561ff2b7a7b9/#a9114ae5be7ffa02b4566dc6e5109d44c">llvm::orc::shared::SPSSerializationTraits&lt; SPSSegFinalizeRequest, tpctypes::SegFinalizeRequest &gt;::size</a>.</p>

</div>
</div>

### Content {#a20543fdb30035570b044c28008d9c42e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;char&gt; llvm::orc::tpctypes::SegFinalizeRequest::Content</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-784a1bef17190e6ab41c561ff2b7a7b9/#a9f26566a1c21b25aa74e802028257708">llvm::orc::shared::SPSSerializationTraits&lt; SPSSegFinalizeRequest, tpctypes::SegFinalizeRequest &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-784a1bef17190e6ab41c561ff2b7a7b9/#aee5f3d5808154c2cd798394a195e5b73">llvm::orc::shared::SPSSerializationTraits&lt; SPSSegFinalizeRequest, tpctypes::SegFinalizeRequest &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-784a1bef17190e6ab41c561ff2b7a7b9/#a9114ae5be7ffa02b4566dc6e5109d44c">llvm::orc::shared::SPSSerializationTraits&lt; SPSSegFinalizeRequest, tpctypes::SegFinalizeRequest &gt;::size</a>.</p>

</div>
</div>

### RAG {#abc86666c4219c9f050f3c30106f4a4e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RemoteAllocGroup llvm::orc::tpctypes::SegFinalizeRequest::RAG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-784a1bef17190e6ab41c561ff2b7a7b9/#a9f26566a1c21b25aa74e802028257708">llvm::orc::shared::SPSSerializationTraits&lt; SPSSegFinalizeRequest, tpctypes::SegFinalizeRequest &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-784a1bef17190e6ab41c561ff2b7a7b9/#aee5f3d5808154c2cd798394a195e5b73">llvm::orc::shared::SPSSerializationTraits&lt; SPSSegFinalizeRequest, tpctypes::SegFinalizeRequest &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-784a1bef17190e6ab41c561ff2b7a7b9/#a9114ae5be7ffa02b4566dc6e5109d44c">llvm::orc::shared::SPSSerializationTraits&lt; SPSSegFinalizeRequest, tpctypes::SegFinalizeRequest &gt;::size</a>.</p>

</div>
</div>

### Size {#a88bf55a6e833d2d04aca01c3e5e01615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::orc::tpctypes::SegFinalizeRequest::Size</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-784a1bef17190e6ab41c561ff2b7a7b9/#a9f26566a1c21b25aa74e802028257708">llvm::orc::shared::SPSSerializationTraits&lt; SPSSegFinalizeRequest, tpctypes::SegFinalizeRequest &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-784a1bef17190e6ab41c561ff2b7a7b9/#aee5f3d5808154c2cd798394a195e5b73">llvm::orc::shared::SPSSerializationTraits&lt; SPSSegFinalizeRequest, tpctypes::SegFinalizeRequest &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-784a1bef17190e6ab41c561ff2b7a7b9/#a9114ae5be7ffa02b4566dc6e5109d44c">llvm::orc::shared::SPSSerializationTraits&lt; SPSSegFinalizeRequest, tpctypes::SegFinalizeRequest &gt;::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
