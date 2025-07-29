---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/fmfsource
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FMFSource` Class

<p>This provides a helper for copying FMF from an instruction or setting specified flags. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FMFSource { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a668e4d8eef9a34e17d2a488d15da2eb7">FMFSource</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2462a20e8f7f637c16ca5d0271004fae">FMFSource</a> (Instruction *Source)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0bfba3f4ab730db1fb4812e909cf427">FMFSource</a> (FastMathFlags FMF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae99ade23f19c465db1f9aaf9786c58d">get</a> (FastMathFlags Default) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e051a80b42475c3a4f3d22f31dda741">FMF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fmfsource">FMFSource</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af63b286b1615a2c0712b4bc0190ab999">intersect</a> (Value *A, Value *B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Intersect the FMF from two instructions. <a href="#af63b286b1615a2c0712b4bc0190ab999">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This provides a helper for copying FMF from an instruction or setting specified flags.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FMFSource() {#a668e4d8eef9a34e17d2a488d15da2eb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FMFSource::FMFSource ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>


<p>Referenced by <a href="#af63b286b1615a2c0712b4bc0190ab999">intersect</a>.</p>

</div>
</div>

### FMFSource() {#a2462a20e8f7f637c16ca5d0271004fae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FMFSource::FMFSource (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Source)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>

</div>
</div>

### FMFSource() {#ad0bfba3f4ab730db1fb4812e909cf427}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FMFSource::FMFSource (<a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### get() {#aae99ade23f19c465db1f9aaf9786c58d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastMathFlags llvm::FMFSource::get (<a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> Default)</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8f733600a2dd274a9d75d0aa03eea7b2">llvm::IRBuilderBase::CreateBinOpFMF</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a583e55c8ed0087682c7ee07a608a89bd">llvm::IRBuilderBase::CreateConstrainedFPBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#af9b27960ecdd02de32114ff5a0b13077">llvm::IRBuilderBase::CreateConstrainedFPCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a16e1a960f1fead3a996f7155c9a691ba">llvm::IRBuilderBase::CreateConstrainedFPUnroundedBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad27ceb2345c5c425b50c7e88ae8f75bb">llvm::IRBuilderBase::CreateFAddFMF</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae844606543ef6010077be2b702d88108">llvm::IRBuilderBase::CreateFDivFMF</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aec0517c3f23ebbd05772964b3d4ab793">llvm::IRBuilderBase::CreateFMulFMF</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#adce7fec7d25956e70f6efc6eb903474d">llvm::IRBuilderBase::CreateFNegFMF</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aee66118b3aa21c99784ea26807ad2c4e">llvm::IRBuilderBase::CreateFRemFMF</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a08fb3d828cb9186e249a2fa3e5a12581">llvm::IRBuilderBase::CreateFSubFMF</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3cd8a9205d8cc6d024b6e6344a72aca0">llvm::IRBuilderBase::CreateSelectFMF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FMF {#a1e051a80b42475c3a4f3d22f31dda741}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;FastMathFlags&gt; llvm::FMFSource::FMF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### intersect() {#af63b286b1615a2c0712b4bc0190ab999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FMFSource llvm::FMFSource::intersect (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * A, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * B)</td>
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

<p>Intersect the FMF from two instructions.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#a668e4d8eef9a34e17d2a488d15da2eb7">FMFSource</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a5946d75decfd106d2b75af6d59009f34">matchIsFiniteTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a8208d3cd3c60073f5c9ceefec06ab2e3">reassociateFCmps</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
