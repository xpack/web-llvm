---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/threadpoolstrategy
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ThreadPoolStrategy` Class

<p>This tells how a thread pool will be used. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ThreadPoolStrategy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threading-h">llvm/Support/Threading.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac128c3b3bd0420224f86d2c385f3af99">compute_thread_count</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieves the max available threads for the current strategy. <a href="#ac128c3b3bd0420224f86d2c385f3af99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91973a96c25c9148226db40b463b5681">apply_thread_strategy</a> (unsigned ThreadPoolNum) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign the current thread to an ideal hardware CPU or NUMA node. <a href="#a91973a96c25c9148226db40b463b5681">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3377000f840bf21702914c7d552af21d">compute_cpu_socket</a> (unsigned ThreadPoolNum) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finds the CPU socket where a thread should go. <a href="#a3377000f840bf21702914c7d552af21d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40a8a25446e00b0d7eb5cc63884bea4e">ThreadsRequested</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d05cc9321306f401f9cc9990720173b">UseHyperThreads</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a006386e2fc403bf7964952c2d97432a8">Limit</a> = false</td>
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

<p>This tells how a thread pool will be used.</p>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threading-h">Threading.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### apply\_thread\_strategy() {#a91973a96c25c9148226db40b463b5681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ThreadPoolStrategy::apply_thread_strategy (unsigned ThreadPoolNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assign the current thread to an ideal hardware CPU or NUMA node.</p>


<p>In a multi-socket system, this ensures threads are assigned to all CPU sockets. <span class="doxyComputerOutput">ThreadPoolNum</span> represents a number bounded by [0, <a href="#ac128c3b3bd0420224f86d2c385f3af99">compute_thread_count()</a>).</p>


<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threading-h">Threading.h</a>.</p>

</div>
</div>

### compute\_cpu\_socket() {#a3377000f840bf21702914c7d552af21d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; llvm::ThreadPoolStrategy::compute_cpu_socket (unsigned ThreadPoolNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finds the CPU socket where a thread should go.</p>


<p>Returns 'std::nullopt' if the thread shall remain on the actual CPU socket.</p>


<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threading-h">Threading.h</a>.</p>

</div>
</div>

### compute\_thread\_count() {#ac128c3b3bd0420224f86d2c385f3af99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ThreadPoolStrategy::compute_thread_count ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieves the max available threads for the current strategy.</p>


<p>This accounts for affinity masks and takes advantage of all CPU sockets.</p>


<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threading-h">Threading.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/support/threading-cpp">Threading.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/singlethreadexecutor/#a3a0e760e0380aa0023a27372d5ffd4dc">llvm::SingleThreadExecutor::SingleThreadExecutor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Limit {#a006386e2fc403bf7964952c2d97432a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ThreadPoolStrategy::Limit = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threading-h">Threading.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a879dd68b6ab547079c3ef8b7a7e39277">llvm::optimal_concurrency</a>.</p>

</div>
</div>

### ThreadsRequested {#a40a8a25446e00b0d7eb5cc63884bea4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ThreadPoolStrategy::ThreadsRequested = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threading-h">Threading.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aaa15319612cd5edf41994eab4a092896">llvm::get_threadpool_strategy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a00440f10281348fd9f7be52e23c7c874">llvm::hardware_concurrency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a01b0ea0a16ef9208a33017ce9399da1a">llvm::heavyweight_hardware_concurrency</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a879dd68b6ab547079c3ef8b7a7e39277">llvm::optimal_concurrency</a>.</p>

</div>
</div>

### UseHyperThreads {#a4d05cc9321306f401f9cc9990720173b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ThreadPoolStrategy::UseHyperThreads = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threading-h">Threading.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a01b0ea0a16ef9208a33017ce9399da1a">llvm::heavyweight_hardware_concurrency</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threading-h">Threading.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/threading-cpp">Threading.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
