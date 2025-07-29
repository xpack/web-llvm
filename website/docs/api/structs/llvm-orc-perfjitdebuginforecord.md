---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/orc/perfjitdebuginforecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `PerfJITDebugInfoRecord` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::orc::PerfJITDebugInfoRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">llvm/ExecutionEngine/Orc/Shared/PerfSharedStructs.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/perfjitrecordprefix">PerfJITRecordPrefix</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac498cb043707773ee83671d5100c333f">Prefix</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab14c326c2bdd9f817a4c1a299611a021">CodeAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebugentry">PerfJITDebugEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0260b983323e6766fcebba356eb635f6">Entries</a></td>
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


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### CodeAddr {#ab14c326c2bdd9f817a4c1a299611a021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::orc::PerfJITDebugInfoRecord::CodeAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-f42140d4aead7dc95bdc42c5e21e5ae9/#a086b0fa2fe687fe229748477fd837494">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugInfoRecord, PerfJITDebugInfoRecord &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-f42140d4aead7dc95bdc42c5e21e5ae9/#a234bd88f0023041de67e361341effdaa">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugInfoRecord, PerfJITDebugInfoRecord &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-f42140d4aead7dc95bdc42c5e21e5ae9/#aa2787a038d86d14e4e8b5f6e90a9e98a">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugInfoRecord, PerfJITDebugInfoRecord &gt;::size</a>.</p>

</div>
</div>

### Entries {#a0260b983323e6766fcebba356eb635f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;PerfJITDebugEntry&gt; llvm::orc::PerfJITDebugInfoRecord::Entries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-f42140d4aead7dc95bdc42c5e21e5ae9/#a086b0fa2fe687fe229748477fd837494">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugInfoRecord, PerfJITDebugInfoRecord &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-f42140d4aead7dc95bdc42c5e21e5ae9/#a234bd88f0023041de67e361341effdaa">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugInfoRecord, PerfJITDebugInfoRecord &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-f42140d4aead7dc95bdc42c5e21e5ae9/#aa2787a038d86d14e4e8b5f6e90a9e98a">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugInfoRecord, PerfJITDebugInfoRecord &gt;::size</a>.</p>

</div>
</div>

### Prefix {#ac498cb043707773ee83671d5100c333f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PerfJITRecordPrefix llvm::orc::PerfJITDebugInfoRecord::Prefix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-f42140d4aead7dc95bdc42c5e21e5ae9/#a086b0fa2fe687fe229748477fd837494">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugInfoRecord, PerfJITDebugInfoRecord &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-f42140d4aead7dc95bdc42c5e21e5ae9/#a234bd88f0023041de67e361341effdaa">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugInfoRecord, PerfJITDebugInfoRecord &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-f42140d4aead7dc95bdc42c5e21e5ae9/#aa2787a038d86d14e4e8b5f6e90a9e98a">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugInfoRecord, PerfJITDebugInfoRecord &gt;::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
