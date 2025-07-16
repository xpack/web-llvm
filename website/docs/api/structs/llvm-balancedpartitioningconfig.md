---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/balancedpartitioningconfig
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BalancedPartitioningConfig` Struct Reference

<p>Algorithm parameters; default values are tuned on real-world binaries. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::BalancedPartitioningConfig { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">llvm/Support/BalancedPartitioning.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a70535c05f2cf437b788d7e02a59d76">SplitDepth</a> = 18</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The depth of the recursive bisection. <a href="#a4a70535c05f2cf437b788d7e02a59d76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5c007c3ba8068e408099814e1b3558e">IterationsPerSplit</a> = 40</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum number of bp iterations per split. <a href="#ad5c007c3ba8068e408099814e1b3558e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79b106f6d64abf9f0bcab25728d2bd82">SkipProbability</a> = 0.1f</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The probability for a vertex to skip a move from its current bucket to another bucket; it often helps to escape from a local optima. <a href="#a79b106f6d64abf9f0bcab25728d2bd82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb5f17251e59b20bc5aa876f7c60e0f">TaskSplitDepth</a> = 9</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursive subtasks up to the given depth are added to the queue and distributed among threads by ThreadPool; all subsequent calls are executed on the same thread. <a href="#abbb5f17251e59b20bc5aa876f7c60e0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Algorithm parameters; default values are tuned on real-world binaries.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### IterationsPerSplit {#ad5c007c3ba8068e408099814e1b3558e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BalancedPartitioningConfig::IterationsPerSplit = 40</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The maximum number of bp iterations per split.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>

</div>
</div>

### SkipProbability {#a79b106f6d64abf9f0bcab25728d2bd82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float llvm::BalancedPartitioningConfig::SkipProbability = 0.1f</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The probability for a vertex to skip a move from its current bucket to another bucket; it often helps to escape from a local optima.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>

</div>
</div>

### SplitDepth {#a4a70535c05f2cf437b788d7e02a59d76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BalancedPartitioningConfig::SplitDepth = 18</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The depth of the recursive bisection.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>

</div>
</div>

### TaskSplitDepth {#abbb5f17251e59b20bc5aa876f7c60e0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BalancedPartitioningConfig::TaskSplitDepth = 9</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursive subtasks up to the given depth are added to the queue and distributed among threads by ThreadPool; all subsequent calls are executed on the same thread.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
