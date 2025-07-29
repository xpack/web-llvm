---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/defaultinlineadvice
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DefaultInlineAdvice` Class



## Declaration

<div class="doxyDeclaration">
class llvm::DefaultInlineAdvice { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">llvm/Analysis/InlineAdvisor.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd3ac174fece42a9120f8fe134adbffe">DefaultInlineAdvice</a> (InlineAdvisor *Advisor, CallBase &amp;CB, std::optional&lt; InlineCost &gt; OIC, OptimizationRemarkEmitter &amp;ORE, bool EmitRemarks=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68697d569ecdcb451fab0ef7189bf2b6">recordUnsuccessfulInliningImpl</a> (const InlineResult &amp;Result) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1875811a0680a47f6f51284d3e80d0cf">recordInliningWithCalleeDeletedImpl</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a477d278fe5f25f3cbf36e3601e1124a8">recordInliningImpl</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69513731b0b93db35d236b119e9b225c">OriginalCB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/inlinecost">InlineCost</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92cbdae954d7114f7ab25fcd7882c7f5">OIC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04e02de5bda6d136f03cc70931e96661">EmitRemarks</a></td>
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


<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DefaultInlineAdvice() {#acd3ac174fece42a9120f8fe134adbffe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DefaultInlineAdvice::DefaultInlineAdvice (<a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a> * Advisor, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/inlinecost">InlineCost</a> &gt; OIC, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE, bool EmitRemarks=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a840ff172791c81e7277a6fcf89c91dbe">llvm::InlineAdvice::Advisor</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a8500015965ef1b86e39cd83fd2fc8dff">llvm::InlineAdvice::InlineAdvice</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a52090ce3aedce0b4004ca443c193b110">llvm::InlineAdvice::ORE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### recordInliningImpl() {#a477d278fe5f25f3cbf36e3601e1124a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefaultInlineAdvice::recordInliningImpl ()</td>
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



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>, definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp">InlineAdvisor.cpp</a>.</p>

</div>
</div>

### recordInliningWithCalleeDeletedImpl() {#a1875811a0680a47f6f51284d3e80d0cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefaultInlineAdvice::recordInliningWithCalleeDeletedImpl ()</td>
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



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp">InlineAdvisor.cpp</a>.</p>

</div>
</div>

### recordUnsuccessfulInliningImpl() {#a68697d569ecdcb451fab0ef7189bf2b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefaultInlineAdvice::recordUnsuccessfulInliningImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/inlineresult">InlineResult</a> &amp; Result)</td>
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



<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp">InlineAdvisor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EmitRemarks {#a04e02de5bda6d136f03cc70931e96661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DefaultInlineAdvice::EmitRemarks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>

</div>
</div>

### OIC {#a92cbdae954d7114f7ab25fcd7882c7f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;InlineCost&gt; llvm::DefaultInlineAdvice::OIC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>

</div>
</div>

### OriginalCB {#a69513731b0b93db35d236b119e9b225c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallBase* const llvm::DefaultInlineAdvice::OriginalCB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>

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
