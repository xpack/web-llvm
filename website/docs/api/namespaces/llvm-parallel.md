---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/parallel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `parallel` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::parallel { ... }
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/parallel/detail">detail</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parallel/taskgroup">TaskGroup</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parallel/perthreadallocator">PerThreadAllocator&lt;AllocatorTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/parallel/perthreadallocator">PerThreadAllocator</a> is used in conjunction with ThreadPoolExecutor to allow per-thread allocations. <a href="/web-llvm/docs/api/classes/llvm/parallel/perthreadallocator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e82d98d22361038741bca9bd34bca85">PerThreadBumpPtrAllocator</a> = <a href="/web-llvm/docs/api/classes/llvm/parallel/perthreadallocator">PerThreadAllocator</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83352bd1dc4147ad0f85ff0fefa57ac3">getThreadIndex</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac537a7c295510dfb54a3260e057c5c91">getThreadCount</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadpoolstrategy">ThreadPoolStrategy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68f04a4e2c26fa6b9cd7517dced50729">strategy</a></td>
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

## Typedefs

### PerThreadBumpPtrAllocator {#a4e82d98d22361038741bca9bd34bca85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::parallel::PerThreadBumpPtrAllocator =  PerThreadAllocator&lt;BumpPtrAllocator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/perthreadbumpptrallocator-h">PerThreadBumpPtrAllocator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getThreadCount() {#ac537a7c295510dfb54a3260e057c5c91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::parallel::getThreadCount ()</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/parallel-h">Parallel.h</a>.</p>


<p>Reference <a href="#ac537a7c295510dfb54a3260e057c5c91">getThreadCount</a>.</p>


<p>Referenced by <a href="#ac537a7c295510dfb54a3260e057c5c91">getThreadCount</a> and <a href="/web-llvm/docs/api/classes/llvm/parallel/perthreadallocator/#a9712b9344a02b17ef04b17ff8a182b56">llvm::parallel::PerThreadAllocator&lt; BumpPtrAllocator &gt;::PerThreadAllocator</a>.</p>

</div>
</div>

### getThreadIndex() {#a83352bd1dc4147ad0f85ff0fefa57ac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::parallel::getThreadIndex ()</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/parallel-h">Parallel.h</a>.</p>


<p>Reference <a href="#a83352bd1dc4147ad0f85ff0fefa57ac3">getThreadIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/methods/#gac50204237d93d1b18c5a6bef8e7f7a35">llvm::parallel::PerThreadAllocator&lt; BumpPtrAllocator &gt;::Allocate</a>, <a href="/web-llvm/docs/api/groups/methods/#ga40b8fb32acf8598697e08acfdeb9dfe6">llvm::parallel::PerThreadAllocator&lt; BumpPtrAllocator &gt;::Deallocate</a>, <a href="#a83352bd1dc4147ad0f85ff0fefa57ac3">getThreadIndex</a> and <a href="/web-llvm/docs/api/groups/methods/#gae12d36c6142e37df006ccd257fe67ed4">llvm::parallel::PerThreadAllocator&lt; BumpPtrAllocator &gt;::getThreadLocalAllocator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### strategy {#a68f04a4e2c26fa6b9cd7517dced50729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ThreadPoolStrategy llvm::parallel::strategy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/parallel-h">Parallel.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/support/parallel-cpp">Parallel.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/concurrenthashtablebyptr/#aedb1b2d838f24c81b5c649395e24ef08">llvm::ConcurrentHashTableByPtr&lt; KeyTy, KeyDataTy, AllocatorTy, Info &gt;::ConcurrentHashTableByPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a42302ab883ef8ec7e51b00701d626ce4">llvm::dwarf_linker::parallel::DWARFLinkerImpl::link</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aca37fe9da8af401451f8bb3c8241f83d">llvm::parallelFor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a656bf8371e619956b2d9e5f58b2f538e">llvm::parallelSort</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad7c6335c3fb4cf669c835f7b97afb3d5">llvm::parallelTransformReduce</a> and <a href="/web-llvm/docs/api/classes/llvm/parallel/taskgroup/#a383436e232e602a67d0f17c76a97057e">llvm::parallel::TaskGroup::TaskGroup</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/parallel-h">Parallel.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/perthreadbumpptrallocator-h">PerThreadBumpPtrAllocator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/parallel-cpp">Parallel.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
