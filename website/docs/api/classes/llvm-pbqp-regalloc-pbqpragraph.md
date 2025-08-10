---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pbqp/regalloc/pbqpragraph
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PBQPRAGraph` Class



## Declaration

<div class="doxyDeclaration">
class llvm::PBQP::RegAlloc::PBQPRAGraph { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">llvm/CodeGen/RegAllocPBQP.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/graph">Graph&lt;SolverT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph">Graph</a> class. <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93188b97982a9a9ebea2f5c8db896869">BaseT</a> = <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph">PBQP::Graph</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/regallocsolverimpl">RegAllocSolverImpl</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad15cdafc5de2fd787a82bf443d245e7e">PBQPRAGraph</a> (GraphMetadata Metadata)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78abfb6b34e68b227c9e5c7704052df2">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump this graph to <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a>. <a href="#a78abfb6b34e68b227c9e5c7704052df2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d4298b31bb96541c38a77aeaa34b842">dump</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump this graph to an output stream. <a href="#a3d4298b31bb96541c38a77aeaa34b842">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a218c419ead049350c41bad2a6b2669cc">printDot</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print a representation of this graph in <a href="/web-llvm/docs/api/namespaces/llvm/dot">DOT</a> format. <a href="#a218c419ead049350c41bad2a6b2669cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BaseT {#a93188b97982a9a9ebea2f5c8db896869}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::RegAlloc::PBQPRAGraph::BaseT =  PBQP::Graph&lt;RegAllocSolverImpl&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PBQPRAGraph() {#ad15cdafc5de2fd787a82bf443d245e7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PBQP::RegAlloc::PBQPRAGraph::PBQPRAGraph (<a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/#a1b4311ed4a57ef1150d10b23d683e439">GraphMetadata</a> Metadata)</td>
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



<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a78abfb6b34e68b227c9e5c7704052df2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void PBQP::RegAlloc::PBQPRAGraph::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump this graph to <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a>.</p>

<p>Declaration at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>, definition at line 924 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpbqp-cpp">RegAllocPBQP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a03503773241005f01b090b9862aad304">llvm::dump</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

### dump() {#a3d4298b31bb96541c38a77aeaa34b842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void PBQP::RegAlloc::PBQPRAGraph::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump this graph to an output stream.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>Output stream to print on.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>, definition at line 903 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpbqp-cpp">RegAllocPBQP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/#afb740fccb3ee61c6176f946bb22e9b1a">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::edgeIds</a>, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/#a7917827865b8d4c4001a7adc0266eb40">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::getEdgeCosts</a>, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/#a5c5ac6071bfedd2049e3351a3c17ca22">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::getEdgeNode1Id</a>, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/#a55617005b3dfcab29cd97f7efe8a679d">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::getEdgeNode2Id</a>, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/#ae767e0396e22226e0aaf4de035412297">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::getNodeCosts</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/#a84ff7ee5d27c3a8173490fb89d7a7379">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::nodeIds</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpbqp-cpp/#a1166be335294ec092a70278682db3950">PrintNodeInfo</a>.</p>

</div>
</div>

### printDot() {#a218c419ead049350c41bad2a6b2669cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PBQP::RegAlloc::PBQPRAGraph::printDot (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print a representation of this graph in <a href="/web-llvm/docs/api/namespaces/llvm/dot">DOT</a> format.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>Output stream to print on.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>, definition at line 929 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpbqp-cpp">RegAllocPBQP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/#afb740fccb3ee61c6176f946bb22e9b1a">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::edgeIds</a>, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/#a7917827865b8d4c4001a7adc0266eb40">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::getEdgeCosts</a>, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/#a5c5ac6071bfedd2049e3351a3c17ca22">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::getEdgeNode1Id</a>, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/#a55617005b3dfcab29cd97f7efe8a679d">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::getEdgeNode2Id</a>, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/#ae767e0396e22226e0aaf4de035412297">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::getNodeCosts</a>, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/#a84ff7ee5d27c3a8173490fb89d7a7379">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::nodeIds</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpbqp-cpp/#a1166be335294ec092a70278682db3950">PrintNodeInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpbqp-cpp">RegAllocPBQP.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
