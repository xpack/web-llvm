---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/timerglobals
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TimerGlobals` Class



## Declaration

<div class="doxyDeclaration">
class llvm::TimerGlobals { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/timerglobals">TimerGlobals</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4713894f737918888ce46df45ee5b0c5">initDeferred</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83b0745c0165f954274a877bc2bd1e12">LibSupportInfoOutputFilename</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; std::string, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a045e48723b0a8fcc2fc3c5ea723d242d">InfoOutputFilename</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7c06f609286798c31a7ded0775e04d9">TrackSpace</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c0c63f01c335d67b5f7a27cfc4d49bf">SortTimers</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/smartmutex">sys::SmartMutex</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44e2fc6343e2ddf39860dc9f04958054">TimerLock</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/timergroup">TimerGroup</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a97864aa11e6beeac8a5061bb5cebfa">DefaultTimerGroup</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/signpostemitter">SignpostEmitter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfd1c473274913d4a8455566ee7740b6">Signposts</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::once_flag</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac924ee4cba3083e1bac1246976a76a01">InitDeferredFlag</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; Name2PairMap &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7cd627113a2b18fcdb285e77f06a285">NamedGroupedTimersPtr</a></td>
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


<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### initDeferred() {#a4713894f737918888ce46df45ee5b0c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TimerGlobals &amp; llvm::TimerGlobals::initDeferred ()</td>
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



<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>


<p>References <a href="#ac924ee4cba3083e1bac1246976a76a01">InitDeferredFlag</a> and <a href="#ad7cd627113a2b18fcdb285e77f06a285">NamedGroupedTimersPtr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DefaultTimerGroup {#a9a97864aa11e6beeac8a5061bb5cebfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TimerGroup llvm::TimerGlobals::DefaultTimerGroup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{"misc", "Miscellaneous Ungrouped Timers",
                               <a href="#a44e2fc6343e2ddf39860dc9f04958054">TimerLock</a>}
</div>
</dd>
</dl>

<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>

</div>
</div>

### InfoOutputFilename {#a045e48723b0a8fcc2fc3c5ea723d242d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt;std::string, true&gt; llvm::TimerGlobals::InfoOutputFilename</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      "info-output-file", <a href="/web-llvm/docs/api/structs/llvm/cl/value-desc">cl::value_desc</a>("filename"),
      <a href="/web-llvm/docs/api/structs/llvm/cl/desc">cl::desc</a>("File to append -<a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a971b2fc3751cade0a6b2f76c92774317">stats</a> and -timer output to"), <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a68075925a54790e71ca790e1d4f21a40a263ac008d8d31f13ce460395fc4cf7e6">cl::Hidden</a>,
      <a href="/web-llvm/docs/api/namespaces/llvm/cl/#ad4de522646a65d987250e3aba9c55931">cl::location</a>(<a href="#a83b0745c0165f954274a877bc2bd1e12">LibSupportInfoOutputFilename</a>)}
</div>
</dd>
</dl>

<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>

</div>
</div>

### InitDeferredFlag {#ac924ee4cba3083e1bac1246976a76a01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::once_flag llvm::TimerGlobals::InitDeferredFlag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>


<p>Referenced by <a href="#a4713894f737918888ce46df45ee5b0c5">initDeferred</a>.</p>

</div>
</div>

### LibSupportInfoOutputFilename {#a83b0745c0165f954274a877bc2bd1e12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::TimerGlobals::LibSupportInfoOutputFilename</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>

</div>
</div>

### NamedGroupedTimersPtr {#ad7cd627113a2b18fcdb285e77f06a285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;Name2PairMap&gt; llvm::TimerGlobals::NamedGroupedTimersPtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>


<p>Referenced by <a href="#a4713894f737918888ce46df45ee5b0c5">initDeferred</a>.</p>

</div>
</div>

### Signposts {#acfd1c473274913d4a8455566ee7740b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SignpostEmitter llvm::TimerGlobals::Signposts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>

</div>
</div>

### SortTimers {#a1c0c63f01c335d67b5f7a27cfc4d49bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt;bool&gt; llvm::TimerGlobals::SortTimers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      "sort-timers",
      <a href="/web-llvm/docs/api/structs/llvm/cl/desc">cl::desc</a>("In the report, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">sort</a> the timers in each group in wall clock"
               " time order"),
      <a href="/web-llvm/docs/api/namespaces/llvm/cl/#ac12e6a8f3a1b511f0dee2ed6de0ae806">cl::init</a>(<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>), <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a68075925a54790e71ca790e1d4f21a40a263ac008d8d31f13ce460395fc4cf7e6">cl::Hidden</a>}
</div>
</dd>
</dl>

<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>

</div>
</div>

### TimerLock {#a44e2fc6343e2ddf39860dc9f04958054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::SmartMutex&lt;true&gt; llvm::TimerGlobals::TimerLock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>

</div>
</div>

### TrackSpace {#aa7c06f609286798c31a7ded0775e04d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt;bool&gt; llvm::TimerGlobals::TrackSpace</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      "track-memory",
      <a href="/web-llvm/docs/api/structs/llvm/cl/desc">cl::desc</a>("Enable -time-passes memory tracking (this may be slow)"),
      cl::Hidden}
</div>
</dd>
</dl>

<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
