---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/ve/vetargettransforminfo-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `VETargetTransformInfo.h` File

<p>This file a TargetTransformInfo::Concept conforming object specific to the VE target machine. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/ve-h">VE.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vetargetmachine-h">VETargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicttiimpl-h">llvm/CodeGen/BasicTTIImpl.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vettiimpl">VETTIImpl</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">llvm::Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec55937be412cbda7aa991ff7baee92b">getVectorElementType</a> (llvm::Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">llvm::Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fbcb58bc1a1edd667581b7993a74f0b">getLaneType</a> (llvm::Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6155dbe759f27f39e06009356e87fdb">isVectorLaneType</a> (llvm::Type &amp;ElemTy)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb6e4cf7fbf298a2192d2bbe9c98d1bb">VEC_VP_CASE</a>(SUFFIX)&nbsp;&nbsp;&nbsp;...</td>
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

<p>This file a TargetTransformInfo::Concept conforming object specific to the VE target machine.</p>


<p>It uses the target's detailed information to provide more precise answers to certain TTI queries, while letting the target independent and default TTI implementations handle the rest.</p>


<div class="doxySectionDef">

## Functions

### getLaneType() {#a3fbcb58bc1a1edd667581b7993a74f0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Type * getLaneType (<a href="/web-llvm/docs/api/classes/llvm/type">llvm::Type</a> * Ty)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vetargettransforminfo-h">VETargetTransformInfo.h</a>.</p>


<p>References <a href="#aec55937be412cbda7aa991ff7baee92b">getVectorElementType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vettiimpl/#ad0b827df207b5ffe51d9bb1ffd3a75e9">llvm::VETTIImpl::isLegalMaskedGather</a>, <a href="/web-llvm/docs/api/classes/llvm/vettiimpl/#ac4f9d68234382ecee5d498e044fb6049">llvm::VETTIImpl::isLegalMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/vettiimpl/#a92db754af46e372d74c7863f1b2ccc2b">llvm::VETTIImpl::isLegalMaskedScatter</a> and <a href="/web-llvm/docs/api/classes/llvm/vettiimpl/#a641821e9d4b829774e3c999a4ce08e7c">llvm::VETTIImpl::isLegalMaskedStore</a>.</p>

</div>
</div>

### getVectorElementType() {#aec55937be412cbda7aa991ff7baee92b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Type * getVectorElementType (<a href="/web-llvm/docs/api/classes/llvm/type">llvm::Type</a> * Ty)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vetargettransforminfo-h">VETargetTransformInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="#a3fbcb58bc1a1edd667581b7993a74f0b">getLaneType</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a157df6c452c1d0206e530eae65dce28b">llvm::HexagonTargetLowering::LowerINSERT_VECTOR_ELT</a>.</p>

</div>
</div>

### isVectorLaneType() {#ad6155dbe759f27f39e06009356e87fdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isVectorLaneType (<a href="/web-llvm/docs/api/classes/llvm/type">llvm::Type</a> &amp; ElemTy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vetargettransforminfo-h">VETargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vettiimpl/#ad0b827df207b5ffe51d9bb1ffd3a75e9">llvm::VETTIImpl::isLegalMaskedGather</a>, <a href="/web-llvm/docs/api/classes/llvm/vettiimpl/#ac4f9d68234382ecee5d498e044fb6049">llvm::VETTIImpl::isLegalMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/vettiimpl/#a92db754af46e372d74c7863f1b2ccc2b">llvm::VETTIImpl::isLegalMaskedScatter</a> and <a href="/web-llvm/docs/api/classes/llvm/vettiimpl/#a641821e9d4b829774e3c999a4ce08e7c">llvm::VETTIImpl::isLegalMaskedStore</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### VEC\_VP\_CASE {#aeb6e4cf7fbf298a2192d2bbe9c98d1bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VEC_VP_CASE(SUFFIX)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case Intrinsic::vp_reduce_##SUFFIX:                                          \
  case Intrinsic::vector_reduce_##SUFFIX:
</div>
</dd>
</dl>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vetargettransforminfo-h">VETargetTransformInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
