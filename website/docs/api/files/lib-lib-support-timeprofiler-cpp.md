---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/timeprofiler-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `TimeProfiler.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/timeprofiler-h">llvm/Support/TimeProfiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlfunctionalextras-h">llvm/ADT/STLFunctionalExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmap-h">llvm/ADT/StringMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/json-h">llvm/Support/JSON.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">llvm/Support/Process.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threading-h">llvm/Support/Threading.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;chrono&gt;
#include &lt;memory&gt;
#include &lt;mutex&gt;
#include &lt;string&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-timeprofiler-cpp-">anonymous{TimeProfiler.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-timeprofiler-cpp-/timetraceprofilerinstances">TimeTraceProfilerInstances</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/timetraceprofilerentry">TimeTraceProfilerEntry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an open or completed time section entry to be captured. <a href="/web-llvm/docs/api/structs/llvm/timetraceprofilerentry/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/inprogressentry">InProgressEntry</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/timetraceprofiler">TimeTraceProfiler</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-timeprofiler-cpp-/system-clock">system_clock</a></td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a793005af6ae802d5a2a2e8ceb4ac2135">LLVM_THREAD_LOCAL</a> <a href="/web-llvm/docs/api/structs/llvm/timetraceprofiler">TimeTraceProfiler</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a835e781b697ee76fc978f6c016effac2">TimeTraceProfilerInstance</a> = nullptr</td>
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

## Variables

### TimeTraceProfilerInstance {#a835e781b697ee76fc978f6c016effac2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_THREAD_LOCAL TimeTraceProfiler* TimeTraceProfilerInstance = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5989ded64c534859a29ac7591af344de">llvm::getTimeTraceProfilerInstance</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8fa9dbbdfaf6cc3897267308ba80e002">llvm::timeTraceAddInstantEvent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa741455d0c8f7b47561d088ac6ffcac7">llvm::timeTraceAsyncProfilerBegin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5ebe73a627d2152cbf696078fc13f21c">llvm::timeTraceProfilerBegin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a414836eaf11ad477825edb20030ec3a0">llvm::timeTraceProfilerBegin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afa36dba6382bf8735dc3b034d699c1ab">llvm::timeTraceProfilerBegin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac8745d28fad8ca10c8ccfa1d839bf0ce">llvm::timeTraceProfilerCleanup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d90de68ff5b5762833013e83e14bec5">llvm::timeTraceProfilerEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee4fdcfef50bf13cb5d9f8bd401bbeee">llvm::timeTraceProfilerEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6e4bd81e19cb403568eeb49955889e2b">llvm::timeTraceProfilerFinishThread</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a69b4f7af261bc6ace511b775a3cb41f6">llvm::timeTraceProfilerInitialize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad4b54dbf227646e844fa454931b02ff9">llvm::timeTraceProfilerWrite</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a95dd9937c9f80f95b741b20bb45e8a33">llvm::timeTraceProfilerWrite</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
