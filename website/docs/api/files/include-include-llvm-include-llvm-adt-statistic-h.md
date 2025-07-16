---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/adt/statistic-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Statistic.h` File Reference

<p>This file defines the 'Statistic' class, which is designed to be an easy way to expose various metrics from passes. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "llvm/Config/llvm-config.h"
#include &lt;atomic&gt;
#include &lt;memory&gt;
#include &lt;vector&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/trackingstatistic">TrackingStatistic</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/noopstatistic">NoopStatistic</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac311f239b900e2f7d6b6b0a71d192361">LLVM_ENABLE_STATS</a>&nbsp;&nbsp;&nbsp;1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6117415b93e5675d5a6c8e1855b3b2f">STATISTIC</a>(VARNAME, DESC)&nbsp;&nbsp;&nbsp;  static <a href="/web-llvm/docs/api/namespaces/llvm/#a6412c3ea6550f1aeab7571b6d38a2bf3">llvm::Statistic</a> VARNAME = {<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, #VARNAME, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetailpredication-cpp/#a51f62d37762db1aa829ad4fe2627fbf9">DESC</a>}</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dbcd375ae3d0b19303f5f48ca1bfce2">ALWAYS_ENABLED_STATISTIC</a>(VARNAME, DESC)&nbsp;&nbsp;&nbsp;  static <a href="/web-llvm/docs/api/classes/llvm/trackingstatistic">llvm::TrackingStatistic</a> VARNAME = {<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, #VARNAME, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetailpredication-cpp/#a51f62d37762db1aa829ad4fe2627fbf9">DESC</a>}</td>
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

<p>This file defines the 'Statistic' class, which is designed to be an easy way to expose various metrics from passes.</p>


<p>These statistics are printed at the end of a run (from llvm_shutdown), when the -stats command line option is passed on the command line.</p>


<p>This is useful for reporting information like the number of instructions simplified, optimized or removed by various transformations, like this:</p>


<p>static Statistic NumInstsKilled("gcse", "Number of instructions killed");</p>


<p>Later, in the code: ++NumInstsKilled;</p>


<p>NOTE: Statistics <em>must</em> be declared as global variables.</p>


<div class="doxySectionDef">

## Macro Definitions

### ALWAYS\_ENABLED\_STATISTIC {#a1dbcd375ae3d0b19303f5f48ca1bfce2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ALWAYS_ENABLED_STATISTIC(VARNAME, DESC)&nbsp;&nbsp;&nbsp;  static <a href="/web-llvm/docs/api/classes/llvm/trackingstatistic">llvm::TrackingStatistic</a> VARNAME = {<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, #VARNAME, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetailpredication-cpp/#a51f62d37762db1aa829ad4fe2627fbf9">DESC</a>}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>

</div>
</div>

### LLVM\_ENABLE\_STATS {#ac311f239b900e2f7d6b6b0a71d192361}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ENABLE_STATS&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>

</div>
</div>

### STATISTIC {#ad6117415b93e5675d5a6c8e1855b3b2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define STATISTIC(VARNAME, DESC)&nbsp;&nbsp;&nbsp;  static <a href="/web-llvm/docs/api/namespaces/llvm/#a6412c3ea6550f1aeab7571b6d38a2bf3">llvm::Statistic</a> VARNAME = {<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, #VARNAME, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetailpredication-cpp/#a51f62d37762db1aa829ad4fe2627fbf9">DESC</a>}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">Statistic.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
