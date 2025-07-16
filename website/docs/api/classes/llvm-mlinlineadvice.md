---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mlinlineadvice
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MLInlineAdvice` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/inlineadvice">InlineAdvice</a> that tracks changes post inlining. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MLInlineAdvice { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">llvm/Analysis/MLInlineAdvisor.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineadvice">InlineAdvice</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Capture state between an inlining decision having had been made, and its impact being observable. <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a413e5428e006570e79370b033a107dec">MLInlineAdvice</a> (MLInlineAdvisor *Advisor, CallBase &amp;CB, OptimizationRemarkEmitter &amp;ORE, bool Recommendation)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26dbfcb9de97830005174278c9656f2b">~MLInlineAdvice</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79fede4389dbc2b630710e3c09787a20">recordInliningImpl</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af08e89bee7499bc47dbc39d981c5c436">recordInliningWithCalleeDeletedImpl</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac725e56738dcc1fc8de94a7554491456">recordUnsuccessfulInliningImpl</a> (const InlineResult &amp;Result) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afab4dde8e888e2564c2108a9c149f12d">recordUnattemptedInliningImpl</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7a31fef6e390f4ddf21f9f63a94f70f">getCaller</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada4b28b495ff3ca02d3373edf2b5bac6">getCallee</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19a31f34d91bfcdfa8c16f9a16079461">updateCachedCallerFPI</a> (FunctionAnalysisManager &amp;FAM) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16a00477fa9425c7332bc38a8aae7f86">reportContextForRemark</a> (DiagnosticInfoOptimizationBase &amp;OR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor">MLInlineAdvisor</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c67fd46fb6f506a914ccd4f455f9772">getAdvisor</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a367c676bd322e75aad02114a0763d955">CallerIRSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6330d9efb13139a5058e3ee2d240c81d">CalleeIRSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2fa94d7c9401db9a42cee3a9e7a4416">CallerAndCalleeEdges</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesinfo">FunctionPropertiesInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21ff04bbba8f30e1e4743b802048c56d">PreInlineCallerFPI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesupdater">FunctionPropertiesUpdater</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98dd37b68d03c8a8eca89397b4d73445">FPU</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/inlineadvice">InlineAdvice</a> that tracks changes post inlining.</p>


<p>For that reason, it only overrides the "successful inlining" extension points.</p>


<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MLInlineAdvice() {#a413e5428e006570e79370b033a107dec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MLInlineAdvice::MLInlineAdvice (<a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor">MLInlineAdvisor</a> * Advisor, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE, bool Recommendation)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a840ff172791c81e7277a6fcf89c91dbe">llvm::InlineAdvice::Advisor</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a00ec8d01596f9885f6303a98fbc8197b">llvm::InlineAdvice::Callee</a>, <a href="#a6330d9efb13139a5058e3ee2d240c81d">CalleeIRSize</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a078183205dd7f49738ba34f1586e9620">llvm::InlineAdvice::Caller</a>, <a href="#ac2fa94d7c9401db9a42cee3a9e7a4416">CallerAndCalleeEdges</a>, <a href="#a367c676bd322e75aad02114a0763d955">CallerIRSize</a>, <a href="#ab7a31fef6e390f4ddf21f9f63a94f70f">getCaller</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a8500015965ef1b86e39cd83fd2fc8dff">llvm::InlineAdvice::InlineAdvice</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a52090ce3aedce0b4004ca443c193b110">llvm::InlineAdvice::ORE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MLInlineAdvice() {#a26dbfcb9de97830005174278c9656f2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::MLInlineAdvice::~MLInlineAdvice ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCallee() {#ada4b28b495ff3ca02d3373edf2b5bac6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::MLInlineAdvice::getCallee ()</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a00ec8d01596f9885f6303a98fbc8197b">llvm::InlineAdvice::Callee</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#a8116ffdfb54f7d195eb185c8bf7c060c">llvm::MLInlineAdvisor::onSuccessfulInlining</a>.</p>

</div>
</div>

### getCaller() {#ab7a31fef6e390f4ddf21f9f63a94f70f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::MLInlineAdvice::getCaller ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a078183205dd7f49738ba34f1586e9620">llvm::InlineAdvice::Caller</a>.</p>


<p>Referenced by <a href="#a413e5428e006570e79370b033a107dec">MLInlineAdvice</a> and <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#a8116ffdfb54f7d195eb185c8bf7c060c">llvm::MLInlineAdvisor::onSuccessfulInlining</a>.</p>

</div>
</div>

### recordInliningImpl() {#a79fede4389dbc2b630710e3c09787a20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MLInlineAdvice::recordInliningImpl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a314b23a57d33b1ca800c2a273b7116ff">llvm::InlineAdvice::Block</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#aadc3866d7b0ecd242180fb85d3b0e748">llvm::InlineAdvice::DLoc</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a52090ce3aedce0b4004ca443c193b110">llvm::InlineAdvice::ORE</a>.</p>

</div>
</div>

### recordInliningWithCalleeDeletedImpl() {#af08e89bee7499bc47dbc39d981c5c436}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MLInlineAdvice::recordInliningWithCalleeDeletedImpl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a314b23a57d33b1ca800c2a273b7116ff">llvm::InlineAdvice::Block</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#aadc3866d7b0ecd242180fb85d3b0e748">llvm::InlineAdvice::DLoc</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a52090ce3aedce0b4004ca443c193b110">llvm::InlineAdvice::ORE</a>.</p>

</div>
</div>

### recordUnattemptedInliningImpl() {#afab4dde8e888e2564c2108a9c149f12d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MLInlineAdvice::recordUnattemptedInliningImpl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 563 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a314b23a57d33b1ca800c2a273b7116ff">llvm::InlineAdvice::Block</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#aadc3866d7b0ecd242180fb85d3b0e748">llvm::InlineAdvice::DLoc</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a52090ce3aedce0b4004ca443c193b110">llvm::InlineAdvice::ORE</a>.</p>

</div>
</div>

### recordUnsuccessfulInliningImpl() {#ac725e56738dcc1fc8de94a7554491456}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MLInlineAdvice::recordUnsuccessfulInliningImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inlineresult">InlineResult</a> &amp; Result)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a314b23a57d33b1ca800c2a273b7116ff">llvm::InlineAdvice::Block</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a078183205dd7f49738ba34f1586e9620">llvm::InlineAdvice::Caller</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#aadc3866d7b0ecd242180fb85d3b0e748">llvm::InlineAdvice::DLoc</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a52090ce3aedce0b4004ca443c193b110">llvm::InlineAdvice::ORE</a>.</p>

</div>
</div>

### updateCachedCallerFPI() {#a19a31f34d91bfcdfa8c16f9a16079461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MLInlineAdvice::updateCachedCallerFPI (<a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; FAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#a8116ffdfb54f7d195eb185c8bf7c060c">llvm::MLInlineAdvisor::onSuccessfulInlining</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getAdvisor() {#a7c67fd46fb6f506a914ccd4f455f9772}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MLInlineAdvisor * llvm::MLInlineAdvice::getAdvisor ()</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>

</div>
</div>

### reportContextForRemark() {#a16a00477fa9425c7332bc38a8aae7f86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MLInlineAdvice::reportContextForRemark (<a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase">DiagnosticInfoOptimizationBase</a> &amp; OR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>, definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CalleeIRSize {#a6330d9efb13139a5058e3ee2d240c81d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int64_t llvm::MLInlineAdvice::CalleeIRSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>


<p>Referenced by <a href="#a413e5428e006570e79370b033a107dec">MLInlineAdvice</a> and <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#a8116ffdfb54f7d195eb185c8bf7c060c">llvm::MLInlineAdvisor::onSuccessfulInlining</a>.</p>

</div>
</div>

### CallerAndCalleeEdges {#ac2fa94d7c9401db9a42cee3a9e7a4416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int64_t llvm::MLInlineAdvice::CallerAndCalleeEdges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>


<p>Referenced by <a href="#a413e5428e006570e79370b033a107dec">MLInlineAdvice</a> and <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#a8116ffdfb54f7d195eb185c8bf7c060c">llvm::MLInlineAdvisor::onSuccessfulInlining</a>.</p>

</div>
</div>

### CallerIRSize {#a367c676bd322e75aad02114a0763d955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int64_t llvm::MLInlineAdvice::CallerIRSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>


<p>Referenced by <a href="#a413e5428e006570e79370b033a107dec">MLInlineAdvice</a> and <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#a8116ffdfb54f7d195eb185c8bf7c060c">llvm::MLInlineAdvisor::onSuccessfulInlining</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FPU {#a98dd37b68d03c8a8eca89397b4d73445}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;FunctionPropertiesUpdater&gt; llvm::MLInlineAdvice::FPU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>

</div>
</div>

### PreInlineCallerFPI {#a21ff04bbba8f30e1e4743b802048c56d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FunctionPropertiesInfo llvm::MLInlineAdvice::PreInlineCallerFPI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlinlineadvisor-h">MLInlineAdvisor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/mlinlineadvisor-cpp">MLInlineAdvisor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
