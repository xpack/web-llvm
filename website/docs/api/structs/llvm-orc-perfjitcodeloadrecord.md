---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/orc/perfjitcodeloadrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `PerfJITCodeLoadRecord` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::orc::PerfJITCodeLoadRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">llvm/ExecutionEngine/Orc/Shared/PerfSharedStructs.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/perfjitrecordprefix">PerfJITRecordPrefix</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0af2fab59e5a415b2e8495ca9c0d7004">Prefix</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae608ce7e74fcd93ba02ab535c4e236c6">Pid</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2bc157b61a363f425358e7c7060b2ab">Tid</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cec5e78b4bc4fad68b775a9a203d9dc">Vma</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47caf48d594ee7c314196e94c46a3225">CodeAddr</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3909c20c62236de51a854ba7ea264194">CodeSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a384e94016dbb531642dfb5962682741f">CodeIndex</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4437835b452f8b54273b3d2ccdf1235f">Name</a></td>
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


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### CodeAddr {#a47caf48d594ee7c314196e94c46a3225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::orc::PerfJITCodeLoadRecord::CodeAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#a18dd02579f665520cf92b298ec9086e8">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#ac2d1672f018589f82c973ead9113ee58">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#a6f0ee01dda5354f3678a4fb5ed9da832">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::size</a>.</p>

</div>
</div>

### CodeIndex {#a384e94016dbb531642dfb5962682741f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::orc::PerfJITCodeLoadRecord::CodeIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#a18dd02579f665520cf92b298ec9086e8">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#ac2d1672f018589f82c973ead9113ee58">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#a6f0ee01dda5354f3678a4fb5ed9da832">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::size</a>.</p>

</div>
</div>

### CodeSize {#a3909c20c62236de51a854ba7ea264194}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::orc::PerfJITCodeLoadRecord::CodeSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#a18dd02579f665520cf92b298ec9086e8">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#ac2d1672f018589f82c973ead9113ee58">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#a6f0ee01dda5354f3678a4fb5ed9da832">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::size</a>.</p>

</div>
</div>

### Name {#a4437835b452f8b54273b3d2ccdf1235f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::orc::PerfJITCodeLoadRecord::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#a18dd02579f665520cf92b298ec9086e8">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#ac2d1672f018589f82c973ead9113ee58">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#a6f0ee01dda5354f3678a4fb5ed9da832">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::size</a>.</p>

</div>
</div>

### Pid {#ae608ce7e74fcd93ba02ab535c4e236c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::orc::PerfJITCodeLoadRecord::Pid</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#a18dd02579f665520cf92b298ec9086e8">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#ac2d1672f018589f82c973ead9113ee58">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#a6f0ee01dda5354f3678a4fb5ed9da832">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::size</a>.</p>

</div>
</div>

### Prefix {#a0af2fab59e5a415b2e8495ca9c0d7004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PerfJITRecordPrefix llvm::orc::PerfJITCodeLoadRecord::Prefix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#a18dd02579f665520cf92b298ec9086e8">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#ac2d1672f018589f82c973ead9113ee58">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#a6f0ee01dda5354f3678a4fb5ed9da832">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::size</a>.</p>

</div>
</div>

### Tid {#ad2bc157b61a363f425358e7c7060b2ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::orc::PerfJITCodeLoadRecord::Tid</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#a18dd02579f665520cf92b298ec9086e8">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#ac2d1672f018589f82c973ead9113ee58">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#a6f0ee01dda5354f3678a4fb5ed9da832">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::size</a>.</p>

</div>
</div>

### Vma {#a2cec5e78b4bc4fad68b775a9a203d9dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::orc::PerfJITCodeLoadRecord::Vma</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#a18dd02579f665520cf92b298ec9086e8">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#ac2d1672f018589f82c973ead9113ee58">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381/#a6f0ee01dda5354f3678a4fb5ed9da832">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord &gt;::size</a>.</p>

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
