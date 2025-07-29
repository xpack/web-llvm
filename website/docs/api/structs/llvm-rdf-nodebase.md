---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/rdf/nodebase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `NodeBase` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::rdf::NodeBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">llvm/CodeGen/RDFGraph.h</a>"
</div>

## Derived Structs

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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/refnode">RefNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dafc6dbe0ace9875cc8cf4d471abd4f">NodeBase</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47f13a9bf570d95ac215312b5c77cc90">getType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad803998605d4a43c2eb44bd90ed19973">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a5d468f74c441d6af070782b1062007">getFlags</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a069d6f399546ffc3a9010c74c9be290b">getNext</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45db36bd4009fb18cd9024ff51d99056">getAttrs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cfd421019c8e6f5f9f361b6d41b945d">setAttrs</a> (uint16_t A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c6eec2ca178b22b6d5c09ffcc021e88">setFlags</a> (uint16_t F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53926687912600df410ee25e0cc9e0c9">append</a> (Node NA)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5bf873d13a38d0b9be8e03ff48c3beb">init</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a893d5a6711a796416c81214a3508ccd4">setNext</a> (NodeId N)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/ref-struct">Ref_struct</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32b73a2d9331c91d8bba428277116eda">RefData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/code-struct">Code_struct</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acadda6599060e9f8d439158d5f18e701">CodeData</a></td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a231d82f024a019aee7e463b5203293ca">Attrs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a257644778f89842b01d594d1dffdd7a8">Reserved</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8279993efad8628daf7f27ee8e37519f">Next</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase">llvm::rdf::NodeBase</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88029b49d31a9544e38d2f8836bec714"></a></td>
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


<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NodeBase() {#a0dafc6dbe0ace9875cc8cf4d471abd4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::rdf::NodeBase::NodeBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#aa55f2634884ac705a0afb375e5e297f4">llvm::rdf::CodeNode::getFirstMember</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#afc6899074d3348226a8a52e495487d47">llvm::rdf::CodeNode::getLastMember</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a3c2cf12c2f59217e967e76435b45a798">llvm::rdf::RefNode::getNextRef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#acefeb286d40feb0a02a947208915f28b">llvm::rdf::RefNode::getOwner</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#a0d9ff571e6ceb5df2eb4d8a4d3011245">llvm::rdf::CodeNode::members_if</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#a59257285938dab7da5b99b9839e87597">llvm::rdf::CodeNode::removeMember</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### append() {#a53926687912600df410ee25e0cc9e0c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::NodeBase::append (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac54dd04d6e441d1b72195477e5bc1909">Node</a> NA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a7e398d2285d22a33c3358ed7904725d7">llvm::rdf::NodeAddr&lt; T &gt;::Id</a> and <a href="#a8279993efad8628daf7f27ee8e37519f">Next</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#acc3549f8f158c94641a967961e069847">llvm::rdf::CodeNode::addMemberAfter</a>.</p>

</div>
</div>

### getAttrs() {#a45db36bd4009fb18cd9024ff51d99056}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::rdf::NodeBase::getAttrs ()</td>
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



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>Reference <a href="#a231d82f024a019aee7e463b5203293ca">Attrs</a>.</p>


<p>Referenced by <a href="#a0c6eec2ca178b22b6d5c09ffcc021e88">setFlags</a>.</p>

</div>
</div>

### getFlags() {#a7a5d468f74c441d6af070782b1062007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::rdf::NodeBase::getFlags ()</td>
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



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="#a231d82f024a019aee7e463b5203293ca">Attrs</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a7bf0ad382e777b7c21faaec5091bd2f5">llvm::rdf::NodeAttrs::flags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a5e800251e291cab9af691282a73e14e9">llvm::rdf::RefNode::getOp</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/phiusenode/#a61edd9a1eb4a1bfc93bf58ad5073b872">llvm::rdf::PhiUseNode::getPredecessor</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/phiusenode/#ab29e872edfff5d7039dadad2febac8c8">llvm::rdf::PhiUseNode::setPredecessor</a>.</p>

</div>
</div>

### getKind() {#ad803998605d4a43c2eb44bd90ed19973}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::rdf::NodeBase::getKind ()</td>
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



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="#a231d82f024a019aee7e463b5203293ca">Attrs</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#aa28f80591f9c0bd065460aa19d4364f4">llvm::rdf::NodeAttrs::kind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/blocknode/#af54142554a951e28c57d4bc6e5c6ce40">llvm::rdf::BlockNode::addPhi</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/instrnode/#ab475c1d11285ad432e000ae49d3049b4">llvm::rdf::InstrNode::getOwner</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#ac8b5aa2c1dd5ee4a4a8bf03730965c29">llvm::rdf::DataFlowGraph::IsCode</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a264db9e61fcbc7db438de1f6a062a96a">llvm::rdf::DataFlowGraph::IsDef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a093013dcf867825e14bac7b7c5eb41a5">llvm::rdf::RefNode::isDef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a555e904e68d3d41e5f2db6beaabd49a9">llvm::rdf::DataFlowGraph::IsPhi</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a924c78446e6a6bca9371f02ae6c62b7b">llvm::rdf::DataFlowGraph::IsRef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a9a057fa5769de2acccd16b02326468b3">llvm::rdf::DataFlowGraph::IsUse</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a7053c149a7a85afbae1ab5dc6cb0ffa5">llvm::rdf::RefNode::isUse</a>.</p>

</div>
</div>

### getNext() {#a069d6f399546ffc3a9010c74c9be290b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeId llvm::rdf::NodeBase::getNext ()</td>
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



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>Reference <a href="#a8279993efad8628daf7f27ee8e37519f">Next</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a3c2cf12c2f59217e967e76435b45a798">llvm::rdf::RefNode::getNextRef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/instrnode/#ab475c1d11285ad432e000ae49d3049b4">llvm::rdf::InstrNode::getOwner</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#acefeb286d40feb0a02a947208915f28b">llvm::rdf::RefNode::getOwner</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#a59257285938dab7da5b99b9839e87597">llvm::rdf::CodeNode::removeMember</a>.</p>

</div>
</div>

### getType() {#a47f13a9bf570d95ac215312b5c77cc90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::rdf::NodeBase::getType ()</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="#a231d82f024a019aee7e463b5203293ca">Attrs</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#afe4630acf2fb57975feaa0b85d524923">llvm::rdf::NodeAttrs::type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/blocknode/#af54142554a951e28c57d4bc6e5c6ce40">llvm::rdf::BlockNode::addPhi</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/instrnode/#ab475c1d11285ad432e000ae49d3049b4">llvm::rdf::InstrNode::getOwner</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#acefeb286d40feb0a02a947208915f28b">llvm::rdf::RefNode::getOwner</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#ac8b5aa2c1dd5ee4a4a8bf03730965c29">llvm::rdf::DataFlowGraph::IsCode</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a264db9e61fcbc7db438de1f6a062a96a">llvm::rdf::DataFlowGraph::IsDef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a093013dcf867825e14bac7b7c5eb41a5">llvm::rdf::RefNode::isDef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a555e904e68d3d41e5f2db6beaabd49a9">llvm::rdf::DataFlowGraph::IsPhi</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a924c78446e6a6bca9371f02ae6c62b7b">llvm::rdf::DataFlowGraph::IsRef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a9a057fa5769de2acccd16b02326468b3">llvm::rdf::DataFlowGraph::IsUse</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a7053c149a7a85afbae1ab5dc6cb0ffa5">llvm::rdf::RefNode::isUse</a>.</p>

</div>
</div>

### init() {#ae5bf873d13a38d0b9be8e03ff48c3beb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::NodeBase::init ()</td>
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



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### setAttrs() {#a4cfd421019c8e6f5f9f361b6d41b945d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::NodeBase::setAttrs (uint16_t A)</td>
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



<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#a231d82f024a019aee7e463b5203293ca">Attrs</a>.</p>


<p>Referenced by <a href="#a0c6eec2ca178b22b6d5c09ffcc021e88">setFlags</a>.</p>

</div>
</div>

### setFlags() {#a0c6eec2ca178b22b6d5c09ffcc021e88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::NodeBase::setFlags (uint16_t F)</td>
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



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a45db36bd4009fb18cd9024ff51d99056">getAttrs</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#acacc9d0ec2cce5168797abbb47a07b7c">llvm::rdf::NodeAttrs::set_flags</a> and <a href="#a4cfd421019c8e6f5f9f361b6d41b945d">setAttrs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a4f334bed0e58d5470180436d28993035">llvm::rdf::DataFlowGraph::getNextShadow</a>.</p>

</div>
</div>

### setNext() {#a893d5a6711a796416c81214a3508ccd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::NodeBase::setNext (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a> N)</td>
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



<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a8279993efad8628daf7f27ee8e37519f">Next</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#a5afff33fe198a8b00e021bf562a82dcb">llvm::rdf::CodeNode::addMember</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/blocknode/#af54142554a951e28c57d4bc6e5c6ce40">llvm::rdf::BlockNode::addPhi</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#a59257285938dab7da5b99b9839e87597">llvm::rdf::CodeNode::removeMember</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CodeData {#acadda6599060e9f8d439158d5f18e701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Code_struct llvm::rdf::NodeBase::CodeData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#a5afff33fe198a8b00e021bf562a82dcb">llvm::rdf::CodeNode::addMember</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#acc3549f8f158c94641a967961e069847">llvm::rdf::CodeNode::addMemberAfter</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/blocknode/#af54142554a951e28c57d4bc6e5c6ce40">llvm::rdf::BlockNode::addPhi</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#afa2a593357e2580338d13e86b553f6c2">llvm::rdf::CodeNode::getCode</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#aa55f2634884ac705a0afb375e5e297f4">llvm::rdf::CodeNode::getFirstMember</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#afc6899074d3348226a8a52e495487d47">llvm::rdf::CodeNode::getLastMember</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#a59257285938dab7da5b99b9839e87597">llvm::rdf::CodeNode::removeMember</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#ad7149fe6ebc8704d6137b39a7037f4fb">llvm::rdf::CodeNode::setCode</a>.</p>

</div>
</div>

### RefData {#a32b73a2d9331c91d8bba428277116eda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Ref_struct llvm::rdf::NodeBase::RefData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a5e800251e291cab9af691282a73e14e9">llvm::rdf::RefNode::getOp</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/phiusenode/#a61edd9a1eb4a1bfc93bf58ad5073b872">llvm::rdf::PhiUseNode::getPredecessor</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/defnode/#abd4268f2ff21aeb4f6b3514d5670fdb8">llvm::rdf::DefNode::getReachedDef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/defnode/#a12780b9ef159b780c10ee6182e86adff">llvm::rdf::DefNode::getReachedUse</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a0f6ab8d492d5ad9f489fc4034c9d3790">llvm::rdf::RefNode::getReachingDef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a65815b43850c5a2eed22a941425e8409">llvm::rdf::RefNode::getRegRef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a37650e1cbcdcbae779a3b0b09367d067">llvm::rdf::RefNode::getSibling</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/defnode/#ac163d524a779a948fe27c9fb3d031301">llvm::rdf::DefNode::linkToDef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/usenode/#a09e9ae696dad2b8e6f0a3ffa29fd1abb">llvm::rdf::UseNode::linkToDef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/phiusenode/#ab29e872edfff5d7039dadad2febac8c8">llvm::rdf::PhiUseNode::setPredecessor</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/defnode/#ab64f4bf5b8df899780551679429e5722">llvm::rdf::DefNode::setReachedDef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/defnode/#a9ec5bcd46e6dd60358614c2f4eeb35f3">llvm::rdf::DefNode::setReachedUse</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a7feaf0a197ba0ddbd5371113a1832165">llvm::rdf::RefNode::setReachingDef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a66a9813e044857db14d81f9a978c2f3e">llvm::rdf::RefNode::setRegRef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a55a295c8919adaa4620b7abdff8137b5">llvm::rdf::RefNode::setRegRef</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a78ec335a78462fdc1e5010347fc98b07">llvm::rdf::RefNode::setSibling</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

###  {#a88029b49d31a9544e38d2f8836bec714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::rdf::NodeBase llvm::rdf::NodeBase</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### Attrs {#a231d82f024a019aee7e463b5203293ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::rdf::NodeBase::Attrs</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>Referenced by <a href="#a45db36bd4009fb18cd9024ff51d99056">getAttrs</a>, <a href="#a7a5d468f74c441d6af070782b1062007">getFlags</a>, <a href="#ad803998605d4a43c2eb44bd90ed19973">getKind</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a65815b43850c5a2eed22a941425e8409">llvm::rdf::RefNode::getRegRef</a>, <a href="#a47f13a9bf570d95ac215312b5c77cc90">getType</a>, <a href="#a4cfd421019c8e6f5f9f361b6d41b945d">setAttrs</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a66a9813e044857db14d81f9a978c2f3e">llvm::rdf::RefNode::setRegRef</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a55a295c8919adaa4620b7abdff8137b5">llvm::rdf::RefNode::setRegRef</a>.</p>

</div>
</div>

### Next {#a8279993efad8628daf7f27ee8e37519f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeId llvm::rdf::NodeBase::Next</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>Referenced by <a href="#a53926687912600df410ee25e0cc9e0c9">append</a>, <a href="#a069d6f399546ffc3a9010c74c9be290b">getNext</a> and <a href="#a893d5a6711a796416c81214a3508ccd4">setNext</a>.</p>

</div>
</div>

### Reserved {#a257644778f89842b01d594d1dffdd7a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::rdf::NodeBase::Reserved</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

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
