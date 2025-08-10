---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/balancedpartitioning/utilitysignature
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `UtilitySignature` Struct

<p>The signature of a particular utility node used for the bisection step, i.e., the number of <span class="doxyComputerOutput">FunctionNodes</span> in each of the two buckets. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::BalancedPartitioning::UtilitySignature { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7982f03d621ffdb803327fb70b4004e1">LeftCount</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of <span class="doxyComputerOutput">FunctionNodes</span> in the left bucket. <a href="#a7982f03d621ffdb803327fb70b4004e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f08c8a8b2b632339e72c02fd5c2a7fa">RightCount</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of <span class="doxyComputerOutput">FunctionNodes</span> in the right bucket. <a href="#a3f08c8a8b2b632339e72c02fd5c2a7fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dd6f4319020e637d6ca1d431f8f9177">CachedGainLR</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cached gain of moving a <span class="doxyComputerOutput">FunctionNode</span> from the left bucket to the right bucket. <a href="#a3dd6f4319020e637d6ca1d431f8f9177">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa20c778a7b81b7fee3fe452f848af1f9">CachedGainRL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cached gain of moving a <span class="doxyComputerOutput">FunctionNode</span> from the right bucket to the left bucket. <a href="#aa20c778a7b81b7fee3fe452f848af1f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca5409dfb66aa19ce8b5eb8332b235ce">CachedGainIsValid</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether <span class="doxyComputerOutput">CachedGainLR</span> and <span class="doxyComputerOutput">CachedGainRL</span> are valid. <a href="#aca5409dfb66aa19ce8b5eb8332b235ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The signature of a particular utility node used for the bisection step, i.e., the number of <span class="doxyComputerOutput">FunctionNodes</span> in each of the two buckets.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### CachedGainIsValid {#aca5409dfb66aa19ce8b5eb8332b235ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BalancedPartitioning::UtilitySignature::CachedGainIsValid = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether <span class="doxyComputerOutput">CachedGainLR</span> and <span class="doxyComputerOutput">CachedGainRL</span> are valid.</p>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>

</div>
</div>

### CachedGainLR {#a3dd6f4319020e637d6ca1d431f8f9177}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float llvm::BalancedPartitioning::UtilitySignature::CachedGainLR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cached gain of moving a <span class="doxyComputerOutput">FunctionNode</span> from the left bucket to the right bucket.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>

</div>
</div>

### CachedGainRL {#aa20c778a7b81b7fee3fe452f848af1f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float llvm::BalancedPartitioning::UtilitySignature::CachedGainRL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cached gain of moving a <span class="doxyComputerOutput">FunctionNode</span> from the right bucket to the left bucket.</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>

</div>
</div>

### LeftCount {#a7982f03d621ffdb803327fb70b4004e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BalancedPartitioning::UtilitySignature::LeftCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of <span class="doxyComputerOutput">FunctionNodes</span> in the left bucket.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>

</div>
</div>

### RightCount {#a3f08c8a8b2b632339e72c02fd5c2a7fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BalancedPartitioning::UtilitySignature::RightCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of <span class="doxyComputerOutput">FunctionNodes</span> in the right bucket.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/balancedpartitioning-h">BalancedPartitioning.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
