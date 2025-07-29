---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/inlineadvice
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InlineAdvice` Class

<p>Capture state between an inlining decision having had been made, and its impact being observable. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::InlineAdvice { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">llvm/Analysis/InlineAdvisor.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-inlineadvisor-cpp-/mandatoryinlineadvice">MandatoryInlineAdvice</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/defaultinlineadvice">DefaultInlineAdvice</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice">MLInlineAdvice</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/inlineadvice">InlineAdvice</a> that tracks changes post inlining. <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8500015965ef1b86e39cd83fd2fc8dff">InlineAdvice</a> (InlineAdvisor *Advisor, CallBase &amp;CB, OptimizationRemarkEmitter &amp;ORE, bool IsInliningRecommended)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f2f0b55164be2994a3f57ef0da2d5b0">InlineAdvice</a> (InlineAdvice &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a159c0cde7d49bf2af6aaa2673fba1c8b">InlineAdvice</a> (const InlineAdvice &amp;)=delete</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a800e01d3e96c44915cc730357816ffb6">~InlineAdvice</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a502cd38779dd8be4dba948542f40e7a6">recordInlining</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Exactly one of the record* APIs must be called. <a href="#a502cd38779dd8be4dba948542f40e7a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9aea72d2562f8b77500a09e2142ee47">recordInliningWithCalleeDeleted</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call after inlining succeeded, and results in the callee being delete-able, meaning, it has no more users, and will be cleaned up subsequently. <a href="#ac9aea72d2562f8b77500a09e2142ee47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1283861a2f0b49ea363c83e6d6af75c1">recordUnsuccessfulInlining</a> (const InlineResult &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call after the decision for a call site was to not inline. <a href="#a1283861a2f0b49ea363c83e6d6af75c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17ab1adda4fe2be5d067a64d93a4b99d">recordUnattemptedInlining</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call to indicate inlining was not attempted. <a href="#a17ab1adda4fe2be5d067a64d93a4b99d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7abcbeaf6e8ebe6acac592b6cdaaad0">isInliningRecommended</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the inlining recommendation. <a href="#ad7abcbeaf6e8ebe6acac592b6cdaaad0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20c6955bf6aae735ace433d5ff837c7e">getOriginalCallSiteDebugLoc</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32d72f641d87600e0e1a21f1a3908b67">getOriginalCallSiteBasicBlock</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cc477a041ff4164bff037ca245f3034">recordInliningImpl</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a170d7fdcdf4dcf62dbc4dc1ceecd0063">recordInliningWithCalleeDeletedImpl</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63e52cfd391f38c46cbc52cfc8d741e0">recordUnsuccessfulInliningImpl</a> (const InlineResult &amp;Result)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a5c729c3dee8bca911ff8fa3357920f">recordUnattemptedInliningImpl</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad109e888832c20346f2dd463e9bcb396">markRecorded</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27f4bd6b7163ca4cf3cd2370f2cd0ce3">recordInlineStatsIfNeeded</a> ()</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a840ff172791c81e7277a6fcf89c91dbe">Advisor</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a078183205dd7f49738ba34f1586e9620">Caller</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Caller and Callee are pre-inlining. <a href="#a078183205dd7f49738ba34f1586e9620">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00ec8d01596f9885f6303a98fbc8197b">Callee</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadc3866d7b0ecd242180fb85d3b0e748">DLoc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a314b23a57d33b1ca800c2a273b7116ff">Block</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52090ce3aedce0b4004ca443c193b110">ORE</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf54b36d4d196330fc5b63d0f0022e80">IsInliningRecommended</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bbc8cd029db1f8f934c88861fb21793">Recorded</a> = false</td>
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

<p>Capture state between an inlining decision having had been made, and its impact being observable.</p>


<p>When collecting model training data, this allows recording features/decisions/partial reward data sets.</p>


<p>Derivations of this type are expected to be tightly coupled with their InliningAdvisors. The base type implements the minimal contractual obligations.</p>


<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InlineAdvice() {#a8500015965ef1b86e39cd83fd2fc8dff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineAdvice::InlineAdvice (<a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a> * Advisor, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE, bool IsInliningRecommended)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp">InlineAdvisor.cpp</a>.</p>


<p>References <a href="#a840ff172791c81e7277a6fcf89c91dbe">Advisor</a>, <a href="#a314b23a57d33b1ca800c2a273b7116ff">Block</a>, <a href="#a00ec8d01596f9885f6303a98fbc8197b">Callee</a>, <a href="#a078183205dd7f49738ba34f1586e9620">Caller</a>, <a href="#aadc3866d7b0ecd242180fb85d3b0e748">DLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp/#aa04dbee2593fa5fbeb0552fcb8a00ee4">getCalledFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstrbundle-cpp/#af44c9b089359803924e0b92bea3b6d03">getDebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="#adf54b36d4d196330fc5b63d0f0022e80">IsInliningRecommended</a> and <a href="#a52090ce3aedce0b4004ca443c193b110">ORE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/defaultinlineadvice/#acd3ac174fece42a9120f8fe134adbffe">llvm::DefaultInlineAdvice::DefaultInlineAdvice</a>, <a href="#a159c0cde7d49bf2af6aaa2673fba1c8b">InlineAdvice</a>, <a href="#a0f2f0b55164be2994a3f57ef0da2d5b0">InlineAdvice</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlineadvisor-cpp-/mandatoryinlineadvice/#af681b273c456b33574537c3d01ef2bb5">anonymous{InlineAdvisor.cpp}::MandatoryInlineAdvice::MandatoryInlineAdvice</a> and <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#a413e5428e006570e79370b033a107dec">llvm::MLInlineAdvice::MLInlineAdvice</a>.</p>

</div>
</div>

### InlineAdvice() {#a0f2f0b55164be2994a3f57ef0da2d5b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InlineAdvice::InlineAdvice (<a href="/web-llvm/docs/api/classes/llvm/inlineadvice">InlineAdvice</a> &amp;&amp;)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Reference <a href="#a8500015965ef1b86e39cd83fd2fc8dff">InlineAdvice</a>.</p>

</div>
</div>

### InlineAdvice() {#a159c0cde7d49bf2af6aaa2673fba1c8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InlineAdvice::InlineAdvice (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inlineadvice">InlineAdvice</a> &amp;)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Reference <a href="#a8500015965ef1b86e39cd83fd2fc8dff">InlineAdvice</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~InlineAdvice() {#a800e01d3e96c44915cc730357816ffb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::InlineAdvice::~InlineAdvice ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getOriginalCallSiteBasicBlock() {#a32d72f641d87600e0e1a21f1a3908b67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock * llvm::InlineAdvice::getOriginalCallSiteBasicBlock ()</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Reference <a href="#a314b23a57d33b1ca800c2a273b7116ff">Block</a>.</p>

</div>
</div>

### getOriginalCallSiteDebugLoc() {#a20c6955bf6aae735ace433d5ff837c7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DebugLoc &amp; llvm::InlineAdvice::getOriginalCallSiteDebugLoc ()</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Reference <a href="#aadc3866d7b0ecd242180fb85d3b0e748">DLoc</a>.</p>

</div>
</div>

### isInliningRecommended() {#ad7abcbeaf6e8ebe6acac592b6cdaaad0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAdvice::isInliningRecommended ()</td>
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

<p>Get the inlining recommendation.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Reference <a href="#adf54b36d4d196330fc5b63d0f0022e80">IsInliningRecommended</a>.</p>

</div>
</div>

### recordInlining() {#a502cd38779dd8be4dba948542f40e7a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InlineAdvice::recordInlining ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Exactly one of the record* APIs must be called.</p>


<p>Implementers may extend behavior by implementing the corresponding record*Impl.</p>


<p>Call after inlining succeeded, and did not result in deleting the callee.</p>


<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>, definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp">InlineAdvisor.cpp</a>.</p>


<p>Reference <a href="#a2cc477a041ff4164bff037ca245f3034">recordInliningImpl</a>.</p>

</div>
</div>

### recordInliningWithCalleeDeleted() {#ac9aea72d2562f8b77500a09e2142ee47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InlineAdvice::recordInliningWithCalleeDeleted ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Call after inlining succeeded, and results in the callee being delete-able, meaning, it has no more users, and will be cleaned up subsequently.</p>

<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp">InlineAdvisor.cpp</a>.</p>


<p>Reference <a href="#a170d7fdcdf4dcf62dbc4dc1ceecd0063">recordInliningWithCalleeDeletedImpl</a>.</p>

</div>
</div>

### recordUnattemptedInlining() {#a17ab1adda4fe2be5d067a64d93a4b99d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InlineAdvice::recordUnattemptedInlining ()</td>
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

<p>Call to indicate inlining was not attempted.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Reference <a href="#a9a5c729c3dee8bca911ff8fa3357920f">recordUnattemptedInliningImpl</a>.</p>

</div>
</div>

### recordUnsuccessfulInlining() {#a1283861a2f0b49ea363c83e6d6af75c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InlineAdvice::recordUnsuccessfulInlining (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inlineresult">InlineResult</a> &amp; Result)</td>
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

<p>Call after the decision for a call site was to not inline.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Reference <a href="#a63e52cfd391f38c46cbc52cfc8d741e0">recordUnsuccessfulInliningImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### recordInliningImpl() {#a2cc477a041ff4164bff037ca245f3034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::InlineAdvice::recordInliningImpl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Referenced by <a href="#a502cd38779dd8be4dba948542f40e7a6">recordInlining</a>.</p>

</div>
</div>

### recordInliningWithCalleeDeletedImpl() {#a170d7fdcdf4dcf62dbc4dc1ceecd0063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::InlineAdvice::recordInliningWithCalleeDeletedImpl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Referenced by <a href="#ac9aea72d2562f8b77500a09e2142ee47">recordInliningWithCalleeDeleted</a>.</p>

</div>
</div>

### recordUnattemptedInliningImpl() {#a9a5c729c3dee8bca911ff8fa3357920f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::InlineAdvice::recordUnattemptedInliningImpl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Referenced by <a href="#a17ab1adda4fe2be5d067a64d93a4b99d">recordUnattemptedInlining</a>.</p>

</div>
</div>

### recordUnsuccessfulInliningImpl() {#a63e52cfd391f38c46cbc52cfc8d741e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::InlineAdvice::recordUnsuccessfulInliningImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inlineresult">InlineResult</a> &amp; Result)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Referenced by <a href="#a1283861a2f0b49ea363c83e6d6af75c1">recordUnsuccessfulInlining</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### markRecorded() {#ad109e888832c20346f2dd463e9bcb396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InlineAdvice::markRecorded ()</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>

</div>
</div>

### recordInlineStatsIfNeeded() {#a27f4bd6b7163ca4cf3cd2370f2cd0ce3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InlineAdvice::recordInlineStatsIfNeeded ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>, definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp">InlineAdvisor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Advisor {#a840ff172791c81e7277a6fcf89c91dbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineAdvisor* const llvm::InlineAdvice::Advisor</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/defaultinlineadvice/#acd3ac174fece42a9120f8fe134adbffe">llvm::DefaultInlineAdvice::DefaultInlineAdvice</a>, <a href="#a8500015965ef1b86e39cd83fd2fc8dff">InlineAdvice</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlineadvisor-cpp-/mandatoryinlineadvice/#af681b273c456b33574537c3d01ef2bb5">anonymous{InlineAdvisor.cpp}::MandatoryInlineAdvice::MandatoryInlineAdvice</a> and <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#a413e5428e006570e79370b033a107dec">llvm::MLInlineAdvice::MLInlineAdvice</a>.</p>

</div>
</div>

### Block {#a314b23a57d33b1ca800c2a273b7116ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock* const llvm::InlineAdvice::Block</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Referenced by <a href="#a32d72f641d87600e0e1a21f1a3908b67">getOriginalCallSiteBasicBlock</a>, <a href="#a8500015965ef1b86e39cd83fd2fc8dff">InlineAdvice</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#a79fede4389dbc2b630710e3c09787a20">llvm::MLInlineAdvice::recordInliningImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#af08e89bee7499bc47dbc39d981c5c436">llvm::MLInlineAdvice::recordInliningWithCalleeDeletedImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#afab4dde8e888e2564c2108a9c149f12d">llvm::MLInlineAdvice::recordUnattemptedInliningImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#ac725e56738dcc1fc8de94a7554491456">llvm::MLInlineAdvice::recordUnsuccessfulInliningImpl</a>.</p>

</div>
</div>

### Callee {#a00ec8d01596f9885f6303a98fbc8197b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* const llvm::InlineAdvice::Callee</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#ada4b28b495ff3ca02d3373edf2b5bac6">llvm::MLInlineAdvice::getCallee</a>, <a href="#a8500015965ef1b86e39cd83fd2fc8dff">InlineAdvice</a> and <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#a413e5428e006570e79370b033a107dec">llvm::MLInlineAdvice::MLInlineAdvice</a>.</p>

</div>
</div>

### Caller {#a078183205dd7f49738ba34f1586e9620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* const llvm::InlineAdvice::Caller</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Caller and Callee are pre-inlining.</p>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#ab7a31fef6e390f4ddf21f9f63a94f70f">llvm::MLInlineAdvice::getCaller</a>, <a href="#a8500015965ef1b86e39cd83fd2fc8dff">InlineAdvice</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#a413e5428e006570e79370b033a107dec">llvm::MLInlineAdvice::MLInlineAdvice</a> and <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#ac725e56738dcc1fc8de94a7554491456">llvm::MLInlineAdvice::recordUnsuccessfulInliningImpl</a>.</p>

</div>
</div>

### DLoc {#aadc3866d7b0ecd242180fb85d3b0e748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DebugLoc llvm::InlineAdvice::DLoc</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Referenced by <a href="#a20c6955bf6aae735ace433d5ff837c7e">getOriginalCallSiteDebugLoc</a>, <a href="#a8500015965ef1b86e39cd83fd2fc8dff">InlineAdvice</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#a79fede4389dbc2b630710e3c09787a20">llvm::MLInlineAdvice::recordInliningImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#af08e89bee7499bc47dbc39d981c5c436">llvm::MLInlineAdvice::recordInliningWithCalleeDeletedImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#afab4dde8e888e2564c2108a9c149f12d">llvm::MLInlineAdvice::recordUnattemptedInliningImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#ac725e56738dcc1fc8de94a7554491456">llvm::MLInlineAdvice::recordUnsuccessfulInliningImpl</a>.</p>

</div>
</div>

### IsInliningRecommended {#adf54b36d4d196330fc5b63d0f0022e80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::InlineAdvice::IsInliningRecommended</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Referenced by <a href="#a8500015965ef1b86e39cd83fd2fc8dff">InlineAdvice</a> and <a href="#ad7abcbeaf6e8ebe6acac592b6cdaaad0">isInliningRecommended</a>.</p>

</div>
</div>

### ORE {#a52090ce3aedce0b4004ca443c193b110}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter&amp; llvm::InlineAdvice::ORE</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/defaultinlineadvice/#acd3ac174fece42a9120f8fe134adbffe">llvm::DefaultInlineAdvice::DefaultInlineAdvice</a>, <a href="#a8500015965ef1b86e39cd83fd2fc8dff">InlineAdvice</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlineadvisor-cpp-/mandatoryinlineadvice/#af681b273c456b33574537c3d01ef2bb5">anonymous{InlineAdvisor.cpp}::MandatoryInlineAdvice::MandatoryInlineAdvice</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#a413e5428e006570e79370b033a107dec">llvm::MLInlineAdvice::MLInlineAdvice</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#a79fede4389dbc2b630710e3c09787a20">llvm::MLInlineAdvice::recordInliningImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#af08e89bee7499bc47dbc39d981c5c436">llvm::MLInlineAdvice::recordInliningWithCalleeDeletedImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#afab4dde8e888e2564c2108a9c149f12d">llvm::MLInlineAdvice::recordUnattemptedInliningImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#ac725e56738dcc1fc8de94a7554491456">llvm::MLInlineAdvice::recordUnsuccessfulInliningImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Recorded {#a6bbc8cd029db1f8f934c88861fb21793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAdvice::Recorded = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp">InlineAdvisor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
