---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/inprogressentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `InProgressEntry` Struct



## Declaration

<div class="doxyDeclaration">
struct InProgressEntry { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d5b05a6b4de77767af37085bb3599ac">InProgressEntry</a> (TimePointType S, TimePointType E, std::string N, std::string Dt, TimeTraceEventType Et)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a8cb48dd55136330da7bfb42a2c1638">InProgressEntry</a> (TimePointType S, TimePointType E, std::string N, TimeTraceMetadata Mt, TimeTraceEventType Et)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/timetraceprofilerentry">TimeTraceProfilerEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85aff93b8ba123fb98113db10addb580">Event</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/timetraceprofilerentry">TimeTraceProfilerEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2213e9a1ec09cc0ce88371c865262633">InstantEvents</a></td>
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


<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InProgressEntry() {#a9d5b05a6b4de77767af37085bb3599ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InProgressEntry::InProgressEntry (<a href="/web-llvm/docs/api/namespaces/anonymous-timeprofiler-cpp-/#a9425994e75f5dcc5ab3062d317f1756f">TimePointType</a> S, <a href="/web-llvm/docs/api/namespaces/anonymous-timeprofiler-cpp-/#a9425994e75f5dcc5ab3062d317f1756f">TimePointType</a> E, std::string N, std::string Dt, <a href="/web-llvm/docs/api/namespaces/llvm/#aad35af14abc5748960dd055e5c04aa41">TimeTraceEventType</a> Et)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>References <a href="#a85aff93b8ba123fb98113db10addb580">Event</a>, <a href="#a2213e9a1ec09cc0ce88371c865262633">InstantEvents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### InProgressEntry() {#a2a8cb48dd55136330da7bfb42a2c1638}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InProgressEntry::InProgressEntry (<a href="/web-llvm/docs/api/namespaces/anonymous-timeprofiler-cpp-/#a9425994e75f5dcc5ab3062d317f1756f">TimePointType</a> S, <a href="/web-llvm/docs/api/namespaces/anonymous-timeprofiler-cpp-/#a9425994e75f5dcc5ab3062d317f1756f">TimePointType</a> E, std::string N, <a href="/web-llvm/docs/api/structs/llvm/timetracemetadata">TimeTraceMetadata</a> Mt, <a href="/web-llvm/docs/api/namespaces/llvm/#aad35af14abc5748960dd055e5c04aa41">TimeTraceEventType</a> Et)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>References <a href="#a85aff93b8ba123fb98113db10addb580">Event</a>, <a href="#a2213e9a1ec09cc0ce88371c865262633">InstantEvents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Event {#a85aff93b8ba123fb98113db10addb580}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TimeTraceProfilerEntry InProgressEntry::Event</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Referenced by <a href="#a9d5b05a6b4de77767af37085bb3599ac">InProgressEntry</a> and <a href="#a2a8cb48dd55136330da7bfb42a2c1638">InProgressEntry</a>.</p>

</div>
</div>

### InstantEvents {#a2213e9a1ec09cc0ce88371c865262633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;TimeTraceProfilerEntry&gt; InProgressEntry::InstantEvents</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Referenced by <a href="#a9d5b05a6b4de77767af37085bb3599ac">InProgressEntry</a> and <a href="#a2a8cb48dd55136330da7bfb42a2c1638">InProgressEntry</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
