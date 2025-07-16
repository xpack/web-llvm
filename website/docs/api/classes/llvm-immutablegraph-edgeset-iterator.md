---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/immutablegraph/edgeset/iterator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `iterator` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::ImmutableGraph::EdgeSet::iterator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">Target/X86/ImmutableGraph.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27f2dbb3f08b18e00de8966b1f5b93a2">iterator</a> (const EdgeSet &amp;Set, size_type Begin)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablegraph/edgeset/iterator">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a977a91f5846144c1fa1ccdea42fa13d0">operator++</a> (int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablegraph/edgeset/iterator">iterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8594a0ddc60182ff71cf2dcd5a906dad">operator++</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablegraph/edge">Edge</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3c6799a182124f3b2e0bf8d229b2ea5">operator*</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadf8fcbe1c116e072b293da5b974df9c">operator==</a> (const iterator &amp;other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae77dcf57dc9d927cfc527486026d56cb">operator!=</a> (const iterator &amp;other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8acd73bbfa341167b642a4c9c1808b38">advance</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/edgeset">EdgeSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5a9b1d7286796929110ffb1a901b5d3">Set</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ea942d21bf6b660533adf1e10fe54b8">Current</a></td>
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


<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### iterator() {#a27f2dbb3f08b18e00de8966b1f5b93a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::iterator::iterator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/edgeset">EdgeSet</a> &amp; Set, <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/#a6000637a017edb428a4b49d690351e42">size_type</a> Begin)</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/edgeset/#a39dad974eb75445be1bd3f2b2c1f3857">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::EdgeSet</a>.</p>


<p>Referenced by <a href="#ae77dcf57dc9d927cfc527486026d56cb">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::iterator::operator!=</a>, <a href="#a8594a0ddc60182ff71cf2dcd5a906dad">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::iterator::operator++</a>, <a href="#a977a91f5846144c1fa1ccdea42fa13d0">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::iterator::operator++</a> and <a href="#aadf8fcbe1c116e072b293da5b974df9c">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::iterator::operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#ae77dcf57dc9d927cfc527486026d56cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::iterator::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/edgeset/iterator">iterator</a> &amp; other)</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<p>Reference <a href="#a27f2dbb3f08b18e00de8966b1f5b93a2">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::iterator::iterator</a>.</p>

</div>
</div>

### operator\*() {#ae3c6799a182124f3b2e0bf8d229b2ea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Edge * llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::iterator::operator* ()</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### operator++() {#a977a91f5846144c1fa1ccdea42fa13d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::iterator::operator++ (int)</td>
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



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<p>Reference <a href="#a27f2dbb3f08b18e00de8966b1f5b93a2">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::iterator::iterator</a>.</p>

</div>
</div>

### operator++() {#a8594a0ddc60182ff71cf2dcd5a906dad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator &amp; llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::iterator::operator++ ()</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<p>Reference <a href="#a27f2dbb3f08b18e00de8966b1f5b93a2">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::iterator::iterator</a>.</p>

</div>
</div>

### operator==() {#aadf8fcbe1c116e072b293da5b974df9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::iterator::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/edgeset/iterator">iterator</a> &amp; other)</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a27f2dbb3f08b18e00de8966b1f5b93a2">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::iterator::iterator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### advance() {#a8acd73bbfa341167b642a4c9c1808b38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::iterator::advance ()</td>
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



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Current {#a4ea942d21bf6b660533adf1e10fe54b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::iterator::Current</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

</div>
</div>

### Set {#ae5a9b1d7286796929110ffb1a901b5d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EdgeSet&amp; llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::EdgeSet::iterator::Set</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/immutablegraph-h">ImmutableGraph.h</a>.</p>

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
