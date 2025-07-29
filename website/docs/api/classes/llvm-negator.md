---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/negator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Negator` Class



## Declaration

<div class="doxyDeclaration">
class llvm::Negator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">Transforms/InstCombine/InstCombineInternal.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace705abb41ee0f3428f23ee70299582e">BuilderTy</a> = <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targetfolder">TargetFolder</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuildercallbackinserter">IRBuilderCallbackInserter</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a274585097ffac5145e8252226f6cc2cf">Result</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a007f36cd63770aa2afbc266698d72f99">Negator</a> (LLVMContext &amp;C, const DataLayout &amp;DL, const DominatorTree &amp;DT, bool IsTrulyNegation)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8329c0f8e42513c6ed0cfba6774a6df">Negator</a> (const Negator &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eba07f57521263a65a5d081d019c914">Negator</a> (Negator &amp;&amp;)=delete</td>
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

## Private Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/negator">Negator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22885c61ce1e5de3ad59c5b2cbec7a48">operator=</a> (const Negator &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/negator">Negator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2017eb6b6bf65b25ab42ad9f283d38b3">operator=</a> (Negator &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c74a4b8e51b2ad36b2077e08ddd372d">getSortedOperandsOfBinOp</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b7d4b06362949ea609c82aee646c0a4">visitImpl</a> (Value *V, bool IsNSW, unsigned Depth)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a561bb46df915266855cb0119eaa9037f">negate</a> (Value *V, bool IsNSW, unsigned Depth)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; Result &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a588489f997b4115bca3bdf943b0f4f39">run</a> (Value *Root, bool IsNSW)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recurse depth-first and attempt to sink the negation. <a href="#a588489f997b4115bca3bdf943b0f4f39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h/#a72a4e048e0449ae5f8676a9551ac50bb">NegatorMaxNodesSSO</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ec6761675c2590a23aace9cbc1688ef">NewInstructions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Top-to-bottom, def-to-use negated instruction tree we produced. <a href="#a6ec6761675c2590a23aace9cbc1688ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irbuilder">BuilderTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01e49fb8561321486ffdc6c5fb9524a6">Builder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4297f8aa6341b686567c12b63b9fd45e">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaad8d39ab5be9a4bd352305c71c0bc79">IsTrulyNegation</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72dbd3d89e994b3974456ce40a30ef68">NegationsCache</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2abe5e7f029b63c7b1bd29ac231ef7fa">Negate</a> (bool LHSIsZero, bool IsNSW, Value *Root, InstCombinerImpl &amp;IC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to negate <span class="doxyComputerOutput">Root</span>. <a href="#a2abe5e7f029b63c7b1bd29ac231ef7fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 802 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BuilderTy {#ace705abb41ee0f3428f23ee70299582e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Negator::BuilderTy =  IRBuilder&lt;TargetFolder, IRBuilderCallbackInserter&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 806 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>.</p>

</div>
</div>

### Result {#a274585097ffac5145e8252226f6cc2cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Negator::Result =  std::pair&lt;ArrayRef&lt;Instruction *&gt; ,
                           Value * &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 823 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### Negator() {#a007f36cd63770aa2afbc266698d72f99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Negator::Negator (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, bool IsTrulyNegation)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 815 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinenegator-cpp">InstCombineNegator.cpp</a>.</p>

</div>
</div>

### Negator() {#ae8329c0f8e42513c6ed0cfba6774a6df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Negator::Negator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/negator">Negator</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 836 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>.</p>

</div>
</div>

### Negator() {#a2eba07f57521263a65a5d081d019c914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Negator::Negator (<a href="/web-llvm/docs/api/classes/llvm/negator">Negator</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 837 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Operators

### operator=() {#a22885c61ce1e5de3ad59c5b2cbec7a48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Negator &amp; llvm::Negator::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/negator">Negator</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 838 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>.</p>

</div>
</div>

### operator=() {#a2017eb6b6bf65b25ab42ad9f283d38b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Negator &amp; llvm::Negator::operator= (<a href="/web-llvm/docs/api/classes/llvm/negator">Negator</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 839 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getSortedOperandsOfBinOp() {#a7c74a4b8e51b2ad36b2077e08ddd372d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt; Value *, 2 &gt; Negator::getSortedOperandsOfBinOp (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 826 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinenegator-cpp">InstCombineNegator.cpp</a>.</p>

</div>
</div>

### negate() {#a561bb46df915266855cb0119eaa9037f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * Negator::negate (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, bool IsNSW, unsigned Depth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 830 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>, definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinenegator-cpp">InstCombineNegator.cpp</a>.</p>

</div>
</div>

### run() {#a588489f997b4115bca3bdf943b0f4f39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Negator::Result &gt; Negator::run (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Root, bool IsNSW)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recurse depth-first and attempt to sink the negation.</p>


<p>FIXME: use worklist?</p>


<p>Declaration at line 834 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>, definition at line 532 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinenegator-cpp">InstCombineNegator.cpp</a>.</p>

</div>
</div>

### visitImpl() {#a3b7d4b06362949ea609c82aee646c0a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * Negator::visitImpl (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, bool IsNSW, unsigned Depth)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 828 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinenegator-cpp">InstCombineNegator.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Builder {#a01e49fb8561321486ffdc6c5fb9524a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BuilderTy llvm::Negator::Builder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>.</p>

</div>
</div>

### DT {#a4297f8aa6341b686567c12b63b9fd45e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DominatorTree&amp; llvm::Negator::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>.</p>

</div>
</div>

### IsTrulyNegation {#aaad8d39ab5be9a4bd352305c71c0bc79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::Negator::IsTrulyNegation</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 811 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>.</p>

</div>
</div>

### NegationsCache {#a72dbd3d89e994b3974456ce40a30ef68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;Value *, Value *&gt; llvm::Negator::NegationsCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 813 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>.</p>

</div>
</div>

### NewInstructions {#a6ec6761675c2590a23aace9cbc1688ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction *, NegatorMaxNodesSSO&gt; llvm::Negator::NewInstructions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Top-to-bottom, def-to-use negated instruction tree we produced.</p>

<p>Definition at line 804 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Negate() {#a2abe5e7f029b63c7b1bd29ac231ef7fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * Negator::Negate (bool LHSIsZero, bool IsNSW, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Root, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl">InstCombinerImpl</a> &amp; IC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to negate <span class="doxyComputerOutput">Root</span>.</p>


<p>Retuns nullptr if negation can't be performed, otherwise returns negated value.</p>


<p>Declaration at line 844 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a>, definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinenegator-cpp">InstCombineNegator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#ae1d331bc844ecb92bdeb0b706ae04396">llvm::InstCombiner::Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#abfaa2c91fd145d6b7e623cabd26ec1de">llvm::IRBuilderBase::ClearInsertionPoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#a16262e69f9cdf5d2c9d5623c3b06af43">llvm::InstCombiner::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#a209240824927e66a0caa50636623e79a">llvm::InstCombiner::getDominatorTree</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8ef25defccf4817608a13e7a9db4000d">llvm::IRBuilderBase::Insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinenegator-cpp/#a399cb04b1d86763d5e7b98059c8ddaf2">NegatorEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63fc74646456a3bed261512f21efe29c">llvm::IRBuilderBase::SetCurrentDebugLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/debugcounter/#a5aace8653ce3726ef07194dcf6bce2bf">llvm::DebugCounter::shouldExecute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineinternal-h">InstCombineInternal.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinenegator-cpp">InstCombineNegator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
