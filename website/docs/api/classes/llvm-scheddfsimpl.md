---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/scheddfsimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SchedDFSImpl` Class Reference

<p>Internal state used to compute <a href="/web-llvm/docs/api/classes/llvm/scheddfsresult">SchedDFSResult</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SchedDFSImpl { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affd919da23161b67d177f3bd8c07b012">SchedDFSImpl</a> (SchedDFSResult &amp;r)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ab4e29b1b9ebb256c6ec991a487f25">isVisited</a> (const SUnit *SU) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this node been visited by the DFS traversal. <a href="#af9ab4e29b1b9ebb256c6ec991a487f25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee17a5350fad1c56abf6f425ef4f6e92">visitPreorder</a> (const SUnit *SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initializes this node's instruction count. <a href="#aee17a5350fad1c56abf6f425ef4f6e92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19e83509e45ee65e4495de5a3ed3d44a">visitPostorderNode</a> (const SUnit *SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called once for each node after all predecessors are visited. <a href="#a19e83509e45ee65e4495de5a3ed3d44a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae259d5b34969a9259dbc66324869c398">visitPostorderEdge</a> (const SDep &amp;PredDep, const SUnit *Succ)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called once for each tree edge after calling visitPostOrderNode on the predecessor. <a href="#ae259d5b34969a9259dbc66324869c398">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd2c96b0f28a1d6e444286a24bdf48f7">visitCrossEdge</a> (const SDep &amp;PredDep, const SUnit *Succ)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a connection for cross edges. <a href="#abd2c96b0f28a1d6e444286a24bdf48f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab97b865e6e2092381b77a6c9bc3aa421">finalize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets each node's subtree <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to the representative <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> and record connections between trees. <a href="#ab97b865e6e2092381b77a6c9bc3aa421">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a616fae155ac2f266346edbb5411470">joinPredSubtree</a> (const SDep &amp;PredDep, const SUnit *Succ, bool CheckLimit=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Joins the predecessor subtree with the successor that is its DFS parent. <a href="#a8a616fae155ac2f266346edbb5411470">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1de1afa4c08361317bce0e400922326">addConnection</a> (unsigned FromTree, unsigned ToTree, unsigned Depth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called by <a href="#ab97b865e6e2092381b77a6c9bc3aa421">finalize()</a> to record a connection between trees. <a href="#aa1de1afa4c08361317bce0e400922326">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheddfsresult">SchedDFSResult</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79c4d3d2e6b93c0846bef03a2cf51b43">R</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inteqclasses">IntEqClasses</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5ef0fbcd0fea1e42251dfcc47f9e040">SubtreeClasses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Join DAG nodes into equivalence classes by their subtree. <a href="#ac5ef0fbcd0fea1e42251dfcc47f9e040">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bc773d9110af1fea218f935e11e57ff">ConnectionPairs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List PredSU, SuccSU pairs that represent data edges between subtrees. <a href="#a2bc773d9110af1fea218f935e11e57ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a>&lt; RootData &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d16baa56487693ab968bccd07247082">RootSet</a></td>
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

<p>Internal state used to compute <a href="/web-llvm/docs/api/classes/llvm/scheddfsresult">SchedDFSResult</a>.</p>

<p>Definition at line 1239 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SchedDFSImpl() {#affd919da23161b67d177f3bd8c07b012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SchedDFSImpl::SchedDFSImpl (<a href="/web-llvm/docs/api/classes/llvm/scheddfsresult">SchedDFSResult</a> &amp; r)</td>
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



<p>Definition at line 1262 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### finalize() {#ab97b865e6e2092381b77a6c9bc3aa421}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SchedDFSImpl::finalize ()</td>
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

<p>Sets each node's subtree <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to the representative <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> and record connections between trees.</p>

<p>Definition at line 1340 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="#aa1de1afa4c08361317bce0e400922326">addConnection</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### isVisited() {#af9ab4e29b1b9ebb256c6ec991a487f25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SchedDFSImpl::isVisited (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>Returns true if this node been visited by the DFS traversal.</p>


<p>During visitPostorderNode the <a href="/web-llvm/docs/api/classes/node">Node</a>'s SubtreeID is assigned to the <a href="/web-llvm/docs/api/classes/node">Node</a> <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. Later, SubtreeID is updated but remains valid.</p>


<p>Definition at line 1270 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>.</p>

</div>
</div>

### visitCrossEdge() {#abd2c96b0f28a1d6e444286a24bdf48f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SchedDFSImpl::visitCrossEdge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; PredDep, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * Succ)</td>
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

<p>Adds a connection for cross edges.</p>

<p>Definition at line 1334 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>.</p>

</div>
</div>

### visitPostorderEdge() {#ae259d5b34969a9259dbc66324869c398}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SchedDFSImpl::visitPostorderEdge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; PredDep, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * Succ)</td>
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

<p>Called once for each tree edge after calling visitPostOrderNode on the predecessor.</p>


<p>Increment the parent node's instruction count and preemptively join this subtree to its parent's if it is small enough.</p>


<p>Definition at line 1327 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>, <a href="#a8a616fae155ac2f266346edbb5411470">joinPredSubtree</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>.</p>

</div>
</div>

### visitPostorderNode() {#a19e83509e45ee65e4495de5a3ed3d44a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SchedDFSImpl::visitPostorderNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>Called once for each node after all predecessors are visited.</p>


<p>Revisit this node's predecessors and potentially join them now that we know the ILP of the other predecessors.</p>


<p>Definition at line 1285 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a055c65558a3e0f7d48f1ed3dde061199">llvm::SDep::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/dfapacketizer-cpp/#acc16edf21eddec420cd4b27adb3111c6">InstrCount</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#acaeaa72d4f5f8423ebade5ac38060b42">llvm::MachineInstr::isTransient</a>, <a href="#a8a616fae155ac2f266346edbb5411470">joinPredSubtree</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a>.</p>

</div>
</div>

### visitPreorder() {#aee17a5350fad1c56abf6f425ef4f6e92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SchedDFSImpl::visitPreorder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
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

<p>Initializes this node's instruction count.</p>


<p>We don't need to flag the node visited until visitPostorder because the DAG cannot have cycles.</p>


<p>Definition at line 1277 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#acaeaa72d4f5f8423ebade5ac38060b42">llvm::MachineInstr::isTransient</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addConnection() {#aa1de1afa4c08361317bce0e400922326}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SchedDFSImpl::addConnection (unsigned FromTree, unsigned ToTree, unsigned Depth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Called by <a href="#ab97b865e6e2092381b77a6c9bc3aa421">finalize()</a> to record a connection between trees.</p>

<p>Definition at line 1404 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#ab97b865e6e2092381b77a6c9bc3aa421">finalize</a>.</p>

</div>
</div>

### joinPredSubtree() {#a8a616fae155ac2f266346edbb5411470}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SchedDFSImpl::joinPredSubtree (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdep">SDep</a> &amp; PredDep, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * Succ, bool CheckLimit=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Joins the predecessor subtree with the successor that is its DFS parent.</p>


<p>Applies some heuristics before joining.</p>


<p>Definition at line 1377 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a055c65558a3e0f7d48f1ed3dde061199">llvm::SDep::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#aab4a86c51e6b126c9c6ef58dbb574431">llvm::SUnit::Succs</a>.</p>


<p>Referenced by <a href="#ae259d5b34969a9259dbc66324869c398">visitPostorderEdge</a> and <a href="#a19e83509e45ee65e4495de5a3ed3d44a">visitPostorderNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ConnectionPairs {#a2bc773d9110af1fea218f935e11e57ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;const SUnit *, const SUnit*&gt; &gt; llvm::SchedDFSImpl::ConnectionPairs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List PredSU, SuccSU pairs that represent data edges between subtrees.</p>

<p>Definition at line 1245 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>

</div>
</div>

### R {#a79c4d3d2e6b93c0846bef03a2cf51b43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SchedDFSResult&amp; llvm::SchedDFSImpl::R</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1240 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>

</div>
</div>

### RootSet {#a7d16baa56487693ab968bccd07247082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparseSet&lt;RootData&gt; llvm::SchedDFSImpl::RootSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1259 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>

</div>
</div>

### SubtreeClasses {#ac5ef0fbcd0fea1e42251dfcc47f9e040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntEqClasses llvm::SchedDFSImpl::SubtreeClasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Join DAG nodes into equivalence classes by their subtree.</p>

<p>Definition at line 1243 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
