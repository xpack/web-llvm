---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/timetraceprofiler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `TimeTraceProfiler` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::TimeTraceProfiler { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ed90bedc720105e3872bfe12245e89d">TimeTraceProfiler</a> (unsigned TimeTraceGranularity=0, StringRef ProcName="", bool TimeTraceVerbose=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/timetraceprofilerentry">TimeTraceProfilerEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac126c92193886f3a968871dd648fbdec">begin</a> (std::string Name, llvm::function_ref&lt; std::string()&gt; Detail, TimeTraceEventType EventType=TimeTraceEventType::CompleteEvent)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/timetraceprofilerentry">TimeTraceProfilerEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68786afa1abe6cfdf9895169bbf8b1a8">begin</a> (std::string Name, llvm::function_ref&lt; TimeTraceMetadata()&gt; Metadata, TimeTraceEventType EventType=TimeTraceEventType::CompleteEvent)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e1c6f77d851ad58a72673f28a21c505">insert</a> (std::string Name, llvm::function_ref&lt; std::string()&gt; Detail)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ebaf2ff216599faeb27ec2ae6287601">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae521e93894bc7e93950f99db8b0b9ab3">end</a> (TimeTraceProfilerEntry &amp;E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a693558700fd7f79d6ba0313d9139f9">write</a> (raw_pwrite_stream &amp;OS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/inprogressentry">InProgressEntry</a> &gt;, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9072357cf7121c6aba997d00be5366de">Stack</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/timetraceprofilerentry">TimeTraceProfilerEntry</a>, 128 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3bfe92c24693032d162b4c211c68366">Entries</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; CountAndDurationType &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dda55aa47e148dba88b5485ad8c84a7">CountAndTotalPerName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> time_point&lt; <a href="/web-llvm/docs/api/classes/anonymous-timeprofiler-cpp-/system-clock">system_clock</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69b31744e8f56af853dacf2b41f1d985">BeginningOfTime</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TimePointType</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc9b53812bdc56fe205d646fd48cd09d">StartTime</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaae58325f44d45fe6b11c8710af37ea1">ProcName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sys/process/#af96f4ca9b4641dfa3b45ed1a07a7d525">sys::Process::Pid</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0665c3b7269ea0f33928576a0c31a26e">Pid</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa561402fab9c46e08086217e53ca04a5">ThreadName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a568bb4a539ffffea6262ff36e4e30001">Tid</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3814390ad9ff6dcae633cda14d5e49eb">TimeTraceGranularity</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1702baa90cbda0302030c61d0f1479c">TimeTraceVerbose</a></td>
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


<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TimeTraceProfiler() {#a9ed90bedc720105e3872bfe12245e89d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TimeTraceProfiler::TimeTraceProfiler (unsigned TimeTraceGranularity=0, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ProcName="", bool TimeTraceVerbose=false)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>References <a href="#a69b31744e8f56af853dacf2b41f1d985">BeginningOfTime</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9f631c8bd3916d1984a0df4ccce73461">llvm::get_thread_name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaa33daad43dedada2aa398a44b91be01">llvm::get_threadid</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a0edd35207e47a9fb4d484238d3172e82">now</a>, <a href="#a0665c3b7269ea0f33928576a0c31a26e">Pid</a>, <a href="#aaae58325f44d45fe6b11c8710af37ea1">ProcName</a>, <a href="#adc9b53812bdc56fe205d646fd48cd09d">StartTime</a>, <a href="#aa561402fab9c46e08086217e53ca04a5">ThreadName</a>, <a href="#a568bb4a539ffffea6262ff36e4e30001">Tid</a>, <a href="#a3814390ad9ff6dcae633cda14d5e49eb">TimeTraceGranularity</a> and <a href="#ad1702baa90cbda0302030c61d0f1479c">TimeTraceVerbose</a>.</p>


<p>Referenced by <a href="#a0a693558700fd7f79d6ba0313d9139f9">write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#ac126c92193886f3a968871dd648fbdec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TimeTraceProfilerEntry * llvm::TimeTraceProfiler::begin (std::string Name, <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; std::string()&gt; Detail, <a href="/web-llvm/docs/api/namespaces/llvm/#aad35af14abc5748960dd055e5c04aa41">TimeTraceEventType</a> EventType=<a href="/web-llvm/docs/api/namespaces/llvm/#aad35af14abc5748960dd055e5c04aa41a119b8a171a57a705aba9b074d88db9b1">TimeTraceEventType::CompleteEvent</a>)</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad35af14abc5748960dd055e5c04aa41a119b8a171a57a705aba9b074d88db9b1">llvm::CompleteEvent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad35af14abc5748960dd055e5c04aa41a2c177ecf931044783d5d8d64c65ee263">llvm::InstantEvent</a> and <a href="#a9072357cf7121c6aba997d00be5366de">Stack</a>.</p>

</div>
</div>

### begin() {#a68786afa1abe6cfdf9895169bbf8b1a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TimeTraceProfilerEntry * llvm::TimeTraceProfiler::begin (std::string Name, <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/timetracemetadata">TimeTraceMetadata</a>()&gt; Metadata, <a href="/web-llvm/docs/api/namespaces/llvm/#aad35af14abc5748960dd055e5c04aa41">TimeTraceEventType</a> EventType=<a href="/web-llvm/docs/api/namespaces/llvm/#aad35af14abc5748960dd055e5c04aa41a119b8a171a57a705aba9b074d88db9b1">TimeTraceEventType::CompleteEvent</a>)</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad35af14abc5748960dd055e5c04aa41a119b8a171a57a705aba9b074d88db9b1">llvm::CompleteEvent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad35af14abc5748960dd055e5c04aa41a2c177ecf931044783d5d8d64c65ee263">llvm::InstantEvent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a26b689be9525270658579553e0adfec1">Metadata</a> and <a href="#a9072357cf7121c6aba997d00be5366de">Stack</a>.</p>

</div>
</div>

### end() {#a5ebaf2ff216599faeb27ec2ae6287601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TimeTraceProfiler::end ()</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5ebaf2ff216599faeb27ec2ae6287601">end</a> and <a href="#a9072357cf7121c6aba997d00be5366de">Stack</a>.</p>


<p>Referenced by <a href="#a5ebaf2ff216599faeb27ec2ae6287601">end</a>.</p>

</div>
</div>

### end() {#ae521e93894bc7e93950f99db8b0b9ab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TimeTraceProfiler::end (<a href="/web-llvm/docs/api/structs/llvm/timetraceprofilerentry">TimeTraceProfilerEntry</a> &amp; E)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="#a2dda55aa47e148dba88b5485ad8c84a7">CountAndTotalPerName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="#ac3bfe92c24693032d162b4c211c68366">Entries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="#a9072357cf7121c6aba997d00be5366de">Stack</a> and <a href="#a3814390ad9ff6dcae633cda14d5e49eb">TimeTraceGranularity</a>.</p>

</div>
</div>

### insert() {#a5e1c6f77d851ad58a72673f28a21c505}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TimeTraceProfiler::insert (std::string Name, <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; std::string()&gt; Detail)</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aad35af14abc5748960dd055e5c04aa41a2c177ecf931044783d5d8d64c65ee263">llvm::InstantEvent</a> and <a href="#a9072357cf7121c6aba997d00be5366de">Stack</a>.</p>

</div>
</div>

### write() {#a0a693558700fd7f79d6ba0313d9139f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TimeTraceProfiler::write (<a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; OS)</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#a5741cf7e48bbab22369fa2aa8c9e151f">llvm::json::OStream::arrayBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#aa4ef0d3ce12400b17d9f9a5cd028a211">llvm::json::OStream::arrayEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad35af14abc5748960dd055e5c04aa41ae68f4ecc5b67fb22797237d95bcdbdd5">llvm::AsyncEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#a4754bca88e59468dba45df18b849920a">llvm::json::OStream::attribute</a>, <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#a39613bf6aa1a8059a4dd25d57c7fd1e5">llvm::json::OStream::attributeBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#aacce5798acdb34154adce0318fdfdaf8">llvm::json::OStream::attributeEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#a0e888ce91e1087ca58869357b718fd38">llvm::json::OStream::attributeObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a69b31744e8f56af853dacf2b41f1d985">BeginningOfTime</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad35af14abc5748960dd055e5c04aa41a119b8a171a57a705aba9b074d88db9b1">llvm::CompleteEvent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="#a2dda55aa47e148dba88b5485ad8c84a7">CountAndTotalPerName</a>, <a href="#ac3bfe92c24693032d162b4c211c68366">Entries</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad35af14abc5748960dd055e5c04aa41a2c177ecf931044783d5d8d64c65ee263">llvm::InstantEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#a06d556674c46c15e5906f2f645f4fbe5">llvm::json::OStream::object</a>, <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#a5f20bfc936e2aaf698df6de5b3a0c397">llvm::json::OStream::objectBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#af9928f1fc2112c92546d8e31ced97033">llvm::json::OStream::objectEnd</a>, <a href="#a0665c3b7269ea0f33928576a0c31a26e">Pid</a>, <a href="#aaae58325f44d45fe6b11c8710af37ea1">ProcName</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmapimpl/#a80596ea56fa14ea5a773d303ee64293c">llvm::StringMapImpl::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="#a9072357cf7121c6aba997d00be5366de">Stack</a>, <a href="#adc9b53812bdc56fe205d646fd48cd09d">StartTime</a>, <a href="#aa561402fab9c46e08086217e53ca04a5">ThreadName</a>, <a href="#a568bb4a539ffffea6262ff36e4e30001">Tid</a>, <a href="#a9ed90bedc720105e3872bfe12245e89d">TimeTraceProfiler</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af5ab7a47bc553dfc3ee92daf969d0d7ca96b0141273eabab320119c467cdcaf17">llvm::Total</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BeginningOfTime {#a69b31744e8f56af853dacf2b41f1d985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const time_point&lt;system_clock&gt; llvm::TimeTraceProfiler::BeginningOfTime</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Referenced by <a href="#a9ed90bedc720105e3872bfe12245e89d">TimeTraceProfiler</a> and <a href="#a0a693558700fd7f79d6ba0313d9139f9">write</a>.</p>

</div>
</div>

### CountAndTotalPerName {#a2dda55aa47e148dba88b5485ad8c84a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;CountAndDurationType&gt; llvm::TimeTraceProfiler::CountAndTotalPerName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Referenced by <a href="#ae521e93894bc7e93950f99db8b0b9ab3">end</a> and <a href="#a0a693558700fd7f79d6ba0313d9139f9">write</a>.</p>

</div>
</div>

### Entries {#ac3bfe92c24693032d162b4c211c68366}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;TimeTraceProfilerEntry, 128&gt; llvm::TimeTraceProfiler::Entries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Referenced by <a href="#ae521e93894bc7e93950f99db8b0b9ab3">end</a> and <a href="#a0a693558700fd7f79d6ba0313d9139f9">write</a>.</p>

</div>
</div>

### Pid {#a0665c3b7269ea0f33928576a0c31a26e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const sys::Process::Pid llvm::TimeTraceProfiler::Pid</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Referenced by <a href="#a9ed90bedc720105e3872bfe12245e89d">TimeTraceProfiler</a> and <a href="#a0a693558700fd7f79d6ba0313d9139f9">write</a>.</p>

</div>
</div>

### ProcName {#aaae58325f44d45fe6b11c8710af37ea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string llvm::TimeTraceProfiler::ProcName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Referenced by <a href="#a9ed90bedc720105e3872bfe12245e89d">TimeTraceProfiler</a> and <a href="#a0a693558700fd7f79d6ba0313d9139f9">write</a>.</p>

</div>
</div>

### Stack {#a9072357cf7121c6aba997d00be5366de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;InProgressEntry&gt;, 16&gt; llvm::TimeTraceProfiler::Stack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Referenced by <a href="#ac126c92193886f3a968871dd648fbdec">begin</a>, <a href="#a68786afa1abe6cfdf9895169bbf8b1a8">begin</a>, <a href="#a5ebaf2ff216599faeb27ec2ae6287601">end</a>, <a href="#ae521e93894bc7e93950f99db8b0b9ab3">end</a>, <a href="#a5e1c6f77d851ad58a72673f28a21c505">insert</a> and <a href="#a0a693558700fd7f79d6ba0313d9139f9">write</a>.</p>

</div>
</div>

### StartTime {#adc9b53812bdc56fe205d646fd48cd09d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TimePointType llvm::TimeTraceProfiler::StartTime</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Referenced by <a href="#a9ed90bedc720105e3872bfe12245e89d">TimeTraceProfiler</a> and <a href="#a0a693558700fd7f79d6ba0313d9139f9">write</a>.</p>

</div>
</div>

### ThreadName {#aa561402fab9c46e08086217e53ca04a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt;0&gt; llvm::TimeTraceProfiler::ThreadName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Referenced by <a href="#a9ed90bedc720105e3872bfe12245e89d">TimeTraceProfiler</a> and <a href="#a0a693558700fd7f79d6ba0313d9139f9">write</a>.</p>

</div>
</div>

### Tid {#a568bb4a539ffffea6262ff36e4e30001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t llvm::TimeTraceProfiler::Tid</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Referenced by <a href="#a9ed90bedc720105e3872bfe12245e89d">TimeTraceProfiler</a> and <a href="#a0a693558700fd7f79d6ba0313d9139f9">write</a>.</p>

</div>
</div>

### TimeTraceGranularity {#a3814390ad9ff6dcae633cda14d5e49eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::TimeTraceProfiler::TimeTraceGranularity</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Referenced by <a href="#ae521e93894bc7e93950f99db8b0b9ab3">end</a> and <a href="#a9ed90bedc720105e3872bfe12245e89d">TimeTraceProfiler</a>.</p>

</div>
</div>

### TimeTraceVerbose {#ad1702baa90cbda0302030c61d0f1479c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::TimeTraceProfiler::TimeTraceVerbose</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timeprofiler-cpp">TimeProfiler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa7db90a41d181a3755d0e29312b8e066">llvm::isTimeTraceVerbose</a> and <a href="#a9ed90bedc720105e3872bfe12245e89d">TimeTraceProfiler</a>.</p>

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
