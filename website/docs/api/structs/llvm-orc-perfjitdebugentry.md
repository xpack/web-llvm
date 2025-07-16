---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/orc/perfjitdebugentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PerfJITDebugEntry` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::orc::PerfJITDebugEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">llvm/ExecutionEngine/Orc/Shared/PerfSharedStructs.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96fbd75b3f55dda4a483318c010d5582">Addr</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdf9cf60ed88f09b1f1a605e3adb87be">Lineno</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad160a48a1e0c89e3d4b75f493a3a2481">Discrim</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad177378fc798a380609c94922326dd37">Name</a></td>
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


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Addr {#a96fbd75b3f55dda4a483318c010d5582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::orc::PerfJITDebugEntry::Addr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-bf8924ae7d79c09d623eda7a9bca91c9/#a6c07c9caeade685e44ce4b07bd6a1b01">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugEntry, PerfJITDebugEntry &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-bf8924ae7d79c09d623eda7a9bca91c9/#afa34f45a8b857a8a7247dbd966a832f0">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugEntry, PerfJITDebugEntry &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-bf8924ae7d79c09d623eda7a9bca91c9/#a1f6660b662ca55807e022cf061f21c2f">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugEntry, PerfJITDebugEntry &gt;::size</a>.</p>

</div>
</div>

### Discrim {#ad160a48a1e0c89e3d4b75f493a3a2481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::orc::PerfJITDebugEntry::Discrim</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-bf8924ae7d79c09d623eda7a9bca91c9/#a6c07c9caeade685e44ce4b07bd6a1b01">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugEntry, PerfJITDebugEntry &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-bf8924ae7d79c09d623eda7a9bca91c9/#afa34f45a8b857a8a7247dbd966a832f0">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugEntry, PerfJITDebugEntry &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-bf8924ae7d79c09d623eda7a9bca91c9/#a1f6660b662ca55807e022cf061f21c2f">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugEntry, PerfJITDebugEntry &gt;::size</a>.</p>

</div>
</div>

### Lineno {#afdf9cf60ed88f09b1f1a605e3adb87be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::orc::PerfJITDebugEntry::Lineno</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-bf8924ae7d79c09d623eda7a9bca91c9/#a6c07c9caeade685e44ce4b07bd6a1b01">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugEntry, PerfJITDebugEntry &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-bf8924ae7d79c09d623eda7a9bca91c9/#afa34f45a8b857a8a7247dbd966a832f0">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugEntry, PerfJITDebugEntry &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-bf8924ae7d79c09d623eda7a9bca91c9/#a1f6660b662ca55807e022cf061f21c2f">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugEntry, PerfJITDebugEntry &gt;::size</a>.</p>

</div>
</div>

### Name {#ad177378fc798a380609c94922326dd37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::orc::PerfJITDebugEntry::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-bf8924ae7d79c09d623eda7a9bca91c9/#a6c07c9caeade685e44ce4b07bd6a1b01">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugEntry, PerfJITDebugEntry &gt;::deserialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-bf8924ae7d79c09d623eda7a9bca91c9/#afa34f45a8b857a8a7247dbd966a832f0">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugEntry, PerfJITDebugEntry &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-bf8924ae7d79c09d623eda7a9bca91c9/#a1f6660b662ca55807e022cf061f21c2f">llvm::orc::shared::SPSSerializationTraits&lt; SPSPerfJITDebugEntry, PerfJITDebugEntry &gt;::size</a>.</p>

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
