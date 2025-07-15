---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/memdgnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MemDGNode` Class Reference

<p>A <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph">DependencyGraph</a> <a href="/web-llvm/docs/api/classes/node">Node</a> for instructions that may read/write memory, or have some ordering constraints, like with stacksave/stackrestore and alloca/inalloca. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::MemDGNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">llvm/Transforms/Vectorize/SandboxVectorizer/DependencyGraph.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode">DGNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph">DependencyGraph</a> <a href="/web-llvm/docs/api/classes/node">Node</a> that points to an <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> and contains memory dependency edges. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af065143585f17219e1066f582fd55021">PredIterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e281b1504ddc5ad8c3fdd3de5fc67e3">DependencyGraph</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaca93c4d946ee53558d24b87a1d131ad">MemDGNode</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode/#a5a092a57c6895926cdc38b5b86d37c12">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d3d14ffce5af497e11ba489b312938c">preds_begin</a> (DependencyGraph &amp;DAG) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode/#a5a092a57c6895926cdc38b5b86d37c12">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a089f843815efa5f6fbc88f1a55409383">preds_end</a> (DependencyGraph &amp;DAG) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad73bb5295e2e89b715d13cd83f35370e">getPrevNode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the previous Mem <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode">DGNode</a> in instruction order. <a href="#ad73bb5295e2e89b715d13cd83f35370e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f4fc05a35f974c411375e46649fd7af">getNextNode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the next Mem <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode">DGNode</a> in instruction order. <a href="#a7f4fc05a35f974c411375e46649fd7af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc30e7d524bb4a48b4f0054fdf4e4487">addMemPred</a> (MemDGNode *PredN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds the mem dependency edge PredN-&gt;this. <a href="#adc30e7d524bb4a48b4f0054fdf4e4487">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29735a2d6ea6cc680b8553d1013e040d">hasMemPred</a> (DGNode *N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns true if there is a memory dependency N-&gt;this. <a href="#a29735a2d6ea6cc680b8553d1013e040d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> * &gt;::const_iterator &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c7e1dacceaa820723fca5c2a15d977">memPreds</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns all memory dependency predecessors. Used by tests. <a href="#a67c7e1dacceaa820723fca5c2a15d977">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98726d4d9fcff82e7518d14b2e6b111a">print</a> (raw_ostream &amp;OS, bool PrintDeps=true) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9375998dbd1099f93a8b58a90029f3ca">setNextNode</a> (MemDGNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates both edges: this&lt;-&gt;N. <a href="#a9375998dbd1099f93a8b58a90029f3ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e43897f37a0f65a5a47c96a6f06cf7c">setPrevNode</a> (MemDGNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates both edges: N&lt;-&gt;this. <a href="#a1e43897f37a0f65a5a47c96a6f06cf7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3859c5fe871ba9770faedbb88c8f9b6a">detachFromChain</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50e383551c8c216e873667473ea972c1">PrevMemN</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a546e632518dc5f186b3335ec35f8df">NextMemN</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6185a7b85865a4507a3ab18096fbcf27">MemPreds</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> predecessors. <a href="#a6185a7b85865a4507a3ab18096fbcf27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ea0a929c3d4b4bb875a19ac00f7aa94">classof</a> (const DGNode *Other)</td>
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

<p>A <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph">DependencyGraph</a> <a href="/web-llvm/docs/api/classes/node">Node</a> for instructions that may read/write memory, or have some ordering constraints, like with stacksave/stackrestore and alloca/inalloca.</p>

<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<div class="doxySectionDef">

## Friends

### DependencyGraph {#a0e281b1504ddc5ad8c3fdd3de5fc67e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph">DependencyGraph</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Reference <a href="#a0e281b1504ddc5ad8c3fdd3de5fc67e3">DependencyGraph</a>.</p>


<p>Referenced by <a href="#a0e281b1504ddc5ad8c3fdd3de5fc67e3">DependencyGraph</a>, <a href="#a1d3d14ffce5af497e11ba489b312938c">preds_begin</a> and <a href="#a089f843815efa5f6fbc88f1a55409383">preds_end</a>.</p>

</div>
</div>

### PredIterator {#af065143585f17219e1066f582fd55021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/prediterator">PredIterator</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="#aaca93c4d946ee53558d24b87a1d131ad">MemDGNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#af065143585f17219e1066f582fd55021">PredIterator</a>.</p>


<p>Referenced by <a href="#af065143585f17219e1066f582fd55021">PredIterator</a>, <a href="#a1d3d14ffce5af497e11ba489b312938c">preds_begin</a> and <a href="#a089f843815efa5f6fbc88f1a55409383">preds_end</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MemDGNode() {#aaca93c4d946ee53558d24b87a1d131ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::MemDGNode::MemDGNode (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode/#a5d180e6958c0349fa578d0fbd3298faa">llvm::sandboxir::DGNode::DGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode/#a476b7ce8aae2be423ff92d723e80c1ff">llvm::sandboxir::DGNode::I</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode/#ac1b89d7c178eb196de3d1f05cc205642">llvm::sandboxir::DGNode::isMemDepNodeCandidate</a> and <a href="#aaca93c4d946ee53558d24b87a1d131ad">MemDGNode</a>.</p>


<p>Referenced by <a href="#adc30e7d524bb4a48b4f0054fdf4e4487">addMemPred</a>, <a href="#a7f4fc05a35f974c411375e46649fd7af">getNextNode</a>, <a href="#ad73bb5295e2e89b715d13cd83f35370e">getPrevNode</a>, <a href="#aaca93c4d946ee53558d24b87a1d131ad">MemDGNode</a> and <a href="#af065143585f17219e1066f582fd55021">PredIterator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addMemPred() {#adc30e7d524bb4a48b4f0054fdf4e4487}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::MemDGNode::addMemPred (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> * PredN)</td>
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

<p>Adds the mem dependency edge PredN-&gt;this.</p>


<p>This also increments the UnscheduledSuccs counter of the predecessor if this node has not been scheduled.</p>


<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aaca93c4d946ee53558d24b87a1d131ad">MemDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode/#ab098cf6863005cd2383e1d347a349fbf">llvm::sandboxir::DGNode::Scheduled</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode/#a7abcb1441a1b337d2be367a2b7cebe9b">llvm::sandboxir::DGNode::UnscheduledSuccs</a>.</p>

</div>
</div>

### getNextNode() {#a7f4fc05a35f974c411375e46649fd7af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDGNode * llvm::sandboxir::MemDGNode::getNextNode ()</td>
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

<p>\Returns the next Mem <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode">DGNode</a> in instruction order.</p>

<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Reference <a href="#aaca93c4d946ee53558d24b87a1d131ad">MemDGNode</a>.</p>

</div>
</div>

### getPrevNode() {#ad73bb5295e2e89b715d13cd83f35370e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDGNode * llvm::sandboxir::MemDGNode::getPrevNode ()</td>
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

<p>\Returns the previous Mem <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode">DGNode</a> in instruction order.</p>

<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Reference <a href="#aaca93c4d946ee53558d24b87a1d131ad">MemDGNode</a>.</p>

</div>
</div>

### hasMemPred() {#a29735a2d6ea6cc680b8553d1013e040d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::MemDGNode::hasMemPred (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode">DGNode</a> * N)</td>
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

<p>\Returns true if there is a memory dependency N-&gt;this.</p>

<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode/#a5d180e6958c0349fa578d0fbd3298faa">llvm::sandboxir::DGNode::DGNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### memPreds() {#a67c7e1dacceaa820723fca5c2a15d977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; DenseSet&lt; MemDGNode * &gt;::const_iterator &gt; llvm::sandboxir::MemDGNode::memPreds ()</td>
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

<p>\Returns all memory dependency predecessors. Used by tests.</p>

<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### preds\_begin() {#a1d3d14ffce5af497e11ba489b312938c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::sandboxir::MemDGNode::preds_begin (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph">DependencyGraph</a> &amp; DAG)</td>
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



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="#a0e281b1504ddc5ad8c3fdd3de5fc67e3">DependencyGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode/#a476b7ce8aae2be423ff92d723e80c1ff">llvm::sandboxir::DGNode::I</a>, <a href="#af065143585f17219e1066f582fd55021">PredIterator</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#aa24cfbd52340fdfc1d9d0a9b41e45226">llvm::sandboxir::skipNonInstr</a>.</p>

</div>
</div>

### preds\_end() {#a089f843815efa5f6fbc88f1a55409383}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::sandboxir::MemDGNode::preds_end (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph">DependencyGraph</a> &amp; DAG)</td>
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



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="#a0e281b1504ddc5ad8c3fdd3de5fc67e3">DependencyGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode/#a476b7ce8aae2be423ff92d723e80c1ff">llvm::sandboxir::DGNode::I</a> and <a href="#af065143585f17219e1066f582fd55021">PredIterator</a>.</p>

</div>
</div>

### print() {#a98726d4d9fcff82e7518d14b2e6b111a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::MemDGNode::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool PrintDeps=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode/#a1d55236dec78bc0420e7d86e78f5518a">llvm::sandboxir::DGNode::print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### detachFromChain() {#a3859c5fe871ba9770faedbb88c8f9b6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::MemDGNode::detachFromChain ()</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

</div>
</div>

### setNextNode() {#a9375998dbd1099f93a8b58a90029f3ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::MemDGNode::setNextNode (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> * N)</td>
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

<p>Creates both edges: this&lt;-&gt;N.</p>

<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

</div>
</div>

### setPrevNode() {#a1e43897f37a0f65a5a47c96a6f06cf7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::MemDGNode::setPrevNode (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> * N)</td>
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

<p>Creates both edges: N&lt;-&gt;this.</p>

<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MemPreds {#a6185a7b85865a4507a3ab18096fbcf27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;MemDGNode *&gt; llvm::sandboxir::MemDGNode::MemPreds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> predecessors.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

</div>
</div>

### NextMemN {#a0a546e632518dc5f186b3335ec35f8df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDGNode* llvm::sandboxir::MemDGNode::NextMemN = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

</div>
</div>

### PrevMemN {#a50e383551c8c216e873667473ea972c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDGNode* llvm::sandboxir::MemDGNode::PrevMemN = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a3ea0a929c3d4b4bb875a19ac00f7aa94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::MemDGNode::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode">DGNode</a> * Other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode/#a5d180e6958c0349fa578d0fbd3298faa">llvm::sandboxir::DGNode::DGNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#af59141b63a92961900cf61ba28262920ae2c37acea7f8d715a2115d6c350fe724">llvm::sandboxir::MemDGNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
