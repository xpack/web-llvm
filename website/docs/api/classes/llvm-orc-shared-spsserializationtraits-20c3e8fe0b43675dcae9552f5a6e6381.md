---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SPSSerializationTraits` Class Template Reference



## Declaration

<div class="doxyDeclaration">
class llvm::orc::shared::SPSSerializationTraits&lt;SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">llvm/ExecutionEngine/Orc/Shared/PerfSharedStructs.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f0ee01dda5354f3678a4fb5ed9da832">size</a> (const PerfJITCodeLoadRecord &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18dd02579f665520cf92b298ec9086e8">deserialize</a> (SPSInputBuffer &amp;IB, PerfJITCodeLoadRecord &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2d1672f018589f82c973ead9113ee58">serialize</a> (SPSOutputBuffer &amp;OB, const PerfJITCodeLoadRecord &amp;Val)</td>
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


<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### deserialize() {#a18dd02579f665520cf92b298ec9086e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::deserialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsinputbuffer">SPSInputBuffer</a> &amp; IB, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord">PerfJITCodeLoadRecord</a> &amp; Val)</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#a47caf48d594ee7c314196e94c46a3225">llvm::orc::PerfJITCodeLoadRecord::CodeAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#a384e94016dbb531642dfb5962682741f">llvm::orc::PerfJITCodeLoadRecord::CodeIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#a3909c20c62236de51a854ba7ea264194">llvm::orc::PerfJITCodeLoadRecord::CodeSize</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#a4437835b452f8b54273b3d2ccdf1235f">llvm::orc::PerfJITCodeLoadRecord::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#ae608ce7e74fcd93ba02ab535c4e236c6">llvm::orc::PerfJITCodeLoadRecord::Pid</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#a0af2fab59e5a415b2e8495ca9c0d7004">llvm::orc::PerfJITCodeLoadRecord::Prefix</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#ad2bc157b61a363f425358e7c7060b2ab">llvm::orc::PerfJITCodeLoadRecord::Tid</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#a2cec5e78b4bc4fad68b775a9a203d9dc">llvm::orc::PerfJITCodeLoadRecord::Vma</a>.</p>

</div>
</div>

### serialize() {#ac2d1672f018589f82c973ead9113ee58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::serialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsoutputbuffer">SPSOutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord">PerfJITCodeLoadRecord</a> &amp; Val)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#a47caf48d594ee7c314196e94c46a3225">llvm::orc::PerfJITCodeLoadRecord::CodeAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#a384e94016dbb531642dfb5962682741f">llvm::orc::PerfJITCodeLoadRecord::CodeIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#a3909c20c62236de51a854ba7ea264194">llvm::orc::PerfJITCodeLoadRecord::CodeSize</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#a4437835b452f8b54273b3d2ccdf1235f">llvm::orc::PerfJITCodeLoadRecord::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#ae608ce7e74fcd93ba02ab535c4e236c6">llvm::orc::PerfJITCodeLoadRecord::Pid</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#a0af2fab59e5a415b2e8495ca9c0d7004">llvm::orc::PerfJITCodeLoadRecord::Prefix</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#ad2bc157b61a363f425358e7c7060b2ab">llvm::orc::PerfJITCodeLoadRecord::Tid</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#a2cec5e78b4bc4fad68b775a9a203d9dc">llvm::orc::PerfJITCodeLoadRecord::Vma</a>.</p>

</div>
</div>

### size() {#a6f0ee01dda5354f3678a4fb5ed9da832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::size (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord">PerfJITCodeLoadRecord</a> &amp; Val)</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#a47caf48d594ee7c314196e94c46a3225">llvm::orc::PerfJITCodeLoadRecord::CodeAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#a384e94016dbb531642dfb5962682741f">llvm::orc::PerfJITCodeLoadRecord::CodeIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#a3909c20c62236de51a854ba7ea264194">llvm::orc::PerfJITCodeLoadRecord::CodeSize</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#a4437835b452f8b54273b3d2ccdf1235f">llvm::orc::PerfJITCodeLoadRecord::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#ae608ce7e74fcd93ba02ab535c4e236c6">llvm::orc::PerfJITCodeLoadRecord::Pid</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#a0af2fab59e5a415b2e8495ca9c0d7004">llvm::orc::PerfJITCodeLoadRecord::Prefix</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#ad2bc157b61a363f425358e7c7060b2ab">llvm::orc::PerfJITCodeLoadRecord::Tid</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord/#a2cec5e78b4bc4fad68b775a9a203d9dc">llvm::orc::PerfJITCodeLoadRecord::Vma</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
