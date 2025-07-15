---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/graphtraits-d331e4256d82fb2920257d4c75d8b96c
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `GraphTraits` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::GraphTraits&lt;SelectionDAG *&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">llvm/CodeGen/SelectionDAG.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/graphtraits-404b5b8ef0c47cc568060468de8cfca6">GraphTraits&lt;SDNode *&gt;</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0570fb0bc9eafc00b40169a88ff51b1">nodes_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/pointer-iterator">pointer_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#affd0aa316a7d7197e5509b7f85a8f34e">SelectionDAG::allnodes_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/graphtraits/#a741f7d63af17a7bd0bcf63f68e8658bd">NodeRef</a> = typename <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> *::UnknownGraphTypeError</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ac0570fb0bc9eafc00b40169a88ff51b1">nodes_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3123c6219394f1f513b1bf7b89d0f85c">nodes_begin</a> (SelectionDAG *G)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ac0570fb0bc9eafc00b40169a88ff51b1">nodes_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a766d4f190756cb226b82cca4b4f5bc39">nodes_end</a> (SelectionDAG *G)</td>
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


<p>Definition at line 2493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">SelectionDAG.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### NodeRef {#a741f7d63af17a7bd0bcf63f68e8658bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GraphTraits&lt; SelectionDAG * &gt;::NodeRef = </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/graphtraits-h">GraphTraits.h</a>.</p>

</div>
</div>

### nodes\_iterator {#ac0570fb0bc9eafc00b40169a88ff51b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GraphTraits&lt; SelectionDAG * &gt;::nodes_iterator =  pointer_iterator&lt;SelectionDAG::allnodes_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">SelectionDAG.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### nodes\_begin() {#a3123c6219394f1f513b1bf7b89d0f85c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">nodes_iterator llvm::GraphTraits&lt; SelectionDAG * &gt;::nodes_begin (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * G)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">SelectionDAG.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>

</div>
</div>

### nodes\_end() {#a766d4f190756cb226b82cca4b4f5bc39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">nodes_iterator llvm::GraphTraits&lt; SelectionDAG * &gt;::nodes_end (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * G)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2500 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">SelectionDAG.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/graphtraits-h">GraphTraits.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">SelectionDAG.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
