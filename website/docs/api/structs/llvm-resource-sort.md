---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/resource-sort
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `resource_sort` Struct Reference

<p>Sorting functions for the Available queue. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::resource_sort { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/resourcepriorityqueue-h">llvm/CodeGen/ResourcePriorityQueue.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af48e499d46375fb1f8530d0c6f60f5f9">resource_sort</a> (ResourcePriorityQueue *pq)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa725f68ef029c25d5053a02441e6d638">operator()</a> (const SUnit *LHS, const SUnit *RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This heuristic is used if DFA scheduling is not desired for some VLIW platform. <a href="#aa725f68ef029c25d5053a02441e6d638">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue">ResourcePriorityQueue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab06712680bebdfe0b21e275cf7c0a377">PQ</a></td>
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

<p>Sorting functions for the Available queue.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/resourcepriorityqueue-h">ResourcePriorityQueue.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### resource\_sort() {#af48e499d46375fb1f8530d0c6f60f5f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::resource_sort::resource_sort (<a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue">ResourcePriorityQueue</a> * pq)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/resourcepriorityqueue-h">ResourcePriorityQueue.h</a>.</p>


<p>Reference <a href="#ab06712680bebdfe0b21e275cf7c0a377">PQ</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator()() {#aa725f68ef029c25d5053a02441e6d638}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool resource_sort::operator() (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This heuristic is used if DFA scheduling is not desired for some VLIW platform.</p>

<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/resourcepriorityqueue-h">ResourcePriorityQueue.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/resourcepriorityqueue-cpp">ResourcePriorityQueue.cpp</a>.</p>


<p>Reference <a href="#ab06712680bebdfe0b21e275cf7c0a377">PQ</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### PQ {#ab06712680bebdfe0b21e275cf7c0a377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResourcePriorityQueue* llvm::resource_sort::PQ</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/resourcepriorityqueue-h">ResourcePriorityQueue.h</a>.</p>


<p>Referenced by <a href="#aa725f68ef029c25d5053a02441e6d638">operator()</a> and <a href="#af48e499d46375fb1f8530d0c6f60f5f9">resource_sort</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/resourcepriorityqueue-h">ResourcePriorityQueue.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/resourcepriorityqueue-cpp">ResourcePriorityQueue.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
