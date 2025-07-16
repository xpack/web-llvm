---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-selectiondag-cpp-/rauwupdatelistener
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RAUWUpdateListener` Class Reference

<p><a href="/web-llvm/docs/api/classes/anonymous-selectiondag-cpp-/rauwupdatelistener">RAUWUpdateListener</a> - Helper for ReplaceAllUsesWith - When the node pointed to by a use iterator is deleted, increment the use iterator so that it doesn't dangle. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{SelectionDAG.cpp}::RAUWUpdateListener { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f8d721912707fda12da5f34b38a18f5">RAUWUpdateListener</a> (SelectionDAG &amp;d, SDNode::use_iterator &amp;ui, SDNode::use_iterator &amp;ue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0fd1ea3020c66b2b588547928a4cf22">NodeDeleted</a> (SDNode *N, SDNode *E) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The node N that was deleted and, if E is not null, an equivalent node E that replaced it. <a href="#ad0fd1ea3020c66b2b588547928a4cf22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode/use-iterator">SDNode::use_iterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1279a79e67c8785c00dfceb4c923c1d">UI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode/use-iterator">SDNode::use_iterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79aa8c5a164149c8205e957a708652d3">UE</a></td>
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

<p><a href="/web-llvm/docs/api/classes/anonymous-selectiondag-cpp-/rauwupdatelistener">RAUWUpdateListener</a> - Helper for ReplaceAllUsesWith - When the node pointed to by a use iterator is deleted, increment the use iterator so that it doesn't dangle.</p>

<p>Definition at line 11632 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RAUWUpdateListener() {#a6f8d721912707fda12da5f34b38a18f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SelectionDAG.cpp}::RAUWUpdateListener::RAUWUpdateListener (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; d, <a href="/web-llvm/docs/api/classes/llvm/sdnode/use-iterator">SDNode::use_iterator</a> &amp; ui, <a href="/web-llvm/docs/api/classes/llvm/sdnode/use-iterator">SDNode::use_iterator</a> &amp; ue)</td>
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



<p>Definition at line 11643 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/selectiondag/dagupdatelistener/#ab3ffbfc6ced2909624e205e7e93b8789">llvm::SelectionDAG::DAGUpdateListener::DAGUpdateListener</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### NodeDeleted() {#ad0fd1ea3020c66b2b588547928a4cf22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SelectionDAG.cpp}::RAUWUpdateListener::NodeDeleted (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * E)</td>
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

<p>Definition at line 11636 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### UE {#a79aa8c5a164149c8205e957a708652d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode::use_iterator&amp; anonymous{SelectionDAG.cpp}::RAUWUpdateListener::UE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11634 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>

</div>
</div>

### UI {#ac1279a79e67c8785c00dfceb4c923c1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode::use_iterator&amp; anonymous{SelectionDAG.cpp}::RAUWUpdateListener::UI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11633 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp">SelectionDAG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
