---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/statistic-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Statistic.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/debugoptions-h">DebugOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/managedstatic-h">llvm/Support/ManagedStatic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mutex-h">llvm/Support/Mutex.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/timer-h">llvm/Support/Timer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">llvm/Support/YAMLTraits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;algorithm&gt;
#include &lt;cstring&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-statistic-cpp-">anonymous{Statistic.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-statistic-cpp-/statisticinfo">StatisticInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is used in a <a href="/web-llvm/docs/api/classes/llvm/managedstatic">ManagedStatic</a> so that it is created on demand (when the first statistic is bumped) and destroyed only when llvm_shutdown is called. <a href="/web-llvm/docs/api/classes/anonymous-statistic-cpp-/statisticinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38906af8cc37ba9ddf2260cf1e2b0483">EnableStats</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>-stats - Command line option to cause transformations to emit stats about what they did. <a href="#a38906af8cc37ba9ddf2260cf1e2b0483">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab47e06a77e4e7bb9d6110586053afd7">StatsAsJSON</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a558f5c44426d0eb7abb82a65e8892d9a">Enabled</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53f79cf8812ccb9a9d038c66e138176d">PrintOnExit</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/managedstatic">ManagedStatic</a>&lt; StatisticInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d1a0181d192027598d0cf59a7291e5d">StatInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/managedstatic">ManagedStatic</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sys/smartmutex">sys::SmartMutex</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac984e1f297b2dac8cbf7c4cf8777e4ea">StatLock</a></td>
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

### Enabled {#a558f5c44426d0eb7abb82a65e8892d9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Enabled</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a846137dc22b3b399b62f606698f3ed59">llvm::AreStatisticsEnabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5fa843ed7ad4b46e6ba9e284656eab96">llvm::EnableStatistics</a>, <a href="/web-llvm/docs/api/structs/llvm/namedregiontimer/#a49aea1d2b11c5daa73a6581fbaed6508">llvm::NamedRegionTimer::NamedRegionTimer</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a905978e46c9c9a277645e938f41e1876">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseCPol</a>, <a href="/web-llvm/docs/api/classes/llvm/trackingstatistic/#af204074bb99629a0b644be5a81b1a269">llvm::TrackingStatistic::RegisterStatistic</a>, <a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator/#a9fd1a3698b32729075e4d192b0f423d0">llvm::LTOCodeGenerator::setDebugPassManager</a>, <a href="/web-llvm/docs/api/groups/options/#gac980489ed9310beb8f24ce41327b39cd">llvm::ThinLTOCodeGenerator::setDebugPassManager</a>, <a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator/#afe9393c3af8e0cc6aba8e3045603d2e3">llvm::LTOCodeGenerator::setFreestanding</a>, <a href="/web-llvm/docs/api/groups/options/#ga61aebfd57af923c49f69294039c528f9">llvm::ThinLTOCodeGenerator::setFreestanding</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a506819ac2ff216f44dd9674f2bebd80b">llvm::X86::updateImpliedFeatures</a>.</p>

</div>
</div>

### EnableStats {#a38906af8cc37ba9ddf2260cf1e2b0483}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EnableStats</td>
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

<p>-stats - Command line option to cause transformations to emit stats about what they did.</p>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a846137dc22b3b399b62f606698f3ed59">llvm::AreStatisticsEnabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87a54c835d57e5f3da731e65fcdddeb6">llvm::initStatisticOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5094c6f6a737f5a94596cdab0b2b449">llvm::PrintStatistics</a>, <a href="/web-llvm/docs/api/classes/llvm/trackingstatistic/#af204074bb99629a0b644be5a81b1a269">llvm::TrackingStatistic::RegisterStatistic</a> and <a href="/web-llvm/docs/api/classes/anonymous-statistic-cpp-/statisticinfo/#a91198341d265a83ba2657a4eb140d0dc">anonymous{Statistic.cpp}::StatisticInfo::~StatisticInfo</a>.</p>

</div>
</div>

### PrintOnExit {#a53f79cf8812ccb9a9d038c66e138176d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PrintOnExit</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5fa843ed7ad4b46e6ba9e284656eab96">llvm::EnableStatistics</a> and <a href="/web-llvm/docs/api/classes/anonymous-statistic-cpp-/statisticinfo/#a91198341d265a83ba2657a4eb140d0dc">anonymous{Statistic.cpp}::StatisticInfo::~StatisticInfo</a>.</p>

</div>
</div>

### StatInfo {#a9d1a0181d192027598d0cf59a7291e5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ManagedStatic&lt;StatisticInfo&gt; StatInfo</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aaf5def081d7ef2cb43fcc6ada7167ef5">llvm::GetStatistics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5094c6f6a737f5a94596cdab0b2b449">llvm::PrintStatistics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4956c1072998f3de28fb64a8979fcbf5">llvm::PrintStatistics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec1a19ebf309a206257e212c33f045a1">llvm::PrintStatisticsJSON</a>, <a href="/web-llvm/docs/api/classes/llvm/trackingstatistic/#af204074bb99629a0b644be5a81b1a269">llvm::TrackingStatistic::RegisterStatistic</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1dee1e2846e883eea571e31bc8fc2d46">llvm::ResetStatistics</a>.</p>

</div>
</div>

### StatLock {#ac984e1f297b2dac8cbf7c4cf8777e4ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ManagedStatic&lt;sys::SmartMutex&lt;true&gt; &gt; StatLock</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aaf5def081d7ef2cb43fcc6ada7167ef5">llvm::GetStatistics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5094c6f6a737f5a94596cdab0b2b449">llvm::PrintStatistics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec1a19ebf309a206257e212c33f045a1">llvm::PrintStatisticsJSON</a>, <a href="/web-llvm/docs/api/classes/llvm/trackingstatistic/#af204074bb99629a0b644be5a81b1a269">llvm::TrackingStatistic::RegisterStatistic</a> and <a href="/web-llvm/docs/api/classes/anonymous-statistic-cpp-/statisticinfo/#a66a9ccf524624d58bb8f87b75dcb2b34">anonymous{Statistic.cpp}::StatisticInfo::reset</a>.</p>

</div>
</div>

### StatsAsJSON {#aab47e06a77e4e7bb9d6110586053afd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StatsAsJSON</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp">Statistic.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a87a54c835d57e5f3da731e65fcdddeb6">llvm::initStatisticOptions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa5094c6f6a737f5a94596cdab0b2b449">llvm::PrintStatistics</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
