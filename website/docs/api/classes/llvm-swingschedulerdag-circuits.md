---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/swingschedulerdag/circuits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Circuits` Class

<p>Helper class to implement Johnson's circuit finding algorithm. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SwingSchedulerDAG::Circuits { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeb7caeaf9ed8038d82a82e8be361d2c">Circuits</a> (std::vector&lt; SUnit &gt; &amp;SUs, ScheduleDAGTopologicalSort &amp;Topo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa08b78cad65fc5d33d42a1a037dfcf36">Circuits</a> (const Circuits &amp;other)=delete</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae394ed10f8938d86f66cb8f6a816256c">~Circuits</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Circuits &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a741d120d1ea6ddcdb6b9e767a3ab4318">operator=</a> (const Circuits &amp;other)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab54c220b6716ea483f6ccae2051df75d">reset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset the data structures used in the circuit algorithm. <a href="#ab54c220b6716ea483f6ccae2051df75d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c38274bdd578f76312898a436134a59">createAdjacencyStructure</a> (SwingSchedulerDAG *DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the adjacency structure of the nodes in the graph. <a href="#a3c38274bdd578f76312898a436134a59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6acea28a08510210f27b963ac686cc53">circuit</a> (int V, int S, NodeSetType &amp;NodeSets, const SwingSchedulerDAG *DAG, bool HasBackedge=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify an elementary circuit in the dependence graph starting at the specified node. <a href="#a6acea28a08510210f27b963ac686cc53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90125290a257c6d2cf684eedd5e892c0">unblock</a> (int U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unblock a node in the circuit finding algorithm. <a href="#a90125290a257c6d2cf684eedd5e892c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab45067501c44d60a2c64b889d167fa43">SUnits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6acc0309925a386d999c598e702abb22">Stack</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4a2c36473f0b194b7c6b898996bf8ab">Blocked</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *, 4 &gt;, 10 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59961a09c56f530fc189c806ff46af17">B</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int, 4 &gt;, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae981debcdf9327465bd957c9b97217b4">AdjK</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; int &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b0b9145267eff19b3e45330a0c02858">Node2Idx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6d15e81d2a78caa9b68319000414494">NumPaths</a> = 0u</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad912c7ae51b792108b04dbd998da812c">MaxPaths</a> = 5</td>
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

<p>Helper class to implement Johnson's circuit finding algorithm.</p>

<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Circuits() {#aaeb7caeaf9ed8038d82a82e8be361d2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SwingSchedulerDAG::Circuits::Circuits (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &gt; &amp; SUs, <a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort">ScheduleDAGTopologicalSort</a> &amp; Topo)</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### Circuits() {#aa08b78cad65fc5d33d42a1a037dfcf36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SwingSchedulerDAG::Circuits::Circuits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Circuits &amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Circuits() {#ae394ed10f8938d86f66cb8f6a816256c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SwingSchedulerDAG::Circuits::~Circuits ()</td>
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



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a741d120d1ea6ddcdb6b9e767a3ab4318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Circuits &amp; llvm::SwingSchedulerDAG::Circuits::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Circuits &amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### circuit() {#a6acea28a08510210f27b963ac686cc53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SwingSchedulerDAG::Circuits::circuit (int V, int S, <a href="/web-llvm/docs/api/classes/llvm/smallvector">NodeSetType</a> &amp; NodeSets, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag">SwingSchedulerDAG</a> * DAG, bool HasBackedge=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identify an elementary circuit in the dependence graph starting at the specified node.</p>

<p>Declaration at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 1653 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>

</div>
</div>

### createAdjacencyStructure() {#a3c38274bdd578f76312898a436134a59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SwingSchedulerDAG::Circuits::createAdjacencyStructure (<a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag">SwingSchedulerDAG</a> * DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create the adjacency structure of the nodes in the graph.</p>

<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 1588 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>

</div>
</div>

### reset() {#ab54c220b6716ea483f6ccae2051df75d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SwingSchedulerDAG::Circuits::reset ()</td>
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

<p>Reset the data structures used in the circuit algorithm.</p>

<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### unblock() {#a90125290a257c6d2cf684eedd5e892c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SwingSchedulerDAG::Circuits::unblock (int U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unblock a node in the circuit finding algorithm.</p>

<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 1694 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AdjK {#ae981debcdf9327465bd957c9b97217b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SmallVector&lt;int, 4&gt;, 16&gt; llvm::SwingSchedulerDAG::Circuits::AdjK</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### B {#a59961a09c56f530fc189c806ff46af17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SmallPtrSet&lt;SUnit *, 4&gt;, 10&gt; llvm::SwingSchedulerDAG::Circuits::B</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### Blocked {#ae4a2c36473f0b194b7c6b898996bf8ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::SwingSchedulerDAG::Circuits::Blocked</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### Node2Idx {#a8b0b9145267eff19b3e45330a0c02858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;int&gt;* llvm::SwingSchedulerDAG::Circuits::Node2Idx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### NumPaths {#ab6d15e81d2a78caa9b68319000414494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SwingSchedulerDAG::Circuits::NumPaths = 0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### Stack {#a6acc0309925a386d999c598e702abb22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt;SUnit *&gt; llvm::SwingSchedulerDAG::Circuits::Stack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### SUnits {#ab45067501c44d60a2c64b889d167fa43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SUnit&gt;&amp; llvm::SwingSchedulerDAG::Circuits::SUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### MaxPaths {#ad912c7ae51b792108b04dbd998da812c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SwingSchedulerDAG::Circuits::MaxPaths = 5</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
