---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/rdf/nodeaddr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `NodeAddr` Struct Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename T&gt;
struct llvm::rdf::NodeAddr&lt;T&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">llvm/CodeGen/RDFGraph.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a00ad353a49d6610c13546b978f501534">NodeAddr</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a7b0ee478d2b496fe2b87fed4874df6ac">NodeAddr</a> (T A, NodeId I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename S&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a409e4db158fbd7b7189201cde71f8b26">NodeAddr</a> (const NodeAddr&lt; S &gt; &amp;NA)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5146bea3d2d6fbdd8675974416ebad73">operator==</a> (const NodeAddr&lt; T &gt; &amp;NA) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeadc879681c50ab15ac5bb644fdfbe60">operator!=</a> (const NodeAddr&lt; T &gt; &amp;NA) const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a150c10db309dcfa7a1093dc0c698d663">Addr</a> = nullptr</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7e398d2285d22a33c3358ed7904725d7">Id</a> = 0</td>
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


<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NodeAddr() {#a00ad353a49d6610c13546b978f501534}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::rdf::NodeAddr&lt; T &gt;::NodeAddr ()</td>
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



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### NodeAddr() {#a7b0ee478d2b496fe2b87fed4874df6ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::rdf::NodeAddr&lt; T &gt;::NodeAddr (T A, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a> I)</td>
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



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### NodeAddr() {#a409e4db158fbd7b7189201cde71f8b26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename S&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::rdf::NodeAddr&lt; T &gt;::NodeAddr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr">NodeAddr</a>&lt; S &gt; &amp; NA)</td>
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



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#aeadc879681c50ab15ac5bb644fdfbe60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::NodeAddr&lt; T &gt;::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr">NodeAddr</a>&lt; T &gt; &amp; NA)</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### operator==() {#a5146bea3d2d6fbdd8675974416ebad73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::NodeAddr&lt; T &gt;::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr">NodeAddr</a>&lt; T &gt; &amp; NA)</td>
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



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>Referenced by <a href="#aeadc879681c50ab15ac5bb644fdfbe60">llvm::rdf::NodeAddr&lt; NodeBase * &gt;::operator!=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Addr {#a150c10db309dcfa7a1093dc0c698d663}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T llvm::rdf::NodeAddr&lt; T &gt;::Addr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#a5afff33fe198a8b00e021bf562a82dcb">llvm::rdf::CodeNode::addMember</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#acc3549f8f158c94641a967961e069847">llvm::rdf::CodeNode::addMemberAfter</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/blocknode/#af54142554a951e28c57d4bc6e5c6ce40">llvm::rdf::BlockNode::addPhi</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a53926687912600df410ee25e0cc9e0c9">llvm::rdf::NodeBase::append</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a0b52d2ebf631ded594b7311d1f2829e3">llvm::rdf::DataFlowGraph::build</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/deadcodeelimination/#a4c7ab56ddc8e8b9a4f7903e9268c10e9">llvm::rdf::DeadCodeElimination::collect</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#ac020365416d380fdc2b913c0daf4691b">llvm::rdf::Liveness::computeLiveIns</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#aa36c6486058550c0b2c5f347e5f0e48b">llvm::rdf::Liveness::computePhiInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/deadcodeelimination/#ac9dc6dd66dabbaf46fe4d72655758f4a">llvm::rdf::DeadCodeElimination::erase</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/funcnode/#a9d0ffbd3083be7cd886e1714817492c8">llvm::rdf::FuncNode::findBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#af948ed7c1cd7c55a1e8cb255d8742936">llvm::rdf::Liveness::getAllReachedUses</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#a2950ed09c69131f420a4eec16bdd2f83">llvm::rdf::Liveness::getAllReachingDefs</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#a0c3a1721c534dbc63fdc081a9365fd9c">llvm::rdf::Liveness::getAllReachingDefs</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#a186be9b537ac3f4112ac6ea3d610ddf3">llvm::rdf::Liveness::getNearestAliasedRef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a3c2cf12c2f59217e967e76435b45a798">llvm::rdf::RefNode::getNextRef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a0cf45c81b2f8aaa8a8968e5e0a6cd68e">llvm::rdf::DataFlowGraph::getNextRelated</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a4f334bed0e58d5470180436d28993035">llvm::rdf::DataFlowGraph::getNextShadow</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/instrnode/#ab475c1d11285ad432e000ae49d3049b4">llvm::rdf::InstrNode::getOwner</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#acefeb286d40feb0a02a947208915f28b">llvm::rdf::RefNode::getOwner</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#ae0d37a7eb6fa39a78f3bcb706766bd73">llvm::rdf::DataFlowGraph::hasUntrackedRef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#ac8b5aa2c1dd5ee4a4a8bf03730965c29">llvm::rdf::DataFlowGraph::IsCode</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a264db9e61fcbc7db438de1f6a062a96a">llvm::rdf::DataFlowGraph::IsDef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a555e904e68d3d41e5f2db6beaabd49a9">llvm::rdf::DataFlowGraph::IsPhi</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a924c78446e6a6bca9371f02ae6c62b7b">llvm::rdf::DataFlowGraph::IsRef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a9a057fa5769de2acccd16b02326468b3">llvm::rdf::DataFlowGraph::IsUse</a>, <a href="#a5146bea3d2d6fbdd8675974416ebad73">llvm::rdf::NodeAddr&lt; NodeBase * &gt;::operator==</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#a59257285938dab7da5b99b9839e87597">llvm::rdf::CodeNode::removeMember</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonrdfopt-cpp-/hexagondce/#af147b385bf71cd50563c0d23b0f9baf7">anonymous{HexagonRDFOpt.cpp}::HexagonDCE::removeOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonrdfopt-cpp-/hexagondce/#a3c29fb0e6cda6fc8b1839501e9b63529">anonymous{HexagonRDFOpt.cpp}::HexagonDCE::rewrite</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonrdfopt-cpp-/hexagondce/#a2fdc22ba5c1d80ca60c2adcd35b3cd41">anonymous{HexagonRDFOpt.cpp}::HexagonDCE::run</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/copypropagation/#ab5cc393f3a921f0a6fe0505561a80e23">llvm::rdf::CopyPropagation::run</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonoptaddrmode-cpp-/hexagonoptaddrmode/#ad07a6a329e102fb53ef087cbba07c002">anonymous{HexagonOptAddrMode.cpp}::HexagonOptAddrMode::runOnMachineFunction</a>.</p>

</div>
</div>

### Id {#a7e398d2285d22a33c3358ed7904725d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeId llvm::rdf::NodeAddr&lt; T &gt;::Id = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#a5afff33fe198a8b00e021bf562a82dcb">llvm::rdf::CodeNode::addMember</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#acc3549f8f158c94641a967961e069847">llvm::rdf::CodeNode::addMemberAfter</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/blocknode/#af54142554a951e28c57d4bc6e5c6ce40">llvm::rdf::BlockNode::addPhi</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a53926687912600df410ee25e0cc9e0c9">llvm::rdf::NodeBase::append</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#aa36c6486058550c0b2c5f347e5f0e48b">llvm::rdf::Liveness::computePhiInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#a0c3a1721c534dbc63fdc081a9365fd9c">llvm::rdf::Liveness::getAllReachingDefs</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#a186be9b537ac3f4112ac6ea3d610ddf3">llvm::rdf::Liveness::getNearestAliasedRef</a>, <a href="#a5146bea3d2d6fbdd8675974416ebad73">llvm::rdf::NodeAddr&lt; NodeBase * &gt;::operator==</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#a59257285938dab7da5b99b9839e87597">llvm::rdf::CodeNode::removeMember</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonrdfopt-cpp-/hexagondce/#a2fdc22ba5c1d80ca60c2adcd35b3cd41">anonymous{HexagonRDFOpt.cpp}::HexagonDCE::run</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/copypropagation/#ab5cc393f3a921f0a6fe0505561a80e23">llvm::rdf::CopyPropagation::run</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
