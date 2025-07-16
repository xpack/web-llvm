---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ContextNode` Struct Reference

<p><a href="/web-llvm/docs/api/classes/node">Node</a> in the Callsite Context Graph. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph::ContextNode { ... }
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27d9f1158e8fdbd37f75e280b700a7af">operator&lt;&lt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a464de20e3b64a8ffd3e5003ec85bd628">ContextNode</a> (bool IsAllocation)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3472b287a75ef2c391d465ffb1be5a5">ContextNode</a> (bool IsAllocation, CallInfo C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::shared_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge">ContextEdge</a> &gt; &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab13b3b267ea5e8401d9e03698002ccb0">getEdgesWithAllocInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14ae478e63dbd2596e224ab2e88e1d3b">getContextIds</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb643e7f3e0b06b7a92c586993f31077">computeAllocType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a035c612184f13edf042a084a914d7d4b">emptyContextIds</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8bf83025a4ed5fa4a076bccbc693071">addClone</a> (ContextNode *Clone)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a604b3bb952eecc61cefdd96797009693">getOrigNode</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65c09e3b6dd0ad4eada5aeb000e6b43f">addOrUpdateCallerEdge</a> (ContextNode *Caller, AllocationType AllocType, unsigned int ContextId)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge">ContextEdge</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ce81b07a0aafa3672824164e18fd7ff">findEdgeFromCallee</a> (const ContextNode *Callee)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge">ContextEdge</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7a94fea6eeece35ff273e7c7bf0d293">findEdgeFromCaller</a> (const ContextNode *Caller)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affae140ed481aa061f54e9acd2ab7100">eraseCalleeEdge</a> (const ContextEdge *Edge)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab34ce9ab779bd29faf752c7a91f364a6">eraseCallerEdge</a> (const ContextEdge *Edge)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ad507e0575b074da4f909f338c7bab4">setCall</a> (CallInfo C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a659cb1a30424bbb144a76499a66f6784">hasCall</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c4cc6a126b6f592b7dc770dbbd1954e">printCall</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63b2124f078e800145596183d4e0e1de">isRemoved</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af75089d03f37e5a0401e2ebf85133ba6">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f9c9934b56d5f01f4e5057f021022c9">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9e8125084b36e9f7d06d3a21d419314">IsAllocation</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d1422c851165b12a95d0cff1c7a1162">Recursive</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f5bb5c9a5b60b75cc7e80a72d1711da">AllocTypes</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84214f5e3a9c485cb3aa7b98d6a512f2">Call</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a>, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade739c46ca314fc9fc3cf4c9089f048b">MatchingCalls</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef8270c7f9cb86c77eae179db3c54a92">OrigStackOrAllocId</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::shared_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge">ContextEdge</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8c264356aaacd67c26e243127fb8514">CalleeEdges</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::shared_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge">ContextEdge</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab8eeabd26ce6b92243a5f349e323256">CallerEdges</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4746b415a3f7fb94dcf653987ff490b3">Clones</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b3703f3c94a72e5835bbdca531f7173">CloneOf</a> = nullptr</td>
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

<p><a href="/web-llvm/docs/api/classes/node">Node</a> in the Callsite Context Graph.</p>

<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<div class="doxySectionDef">

## Friends

### operator&lt;&lt; {#a27d9f1158e8fdbd37f75e280b700a7af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> &amp; Node</td>
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


<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="#a464de20e3b64a8ffd3e5003ec85bd628">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::ContextNode</a> and <a href="/web-llvm/docs/api/classes/node/#a05779201e7fa0913e5b50fdbc5c49135">Node::print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ContextNode() {#a464de20e3b64a8ffd3e5003ec85bd628}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::ContextNode (bool IsAllocation)</td>
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



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="#a84214f5e3a9c485cb3aa7b98d6a512f2">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::Call</a> and <a href="#ad9e8125084b36e9f7d06d3a21d419314">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::IsAllocation</a>.</p>


<p>Referenced by <a href="#af8bf83025a4ed5fa4a076bccbc693071">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::addClone</a>, <a href="#a65c09e3b6dd0ad4eada5aeb000e6b43f">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::addOrUpdateCallerEdge</a>, <a href="#a3ce81b07a0aafa3672824164e18fd7ff">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::findEdgeFromCallee</a>, <a href="#ad7a94fea6eeece35ff273e7c7bf0d293">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::findEdgeFromCaller</a>, <a href="#a604b3bb952eecc61cefdd96797009693">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::getOrigNode</a> and <a href="#a27d9f1158e8fdbd37f75e280b700a7af">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::operator&lt;&lt;</a>.</p>

</div>
</div>

### ContextNode() {#ac3472b287a75ef2c391d465ffb1be5a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::ContextNode (bool IsAllocation, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a> C)</td>
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



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a84214f5e3a9c485cb3aa7b98d6a512f2">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::Call</a> and <a href="#ad9e8125084b36e9f7d06d3a21d419314">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::IsAllocation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addClone() {#af8bf83025a4ed5fa4a076bccbc693071}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::addClone (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * Clone)</td>
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



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8b3703f3c94a72e5835bbdca531f7173">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::CloneOf</a>, <a href="#a4746b415a3f7fb94dcf653987ff490b3">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::Clones</a> and <a href="#a464de20e3b64a8ffd3e5003ec85bd628">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::ContextNode</a>.</p>

</div>
</div>

### addOrUpdateCallerEdge() {#a65c09e3b6dd0ad4eada5aeb000e6b43f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::ContextNode::addOrUpdateCallerEdge (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * Caller, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27">AllocationType</a> AllocType, unsigned int ContextId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="#aab8eeabd26ce6b92243a5f349e323256">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::CallerEdges</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a24a25f8f197ec2041fd2a9efcd4160b1">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallsiteContextGraph</a> and <a href="#a464de20e3b64a8ffd3e5003ec85bd628">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::ContextNode</a>.</p>

</div>
</div>

### computeAllocType() {#afb643e7f3e0b06b7a92c586993f31077}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::computeAllocType ()</td>
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



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27a1a3c2e99e572ec71d3820d0363d90742">llvm::Cold</a>, <a href="#ab13b3b267ea5e8401d9e03698002ccb0">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::getEdgesWithAllocInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27ad814aa38fbac7f6d03b30741366aae56">llvm::NotCold</a>.</p>

</div>
</div>

### dump() {#af75089d03f37e5a0401e2ebf85133ba6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::ContextNode::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a24a25f8f197ec2041fd2a9efcd4160b1">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallsiteContextGraph</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#a4f9c9934b56d5f01f4e5057f021022c9">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::print</a>.</p>

</div>
</div>

### emptyContextIds() {#a035c612184f13edf042a084a914d7d4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::emptyContextIds ()</td>
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



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Reference <a href="#ab13b3b267ea5e8401d9e03698002ccb0">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::getEdgesWithAllocInfo</a>.</p>


<p>Referenced by <a href="#a63b2124f078e800145596183d4e0e1de">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::isRemoved</a>.</p>

</div>
</div>

### eraseCalleeEdge() {#affae140ed481aa061f54e9acd2ab7100}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::ContextNode::eraseCalleeEdge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge">ContextEdge</a> * Edge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa8c264356aaacd67c26e243127fb8514">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::CalleeEdges</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a24a25f8f197ec2041fd2a9efcd4160b1">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallsiteContextGraph</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>.</p>

</div>
</div>

### eraseCallerEdge() {#ab34ce9ab779bd29faf752c7a91f364a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::ContextNode::eraseCallerEdge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge">ContextEdge</a> * Edge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aab8eeabd26ce6b92243a5f349e323256">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::CallerEdges</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a24a25f8f197ec2041fd2a9efcd4160b1">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallsiteContextGraph</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>.</p>

</div>
</div>

### findEdgeFromCallee() {#a3ce81b07a0aafa3672824164e18fd7ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge * CallsiteContextGraph::ContextNode::findEdgeFromCallee (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * Callee)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="#aa8c264356aaacd67c26e243127fb8514">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::CalleeEdges</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a24a25f8f197ec2041fd2a9efcd4160b1">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallsiteContextGraph</a> and <a href="#a464de20e3b64a8ffd3e5003ec85bd628">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::ContextNode</a>.</p>

</div>
</div>

### findEdgeFromCaller() {#ad7a94fea6eeece35ff273e7c7bf0d293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge * CallsiteContextGraph::ContextNode::findEdgeFromCaller (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> * Caller)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="#aab8eeabd26ce6b92243a5f349e323256">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::CallerEdges</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a24a25f8f197ec2041fd2a9efcd4160b1">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallsiteContextGraph</a> and <a href="#a464de20e3b64a8ffd3e5003ec85bd628">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::ContextNode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a6e0e5a23aea2cd0d2bc271342e6e5c34">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::updateStackNodes</a>.</p>

</div>
</div>

### getContextIds() {#a14ae478e63dbd2596e224ab2e88e1d3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt; uint32_t &gt; anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::getContextIds ()</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#ab13b3b267ea5e8401d9e03698002ccb0">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::getEdgesWithAllocInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a5b0a15cec07aa8f0f9e60cd343676bca">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::reserve</a>.</p>


<p>Referenced by <a href="#a4f9c9934b56d5f01f4e5057f021022c9">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::print</a> and <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a6e0e5a23aea2cd0d2bc271342e6e5c34">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::updateStackNodes</a>.</p>

</div>
</div>

### getEdgesWithAllocInfo() {#ab13b3b267ea5e8401d9e03698002ccb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; std::shared_ptr&lt; ContextEdge &gt; &gt; * anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::getEdgesWithAllocInfo ()</td>
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



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa8c264356aaacd67c26e243127fb8514">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::CalleeEdges</a>, <a href="#aab8eeabd26ce6b92243a5f349e323256">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::CallerEdges</a> and <a href="#ad9e8125084b36e9f7d06d3a21d419314">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::IsAllocation</a>.</p>


<p>Referenced by <a href="#afb643e7f3e0b06b7a92c586993f31077">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::computeAllocType</a>, <a href="#a035c612184f13edf042a084a914d7d4b">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::emptyContextIds</a> and <a href="#a14ae478e63dbd2596e224ab2e88e1d3b">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::getContextIds</a>.</p>

</div>
</div>

### getOrigNode() {#a604b3bb952eecc61cefdd96797009693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextNode * anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::getOrigNode ()</td>
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



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="#a8b3703f3c94a72e5835bbdca531f7173">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::CloneOf</a> and <a href="#a464de20e3b64a8ffd3e5003ec85bd628">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::ContextNode</a>.</p>

</div>
</div>

### hasCall() {#a659cb1a30424bbb144a76499a66f6784}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::hasCall ()</td>
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



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Reference <a href="#a84214f5e3a9c485cb3aa7b98d6a512f2">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::Call</a>.</p>

</div>
</div>

### isRemoved() {#a63b2124f078e800145596183d4e0e1de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::isRemoved ()</td>
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



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="#a2f5bb5c9a5b60b75cc7e80a72d1711da">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::AllocTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a035c612184f13edf042a084a914d7d4b">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::emptyContextIds</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### print() {#a4f9c9934b56d5f01f4e5057f021022c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallsiteContextGraph::ContextNode::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="#a2f5bb5c9a5b60b75cc7e80a72d1711da">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::AllocTypes</a>, <a href="#aa8c264356aaacd67c26e243127fb8514">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::CalleeEdges</a>, <a href="#aab8eeabd26ce6b92243a5f349e323256">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::CallerEdges</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a24a25f8f197ec2041fd2a9efcd4160b1">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallsiteContextGraph</a>, <a href="#a8b3703f3c94a72e5835bbdca531f7173">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::CloneOf</a>, <a href="#a4746b415a3f7fb94dcf653987ff490b3">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::Clones</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#a78e5652d529e02da75e8087017930e28">getAllocTypeString</a>, <a href="#a14ae478e63dbd2596e224ab2e88e1d3b">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::getContextIds</a>, <a href="#ade739c46ca314fc9fc3cf4c9089f048b">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::MatchingCalls</a>, <a href="#a9c4cc6a126b6f592b7dc770dbbd1954e">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::printCall</a> and <a href="#a8d1422c851165b12a95d0cff1c7a1162">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::Recursive</a>.</p>


<p>Referenced by <a href="#af75089d03f37e5a0401e2ebf85133ba6">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::dump</a>.</p>

</div>
</div>

### printCall() {#a9c4cc6a126b6f592b7dc770dbbd1954e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::printCall (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Reference <a href="#a84214f5e3a9c485cb3aa7b98d6a512f2">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::Call</a>.</p>


<p>Referenced by <a href="#a4f9c9934b56d5f01f4e5057f021022c9">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::print</a>.</p>

</div>
</div>

### setCall() {#a3ad507e0575b074da4f909f338c7bab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::setCall (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a> C)</td>
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



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a84214f5e3a9c485cb3aa7b98d6a512f2">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::Call</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#af222e51d6efae0aeb9ea76cac1b46300">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::assignFunctions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AllocTypes {#a2f5bb5c9a5b60b75cc7e80a72d1711da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::AllocTypes = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#adf8f8ad14c08099e793ca64a0768c96a">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::addAllocNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#af222e51d6efae0aeb9ea76cac1b46300">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::assignFunctions</a>, <a href="#a63b2124f078e800145596183d4e0e1de">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::isRemoved</a> and <a href="#a4f9c9934b56d5f01f4e5057f021022c9">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::print</a>.</p>

</div>
</div>

### Call {#a84214f5e3a9c485cb3aa7b98d6a512f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInfo anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::Call</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="#a464de20e3b64a8ffd3e5003ec85bd628">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::ContextNode</a>, <a href="#ac3472b287a75ef2c391d465ffb1be5a5">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::ContextNode</a>, <a href="#a659cb1a30424bbb144a76499a66f6784">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::hasCall</a>, <a href="#a9c4cc6a126b6f592b7dc770dbbd1954e">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::printCall</a> and <a href="#a3ad507e0575b074da4f909f338c7bab4">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::setCall</a>.</p>

</div>
</div>

### CalleeEdges {#aa8c264356aaacd67c26e243127fb8514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::shared_ptr&lt;ContextEdge&gt; &gt; anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::CalleeEdges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="#affae140ed481aa061f54e9acd2ab7100">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::eraseCalleeEdge</a>, <a href="#a3ce81b07a0aafa3672824164e18fd7ff">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::findEdgeFromCallee</a>, <a href="#ab13b3b267ea5e8401d9e03698002ccb0">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::getEdgesWithAllocInfo</a> and <a href="#a4f9c9934b56d5f01f4e5057f021022c9">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::print</a>.</p>

</div>
</div>

### CallerEdges {#aab8eeabd26ce6b92243a5f349e323256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::shared_ptr&lt;ContextEdge&gt; &gt; anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::CallerEdges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="#a65c09e3b6dd0ad4eada5aeb000e6b43f">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::addOrUpdateCallerEdge</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#af222e51d6efae0aeb9ea76cac1b46300">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::assignFunctions</a>, <a href="#ab34ce9ab779bd29faf752c7a91f364a6">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::eraseCallerEdge</a>, <a href="#ad7a94fea6eeece35ff273e7c7bf0d293">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::findEdgeFromCaller</a>, <a href="#ab13b3b267ea5e8401d9e03698002ccb0">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::getEdgesWithAllocInfo</a>, <a href="#a4f9c9934b56d5f01f4e5057f021022c9">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::print</a> and <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a6e0e5a23aea2cd0d2bc271342e6e5c34">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::updateStackNodes</a>.</p>

</div>
</div>

### CloneOf {#a8b3703f3c94a72e5835bbdca531f7173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ContextNode* anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::CloneOf = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="#af8bf83025a4ed5fa4a076bccbc693071">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::addClone</a>, <a href="#a604b3bb952eecc61cefdd96797009693">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::getOrigNode</a> and <a href="#a4f9c9934b56d5f01f4e5057f021022c9">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::print</a>.</p>

</div>
</div>

### Clones {#a4746b415a3f7fb94dcf653987ff490b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ContextNode *&gt; anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::Clones</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="#af8bf83025a4ed5fa4a076bccbc693071">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::addClone</a> and <a href="#a4f9c9934b56d5f01f4e5057f021022c9">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::print</a>.</p>

</div>
</div>

### IsAllocation {#ad9e8125084b36e9f7d06d3a21d419314}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::IsAllocation</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="#a464de20e3b64a8ffd3e5003ec85bd628">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::ContextNode</a>, <a href="#ac3472b287a75ef2c391d465ffb1be5a5">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::ContextNode</a> and <a href="#ab13b3b267ea5e8401d9e03698002ccb0">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::getEdgesWithAllocInfo</a>.</p>

</div>
</div>

### MatchingCalls {#ade739c46ca314fc9fc3cf4c9089f048b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;CallInfo, 0&gt; anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::MatchingCalls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#af222e51d6efae0aeb9ea76cac1b46300">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::assignFunctions</a> and <a href="#a4f9c9934b56d5f01f4e5057f021022c9">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::print</a>.</p>

</div>
</div>

### OrigStackOrAllocId {#aef8270c7f9cb86c77eae179db3c54a92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::OrigStackOrAllocId = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#adf8f8ad14c08099e793ca64a0768c96a">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::addAllocNode</a>.</p>

</div>
</div>

### Recursive {#a8d1422c851165b12a95d0cff1c7a1162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::Recursive = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="#a4f9c9934b56d5f01f4e5057f021022c9">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::print</a> and <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a6e0e5a23aea2cd0d2bc271342e6e5c34">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::updateStackNodes</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
