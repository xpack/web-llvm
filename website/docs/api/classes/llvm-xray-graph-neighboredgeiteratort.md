---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/xray/graph/neighboredgeiteratort
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `NeighborEdgeIteratorT` Class Template

<p>An Iterator adapter using an InnerInvGraphT::iterator as a base iterator, and storing the <a href="/web-llvm/docs/api/classes/llvm/xray/graph/#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a> the iterator range comes from. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;bool IsConst, bool IsOut, typename BaseIt = typename NeighborSetT::const_iterator, typename T = std::conditional_t&lt;IsConst, const EdgeValueType, EdgeValueType&gt;&gt;
class llvm::xray::Graph::NeighborEdgeIteratorT&lt;IsConst, IsOut, BaseIt, T&gt; { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-adaptor-base">iterator_adaptor_base&lt;DerivedT, WrappedIteratorT, IteratorCategoryT, T, DifferenceTypeT, PointerT, ReferenceT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CRTP base class for adapting an iterator to a different type. <a href="/web-llvm/docs/api/classes/llvm/iterator-adaptor-base/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0d6a83803c8c0371605b537a14ed93bd">InternalEdgeMapT</a> = std::conditional_t&lt; IsConst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">EdgeMapT</a>, <a href="/web-llvm/docs/api/classes/llvm/densemap">EdgeMapT</a> &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a883af30517d0609b29d64ae510f6a666">NeighborEdgeIteratorT&lt; false, IsOut, BaseIt, EdgeValueType &gt;</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a14314d8b98f71c3ab54b862043a883b6">NeighborEdgeIteratorT&lt; true, IsOut, BaseIt, const EdgeValueType &gt;</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a1e1da1429aa7620847e1e55da72a710b">NeighborEdgeIteratorT</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ac7d91c5c59468678f1297f67f0b93e8c">NeighborEdgeIteratorT</a> (BaseIt _I, InternalEdgeMapT *_MP, VertexIdentifier _SI)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ab430523380c4d472b707b7cd5ec66d59">operator NeighborEdgeIteratorT&lt; IsConstDest, IsOut, BaseIt, const EdgeValueType &gt;</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3df376e2f288cc6f7762cfe9c40f19af">operator*</a> () const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">InternalEdgeMapT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6c676174c2f30fda9b13cadb3ae1dbbe">MP</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/xray/graph/#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a25ba8f1bd56f8872ee88ed4b9e16a68f">SI</a></td>
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

<p>An Iterator adapter using an InnerInvGraphT::iterator as a base iterator, and storing the <a href="/web-llvm/docs/api/classes/llvm/xray/graph/#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a> the iterator range comes from.</p>


<p>The dereference operator is then performed using a pointer to the graph's edge set.</p>


<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### InternalEdgeMapT {#a0d6a83803c8c0371605b537a14ed93bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsConst, bool IsOut, typename BaseIt = typename NeighborSetT::const_iterator, typename T = std::conditional_t&lt;IsConst, const EdgeValueType, EdgeValueType&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::NeighborEdgeIteratorT&lt; IsConst, IsOut, BaseIt, T &gt;::InternalEdgeMapT = 
        std::conditional_t&lt;IsConst, const EdgeMapT, EdgeMapT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### NeighborEdgeIteratorT&lt; false, IsOut, BaseIt, EdgeValueType &gt; {#a883af30517d0609b29d64ae510f6a666}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class NeighborEdgeIteratorT&lt; false, IsOut, BaseIt, <a href="/web-llvm/docs/api/classes/llvm/xray/graph/#af3591e0d96718a0f1b28a7e3b7d8705a">EdgeValueType</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### NeighborEdgeIteratorT&lt; true, IsOut, BaseIt, const EdgeValueType &gt; {#a14314d8b98f71c3ab54b862043a883b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class NeighborEdgeIteratorT&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, IsOut, BaseIt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/xray/graph/#af3591e0d96718a0f1b28a7e3b7d8705a">EdgeValueType</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### NeighborEdgeIteratorT() {#a1e1da1429aa7620847e1e55da72a710b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsConst, bool IsOut, typename BaseIt = typename NeighborSetT::const_iterator, typename T = std::conditional_t&lt;IsConst, const EdgeValueType, EdgeValueType&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::NeighborEdgeIteratorT&lt; IsConst, IsOut, BaseIt, T &gt;::NeighborEdgeIteratorT ()</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### NeighborEdgeIteratorT() {#ac7d91c5c59468678f1297f67f0b93e8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsConst, bool IsOut, typename BaseIt = typename NeighborSetT::const_iterator, typename T = std::conditional_t&lt;IsConst, const EdgeValueType, EdgeValueType&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::NeighborEdgeIteratorT&lt; IsConst, IsOut, BaseIt, T &gt;::NeighborEdgeIteratorT (BaseIt _I, InternalEdgeMapT * _MP, <a href="/web-llvm/docs/api/classes/llvm/xray/graph/#aa7d4f1e9198ebd47ab0fc3cef797ac86">VertexIdentifier</a> _SI)</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator NeighborEdgeIteratorT&lt; IsConstDest, IsOut, BaseIt, const EdgeValueType &gt;() {#ab430523380c4d472b707b7cd5ec66d59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsConstDest, typename = std::enable_if_t&lt;IsConstDest &amp;&amp; !IsConst&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::NeighborEdgeIteratorT&lt; IsConst, IsOut, BaseIt, T &gt;::operator NeighborEdgeIteratorT&lt; IsConstDest, IsOut, BaseIt, const EdgeValueType &gt; ()</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### operator\*() {#a3df376e2f288cc6f7762cfe9c40f19af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsConst, bool IsOut, typename BaseIt = typename NeighborSetT::const_iterator, typename T = std::conditional_t&lt;IsConst, const EdgeValueType, EdgeValueType&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T &amp; llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::NeighborEdgeIteratorT&lt; IsConst, IsOut, BaseIt, T &gt;::operator* ()</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MP {#a6c676174c2f30fda9b13cadb3ae1dbbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsConst, bool IsOut, typename BaseIt = typename NeighborSetT::const_iterator, typename T = std::conditional_t&lt;IsConst, const EdgeValueType, EdgeValueType&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InternalEdgeMapT* llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::NeighborEdgeIteratorT&lt; IsConst, IsOut, BaseIt, T &gt;::MP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

### SI {#a25ba8f1bd56f8872ee88ed4b9e16a68f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsConst, bool IsOut, typename BaseIt = typename NeighborSetT::const_iterator, typename T = std::conditional_t&lt;IsConst, const EdgeValueType, EdgeValueType&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VertexIdentifier llvm::xray::Graph&lt; VertexAttribute, EdgeAttribute, VI &gt;::NeighborEdgeIteratorT&lt; IsConst, IsOut, BaseIt, T &gt;::SI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/graph-h">Graph.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
