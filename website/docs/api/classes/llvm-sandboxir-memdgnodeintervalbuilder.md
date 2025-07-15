---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/memdgnodeintervalbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MemDGNodeIntervalBuilder` Class Reference

<p>Convenience builders for a <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> interval. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::MemDGNodeIntervalBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">llvm/Transforms/Vectorize/SandboxVectorizer/DependencyGraph.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99dd801df4d1697edd4ddd637666c084">getTopMemDGNode</a> (const Interval&lt; Instruction &gt; &amp;Intvl, const DependencyGraph &amp;DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scans the instruction chain in <span class="doxyComputerOutput">Intvl</span> top-down, returning the top-most <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a>, or nullptr. <a href="#a99dd801df4d1697edd4ddd637666c084">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a0f15c37075c267f196cf8b7924e972">getBotMemDGNode</a> (const Interval&lt; Instruction &gt; &amp;Intvl, const DependencyGraph &amp;DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scans the instruction chain in <span class="doxyComputerOutput">Intvl</span> bottom-up, returning the bottom-most <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a>, or nullptr. <a href="#a5a0f15c37075c267f196cf8b7924e972">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/interval">Interval</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0cf2e45248094d2e024dc4ce6917fdc">make</a> (const Interval&lt; Instruction &gt; &amp;Instrs, DependencyGraph &amp;DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given <span class="doxyComputerOutput">Instrs</span> it finds their closest mem nodes in the interval and returns the corresponding mem range. <a href="#af0cf2e45248094d2e024dc4ce6917fdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/interval">Interval</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8327c744ebcc1796ba86773b96a9eb86">makeEmpty</a> ()</td>
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

<p>Convenience builders for a <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a> interval.</p>

<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### getBotMemDGNode() {#a5a0f15c37075c267f196cf8b7924e972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDGNode * llvm::sandboxir::MemDGNodeIntervalBuilder::getBotMemDGNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/interval">Interval</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> &gt; &amp; Intvl, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph">DependencyGraph</a> &amp; DAG)</td>
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

<p>Scans the instruction chain in <span class="doxyComputerOutput">Intvl</span> bottom-up, returning the bottom-most <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a>, or nullptr.</p>

<p>Declaration at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sandboxir/interval/#a6c8ab591004dccad507600e836e262f1">llvm::sandboxir::Interval&lt; T &gt;::bottom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph/#a53d01fa2445dc8a828884a106979acc1">llvm::sandboxir::DependencyGraph::getNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode/#ac1b89d7c178eb196de3d1f05cc205642">llvm::sandboxir::DGNode::isMemDepNodeCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/interval/#abe73e2d461fdd73a08d47fc4968e49e9">llvm::sandboxir::Interval&lt; T &gt;::top</a>.</p>


<p>Referenced by <a href="#af0cf2e45248094d2e024dc4ce6917fdc">make</a>.</p>

</div>
</div>

### getTopMemDGNode() {#a99dd801df4d1697edd4ddd637666c084}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemDGNode * llvm::sandboxir::MemDGNodeIntervalBuilder::getTopMemDGNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/interval">Interval</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> &gt; &amp; Intvl, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph">DependencyGraph</a> &amp; DAG)</td>
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

<p>Scans the instruction chain in <span class="doxyComputerOutput">Intvl</span> top-down, returning the top-most <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode">MemDGNode</a>, or nullptr.</p>

<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sandboxir/interval/#a6c8ab591004dccad507600e836e262f1">llvm::sandboxir::Interval&lt; T &gt;::bottom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph/#a53d01fa2445dc8a828884a106979acc1">llvm::sandboxir::DependencyGraph::getNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode/#ac1b89d7c178eb196de3d1f05cc205642">llvm::sandboxir::DGNode::isMemDepNodeCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/interval/#abe73e2d461fdd73a08d47fc4968e49e9">llvm::sandboxir::Interval&lt; T &gt;::top</a>.</p>


<p>Referenced by <a href="#af0cf2e45248094d2e024dc4ce6917fdc">make</a>.</p>

</div>
</div>

### make() {#af0cf2e45248094d2e024dc4ce6917fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Interval&lt; MemDGNode &gt; llvm::sandboxir::MemDGNodeIntervalBuilder::make (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/interval">Interval</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> &gt; &amp; Instrs, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph">DependencyGraph</a> &amp; DAG)</td>
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

<p>Given <span class="doxyComputerOutput">Instrs</span> it finds their closest mem nodes in the interval and returns the corresponding mem range.</p>


<p>Note: BotN (or its neighboring mem node) is included in the range.</p>


<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/dependencygraph-cpp">DependencyGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5a0f15c37075c267f196cf8b7924e972">getBotMemDGNode</a> and <a href="#a99dd801df4d1697edd4ddd637666c084">getTopMemDGNode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph/#ab89419b289ce60676c9dcca14e365b7b">llvm::sandboxir::DependencyGraph::extend</a>.</p>

</div>
</div>

### makeEmpty() {#a8327c744ebcc1796ba86773b96a9eb86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Interval&lt; MemDGNode &gt; llvm::sandboxir::MemDGNodeIntervalBuilder::makeEmpty ()</td>
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



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/dependencygraph-h">DependencyGraph.h</a>.</p>

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
