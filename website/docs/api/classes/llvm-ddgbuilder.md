---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ddgbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DDGBuilder` Class Reference

<p>Concrete implementation of a pure data dependence graph builder. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DDGBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">llvm/Analysis/DDG.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder">AbstractDependenceGraphBuilder&lt;GraphType&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This abstract builder class defines a set of high-level steps for creating DDG-like graphs. <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62f64b4d223684f143c63956473759c7">DDGBuilder</a> (DataDependenceGraph &amp;G, DependenceInfo &amp;D, const BasicBlockListType &amp;BBs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a747e73c6c04373e9b74124ed2a107">createRootNode</a> () final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the root node of the graph. <a href="#a97a747e73c6c04373e9b74124ed2a107">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57591018466a76e11fd3cadceea418cf">createFineGrainedNode</a> (Instruction &amp;I) final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an atomic node in the graph given a single instruction. <a href="#a57591018466a76e11fd3cadceea418cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a196700d3ee334c18a710c4e6d51531a3">createPiBlock</a> (const NodeListType &amp;L) final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a pi-block node in the graph representing a group of nodes in an SCC of the graph. <a href="#a196700d3ee334c18a710c4e6d51531a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ddgedge">DDGEdge</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac33b5c8d5ecff5ef5c65e4265eaefe84">createDefUseEdge</a> (DDGNode &amp;Src, DDGNode &amp;Tgt) final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a def-use edge going from <span class="doxyComputerOutput">Src</span> to <span class="doxyComputerOutput">Tgt</span>. <a href="#ac33b5c8d5ecff5ef5c65e4265eaefe84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ddgedge">DDGEdge</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a764b798b08a46865837f0754ceeb06fb">createMemoryEdge</a> (DDGNode &amp;Src, DDGNode &amp;Tgt) final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a memory dependence edge going from <span class="doxyComputerOutput">Src</span> to <span class="doxyComputerOutput">Tgt</span>. <a href="#a764b798b08a46865837f0754ceeb06fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ddgedge">DDGEdge</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a919b0b88ee4f3927bf9b41275dacd095">createRootedEdge</a> (DDGNode &amp;Src, DDGNode &amp;Tgt) final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a rooted edge going from <span class="doxyComputerOutput">Src</span> to <span class="doxyComputerOutput">Tgt</span> . <a href="#a919b0b88ee4f3927bf9b41275dacd095">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#ac6158af6f5ec713149c0547d07d6cabe">NodeListType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e4484d16aab57829b9d4b17d08ae959">getNodesInPiBlock</a> (const DDGNode &amp;N) final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a pi-block node, return a vector of all the nodes contained within it. <a href="#a9e4484d16aab57829b9d4b17d08ae959">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16fd25a9c287f12160c42cf158a4ef01">areNodesMergeable</a> (const DDGNode &amp;Src, const DDGNode &amp;Tgt) const final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the two nodes \pSrc and \pTgt are both simple nodes and the consecutive instructions after merging belong to the same basic block. <a href="#a16fd25a9c287f12160c42cf158a4ef01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbb8f28825fc0fea6623b3cde808262a">mergeNodes</a> (DDGNode &amp;Src, DDGNode &amp;Tgt) final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append the content of node <span class="doxyComputerOutput">B</span> into node <span class="doxyComputerOutput">A</span> and remove <span class="doxyComputerOutput">B</span> and the edge between <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> from the graph. <a href="#afbb8f28825fc0fea6623b3cde808262a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af466c259b082a4b93ec0ff04109c433e">shouldSimplify</a> () const final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if graph simplification step is requested, and false otherwise. <a href="#af466c259b082a4b93ec0ff04109c433e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eaac6afc378c33dc60026f02b47632c">shouldCreatePiBlocks</a> () const final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if creation of pi-blocks are supported and desired, and false otherwise. <a href="#a6eaac6afc378c33dc60026f02b47632c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Concrete implementation of a pure data dependence graph builder.</p>


<p>This class provides custom implementation for the pure-virtual functions used in the generic dependence graph build algorithm.</p>


<p>For information about time complexity of the build algorithm see the comments near the declaration of <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder">AbstractDependenceGraphBuilder</a>.</p>


<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DDGBuilder() {#a62f64b4d223684f143c63956473759c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DDGBuilder::DDGBuilder (<a href="/web-llvm/docs/api/classes/llvm/datadependencegraph">DataDependenceGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo">DependenceInfo</a> &amp; D, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#a3b2bdc5e87a8bb28088f7af9ec9201ab">BasicBlockListType</a> &amp; BBs)</td>
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



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#a7b91f6ee87fdd6c6992b19918a51a8fc">llvm::AbstractDependenceGraphBuilder&lt; DataDependenceGraph &gt;::AbstractDependenceGraphBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### areNodesMergeable() {#a16fd25a9c287f12160c42cf158a4ef01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DDGBuilder::areNodesMergeable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp; Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp; Tgt)</td>
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

<p>Return true if the two nodes \pSrc and \pTgt are both simple nodes and the consecutive instructions after merging belong to the same basic block.</p>

<p>Declaration at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>, definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ddg-cpp">DDG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

### createDefUseEdge() {#ac33b5c8d5ecff5ef5c65e4265eaefe84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DDGEdge &amp; llvm::DDGBuilder::createDefUseEdge (<a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp; Tgt)</td>
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

<p>Create a def-use edge going from <span class="doxyComputerOutput">Src</span> to <span class="doxyComputerOutput">Tgt</span>.</p>

<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#adfe1af074dc71e900744bf6e4fbe3356">llvm::AbstractDependenceGraphBuilder&lt; DataDependenceGraph &gt;::Graph</a> and <a href="/web-llvm/docs/api/classes/llvm/ddgedge/#a3778f36f0b9f1e346196a8f8e60a833ba2bf1e50cea889e4d706461e22789089b">llvm::DDGEdge::RegisterDefUse</a>.</p>

</div>
</div>

### createFineGrainedNode() {#a57591018466a76e11fd3cadceea418cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DDGNode &amp; llvm::DDGBuilder::createFineGrainedNode (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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

<p>Create an atomic node in the graph given a single instruction.</p>

<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#adfe1af074dc71e900744bf6e4fbe3356">llvm::AbstractDependenceGraphBuilder&lt; DataDependenceGraph &gt;::Graph</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### createMemoryEdge() {#a764b798b08a46865837f0754ceeb06fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DDGEdge &amp; llvm::DDGBuilder::createMemoryEdge (<a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp; Tgt)</td>
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

<p>Create a memory dependence edge going from <span class="doxyComputerOutput">Src</span> to <span class="doxyComputerOutput">Tgt</span>.</p>

<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#adfe1af074dc71e900744bf6e4fbe3356">llvm::AbstractDependenceGraphBuilder&lt; DataDependenceGraph &gt;::Graph</a> and <a href="/web-llvm/docs/api/classes/llvm/ddgedge/#a3778f36f0b9f1e346196a8f8e60a833bad307e4a4462ecd7b9733b088e912df5c">llvm::DDGEdge::MemoryDependence</a>.</p>

</div>
</div>

### createPiBlock() {#a196700d3ee334c18a710c4e6d51531a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DDGNode &amp; llvm::DDGBuilder::createPiBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#ac6158af6f5ec713149c0547d07d6cabe">NodeListType</a> &amp; L)</td>
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

<p>Create a pi-block node in the graph representing a group of nodes in an SCC of the graph.</p>

<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#adfe1af074dc71e900744bf6e4fbe3356">llvm::AbstractDependenceGraphBuilder&lt; DataDependenceGraph &gt;::Graph</a>.</p>

</div>
</div>

### createRootedEdge() {#a919b0b88ee4f3927bf9b41275dacd095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DDGEdge &amp; llvm::DDGBuilder::createRootedEdge (<a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp; Tgt)</td>
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

<p>Create a rooted edge going from <span class="doxyComputerOutput">Src</span> to <span class="doxyComputerOutput">Tgt</span> .</p>

<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#adfe1af074dc71e900744bf6e4fbe3356">llvm::AbstractDependenceGraphBuilder&lt; DataDependenceGraph &gt;::Graph</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/ddgedge/#a3778f36f0b9f1e346196a8f8e60a833ba4e09d3aae9ff4b3949f387da86f7519c">llvm::DDGEdge::Rooted</a>.</p>

</div>
</div>

### createRootNode() {#a97a747e73c6c04373e9b74124ed2a107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DDGNode &amp; llvm::DDGBuilder::createRootNode ()</td>
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

<p>Create the root node of the graph.</p>

<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#adfe1af074dc71e900744bf6e4fbe3356">llvm::AbstractDependenceGraphBuilder&lt; DataDependenceGraph &gt;::Graph</a>.</p>

</div>
</div>

### getNodesInPiBlock() {#a9e4484d16aab57829b9d4b17d08ae959}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NodeListType &amp; llvm::DDGBuilder::getNodesInPiBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp; N)</td>
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

<p>Given a pi-block node, return a vector of all the nodes contained within it.</p>

<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### mergeNodes() {#afbb8f28825fc0fea6623b3cde808262a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DDGBuilder::mergeNodes (<a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/ddgnode">DDGNode</a> &amp; B)</td>
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

<p>Append the content of node <span class="doxyComputerOutput">B</span> into node <span class="doxyComputerOutput">A</span> and remove <span class="doxyComputerOutput">B</span> and the edge between <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> from the graph.</p>

<p>Declaration at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ddg-cpp">DDG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#a0d2445b044da844555d1f25db33979ce">llvm::AbstractDependenceGraphBuilder&lt; DataDependenceGraph &gt;::destroyEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#ab95e08bc6b6b4d0e95caada63521ad6d">llvm::AbstractDependenceGraphBuilder&lt; DataDependenceGraph &gt;::destroyNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dgedge/#a8455b66c2ed8311421b4168986a83f42">llvm::DGEdge&lt; NodeType, EdgeType &gt;::getTargetNode</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#adfe1af074dc71e900744bf6e4fbe3356">llvm::AbstractDependenceGraphBuilder&lt; DataDependenceGraph &gt;::Graph</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### shouldCreatePiBlocks() {#a6eaac6afc378c33dc60026f02b47632c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DDGBuilder::shouldCreatePiBlocks ()</td>
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

<p>Return true if creation of pi-blocks are supported and desired, and false otherwise.</p>

<p>Declaration at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>, definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ddg-cpp">DDG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/ddg-cpp/#a3cf39484d04dc2d164e808150fde0296">CreatePiBlocks</a>.</p>

</div>
</div>

### shouldSimplify() {#af466c259b082a4b93ec0ff04109c433e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DDGBuilder::shouldSimplify ()</td>
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

<p>Return true if graph simplification step is requested, and false otherwise.</p>

<p>Declaration at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a>, definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ddg-cpp">DDG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/ddg-cpp/#a88dda20e9416a19338ab775fca51b22a">SimplifyDDG</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ddg-h">DDG.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/ddg-cpp">DDG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
