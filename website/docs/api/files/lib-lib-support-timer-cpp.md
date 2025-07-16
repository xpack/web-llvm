---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/timer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Timer.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/timer-h">llvm/Support/Timer.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/debugoptions-h">DebugOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmap-h">llvm/ADT/StringMap.h</a>"
#include "llvm/Config/config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/managedstatic-h">llvm/Support/ManagedStatic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mutex-h">llvm/Support/Mutex.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">llvm/Support/Process.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/signposts-h">llvm/Support/Signposts.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">llvm/Support/YAMLTraits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;limits&gt;
#include &lt;optional&gt;
#include &lt;libproc.h&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-timer-cpp-">anonymous{Timer.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-timer-cpp-/name2pairmap">Name2PairMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/timerglobals">TimerGlobals</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f4ca43ffece041331105197642827f4">libSupportInfoOutputFilename</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f76e122a07668be56a5dfeca2454588">trackSpace</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b8a6e82ab19073b9d3efd3da734251f">sortTimers</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/signpostemitter">SignpostEmitter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a293de2dbf1e57b01ddeeb62b307f709c">signposts</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sys/smartmutex">sys::SmartMutex</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a045753d0e43214174c828a9d55b4908a">timerLock</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/timergroup">TimerGroup</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11ed953c3156a50de57fe91b75e0f0fc">defaultTimerGroup</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static Name2PairMap &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb6d577d1cb5c950d39c4fe15ef86fe4">namedGroupedTimers</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a552e7f089f2210623ca8ee55d313ddfe">getMemUsage</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaadd63f826bb964e10a62cb7ddc70a2">getCurInstructionsExecuted</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a558cc06dc9c21ec11f8a980d608b03e8">printVal</a> (double Val, double Total, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/timergroup">TimerGroup</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6642d7e0eb643b2f2aa3ecfd4a11f9db">TimerGroupList</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the global list of TimerGroups, maintained by the <a href="/web-llvm/docs/api/classes/llvm/timergroup">TimerGroup</a> ctor/dtor and is protected by the timerLock lock. <a href="#a6642d7e0eb643b2f2aa3ecfd4a11f9db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/managedstatic">ManagedStatic</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/timerglobals">TimerGlobals</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a2715ee69960530b0a5716c28dc1641">ManagedTimerGlobals</a></td>
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

## Functions

### defaultTimerGroup() {#a11ed953c3156a50de57fe91b75e0f0fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TimerGroup &amp; defaultTimerGroup ()</td>
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



<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>


<p>Reference <a href="#a0a2715ee69960530b0a5716c28dc1641">ManagedTimerGlobals</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/timer/#a626ef204535e60dae4e698189c534583">llvm::Timer::init</a>.</p>

</div>
</div>

### getCurInstructionsExecuted() {#adaadd63f826bb964e10a62cb7ddc70a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getCurInstructionsExecuted ()</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/timerecord/#a867cbf168949d9b11c9dcb23ffb6989b">llvm::TimeRecord::getCurrentTime</a>.</p>

</div>
</div>

### getMemUsage() {#a552e7f089f2210623ca8ee55d313ddfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t getMemUsage ()</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sys/process/#aefb2b72e3e500a8b559e5d8c265b40e6">llvm::sys::Process::GetMallocUsage</a> and <a href="#a1f76e122a07668be56a5dfeca2454588">trackSpace</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/timerecord/#a867cbf168949d9b11c9dcb23ffb6989b">llvm::TimeRecord::getCurrentTime</a>.</p>

</div>
</div>

### libSupportInfoOutputFilename() {#a1f4ca43ffece041331105197642827f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string &amp; libSupportInfoOutputFilename ()</td>
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



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>


<p>Reference <a href="#a0a2715ee69960530b0a5716c28dc1641">ManagedTimerGlobals</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a09515ea8784bdea8e0e866799bb38409">llvm::CreateInfoOutputFile</a>.</p>

</div>
</div>

### namedGroupedTimers() {#afb6d577d1cb5c950d39c4fe15ef86fe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Name2PairMap &amp; namedGroupedTimers ()</td>
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



<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>


<p>Reference <a href="#a0a2715ee69960530b0a5716c28dc1641">ManagedTimerGlobals</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/namedregiontimer/#a49aea1d2b11c5daa73a6581fbaed6508">llvm::NamedRegionTimer::NamedRegionTimer</a>.</p>

</div>
</div>

### printVal() {#a558cc06dc9c21ec11f8a980d608b03e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printVal (double Val, double Total, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af5ab7a47bc553dfc3ee92daf969d0d7ca96b0141273eabab320119c467cdcaf17">llvm::Total</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/timerecord/#abc3d2ce671fe9070a5bbac3b6591497b">llvm::TimeRecord::print</a>.</p>

</div>
</div>

### signposts() {#a293de2dbf1e57b01ddeeb62b307f709c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SignpostEmitter &amp; signposts ()</td>
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



<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>


<p>Reference <a href="#a0a2715ee69960530b0a5716c28dc1641">ManagedTimerGlobals</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/timer/#aa8c887576ec3b0d68c10ebf4097c367c">llvm::Timer::startTimer</a> and <a href="/web-llvm/docs/api/classes/llvm/timer/#a27f97da1b1d19ad74a847703ca25c455">llvm::Timer::stopTimer</a>.</p>

</div>
</div>

### sortTimers() {#a4b8a6e82ab19073b9d3efd3da734251f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool sortTimers ()</td>
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



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>


<p>Reference <a href="#a0a2715ee69960530b0a5716c28dc1641">ManagedTimerGlobals</a>.</p>

</div>
</div>

### timerLock() {#a045753d0e43214174c828a9d55b4908a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::SmartMutex&lt; true &gt; &amp; timerLock ()</td>
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



<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>


<p>Reference <a href="#a0a2715ee69960530b0a5716c28dc1641">ManagedTimerGlobals</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/timergroup/#a726a6fcdd700935b08afd02091d5ec75">llvm::TimerGroup::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/timergroup/#a5677ae12c385811e1ddcaf063644838a">llvm::TimerGroup::clearAll</a>, <a href="/web-llvm/docs/api/classes/anonymous-timer-cpp-/name2pairmap/#a0fe94b51268cc8c128c60567a255a9ca">anonymous{Timer.cpp}::Name2PairMap::get</a>, <a href="/web-llvm/docs/api/classes/llvm/timergroup/#a49bc01107059f84cec6dc0fd3fb98871">llvm::TimerGroup::print</a>, <a href="/web-llvm/docs/api/classes/llvm/timergroup/#a0055d6c88e2981d059986c012f6183af">llvm::TimerGroup::printAll</a>, <a href="/web-llvm/docs/api/classes/llvm/timergroup/#af4bdbb396753a9f904cc63937bcbe026">llvm::TimerGroup::printAllJSONValues</a>, <a href="/web-llvm/docs/api/classes/llvm/timergroup/#af4c8a9ee715a98a536ccb52bdb1f3a2d">llvm::TimerGroup::printJSONValues</a>, <a href="/web-llvm/docs/api/classes/llvm/timergroup/#a41522424f46bb62c3d4be9559b297380">llvm::TimerGroup::TimerGroup</a> and <a href="/web-llvm/docs/api/classes/llvm/timergroup/#a9efb4749c57851398d2b7f84b24f017d">llvm::TimerGroup::~TimerGroup</a>.</p>

</div>
</div>

### trackSpace() {#a1f76e122a07668be56a5dfeca2454588}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool trackSpace ()</td>
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



<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>


<p>Reference <a href="#a0a2715ee69960530b0a5716c28dc1641">ManagedTimerGlobals</a>.</p>


<p>Referenced by <a href="#a552e7f089f2210623ca8ee55d313ddfe">getMemUsage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ManagedTimerGlobals {#a0a2715ee69960530b0a5716c28dc1641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ManagedStatic&lt;TimerGlobals&gt; ManagedTimerGlobals</td>
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



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/timergroup/#aca3d0aa3c0b7f45bf7fa527e30d423bf">llvm::TimerGroup::acquireTimerGlobals</a>, <a href="/web-llvm/docs/api/classes/llvm/timergroup/#af7e26e04ebc4659b165821aa390316a7">llvm::TimerGroup::constructForStatistics</a>, <a href="#a11ed953c3156a50de57fe91b75e0f0fc">defaultTimerGroup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a020f377cc123ca6dfabe1ebc5cc55f">llvm::initTimerOptions</a>, <a href="#a1f4ca43ffece041331105197642827f4">libSupportInfoOutputFilename</a>, <a href="#afb6d577d1cb5c950d39c4fe15ef86fe4">namedGroupedTimers</a>, <a href="#a293de2dbf1e57b01ddeeb62b307f709c">signposts</a>, <a href="#a4b8a6e82ab19073b9d3efd3da734251f">sortTimers</a>, <a href="#a045753d0e43214174c828a9d55b4908a">timerLock</a> and <a href="#a1f76e122a07668be56a5dfeca2454588">trackSpace</a>.</p>

</div>
</div>

### TimerGroupList {#a6642d7e0eb643b2f2aa3ecfd4a11f9db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TimerGroup* TimerGroupList = nullptr</td>
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

<p>This is the global list of TimerGroups, maintained by the <a href="/web-llvm/docs/api/classes/llvm/timergroup">TimerGroup</a> ctor/dtor and is protected by the timerLock lock.</p>

<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/timergroup/#a5677ae12c385811e1ddcaf063644838a">llvm::TimerGroup::clearAll</a>, <a href="/web-llvm/docs/api/classes/llvm/timergroup/#a0055d6c88e2981d059986c012f6183af">llvm::TimerGroup::printAll</a> and <a href="/web-llvm/docs/api/classes/llvm/timergroup/#af4bdbb396753a9f904cc63937bcbe026">llvm::TimerGroup::printAllJSONValues</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
