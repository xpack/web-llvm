---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/orc/memorymapper/allocinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `AllocInfo` Struct

<p>Represents a single allocation containing multiple segments and initialization and deinitialization actions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::orc::MemoryMapper::AllocInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">llvm/ExecutionEngine/Orc/MemoryMapper.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ae25e2221d662f2fbffc49d0b172b3a">MappingBase</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/memorymapper/allocinfo/seginfo">SegInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b6dcea60d496fc8de6d65188804b995">Segments</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/#a6da0b5cb8e68a6cc791a183d9d38aae0">shared::AllocActions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa83c8c10a9eb18cd233eed2ecf12ca71">Actions</a></td>
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

## Description {#details}

<p>Represents a single allocation containing multiple segments and initialization and deinitialization actions.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Actions {#aa83c8c10a9eb18cd233eed2ecf12ca71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">shared::AllocActions llvm::orc::MemoryMapper::AllocInfo::Actions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/mapperjitlinkmemorymanager/inflightalloc/#a5a96a71e0a19bc870ccc43952e2b74e1">llvm::orc::MapperJITLinkMemoryManager::InFlightAlloc::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemorymapper/#a492e4d6b2bf660e7c499e22f85b72440">llvm::orc::InProcessMemoryMapper::initialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/sharedmemorymapper/#a6776668e9d06d4ffccc140a13cd25095">llvm::orc::SharedMemoryMapper::initialize</a>.</p>

</div>
</div>

### MappingBase {#a8ae25e2221d662f2fbffc49d0b172b3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::MemoryMapper::AllocInfo::MappingBase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/mapperjitlinkmemorymanager/inflightalloc/#a5a96a71e0a19bc870ccc43952e2b74e1">llvm::orc::MapperJITLinkMemoryManager::InFlightAlloc::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemorymapper/#a492e4d6b2bf660e7c499e22f85b72440">llvm::orc::InProcessMemoryMapper::initialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/sharedmemorymapper/#a6776668e9d06d4ffccc140a13cd25095">llvm::orc::SharedMemoryMapper::initialize</a>.</p>

</div>
</div>

### Segments {#a6b6dcea60d496fc8de6d65188804b995}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SegInfo&gt; llvm::orc::MemoryMapper::AllocInfo::Segments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/mapperjitlinkmemorymanager/inflightalloc/#a5a96a71e0a19bc870ccc43952e2b74e1">llvm::orc::MapperJITLinkMemoryManager::InFlightAlloc::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemorymapper/#a492e4d6b2bf660e7c499e22f85b72440">llvm::orc::InProcessMemoryMapper::initialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/sharedmemorymapper/#a6776668e9d06d4ffccc140a13cd25095">llvm::orc::SharedMemoryMapper::initialize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/memorymapper-h">MemoryMapper.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
