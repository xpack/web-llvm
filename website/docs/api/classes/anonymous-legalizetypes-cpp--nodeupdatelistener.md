---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-legalizetypes-cpp-/nodeupdatelistener
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `NodeUpdateListener` Class

<p>This class is a DAGUpdateListener that listens for updates to nodes and recomputes their ready state. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{LegalizeTypes.cpp}::NodeUpdateListener { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/selectiondag/dagupdatelistener">DAGUpdateListener</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clients of various APIs that cause global effects on the DAG can optionally implement this interface. <a href="/web-llvm/docs/api/structs/llvm/selectiondag/dagupdatelistener/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e5a39703ca3f66df4a37449c50f2e42">NodeUpdateListener</a> (DAGTypeLegalizer &amp;dtl, SmallSetVector&lt; SDNode *, 16 &gt; &amp;nta)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa976778bc4ac96d362ff62058d8586a7">NodeDeleted</a> (SDNode *N, SDNode *E) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The node N that was deleted and, if E is not null, an equivalent node E that replaced it. <a href="#aa976778bc4ac96d362ff62058d8586a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf34249f3e61610c017c54e3445dda14">NodeUpdated</a> (SDNode *N) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The node N that was updated. <a href="#acf34249f3e61610c017c54e3445dda14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dagtypelegalizer">DAGTypeLegalizer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac03afb2f7134bcfd06059c8e2be5e338">DTL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, 16 &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b740a9f97ee58054e10d7160fb0e0c9">NodesToAnalyze</a></td>
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

<p>This class is a DAGUpdateListener that listens for updates to nodes and recomputes their ready state.</p>

<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizetypes-cpp">LegalizeTypes.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NodeUpdateListener() {#a1e5a39703ca3f66df4a37449c50f2e42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LegalizeTypes.cpp}::NodeUpdateListener::NodeUpdateListener (<a href="/web-llvm/docs/api/classes/llvm/dagtypelegalizer">DAGTypeLegalizer</a> &amp; dtl, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *, 16 &gt; &amp; nta)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizetypes-cpp">LegalizeTypes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/selectiondag/dagupdatelistener/#ab3ffbfc6ced2909624e205e7e93b8789">llvm::SelectionDAG::DAGUpdateListener::DAGUpdateListener</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### NodeDeleted() {#aa976778bc4ac96d362ff62058d8586a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LegalizeTypes.cpp}::NodeUpdateListener::NodeDeleted (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * E)</td>
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

<p>The node N that was deleted and, if E is not null, an equivalent node E that replaced it.</p>

<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizetypes-cpp">LegalizeTypes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/dagtypelegalizer/#ab1ef8198b3a82d5a2161eb72f5910994a8538ef2e6f2a154d8fb2032f068a3ed8">llvm::DAGTypeLegalizer::NewNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dagtypelegalizer/#ab1ef8198b3a82d5a2161eb72f5910994af6b7630aca04cca9a65516a381267417">llvm::DAGTypeLegalizer::Processed</a> and <a href="/web-llvm/docs/api/classes/llvm/dagtypelegalizer/#ab1ef8198b3a82d5a2161eb72f5910994a5c4b2709df114f7ca7344a9e264ca9b8">llvm::DAGTypeLegalizer::ReadyToProcess</a>.</p>

</div>
</div>

### NodeUpdated() {#acf34249f3e61610c017c54e3445dda14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LegalizeTypes.cpp}::NodeUpdateListener::NodeUpdated (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>The node N that was updated.</p>

<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizetypes-cpp">LegalizeTypes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/dagtypelegalizer/#ab1ef8198b3a82d5a2161eb72f5910994a8538ef2e6f2a154d8fb2032f068a3ed8">llvm::DAGTypeLegalizer::NewNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dagtypelegalizer/#ab1ef8198b3a82d5a2161eb72f5910994af6b7630aca04cca9a65516a381267417">llvm::DAGTypeLegalizer::Processed</a> and <a href="/web-llvm/docs/api/classes/llvm/dagtypelegalizer/#ab1ef8198b3a82d5a2161eb72f5910994a5c4b2709df114f7ca7344a9e264ca9b8">llvm::DAGTypeLegalizer::ReadyToProcess</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DTL {#ac03afb2f7134bcfd06059c8e2be5e338}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DAGTypeLegalizer&amp; anonymous{LegalizeTypes.cpp}::NodeUpdateListener::DTL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizetypes-cpp">LegalizeTypes.cpp</a>.</p>

</div>
</div>

### NodesToAnalyze {#a7b740a9f97ee58054e10d7160fb0e0c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetVector&lt;SDNode*, 16&gt;&amp; anonymous{LegalizeTypes.cpp}::NodeUpdateListener::NodesToAnalyze</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizetypes-cpp">LegalizeTypes.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizetypes-cpp">LegalizeTypes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
