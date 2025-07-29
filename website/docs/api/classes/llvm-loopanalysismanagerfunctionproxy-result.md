---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loopanalysismanagerfunctionproxy/result
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Result` Class Template

<p>A specialized result for the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a43d65ba07f09dd4c0c13d551848cdc88">LoopAnalysisManagerFunctionProxy</a></span> which retains a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a></span> reference. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LoopAnalysisManagerFunctionProxy::Result { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">llvm/Analysis/LoopAnalysisManager.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb4b1468c8e2219caee1d322dd73db47">Result</a> (LoopAnalysisManager &amp;InnerAM, LoopInfo &amp;LI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8acf40c14512eb61a1b48da1876ce9b">Result</a> (Result &amp;&amp;Arg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a047a9fa29538876a3d48f7c97980e8ac">~Result</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopanalysismanagerfunctionproxy/result">Result</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a970c1a12958995d2abc1d31f39f8e232">operator=</a> (Result &amp;&amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5dd4078b26f26598fae0fe0c9b893c4">markMSSAUsed</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> as used so we can invalidate self if MSSA is invalidated. <a href="#ac5dd4078b26f26598fae0fe0c9b893c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a58dde534a0ea2a23cb6c779c5c283f75">LoopAnalysisManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47feb8711d612c46a16284bf8f284edc">getManager</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accessor for the analysis manager. <a href="#a47feb8711d612c46a16284bf8f284edc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75c73b4e1766a4a21df494320f1e8cde">invalidate</a> (Function &amp;F, const PreservedAnalyses &amp;PA, FunctionAnalysisManager::Invalidator &amp;Inv)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handler for invalidation of the proxy for a particular function. <a href="#a75c73b4e1766a4a21df494320f1e8cde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a58dde534a0ea2a23cb6c779c5c283f75">LoopAnalysisManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a571fff81de99f5a7d7729aab6441a6b9">InnerAM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fcd6b2d59e10647f6dada5941624b0f">LI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c71d278bc7fddd054410484419f27f2">MSSAUsed</a> = false</td>
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

<p>A specialized result for the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a43d65ba07f09dd4c0c13d551848cdc88">LoopAnalysisManagerFunctionProxy</a></span> which retains a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a></span> reference.</p>


<p>This allows it to collect loop objects for which analysis results may be cached in the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a58dde534a0ea2a23cb6c779c5c283f75">LoopAnalysisManager</a></span>.</p>


<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Result() {#adb4b1468c8e2219caee1d322dd73db47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoopAnalysisManagerFunctionProxy::Result::Result (<a href="/web-llvm/docs/api/namespaces/llvm/#a58dde534a0ea2a23cb6c779c5c283f75">LoopAnalysisManager</a> &amp; InnerAM, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>


<p>Referenced by <a href="#a970c1a12958995d2abc1d31f39f8e232">operator=</a> and <a href="#aa8acf40c14512eb61a1b48da1876ce9b">Result</a>.</p>

</div>
</div>

### Result() {#aa8acf40c14512eb61a1b48da1876ce9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoopAnalysisManagerFunctionProxy::Result::Result (<a href="/web-llvm/docs/api/classes/llvm/loopanalysismanagerfunctionproxy/result">Result</a> &amp;&amp; Arg)</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#adb4b1468c8e2219caee1d322dd73db47">Result</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Result() {#a047a9fa29538876a3d48f7c97980e8ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoopAnalysisManagerFunctionProxy::Result::~Result ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a970c1a12958995d2abc1d31f39f8e232}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Result &amp; llvm::LoopAnalysisManagerFunctionProxy::Result::operator= (<a href="/web-llvm/docs/api/classes/llvm/loopanalysismanagerfunctionproxy/result">Result</a> &amp;&amp; RHS)</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>


<p>References <a href="#adb4b1468c8e2219caee1d322dd73db47">Result</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getManager() {#a47feb8711d612c46a16284bf8f284edc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopAnalysisManager &amp; llvm::LoopAnalysisManagerFunctionProxy::Result::getManager ()</td>
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

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>

</div>
</div>

### invalidate() {#a75c73b4e1766a4a21df494320f1e8cde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopAnalysisManagerFunctionProxy::Result::invalidate (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp; PA, FunctionAnalysisManager::Invalidator &amp; Inv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handler for invalidation of the proxy for a particular function.</p>


<p>If the proxy, <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a></span>, and associated analyses are preserved, this will merely forward the invalidation event to any cached loop analysis results for loops within this function.</p>


<p>If the necessary loop infrastructure is not preserved, this will forcibly clear all of the cached analysis results that are keyed on the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a></span> for this function.</p>


<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### markMSSAUsed() {#ac5dd4078b26f26598fae0fe0c9b893c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopAnalysisManagerFunctionProxy::Result::markMSSAUsed ()</td>
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

<p>Mark <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> as used so we can invalidate self if MSSA is invalidated.</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### InnerAM {#a571fff81de99f5a7d7729aab6441a6b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopAnalysisManager* llvm::LoopAnalysisManagerFunctionProxy::Result::InnerAM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>

</div>
</div>

### LI {#a4fcd6b2d59e10647f6dada5941624b0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* llvm::LoopAnalysisManagerFunctionProxy::Result::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>

</div>
</div>

### MSSAUsed {#a8c71d278bc7fddd054410484419f27f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopAnalysisManagerFunctionProxy::Result::MSSAUsed = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h">LoopAnalysisManager.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
