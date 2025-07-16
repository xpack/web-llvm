---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/rdf/phiusenode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PhiUseNode` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::rdf::PhiUseNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">llvm/CodeGen/RDFGraph.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/usenode">UseNode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61edd9a1eb4a1bfc93bf58ad5073b872">getPredecessor</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab29e872edfff5d7039dadad2febac8c8">setPredecessor</a> (NodeId B)</td>
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


<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getPredecessor() {#a61edd9a1eb4a1bfc93bf58ad5073b872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeId llvm::rdf::PhiUseNode::getPredecessor ()</td>
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



<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a7a5d468f74c441d6af070782b1062007">llvm::rdf::NodeBase::getFlags</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da1ec381406c0c91aef4a414bdba131112">llvm::rdf::NodeAttrs::PhiRef</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a32b73a2d9331c91d8bba428277116eda">llvm::rdf::NodeBase::RefData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a0cf45c81b2f8aaa8a8968e5e0a6cd68e">llvm::rdf::DataFlowGraph::getNextRelated</a>.</p>

</div>
</div>

### setPredecessor() {#ab29e872edfff5d7039dadad2febac8c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::PhiUseNode::setPredecessor (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a> B)</td>
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



<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a7a5d468f74c441d6af070782b1062007">llvm::rdf::NodeBase::getFlags</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da1ec381406c0c91aef4a414bdba131112">llvm::rdf::NodeAttrs::PhiRef</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a32b73a2d9331c91d8bba428277116eda">llvm::rdf::NodeBase::RefData</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
