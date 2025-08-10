---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-regallocpbqp-cpp-/spillcosts
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SpillCosts` Class

<p>Set spill costs for each node in the <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> reg-alloc graph. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{RegAllocPBQP.cpp}::SpillCosts { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqpraconstraint">PBQPRAConstraint</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract base for classes implementing <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> register allocation constraints (e.g. <a href="/web-llvm/docs/api/classes/llvm/pbqpraconstraint/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a1e3c936c56e8a7424d8bd2f4265cb">apply</a> (PBQPRAGraph &amp;G) override</td>
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

<p>Set spill costs for each node in the <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> reg-alloc graph.</p>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpbqp-cpp">RegAllocPBQP.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### apply() {#a24a1e3c936c56e8a7424d8bd2f4265cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RegAllocPBQP.cpp}::SpillCosts::apply (<a href="/web-llvm/docs/api/namespaces/llvm/#a3e50e01d41081a45d6a7f23af6b52df2">PBQPRAGraph</a> &amp; G)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpbqp-cpp">RegAllocPBQP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a8208eacaf02c9742c8ed7f09ec0837f3">llvm::LiveIntervals::getInterval</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pbqp/regalloc/#acf6e46dd5dbc447eece534e9ce368945">llvm::PBQP::RegAlloc::getSpillOptionIdx</a> and <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a0fc46dffc68d1302d150b7e4c28c7983">llvm::LiveInterval::weight</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpbqp-cpp">RegAllocPBQP.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
