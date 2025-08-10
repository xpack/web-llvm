---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/rdf/codenode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `CodeNode` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::rdf::CodeNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">llvm/CodeGen/RDFGraph.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase">NodeBase</a></td>
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

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/blocknode">BlockNode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/funcnode">FuncNode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/instrnode">InstrNode</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afa2a593357e2580338d13e86b553f6c2">getCode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7149fe6ebc8704d6137b39a7037f4fb">setCode</a> (void *C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac54dd04d6e441d1b72195477e5bc1909">Node</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa55f2634884ac705a0afb375e5e297f4">getFirstMember</a> (const DataFlowGraph &amp;G) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac54dd04d6e441d1b72195477e5bc1909">Node</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc6899074d3348226a8a52e495487d47">getLastMember</a> (const DataFlowGraph &amp;G) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5afff33fe198a8b00e021bf562a82dcb">addMember</a> (Node NA, const DataFlowGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc3549f8f158c94641a967961e069847">addMemberAfter</a> (Node MA, Node NA, const DataFlowGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59257285938dab7da5b99b9839e87597">removeMember</a> (Node NA, const DataFlowGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad18ad8bc2c127dd4844b3186233d68f5">NodeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59ca51e5707323e7ed6f1fa512b3f589">members</a> (const DataFlowGraph &amp;G) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Predicate&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad18ad8bc2c127dd4844b3186233d68f5">NodeList</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0d9ff571e6ceb5df2eb4d8a4d3011245">members_if</a> (Predicate P, const DataFlowGraph &amp;G) const</td>
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


<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### addMember() {#a5afff33fe198a8b00e021bf562a82dcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::CodeNode::addMember (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac54dd04d6e441d1b72195477e5bc1909">Node</a> NA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph">DataFlowGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 620 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#acadda6599060e9f8d439158d5f18e701">llvm::rdf::NodeBase::CodeData</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#afc6899074d3348226a8a52e495487d47">getLastMember</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a7e398d2285d22a33c3358ed7904725d7">llvm::rdf::NodeAddr&lt; T &gt;::Id</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3ad01fd9b01e9dde8bd3dc247afbfb7218">ML</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a893d5a6711a796416c81214a3508ccd4">llvm::rdf::NodeBase::setNext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/blocknode/#af54142554a951e28c57d4bc6e5c6ce40">llvm::rdf::BlockNode::addPhi</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a0b52d2ebf631ded594b7311d1f2829e3">llvm::rdf::DataFlowGraph::build</a>.</p>

</div>
</div>

### addMemberAfter() {#acc3549f8f158c94641a967961e069847}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::CodeNode::addMemberAfter (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac54dd04d6e441d1b72195477e5bc1909">Node</a> MA, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac54dd04d6e441d1b72195477e5bc1909">Node</a> NA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph">DataFlowGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 621 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a53926687912600df410ee25e0cc9e0c9">llvm::rdf::NodeBase::append</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#acadda6599060e9f8d439158d5f18e701">llvm::rdf::NodeBase::CodeData</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a7e398d2285d22a33c3358ed7904725d7">llvm::rdf::NodeAddr&lt; T &gt;::Id</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/blocknode/#af54142554a951e28c57d4bc6e5c6ce40">llvm::rdf::BlockNode::addPhi</a>.</p>

</div>
</div>

### getCode() {#afa2a593357e2580338d13e86b553f6c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T llvm::rdf::CodeNode::getCode ()</td>
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



<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#acadda6599060e9f8d439158d5f18e701">llvm::rdf::NodeBase::CodeData</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/blocknode/#ac31264a23924e7566514128d8b64b9a9">llvm::rdf::BlockNode::getCode</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/funcnode/#a0123488d523150e7f7f0a109d248481a">llvm::rdf::FuncNode::getCode</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/stmtnode/#ae16b26d08408d8aec231bbe13bc9e9f9">llvm::rdf::StmtNode::getCode</a>.</p>

</div>
</div>

### getFirstMember() {#aa55f2634884ac705a0afb375e5e297f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node llvm::rdf::CodeNode::getFirstMember (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph">DataFlowGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#acadda6599060e9f8d439158d5f18e701">llvm::rdf::NodeBase::CodeData</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a0dafc6dbe0ace9875cc8cf4d471abd4f">llvm::rdf::NodeBase::NodeBase</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/blocknode/#af54142554a951e28c57d4bc6e5c6ce40">llvm::rdf::BlockNode::addPhi</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a3c2cf12c2f59217e967e76435b45a798">llvm::rdf::RefNode::getNextRef</a>, <a href="#a0d9ff571e6ceb5df2eb4d8a4d3011245">members_if</a> and <a href="#a59257285938dab7da5b99b9839e87597">removeMember</a>.</p>

</div>
</div>

### getLastMember() {#afc6899074d3348226a8a52e495487d47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node llvm::rdf::CodeNode::getLastMember (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph">DataFlowGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 619 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#acadda6599060e9f8d439158d5f18e701">llvm::rdf::NodeBase::CodeData</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a0dafc6dbe0ace9875cc8cf4d471abd4f">llvm::rdf::NodeBase::NodeBase</a>.</p>


<p>Referenced by <a href="#a5afff33fe198a8b00e021bf562a82dcb">addMember</a>.</p>

</div>
</div>

### members() {#a59ca51e5707323e7ed6f1fa512b3f589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeList llvm::rdf::CodeNode::members (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph">DataFlowGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="#a0d9ff571e6ceb5df2eb4d8a4d3011245">members_if</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#ae0d37a7eb6fa39a78f3bcb706766bd73">llvm::rdf::DataFlowGraph::hasUntrackedRef</a>.</p>

</div>
</div>

### members\_if() {#a0d9ff571e6ceb5df2eb4d8a4d3011245}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Predicate&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeList llvm::rdf::CodeNode::members_if (<a href="/web-llvm/docs/api/classes/predicate">Predicate</a> P, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph">DataFlowGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#aa55f2634884ac705a0afb375e5e297f4">getFirstMember</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a0dafc6dbe0ace9875cc8cf4d471abd4f">llvm::rdf::NodeBase::NodeBase</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/funcnode/#a9d0ffbd3083be7cd886e1714817492c8">llvm::rdf::FuncNode::findBlock</a> and <a href="#a59ca51e5707323e7ed6f1fa512b3f589">members</a>.</p>

</div>
</div>

### removeMember() {#a59257285938dab7da5b99b9839e87597}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::CodeNode::removeMember (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac54dd04d6e441d1b72195477e5bc1909">Node</a> NA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph">DataFlowGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 487 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#acadda6599060e9f8d439158d5f18e701">llvm::rdf::NodeBase::CodeData</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#aa55f2634884ac705a0afb375e5e297f4">getFirstMember</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a069d6f399546ffc3a9010c74c9be290b">llvm::rdf::NodeBase::getNext</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a7e398d2285d22a33c3358ed7904725d7">llvm::rdf::NodeAddr&lt; T &gt;::Id</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a0dafc6dbe0ace9875cc8cf4d471abd4f">llvm::rdf::NodeBase::NodeBase</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a893d5a6711a796416c81214a3508ccd4">llvm::rdf::NodeBase::setNext</a>.</p>

</div>
</div>

### setCode() {#ad7149fe6ebc8704d6137b39a7037f4fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::CodeNode::setCode (void * C)</td>
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



<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#acadda6599060e9f8d439158d5f18e701">llvm::rdf::NodeBase::CodeData</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
