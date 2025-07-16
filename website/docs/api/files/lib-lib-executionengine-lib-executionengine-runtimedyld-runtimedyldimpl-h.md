---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `RuntimeDyldImpl.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmap-h">llvm/ADT/StringMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/symbolstringpool-h">llvm/ExecutionEngine/Orc/SymbolStringPool.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/rtdyldmemorymanager-h">llvm/ExecutionEngine/RTDyldMemoryManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyld-h">llvm/ExecutionEngine/RuntimeDyld.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/runtimedyldchecker-h">llvm/ExecutionEngine/RuntimeDyldChecker.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">llvm/Object/ObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mutex-h">llvm/Support/Mutex.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/swapbyteorder-h">llvm/Support/SwapByteOrder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/host-h">llvm/TargetParser/Host.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include &lt;deque&gt;
#include &lt;map&gt;
#include &lt;system_error&gt;
#include &lt;unordered_map&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sectionentry">SectionEntry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sectionentry">SectionEntry</a> - represents a section emitted into memory by the dynamic linker. <a href="/web-llvm/docs/api/classes/llvm/sectionentry/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/relocationentry">RelocationEntry</a> - used to represent relocations internally in the dynamic linker. <a href="/web-llvm/docs/api/classes/llvm/relocationentry/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/relocationentry/sectionpair">SectionPair</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/relocationvalueref">RelocationValueRef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/symboltableentry">SymbolTableEntry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Symbol info for <a href="/web-llvm/docs/api/classes/llvm/runtimedyld">RuntimeDyld</a>. <a href="/web-llvm/docs/api/classes/llvm/symboltableentry/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl">RuntimeDyldImpl</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4c1923d575768fb7d3dc8e15f49337c">UNIMPLEMENTED_RELOC</a>(RelType)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ec5b0d10052cef17027844769e60240">RTDYLD_INVALID_SECTION_ID</a>&nbsp;&nbsp;&nbsp;((<a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a8ad6e355243eab1c1a3993f9bda8b2d1">RuntimeDyldImpl::SID</a>)(-1))</td>
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


<div class="doxySectionDef">

## Macro Definitions

### RTDYLD\_INVALID\_SECTION\_ID {#a0ec5b0d10052cef17027844769e60240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RTDYLD_INVALID_SECTION_ID&nbsp;&nbsp;&nbsp;((<a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a8ad6e355243eab1c1a3993f9bda8b2d1">RuntimeDyldImpl::SID</a>)(-1))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/runtimedyldmacho/ehframerelatedsections/#add16154c01672fa0e76b4dbbd4c7791d">llvm::RuntimeDyldMachO::EHFrameRelatedSections::EHFrameRelatedSections</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachocrtpbase/#afdfe2cf5151ed6e7266417d9f1db5f80">llvm::RuntimeDyldMachOCRTPBase&lt; Impl &gt;::finalizeLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachocrtpbase/#a320dd78d770da97700997cca111f7946">llvm::RuntimeDyldMachOCRTPBase&lt; Impl &gt;::registerEHFrames</a>.</p>

</div>
</div>

### UNIMPLEMENTED\_RELOC {#af4c1923d575768fb7d3dc8e15f49337c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define UNIMPLEMENTED_RELOC(RelType)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case RelType: \
    return make_error&lt;<a href="/web-llvm/docs/api/classes/llvm/runtimedylderror">RuntimeDyldError</a>&gt;("Unimplemented relocation: " #RelType)
</div>
</dd>
</dl>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldimpl-h">RuntimeDyldImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#ad0cc2b7a34912033f88c7169756683cb">llvm::RuntimeDyldMachOARM::processRelocationRef</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoi386/#a5bd3ae889a8d52356bd6b32e45c7aa6c">llvm::RuntimeDyldMachOI386::processRelocationRef</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachox86-64/#a59ad91c5ccf9ed8867eab9cc5424b151">llvm::RuntimeDyldMachOX86_64::processRelocationRef</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
