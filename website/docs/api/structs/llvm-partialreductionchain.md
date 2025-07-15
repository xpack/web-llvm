---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/partialreductionchain
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PartialReductionChain` Struct Reference

<p>A chain of instructions that form a partial reduction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::PartialReductionChain { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">Transforms/Vectorize/VPRecipeBuilder.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bfb0bdf19a26c2cf8012431cf3767dc">PartialReductionChain</a> (Instruction *Reduction, Instruction *ExtendA, Instruction *ExtendB, Instruction *BinOp)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a361f16955c8555edbee19fe966bff4">Reduction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The top-level binary operation that forms the reduction to a scalar after the loop body. <a href="#a7a361f16955c8555edbee19fe966bff4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbd3156f87785070d240a647f6c9bed8">ExtendA</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The extension of each of the inner binary operation's operands. <a href="#afbd3156f87785070d240a647f6c9bed8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ac993e4efd6a9e8e3ea11f89ef88ace">ExtendB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b204c4d86e9755fe475ce0ea89969a">BinOp</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The binary operation using the extends that is then reduced. <a href="#a08b204c4d86e9755fe475ce0ea89969a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A chain of instructions that form a partial reduction.</p>


<p>Designed to match: reduction_bin_op (bin_op (extend (A), (extend (B))), accumulator).</p>


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PartialReductionChain() {#a6bfb0bdf19a26c2cf8012431cf3767dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PartialReductionChain::PartialReductionChain (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Reduction, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ExtendA, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ExtendB, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * BinOp)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>


<p>References <a href="#a08b204c4d86e9755fe475ce0ea89969a">BinOp</a>, <a href="#afbd3156f87785070d240a647f6c9bed8">ExtendA</a>, <a href="#a4ac993e4efd6a9e8e3ea11f89ef88ace">ExtendB</a> and <a href="#a7a361f16955c8555edbee19fe966bff4">Reduction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BinOp {#a08b204c4d86e9755fe475ce0ea89969a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* llvm::PartialReductionChain::BinOp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The binary operation using the extends that is then reduced.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>


<p>Referenced by <a href="#a6bfb0bdf19a26c2cf8012431cf3767dc">PartialReductionChain</a>.</p>

</div>
</div>

### ExtendA {#afbd3156f87785070d240a647f6c9bed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* llvm::PartialReductionChain::ExtendA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The extension of each of the inner binary operation's operands.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>


<p>Referenced by <a href="#a6bfb0bdf19a26c2cf8012431cf3767dc">PartialReductionChain</a>.</p>

</div>
</div>

### ExtendB {#a4ac993e4efd6a9e8e3ea11f89ef88ace}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* llvm::PartialReductionChain::ExtendB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>


<p>Referenced by <a href="#a6bfb0bdf19a26c2cf8012431cf3767dc">PartialReductionChain</a>.</p>

</div>
</div>

### Reduction {#a7a361f16955c8555edbee19fe966bff4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* llvm::PartialReductionChain::Reduction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The top-level binary operation that forms the reduction to a scalar after the loop body.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>


<p>Referenced by <a href="#a6bfb0bdf19a26c2cf8012431cf3767dc">PartialReductionChain</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
