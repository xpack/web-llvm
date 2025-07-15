---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/cgsccanalysismanagermoduleproxy/result
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Result` Class Template Reference

<p>We need a specialized result for the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab279be449a12f8ba5f83dceba257d796">CGSCCAnalysisManagerModuleProxy</a></span> so it can have access to the call graph in order to walk all the SCCs when invalidating things. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CGSCCAnalysisManagerModuleProxy::Result { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">llvm/Analysis/CGSCCPassManager.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9ae8a63b0c58ad042b358276dd7cba6">Result</a> (CGSCCAnalysisManager &amp;InnerAM, LazyCallGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a571b2bbf074b46c75300bd8f14c5ab72">CGSCCAnalysisManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab27a26c6fc63e3a774a71a952d69ca3a">getManager</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accessor for the analysis manager. <a href="#ab27a26c6fc63e3a774a71a952d69ca3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e5728ec78bc4596393912985f0d2c57">invalidate</a> (Module &amp;M, const PreservedAnalyses &amp;PA, ModuleAnalysisManager::Invalidator &amp;Inv)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handler for invalidation of the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>. <a href="#a0e5728ec78bc4596393912985f0d2c57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a571b2bbf074b46c75300bd8f14c5ab72">CGSCCAnalysisManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a059de2cd262fec2cebe08e4f0de78ff1">InnerAM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08c90ef47888cc108382c3dc676a1af7">G</a></td>
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

<p>We need a specialized result for the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab279be449a12f8ba5f83dceba257d796">CGSCCAnalysisManagerModuleProxy</a></span> so it can have access to the call graph in order to walk all the SCCs when invalidating things.</p>

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">CGSCCPassManager.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Result() {#ad9ae8a63b0c58ad042b358276dd7cba6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CGSCCAnalysisManagerModuleProxy::Result::Result (<a href="/web-llvm/docs/api/namespaces/llvm/#a571b2bbf074b46c75300bd8f14c5ab72">CGSCCAnalysisManager</a> &amp; InnerAM, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> &amp; G)</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">CGSCCPassManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getManager() {#ab27a26c6fc63e3a774a71a952d69ca3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CGSCCAnalysisManager &amp; llvm::CGSCCAnalysisManagerModuleProxy::Result::getManager ()</td>
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

<p>Accessor for the analysis manager.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">CGSCCPassManager.h</a>.</p>

</div>
</div>

### invalidate() {#a0e5728ec78bc4596393912985f0d2c57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CGSCCAnalysisManagerModuleProxy::Result::invalidate (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a> &amp; PA, ModuleAnalysisManager::Invalidator &amp; Inv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handler for invalidation of the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>.</p>


<p>If the proxy analysis itself is preserved, then we assume that the set of SCCs in the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> hasn't changed. Thus any pointers to SCCs in the <a href="/web-llvm/docs/api/namespaces/llvm/#a571b2bbf074b46c75300bd8f14c5ab72">CGSCCAnalysisManager</a> are still valid, and we don't need to call <span class="doxyComputerOutput">clear</span> on the <a href="/web-llvm/docs/api/namespaces/llvm/#a571b2bbf074b46c75300bd8f14c5ab72">CGSCCAnalysisManager</a>.</p>


<p>Regardless of whether this analysis is marked as preserved, all of the analyses in the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a571b2bbf074b46c75300bd8f14c5ab72">CGSCCAnalysisManager</a></span> are potentially invalidated based on the set of preserved analyses.</p>


<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">CGSCCPassManager.h</a>, definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp">CGSCCPassManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses/#a2de5aab2964e0b9266423d5f6c375051">llvm::PreservedAnalyses::allAnalysesInSetPreserved</a>, <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses/#a0eb77e2d868c69bebc48c07b49675748">llvm::PreservedAnalyses::areAllPreserved</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses/#aa7a1b769f9c57010cc41d9c3bb9d39c6">llvm::PreservedAnalyses::getChecker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### G {#a08c90ef47888cc108382c3dc676a1af7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallGraph* llvm::CGSCCAnalysisManagerModuleProxy::Result::G</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">CGSCCPassManager.h</a>.</p>

</div>
</div>

### InnerAM {#a059de2cd262fec2cebe08e4f0de78ff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CGSCCAnalysisManager* llvm::CGSCCAnalysisManagerModuleProxy::Result::InnerAM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">CGSCCPassManager.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">CGSCCPassManager.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp">CGSCCPassManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
