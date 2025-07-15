---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba
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
class llvm::orc::shared::SPSSerializationTraits&lt;SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">llvm/ExecutionEngine/Orc/Shared/PerfSharedStructs.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c07605bd39faf455d36a2188542a2d2">size</a> (const PerfJITCodeUnwindingInfoRecord &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a886586ae910417523a871ba443281609">deserialize</a> (SPSInputBuffer &amp;IB, PerfJITCodeUnwindingInfoRecord &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cf65444b21f02f484980b26fece3366">serialize</a> (SPSOutputBuffer &amp;OB, const PerfJITCodeUnwindingInfoRecord &amp;Val)</td>
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


<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### deserialize() {#a886586ae910417523a871ba443281609}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::deserialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsinputbuffer">SPSInputBuffer</a> &amp; IB, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord">PerfJITCodeUnwindingInfoRecord</a> &amp; Val)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#a83a80a814ff78bed1468dfb2faf6f1c8">llvm::orc::PerfJITCodeUnwindingInfoRecord::EHFrameAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#a8c89031e6d128234be20f5efd967b3b1">llvm::orc::PerfJITCodeUnwindingInfoRecord::EHFrameHdr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#a0133bf2a299f142d600426ff21caa9d0">llvm::orc::PerfJITCodeUnwindingInfoRecord::EHFrameHdrAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#a5e04128c6b74df5fe44f83282fdf3490">llvm::orc::PerfJITCodeUnwindingInfoRecord::EHFrameHdrSize</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#ab64378addaac9ffdaf9910c053f5f137">llvm::orc::PerfJITCodeUnwindingInfoRecord::MappedSize</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#af2e7b4e4f8057abfa680eaaece56a449">llvm::orc::PerfJITCodeUnwindingInfoRecord::Prefix</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#a69b10c7db3db5c4f7f47073c7c35cebb">llvm::orc::PerfJITCodeUnwindingInfoRecord::UnwindDataSize</a>.</p>

</div>
</div>

### serialize() {#a7cf65444b21f02f484980b26fece3366}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::serialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsoutputbuffer">SPSOutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord">PerfJITCodeUnwindingInfoRecord</a> &amp; Val)</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#a83a80a814ff78bed1468dfb2faf6f1c8">llvm::orc::PerfJITCodeUnwindingInfoRecord::EHFrameAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#a8c89031e6d128234be20f5efd967b3b1">llvm::orc::PerfJITCodeUnwindingInfoRecord::EHFrameHdr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#a0133bf2a299f142d600426ff21caa9d0">llvm::orc::PerfJITCodeUnwindingInfoRecord::EHFrameHdrAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#a5e04128c6b74df5fe44f83282fdf3490">llvm::orc::PerfJITCodeUnwindingInfoRecord::EHFrameHdrSize</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#ab64378addaac9ffdaf9910c053f5f137">llvm::orc::PerfJITCodeUnwindingInfoRecord::MappedSize</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#af2e7b4e4f8057abfa680eaaece56a449">llvm::orc::PerfJITCodeUnwindingInfoRecord::Prefix</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#a69b10c7db3db5c4f7f47073c7c35cebb">llvm::orc::PerfJITCodeUnwindingInfoRecord::UnwindDataSize</a>.</p>

</div>
</div>

### size() {#a5c07605bd39faf455d36a2188542a2d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::size (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord">PerfJITCodeUnwindingInfoRecord</a> &amp; Val)</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#a83a80a814ff78bed1468dfb2faf6f1c8">llvm::orc::PerfJITCodeUnwindingInfoRecord::EHFrameAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#a8c89031e6d128234be20f5efd967b3b1">llvm::orc::PerfJITCodeUnwindingInfoRecord::EHFrameHdr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#a0133bf2a299f142d600426ff21caa9d0">llvm::orc::PerfJITCodeUnwindingInfoRecord::EHFrameHdrAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#a5e04128c6b74df5fe44f83282fdf3490">llvm::orc::PerfJITCodeUnwindingInfoRecord::EHFrameHdrSize</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#ab64378addaac9ffdaf9910c053f5f137">llvm::orc::PerfJITCodeUnwindingInfoRecord::MappedSize</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#af2e7b4e4f8057abfa680eaaece56a449">llvm::orc::PerfJITCodeUnwindingInfoRecord::Prefix</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#a69b10c7db3db5c4f7f47073c7c35cebb">llvm::orc::PerfJITCodeUnwindingInfoRecord::UnwindDataSize</a>.</p>

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
