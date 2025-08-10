---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/timetraceprofilerentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `TimeTraceProfilerEntry` Struct

<p>Represents an open or completed time section entry to be captured. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::TimeTraceProfilerEntry { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cac605ae10bf41e0287bf9092d5b737">TimeTraceProfilerEntry</a> (TimePointType &amp;&amp;S, TimePointType &amp;&amp;E, std::string &amp;&amp;N, std::string &amp;&amp;Dt, TimeTraceEventType Et)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6edb393ad901a281393d41f46d6c9524">TimeTraceProfilerEntry</a> (TimePointType &amp;&amp;S, TimePointType &amp;&amp;E, std::string &amp;&amp;N, TimeTraceMetadata &amp;&amp;Mt, TimeTraceEventType Et)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">ClockType::rep</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace6db8639f337a01e7b985bbbb90d9e2">getFlameGraphStartUs</a> (TimePointType StartTime) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ClockType::rep</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a598e967448a332adc4eeb3dd6addf060">getFlameGraphDurUs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TimePointType</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b12d592c97ddc5081fd39aa667ec491">Start</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">TimePointType</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac671cbaa6eb4a2eb7cf95c59e315d06c">End</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ffb288c26cfa812542aa2fdcf15e6c3">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/timetracemetadata">TimeTraceMetadata</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad155cf504f48ea1c33a8580f4cc6f401">Metadata</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad35af14abc5748960dd055e5c04aa41">TimeTraceEventType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7006ae5f178ee7820bccd9ce47a493e4">EventType</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#aad35af14abc5748960dd055e5c04aa41a119b8a171a57a705aba9b074d88db9b1">TimeTraceEventType::CompleteEvent</a></td>
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

<p>Represents an open or completed time section entry to be captured.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TimeTraceProfilerEntry() {#a1cac605ae10bf41e0287bf9092d5b737}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TimeTraceProfilerEntry::TimeTraceProfilerEntry (TimePointType &amp;&amp; S, TimePointType &amp;&amp; E, std::string &amp;&amp; N, std::string &amp;&amp; Dt, <a href="/web-llvm/docs/api/namespaces/llvm/#aad35af14abc5748960dd055e5c04aa41">TimeTraceEventType</a> Et)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>References <a href="#ac671cbaa6eb4a2eb7cf95c59e315d06c">End</a>, <a href="#a7006ae5f178ee7820bccd9ce47a493e4">EventType</a>, <a href="#ad155cf504f48ea1c33a8580f4cc6f401">Metadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a5ffb288c26cfa812542aa2fdcf15e6c3">Name</a> and <a href="#a0b12d592c97ddc5081fd39aa667ec491">Start</a>.</p>

</div>
</div>

### TimeTraceProfilerEntry() {#a6edb393ad901a281393d41f46d6c9524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TimeTraceProfilerEntry::TimeTraceProfilerEntry (TimePointType &amp;&amp; S, TimePointType &amp;&amp; E, std::string &amp;&amp; N, <a href="/web-llvm/docs/api/structs/llvm/timetracemetadata">TimeTraceMetadata</a> &amp;&amp; Mt, <a href="/web-llvm/docs/api/namespaces/llvm/#aad35af14abc5748960dd055e5c04aa41">TimeTraceEventType</a> Et)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>References <a href="#ac671cbaa6eb4a2eb7cf95c59e315d06c">End</a>, <a href="#a7006ae5f178ee7820bccd9ce47a493e4">EventType</a>, <a href="#ad155cf504f48ea1c33a8580f4cc6f401">Metadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a5ffb288c26cfa812542aa2fdcf15e6c3">Name</a> and <a href="#a0b12d592c97ddc5081fd39aa667ec491">Start</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFlameGraphDurUs() {#a598e967448a332adc4eeb3dd6addf060}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClockType::rep llvm::TimeTraceProfilerEntry::getFlameGraphDurUs ()</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>References <a href="#ac671cbaa6eb4a2eb7cf95c59e315d06c">End</a> and <a href="#a0b12d592c97ddc5081fd39aa667ec491">Start</a>.</p>

</div>
</div>

### getFlameGraphStartUs() {#ace6db8639f337a01e7b985bbbb90d9e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClockType::rep llvm::TimeTraceProfilerEntry::getFlameGraphStartUs (TimePointType StartTime)</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Reference <a href="#a0b12d592c97ddc5081fd39aa667ec491">Start</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### End {#ac671cbaa6eb4a2eb7cf95c59e315d06c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TimePointType llvm::TimeTraceProfilerEntry::End</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Referenced by <a href="#a598e967448a332adc4eeb3dd6addf060">getFlameGraphDurUs</a>, <a href="#a1cac605ae10bf41e0287bf9092d5b737">TimeTraceProfilerEntry</a> and <a href="#a6edb393ad901a281393d41f46d6c9524">TimeTraceProfilerEntry</a>.</p>

</div>
</div>

### EventType {#a7006ae5f178ee7820bccd9ce47a493e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TimeTraceEventType llvm::TimeTraceProfilerEntry::EventType = <a href="/web-llvm/docs/api/namespaces/llvm/#aad35af14abc5748960dd055e5c04aa41a119b8a171a57a705aba9b074d88db9b1">TimeTraceEventType::CompleteEvent</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Referenced by <a href="#a1cac605ae10bf41e0287bf9092d5b737">TimeTraceProfilerEntry</a> and <a href="#a6edb393ad901a281393d41f46d6c9524">TimeTraceProfilerEntry</a>.</p>

</div>
</div>

### Metadata {#ad155cf504f48ea1c33a8580f4cc6f401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TimeTraceMetadata llvm::TimeTraceProfilerEntry::Metadata</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Referenced by <a href="#a1cac605ae10bf41e0287bf9092d5b737">TimeTraceProfilerEntry</a> and <a href="#a6edb393ad901a281393d41f46d6c9524">TimeTraceProfilerEntry</a>.</p>

</div>
</div>

### Name {#a5ffb288c26cfa812542aa2fdcf15e6c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string llvm::TimeTraceProfilerEntry::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Referenced by <a href="#a1cac605ae10bf41e0287bf9092d5b737">TimeTraceProfilerEntry</a> and <a href="#a6edb393ad901a281393d41f46d6c9524">TimeTraceProfilerEntry</a>.</p>

</div>
</div>

### Start {#a0b12d592c97ddc5081fd39aa667ec491}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TimePointType llvm::TimeTraceProfilerEntry::Start</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Referenced by <a href="#a598e967448a332adc4eeb3dd6addf060">getFlameGraphDurUs</a>, <a href="#ace6db8639f337a01e7b985bbbb90d9e2">getFlameGraphStartUs</a>, <a href="#a1cac605ae10bf41e0287bf9092d5b737">TimeTraceProfilerEntry</a> and <a href="#a6edb393ad901a281393d41f46d6c9524">TimeTraceProfilerEntry</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
