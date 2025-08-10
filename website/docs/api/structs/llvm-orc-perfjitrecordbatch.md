---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/orc/perfjitrecordbatch
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `PerfJITRecordBatch` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::orc::PerfJITRecordBatch { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">llvm/ExecutionEngine/Orc/Shared/PerfSharedStructs.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebuginforecord">PerfJITDebugInfoRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55770d4a7181cf614f005f4fb62a2e62">DebugInfoRecords</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord">PerfJITCodeLoadRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed5c2092464488662d58242c310db140">CodeLoadRecords</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord">PerfJITCodeUnwindingInfoRecord</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cff396945130f0d41bcca7bd88bc513">UnwindingRecord</a></td>
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


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### CodeLoadRecords {#aed5c2092464488662d58242c310db140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;PerfJITCodeLoadRecord&gt; llvm::orc::PerfJITRecordBatch::CodeLoadRecords</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-46145372e1312ab0db588d8e712df78b/#ad6dd87bd98be97ed9aeb0699a44dd6ed">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITRecordBatch, PerfJITRecordBatch &gt;::deserialize</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#a55e3f6a5c003de75eabd889a24709857">anonymous{PerfSupportPlugin.cpp}::getRecords</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-46145372e1312ab0db588d8e712df78b/#a3bf0a7c0d1e4e0e0e539cf86e110350a">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITRecordBatch, PerfJITRecordBatch &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-46145372e1312ab0db588d8e712df78b/#acc65c5b52f714b7dd23119b591adc8e0">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITRecordBatch, PerfJITRecordBatch &gt;::size</a>.</p>

</div>
</div>

### DebugInfoRecords {#a55770d4a7181cf614f005f4fb62a2e62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;PerfJITDebugInfoRecord&gt; llvm::orc::PerfJITRecordBatch::DebugInfoRecords</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-46145372e1312ab0db588d8e712df78b/#ad6dd87bd98be97ed9aeb0699a44dd6ed">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITRecordBatch, PerfJITRecordBatch &gt;::deserialize</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#a55e3f6a5c003de75eabd889a24709857">anonymous{PerfSupportPlugin.cpp}::getRecords</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-46145372e1312ab0db588d8e712df78b/#a3bf0a7c0d1e4e0e0e539cf86e110350a">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITRecordBatch, PerfJITRecordBatch &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-46145372e1312ab0db588d8e712df78b/#acc65c5b52f714b7dd23119b591adc8e0">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITRecordBatch, PerfJITRecordBatch &gt;::size</a>.</p>

</div>
</div>

### UnwindingRecord {#a8cff396945130f0d41bcca7bd88bc513}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PerfJITCodeUnwindingInfoRecord llvm::orc::PerfJITRecordBatch::UnwindingRecord</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-46145372e1312ab0db588d8e712df78b/#ad6dd87bd98be97ed9aeb0699a44dd6ed">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITRecordBatch, PerfJITRecordBatch &gt;::deserialize</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#a55e3f6a5c003de75eabd889a24709857">anonymous{PerfSupportPlugin.cpp}::getRecords</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-46145372e1312ab0db588d8e712df78b/#a3bf0a7c0d1e4e0e0e539cf86e110350a">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITRecordBatch, PerfJITRecordBatch &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-46145372e1312ab0db588d8e712df78b/#acc65c5b52f714b7dd23119b591adc8e0">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITRecordBatch, PerfJITRecordBatch &gt;::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
