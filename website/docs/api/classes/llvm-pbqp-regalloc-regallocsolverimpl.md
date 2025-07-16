---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pbqp/regalloc/regallocsolverimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RegAllocSolverImpl` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::PBQP::RegAlloc::RegAllocSolverImpl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">llvm/CodeGen/RegAllocPBQP.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad81ed1ec529c1f7c9d8819dafb444dd8">RawVector</a> = <a href="/web-llvm/docs/api/classes/llvm/pbqp/vector">PBQP::Vector</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a189d06ab3dca5870c2a347e91a43490d">RawMatrix</a> = <a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">PBQP::Matrix</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f3369eccf0486c246b9a4e52f3ad5e2">Vector</a> = <a href="/web-llvm/docs/api/classes/llvm/pbqp/vector">PBQP::Vector</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0bbdafab57812ec43eb7912ec60040a">Matrix</a> = <a href="/web-llvm/docs/api/classes/llvm/pbqp/mdmatrix">RAMatrix</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e4120f6053795a7d6574410935a78c4">CostAllocator</a> = <a href="/web-llvm/docs/api/classes/llvm/pbqp/poolcostallocator">PBQP::PoolCostAllocator</a>&lt; <a href="#a2f3369eccf0486c246b9a4e52f3ad5e2">Vector</a>, <a href="#ae0bbdafab57812ec43eb7912ec60040a">Matrix</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a882a5d143fa147a161f2f7e12543622e">NodeId</a> = <a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">GraphBase::NodeId</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a048ad1767be1d154a0482fb06325c889">EdgeId</a> = <a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a679643c1e5202061ef3e9b121a2a7dce">GraphBase::EdgeId</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac05c7d03c98e19bddb708ec1a837c324">NodeMetadata</a> = <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/nodemetadata">RegAlloc::NodeMetadata</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20c8319042007f64dadaa628301d9575">GraphMetadata</a> = <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/graphmetadata">RegAlloc::GraphMetadata</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34eec38b7af10d85a3fb2ee8b50aea38">Graph</a> = <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph">PBQP::Graph</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/regallocsolverimpl">RegAllocSolverImpl</a> &gt;</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b0edd3e17d4ebc093ab792e375508a9">RAMatrix</a> = <a href="/web-llvm/docs/api/classes/llvm/pbqp/mdmatrix">MDMatrix</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/matrixmetadata">MatrixMetadata</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa724d92a06dff6d74e4c978fd66847fb">NodeSet</a> = std::set&lt; <a href="#a882a5d143fa147a161f2f7e12543622e">NodeId</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acffcfc1501a9c4bd67ad2ddd9d509e5b">RegAllocSolverImpl</a> (Graph &amp;G)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/solution">Solution</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af627ac537503219854146d8a62ff67f4">solve</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa23e26965fa2403fae5617990944cc91">handleAddNode</a> (NodeId NId)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b9ee6feb43c41c8a3a4b98704ad575f">handleRemoveNode</a> (NodeId NId)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a331c82b5c04343af3c7ace3c9107e134">handleSetNodeCosts</a> (NodeId NId, const Vector &amp;newCosts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acce95f2c09046a3cf58a37b1194157a6">handleAddEdge</a> (EdgeId EId)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63cb5b126699087dcdd956681e1686cf">handleDisconnectEdge</a> (EdgeId EId, NodeId NId)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9368cb01cb6c15a40aea0541d6a5974">handleReconnectEdge</a> (EdgeId EId, NodeId NId)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61bc4541418cc85ba3130756c7dc86b5">handleUpdateCosts</a> (EdgeId EId, const Matrix &amp;NewCosts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a085baf3aa391535135b9f48cd1bbddaf">promote</a> (NodeId NId, NodeMetadata &amp;NMd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af095e7231170470b806de1e4ec3f8d39">removeFromCurrentSet</a> (NodeId NId)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29e99a44ca12f2aa6feb4a5c34117607">moveToOptimallyReducibleNodes</a> (NodeId NId)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa56bc20fa1679f20f1ffd5fd3c96ac2a">moveToConservativelyAllocatableNodes</a> (NodeId NId)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade5413dff75e1c175434617875227c10">moveToNotProvablyAllocatableNodes</a> (NodeId NId)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a0becab886cce3c04b459287641c8dd">setup</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/pbqp/graphbase/#a7187d2e408994bd7307a4c8f32f745a8">GraphBase::NodeId</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bffc2c50a7a1da79005b7a086920c9c">reduce</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a34eec38b7af10d85a3fb2ee8b50aea38">Graph</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a328459b7d8d5cff64595f10d2a419825">G</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">NodeSet</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a7aa760ac244cf7120695846fadd413">OptimallyReducibleNodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">NodeSet</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03f101daad2698753e67f0f270f47d34">ConservativelyAllocatableNodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">NodeSet</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a250d83710e0a2e7bccb216d7cd72e215">NotProvablyAllocatableNodes</a></td>
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


<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CostAllocator {#a4e4120f6053795a7d6574410935a78c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::RegAlloc::RegAllocSolverImpl::CostAllocator =  PBQP::PoolCostAllocator&lt;Vector, Matrix&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### EdgeId {#a048ad1767be1d154a0482fb06325c889}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::RegAlloc::RegAllocSolverImpl::EdgeId =  GraphBase::EdgeId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### Graph {#a34eec38b7af10d85a3fb2ee8b50aea38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::RegAlloc::RegAllocSolverImpl::Graph =  PBQP::Graph&lt;RegAllocSolverImpl&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### GraphMetadata {#a20c8319042007f64dadaa628301d9575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::RegAlloc::RegAllocSolverImpl::GraphMetadata =  RegAlloc::GraphMetadata</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### Matrix {#ae0bbdafab57812ec43eb7912ec60040a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::RegAlloc::RegAllocSolverImpl::Matrix =  RAMatrix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### NodeId {#a882a5d143fa147a161f2f7e12543622e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::RegAlloc::RegAllocSolverImpl::NodeId =  GraphBase::NodeId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### NodeMetadata {#ac05c7d03c98e19bddb708ec1a837c324}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::RegAlloc::RegAllocSolverImpl::NodeMetadata =  RegAlloc::NodeMetadata</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### RawMatrix {#a189d06ab3dca5870c2a347e91a43490d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::RegAlloc::RegAllocSolverImpl::RawMatrix =  PBQP::Matrix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### RawVector {#ad81ed1ec529c1f7c9d8819dafb444dd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::RegAlloc::RegAllocSolverImpl::RawVector =  PBQP::Vector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### Vector {#a2f3369eccf0486c246b9a4e52f3ad5e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::RegAlloc::RegAllocSolverImpl::Vector =  PBQP::Vector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### NodeSet {#aa724d92a06dff6d74e4c978fd66847fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::RegAlloc::RegAllocSolverImpl::NodeSet =  std::set&lt;NodeId&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### RAMatrix {#a0b0edd3e17d4ebc093ab792e375508a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::RegAlloc::RegAllocSolverImpl::RAMatrix =  MDMatrix&lt;MatrixMetadata&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RegAllocSolverImpl() {#acffcfc1501a9c4bd67ad2ddd9d509e5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PBQP::RegAlloc::RegAllocSolverImpl::RegAllocSolverImpl (<a href="#a34eec38b7af10d85a3fb2ee8b50aea38">Graph</a> &amp; G)</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### handleAddEdge() {#acce95f2c09046a3cf58a37b1194157a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::RegAlloc::RegAllocSolverImpl::handleAddEdge (<a href="#a048ad1767be1d154a0482fb06325c889">EdgeId</a> EId)</td>
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



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>Reference <a href="#af9368cb01cb6c15a40aea0541d6a5974">handleReconnectEdge</a>.</p>

</div>
</div>

### handleAddNode() {#aa23e26965fa2403fae5617990944cc91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::RegAlloc::RegAllocSolverImpl::handleAddNode (<a href="#a882a5d143fa147a161f2f7e12543622e">NodeId</a> NId)</td>
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



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### handleDisconnectEdge() {#a63cb5b126699087dcdd956681e1686cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::RegAlloc::RegAllocSolverImpl::handleDisconnectEdge (<a href="#a048ad1767be1d154a0482fb06325c889">EdgeId</a> EId, <a href="#a882a5d143fa147a161f2f7e12543622e">NodeId</a> NId)</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/nodemetadata/#a1c74e0792948c70c031151491b34da14">llvm::PBQP::RegAlloc::NodeMetadata::handleRemoveEdge</a>.</p>

</div>
</div>

### handleReconnectEdge() {#af9368cb01cb6c15a40aea0541d6a5974}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::RegAlloc::RegAllocSolverImpl::handleReconnectEdge (<a href="#a048ad1767be1d154a0482fb06325c889">EdgeId</a> EId, <a href="#a882a5d143fa147a161f2f7e12543622e">NodeId</a> NId)</td>
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



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/nodemetadata/#af604de88cfa10f1c5c955d781ee30d7a">llvm::PBQP::RegAlloc::NodeMetadata::handleAddEdge</a>.</p>


<p>Referenced by <a href="#acce95f2c09046a3cf58a37b1194157a6">handleAddEdge</a>.</p>

</div>
</div>

### handleRemoveNode() {#a4b9ee6feb43c41c8a3a4b98704ad575f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::RegAlloc::RegAllocSolverImpl::handleRemoveNode (<a href="#a882a5d143fa147a161f2f7e12543622e">NodeId</a> NId)</td>
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



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### handleSetNodeCosts() {#a331c82b5c04343af3c7ace3c9107e134}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::RegAlloc::RegAllocSolverImpl::handleSetNodeCosts (<a href="#a882a5d143fa147a161f2f7e12543622e">NodeId</a> NId, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2f3369eccf0486c246b9a4e52f3ad5e2">Vector</a> &amp; newCosts)</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### handleUpdateCosts() {#a61bc4541418cc85ba3130756c7dc86b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::RegAlloc::RegAllocSolverImpl::handleUpdateCosts (<a href="#a048ad1767be1d154a0482fb06325c889">EdgeId</a> EId, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae0bbdafab57812ec43eb7912ec60040a">Matrix</a> &amp; NewCosts)</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pbqp/mdmatrix/#acd63ba8da2c8d08ff0fc73f840926666">llvm::PBQP::MDMatrix&lt; Metadata &gt;::getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/nodemetadata/#af604de88cfa10f1c5c955d781ee30d7a">llvm::PBQP::RegAlloc::NodeMetadata::handleAddEdge</a> and <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/nodemetadata/#a1c74e0792948c70c031151491b34da14">llvm::PBQP::RegAlloc::NodeMetadata::handleRemoveEdge</a>.</p>

</div>
</div>

### solve() {#af627ac537503219854146d8a62ff67f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Solution llvm::PBQP::RegAlloc::RegAllocSolverImpl::solve ()</td>
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



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pbqp/#aca4beb871fa19efbf46dbb8487d05ae9">llvm::PBQP::backpropagate</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a6d827fc34f1b4371a0b7183d3ca5bcac">reduce</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/pbqp/regalloc/#a57e1115cb3c891254a6e675437c1a40c">llvm::PBQP::RegAlloc::solve</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### moveToConservativelyAllocatableNodes() {#aa56bc20fa1679f20f1ffd5fd3c96ac2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::RegAlloc::RegAllocSolverImpl::moveToConservativelyAllocatableNodes (<a href="#a882a5d143fa147a161f2f7e12543622e">NodeId</a> NId)</td>
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



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### moveToNotProvablyAllocatableNodes() {#ade5413dff75e1c175434617875227c10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::RegAlloc::RegAllocSolverImpl::moveToNotProvablyAllocatableNodes (<a href="#a882a5d143fa147a161f2f7e12543622e">NodeId</a> NId)</td>
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



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### moveToOptimallyReducibleNodes() {#a29e99a44ca12f2aa6feb4a5c34117607}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::RegAlloc::RegAllocSolverImpl::moveToOptimallyReducibleNodes (<a href="#a882a5d143fa147a161f2f7e12543622e">NodeId</a> NId)</td>
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



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### promote() {#a085baf3aa391535135b9f48cd1bbddaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::RegAlloc::RegAllocSolverImpl::promote (<a href="#a882a5d143fa147a161f2f7e12543622e">NodeId</a> NId, <a href="#ac05c7d03c98e19bddb708ec1a837c324">NodeMetadata</a> &amp; NMd)</td>
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



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### reduce() {#a7bffc2c50a7a1da79005b7a086920c9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; GraphBase::NodeId &gt; llvm::PBQP::RegAlloc::RegAllocSolverImpl::reduce ()</td>
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



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### removeFromCurrentSet() {#af095e7231170470b806de1e4ec3f8d39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::RegAlloc::RegAllocSolverImpl::removeFromCurrentSet (<a href="#a882a5d143fa147a161f2f7e12543622e">NodeId</a> NId)</td>
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



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### setup() {#a7a0becab886cce3c04b459287641c8dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PBQP::RegAlloc::RegAllocSolverImpl::setup ()</td>
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



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ConservativelyAllocatableNodes {#a03f101daad2698753e67f0f270f47d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeSet llvm::PBQP::RegAlloc::RegAllocSolverImpl::ConservativelyAllocatableNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### G {#a328459b7d8d5cff64595f10d2a419825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Graph&amp; llvm::PBQP::RegAlloc::RegAllocSolverImpl::G</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### NotProvablyAllocatableNodes {#a250d83710e0a2e7bccb216d7cd72e215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeSet llvm::PBQP::RegAlloc::RegAllocSolverImpl::NotProvablyAllocatableNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### OptimallyReducibleNodes {#a2a7aa760ac244cf7120695846fadd413}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeSet llvm::PBQP::RegAlloc::RegAllocSolverImpl::OptimallyReducibleNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
