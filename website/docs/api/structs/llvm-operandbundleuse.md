---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/operandbundleuse
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `OperandBundleUse` Struct

<p>A lightweight accessor for an operand bundle meant to be passed around by value. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::OperandBundleUse { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c30b8969b997efb2b8a4ef6f06879cf">OperandBundleUse</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a606007cc5256366205c911e1e09280e0">OperandBundleUse</a> (StringMapEntry&lt; uint32_t &gt; *Tag, ArrayRef&lt; Use &gt; Inputs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac238c607b975f154fdb79217216c210b">operandHasAttr</a> (unsigned Idx, Attribute::AttrKind A) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the operand at index <span class="doxyComputerOutput">Idx</span> in this operand bundle has the attribute A. <a href="#ac238c607b975f154fdb79217216c210b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18c31f8bc506304f4a6c1e4047f1e2bb">getTagName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the tag of this operand bundle as a string. <a href="#a18c31f8bc506304f4a6c1e4047f1e2bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6386ca6c50ec4ef5d9a0f13e7fe8f0c9">getTagID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the tag of this operand bundle as an integer. <a href="#a6386ca6c50ec4ef5d9a0f13e7fe8f0c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bd7090fddde0e93743906756b5ba660">isDeoptOperandBundle</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a "deopt" operand bundle. <a href="#a2bd7090fddde0e93743906756b5ba660">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10c3844c83f201ea13fbf0b92aca41ff">isFuncletOperandBundle</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a "funclet" operand bundle. <a href="#a10c3844c83f201ea13fbf0b92aca41ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78dff764432c73c194e76b65148a1f9">isCFGuardTargetOperandBundle</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a "cfguardtarget" operand bundle. <a href="#ad78dff764432c73c194e76b65148a1f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d68cbafa7572a5216785c899dc621fa">Inputs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a>&lt; uint32_t &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82e86a25ade5508e82b838fec8a7b0b8">Tag</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to an entry in <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a6ca6e14339dfb653b003a458b80a4802">LLVMContextImpl::getOrInsertBundleTag</a>. <a href="#a82e86a25ade5508e82b838fec8a7b0b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A lightweight accessor for an operand bundle meant to be passed around by value.</p>

<p>Definition at line 1007 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OperandBundleUse() {#a5c30b8969b997efb2b8a4ef6f06879cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OperandBundleUse::OperandBundleUse ()</td>
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



<p>Definition at line 1010 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

### OperandBundleUse() {#a606007cc5256366205c911e1e09280e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OperandBundleUse::OperandBundleUse (<a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a>&lt; uint32_t &gt; * Tag, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &gt; Inputs)</td>
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



<p>Definition at line 1011 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a6d68cbafa7572a5216785c899dc621fa">Inputs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getTagID() {#a6386ca6c50ec4ef5d9a0f13e7fe8f0c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::OperandBundleUse::getTagID ()</td>
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

<p>Return the tag of this operand bundle as an integer.</p>


<p>Operand bundle tags are interned by <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a6ca6e14339dfb653b003a458b80a4802">LLVMContextImpl::getOrInsertBundleTag</a>, and this function returns the unique integer getOrInsertBundleTag associated the tag of this operand bundle to.</p>


<p>Definition at line 1035 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a25f0b41add9507b8eafadfbc4a090d6c">cloneInstructionInExitBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aa2d248762d49cd9fa5443dea54c7e6f3">llvm::CallBase::hasOperandBundlesOtherThan</a>, <a href="#ad78dff764432c73c194e76b65148a1f9">isCFGuardTargetOperandBundle</a>, <a href="#a2bd7090fddde0e93743906756b5ba660">isDeoptOperandBundle</a>, <a href="#a10c3844c83f201ea13fbf0b92aca41ff">isFuncletOperandBundle</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a203a11487b55577e3f295af2e3e2ae2a">llvm::CallBase::isOperandBundleOfType</a>.</p>

</div>
</div>

### getTagName() {#a18c31f8bc506304f4a6c1e4047f1e2bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::OperandBundleUse::getTagName ()</td>
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

<p>Return the tag of this operand bundle as a string.</p>

<p>Definition at line 1026 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/alignmentfromassumptionspass/#a1ef8e45df24dcf4222b48c8fe4077c3e">llvm::AlignmentFromAssumptionsPass::extractAlignmentInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/assumptioncache-cpp/#a51e2be2d1cd63e7b951c1f25c8eb182b">findAffectedValues</a>, <a href="/web-llvm/docs/api/classes/llvm/operandbundledeft/#a305a479bc62cb68d8a308a0ba43e7505">llvm::OperandBundleDefT&lt; Value * &gt;::OperandBundleDefT</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a404d6605bd1587cb6b67b8b1f575022e">anonymous{AsmWriter.cpp}::AssemblyWriter::writeOperandBundles</a>.</p>

</div>
</div>

### isCFGuardTargetOperandBundle() {#ad78dff764432c73c194e76b65148a1f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OperandBundleUse::isCFGuardTargetOperandBundle ()</td>
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

<p>Return true if this is a "cfguardtarget" operand bundle.</p>

<p>Definition at line 1050 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a6386ca6c50ec4ef5d9a0f13e7fe8f0c9">getTagID</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9ca7ccabf0c8cf51c267c1e0cd9a66261d8">llvm::LLVMContext::OB_cfguardtarget</a>.</p>

</div>
</div>

### isDeoptOperandBundle() {#a2bd7090fddde0e93743906756b5ba660}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OperandBundleUse::isDeoptOperandBundle ()</td>
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

<p>Return true if this is a "deopt" operand bundle.</p>

<p>Definition at line 1040 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a6386ca6c50ec4ef5d9a0f13e7fe8f0c9">getTagID</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9ca3f6df86c6efab701ade7abbc3134c25a">llvm::LLVMContext::OB_deopt</a>.</p>


<p>Referenced by <a href="#ac238c607b975f154fdb79217216c210b">operandHasAttr</a>.</p>

</div>
</div>

### isFuncletOperandBundle() {#a10c3844c83f201ea13fbf0b92aca41ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OperandBundleUse::isFuncletOperandBundle ()</td>
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

<p>Return true if this is a "funclet" operand bundle.</p>

<p>Definition at line 1045 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a6386ca6c50ec4ef5d9a0f13e7fe8f0c9">getTagID</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9ca8997c6b0930e2c05209e95e7172c6cf3">llvm::LLVMContext::OB_funclet</a>.</p>

</div>
</div>

### operandHasAttr() {#ac238c607b975f154fdb79217216c210b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OperandBundleUse::operandHasAttr (unsigned Idx, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> A)</td>
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

<p>Return true if the operand at index <span class="doxyComputerOutput">Idx</span> in this operand bundle has the attribute A.</p>

<p>Definition at line 1016 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a6d68cbafa7572a5216785c899dc621fa">Inputs</a> and <a href="#a2bd7090fddde0e93743906756b5ba660">isDeoptOperandBundle</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Inputs {#a6d68cbafa7572a5216785c899dc621fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;Use&gt; llvm::OperandBundleUse::Inputs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1008 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/alignmentfromassumptionspass/#a1ef8e45df24dcf4222b48c8fe4077c3e">llvm::AlignmentFromAssumptionsPass::extractAlignmentInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/assumptioncache-cpp/#a51e2be2d1cd63e7b951c1f25c8eb182b">findAffectedValues</a>, <a href="/web-llvm/docs/api/classes/llvm/operandbundledeft/#a305a479bc62cb68d8a308a0ba43e7505">llvm::OperandBundleDefT&lt; Value * &gt;::OperandBundleDefT</a>, <a href="#a606007cc5256366205c911e1e09280e0">OperandBundleUse</a>, <a href="#ac238c607b975f154fdb79217216c210b">operandHasAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a404d6605bd1587cb6b67b8b1f575022e">anonymous{AsmWriter.cpp}::AssemblyWriter::writeOperandBundles</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Tag {#a82e86a25ade5508e82b838fec8a7b0b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMapEntry&lt;uint32_t&gt;* llvm::OperandBundleUse::Tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer to an entry in <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a6ca6e14339dfb653b003a458b80a4802">LLVMContextImpl::getOrInsertBundleTag</a>.</p>

<p>Definition at line 1056 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
