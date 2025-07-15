---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/defaultpriorityadvisor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DefaultPriorityAdvisor` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::DefaultPriorityAdvisor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">CodeGen/RegAllocPriorityAdvisor.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regallocpriorityadvisor">RegAllocPriorityAdvisor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface to the priority advisor, which is responsible for prioritizing live ranges. <a href="/web-llvm/docs/api/classes/llvm/regallocpriorityadvisor/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b56a26431d84ec4b815ad8f2c9c171f">DefaultPriorityAdvisor</a> (const MachineFunction &amp;MF, const RAGreedy &amp;RA, SlotIndexes *const Indexes)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81d74832694588ee01cfcef575ec45a3">getPriority</a> (const LiveInterval &amp;LI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the priority value for a live range. <a href="#a81d74832694588ee01cfcef575ec45a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DefaultPriorityAdvisor() {#a6b56a26431d84ec4b815ad8f2c9c171f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DefaultPriorityAdvisor::DefaultPriorityAdvisor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ragreedy">RAGreedy</a> &amp; RA, <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Indexes)</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/regallocpriorityadvisor/#aa0d874faa48e46514c877bd65bd0c2cd">llvm::RegAllocPriorityAdvisor::Indexes</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocpriorityadvisor/#abf987014e5e42fb7b026f07f6531c4e6">llvm::RegAllocPriorityAdvisor::RA</a> and <a href="/web-llvm/docs/api/classes/llvm/regallocpriorityadvisor/#a24f50907e5573ee63e225caf72e35673">llvm::RegAllocPriorityAdvisor::RegAllocPriorityAdvisor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getPriority() {#a81d74832694588ee01cfcef575ec45a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DefaultPriorityAdvisor::getPriority (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the priority value for a live range.</p>


<p>A float value is used since ML prefers it.</p>


<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a>, definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp">RegAllocGreedy.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpriorityadvisor-h">RegAllocPriorityAdvisor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
