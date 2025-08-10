---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/shared/spsserializationtraits-f42140d4aead7dc95bdc42c5e21e5ae9
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SPSSerializationTraits` Class Template



## Declaration

<div class="doxyDeclaration">
class llvm::orc::shared::SPSSerializationTraits&lt;SPSPerfJITDebugInfoRecord, PerfJITDebugInfoRecord&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">llvm/ExecutionEngine/Orc/Shared/PerfSharedStructs.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2787a038d86d14e4e8b5f6e90a9e98a">size</a> (const PerfJITDebugInfoRecord &amp;Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a086b0fa2fe687fe229748477fd837494">deserialize</a> (SPSInputBuffer &amp;IB, PerfJITDebugInfoRecord &amp;Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a234bd88f0023041de67e361341effdaa">serialize</a> (SPSOutputBuffer &amp;OB, const PerfJITDebugInfoRecord &amp;Val)</td>
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


<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### deserialize() {#a086b0fa2fe687fe229748477fd837494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugInfoRecord, PerfJITDebugInfoRecord &gt;::deserialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsinputbuffer">SPSInputBuffer</a> &amp; IB, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebuginforecord">PerfJITDebugInfoRecord</a> &amp; Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebuginforecord/#ab14c326c2bdd9f817a4c1a299611a021">llvm::orc::PerfJITDebugInfoRecord::CodeAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebuginforecord/#a0260b983323e6766fcebba356eb635f6">llvm::orc::PerfJITDebugInfoRecord::Entries</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebuginforecord/#ac498cb043707773ee83671d5100c333f">llvm::orc::PerfJITDebugInfoRecord::Prefix</a>.</p>

</div>
</div>

### serialize() {#a234bd88f0023041de67e361341effdaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugInfoRecord, PerfJITDebugInfoRecord &gt;::serialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsoutputbuffer">SPSOutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebuginforecord">PerfJITDebugInfoRecord</a> &amp; Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebuginforecord/#ab14c326c2bdd9f817a4c1a299611a021">llvm::orc::PerfJITDebugInfoRecord::CodeAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebuginforecord/#a0260b983323e6766fcebba356eb635f6">llvm::orc::PerfJITDebugInfoRecord::Entries</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebuginforecord/#ac498cb043707773ee83671d5100c333f">llvm::orc::PerfJITDebugInfoRecord::Prefix</a>.</p>

</div>
</div>

### size() {#aa2787a038d86d14e4e8b5f6e90a9e98a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugInfoRecord, PerfJITDebugInfoRecord &gt;::size (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebuginforecord">PerfJITDebugInfoRecord</a> &amp; Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebuginforecord/#ab14c326c2bdd9f817a4c1a299611a021">llvm::orc::PerfJITDebugInfoRecord::CodeAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebuginforecord/#a0260b983323e6766fcebba356eb635f6">llvm::orc::PerfJITDebugInfoRecord::Entries</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebuginforecord/#ac498cb043707773ee83671d5100c333f">llvm::orc::PerfJITDebugInfoRecord::Prefix</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
