---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/intervalmapimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `IntervalMapImpl` Namespace Reference

<p><a href="/web-llvm/docs/api/namespaces/llvm/intervalmapimpl">IntervalMapImpl</a> - Namespace used for <a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a> implementation details. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::IntervalMapImpl { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/branchnode">BranchNode&lt;KeyT, ValT, N, Traits&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/leafnode">LeafNode&lt;KeyT, ValT, N, Traits&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/nodebase">NodeBase&lt;T1, T2, N&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/noderef">NodeRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/intervalmapimpl/nodesizer">NodeSizer&lt;KeyT, ValT&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/path">Path</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab92974e292699af764f4bd02d1f44448">IdxPair</a> = std::pair&lt; unsigned, unsigned &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#aacf91952cde5989ab8c6b38b501021c1">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1edda7c684a88b0c8aa8480aa869451b">adjustSiblingSizes</a> (NodeT *Node[], unsigned Nodes, unsigned CurSize[], const unsigned NewSize[])</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a1edda7c684a88b0c8aa8480aa869451b">IntervalMapImpl::adjustSiblingSizes</a> - Move elements between sibling nodes. <a href="#a1edda7c684a88b0c8aa8480aa869451b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab92974e292699af764f4bd02d1f44448">IdxPair</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc507d70d9385ae35dcdb70dc1bebc19">distribute</a> (unsigned Nodes, unsigned Elements, unsigned Capacity, const unsigned *CurSize, unsigned NewSize[], unsigned Position, bool Grow)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#adc507d70d9385ae35dcdb70dc1bebc19">IntervalMapImpl::distribute</a> - Compute a new distribution of node elements after an overflow or underflow. <a href="#adc507d70d9385ae35dcdb70dc1bebc19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/namespaces/llvm/intervalmapimpl">IntervalMapImpl</a> - Namespace used for <a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a> implementation details.</p>


<p>It should be considered private to the implementation.</p>


<div class="doxySectionDef">

## Typedefs

### IdxPair {#ab92974e292699af764f4bd02d1f44448}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IntervalMapImpl::IdxPair =  std::pair&lt;unsigned,unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#aacf91952cde5989ab8c6b38b501021c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Log2CacheLine<a id="aacf91952cde5989ab8c6b38b501021c1a4b980c1f20e48e79647774737cf4f1ce"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CacheLineBytes<a id="aacf91952cde5989ab8c6b38b501021c1a22be8a9f335245b5ce05d2a3d35a9221"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; Log2CacheLine)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DesiredNodeBytes<a id="aacf91952cde5989ab8c6b38b501021c1ab4675b39ebff7a48b8f66be1e97f1575"></a></td>
<td class="doxyEnumItemDescription"> (= 3 * CacheLineBytes)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### adjustSiblingSizes() {#a1edda7c684a88b0c8aa8480aa869451b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntervalMapImpl::adjustSiblingSizes (NodeT * Node=[], unsigned Nodes, unsigned CurSize=[], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned NewSize=[])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a1edda7c684a88b0c8aa8480aa869451b">IntervalMapImpl::adjustSiblingSizes</a> - Move elements between sibling nodes.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/node"&gt;Node&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>Array of pointers to sibling nodes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Nodes</td>
<td class="doxyParamItemDescription"><p>Number of nodes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CurSize</td>
<td class="doxyParamItemDescription"><p>Array of current node sizes, will be overwritten.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NewSize</td>
<td class="doxyParamItemDescription"><p>Array of desired node sizes.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### distribute() {#adc507d70d9385ae35dcdb70dc1bebc19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IdxPair llvm::IntervalMapImpl::distribute (unsigned Nodes, unsigned Elements, unsigned Capacity, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned * CurSize, unsigned NewSize=[], unsigned Position, bool Grow)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#adc507d70d9385ae35dcdb70dc1bebc19">IntervalMapImpl::distribute</a> - Compute a new distribution of node elements after an overflow or underflow.</p>


<p>Reserve space for a new element at Position, and compute the node that will hold Position after redistributing node elements.</p>


<p>It is required that</p>


<p>Elements == sum(CurSize), and Elements + Grow &lt;= Nodes * Capacity.</p>


<p>NewSize[] will be filled in such that:</p>


<p>sum(NewSize) == Elements, and NewSize[i] &lt;= Capacity.</p>


<p>The returned index is the node where Position will go, so:</p>


<p>sum(NewSize[0..idx-1]) &lt;= Position sum(NewSize[0..idx]) &gt;= Position</p>


<p>The last equality, sum(NewSize[0..idx]) == Position, can only happen when Grow is set and NewSize[idx] == Capacity-1. The index points to the node before the one holding the Position'th element where there is room for an insertion.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Nodes</td>
<td class="doxyParamItemDescription"><p>The number of nodes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Elements</td>
<td class="doxyParamItemDescription"><p>Total elements in all nodes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Capacity</td>
<td class="doxyParamItemDescription"><p>The capacity of each node.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CurSize</td>
<td class="doxyParamItemDescription"><p>Array[Nodes] of current node sizes, or NULL.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NewSize</td>
<td class="doxyParamItemDescription"><p>Array[Nodes] to receive the new node sizes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Position</td>
<td class="doxyParamItemDescription"><p>Insert position.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Grow</td>
<td class="doxyParamItemDescription"><p>Reserve space for a new element at Position.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>(node, offset) for Position.</p></dd>
</dl>


<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/support/intervalmap-cpp">IntervalMap.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intervalmap-h">IntervalMap.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/intervalmap-cpp">IntervalMap.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
