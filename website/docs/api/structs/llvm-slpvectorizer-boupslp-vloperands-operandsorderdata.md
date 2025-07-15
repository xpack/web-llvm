---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/slpvectorizer/boupslp/vloperands/operandsorderdata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `OperandsOrderData` Struct Reference

<p>Data structure that helps to reorder operands. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::slpvectorizer::BoUpSLP::VLOperands::OperandsOrderData { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d7b969aa757358cc66838b894b0f743">NumOfAPOs</a> = UINT_MAX</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The best number of operands with the same APOs, which can be reordered. <a href="#a6d7b969aa757358cc66838b894b0f743">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fe47bae7e37639797e71db8d82a7b48">NumOpsWithSameOpcodeParent</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of operands with the same/alternate instruction opcode and parent. <a href="#a4fe47bae7e37639797e71db8d82a7b48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4ed9a6ff7cdb49815d4bbf3e471207a">Hash</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hash for the actual operands ordering. <a href="#aa4ed9a6ff7cdb49815d4bbf3e471207a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Data structure that helps to reorder operands.</p>

<p>Definition at line 2363 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Hash {#aa4ed9a6ff7cdb49815d4bbf3e471207a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::slpvectorizer::BoUpSLP::VLOperands::OperandsOrderData::Hash = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hash for the actual operands ordering.</p>


<p>Used to count operands, actually their position id and opcode value. It is used in the voting mechanism to find the lane with the least number of operands that can freely move about or less profitable because it already has the most optimal set of operands. Can be replaced with <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;unsigned&gt;</a> instead but hash code is faster and requires less memory.</p>


<p>Definition at line 2377 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### NumOfAPOs {#a6d7b969aa757358cc66838b894b0f743}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::slpvectorizer::BoUpSLP::VLOperands::OperandsOrderData::NumOfAPOs = UINT_MAX</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The best number of operands with the same APOs, which can be reordered.</p>

<p>Definition at line 2366 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### NumOpsWithSameOpcodeParent {#a4fe47bae7e37639797e71db8d82a7b48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::slpvectorizer::BoUpSLP::VLOperands::OperandsOrderData::NumOpsWithSameOpcodeParent = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of operands with the same/alternate instruction opcode and parent.</p>

<p>Definition at line 2369 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
