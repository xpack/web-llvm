---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dagdeltaalgorithm
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DAGDeltaAlgorithm` Class

<p><a href="/web-llvm/docs/api/classes/llvm/dagdeltaalgorithm">DAGDeltaAlgorithm</a> - Implements a "delta debugging" algorithm for minimizing directed acyclic graphs using a predicate function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DAGDeltaAlgorithm { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/dagdeltaalgorithm-h">llvm/ADT/DAGDeltaAlgorithm.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4db5080e3127c468dd4bc6c0812142c">change_ty</a> = unsigned</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a658d0ed343fe1a2a704d4219a0a1a8ec">edge_ty</a> = std::pair&lt; <a href="#ad4db5080e3127c468dd4bc6c0812142c">change_ty</a>, <a href="#ad4db5080e3127c468dd4bc6c0812142c">change_ty</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f8cd32d8d69f713bf3c1dbeb942273a">changeset_ty</a> = std::set&lt; <a href="#ad4db5080e3127c468dd4bc6c0812142c">change_ty</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ef67c22dd53f113a1efa84a39ce14da">changesetlist_ty</a> = std::vector&lt; <a href="#a3f8cd32d8d69f713bf3c1dbeb942273a">changeset_ty</a> &gt;</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb9bf7f6f4b974912a37ab46382cafe4">~DAGDeltaAlgorithm</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3f8cd32d8d69f713bf3c1dbeb942273a">changeset_ty</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad81448e27f4064d1df0bc1b6d816e65a">Run</a> (const changeset_ty &amp;Changes, const std::vector&lt; edge_ty &gt; &amp;Dependencies)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run - Minimize the DAG formed by the <span class="doxyComputerOutput">Changes</span> vertices and the <span class="doxyComputerOutput">Dependencies</span> edges by executing. <a href="#ad81448e27f4064d1df0bc1b6d816e65a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99839595939902668e36df8ee1719c0e">UpdatedSearchState</a> (const changeset_ty &amp;Changes, const changesetlist_ty &amp;Sets, const changeset_ty &amp;Required)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>UpdatedSearchState - Callback used when the search state changes. <a href="#a99839595939902668e36df8ee1719c0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ce094907b560cfd137fc68897103e48">ExecuteOneTest</a> (const changeset_ty &amp;S)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ExecuteOneTest - Execute a single test predicate on the change set <span class="doxyComputerOutput">S</span>. <a href="#a2ce094907b560cfd137fc68897103e48">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab59f88357218a3ae22e8d0ae0c28ef50">anchor</a> ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/dagdeltaalgorithm">DAGDeltaAlgorithm</a> - Implements a "delta debugging" algorithm for minimizing directed acyclic graphs using a predicate function.</p>


<p>The result of the algorithm is a subset of the input change set which is guaranteed to satisfy the predicate, assuming that the input set did. For well formed predicates, the result set is guaranteed to be such that removing any single element not required by the dependencies on the other elements would falsify the predicate.</p>


<p>The DAG should be used to represent dependencies in the changes which are likely to hold across the predicate function. That is, for a particular changeset S and predicate P:</p>


<p><a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P(S)</a> =&gt; <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P(S union pred(S))</a></p>


<p>The minimization algorithm uses this dependency information to attempt to eagerly prune large subsets of changes. As with</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/deltaalgorithm">DeltaAlgorithm</a>, the DAG is not required to satisfy this property, but the algorithm will run substantially fewer tests with appropriate <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp/#a5dcd4fc8ee34f9e83ef4c742f07bd909">dependencies</a>.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/deltaalgorithm">DeltaAlgorithm</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> more information on the properties which the predicate <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> itself should satisfy.</p></dd>
</dl>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/dagdeltaalgorithm-h">DAGDeltaAlgorithm.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### change\_ty {#ad4db5080e3127c468dd4bc6c0812142c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DAGDeltaAlgorithm::change_ty =  unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/dagdeltaalgorithm-h">DAGDeltaAlgorithm.h</a>.</p>

</div>
</div>

### changeset\_ty {#a3f8cd32d8d69f713bf3c1dbeb942273a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DAGDeltaAlgorithm::changeset_ty =  std::set&lt;change_ty&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/dagdeltaalgorithm-h">DAGDeltaAlgorithm.h</a>.</p>

</div>
</div>

### changesetlist\_ty {#a2ef67c22dd53f113a1efa84a39ce14da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DAGDeltaAlgorithm::changesetlist_ty =  std::vector&lt;changeset_ty&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/dagdeltaalgorithm-h">DAGDeltaAlgorithm.h</a>.</p>

</div>
</div>

### edge\_ty {#a658d0ed343fe1a2a704d4219a0a1a8ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DAGDeltaAlgorithm::edge_ty =  std::pair&lt;change_ty, change_ty&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/dagdeltaalgorithm-h">DAGDeltaAlgorithm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DAGDeltaAlgorithm() {#acb9bf7f6f4b974912a37ab46382cafe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::DAGDeltaAlgorithm::~DAGDeltaAlgorithm ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/dagdeltaalgorithm-h">DAGDeltaAlgorithm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### ExecuteOneTest() {#a2ce094907b560cfd137fc68897103e48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::DAGDeltaAlgorithm::ExecuteOneTest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3f8cd32d8d69f713bf3c1dbeb942273a">changeset_ty</a> &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ExecuteOneTest - Execute a single test predicate on the change set <span class="doxyComputerOutput">S</span>.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/dagdeltaalgorithm-h">DAGDeltaAlgorithm.h</a>.</p>

</div>
</div>

### Run() {#ad81448e27f4064d1df0bc1b6d816e65a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DAGDeltaAlgorithm::changeset_ty DAGDeltaAlgorithm::Run (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3f8cd32d8d69f713bf3c1dbeb942273a">changeset_ty</a> &amp; Changes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="#a658d0ed343fe1a2a704d4219a0a1a8ec">edge_ty</a> &gt; &amp; Dependencies)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run - Minimize the DAG formed by the <span class="doxyComputerOutput">Changes</span> vertices and the <span class="doxyComputerOutput">Dependencies</span> edges by executing.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a2ce094907b560cfd137fc68897103e48">ExecuteOneTest()</a> on subsets of changes and returning the smallest set which still satisfies the <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#a106e32122c569cdb42ddf61ecbb0aad1">test</a> predicate and the input <span class="doxyComputerOutput">Dependencies</span>.</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Changes</td>
<td class="doxyParamItemDescription"><p>The list of changes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Dependencies</td>
<td class="doxyParamItemDescription"><p>The list of dependencies amongst changes. For each (x,y) in <span class="doxyComputerOutput">Dependencies</span>, both x and y must be in <span class="doxyComputerOutput">Changes</span>. The minimization algorithm guarantees that for each tested changed set S, <code>$ x \in S $</code> implies <code>$ y \in S $</code>. It is an error to have cyclic dependencies.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/dagdeltaalgorithm-h">DAGDeltaAlgorithm.h</a>, definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### UpdatedSearchState() {#a99839595939902668e36df8ee1719c0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DAGDeltaAlgorithm::UpdatedSearchState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3f8cd32d8d69f713bf3c1dbeb942273a">changeset_ty</a> &amp; Changes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2ef67c22dd53f113a1efa84a39ce14da">changesetlist_ty</a> &amp; Sets, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3f8cd32d8d69f713bf3c1dbeb942273a">changeset_ty</a> &amp; Required)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>UpdatedSearchState - Callback used when the search state changes.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/dagdeltaalgorithm-h">DAGDeltaAlgorithm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#ab59f88357218a3ae22e8d0ae0c28ef50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DAGDeltaAlgorithm::anchor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/dagdeltaalgorithm-h">DAGDeltaAlgorithm.h</a>, definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/dagdeltaalgorithm-h">DAGDeltaAlgorithm.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
