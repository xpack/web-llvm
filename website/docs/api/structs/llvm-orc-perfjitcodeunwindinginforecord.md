---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/orc/perfjitcodeunwindinginforecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PerfJITCodeUnwindingInfoRecord` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::orc::PerfJITCodeUnwindingInfoRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">llvm/ExecutionEngine/Orc/Shared/PerfSharedStructs.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/perfjitrecordprefix">PerfJITRecordPrefix</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2e7b4e4f8057abfa680eaaece56a449">Prefix</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69b10c7db3db5c4f7f47073c7c35cebb">UnwindDataSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e04128c6b74df5fe44f83282fdf3490">EHFrameHdrSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab64378addaac9ffdaf9910c053f5f137">MappedSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0133bf2a299f142d600426ff21caa9d0">EHFrameHdrAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c89031e6d128234be20f5efd967b3b1">EHFrameHdr</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83a80a814ff78bed1468dfb2faf6f1c8">EHFrameAddr</a></td>
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


<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### EHFrameAddr {#a83a80a814ff78bed1468dfb2faf6f1c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::orc::PerfJITCodeUnwindingInfoRecord::EHFrameAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a886586ae910417523a871ba443281609">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a7cf65444b21f02f484980b26fece3366">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a5c07605bd39faf455d36a2188542a2d2">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::size</a>.</p>

</div>
</div>

### EHFrameHdr {#a8c89031e6d128234be20f5efd967b3b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::orc::PerfJITCodeUnwindingInfoRecord::EHFrameHdr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a886586ae910417523a871ba443281609">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a7cf65444b21f02f484980b26fece3366">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a5c07605bd39faf455d36a2188542a2d2">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::size</a>.</p>

</div>
</div>

### EHFrameHdrAddr {#a0133bf2a299f142d600426ff21caa9d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::orc::PerfJITCodeUnwindingInfoRecord::EHFrameHdrAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a886586ae910417523a871ba443281609">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a7cf65444b21f02f484980b26fece3366">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a5c07605bd39faf455d36a2188542a2d2">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::size</a>.</p>

</div>
</div>

### EHFrameHdrSize {#a5e04128c6b74df5fe44f83282fdf3490}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::orc::PerfJITCodeUnwindingInfoRecord::EHFrameHdrSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a886586ae910417523a871ba443281609">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a7cf65444b21f02f484980b26fece3366">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a5c07605bd39faf455d36a2188542a2d2">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::size</a>.</p>

</div>
</div>

### MappedSize {#ab64378addaac9ffdaf9910c053f5f137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::orc::PerfJITCodeUnwindingInfoRecord::MappedSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a886586ae910417523a871ba443281609">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a7cf65444b21f02f484980b26fece3366">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a5c07605bd39faf455d36a2188542a2d2">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::size</a>.</p>

</div>
</div>

### Prefix {#af2e7b4e4f8057abfa680eaaece56a449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PerfJITRecordPrefix llvm::orc::PerfJITCodeUnwindingInfoRecord::Prefix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a886586ae910417523a871ba443281609">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::deserialize</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#a55e3f6a5c003de75eabd889a24709857">anonymous{PerfSupportPlugin.cpp}::getRecords</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a7cf65444b21f02f484980b26fece3366">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a5c07605bd39faf455d36a2188542a2d2">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::size</a>.</p>

</div>
</div>

### UnwindDataSize {#a69b10c7db3db5c4f7f47073c7c35cebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::orc::PerfJITCodeUnwindingInfoRecord::UnwindDataSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a886586ae910417523a871ba443281609">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a7cf65444b21f02f484980b26fece3366">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba/#a5c07605bd39faf455d36a2188542a2d2">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord &gt;::size</a>.</p>

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
