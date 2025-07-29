---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/graphtraits-9ac678cba1b93dbde91361363a8c8a8e
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `GraphTraits` Struct Template

<p><a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a> specialization to recursively traverse <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> nodes, including traversing through VPRegionBlocks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::GraphTraits&lt;VPBlockDeepTraversalWrapper&lt; VPBlockBase * &gt;&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplancfg-h">Transforms/Vectorize/VPlanCFG.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0be3150019067bf23c04147dabb4e130">NodeRef</a> = <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> *</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41400d6ffa3a67ba48ac701b62e503ea">ChildIteratorType</a> = <a href="/web-llvm/docs/api/classes/llvm/vpallsuccessorsiterator">VPAllSuccessorsIterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a0be3150019067bf23c04147dabb4e130">NodeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f92cc63126efa4835b782d4dcedf1e2">getEntryNode</a> (VPBlockDeepTraversalWrapper&lt; VPBlockBase * &gt; N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a41400d6ffa3a67ba48ac701b62e503ea">ChildIteratorType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa23188a92e58f4d24281cf91d49bf6d4">child_begin</a> (NodeRef N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a41400d6ffa3a67ba48ac701b62e503ea">ChildIteratorType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a674a487e693cc9d8974189f99e1791b3">child_end</a> (NodeRef N)</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a> specialization to recursively traverse <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> nodes, including traversing through VPRegionBlocks.</p>


<p>Exit blocks of a region implicitly have their parent region's successors. This ensures all blocks in a region are visited before any blocks in a successor region when doing a reverse post-order traversal of the graph.</p>


<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplancfg-h">VPlanCFG.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ChildIteratorType {#a41400d6ffa3a67ba48ac701b62e503ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GraphTraits&lt; VPBlockDeepTraversalWrapper&lt; VPBlockBase * &gt; &gt;::ChildIteratorType =  VPAllSuccessorsIterator&lt;VPBlockBase *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplancfg-h">VPlanCFG.h</a>.</p>

</div>
</div>

### NodeRef {#a0be3150019067bf23c04147dabb4e130}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GraphTraits&lt; VPBlockDeepTraversalWrapper&lt; VPBlockBase * &gt; &gt;::NodeRef =  VPBlockBase *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplancfg-h">VPlanCFG.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### child\_begin() {#aa23188a92e58f4d24281cf91d49bf6d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChildIteratorType llvm::GraphTraits&lt; VPBlockDeepTraversalWrapper&lt; VPBlockBase * &gt; &gt;::child_begin (<a href="#a0be3150019067bf23c04147dabb4e130">NodeRef</a> N)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplancfg-h">VPlanCFG.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### child\_end() {#a674a487e693cc9d8974189f99e1791b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChildIteratorType llvm::GraphTraits&lt; VPBlockDeepTraversalWrapper&lt; VPBlockBase * &gt; &gt;::child_end (<a href="#a0be3150019067bf23c04147dabb4e130">NodeRef</a> N)</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplancfg-h">VPlanCFG.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpallsuccessorsiterator/#ae3a8376055932ebff3313988fee1a588">llvm::VPAllSuccessorsIterator&lt; VPBlockBase * &gt;::end</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getEntryNode() {#a3f92cc63126efa4835b782d4dcedf1e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeRef llvm::GraphTraits&lt; VPBlockDeepTraversalWrapper&lt; VPBlockBase * &gt; &gt;::getEntryNode (<a href="/web-llvm/docs/api/classes/llvm/vpblockdeeptraversalwrapper">VPBlockDeepTraversalWrapper</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpblockbase">VPBlockBase</a> * &gt; N)</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplancfg-h">VPlanCFG.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplancfg-h">VPlanCFG.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
