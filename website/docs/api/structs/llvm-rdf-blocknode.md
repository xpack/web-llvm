---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/rdf/blocknode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BlockNode` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::rdf::BlockNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">llvm/CodeGen/RDFGraph.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/codenode">CodeNode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac31264a23924e7566514128d8b64b9a9">getCode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af54142554a951e28c57d4bc6e5c6ce40">addPhi</a> (Phi PA, const DataFlowGraph &amp;G)</td>
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


<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### addPhi() {#af54142554a951e28c57d4bc6e5c6ce40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::BlockNode::addPhi (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a379bee2dadbfd1d7a599f003c4275dd8">Phi</a> PA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph">DataFlowGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 648 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#a5afff33fe198a8b00e021bf562a82dcb">llvm::rdf::CodeNode::addMember</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#acc3549f8f158c94641a967961e069847">llvm::rdf::CodeNode::addMemberAfter</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da3897c75682d603726fd11a4ce74fbfdf">llvm::rdf::NodeAttrs::Code</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#acadda6599060e9f8d439158d5f18e701">llvm::rdf::NodeBase::CodeData</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#aa55f2634884ac705a0afb375e5e297f4">llvm::rdf::CodeNode::getFirstMember</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#ad803998605d4a43c2eb44bd90ed19973">llvm::rdf::NodeBase::getKind</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a47f13a9bf570d95ac215312b5c77cc90">llvm::rdf::NodeBase::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a7e398d2285d22a33c3358ed7904725d7">llvm::rdf::NodeAddr&lt; T &gt;::Id</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da0ae60988901d9b6e0499d07f94e8fc00">llvm::rdf::NodeAttrs::Phi</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a893d5a6711a796416c81214a3508ccd4">llvm::rdf::NodeBase::setNext</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da91376b865b14d172148590ff1c69e403">llvm::rdf::NodeAttrs::Stmt</a>.</p>

</div>
</div>

### getCode() {#ac31264a23924e7566514128d8b64b9a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::rdf::BlockNode::getCode ()</td>
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



<p>Definition at line 644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#afa2a593357e2580338d13e86b553f6c2">llvm::rdf::CodeNode::getCode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a0b52d2ebf631ded594b7311d1f2829e3">llvm::rdf::DataFlowGraph::build</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/funcnode/#a9d0ffbd3083be7cd886e1714817492c8">llvm::rdf::FuncNode::findBlock</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
