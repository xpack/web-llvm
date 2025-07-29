---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/inlineadvisoranalysisprinterpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InlineAdvisorAnalysisPrinterPass` Class

<p>Printer pass for the <a href="/web-llvm/docs/api/classes/llvm/inlineadvisoranalysis">InlineAdvisorAnalysis</a> results. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::InlineAdvisorAnalysisPrinterPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">llvm/Analysis/InlineAdvisor.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/passinfomixin">PassInfoMixin&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP mix-in to automatically provide informational APIs needed for passes. <a href="/web-llvm/docs/api/structs/llvm/passinfomixin/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcb710e3f9364194a402caaef0a18f98">InlineAdvisorAnalysisPrinterPass</a> (raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">PreservedAnalyses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6fd30da8bd8c6528e6bc9aa4c2f6633">run</a> (Module &amp;M, ModuleAnalysisManager &amp;MAM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">PreservedAnalyses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0f697cf524e464ace6a8652e4dbb128">run</a> (LazyCallGraph::SCC &amp;InitialC, CGSCCAnalysisManager &amp;AM, LazyCallGraph &amp;CG, CGSCCUpdateResult &amp;UR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9cfc86b35c84a0b82dd1b367dd70f2e">OS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a513467fe589a338326f26ec9f9545f39">isRequired</a> ()</td>
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

<p>Printer pass for the <a href="/web-llvm/docs/api/classes/llvm/inlineadvisoranalysis">InlineAdvisorAnalysis</a> results.</p>

<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InlineAdvisorAnalysisPrinterPass() {#adcb710e3f9364194a402caaef0a18f98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InlineAdvisorAnalysisPrinterPass::InlineAdvisorAnalysisPrinterPass (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#ab6fd30da8bd8c6528e6bc9aa4c2f6633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses InlineAdvisorAnalysisPrinterPass::run (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp; MAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>, definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp">InlineAdvisor.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a85bddafa659a93a7a67c9094648259be">MAM</a>.</p>

</div>
</div>

### run() {#af0f697cf524e464ace6a8652e4dbb128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses InlineAdvisorAnalysisPrinterPass::run (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">LazyCallGraph::SCC</a> &amp; InitialC, <a href="/web-llvm/docs/api/namespaces/llvm/#a571b2bbf074b46c75300bd8f14c5ab72">CGSCCAnalysisManager</a> &amp; AM, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> &amp; CG, <a href="/web-llvm/docs/api/structs/llvm/cgsccupdateresult">CGSCCUpdateResult</a> &amp; UR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>, definition at line 639 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp">InlineAdvisor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc/#abb7ae9233d82816a8d4f2f72490c4ac0">llvm::LazyCallGraph::SCC::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#aaab1fad63e4f3b8679469720a873fedd">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getResult</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc/#a5592b0404f95c589801ea255fa95fb63">llvm::LazyCallGraph::SCC::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### OS {#aa9cfc86b35c84a0b82dd1b367dd70f2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream&amp; llvm::InlineAdvisorAnalysisPrinterPass::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isRequired() {#a513467fe589a338326f26ec9f9545f39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAdvisorAnalysisPrinterPass::isRequired ()</td>
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



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">InlineAdvisor.h</a>.</p>

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
