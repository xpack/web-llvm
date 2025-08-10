---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/namedregiontimer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `NamedRegionTimer` Struct

<p>This class is basically a combination of <a href="/web-llvm/docs/api/classes/llvm/timeregion">TimeRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/timer">Timer</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::NamedRegionTimer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/timer-h">llvm/Support/Timer.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/timeregion">TimeRegion</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/timeregion">TimeRegion</a> class is used as a helper class to call the startTimer() and stopTimer() methods of the <a href="/web-llvm/docs/api/classes/llvm/timer">Timer</a> class. <a href="/web-llvm/docs/api/classes/llvm/timeregion/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/anonymous-amdgpusplitmodule-cpp-/splitmoduletimer">SplitModuleTimer</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49aea1d2b11c5daa73a6581fbaed6508">NamedRegionTimer</a> (StringRef Name, StringRef Description, StringRef GroupName, StringRef GroupDescription, bool Enabled=true)</td>
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

<p>This class is basically a combination of <a href="/web-llvm/docs/api/classes/llvm/timeregion">TimeRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/timer">Timer</a>.</p>


<p>It allows you to declare a new timer, AND specify the region to time, all in one statement. All timers with the same name are merged. This is primarily used for debugging and for hunting performance problems.</p>


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/timer-h">Timer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NamedRegionTimer() {#a49aea1d2b11c5daa73a6581fbaed6508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedRegionTimer::NamedRegionTimer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Description, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> GroupName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> GroupDescription, bool Enabled=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/timer-h">Timer.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp/#a558f5c44426d0eb7abb82a65e8892d9a">Enabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp/#afb6d577d1cb5c950d39c4fe15ef86fe4">namedGroupedTimers</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/anonymous-amdgpusplitmodule-cpp-/splitmoduletimer/#a32caff3fa952d45c3f9c935ce9eecce2">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitModuleTimer::SplitModuleTimer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/timer-h">Timer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp">Timer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
