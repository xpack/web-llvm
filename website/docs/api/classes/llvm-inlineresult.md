---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/inlineresult
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InlineResult` Class

<p><a href="/web-llvm/docs/api/classes/llvm/inlineresult">InlineResult</a> is basically true or false. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::InlineResult { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">llvm/Analysis/InlineCost.h</a>"
</div>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96055ffe777b00650b47d4e3e0e70e97">InlineResult</a> (const char *Message=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af279070ae6350a3acd0e80ba7da7d397">isSuccess</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb1d767a6bb5c1db638b108eda9138b0">getFailureReason</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37b24c6852d9a412ea9ac4c9f46e5f00">Message</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/inlineresult">InlineResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a364fcb5fb838e7ca83b9fc379bcb4a0a">success</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/inlineresult">InlineResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77027fdc657b15aa5dd3d022e0fc07d3">failure</a> (const char *Reason)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/inlineresult">InlineResult</a> is basically true or false.</p>


<p>For false results the message describes a reason.</p>


<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### InlineResult() {#a96055ffe777b00650b47d4e3e0e70e97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InlineResult::InlineResult (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Message=nullptr)</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFailureReason() {#afb1d767a6bb5c1db638b108eda9138b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::InlineResult::getFailureReason ()</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#af279070ae6350a3acd0e80ba7da7d397">isSuccess</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-alwaysinliner-cpp-/#af5bb12426b6361914b816365eee4b4fd">anonymous{AlwaysInliner.cpp}::AlwaysInlineImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a11326a8194a8022478ebafeba2b5ccb5">llvm::getInlineCost</a>.</p>

</div>
</div>

### isSuccess() {#af279070ae6350a3acd0e80ba7da7d397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineResult::isSuccess ()</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-alwaysinliner-cpp-/#af5bb12426b6361914b816365eee4b4fd">anonymous{AlwaysInliner.cpp}::AlwaysInlineImpl</a>, <a href="#afb1d767a6bb5c1db638b108eda9138b0">getFailureReason</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11326a8194a8022478ebafeba2b5ccb5">llvm::getInlineCost</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#a05dd87a2da7ddff8ce97716e3b479b2e">InsertSafepointPoll</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Message {#a37b24c6852d9a412ea9ac4c9f46e5f00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::InlineResult::Message = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### failure() {#a77027fdc657b15aa5dd3d022e0fc07d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineResult llvm::InlineResult::failure (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Reason)</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a75514cc4632af88b58a31912c8bd9ecc">anonymous{InlineCost.cpp}::CallAnalyzer::analyze</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#ace15c0f86fa672d5a700a5f76b8b43e9">anonymous{InlineCost.cpp}::CallAnalyzer::analyzeBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa41f9508130468035e0087f7cbdffa14">llvm::getAttributeBasedInliningDecision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5ae8db70add348cf4c743530e9b9f54e">llvm::isInlineViable</a>.</p>

</div>
</div>

### success() {#a364fcb5fb838e7ca83b9fc379bcb4a0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineResult llvm::InlineResult::success ()</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a75514cc4632af88b58a31912c8bd9ecc">anonymous{InlineCost.cpp}::CallAnalyzer::analyze</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#ace15c0f86fa672d5a700a5f76b8b43e9">anonymous{InlineCost.cpp}::CallAnalyzer::analyzeBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a7896a35fbca2436be392ec036dc8ddcf">anonymous{InlineCost.cpp}::CallAnalyzer::finalizeAnalysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa41f9508130468035e0087f7cbdffa14">llvm::getAttributeBasedInliningDecision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5ae8db70add348cf4c743530e9b9f54e">llvm::isInlineViable</a> and <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a562c4d99c3b86a6aed450011e796e2bf">anonymous{InlineCost.cpp}::CallAnalyzer::onAnalysisStart</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">InlineCost.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
