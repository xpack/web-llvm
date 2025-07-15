---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/lazycallgraph/refscc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RefSCC` Class Reference

<p>A <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> of the call graph. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LazyCallGraph::RefSCC { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">llvm/Analysis/LazyCallGraph.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad85b2ad566b56110886f3c39653b88fa">iterator</a> = <a href="/web-llvm/docs/api/structs/llvm/pointee-iterator">pointee_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> * &gt;::const_iterator &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69b7350ecfd665c8008e5a47c6734c87">range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ad85b2ad566b56110886f3c39653b88fa">iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8fea2aaa35fad7cf415558c8b753288">parent_iterator</a> = <a href="/web-llvm/docs/api/structs/llvm/pointee-iterator">pointee_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> * &gt;::const_iterator &gt;</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81774ea46253e6427d63a610bd624c08">LazyCallGraph</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a7a57d977301c68294ee8d4c92543ce">LazyCallGraph::Node</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae06c7c08f7da5bc7d384c81be0b83910">operator&lt;&lt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print a short description useful for debugging or logging. <a href="#ae06c7c08f7da5bc7d384c81be0b83910">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5fb8a48f9e09ffb93f285d7e121af7d">RefSCC</a> (LazyCallGraph &amp;G)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fast-path constructor. <a href="#ab5fb8a48f9e09ffb93f285d7e121af7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a571517d23e9e5252dc87f5c23e7105f2">operator[]</a> (int Idx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad85b2ad566b56110886f3c39653b88fa">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc4aeec51553504ba50594d9fb8ac4b1">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad85b2ad566b56110886f3c39653b88fa">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbbe8357e4c4fef5f9b7809b41abcdcd">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ssize_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac62cb27d2f0946c9febb1e1d1e377f55">size</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad85b2ad566b56110886f3c39653b88fa">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51f7db86dd464b937f03aab0fbf51506">find</a> (SCC &amp;C) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af952e1ffaf5cd4bd83b63cf7fb4cb068">isParentOf</a> (const RefSCC &amp;RC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> is a parent of <em>RC</em>. <a href="#af952e1ffaf5cd4bd83b63cf7fb4cb068">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35a8d25c6df3f1d3bc5faba32de1dd55">isAncestorOf</a> (const RefSCC &amp;RC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> is an ancestor of <em>RC</em>. <a href="#a35a8d25c6df3f1d3bc5faba32de1dd55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c04e8da471c500d025dfdf206c24ed2">isChildOf</a> (const RefSCC &amp;RC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> is a child of <em>RC</em>. <a href="#a5c04e8da471c500d025dfdf206c24ed2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59f6c7fa7f420326cc1f7026e51b0668">isDescendantOf</a> (const RefSCC &amp;RC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> is a descendant of <em>RC</em>. <a href="#a59f6c7fa7f420326cc1f7026e51b0668">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac30dc61a31f34e7359336fa637104bfb">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide a short name by printing this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> to a std::string. <a href="#ac30dc61a31f34e7359336fa637104bfb">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab484ec648a8540467efe37c71d1531ff">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21ed0a8438a4d6b61af5c4832b4d0124">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump a short description of this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> to stderr. <a href="#a21ed0a8438a4d6b61af5c4832b4d0124">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a992480861cbbf2f720a27e2b56700682">verify</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify invariants about the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> and all its SCCs. <a href="#a992480861cbbf2f720a27e2b56700682">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a258d60676d3507f4371f54614265c4c5">G</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64f45fde9dbe447ac0e25a3c83bd00bf">SCCs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A postorder list of the inner SCCs. <a href="#a64f45fde9dbe447ac0e25a3c83bd00bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> *, int, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2e66513096a8568624f8bb6177df0df">SCCIndices</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A map from <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> to index in the postorder list. <a href="#ae2e66513096a8568624f8bb6177df0df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Mutation API Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2957918db7f91f405b11d92c1ebf3b0f">switchInternalEdgeToCall</a> (Node &amp;SourceN, Node &amp;TargetN, function_ref&lt; void(ArrayRef&lt; SCC * &gt; MergedSCCs)&gt; MergeCB={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make an existing internal ref edge into a call edge. <a href="#a2957918db7f91f405b11d92c1ebf3b0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2f9bc7458beec4389ccf7fb88199d4b">switchTrivialInternalEdgeToRef</a> (Node &amp;SourceN, Node &amp;TargetN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make an existing internal call edge between separate SCCs into a ref edge. <a href="#ae2f9bc7458beec4389ccf7fb88199d4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ad85b2ad566b56110886f3c39653b88fa">iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96fe0cb15ded58bd1824fa4e3daec680">switchInternalEdgeToRef</a> (Node &amp;SourceN, Node &amp;TargetN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make an existing internal call edge within a single <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> into a ref edge. <a href="#a96fe0cb15ded58bd1824fa4e3daec680">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cc0541c3ee15c565ac05fe11f5459d2">switchOutgoingEdgeToCall</a> (Node &amp;SourceN, Node &amp;TargetN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make an existing outgoing ref edge into a call edge. <a href="#a5cc0541c3ee15c565ac05fe11f5459d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adce8df277d53b4d87581583c8269ac71">switchOutgoingEdgeToRef</a> (Node &amp;SourceN, Node &amp;TargetN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make an existing outgoing call edge into a ref edge. <a href="#adce8df277d53b4d87581583c8269ac71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa57986c798b44affab5e4d5953e37727">insertInternalRefEdge</a> (Node &amp;SourceN, Node &amp;TargetN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a ref edge from one node in this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> to another in this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a>. <a href="#aa57986c798b44affab5e4d5953e37727">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a743c2ac21f2f8a8c6af18e1e09f13229">insertOutgoingEdge</a> (Node &amp;SourceN, Node &amp;TargetN, Edge::Kind EK)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert an edge whose parent is in this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> and child is in some child <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a>. <a href="#a743c2ac21f2f8a8c6af18e1e09f13229">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> *, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01b1581633bb40f86d6dc62a1c1a7f72">insertIncomingRefEdge</a> (Node &amp;SourceN, Node &amp;TargetN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert an edge whose source is in a descendant <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> and target is in this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a>. <a href="#a01b1581633bb40f86d6dc62a1c1a7f72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab130250bcdaefbfd3c583cad7b120b62">removeOutgoingEdge</a> (Node &amp;SourceN, Node &amp;TargetN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove an edge whose source is in this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> and target is <em>not</em>. <a href="#ab130250bcdaefbfd3c583cad7b120b62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> *, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87dd1a69c8d8492e78b32708ceacb2c6">removeInternalRefEdges</a> (ArrayRef&lt; std::pair&lt; Node *, Node * &gt; &gt; Edges)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a list of ref edges which are entirely within this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a>. <a href="#a87dd1a69c8d8492e78b32708ceacb2c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf3ba7d78f09755223609e4978bebef7">insertTrivialCallEdge</a> (Node &amp;SourceN, Node &amp;TargetN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A convenience wrapper around the above to handle trivial cases of inserting a new call edge. <a href="#aaf3ba7d78f09755223609e4978bebef7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a393b4565f554b9d8382c8f610b7f2ce7">insertTrivialRefEdge</a> (Node &amp;SourceN, Node &amp;TargetN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A convenience wrapper around the above to handle trivial cases of inserting a new ref edge. <a href="#a393b4565f554b9d8382c8f610b7f2ce7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70f7f0574edbfc0f75424499133d4ba3">replaceNodeFunction</a> (Node &amp;N, Function &amp;NewF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Directly replace a node's function with a new function. <a href="#a70f7f0574edbfc0f75424499133d4ba3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> of the call graph.</p>


<p>This models a Strongly Connected Component of function reference edges in the call graph. As opposed to actual SCCs, these can be used to scope subgraphs of the module which are independent from other subgraphs of the module because they do not reference it in any way. This is also the unit where we do mutation of the graph in order to restrict mutations to those which don't violate this independence.</p>


<p>A <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> contains a DAG of actual SCCs. All the nodes within the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> are necessarily within some actual <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> that nests within it. Since a direct call <em>is</em> a reference, there will always be at least one <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> around any <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a>.</p>


<p>Spurious ref edges, meaning ref edges that still exist in the call graph even though the corresponding IR reference no longer exists, are allowed. This is mostly to support argument promotion, which can modify a caller to no longer pass a function. The only place that needs to specially handle this is deleting a dead function/node, otherwise the dead ref edges are automatically removed when visiting the function/node no longer containing the ref edge.</p>


<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#ad85b2ad566b56110886f3c39653b88fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LazyCallGraph::RefSCC::iterator =  pointee_iterator&lt;SmallVectorImpl&lt;SCC *&gt;::const_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### parent\_iterator {#ad8fea2aaa35fad7cf415558c8b753288}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LazyCallGraph::RefSCC::parent_iterator = 
        pointee_iterator&lt;SmallPtrSetImpl&lt;RefSCC *&gt;::const_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### range {#a69b7350ecfd665c8008e5a47c6734c87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LazyCallGraph::RefSCC::range =  iterator_range&lt;iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### LazyCallGraph {#a81774ea46253e6427d63a610bd624c08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="#a81774ea46253e6427d63a610bd624c08">LazyCallGraph</a>.</p>


<p>Referenced by <a href="#a81774ea46253e6427d63a610bd624c08">LazyCallGraph</a> and <a href="#a3a7a57d977301c68294ee8d4c92543ce">LazyCallGraph::Node</a>.</p>

</div>
</div>

### LazyCallGraph::Node {#a3a7a57d977301c68294ee8d4c92543ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">LazyCallGraph::Node</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="#a81774ea46253e6427d63a610bd624c08">LazyCallGraph</a>.</p>


<p>Referenced by <a href="#a01b1581633bb40f86d6dc62a1c1a7f72">insertIncomingRefEdge</a>, <a href="#aa57986c798b44affab5e4d5953e37727">insertInternalRefEdge</a>, <a href="#a743c2ac21f2f8a8c6af18e1e09f13229">insertOutgoingEdge</a>, <a href="#aaf3ba7d78f09755223609e4978bebef7">insertTrivialCallEdge</a>, <a href="#a393b4565f554b9d8382c8f610b7f2ce7">insertTrivialRefEdge</a>, <a href="#a35a8d25c6df3f1d3bc5faba32de1dd55">isAncestorOf</a>, <a href="#af952e1ffaf5cd4bd83b63cf7fb4cb068">isParentOf</a>, <a href="#a87dd1a69c8d8492e78b32708ceacb2c6">removeInternalRefEdges</a>, <a href="#ab130250bcdaefbfd3c583cad7b120b62">removeOutgoingEdge</a>, <a href="#a70f7f0574edbfc0f75424499133d4ba3">replaceNodeFunction</a>, <a href="#a2957918db7f91f405b11d92c1ebf3b0f">switchInternalEdgeToCall</a>, <a href="#a96fe0cb15ded58bd1824fa4e3daec680">switchInternalEdgeToRef</a>, <a href="#a5cc0541c3ee15c565ac05fe11f5459d2">switchOutgoingEdgeToCall</a>, <a href="#adce8df277d53b4d87581583c8269ac71">switchOutgoingEdgeToRef</a> and <a href="#ae2f9bc7458beec4389ccf7fb88199d4b">switchTrivialInternalEdgeToRef</a>.</p>

</div>
</div>

### operator&lt;&lt; {#ae06c7c08f7da5bc7d384c81be0b83910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> &amp; RC</td>
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

<p>Print a short description useful for debugging or logging.</p>


<p>We print the SCCs wrapped in '[]'s and skipping the middle SCCs if there are a large number.</p>


<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### RefSCC() {#ab5fb8a48f9e09ffb93f285d7e121af7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallGraph::RefSCC::RefSCC (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fast-path constructor.</p>


<p>RefSCCs should instead be constructed by calling formRefSCCFast on the graph itself.</p>


<p>Declaration at line 555 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#a571517d23e9e5252dc87f5c23e7105f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCC &amp; llvm::LazyCallGraph::RefSCC::operator[] (int Idx)</td>
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



<p>Definition at line 614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#acc4aeec51553504ba50594d9fb8ac4b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::LazyCallGraph::RefSCC::begin ()</td>
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



<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#a97b7a3d43f4f6eb3ab16554f56bd0cc4">llvm::LazyCallGraph::removeDeadFunctions</a>.</p>

</div>
</div>

### end() {#acbbe8357e4c4fef5f9b7809b41abcdcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::LazyCallGraph::RefSCC::end ()</td>
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



<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### find() {#a51f7db86dd464b937f03aab0fbf51506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::LazyCallGraph::RefSCC::find (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> &amp; C)</td>
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



<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### getName() {#ac30dc61a31f34e7359336fa637104bfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::LazyCallGraph::RefSCC::getName ()</td>
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

<p>Provide a short name by printing this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> to a std::string.</p>


<p>This copes with the fact that we don't have a name per se for an <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> while still making the use of this in debugging and logging useful.</p>


<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>.</p>

</div>
</div>

### isAncestorOf() {#a35a8d25c6df3f1d3bc5faba32de1dd55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LazyCallGraph::RefSCC::isAncestorOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> &amp; RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> is an ancestor of <em>RC</em>.</p>


<p>CAUTION: This method walks the directed graph of edges as far as necessary to find a possible path to the argument. In the worst case this may walk the entire graph and can be extremely expensive.</p>


<p>Declaration at line 631 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#a3a7a57d977301c68294ee8d4c92543ce">LazyCallGraph::Node</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a59f6c7fa7f420326cc1f7026e51b0668">isDescendantOf</a>.</p>

</div>
</div>

### isChildOf() {#a5c04e8da471c500d025dfdf206c24ed2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LazyCallGraph::RefSCC::isChildOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> &amp; RC)</td>
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

<p>Test if this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> is a child of <em>RC</em>.</p>


<p>CAUTION: This method walks every edge in the argument <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a></span>, it can be very expensive.</p>


<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="#af952e1ffaf5cd4bd83b63cf7fb4cb068">isParentOf</a>.</p>

</div>
</div>

### isDescendantOf() {#a59f6c7fa7f420326cc1f7026e51b0668}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LazyCallGraph::RefSCC::isDescendantOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> &amp; RC)</td>
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

<p>Test if this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> is a descendant of <em>RC</em>.</p>


<p>CAUTION: This method walks the directed graph of edges as far as necessary to find a possible path from the argument. In the worst case this may walk the entire graph and can be extremely expensive.</p>


<p>Definition at line 644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="#a35a8d25c6df3f1d3bc5faba32de1dd55">isAncestorOf</a>.</p>


<p>Referenced by <a href="#a01b1581633bb40f86d6dc62a1c1a7f72">insertIncomingRefEdge</a>.</p>

</div>
</div>

### isParentOf() {#af952e1ffaf5cd4bd83b63cf7fb4cb068}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LazyCallGraph::RefSCC::isParentOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> &amp; RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> is a parent of <em>RC</em>.</p>


<p>CAUTION: This method walks every edge in the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a></span>, it can be very expensive.</p>


<p>Declaration at line 624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a3a7a57d977301c68294ee8d4c92543ce">LazyCallGraph::Node</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a5c04e8da471c500d025dfdf206c24ed2">isChildOf</a>.</p>

</div>
</div>

### size() {#ac62cb27d2f0946c9febb1e1d1e377f55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ssize_t llvm::LazyCallGraph::RefSCC::size ()</td>
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



<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#a72787ab6acfbe504a11ca1d927513356">llvm::LazyCallGraph::buildRefSCCs</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#a97b7a3d43f4f6eb3ab16554f56bd0cc4">llvm::LazyCallGraph::removeDeadFunctions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### clear() {#ab484ec648a8540467efe37c71d1531ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LazyCallGraph::RefSCC::clear ()</td>
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



<p>Definition at line 557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### dump() {#a21ed0a8438a4d6b61af5c4832b4d0124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void LazyCallGraph::RefSCC::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump a short description of this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> to stderr.</p>

<p>Declaration at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>

</div>
</div>

### verify() {#a992480861cbbf2f720a27e2b56700682}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::RefSCC::verify ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify invariants about the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> and all its SCCs.</p>


<p>This will attempt to validate all of the invariants <em>within</em> the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a>, but not that it is a strongly connected component of the larger graph. This makes it useful even when partially through an update.</p>


<p>Invariants checked:</p>


<ul class="doxyList ">
<li>SCCs and their indices match.</li>
<li>The SCCs list is in fact in post-order.</li>
</ul>

<p>Declaration at line 600 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### G {#a258d60676d3507f4371f54614265c4c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallGraph* llvm::LazyCallGraph::RefSCC::G</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### SCCIndices {#ae2e66513096a8568624f8bb6177df0df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;SCC *, int, 4&gt; llvm::LazyCallGraph::RefSCC::SCCIndices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A map from <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> to index in the postorder list.</p>

<p>Definition at line 551 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### SCCs {#a64f45fde9dbe447ac0e25a3c83bd00bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SCC *, 4&gt; llvm::LazyCallGraph::RefSCC::SCCs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A postorder list of the inner SCCs.</p>

<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Mutation API



<p>These methods provide the core API for updating the call graph in the presence of (potentially still in-flight) DFS-found RefSCCs and SCCs.</p>


<p>Note that these methods sometimes have complex runtimes, so be careful how you call them.</p>


### insertIncomingRefEdge {#a01b1581633bb40f86d6dc62a1c1a7f72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; LazyCallGraph::RefSCC *, 1 &gt; LazyCallGraph::RefSCC::insertIncomingRefEdge (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; SourceN, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; TargetN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert an edge whose source is in a descendant <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> and target is in this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a>.</p>


<p>There must be an existing path from the target to the source in this case.</p>


<p>NB! This is has the potential to be a very expensive function. It inherently forms a cycle in the prior <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> DAG and we have to merge RefSCCs to resolve that cycle. But finding all of the RefSCCs which participate in the cycle can in the worst case require traversing every <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> in the graph. Every attempt is made to avoid that, but passes must still exercise caution calling this routine repeatedly.</p>


<p>Also note that this can only insert ref edges. In order to insert a call edge, first insert a ref edge and then switch it to a call edge. These are intentionally kept as separate interfaces because each step of the operation invalidates a different set of data structures.</p>


<p>This returns all the RefSCCs which were merged into the this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> (the target's). This allows callers to invalidate any cached information.</p>


<p>FIXME: We could possibly optimize this quite a bit for cases where the caller and callee are very nearby in the graph. See comments in the implementation for details, but that use case might impact users.</p>


<p>Declaration at line 778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 1006 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/iterator-range/#af5a020bd9dd7bc8487dd53ce443fdd8f">llvm::iterator_range&lt; IteratorT &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/iterator-range/#aa0344673da91896d39f1b35755ee5d4e">llvm::iterator_range&lt; IteratorT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#a59f6c7fa7f420326cc1f7026e51b0668">isDescendantOf</a>, <a href="#a3a7a57d977301c68294ee8d4c92543ce">LazyCallGraph::Node</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af45c4dc83c083c5ae914d96fd3ce96">llvm::make_scope_exit</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13a81845d1d6d0f58deb757fad1e739c32c">llvm::LazyCallGraph::Edge::Ref</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#a88f678a123e3721551a1b867ed4b021c">updatePostorderSequenceForEdgeInsertion</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#aea1129b8892c0b3869793b0354270544">llvm::LazyCallGraph::verify</a>.</p>

</div>
</div>

### insertInternalRefEdge {#aa57986c798b44affab5e4d5953e37727}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::RefSCC::insertInternalRefEdge (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; SourceN, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; TargetN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a ref edge from one node in this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> to another in this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a>.</p>


<p>This is always a trivial operation as it doesn't change any part of the graph structure besides connecting the two nodes.</p>


<p>Note that we don't support directly inserting internal <em>call</em> edges because that could change the graph structure and requires returning information about what became invalid. As a consequence, the pattern should be to first insert the necessary ref edge, and then to switch it to a call edge if needed and handle any invalidation that results. See the <span class="doxyComputerOutput">switchInternalEdgeToCall</span> routine for details.</p>


<p>Declaration at line 743 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 974 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3a7a57d977301c68294ee8d4c92543ce">LazyCallGraph::Node</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13a81845d1d6d0f58deb757fad1e739c32c">llvm::LazyCallGraph::Edge::Ref</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#aea1129b8892c0b3869793b0354270544">llvm::LazyCallGraph::verify</a>.</p>

</div>
</div>

### insertOutgoingEdge {#a743c2ac21f2f8a8c6af18e1e09f13229}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::RefSCC::insertOutgoingEdge (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; SourceN, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; TargetN, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13">Edge::Kind</a> EK)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert an edge whose parent is in this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> and child is in some child <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a>.</p>


<p>There must be an existing path from the <span class="doxyComputerOutput">SourceN</span> to the <span class="doxyComputerOutput">TargetN</span>. This operation is inexpensive and does not change the set of SCCs and RefSCCs in the graph.</p>


<p>Declaration at line 751 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 986 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3a7a57d977301c68294ee8d4c92543ce">LazyCallGraph::Node</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#aea1129b8892c0b3869793b0354270544">llvm::LazyCallGraph::verify</a>.</p>

</div>
</div>

### insertTrivialCallEdge {#aaf3ba7d78f09755223609e4978bebef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::RefSCC::insertTrivialCallEdge (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; SourceN, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; TargetN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A convenience wrapper around the above to handle trivial cases of inserting a new call edge.</p>


<p>This is trivial whenever the target is in the same <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> as the source or the edge is an outgoing edge to some descendant <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a>. In these cases there is no change to the cyclic structure of SCCs or RefSCCs.</p>


<p>To further make calling this convenient, it also handles inserting already existing edges.</p>


<p>Declaration at line 843 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 1395 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13a13b74fdca959e0c5da734f789b298cf6">llvm::LazyCallGraph::Edge::Call</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="#a3a7a57d977301c68294ee8d4c92543ce">LazyCallGraph::Node</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af45c4dc83c083c5ae914d96fd3ce96">llvm::make_scope_exit</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#aea1129b8892c0b3869793b0354270544">llvm::LazyCallGraph::verify</a>.</p>

</div>
</div>

### insertTrivialRefEdge {#a393b4565f554b9d8382c8f610b7f2ce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::RefSCC::insertTrivialRefEdge (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; SourceN, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; TargetN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A convenience wrapper around the above to handle trivial cases of inserting a new ref edge.</p>


<p>This is trivial whenever the target is in the same <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> as the source or the edge is an outgoing edge to some descendant <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a>. In these cases there is no change to the cyclic structure of the RefSCCs.</p>


<p>To further make calling this convenient, it also handles inserting already existing edges.</p>


<p>Declaration at line 854 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 1424 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="#a3a7a57d977301c68294ee8d4c92543ce">LazyCallGraph::Node</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af45c4dc83c083c5ae914d96fd3ce96">llvm::make_scope_exit</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13a81845d1d6d0f58deb757fad1e739c32c">llvm::LazyCallGraph::Edge::Ref</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#aea1129b8892c0b3869793b0354270544">llvm::LazyCallGraph::verify</a>.</p>

</div>
</div>

### removeInternalRefEdges {#a87dd1a69c8d8492e78b32708ceacb2c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; LazyCallGraph::RefSCC *, 1 &gt; LazyCallGraph::RefSCC::removeInternalRefEdges (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> *, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> * &gt; &gt; Edges)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove a list of ref edges which are entirely within this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a>.</p>


<p>Both the <em>SourceN</em> and all of the <em>TargetNs</em> must be within this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a>. Removing these edges may break cycles that form this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> and thus this operation may change the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> graph significantly. In particular, this operation will re-form new RefSCCs based on the remaining connectivity of the graph. The following invariants are guaranteed to hold after calling this method:</p>


<p>1) If a ref-cycle remains after removal, it leaves this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> intact and in the graph. No new RefSCCs are built. 2) Otherwise, this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> will be dead after this call and no longer in the graph or the postorder traversal of the call graph. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> iterator pointing at this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> will become invalid. 3) All newly formed RefSCCs will be returned and the order of the RefSCCs returned will be a valid postorder traversal of the new RefSCCs. 4) No <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> other than this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> has its member set changed (this is inherent in the definition of removing such an edge).</p>


<p>These invariants are very important to ensure that we can build optimization pipelines on top of the CGSCC pass manager which intelligently update the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> graph without invalidating other parts of the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> graph.</p>


<p>Note that we provide no routine to remove a <em>call</em> edge. Instead, you must first switch it to a ref edge using <span class="doxyComputerOutput">switchInternalEdgeToRef</span>. This split API is intentional as each of these two steps can invalidate a different aspect of the graph structure and needs to have the invalidation handled independently.</p>


<p>The runtime complexity of this method is, in the worst case, O(V+E) where V is the number of nodes in this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> and E is the number of edges leaving the nodes in this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a>. Note that E includes both edges within this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> and edges from this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> to child RefSCCs. Some effort has been made to minimize the overhead of common cases such as self-edges and edge removals which result in a spanning tree with no more cycles.</p>


<p>Declaration at line 832 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 1165 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edgesequence/#a64d53c120b022f979edf7718f33d77aa">llvm::LazyCallGraph::EdgeSequence::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edgesequence/#a4d46ac540030f05b75b6e525b5cbc7f8">llvm::LazyCallGraph::EdgeSequence::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::SmallVectorImpl&lt; T &gt;::erase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a3a7a57d977301c68294ee8d4c92543ce">LazyCallGraph::Node</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af45c4dc83c083c5ae914d96fd3ce96">llvm::make_scope_exit</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#aea1129b8892c0b3869793b0354270544">llvm::LazyCallGraph::verify</a>.</p>

</div>
</div>

### removeOutgoingEdge {#ab130250bcdaefbfd3c583cad7b120b62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::RefSCC::removeOutgoingEdge (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; SourceN, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; TargetN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove an edge whose source is in this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> and target is <em>not</em>.</p>


<p>This removes an inter-RefSCC edge. All inter-RefSCC edges originating from this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> have been fully explored by any in-flight DFS graph formation, so this is always safe to call once you have the source <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a>.</p>


<p>This operation does not change the cyclic structure of the graph and so is very inexpensive. It may change the connectivity graph of the SCCs though, so be careful calling this while iterating over them.</p>


<p>Declaration at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 1147 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3a7a57d977301c68294ee8d4c92543ce">LazyCallGraph::Node</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af45c4dc83c083c5ae914d96fd3ce96">llvm::make_scope_exit</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#aea1129b8892c0b3869793b0354270544">llvm::LazyCallGraph::verify</a>.</p>

</div>
</div>

### replaceNodeFunction {#a70f7f0574edbfc0f75424499133d4ba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::RefSCC::replaceNodeFunction (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; N, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; NewF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Directly replace a node's function with a new function.</p>


<p>This should be used when moving the body and users of a function to a new formal function object but not otherwise changing the call graph structure in any way.</p>


<p>It requires that the old function in the provided node have zero uses and the new function must have calls and references to it establishing an equivalent graph.</p>


<p>Declaration at line 865 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 1448 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3a7a57d977301c68294ee8d4c92543ce">LazyCallGraph::Node</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af45c4dc83c083c5ae914d96fd3ce96">llvm::make_scope_exit</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#aea1129b8892c0b3869793b0354270544">llvm::LazyCallGraph::verify</a>.</p>

</div>
</div>

### switchInternalEdgeToCall {#a2957918db7f91f405b11d92c1ebf3b0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LazyCallGraph::RefSCC::switchInternalEdgeToCall (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; SourceN, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; TargetN, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> * &gt; MergedSCCs)&gt; MergeCB={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make an existing internal ref edge into a call edge.</p>


<p>This may form a larger cycle and thus collapse SCCs into TargetN's <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a>. If that happens, the optional callback <span class="doxyComputerOutput">MergedCB</span> will be invoked (if provided) on the SCCs being merged away prior to actually performing the merge. Note that this will never include the target <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> as that will be the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> functions are merged into to resolve the cycle. Once this function returns, these merged SCCs are not in a valid state but the pointers will remain valid until destruction of the parent graph instance for the purpose of clearing cached information. This function also returns 'true' if a cycle was formed and some SCCs merged away as a convenience.</p>


<p>After this operation, both SourceN's <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> and TargetN's <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> may move position within this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a>'s postorder list. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> SCCs merged are merged into the TargetN's <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> in order to preserve reachability analyses which took place on that <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a>.</p>


<p>Declaration at line 686 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13a13b74fdca959e0c5da734f789b298cf6">llvm::LazyCallGraph::Edge::Call</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc/#aef7abf8c91d56934fe4097746f8e5c30">llvm::LazyCallGraph::SCC::getOuterRefSCC</a>, <a href="#a3a7a57d977301c68294ee8d4c92543ce">LazyCallGraph::Node</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af45c4dc83c083c5ae914d96fd3ce96">llvm::make_scope_exit</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#a88f678a123e3721551a1b867ed4b021c">updatePostorderSequenceForEdgeInsertion</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#aea1129b8892c0b3869793b0354270544">llvm::LazyCallGraph::verify</a>.</p>

</div>
</div>

### switchInternalEdgeToRef {#a96fe0cb15ded58bd1824fa4e3daec680}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; LazyCallGraph::RefSCC::iterator &gt; LazyCallGraph::RefSCC::switchInternalEdgeToRef (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; SourceN, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; TargetN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make an existing internal call edge within a single <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> into a ref edge.</p>


<p>Since SourceN and TargetN are part of a single <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a>, this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> may be split up due to breaking a cycle in the call edges that formed it. If that happens, then this routine will insert new SCCs into the postorder list <em>before</em> the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> of TargetN (previously the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> of both). This preserves postorder as the TargetN can reach all of the other nodes by definition of previously being in a single <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> formed by the cycle from SourceN to TargetN.</p>


<p>The newly added SCCs are added <em>immediately</em> and contiguously prior to the TargetN <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> and return the range covering the new SCCs in the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a>'s postorder sequence. You can directly iterate the returned range to observe all of the new SCCs in postorder.</p>


<p>Note that if SourceN and TargetN are in separate SCCs, the simpler routine <span class="doxyComputerOutput">switchTrivialInternalEdgeToRef</span> should be used instead.</p>


<p>Declaration at line 716 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 752 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::SmallVectorImpl&lt; T &gt;::erase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a3a7a57d977301c68294ee8d4c92543ce">LazyCallGraph::Node</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af45c4dc83c083c5ae914d96fd3ce96">llvm::make_scope_exit</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a23aab542398091e1fcfd46b6006d64ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::rbegin</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13a81845d1d6d0f58deb757fad1e739c32c">llvm::LazyCallGraph::Edge::Ref</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc/#a5592b0404f95c589801ea255fa95fb63">llvm::LazyCallGraph::SCC::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#abd962b7b01f49ce61ea41ee10c49e313">llvm::SmallVectorImpl&lt; T &gt;::swap</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#aea1129b8892c0b3869793b0354270544">llvm::LazyCallGraph::verify</a>.</p>

</div>
</div>

### switchOutgoingEdgeToCall {#a5cc0541c3ee15c565ac05fe11f5459d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::RefSCC::switchOutgoingEdgeToCall (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; SourceN, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; TargetN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make an existing outgoing ref edge into a call edge.</p>


<p>Note that this is trivial as there are no cyclic impacts and there remains a reference edge.</p>


<p>Declaration at line 723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 932 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13a13b74fdca959e0c5da734f789b298cf6">llvm::LazyCallGraph::Edge::Call</a>, <a href="#a3a7a57d977301c68294ee8d4c92543ce">LazyCallGraph::Node</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#aea1129b8892c0b3869793b0354270544">llvm::LazyCallGraph::verify</a>.</p>

</div>
</div>

### switchOutgoingEdgeToRef {#adce8df277d53b4d87581583c8269ac71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::RefSCC::switchOutgoingEdgeToRef (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; SourceN, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; TargetN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make an existing outgoing call edge into a ref edge.</p>


<p>This is trivial as there are no cyclic impacts and there remains a reference edge.</p>


<p>Declaration at line 729 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 953 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3a7a57d977301c68294ee8d4c92543ce">LazyCallGraph::Node</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13a81845d1d6d0f58deb757fad1e739c32c">llvm::LazyCallGraph::Edge::Ref</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#aea1129b8892c0b3869793b0354270544">llvm::LazyCallGraph::verify</a>.</p>

</div>
</div>

### switchTrivialInternalEdgeToRef {#ae2f9bc7458beec4389ccf7fb88199d4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::RefSCC::switchTrivialInternalEdgeToRef (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; SourceN, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> &amp; TargetN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make an existing internal call edge between separate SCCs into a ref edge.</p>


<p>If SourceN and TargetN in separate SCCs within this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a>, changing the call edge between them to a ref edge is a trivial operation that does not require any structural changes to the call graph.</p>


<p>Declaration at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 733 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3a7a57d977301c68294ee8d4c92543ce">LazyCallGraph::Node</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af45c4dc83c083c5ae914d96fd3ce96">llvm::make_scope_exit</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13a81845d1d6d0f58deb757fad1e739c32c">llvm::LazyCallGraph::Edge::Ref</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#aea1129b8892c0b3869793b0354270544">llvm::LazyCallGraph::verify</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
