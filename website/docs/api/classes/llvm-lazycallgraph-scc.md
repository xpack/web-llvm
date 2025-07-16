---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/lazycallgraph/scc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SCC` Class Reference

<p>An <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> of the call graph. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LazyCallGraph::SCC { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">llvm/Analysis/LazyCallGraph.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fb4c5eb5860ec05a7a180a62148288d">iterator</a> = <a href="/web-llvm/docs/api/structs/llvm/pointee-iterator">pointee_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> * &gt;::const_iterator &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9caadc9c841ba10afbd2200bec580b18">operator&lt;&lt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print a short description useful for debugging or logging. <a href="#a9caadc9c841ba10afbd2200bec580b18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NodeRangeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a244033b61a9d029c4c141b6af6bd87ad">SCC</a> (RefSCC &amp;OuterRefSCC, NodeRangeT &amp;&amp;Nodes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2fb4c5eb5860ec05a7a180a62148288d">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb7ae9233d82816a8d4f2f72490c4ac0">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2fb4c5eb5860ec05a7a180a62148288d">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a189dc256892604798e0542254dd4a704">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5592b0404f95c589801ea255fa95fb63">size</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef7abf8c91d56934fe4097746f8e5c30">getOuterRefSCC</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a542a7d70121296c36071303e26b68b7a">isParentOf</a> (const SCC &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> is a parent of <em>C</em>. <a href="#a542a7d70121296c36071303e26b68b7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a024bad6935b15f7080b08b5dfec4eade">isAncestorOf</a> (const SCC &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> is an ancestor of <em>C</em>. <a href="#a024bad6935b15f7080b08b5dfec4eade">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a571e944cc1b3b151736f9c8ff6c38b56">isChildOf</a> (const SCC &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> is a child of <em>C</em>. <a href="#a571e944cc1b3b151736f9c8ff6c38b56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4c82af92f2f7cf3d4e031d552c6b4f2">isDescendantOf</a> (const SCC &amp;C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> is a descendant of <em>C</em>. <a href="#ab4c82af92f2f7cf3d4e031d552c6b4f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abac122ed462169c3afbf43309644b415">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide a short name by printing this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> to a std::string. <a href="#abac122ed462169c3afbf43309644b415">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abac1d4eeddbdef810323ec3aa37545b5">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9794373c7b154004d5d4a4bc7aeb6f93">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump a short description of this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> to stderr. <a href="#a9794373c7b154004d5d4a4bc7aeb6f93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06a877510671d08945cc742ac3719559">verify</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify invariants about the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a>. <a href="#a06a877510671d08945cc742ac3719559">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57d06ed7adab69e2bddba8948f8f73a8">OuterRefSCC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">Node</a> *, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17bb9bcf841df7c8c413e6bf883f80da">Nodes</a></td>
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

<p>An <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> of the call graph.</p>


<p>This represents a Strongly Connected Component of the direct call graph – ignoring indirect calls and function references. It stores this as a collection of call graph nodes. While the order of nodes in the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> is stable, it is not any particular order.</p>


<p>The SCCs are nested within a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a></span>, see below for details about that outer structure. SCCs do not support mutation of the call graph, that must be done through the containing <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a></span> in order to fully reason about the ordering and connections of the graph.</p>


<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#a2fb4c5eb5860ec05a7a180a62148288d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LazyCallGraph::SCC::iterator =  pointee_iterator&lt;SmallVectorImpl&lt;Node *&gt;::const_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

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


<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="#a81774ea46253e6427d63a610bd624c08">LazyCallGraph</a>.</p>


<p>Referenced by <a href="#a024bad6935b15f7080b08b5dfec4eade">isAncestorOf</a> and <a href="#a81774ea46253e6427d63a610bd624c08">LazyCallGraph</a>.</p>

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


<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Referenced by <a href="#a024bad6935b15f7080b08b5dfec4eade">isAncestorOf</a> and <a href="#a542a7d70121296c36071303e26b68b7a">isParentOf</a>.</p>

</div>
</div>

### operator&lt;&lt; {#a9caadc9c841ba10afbd2200bec580b18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> &amp; C</td>
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


<p>We print the function names in the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> wrapped in '()'s and skipping the middle functions if there are a large number.</p>


<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### SCC() {#a244033b61a9d029c4c141b6af6bd87ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NodeRangeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LazyCallGraph::SCC::SCC (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">RefSCC</a> &amp; OuterRefSCC, NodeRangeT &amp;&amp; Nodes)</td>
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



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#abb7ae9233d82816a8d4f2f72490c4ac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::LazyCallGraph::SCC::begin ()</td>
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



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/inlineadvisoranalysisprinterpass/#af0f697cf524e464ace6a8652e4dbb128">llvm::InlineAdvisorAnalysisPrinterPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>.</p>

</div>
</div>

### end() {#a189dc256892604798e0542254dd4a704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::LazyCallGraph::SCC::end ()</td>
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



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### getName() {#abac122ed462169c3afbf43309644b415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::LazyCallGraph::SCC::getName ()</td>
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

<p>Provide a short name by printing this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> to a std::string.</p>


<p>This copes with the fact that we don't have a name per se for an <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> while still making the use of this in debugging and logging useful.</p>


<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>.</p>

</div>
</div>

### getOuterRefSCC() {#aef7abf8c91d56934fe4097746f8e5c30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RefSCC &amp; llvm::LazyCallGraph::SCC::getOuterRefSCC ()</td>
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



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a2957918db7f91f405b11d92c1ebf3b0f">llvm::LazyCallGraph::RefSCC::switchInternalEdgeToCall</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#a490117b63072462d035a6933fdb94c1f">updateCGAndAnalysisManagerForPass</a>.</p>

</div>
</div>

### isAncestorOf() {#a024bad6935b15f7080b08b5dfec4eade}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LazyCallGraph::SCC::isAncestorOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> is an ancestor of <em>C</em>.</p>


<p>Note that in the worst case this is linear in the number of edges departing the current <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> and every <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> in the entire graph reachable from this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a>. Thus this very well may walk every edge in the entire call graph! Do not call this in a tight loop!</p>


<p>Declaration at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#a81774ea46253e6427d63a610bd624c08">LazyCallGraph</a>, <a href="#a3a7a57d977301c68294ee8d4c92543ce">LazyCallGraph::Node</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### isChildOf() {#a571e944cc1b3b151736f9c8ff6c38b56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LazyCallGraph::SCC::isChildOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> &amp; C)</td>
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

<p>Test if this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> is a child of <em>C</em>.</p>


<p>See the comments for <span class="doxyComputerOutput">isParentOf</span> for detailed notes about the complexity of this routine.</p>


<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### isDescendantOf() {#ab4c82af92f2f7cf3d4e031d552c6b4f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LazyCallGraph::SCC::isDescendantOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> &amp; C)</td>
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

<p>Test if this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> is a descendant of <em>C</em>.</p>


<p>See the comments for <span class="doxyComputerOutput">isParentOf</span> for detailed notes about the complexity of this routine.</p>


<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### isParentOf() {#a542a7d70121296c36071303e26b68b7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LazyCallGraph::SCC::isParentOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> is a parent of <em>C</em>.</p>


<p>Note that this is linear in the number of edges departing the current <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a>.</p>


<p>Declaration at line 485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a3a7a57d977301c68294ee8d4c92543ce">LazyCallGraph::Node</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### size() {#a5592b0404f95c589801ea255fa95fb63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::LazyCallGraph::SCC::size ()</td>
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



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/inlineadvisoranalysisprinterpass/#af0f697cf524e464ace6a8652e4dbb128">llvm::InlineAdvisorAnalysisPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a96fe0cb15ded58bd1824fa4e3daec680">llvm::LazyCallGraph::RefSCC::switchInternalEdgeToRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### clear() {#abac1d4eeddbdef810323ec3aa37545b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LazyCallGraph::SCC::clear ()</td>
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



<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### dump() {#a9794373c7b154004d5d4a4bc7aeb6f93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void LazyCallGraph::SCC::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump a short description of this <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a> to stderr.</p>

<p>Declaration at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>

</div>
</div>

### verify() {#a06a877510671d08945cc742ac3719559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LazyCallGraph::SCC::verify ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify invariants about the <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a>.</p>


<p>This will attempt to validate all of the basic invariants within an <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">SCC</a>, but not that it is a strongly connected component per se. Primarily useful while building and updating the graph to check that basic properties are in place rather than having inexplicable crashes later.</p>


<p>Declaration at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>, definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Nodes {#a17bb9bcf841df7c8c413e6bf883f80da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Node *, 1&gt; llvm::LazyCallGraph::SCC::Nodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

</div>
</div>

### OuterRefSCC {#a57d06ed7adab69e2bddba8948f8f73a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RefSCC* llvm::LazyCallGraph::SCC::OuterRefSCC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">LazyCallGraph.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
