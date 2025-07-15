---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/orc/perfjitrecordprefix
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PerfJITRecordPrefix` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::orc::PerfJITRecordPrefix { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">llvm/ExecutionEngine/Orc/Shared/PerfSharedStructs.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#a58aef37a030d9c1e56eaa6ee5bef47a4">PerfJITRecordType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f4f47fe3fd91943aa4640c078b87182">Id</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04ad3002e4d48b2dfdb8c830cce5d0fb">TotalSize</a></td>
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


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Id {#a2f4f47fe3fd91943aa4640c078b87182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PerfJITRecordType llvm::orc::PerfJITRecordPrefix::Id</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-b23e5a852f3aefd3a94c5f626e3e85e7/#a0bda928ea2df280e15aa108024d7d495">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITRecordPrefix, PerfJITRecordPrefix &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-b23e5a852f3aefd3a94c5f626e3e85e7/#a864160b113454da63520f83e6fb74310">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITRecordPrefix, PerfJITRecordPrefix &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-b23e5a852f3aefd3a94c5f626e3e85e7/#a4b30dcdac0a0b023060320ba7c97715a">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITRecordPrefix, PerfJITRecordPrefix &gt;::size</a>.</p>

</div>
</div>

### TotalSize {#a04ad3002e4d48b2dfdb8c830cce5d0fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::orc::PerfJITRecordPrefix::TotalSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-b23e5a852f3aefd3a94c5f626e3e85e7/#a0bda928ea2df280e15aa108024d7d495">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITRecordPrefix, PerfJITRecordPrefix &gt;::deserialize</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#a55e3f6a5c003de75eabd889a24709857">anonymous{PerfSupportPlugin.cpp}::getRecords</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-b23e5a852f3aefd3a94c5f626e3e85e7/#a864160b113454da63520f83e6fb74310">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITRecordPrefix, PerfJITRecordPrefix &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-b23e5a852f3aefd3a94c5f626e3e85e7/#a4b30dcdac0a0b023060320ba7c97715a">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITRecordPrefix, PerfJITRecordPrefix &gt;::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
