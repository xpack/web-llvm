---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dotgraphtraitsprinterwrapperpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DOTGraphTraitsPrinterWrapperPass` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename AnalysisT, bool IsSimple, typename GraphT = AnalysisT *, typename AnalysisGraphTraitsT = LegacyDefaultAnalysisGraphTraits&lt;AnalysisT, GraphT&gt;&gt;
class llvm::DOTGraphTraitsPrinterWrapperPass&lt;AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">llvm/Analysis/DOTGraphTraitsPass.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> class - This class is used to implement most global optimizations. <a href="/web-llvm/docs/api/classes/llvm/functionpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ab1446cbb4503af5fed6bd88cf58cc4f6">DOTGraphTraitsPrinterWrapperPass</a> (StringRef GraphName, char &amp;ID)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abd6ce36a525dd5022e194577db9ad826">processFunction</a> (Function &amp;F, AnalysisT &amp;Analysis)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this function should be processed. <a href="#abd6ce36a525dd5022e194577db9ad826">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a13f01c501d30959accca2ddeec59fe10">runOnFunction</a> (Function &amp;F) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnFunction - Virtual method overriden by subclasses to do the per-function processing of the pass. <a href="#a13f01c501d30959accca2ddeec59fe10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa02c07be447c35d11d0e51b8227abf39">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#aa02c07be447c35d11d0e51b8227abf39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abd62dc7206246c6d38eea636a0097425">Name</a></td>
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


<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">DOTGraphTraitsPass.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DOTGraphTraitsPrinterWrapperPass() {#ab1446cbb4503af5fed6bd88cf58cc4f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisT, bool IsSimple, typename GraphT = AnalysisT *, typename AnalysisGraphTraitsT = LegacyDefaultAnalysisGraphTraits&lt;AnalysisT, GraphT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DOTGraphTraitsPrinterWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::DOTGraphTraitsPrinterWrapperPass (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> GraphName, char &amp; ID)</td>
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



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">DOTGraphTraitsPass.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/functionpass/#a7691d83e3561f781cae4ce4a01bdfa93">llvm::FunctionPass::FunctionPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#aa02c07be447c35d11d0e51b8227abf39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisT, bool IsSimple, typename GraphT = AnalysisT *, typename AnalysisGraphTraitsT = LegacyDefaultAnalysisGraphTraits&lt;AnalysisT, GraphT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DOTGraphTraitsPrinterWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">DOTGraphTraitsPass.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af22b06a6a4f9df80454071685a0d6a02">llvm::AnalysisUsage::setPreservesAll</a>.</p>

</div>
</div>

### processFunction() {#abd6ce36a525dd5022e194577db9ad826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisT, bool IsSimple, typename GraphT = AnalysisT *, typename AnalysisGraphTraitsT = LegacyDefaultAnalysisGraphTraits&lt;AnalysisT, GraphT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::DOTGraphTraitsPrinterWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::processFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, AnalysisT &amp; Analysis)</td>
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

<p>Return true if this function should be processed.</p>


<p>An implementation of this class my override this function to indicate that only certain functions should be printed.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Analysis</td>
<td class="doxyParamItemDescription"><p>The current analysis result for this function.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">DOTGraphTraitsPass.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a13f01c501d30959accca2ddeec59fe10">llvm::DOTGraphTraitsPrinterWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::runOnFunction</a>.</p>

</div>
</div>

### runOnFunction() {#a13f01c501d30959accca2ddeec59fe10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisT, bool IsSimple, typename GraphT = AnalysisT *, typename AnalysisGraphTraitsT = LegacyDefaultAnalysisGraphTraits&lt;AnalysisT, GraphT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DOTGraphTraitsPrinterWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>runOnFunction - Virtual method overriden by subclasses to do the per-function processing of the pass.</p>

<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">DOTGraphTraitsPass.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9dcf1b0fa5c6aaf08fa0700990ac067a">llvm::printGraphForFunction</a> and <a href="#abd6ce36a525dd5022e194577db9ad826">llvm::DOTGraphTraitsPrinterWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::processFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Name {#abd62dc7206246c6d38eea636a0097425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisT, bool IsSimple, typename GraphT = AnalysisT *, typename AnalysisGraphTraitsT = LegacyDefaultAnalysisGraphTraits&lt;AnalysisT, GraphT&gt;&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraitsPrinterWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">DOTGraphTraitsPass.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/dotgraphtraitspass-h">DOTGraphTraitsPass.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
