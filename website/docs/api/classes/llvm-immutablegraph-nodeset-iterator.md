---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/immutablegraph/nodeset/iterator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `iterator` Class



## Declaration

<div class="doxyDeclaration">
class llvm::ImmutableGraph::NodeSet::iterator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">Target/X86/ImmutableGraph.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a579c6d1821bc4ed5d3ceb38f21ec179a">iterator</a> (const NodeSet &amp;Set, size_type Begin)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablegraph/nodeset/iterator">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dd2e9ac22e4346e0eb71620cb7e9bf1">operator++</a> (int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablegraph/nodeset/iterator">iterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f5898e6b7dcc16bd99af310f405f5ab">operator++</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablegraph/node">Node</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4805a72ef937bb4d3545616970411b45">operator*</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac63a63d36c0dc4d69db64d63d84f319b">operator==</a> (const iterator &amp;other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84ba7d2055a70e198e480d20454ce7fc">operator!=</a> (const iterator &amp;other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43e4f30b0be7277e64e386459a9e549e">advance</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/nodeset">NodeSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c9e97c0ad8cb4e5ab2103bcf4321e6c">Set</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablegraph/#a6000637a017edb428a4b49d690351e42">size_type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06f9591107d539c9c77cbd582cb3e8c7">Current</a></td>
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


<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### iterator() {#a579c6d1821bc4ed5d3ceb38f21ec179a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::iterator::iterator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/nodeset">NodeSet</a> &amp; Set, <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/#a6000637a017edb428a4b49d690351e42">size_type</a> Begin)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/nodeset/#a71c094f9dabd89f5ff79c1dbabc70660">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::NodeSet</a>.</p>


<p>Referenced by <a href="#a84ba7d2055a70e198e480d20454ce7fc">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::iterator::operator!=</a>, <a href="#a9f5898e6b7dcc16bd99af310f405f5ab">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::iterator::operator++</a>, <a href="#a6dd2e9ac22e4346e0eb71620cb7e9bf1">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::iterator::operator++</a> and <a href="#ac63a63d36c0dc4d69db64d63d84f319b">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::iterator::operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a84ba7d2055a70e198e480d20454ce7fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::iterator::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/nodeset/iterator">iterator</a> &amp; other)</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<p>Reference <a href="#a579c6d1821bc4ed5d3ceb38f21ec179a">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::iterator::iterator</a>.</p>

</div>
</div>

### operator\*() {#a4805a72ef937bb4d3545616970411b45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::iterator::operator* ()</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### operator++() {#a6dd2e9ac22e4346e0eb71620cb7e9bf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::iterator::operator++ (int)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<p>Reference <a href="#a579c6d1821bc4ed5d3ceb38f21ec179a">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::iterator::iterator</a>.</p>

</div>
</div>

### operator++() {#a9f5898e6b7dcc16bd99af310f405f5ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator &amp; llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::iterator::operator++ ()</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<p>Reference <a href="#a579c6d1821bc4ed5d3ceb38f21ec179a">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::iterator::iterator</a>.</p>

</div>
</div>

### operator==() {#ac63a63d36c0dc4d69db64d63d84f319b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::iterator::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/nodeset/iterator">iterator</a> &amp; other)</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a579c6d1821bc4ed5d3ceb38f21ec179a">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::iterator::iterator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### advance() {#a43e4f30b0be7277e64e386459a9e549e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::iterator::advance ()</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Current {#a06f9591107d539c9c77cbd582cb3e8c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::iterator::Current</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

### Set {#a2c9e97c0ad8cb4e5ab2103bcf4321e6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NodeSet&amp; llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::iterator::Set</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
