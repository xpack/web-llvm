---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/defaultinlineadvisor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DefaultInlineAdvisor` Class Reference

<p>The default (manual heuristics) implementation of the <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DefaultInlineAdvisor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">llvm/Analysis/InlineAdvisor.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface for deciding whether to inline a call site or not. <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b40df01d9cb958784cdfee64bfce7f6">DefaultInlineAdvisor</a> (Module &amp;M, FunctionAnalysisManager &amp;FAM, InlineParams Params, InlineContext IC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/inlineadvice">InlineAdvice</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41b7b1ac5ba13cf374a317a45e062718">getAdviceImpl</a> (CallBase &amp;CB) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/inlineparams">InlineParams</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a670c52d68ce839e511e2afc166ea42de">Params</a></td>
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

<p>The default (manual heuristics) implementation of the <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a>.</p>


<p>This implementation does not need to keep state between inliner pass runs, and is reusable as-is for inliner pass test scenarios, as well as for regular use.</p>


<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DefaultInlineAdvisor() {#a5b40df01d9cb958784cdfee64bfce7f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DefaultInlineAdvisor::DefaultInlineAdvisor (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; FAM, <a href="/web-llvm/docs/api/structs/llvm/inlineparams">InlineParams</a> Params, <a href="/web-llvm/docs/api/structs/llvm/inlinecontext">InlineContext</a> IC)</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#a1b1b99bc0fe39cbe400f49bbd65f01c3">llvm::InlineAdvisor::FAM</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#a0253ac1349dcc28b1ff91eaa4230d173">llvm::InlineAdvisor::IC</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#aec021d6b460b139f3c1d570a0f2dd4b6">llvm::InlineAdvisor::InlineAdvisor</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#ab63e90899ab78f60bf47256071c0a48b">llvm::InlineAdvisor::M</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getAdviceImpl() {#a41b7b1ac5ba13cf374a317a45e062718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; InlineAdvice &gt; DefaultInlineAdvisor::getAdviceImpl (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
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



<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>, definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp">InlineAdvisor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Params {#a670c52d68ce839e511e2afc166ea42de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineParams llvm::DefaultInlineAdvisor::Params</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>

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
