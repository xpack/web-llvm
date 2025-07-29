---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-siloweri1copies-cpp-/phiincominganalysis
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PhiIncomingAnalysis` Class

<p>Helper class that determines the relationship between incoming values of a phi in the control flow graph to determine where an incoming value can simply be taken as a scalar lane mask as-is, and where it needs to be merged with another, previously defined lane mask. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{SILowerI1Copies.cpp}::PhiIncomingAnalysis { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb21aa4a6197f05bf7b9184f7a44378a">PhiIncomingAnalysis</a> (MachinePostDominatorTree &amp;PDT, const SIInstrInfo *TII)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04fa6c6f78b872bc118732b77ec5ae3f">isSource</a> (MachineBasicBlock &amp;MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether <span class="doxyComputerOutput">MBB</span> is a source in the induced subgraph of reachable blocks. <a href="#a04fa6c6f78b872bc118732b77ec5ae3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a218325d9a800abec0379d5d7fe8c14fb">predecessors</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a223f44f36f65f70b6e7f23b59baffd15">analyze</a> (MachineBasicBlock &amp;DefBlock, ArrayRef&lt; Incoming &gt; Incomings)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortree">MachinePostDominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c2dd599a3f90a04f75792da4e59e782">PDT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d4d390327b2fc61014616c159ffc214">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28dca0773176296a2dfd5372bc6d6514">ReachableMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8a1a101935ab1120cfae7f26a28667d">ReachableOrdered</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a233c26c953d71a3e68f55cc7860f10d1">Stack</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1113df9efb8ba98a43a16c59d9a1eb50">Predecessors</a></td>
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

<p>Helper class that determines the relationship between incoming values of a phi in the control flow graph to determine where an incoming value can simply be taken as a scalar lane mask as-is, and where it needs to be merged with another, previously defined lane mask.</p>


<p>The approach is as follows:</p>


<ul class="doxyList ">
<li>Determine all basic blocks which, starting from the incoming blocks, a wave may reach before entering the def block (the block containing the phi).</li>
<li>If an incoming block has no predecessors in this set, we can take the incoming value as a scalar lane mask as-is. – A special case of this is when the def block has a self-loop.</li>
<li>Otherwise, the incoming value needs to be merged with a previously defined lane mask.</li>
<li>If there is a path into the set of reachable blocks that does <em>not</em> go through an incoming block where we can take the scalar lane mask as-is, we need to invent an available value for the <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a>. Choices are 0 and undef, with differing consequences for how to merge values etc.</li>
</ul>

<p>TODO: We could use region analysis to quickly skip over SESE regions during the traversal.</p>


<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PhiIncomingAnalysis() {#abb21aa4a6197f05bf7b9184f7a44378a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SILowerI1Copies.cpp}::PhiIncomingAnalysis::PhiIncomingAnalysis (<a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortree">MachinePostDominatorTree</a> &amp; PDT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> * TII)</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### analyze() {#a223f44f36f65f70b6e7f23b59baffd15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SILowerI1Copies.cpp}::PhiIncomingAnalysis::analyze (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; DefBlock, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/incoming">Incoming</a> &gt; Incomings)</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/incoming/#abff0731632db5e52bc5ea3fdba5dbd8d">llvm::Incoming::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3b1dce1f3354a357fb9061bb7568a84e">llvm::MachineBasicBlock::push_back</a>.</p>

</div>
</div>

### isSource() {#a04fa6c6f78b872bc118732b77ec5ae3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SILowerI1Copies.cpp}::PhiIncomingAnalysis::isSource (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p>Returns whether <span class="doxyComputerOutput">MBB</span> is a source in the induced subgraph of reachable blocks.</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### predecessors() {#a218325d9a800abec0379d5d7fe8c14fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MachineBasicBlock * &gt; anonymous{SILowerI1Copies.cpp}::PhiIncomingAnalysis::predecessors ()</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### PDT {#a6c2dd599a3f90a04f75792da4e59e782}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachinePostDominatorTree&amp; anonymous{SILowerI1Copies.cpp}::PhiIncomingAnalysis::PDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

### Predecessors {#a1113df9efb8ba98a43a16c59d9a1eb50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineBasicBlock *, 4&gt; anonymous{SILowerI1Copies.cpp}::PhiIncomingAnalysis::Predecessors</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

### ReachableMap {#a28dca0773176296a2dfd5372bc6d6514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineBasicBlock *, bool&gt; anonymous{SILowerI1Copies.cpp}::PhiIncomingAnalysis::ReachableMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

### ReachableOrdered {#af8a1a101935ab1120cfae7f26a28667d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineBasicBlock *, 4&gt; anonymous{SILowerI1Copies.cpp}::PhiIncomingAnalysis::ReachableOrdered</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

### Stack {#a233c26c953d71a3e68f55cc7860f10d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineBasicBlock *, 4&gt; anonymous{SILowerI1Copies.cpp}::PhiIncomingAnalysis::Stack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

### TII {#a0d4d390327b2fc61014616c159ffc214}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIInstrInfo* anonymous{SILowerI1Copies.cpp}::PhiIncomingAnalysis::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
