---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/preservedanalyses
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PreservedAnalyses` Class Reference

<p>A set of analyses that are preserved following a run of a transformation pass. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PreservedAnalyses { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">llvm/IR/Analysis.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AnalysisT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad966bea18aa62ffb9e040509adc7c99f">preserve</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark an analysis as preserved. <a href="#ad966bea18aa62ffb9e040509adc7c99f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac138874dedaeb0b8cdcf6c381bc2103b">preserve</a> (AnalysisKey *ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an analysis's <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, mark the analysis as preserved, adding it to the set. <a href="#ac138874dedaeb0b8cdcf6c381bc2103b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AnalysisSetT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a937c42f77e161349ce0f999e448c7027">preserveSet</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark an analysis set as preserved. <a href="#a937c42f77e161349ce0f999e448c7027">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05f35e3a28f0760667448247878c1b80">preserveSet</a> (AnalysisSetKey *ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark an analysis set as preserved using its <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#a05f35e3a28f0760667448247878c1b80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AnalysisT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac8a842a601c470fa22db443ac34d0a67">abandon</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark an analysis as abandoned. <a href="#ac8a842a601c470fa22db443ac34d0a67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73a88c83a622e7dba81e049710d8bab7">abandon</a> (AnalysisKey *ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark an analysis as abandoned using its <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#a73a88c83a622e7dba81e049710d8bab7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f5dc18d0b2c71cba501f12975188e40">intersect</a> (const PreservedAnalyses &amp;Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Intersect this set with another in place. <a href="#a5f5dc18d0b2c71cba501f12975188e40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72f56d9cb73db3c1ea0eee8fba48b64c">intersect</a> (PreservedAnalyses &amp;&amp;Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Intersect this set with a temporary other set in place. <a href="#a72f56d9cb73db3c1ea0eee8fba48b64c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AnalysisT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/preservedanalyses/preservedanalysischecker">PreservedAnalysisChecker</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa7a1b769f9c57010cc41d9c3bb9d39c6">getChecker</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a checker for this <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a></span> and the specified analysis type. <a href="#aa7a1b769f9c57010cc41d9c3bb9d39c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/preservedanalyses/preservedanalysischecker">PreservedAnalysisChecker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a452552a70b5998a3a831fb2560498927">getChecker</a> (AnalysisKey *ID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a checker for this <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a></span> and the specified analysis <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#a452552a70b5998a3a831fb2560498927">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eb77e2d868c69bebc48c07b49675748">areAllPreserved</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether all analyses are preserved (and none are abandoned). <a href="#a0eb77e2d868c69bebc48c07b49675748">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AnalysisSetT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2de5aab2964e0b9266423d5f6c375051">allAnalysesInSetPreserved</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Directly test whether a set of analyses is preserved. <a href="#a2de5aab2964e0b9266423d5f6c375051">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7810efbb63c59ebac46c15ac6008a7f7">allAnalysesInSetPreserved</a> (AnalysisSetKey *SetID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Directly test whether a set of analyses is preserved. <a href="#a7810efbb63c59ebac46c15ac6008a7f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; void *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8b1077ed88229e6b2a24bbea9292807">PreservedIDs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The IDs of analyses and analysis sets that are preserved. <a href="#ae8b1077ed88229e6b2a24bbea9292807">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a> *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37b20de6fd9783d24921c263d127a291">NotPreservedAnalysisIDs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The IDs of explicitly not-preserved analyses. <a href="#a37b20de6fd9783d24921c263d127a291">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03797a73044a81cbc6a3409d6c72ee8f">none</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience factory function for the empty preserved set. <a href="#a03797a73044a81cbc6a3409d6c72ee8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1258a1ff55557c27684010ebd7283712">all</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a special preserved set that preserves all passes. <a href="#a1258a1ff55557c27684010ebd7283712">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AnalysisSetT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aea87afbe4520fdc60652c554501f5cdf">allInSet</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a preserved analyses object with a single preserved set. <a href="#aea87afbe4520fdc60652c554501f5cdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/analysissetkey">AnalysisSetKey</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adff624f8bb356741634ae566379c463f">AllAnalysesKey</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A special key used to indicate all analyses. <a href="#adff624f8bb356741634ae566379c463f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A set of analyses that are preserved following a run of a transformation pass.</p>


<p>Transformation passes build and return these objects to communicate which analyses are still valid after the transformation. For most passes this is fairly simple: if they don't change anything all analyses are preserved, otherwise only a short list of analyses that have been explicitly updated are preserved.</p>


<p>This class also lets transformation passes mark abstract <em>sets</em> of analyses as preserved. A transformation that (say) does not alter the CFG can indicate such by marking a particular <a href="/web-llvm/docs/api/structs/llvm/analysissetkey">AnalysisSetKey</a> as preserved, and then analyses can query whether that <a href="/web-llvm/docs/api/structs/llvm/analysissetkey">AnalysisSetKey</a> is preserved.</p>


<p>Finally, this class can represent an "abandoned" analysis, which is not preserved even if it would be covered by some abstract set of analyses.</p>


<p>Given a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a></span> object, an analysis will typically want to figure out whether it is preserved. In the example below, MyAnalysisType is preserved if it's not abandoned, and (a) it's explicitly marked as preserved, (b), the set <a href="/web-llvm/docs/api/classes/llvm/allanalyseson">AllAnalysesOn&lt;MyIRUnit&gt;</a> is preserved, or (c) both AnalysisSetA and AnalysisSetB are preserved.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> PAC = PA.getChecker&lt;MyAnalysisType&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (PAC.preserved() || PAC.preservedSet&lt;AllAnalysesOn&lt;MyIRUnit&gt;&gt;() ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    (PAC.preservedSet&lt;AnalysisSetA&gt;() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">     PAC.preservedSet&lt;AnalysisSetB&gt;())) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// The analysis has been successfully preserved ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### abandon() {#ac8a842a601c470fa22db443ac34d0a67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PreservedAnalyses::abandon ()</td>
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

<p>Mark an analysis as abandoned.</p>


<p>An abandoned analysis is not preserved, even if it is nominally covered by some other set or was previously explicitly marked as preserved.</p>


<p>Note that you can only abandon a specific analysis, not a <em>set</em> of analyses.</p>


<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>


<p>Reference <a href="#ac8a842a601c470fa22db443ac34d0a67">abandon</a>.</p>


<p>Referenced by <a href="#ac8a842a601c470fa22db443ac34d0a67">abandon</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#a8116ffdfb54f7d195eb185c8bf7c060c">llvm::MLInlineAdvisor::onSuccessfulInlining</a>, <a href="/web-llvm/docs/api/classes/llvm/addresssanitizerpass/#a987afb1c68c5891e0b9a67cdac48147d">llvm::AddressSanitizerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/correlatedvaluepropagationpass/#a1672fc6d49348158aa95dbb4ae80224c">llvm::CorrelatedValuePropagationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dataflowsanitizerpass/#a763709e61e42f6df707528b509adf8de">llvm::DataFlowSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/hwaddresssanitizerpass/#a0ab6bbfe1dc498f2c9a8603d672fbb1b">llvm::HWAddressSanitizerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/invalidateanalysispass/#a935620d91529983e8e139ceb8532b5cb">llvm::InvalidateAnalysisPass&lt; AnalysisT &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ircepass/#ac7e45d3f509c7e40c4d6666a24e88f73">llvm::IRCEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loweremutlspass/#aa02b6a6722504e6fb7a176a81fc5d49c">llvm::LowerEmuTLSPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/memorysanitizerpass/#adfd94cfcef9d896734905bd5a18a05df">llvm::MemorySanitizerPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/sanitizercoveragepass/#a93d554aebdab8ad87f41ba8e07f73cad">llvm::SanitizerCoveragePass::run</a>.</p>

</div>
</div>

### abandon() {#a73a88c83a622e7dba81e049710d8bab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PreservedAnalyses::abandon (<a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a> * ID)</td>
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

<p>Mark an analysis as abandoned using its <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>


<p>An abandoned analysis is not preserved, even if it is nominally covered by some other set or was previously explicitly marked as preserved.</p>


<p>Note that you can only abandon a specific analysis, not a <em>set</em> of analyses.</p>


<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>

</div>
</div>

### allAnalysesInSetPreserved() {#a2de5aab2964e0b9266423d5f6c375051}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisSetT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PreservedAnalyses::allAnalysesInSetPreserved ()</td>
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

<p>Directly test whether a set of analyses is preserved.</p>


<p>This is only true when no analyses have been explicitly abandoned.</p>


<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>


<p>Reference <a href="#a2de5aab2964e0b9266423d5f6c375051">allAnalysesInSetPreserved</a>.</p>


<p>Referenced by <a href="#a2de5aab2964e0b9266423d5f6c375051">allAnalysesInSetPreserved</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#a64b2a209a16bcd41375b5cae12690eaa">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/cgsccanalysismanagermoduleproxy/result/#a0e5728ec78bc4596393912985f0d2c57">llvm::CGSCCAnalysisManagerModuleProxy::Result::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/functionanalysismanagercgsccproxy/result/#a1d080c4ca8dd19e09237ac942b78acc7">llvm::FunctionAnalysisManagerCGSCCProxy::Result::invalidate</a> and <a href="/web-llvm/docs/api/structs/llvm/memoryssaanalysis/result/#aa7ef622a6a2b5d83ccd6b06a42f0ba48">llvm::MemorySSAAnalysis::Result::invalidate</a>.</p>

</div>
</div>

### allAnalysesInSetPreserved() {#a7810efbb63c59ebac46c15ac6008a7f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PreservedAnalyses::allAnalysesInSetPreserved (<a href="/web-llvm/docs/api/structs/llvm/analysissetkey">AnalysisSetKey</a> * SetID)</td>
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

<p>Directly test whether a set of analyses is preserved.</p>


<p>This is only true when no analyses have been explicitly abandoned.</p>


<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>

</div>
</div>

### areAllPreserved() {#a0eb77e2d868c69bebc48c07b49675748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PreservedAnalyses::areAllPreserved ()</td>
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

<p>Test whether all analyses are preserved (and none are abandoned).</p>


<p>This is used primarily to optimize for the common case of a transformation which makes no changes to the IR.</p>


<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>


<p>Referenced by <a href="#a5f5dc18d0b2c71cba501f12975188e40">intersect</a>, <a href="#a72f56d9cb73db3c1ea0eee8fba48b64c">intersect</a>, <a href="/web-llvm/docs/api/classes/llvm/cgsccanalysismanagermoduleproxy/result/#a0e5728ec78bc4596393912985f0d2c57">llvm::CGSCCAnalysisManagerModuleProxy::Result::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/functionanalysismanagercgsccproxy/result/#a1d080c4ca8dd19e09237ac942b78acc7">llvm::FunctionAnalysisManagerCGSCCProxy::Result::invalidate</a>, <a href="#ac138874dedaeb0b8cdcf6c381bc2103b">preserve</a>, <a href="#a05f35e3a28f0760667448247878c1b80">preserveSet</a> and <a href="/web-llvm/docs/api/classes/anonymous-deadargumentelimination-cpp-/dae/#aad73a45cb4228e4fdff6c69e56d4d1a6">anonymous{DeadArgumentElimination.cpp}::DAE::runOnModule</a>.</p>

</div>
</div>

### getChecker() {#aa7a1b769f9c57010cc41d9c3bb9d39c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalysisChecker llvm::PreservedAnalyses::getChecker ()</td>
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

<p>Build a checker for this <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a></span> and the specified analysis type.</p>


<p>You can use the returned object to query whether an analysis was preserved. See the example in the comment on <span class="doxyComputerOutput">PreservedAnalysis</span>.</p>


<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ab7812060208cc92d9a0f3baa2dbd8e34">llvm::AAResults::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo/#ada47feae78e3f75c04c5474d5d805b09">llvm::BlockFrequencyInfo::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo/#a41951a9cbc849c4e0f2930f594c08847">llvm::BranchProbabilityInfo::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraph/#aafd0f61134b8387fbc0eb555142ad377">llvm::CallGraph::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/cgsccanalysismanagermoduleproxy/result/#a0e5728ec78bc4596393912985f0d2c57">llvm::CGSCCAnalysisManagerModuleProxy::Result::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a10d6c1036e234fab6e63803cf9fb62de">llvm::DependenceInfo::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/dominancefrontier/#a0281b508b2c122712bce17f594ea2c6d">llvm::DominanceFrontier::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#ae5abacbe0c3439b1f549f2d14292d0b1">llvm::DominatorTree::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilresourcetypemap/#ab1bb0aa816bb206f2163aecaf5360ce2">llvm::DXILResourceTypeMap::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/edgebundles/#a57ef483dd270cd42f2078099e172b0bd">llvm::EdgeBundles::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/functionanalysismanagercgsccproxy/result/#a1d080c4ca8dd19e09237ac942b78acc7">llvm::FunctionAnalysisManagerCGSCCProxy::Result::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/gcfunctioninfo/#a5f0d6e8c1a2258002879798734887921">llvm::GCFunctionInfo::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/globalsaaresult/#a6a669878583bed7b1ce9d1328b6b247e">llvm::GlobalsAAResult::invalidate</a>, <a href="/web-llvm/docs/api/structs/llvm/inlineadvisoranalysis/result/#ada8117eb5e7caf1e9ba0ac376735cf5c">llvm::InlineAdvisorAnalysis::Result::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#ae6c105e6215a1507fd7bc89f83e3c62f">llvm::LazyCallGraph::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo/#ae4dba96048be25f29b0ea6d715e873b2">llvm::LazyValueInfo::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/#ae1c2d5d3bb918342da8f156b7dc66a3c">llvm::LiveDebugVariables::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a7006961215ea5d215922af0f7b169a13">llvm::LiveIntervals::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfomanager/#a2680b21c365ab37c25b6d19ede287eb4">llvm::LoopAccessInfoManager::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfo/#a652aa0b059d50fc8ce065498020075e7">llvm::LoopInfo::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo/#aa91486e3f4b23c4b8937543e36b97de2">llvm::MachineBlockFrequencyInfo::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo/#a3cdcc5c57bbaa51937e0eba3197be755">llvm::MachineBranchProbabilityInfo::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree/#a49aa404b2a0f405d7db45e4aebd7706f">llvm::MachineDominatorTree::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionanalysis/result/#ab14fa1d2a1e2ef1dfad5ae9ef3337cd6">llvm::MachineFunctionAnalysis::Result::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo/#a418c848d6a9b1e0752090032b7ac8278">llvm::MachineLoopInfo::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortree/#a1deaedd3d73b764265d064639c1d36c0">llvm::MachinePostDominatorTree::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/#a783dbb62857dc2d0ca195934071d5b88">llvm::MachineTraceMetrics::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#afdb9a6afa20a9c40940f135b6a1cf59b">llvm::MemoryDependenceResults::invalidate</a>, <a href="/web-llvm/docs/api/structs/llvm/memoryssaanalysis/result/#aa7ef622a6a2b5d83ccd6b06a42f0ba48">llvm::MemorySSAAnalysis::Result::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/pgocontextualprofile/#a5e148b3ef3e5c8affa1403cef577159f">llvm::PGOContextualProfile::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/phivalues/#a88bf36667a2c9280d2ce163c7c57e716">llvm::PhiValues::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/physicalregisterusageinfo/#a08cca56920d14f500104268455af4306">llvm::PhysicalRegisterUsageInfo::invalidate</a>, <a href="/web-llvm/docs/api/structs/llvm/preservedcfgcheckerinstrumentation/cfg/#ac7bbe98acd9179e895bd2e5fa9c8e96c">llvm::PreservedCFGCheckerInstrumentation::CFG::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/regioninfo/#ad0336f49c52907a530484c2c4a3b2f82">llvm::RegionInfo::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a93a455a6a60ac3b40d15464bc3b86e90">llvm::ScalarEvolution::invalidate</a>, <a href="/web-llvm/docs/api/structs/llvm/shouldrunextrapasses/result/#afb0d98d85d8f59895de32dd450f0f0ef">llvm::ShouldRunExtraPasses&lt; MarkerTy &gt;::Result::invalidate</a>, <a href="/web-llvm/docs/api/structs/llvm/shouldrunextrapasses/result/#aa7d7720f8274811cf36bc0bfae1ec0fe">llvm::ShouldRunExtraPasses&lt; MarkerTy &gt;::Result::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/spillplacement/#a64ebfd5ad1ddae5f9cd92ea10af28610">llvm::SpillPlacement::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/cgscctofunctionpassadaptor/#a44a083f826f2f2a189d3979eb43dd5ed">llvm::CGSCCToFunctionPassAdaptor::run</a> and <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a>.</p>

</div>
</div>

### getChecker() {#a452552a70b5998a3a831fb2560498927}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalysisChecker llvm::PreservedAnalyses::getChecker (<a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a> * ID)</td>
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

<p>Build a checker for this <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a></span> and the specified analysis <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>


<p>You can use the returned object to query whether an analysis was preserved. See the example in the comment on <span class="doxyComputerOutput">PreservedAnalysis</span>.</p>


<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>

</div>
</div>

### intersect() {#a5f5dc18d0b2c71cba501f12975188e40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PreservedAnalyses::intersect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a> &amp; Arg)</td>
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

<p>Intersect this set with another in place.</p>


<p>This is a mutating operation on this preserved set, removing all preserved passes which are not also preserved in the argument.</p>


<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>


<p>References <a href="#a0eb77e2d868c69bebc48c07b49675748">areAllPreserved</a> and <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#af74676a3c7447be34bd2c1da76ec0c48">llvm::SmallPtrSetImpl&lt; PtrType &gt;::contains</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cgscctofunctionpassadaptor/#a44a083f826f2f2a189d3979eb43dd5ed">llvm::CGSCCToFunctionPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/devirtsccrepeatedpass/#a11597e1847c3156c4866aa0a43a1b71b">llvm::DevirtSCCRepeatedPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#a0ff99def687659818bdb4a25afd82c94">llvm::ModuleToPostOrderCGSCCPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#aef5d9142acafceffd14c76b8ddd0fd4e">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::run</a> and <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a6d74effaad77f6ecb91e1806993cda8f">llvm::PassManager&lt; LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp; &gt;::run</a>.</p>

</div>
</div>

### intersect() {#a72f56d9cb73db3c1ea0eee8fba48b64c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PreservedAnalyses::intersect (<a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a> &amp;&amp; Arg)</td>
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

<p>Intersect this set with a temporary other set in place.</p>


<p>This is a mutating operation on this preserved set, removing all preserved passes which are not also preserved in the argument.</p>


<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>


<p>Reference <a href="#a0eb77e2d868c69bebc48c07b49675748">areAllPreserved</a>.</p>

</div>
</div>

### preserve() {#ad966bea18aa62ffb9e040509adc7c99f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PreservedAnalyses::preserve ()</td>
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

<p>Mark an analysis as preserved.</p>

<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>


<p>Reference <a href="#ad966bea18aa62ffb9e040509adc7c99f">preserve</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac7294ba4e105807674fe3a394437fcc1">llvm::getLoopPassPreservedAnalyses</a>, <a href="#ad966bea18aa62ffb9e040509adc7c99f">preserve</a>, <a href="/web-llvm/docs/api/structs/llvm/adcepass/#a164c2d5f016f5cde2edc6c402dca72cb">llvm::ADCEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/aggressiveinstcombinepass/#a1d380b75a626cf6035ca021b9033e8f4">llvm::AggressiveInstCombinePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/alignmentfromassumptionspass/#a850fc86971c292f64bfad4d9076bfea8">llvm::AlignmentFromAssumptionsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuatomicoptimizerpass/#a61ccbe84ff2f490892da47cd8af3d621">llvm::AMDGPUAtomicOptimizerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuperfhintanalysispass/#abd3d261eb47ebf4c6d8fe9b40a90e726">llvm::AMDGPUPerfHintAnalysisPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpupromotekernelargumentspass/#a09b7bed11d55d255fef525817e8d1a6b">llvm::AMDGPUPromoteKernelArgumentsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuswlowerldspass/#a60fde742e4c1eaef19a09e78c111cd6a">llvm::AMDGPUSwLowerLDSPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentpromotionpass/#afe0f49f9daec2532b14ded30ed46ff28">llvm::ArgumentPromotionPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorcgsccpass/#a305cbdd90350f05f5ee772811d596ded">llvm::AttributorCGSCCPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorlightcgsccpass/#a1725467ef5883a44e7777d681c6a4d32">llvm::AttributorLightCGSCCPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorlightpass/#af4dc3e41c843da6385d1252386d4c03e">llvm::AttributorLightPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/breakcriticaledgespass/#a5f8ef6ce9ef2eb4568d48e3530b5652d">llvm::BreakCriticalEdgesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrpreparepass/#a9281dc805301bc24be1f5401e30a878f">llvm::CallBrPreparePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/callsitesplittingpass/#a758aec9b799aa0d0559635cfc6144f36">llvm::CallSiteSplittingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cgscctofunctionpassadaptor/#a44a083f826f2f2a189d3979eb43dd5ed">llvm::CGSCCToFunctionPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/codegenpreparepass/#a33f05511e053fdbfa05140b0cd29553a">llvm::CodeGenPreparePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/complexdeinterleavingpass/#aa41892eb6184fda37101c5488412abc5">llvm::ComplexDeinterleavingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/constrainteliminationpass/#a42aea849d980d7bce1c0ef31ac326e87">llvm::ConstraintEliminationPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/correlatedvaluepropagationpass/#a1672fc6d49348158aa95dbb4ae80224c">llvm::CorrelatedValuePropagationPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/dfajumpthreadingpass/#a1e2cfc4a731613030f8f416677999fa0">llvm::DFAJumpThreadingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dsepass/#a29b9f8c28e2ba0531f66bd82e8c5a32e">llvm::DSEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfehpreparepass/#aa5ae7b5c2898ddfa38ede1415c5d6d3c">llvm::DwarfEHPreparePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxiloplowering/#a8907c1ee9a102c2ec9a7895d352a7a6e">llvm::DXILOpLowering::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilresourceaccess/#a1d78f24c9cef5813c0cb9aea5b00b183">llvm::DXILResourceAccess::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilupgradepass/#abc0869ccaedd0cb2879db7c457fb0ac8">llvm::DXILUpgradePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/earlycsepass/#a1977dd7d302009cd95b32ad3a5dd8db6">llvm::EarlyCSEPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/fixirreduciblepass/#a61707c67652fa7e327bb8ac607164e09">llvm::FixIrreduciblePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/gcloweringpass/#aa642143ff84b39a1e644a6435f69b643">llvm::GCLoweringPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/globaloptpass/#a0be1afba37502be6858f2a1c38955be8">llvm::GlobalOptPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/guardwideningpass/#a13571b5fc50d701864f8b3de9b930b7f">llvm::GuardWideningPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/gvnhoistpass/#a73462db6e4114fd6c543b9b3de65a504">llvm::GVNHoistPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnpass/#a25dcf17194b012b2b35388798cac2da7">llvm::GVNPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/hardwareloopspass/#a7b139351e6b64d570e4ee5b7ece478ea">llvm::HardwareLoopsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/hwaddresssanitizerpass/#a0ab6bbfe1dc498f2c9a8603d672fbb1b">llvm::HWAddressSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrexpandpass/#af36e885f10703886f9001dd79432b77f">llvm::IndirectBrExpandPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/inferaddressspacespass/#a8750fe658baa71eeba987c3bea8bf83e">llvm::InferAddressSpacesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinepass/#aa1ffc7ad08181545bbc25eabac7f5aae">llvm::InstCombinePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ipsccppass/#a7c77a408787021dc65c12646cee2ac43">llvm::IPSCCPPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/jumptabletoswitchpass/#a84778fc53894f05e88ce0cc794561742">llvm::JumpTableToSwitchPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lcssapass/#a7ae4df8ff3ca478772f6f055bf88bd1f">llvm::LCSSAPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopdataprefetchpass/#af1020d68a0e1a023973890cf0e079c28">llvm::LoopDataPrefetchPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopdistributepass/#ab4ccb40cf0dd5fd358dd5e0f0d4d7c6f">llvm::LoopDistributePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/loopextractorpass/#ac1cd83190da80057c6903402d80cc1f7">llvm::LoopExtractorPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopfusepass/#a971f40ada3f1410759faede02bfbace7">llvm::LoopFusePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/looploadeliminationpass/#af81bad0018d7e67a1c92d785305426b0">llvm::LoopLoadEliminationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsimplifypass/#a294bd885b054adcb86315a9112ea0b33">llvm::LoopSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsinkpass/#a11eda417d0372700a9b48e41f267ab92">llvm::LoopSinkPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#af3b0e58cfdb2c6c663cd47a8808ba70a">llvm::LoopVectorizePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/lowerconstantintrinsicspass/#ab82707f4044f916e7c0ce1955b987cba">llvm::LowerConstantIntrinsicsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lowermatrixintrinsicspass/#a7b05a9de14294b7a5a7904cc8d5c8e1e">llvm::LowerMatrixIntrinsicsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memcpyoptpass/#a07c3f5129a977e2f949212878c3042ae">llvm::MemCpyOptPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/mergeicmpspass/#a96cfc6defc256b49f69f6fb8bfbf8c87">llvm::MergeICmpsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moveautoinitpass/#a55a3f992f62d23ae617927c2de5a81c9">llvm::MoveAutoInitPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/naryreassociatepass/#a44a686152f979478fbbac82b70bf85fb">llvm::NaryReassociatePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/newgvnpass/#a6b1b7ab1a677eb8039694b4dfe6cb997">llvm::NewGVNPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/partiallyinlinelibcallspass/#a0e2ff100989ce66c294cfe38904c6cf1">llvm::PartiallyInlineLibCallsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoinstrumentationgencreatevar/#a48fd4403aec933165941509e289a4938">llvm::PGOInstrumentationGenCreateVar::run</a>, <a href="/web-llvm/docs/api/structs/llvm/postorderfunctionattrspass/#a8312d250d0f7b4407b4bad97293e5865">llvm::PostOrderFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/regtomempass/#a0a8fbb23329369eafe88acc194f6336d">llvm::RegToMemPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/replacewithveclib/#ac03e0f62c8cbbdd055546686f847183c">llvm::ReplaceWithVeclib::run</a>, <a href="/web-llvm/docs/api/classes/llvm/reversepostorderfunctionattrspass/#a711463cdc12e518aaca8c394a0f82139">llvm::ReversePostOrderFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/rewritestatepointsforgc/#af56b6dd2da7f65fa682eaf6a16cdb36a">llvm::RewriteStatepointsForGC::run</a>, <a href="/web-llvm/docs/api/classes/llvm/safestackpass/#a7a84d5b29faf6a5ce458e61ac1f79cab">llvm::SafeStackPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/scalarizemaskedmemintrinpass/#ab805176ab5d08e2a34fadbc760bca5a6">llvm::ScalarizeMaskedMemIntrinPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarizerpass/#a250da10ea723b93bcd9f52cd0bca4d7e">llvm::ScalarizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/shadowstackgcloweringpass/#a2053b340bf34047264af3190e9473953">llvm::ShadowStackGCLoweringPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/siannotatecontrolflowpass/#a84e9204f8b261089c66706e2941ee6da">llvm::SIAnnotateControlFlowPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/simplifycfgpass/#a1196be608a7f568e9cb19fe11f80ebe2">llvm::SimplifyCFGPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sroapass/#a6cca3e145c2eb9050c6b4b94e2f760a0">llvm::SROAPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/stackprotectorpass/#af99d23fe1a6d3d9ebfdf9fa3a101830a">llvm::StackProtectorPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/straightlinestrengthreducepass/#a40a452b8f3a3f5538eed5201e5bfdcc4">llvm::StraightLineStrengthReducePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/structurizecfgpass/#aeb3e7a1f92ba7129a43fdfe85ea9c000">llvm::StructurizeCFGPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/tailcallelimpass/#ab754a2815f5333ff5f443593896814dc">llvm::TailCallElimPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/typepromotionpass/#addcc6ab5729a0a8e495cdc585f02234c">llvm::TypePromotionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/unifyloopexitspass/#afa18953dc3062e2c68866c9065b12bcb">llvm::UnifyLoopExitsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/unreachableblockelimpass/#a9941546788895103d10cdd0cfabe968c">llvm::UnreachableBlockElimPass::run</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-expandmemcmp-cpp-/#a1ed6e9933878fa5790bdacff6d5a907b">anonymous{ExpandMemCmp.cpp}::runImpl</a>.</p>

</div>
</div>

### preserve() {#ac138874dedaeb0b8cdcf6c381bc2103b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PreservedAnalyses::preserve (<a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a> * ID)</td>
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

<p>Given an analysis's <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, mark the analysis as preserved, adding it to the set.</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>


<p>Reference <a href="#a0eb77e2d868c69bebc48c07b49675748">areAllPreserved</a>.</p>

</div>
</div>

### preserveSet() {#a937c42f77e161349ce0f999e448c7027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisSetT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PreservedAnalyses::preserveSet ()</td>
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

<p>Mark an analysis set as preserved.</p>

<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>


<p>Reference <a href="#a937c42f77e161349ce0f999e448c7027">preserveSet</a>.</p>


<p>Referenced by <a href="#aea87afbe4520fdc60652c554501f5cdf">allInSet</a>, <a href="#a937c42f77e161349ce0f999e448c7027">preserveSet</a>, <a href="/web-llvm/docs/api/classes/llvm/debugifyeachinstrumentation/#ac08162972dd07f89c515c12aa05aa279">llvm::DebugifyEachInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp/#a4d9bbafb5550c98593c6100ca4c43416">rtsanPreservedCFGAnalyses</a>, <a href="/web-llvm/docs/api/structs/llvm/adcepass/#a164c2d5f016f5cde2edc6c402dca72cb">llvm::ADCEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/aggressiveinstcombinepass/#a1d380b75a626cf6035ca021b9033e8f4">llvm::AggressiveInstCombinePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/alignmentfromassumptionspass/#a850fc86971c292f64bfad4d9076bfea8">llvm::AlignmentFromAssumptionsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/alwaysinlinerpass/#ac95b8d75e282ac5dbb2ed47ae1e1c88b">llvm::AlwaysInlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuannotateuniformvaluespass/#ad40e073c46402aba328eb57891116b74">llvm::AMDGPUAnnotateUniformValuesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucodegenpreparepass/#a09ffc2a128b37269498bbcabc7f145d4">llvm::AMDGPUCodeGenPreparePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulatecodegenpreparepass/#a5a4ff24504b852091b900d036f556885">llvm::AMDGPULateCodeGenPreparePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulowerkernelargumentspass/#ae2558d2ae5e88579c75cd73760cd0d5d">llvm::AMDGPULowerKernelArgumentsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpupromoteallocapass/#a620e8ec3e3017fcb099b9410cc0056d5">llvm::AMDGPUPromoteAllocaPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpupromoteallocatovectorpass/#a4d58a8f51935070c2ec517b3becde405">llvm::AMDGPUPromoteAllocaToVectorPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpupromotekernelargumentspass/#a09b7bed11d55d255fef525817e8d1a6b">llvm::AMDGPUPromoteKernelArgumentsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpurewriteundefforphipass/#a389937d71bd8740fe3be1c396949e0bb">llvm::AMDGPURewriteUndefForPHIPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentpromotionpass/#afe0f49f9daec2532b14ded30ed46ff28">llvm::ArgumentPromotionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/assignmenttrackingpass/#a56ff79a9fa9dba1d34f2e7d55319b6cb">llvm::AssignmentTrackingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/assignmenttrackingpass/#a809e420808034e2e213e44b485fed902">llvm::AssignmentTrackingPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/assumebuilderpass/#aca0fa8f3093912d8045361e2f6b79cac">llvm::AssumeBuilderPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/assumesimplifypass/#a378f8b2a8e11ac78939bd1c732f05d2e">llvm::AssumeSimplifyPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorlightcgsccpass/#a1725467ef5883a44e7777d681c6a4d32">llvm::AttributorLightCGSCCPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorlightpass/#af4dc3e41c843da6385d1252386d4c03e">llvm::AttributorLightPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/bdcepass/#afbbfc5e8696e402cd67ebdc99da7c47a">llvm::BDCEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cgscctofunctionpassadaptor/#a44a083f826f2f2a189d3979eb43dd5ed">llvm::CGSCCToFunctionPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/constanthoistingpass/#abe3f0e309e575379e5bae02d1907f394">llvm::ConstantHoistingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/constrainteliminationpass/#a42aea849d980d7bce1c0ef31ac326e87">llvm::ConstraintEliminationPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/corocleanuppass/#ad94b3bcb5dea38b6b7d891fa9344322c">llvm::CoroCleanupPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/coroearlypass/#a51727f84394faeab7cf97730aec48488">llvm::CoroEarlyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dcepass/#ae0adbbdfa4d74b93465ac5dd85124af4">llvm::DCEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/deadmachineinstructionelimpass/#ad3348ab2ee0fa767f8b2f39e16f78ac4">llvm::DeadMachineInstructionElimPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/divrempairspass/#a4247592199f0303b2d61eb171b2acdd1">llvm::DivRemPairsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dsepass/#a29b9f8c28e2ba0531f66bd82e8c5a32e">llvm::DSEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilupgradepass/#abc0869ccaedd0cb2879db7c457fb0ac8">llvm::DXILUpgradePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/earlycsepass/#a1977dd7d302009cd95b32ad3a5dd8db6">llvm::EarlyCSEPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/entryexitinstrumenterpass/#a01fcebccd3470faf07c176cd6934b7f7">llvm::EntryExitInstrumenterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/expandreductionspass/#a9fea76fcf757718eb4aafcd72cb89038">llvm::ExpandReductionsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/float2intpass/#ad9900fbd867b1e73f7da240f0e7a28c1">llvm::Float2IntPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/globalmergepass/#a3f8ec211506240dc543433b4fda3d011">llvm::GlobalMergePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/globaloptpass/#a0be1afba37502be6858f2a1c38955be8">llvm::GlobalOptPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/guardwideningpass/#a13571b5fc50d701864f8b3de9b930b7f">llvm::GuardWideningPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonvectorloopcarriedreusepass/#a32948988705da5dd73dba608197477fc">llvm::HexagonVectorLoopCarriedReusePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/inferaddressspacespass/#a8750fe658baa71eeba987c3bea8bf83e">llvm::InferAddressSpacesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinepass/#aa1ffc7ad08181545bbc25eabac7f5aae">llvm::InstCombinePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instsimplifypass/#ad073cb9259c01c880086405f8776a106">llvm::InstSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavedaccesspass/#ae66f66ef855bdcccfe7802d81f9a816a">llvm::InterleavedAccessPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/irnormalizerpass/#a4590cd6cc5d19e52abb0cc259f99da92">llvm::IRNormalizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lcssapass/#a7ae4df8ff3ca478772f6f055bf88bd1f">llvm::LCSSAPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loadstorevectorizerpass/#a78465c41b72ca43acdbbfc47cbce3d76">llvm::LoadStoreVectorizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsinkpass/#a11eda417d0372700a9b48e41f267ab92">llvm::LoopSinkPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#af3b0e58cfdb2c6c663cd47a8808ba70a">llvm::LoopVectorizePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lowerglobaldtorspass/#a8895fb3cf22b753143095a1552ca974a">llvm::LowerGlobalDtorsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memcpyoptpass/#a07c3f5129a977e2f949212878c3042ae">llvm::MemCpyOptPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/mergedloadstoremotionpass/#af9d31b63718e1ad6d4e0881e49a415bd">llvm::MergedLoadStoreMotionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moveautoinitpass/#a55a3f992f62d23ae617927c2de5a81c9">llvm::MoveAutoInitPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/naryreassociatepass/#a44a686152f979478fbbac82b70bf85fb">llvm::NaryReassociatePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarcapelimpass/#ae4e95bbaf8d3c3a8b8df38c406a73030">llvm::ObjCARCAPElimPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarccontractpass/#a37aa96fbe116641ca7204a785341c962">llvm::ObjCARCContractPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarcexpandpass/#afec00b95aa5fccab1101e69496207a4a">llvm::ObjCARCExpandPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarcoptpass/#a02b31ca54388bfecbdd6593b7563d146">llvm::ObjCARCOptPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#aef5d9142acafceffd14c76b8ddd0fd4e">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoinstrumentationgencreatevar/#a48fd4403aec933165941509e289a4938">llvm::PGOInstrumentationGenCreateVar::run</a>, <a href="/web-llvm/docs/api/structs/llvm/postorderfunctionattrspass/#a8312d250d0f7b4407b4bad97293e5865">llvm::PostOrderFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/promotepass/#aca8a105910e7bb81285435f553e71872">llvm::PromotePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/reassociatepass/#aadf6b90fc920d89751c191799ff3e6ea">llvm::ReassociatePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/redundantdbginsteliminationpass/#aae0280e54f28cf0e183b7a6f64a0f2fa">llvm::RedundantDbgInstEliminationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/rellookuptableconverterpass/#a3b1519f165c877970b589c9f53db69eb">llvm::RelLookupTableConverterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/replacewithveclib/#ac03e0f62c8cbbdd055546686f847183c">llvm::ReplaceWithVeclib::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxvectorizerpass/#a551ef06f642e5ab4d0e22806eb5bb4ac">llvm::SandboxVectorizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/separateconstoffsetfromgeppass/#a949e76f284f0977c83f729850a8b8a8b">llvm::SeparateConstOffsetFromGEPPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/siloadstoreoptimizerpass/#a73bd665c6e03c1dc196c107a450e228a">llvm::SILoadStoreOptimizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/siloweri1copiespass/#a0af1fadc28e71aac6e7e74c59686a02b">llvm::SILowerI1CopiesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sinkingpass/#a07a25f4cfc32581da84eea1e0ced7f2e">llvm::SinkingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sipeepholesdwapass/#af333339d4156056152073cbe27eb1887">llvm::SIPeepholeSDWAPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/slpvectorizerpass/#aaec443311cb572adf0e2db9db82279ef">llvm::SLPVectorizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/speculativeexecutionpass/#a75693e29732ce9935478d5fdc533c67d">llvm::SpeculativeExecutionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvstructurizerwrapper/#abd2d6184a5dcf12b75b70b9f315e8389">llvm::SPIRVStructurizerWrapper::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sroapass/#a6cca3e145c2eb9050c6b4b94e2f760a0">llvm::SROAPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/straightlinestrengthreducepass/#a40a452b8f3a3f5538eed5201e5bfdcc4">llvm::StraightLineStrengthReducePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/stripdeaddebuginfopass/#a3e36223722fcea87ee11a32aee055a06">llvm::StripDeadDebugInfoPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/stripdebugdeclarepass/#abf54ab0e38786321455ba758fe471099">llvm::StripDebugDeclarePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/stripgcrelocates/#aaa7527b13944005e12d9f2ebf6a2c8a3">llvm::StripGCRelocates::run</a>, <a href="/web-llvm/docs/api/structs/llvm/stripnondebugsymbolspass/#abd66c8908698f8f7cdc8db3f951d07b5">llvm::StripNonDebugSymbolsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/stripnonlinetabledebuginfopass/#a9bb911c9d4a523b04904bd44da4e8204">llvm::StripNonLineTableDebugInfoPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/stripsymbolspass/#af8e937fce4b8ddd782b81929f3f2c637">llvm::StripSymbolsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/typepromotionpass/#addcc6ab5729a0a8e495cdc585f02234c">llvm::TypePromotionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/vectorcombinepass/#a6a1e4cac923bd64f58cb782f1a5ba91a">llvm::VectorCombinePass::run</a>, <a href="/web-llvm/docs/api/classes/newpmdebugifypass/#a3467f1430bf7b9dd04778821d779bf96">NewPMDebugifyPass::run</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a6c7a8371c75641e29a5259c131fd8408">runAttributorLightOnFunctions</a>.</p>

</div>
</div>

### preserveSet() {#a05f35e3a28f0760667448247878c1b80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PreservedAnalyses::preserveSet (<a href="/web-llvm/docs/api/structs/llvm/analysissetkey">AnalysisSetKey</a> * ID)</td>
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

<p>Mark an analysis set as preserved using its <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>


<p>Reference <a href="#a0eb77e2d868c69bebc48c07b49675748">areAllPreserved</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### NotPreservedAnalysisIDs {#a37b20de6fd9783d24921c263d127a291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;AnalysisKey *, 2&gt; llvm::PreservedAnalyses::NotPreservedAnalysisIDs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The IDs of explicitly not-preserved analyses.</p>


<p>If an analysis in this set is covered by a set in <span class="doxyComputerOutput">PreservedIDs</span>, we consider it not-preserved. That is, <span class="doxyComputerOutput">NotPreservedAnalysisIDs</span> always "wins" over analysis sets in <span class="doxyComputerOutput">PreservedIDs</span>.</p>


<p>Also, a given <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> should never occur both here and in <span class="doxyComputerOutput">PreservedIDs</span>.</p>


<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>

</div>
</div>

### PreservedIDs {#ae8b1077ed88229e6b2a24bbea9292807}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;void *, 2&gt; llvm::PreservedAnalyses::PreservedIDs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The IDs of analyses and analysis sets that are preserved.</p>

<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### all() {#a1258a1ff55557c27684010ebd7283712}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses llvm::PreservedAnalyses::all ()</td>
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

<p>Construct a special preserved set that preserves all passes.</p>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/optimizephis-cpp/#aa06400d4e92e2a1acf8889f457160abf">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/anonymous-instcount-cpp-/instcount/#a2f6d5d0af5c247dfbf0a42a84559ec23">anonymous{InstCount.cpp}::InstCount::InstVisitor&lt; InstCount &gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#a8116ffdfb54f7d195eb185c8bf7c060c">llvm::MLInlineAdvisor::onSuccessfulInlining</a>, <a href="/web-llvm/docs/api/classes/anonymous-passbuilder-cpp-/triggercrashfunctionpass/#adace6a9ea628e5581f850e92c5ae6eb9">anonymous{PassBuilder.cpp}::TriggerCrashFunctionPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-passbuilder-cpp-/triggercrashmodulepass/#ab794b16e75478f7cc96a4cac7002dea1">anonymous{PassBuilder.cpp}::TriggerCrashModulePass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-passbuilder-cpp-/triggerverifiererrorpass/#a477b123c7ac80e57d0c8ac4abb0ff293">anonymous{PassBuilder.cpp}::TriggerVerifierErrorPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectoptimize-cpp-/selectoptimizeimpl/#ae454ad67b6e4fa9846a5395dc76759d6">anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::run</a>, <a href="/web-llvm/docs/api/classes/llvm/aaevaluator/#a9ed5f1670101ec861ebdd6c74540f4da">llvm::AAEvaluator::run</a>, <a href="/web-llvm/docs/api/structs/llvm/adcepass/#a164c2d5f016f5cde2edc6c402dca72cb">llvm::ADCEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/adddiscriminatorspass/#a7c89dac3d04b8cda0fe7586df5429d28">llvm::AddDiscriminatorsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/addresssanitizerpass/#a987afb1c68c5891e0b9a67cdac48147d">llvm::AddressSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/aggressiveinstcombinepass/#a1d380b75a626cf6035ca021b9033e8f4">llvm::AggressiveInstCombinePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/aliassetsprinterpass/#a3a8a27458f2832e65ace0c61bb035be7">llvm::AliasSetsPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/alignmentfromassumptionspass/#a850fc86971c292f64bfad4d9076bfea8">llvm::AlignmentFromAssumptionsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/alwaysinlinerpass/#ac95b8d75e282ac5dbb2ed47ae1e1c88b">llvm::AlwaysInlinerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpualwaysinlinepass/#aae20ee2a6a4ad198fc7b74d1a5a726c0">llvm::AMDGPUAlwaysInlinePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuannotateuniformvaluespass/#ad40e073c46402aba328eb57891116b74">llvm::AMDGPUAnnotateUniformValuesPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuatomicoptimizerpass/#a61ccbe84ff2f490892da47cd8af3d621">llvm::AMDGPUAtomicOptimizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuattributorpass/#a6b853868668b480de1fb9a5638185bbf">llvm::AMDGPUAttributorPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucodegenpreparepass/#a09ffc2a128b37269498bbcabc7f145d4">llvm::AMDGPUCodeGenPreparePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuctordtorloweringpass/#ad4e5fca7d7b0ff779714b3827d0b5ae9">llvm::AMDGPUCtorDtorLoweringPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuimageintrinsicoptimizerpass/#a11860dd752695b8560ec59e4459f1417">llvm::AMDGPUImageIntrinsicOptimizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulatecodegenpreparepass/#a5a4ff24504b852091b900d036f556885">llvm::AMDGPULateCodeGenPreparePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpulowerbufferfatpointerspass/#a629f4e8b3eddebb7df9b92172a9025b1">llvm::AMDGPULowerBufferFatPointersPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulowerkernelargumentspass/#ae2558d2ae5e88579c75cd73760cd0d5d">llvm::AMDGPULowerKernelArgumentsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpulowerkernelattributespass/#af67c40d9973225a0cdd48e2c13ffe9d2">llvm::AMDGPULowerKernelAttributesPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpulowermoduleldspass/#a76be940af9a6ce8a688affa5368cd3cb">llvm::AMDGPULowerModuleLDSPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuopenclenqueuedblockloweringpass/#ae8399e5456f80b9b739058cc30df10f3">llvm::AMDGPUOpenCLEnqueuedBlockLoweringPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuperfhintanalysispass/#abd3d261eb47ebf4c6d8fe9b40a90e726">llvm::AMDGPUPerfHintAnalysisPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupreloadkernargprologpass/#a0f5aef9a9f098c2144b9ac4e62675666">llvm::AMDGPUPreloadKernArgPrologPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuprintfruntimebindingpass/#a04bc7056720bebea77cc9fcab42aecc3">llvm::AMDGPUPrintfRuntimeBindingPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpupromoteallocapass/#a620e8ec3e3017fcb099b9410cc0056d5">llvm::AMDGPUPromoteAllocaPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpupromoteallocatovectorpass/#a4d58a8f51935070c2ec517b3becde405">llvm::AMDGPUPromoteAllocaToVectorPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpupromotekernelargumentspass/#a09b7bed11d55d255fef525817e8d1a6b">llvm::AMDGPUPromoteKernelArgumentsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuremoveincompatiblefunctionspass/#ac67b2b8b03c9e7cecf703fd30abb485e">llvm::AMDGPURemoveIncompatibleFunctionsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpurewriteundefforphipass/#a389937d71bd8740fe3be1c396949e0bb">llvm::AMDGPURewriteUndefForPHIPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpusimplifylibcallspass/#ae83c4c6a3cf049dbac4ce40c2fa476dd">llvm::AMDGPUSimplifyLibCallsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuswlowerldspass/#a60fde742e4c1eaef19a09e78c111cd6a">llvm::AMDGPUSwLowerLDSPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuunifydivergentexitnodespass/#a3e73b9a5c7212271285ef6c38d1cd26d">llvm::AMDGPUUnifyDivergentExitNodesPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuunifymetadatapass/#a538284b7129994222827deed13f792cc">llvm::AMDGPUUnifyMetadataPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuusenativecallspass/#a153430907ef218b9118d28f077a5dd78">llvm::AMDGPUUseNativeCallsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/annotation2metadatapass/#aa7680281613fde3b2326fc67b34dbcd9">llvm::Annotation2MetadataPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/annotationremarkspass/#a1dd7b1feb9652fcb6ea5e6741029b063">llvm::AnnotationRemarksPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentpromotionpass/#afe0f49f9daec2532b14ded30ed46ff28">llvm::ArgumentPromotionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/assignmenttrackingpass/#a56ff79a9fa9dba1d34f2e7d55319b6cb">llvm::AssignmentTrackingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/assignmenttrackingpass/#a809e420808034e2e213e44b485fed902">llvm::AssignmentTrackingPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/assumebuilderpass/#aca0fa8f3093912d8045361e2f6b79cac">llvm::AssumeBuilderPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/assumesimplifypass/#a378f8b2a8e11ac78939bd1c732f05d2e">llvm::AssumeSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/assumptionprinterpass/#a140e7194c82dc0eda75b3602736a0b83">llvm::AssumptionPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicexpandpass/#ae932e2c8ae7317381567ef80224874d5">llvm::AtomicExpandPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorcgsccpass/#a305cbdd90350f05f5ee772811d596ded">llvm::AttributorCGSCCPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorlightcgsccpass/#a1725467ef5883a44e7777d681c6a4d32">llvm::AttributorLightCGSCCPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorlightpass/#af4dc3e41c843da6385d1252386d4c03e">llvm::AttributorLightPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorpass/#aba65d47dce0a15a90eb4e519ffc4929c">llvm::AttributorPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/bdcepass/#afbbfc5e8696e402cd67ebdc99da7c47a">llvm::BDCEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodewriterpass/#a2cf5fec0ba55756093b6c7e6c8f31c00">llvm::BitcodeWriterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/blockextractorpass/#a9be62d1c1fc68905037c91b681e7a329">llvm::BlockExtractorPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyprinterpass/#a5a6cbafd8221cce28bfb4fe7aca32f94">llvm::BlockFrequencyPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/boundscheckingpass/#aaeef3ef960131b08e172917320b9507d">llvm::BoundsCheckingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfabstractmemberaccesspass/#a6dc0d5add9dd3e49bf053ce9eed7a998">llvm::BPFAbstractMemberAccessPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfadjustoptpass/#a24d58eb05b954d419e136f326ec3b8cd">llvm::BPFAdjustOptPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfaspacecastsimplifypass/#a76364c57022d89ac618f1b1e22bef6e2">llvm::BPFASpaceCastSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfirpeepholepass/#abf9fca0eab24cbc96c2d0c2c2a1438a4">llvm::BPFIRPeepholePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfpreserveditypepass/#ae1e68a4457f7157f360590db8094edc4">llvm::BPFPreserveDITypePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfpreservestaticoffsetpass/#aef25d4cdefd91999a61e1854ea64b148">llvm::BPFPreserveStaticOffsetPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityprinterpass/#af8bbfa323a4917223612dff12067110b">llvm::BranchProbabilityPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/breakcriticaledgespass/#a5f8ef6ce9ef2eb4568d48e3530b5652d">llvm::BreakCriticalEdgesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrpreparepass/#a9281dc805301bc24be1f5401e30a878f">llvm::CallBrPreparePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/calledvaluepropagationpass/#a97d2795c46a61afbc87c4c88caac7124">llvm::CalledValuePropagationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphdotprinterpass/#a7d72837594bc13f77f2d84bcfd0752de">llvm::CallGraphDOTPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphprinterpass/#a3bb83e1831d2ffb599b81c6bd047a7b9">llvm::CallGraphPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphsccsprinterpass/#adab3cbb8d806b7d4d2138bd93e92c99a">llvm::CallGraphSCCsPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphviewerpass/#aaea10b30adce800d7d54b5394a49567b">llvm::CallGraphViewerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/callsitesplittingpass/#a758aec9b799aa0d0559635cfc6144f36">llvm::CallSiteSplittingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalizealiasespass/#adbebb133afffe58930e8681d47c2b071">llvm::CanonicalizeAliasesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalizefreezeinloopspass/#a8bc859057e091c18fffefa68d8dcd3e6">llvm::CanonicalizeFreezeInLoopsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cfgonlyprinterpass/#af4633166ee31522ede36144c2cadde39">llvm::CFGOnlyPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cfgonlyviewerpass/#a2c9830e7108892805b14bca50f644d0c">llvm::CFGOnlyViewerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cfgprinterpass/#a4d6be8adf1d7c561f9a47831f910fd91">llvm::CFGPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cfgsccprinterpass/#a96473022551496bd57cb61b5b56b1270">llvm::CFGSCCPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cfguardpass/#a0d01e5f89b3ff7eb3f081f3ec59d27bb">llvm::CFGuardPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cfgviewerpass/#a4ec76f0493f0ee9679e2a15343680ccf">llvm::CFGViewerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cgprofilepass/#ab84e768b0ca66104a03d4dd6f96422fe">llvm::CGProfilePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cgscctofunctionpassadaptor/#a44a083f826f2f2a189d3979eb43dd5ed">llvm::CGSCCToFunctionPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/codegenpreparepass/#a33f05511e053fdbfa05140b0cd29553a">llvm::CodeGenPreparePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/complexdeinterleavingpass/#aa41892eb6184fda37101c5488412abc5">llvm::ComplexDeinterleavingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/constanthoistingpass/#abe3f0e309e575379e5bae02d1907f394">llvm::ConstantHoistingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/constantmergepass/#aea5f79617ea5595171a5ce5d3deac6b4">llvm::ConstantMergePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/constrainteliminationpass/#a42aea849d980d7bce1c0ef31ac326e87">llvm::ConstraintEliminationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/controlheightreductionpass/#aa07878663a309c8f4a4537b971c6d3b0">llvm::ControlHeightReductionPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/coroannotationelidepass/#a411202dc502ac666302ba81c40e94b10">llvm::CoroAnnotationElidePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/corocleanuppass/#ad94b3bcb5dea38b6b7d891fa9344322c">llvm::CoroCleanupPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/coroconditionalwrapper/#a393e9909fb7adb8a1effe8ac4fe745d3">llvm::CoroConditionalWrapper::run</a>, <a href="/web-llvm/docs/api/structs/llvm/coroearlypass/#a51727f84394faeab7cf97730aec48488">llvm::CoroEarlyPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/coroelidepass/#a6dfdc223099c4ca952c8b0369027e34d">llvm::CoroElidePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/corosplitpass/#a47f6589634ad33a13369ace133b9f4b2">llvm::CoroSplitPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/correlatedvaluepropagationpass/#a1672fc6d49348158aa95dbb4ae80224c">llvm::CorrelatedValuePropagationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/costmodelprinterpass/#a6685ffe146df7448fc95cd7fcec89e55">llvm::CostModelPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/countvisitspass/#a0c5311373852fe7cd5458324db4cf363">llvm::CountVisitsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/crossdsocfipass/#a4dfd6efbe42e2fe46955cce4d9bbc8ef">llvm::CrossDSOCFIPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ctxprofanalysisprinterpass/#a3edae17ead4808eee55b99b0e1add11b">llvm::CtxProfAnalysisPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cycleinfoprinterpass/#a5fe94fefc760afe4f7b178e72299aa39">llvm::CycleInfoPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/cycleinfoverifierpass/#af9fcac728641055cca5bdb95469dc5e4">llvm::CycleInfoVerifierPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dataflowsanitizerpass/#a763709e61e42f6df707528b509adf8de">llvm::DataFlowSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dcepass/#ae0adbbdfa4d74b93465ac5dd85124af4">llvm::DCEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ddganalysisprinterpass/#aa18a597cd04af57bb4061499d5d5640c">llvm::DDGAnalysisPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ddgdotprinterpass/#ad73a209beeea1475814429bdd8bdeda5">llvm::DDGDotPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/deadargumenteliminationpass/#a29ba94ac3af7390af4fa3209e6647732">llvm::DeadArgumentEliminationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/deadmachineinstructionelimpass/#ad3348ab2ee0fa767f8b2f39e16f78ac4">llvm::DeadMachineInstructionElimPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/debugassignmenttrackingprinterpass/#a2fca7dac7d7904748ce1fd08da363d2a">llvm::DebugAssignmentTrackingPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/delinearizationprinterpass/#af564d4ce1f4c1029592d1a923b0d2c43">llvm::DelinearizationPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/demandedbitsprinterpass/#a3f85a7e646826596cd811e66f0df417f">llvm::DemandedBitsPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/dependenceanalysisprinterpass/#a94874ca66100ea29adacb124f5d73db0">llvm::DependenceAnalysisPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/devirtsccrepeatedpass/#a11597e1847c3156c4866aa0a43a1b71b">llvm::DevirtSCCRepeatedPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/dfajumpthreadingpass/#a1e2cfc4a731613030f8f416677999fa0">llvm::DFAJumpThreadingPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/divrempairspass/#a4247592199f0303b2d61eb171b2acdd1">llvm::DivRemPairsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dominancefrontierprinterpass/#aae343d5e2c1b700a31142af232a990cf">llvm::DominanceFrontierPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreeprinterpass/#a4e7ca1ff82e0d63a88d574a545380fea">llvm::DominatorTreePrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/dominatortreeverifierpass/#a680c63d627c9e32ca9f2ba34e52c6543">llvm::DominatorTreeVerifierPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraitsprinter/#a08f94d0dd9cf5bd433019e64b44d0d58">llvm::DOTGraphTraitsPrinter&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::run</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraitsviewer/#a785d4e2677b22a4dc41713c1e82c492f">llvm::DOTGraphTraitsViewer&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dsepass/#a29b9f8c28e2ba0531f66bd82e8c5a32e">llvm::DSEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfehpreparepass/#aa5ae7b5c2898ddfa38ede1415c5d6d3c">llvm::DwarfEHPreparePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/shaderflagsanalysisprinter/#a0784c57dc0671927404b56c94ec983c8">llvm::dxil::ShaderFlagsAnalysisPrinter::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxildatascalarization/#a74fa6f4c573da9c931d244b175ff6ea9">llvm::DXILDataScalarization::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilfinalizelinkage/#af624c56c0240734e52623e85d262ba7d">llvm::DXILFinalizeLinkage::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilflattenarrays/#a6c2e417054f84cfe4021992ebaa98169">llvm::DXILFlattenArrays::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilintrinsicexpansion/#a8c44e930b068104f227b3c1b0f4f3151">llvm::DXILIntrinsicExpansion::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilmetadataanalysisprinterpass/#a853a7e2cfb272918dbcf0f260f091598">llvm::DXILMetadataAnalysisPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxiloplowering/#a8907c1ee9a102c2ec9a7895d352a7a6e">llvm::DXILOpLowering::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilprettyprinterpass/#a80163db1be8afd66500bc24bb7275747">llvm::DXILPrettyPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilresourceaccess/#a1d78f24c9cef5813c0cb9aea5b00b183">llvm::DXILResourceAccess::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilresourcebindingprinterpass/#a9c5f08a05826fa28ba48d255e06f1b97">llvm::DXILResourceBindingPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxiltranslatemetadata/#a11fd26b2f007c308546f237ba5918bc5">llvm::DXILTranslateMetadata::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilupgradepass/#abc0869ccaedd0cb2879db7c457fb0ac8">llvm::DXILUpgradePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/earlycsepass/#a1977dd7d302009cd95b32ad3a5dd8db6">llvm::EarlyCSEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/earlyifconverterpass/#a9f45d5f14e7be68f178eadf56bd84d25">llvm::EarlyIfConverterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/eliminateavailableexternallypass/#acb30ee5db432a603141e0f783643f5d1">llvm::EliminateAvailableExternallyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/embedbitcodepass/#a733d88adb5c9a8361ed07a8673514de5">llvm::EmbedBitcodePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/entryexitinstrumenterpass/#a01fcebccd3470faf07c176cd6934b7f7">llvm::EntryExitInstrumenterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/expandlargedivrempass/#ab3c55956a41284798a17daed1f2d3de2">llvm::ExpandLargeDivRemPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/expandlargefpconvertpass/#ac98aeadd0bb290c908220397e777c556">llvm::ExpandLargeFpConvertPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/expandreductionspass/#a9fea76fcf757718eb4aafcd72cb89038">llvm::ExpandReductionsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/expandvariadicspass/#a2be438827ecb51c62941f87fbd3c0b79">llvm::ExpandVariadicsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/extrafunctionpassmanager/#ae66709ae0e3be48ab315ad2ac6ae6fa7">llvm::ExtraFunctionPassManager&lt; MarkerTy &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/extralooppassmanager/#abc9e4c26ae75979993c43cbd6392104c">llvm::ExtraLoopPassManager&lt; MarkerTy &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/finalizeiselpass/#ad2c0689c7c7707da00dbf33e6e8614c1">llvm::FinalizeISelPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/fixirreduciblepass/#a61707c67652fa7e327bb8ac607164e09">llvm::FixIrreduciblePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/flattencfgpass/#ac48dd5c80bc3b98f2e2f5aa65117456f">llvm::FlattenCFGPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/float2intpass/#ad9900fbd867b1e73f7da240f0e7a28c1">llvm::Float2IntPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/forcefunctionattrspass/#a87517a35ede072d09d6c9889584780d5">llvm::ForceFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimportpass/#a4eb08e2a18ca18c8e8ee7d1a8d3de7f2">llvm::FunctionImportPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesprinterpass/#aac1f30e6e61c72eaa61dc3daf83dc588">llvm::FunctionPropertiesPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontomachinefunctionpassadaptor/#a1c8aea757190a42fd931c0d95a4f2721">llvm::FunctionToMachineFunctionPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/gcloweringpass/#aa642143ff84b39a1e644a6435f69b643">llvm::GCLoweringPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndppcombinepass/#a91369071e0136a16498790096d679182">llvm::GCNDPPCombinePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovprofilerpass/#abe3a54029a1d4094373deb485452f033">llvm::GCOVProfilerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/generictonvvmpass/#a0c8c7750ef98d7c7d7efdd45cdcf5775">llvm::GenericToNVVMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/globaldcepass/#ae98558816f50b4a9f6f7244b2deadd53">llvm::GlobalDCEPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/globalmergefuncpass/#a51a440937b3f08b15f896d0c11777a78">llvm::GlobalMergeFuncPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/globalmergepass/#a3f8ec211506240dc543433b4fda3d011">llvm::GlobalMergePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/globaloptpass/#a0be1afba37502be6858f2a1c38955be8">llvm::GlobalOptPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/globalsplitpass/#add1bf1b7eb3fab7b1e542411688c208d">llvm::GlobalSplitPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/guardwideningpass/#a13571b5fc50d701864f8b3de9b930b7f">llvm::GuardWideningPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/guardwideningpass/#a37a71785c3d451d302d2cb9e108f5424">llvm::GuardWideningPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/gvnhoistpass/#a73462db6e4114fd6c543b9b3de65a504">llvm::GVNHoistPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnpass/#a25dcf17194b012b2b35388798cac2da7">llvm::GVNPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/gvnsinkpass/#ae98a89808429d79b6d50dffe2109a2d6">llvm::GVNSinkPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/hardwareloopspass/#a7b139351e6b64d570e4ee5b7ece478ea">llvm::HardwareLoopsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/helloworldpass/#a70a8d28d6ffab19e8118ea202a0d028d">llvm::HelloWorldPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonloopidiomrecognitionpass/#ad008d67ca81f40a0890b9e0d69377ba7">llvm::HexagonLoopIdiomRecognitionPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonvectorloopcarriedreusepass/#a32948988705da5dd73dba608197477fc">llvm::HexagonVectorLoopCarriedReusePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/hotcoldsplittingpass/#a1428bc0c1945db2bcb0bc0b17447c18c">llvm::HotColdSplittingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/hwaddresssanitizerpass/#a0ab6bbfe1dc498f2c9a8603d672fbb1b">llvm::HWAddressSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrexpandpass/#af36e885f10703886f9001dd79432b77f">llvm::IndirectBrExpandPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/indvarsimplifypass/#a00bd6521a4f23d764d5d1403e7728e8f">llvm::IndVarSimplifyPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/inferaddressspacespass/#a8750fe658baa71eeba987c3bea8bf83e">llvm::InferAddressSpacesPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/inferalignmentpass/#ad5a046232f4066339175c677ff26b9f5">llvm::InferAlignmentPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/inferfunctionattrspass/#a43509c520610b43c4b366bee12dc1f4b">llvm::InferFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/injecttlimappings/#a132043059b6f75e1cdca29b58c58d872">llvm::InjectTLIMappings::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisoranalysisprinterpass/#af0f697cf524e464ace6a8652e4dbb128">llvm::InlineAdvisorAnalysisPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisoranalysisprinterpass/#ab6fd30da8bd8c6528e6bc9aa4c2f6633">llvm::InlineAdvisorAnalysisPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/inlinecostannotationprinterpass/#aa0abf6fac51bc051d817b1f71c921098">llvm::InlineCostAnnotationPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinesizeestimatoranalysisprinterpass/#a5e90152cff8dae138bbd12056eeb56ca">llvm::InlineSizeEstimatorAnalysisPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinepass/#aa1ffc7ad08181545bbc25eabac7f5aae">llvm::InstCombinePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instrorderfilepass/#a30a949f855bc23cc82f5e0d503131095">llvm::InstrOrderFilePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofilingloweringpass/#a610148cfab0328ada1642b17b9a9e71c">llvm::InstrProfilingLoweringPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/instructionnamerpass/#ab1441d48ca950f93ea762289bcaa19f4">llvm::InstructionNamerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instsimplifypass/#ad073cb9259c01c880086405f8776a106">llvm::InstSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavedaccesspass/#ae66f66ef855bdcccfe7802d81f9a816a">llvm::InterleavedAccessPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavedloadcombinepass/#abd04f9ee840b4323bdb0bffe6a02a5f6">llvm::InterleavedLoadCombinePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/internalizepass/#ac372346dd14c9889c13a849269751d8b">llvm::InternalizePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/invalidateanalysispass/#a935620d91529983e8e139ceb8532b5cb">llvm::InvalidateAnalysisPass&lt; AnalysisT &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ipsccppass/#a7c77a408787021dc65c12646cee2ac43">llvm::IPSCCPPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ircepass/#ac7e45d3f509c7e40c4d6666a24e88f73">llvm::IRCEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/iroutlinerpass/#a5b9a8fe2c3b6834817b2c12b08441cff">llvm::IROutlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarityanalysisprinterpass/#a8dde7acadd30b1860704841855a1a07d">llvm::IRSimilarityAnalysisPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ivusersprinterpass/#acaca26216fbb3760b644841037f422d7">llvm::IVUsersPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/jmcinstrumenterpass/#a5d2aeb7f2893f237f1662e2f9cc19eb5">llvm::JMCInstrumenterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/jumptabletoswitchpass/#a84778fc53894f05e88ce0cc794561742">llvm::JumpTableToSwitchPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a48dd43ef05b66261790497edbdac92d9">llvm::JumpThreadingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/kcfipass/#a19dcb564cb3c8a4de327c6f9cabed5b3">llvm::KCFIPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraphdotprinterpass/#a172985546be95f992c665ac5d82e4a08">llvm::LazyCallGraphDOTPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraphprinterpass/#a2860c75599e4f96204b58e3c3be96dfe">llvm::LazyCallGraphPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfoprinterpass/#ab0c9c93431b62e36767c973517bf1733">llvm::LazyValueInfoPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lcssapass/#a7ae4df8ff3ca478772f6f055bf88bd1f">llvm::LCSSAPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/libcallsshrinkwrappass/#ae988b0b1818ad722c8cfae3a649223c0">llvm::LibCallsShrinkWrapPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/licmpass/#aa540c3d95adfef29cc520491ce4ebdab">llvm::LICMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lintpass/#a414d1a9e191f52da209fd34c264a0cd4">llvm::LintPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/livedebugvariablesprinterpass/#ab768a4034fa150ccf9784887c90ea58c">llvm::LiveDebugVariablesPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalsprinterpass/#a27fc3994cdeaf984273c9ec315423631">llvm::LiveIntervalsPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/livestacksprinterpass/#aa3bb974f54082b4cda61faff8b9756c0">llvm::LiveStacksPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariablesprinterpass/#a9b4943b4e128bc059ad8261448328184">llvm::LiveVariablesPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lnicmpass/#a1ddd3ffe6782be6b893dcf33dcf4e3c0">llvm::LNICMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loadstorevectorizerpass/#a78465c41b72ca43acdbbfc47cbce3d76">llvm::LoadStoreVectorizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/localstackslotallocationpass/#ac01bf972899174b034f940c498e28f07">llvm::LocalStackSlotAllocationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfoprinterpass/#ac64f34186e4e16d5b0baca6d232c810d">llvm::LoopAccessInfoPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopboundsplitpass/#a488751cbcea1a2e3da39c4e67ecfd98c">llvm::LoopBoundSplitPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopcacheprinterpass/#aa35925026f576bd3c47e2f91cd2eb737">llvm::LoopCachePrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopdataprefetchpass/#af1020d68a0e1a023973890cf0e079c28">llvm::LoopDataPrefetchPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopdeletionpass/#adc91b7d6d8d4770240d4cce7adf7fb01">llvm::LoopDeletionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopdistributepass/#ab4ccb40cf0dd5fd358dd5e0f0d4d7c6f">llvm::LoopDistributePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/loopextractorpass/#ac1cd83190da80057c6903402d80cc1f7">llvm::LoopExtractorPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopflattenpass/#af1670b8924fecfd8a7f0c4dc140bf603">llvm::LoopFlattenPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopfullunrollpass/#aacf97677dabaa7e583a690244bde44ea">llvm::LoopFullUnrollPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopfusepass/#a971f40ada3f1410759faede02bfbace7">llvm::LoopFusePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopidiomrecognizepass/#a4a3aed1996ede85e98aa361e6f5d74a2">llvm::LoopIdiomRecognizePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopidiomvectorizepass/#a0b63cb3362045110398f3faf3ddbee74">llvm::LoopIdiomVectorizePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinstsimplifypass/#a3e829edc978ccb3a88ff5532faf75879">llvm::LoopInstSimplifyPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/loopinterchangepass/#a99a46045e2cc7182d6a786d400604d76">llvm::LoopInterchangePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/looploadeliminationpass/#af81bad0018d7e67a1c92d785305426b0">llvm::LoopLoadEliminationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopnestprinterpass/#aaf9544eaca7fe1e7b473639f38a3b094">llvm::LoopNestPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looppredicationpass/#ae0a08563a94fcfe8107a3d45564b881e">llvm::LoopPredicationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopprinterpass/#accccc20ac629c11b33de7dcb9fbc8449">llvm::LoopPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looprotatepass/#aa87b74697e2ab3e760eddd32b866c508">llvm::LoopRotatePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsimplifycfgpass/#a6080bbb0e8e74dbaf955a64f844978a4">llvm::LoopSimplifyCFGPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsimplifypass/#a294bd885b054adcb86315a9112ea0b33">llvm::LoopSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsinkpass/#a11eda417d0372700a9b48e41f267ab92">llvm::LoopSinkPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopstrengthreducepass/#a4e475c0fcd6ade09109db20acb073a77">llvm::LoopStrengthReducePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/looptermfoldpass/#abefaee9143bf56e20b254a2f9a1bae56">llvm::LoopTermFoldPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopunrollandjampass/#aceae0aba9cc69bf89d3241d61190b9ec">llvm::LoopUnrollAndJamPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopunrollpass/#a62ed17cf8aa893362e6c3c1f6d8a0898">llvm::LoopUnrollPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#af3b0e58cfdb2c6c663cd47a8808ba70a">llvm::LoopVectorizePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/loopverifierpass/#ac0ce536f08ade507773b16d2ceb9e8d1">llvm::LoopVerifierPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopversioninglicmpass/#ac248c8958e091a1497a9b5ca728e4e78">llvm::LoopVersioningLICMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopversioningpass/#ab85aee23551eb41e8d1d7e01e1fd3f98">llvm::LoopVersioningPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lowerallowcheckpass/#a0333cadd9ec11ea319d1fd3d3e0e6f05">llvm::LowerAllowCheckPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loweratomicpass/#aa6367f2b0be097467a383973068b444e">llvm::LowerAtomicPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/lowerconstantintrinsicspass/#ab82707f4044f916e7c0ce1955b987cba">llvm::LowerConstantIntrinsicsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loweremutlspass/#aa02b6a6722504e6fb7a176a81fc5d49c">llvm::LowerEmuTLSPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/lowerexpectintrinsicpass/#afb59e74c5181b5a9fa8d58780be0699a">llvm::LowerExpectIntrinsicPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lowerglobaldtorspass/#a8895fb3cf22b753143095a1552ca974a">llvm::LowerGlobalDtorsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/lowerguardintrinsicpass/#a4ba7c788e41caef18b1c9c8f7fbfcdcc">llvm::LowerGuardIntrinsicPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lowerifuncpass/#afa57ad3cdcdc6ae559bb8444e407665a">llvm::LowerIFuncPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lowerinvokepass/#a13431158a9ef331dddfb0484b37f7bee">llvm::LowerInvokePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lowermatrixintrinsicspass/#a7b05a9de14294b7a5a7904cc8d5c8e1e">llvm::LowerMatrixIntrinsicsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/lowerswitchpass/#a7ed296f67da3966a7e2c0dd6f4fbcf9e">llvm::LowerSwitchPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lowertypetestspass/#af14b972caecee35ee8e3a66b85ea3842">llvm::LowerTypeTestsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/lowerwidenableconditionpass/#af8574e7bcb8abe98879ae5a8cbf1f0c5">llvm::LowerWidenableConditionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyprinterpass/#aa35b27316428c32c7d320f53174fdbd5">llvm::MachineBlockFrequencyPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityprinterpass/#a7aef24d9b265073b477cd3781bb733ef">llvm::MachineBranchProbabilityPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machinecsepass/#a495f06046288f4b8207cd36d72d19939">llvm::MachineCSEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortreeprinterpass/#adba4d4be92ffca419c2d16979f1c6d11">llvm::MachineDominatorTreePrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machinelicmbasepass/#a32a6c3c28482b75adeee98d1abf60ff9">llvm::MachineLICMBasePass&lt; DerivedT, PreRegAlloc &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloopprinterpass/#ab87752c40887e452b51a8300347641de">llvm::MachineLoopPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortreeprinterpass/#a3979191544a4fa418cb6332df5edd481">llvm::MachinePostDominatorTreePrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetricsverifierpass/#a6ba933eae8cb10287475af486e7b1602">llvm::MachineTraceMetricsVerifierPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machineverifierpass/#a8f6669235c21d5e639d04b8859f74d95">llvm::MachineVerifierPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/makeguardsexplicitpass/#a025fe5043bbaa6412a601f3f8f9bbf17">llvm::MakeGuardsExplicitPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memcpyoptpass/#a07c3f5129a977e2f949212878c3042ae">llvm::MemCpyOptPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memderefprinterpass/#a9643b91d2f4e79487e5b260eb11fef74">llvm::MemDerefPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/memorysanitizerpass/#adfd94cfcef9d896734905bd5a18a05df">llvm::MemorySanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaprinterpass/#ab228481c477a8f642742650e2f03c231">llvm::MemorySSAPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/memoryssaverifierpass/#a5fa2dbea1ad6cf5950da7d2a642a73bd">llvm::MemorySSAVerifierPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssawalkerprinterpass/#a9982e0fb4d45bbefee3aa1a790306610">llvm::MemorySSAWalkerPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memprofcontextdisambiguation/#ac43814024a542d89728f88411b553e6d">llvm::MemProfContextDisambiguation::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memprofilerpass/#a9da61a3f33d95e94a03f2b2431100492">llvm::MemProfilerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memprofusepass/#a301e9c18f7576c32229ca4c2a06fb8e4">llvm::MemProfUsePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/mergedloadstoremotionpass/#af9d31b63718e1ad6d4e0881e49a415bd">llvm::MergedLoadStoreMotionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/mergefunctionspass/#ad0198e9945bcf4a17c56e124e7e804ed">llvm::MergeFunctionsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/mergeicmpspass/#a96cfc6defc256b49f69f6fb8bfbf8c87">llvm::MergeICmpsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/metarenamerpass/#a1f547e81e18e412faa9f0a8a71cbd90c">llvm::MetaRenamerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduledebuginfoprinterpass/#a0c14bc5fba5000829a981ee9a17d00be">llvm::ModuleDebugInfoPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#ab7155781c9a6aafef322de28d9bc4c86">llvm::ModuleInlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/modulememprofilerpass/#a1f56cd341951380da3dc0a019a5b4a3e">llvm::ModuleMemProfilerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/modulethreadsanitizerpass/#adf10c75c773504153d27d41a73ad2223">llvm::ModuleThreadSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#a0ff99def687659818bdb4a25afd82c94">llvm::ModuleToPostOrderCGSCCPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moveautoinitpass/#a55a3f992f62d23ae617927c2de5a81c9">llvm::MoveAutoInitPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/mustbeexecutedcontextprinterpass/#a1b1a19034ac7bbb0481e54e850fc431a">llvm::MustBeExecutedContextPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/mustexecuteprinterpass/#ac776766336198f23f11dc141cd0278d7">llvm::MustExecutePrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/nameanonglobalpass/#a182eb1220b11d52d74537fada176af97">llvm::NameAnonGlobalPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/naryreassociatepass/#a44a686152f979478fbbac82b70bf85fb">llvm::NaryReassociatePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/newgvnpass/#a6b1b7ab1a677eb8039694b4dfe6cb997">llvm::NewGVNPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/noopcgsccpass/#a1c0d06a2f0e4699324b2f82ee93fe193">llvm::NoOpCGSCCPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/noopfunctionpass/#a41d3b617d5b30423f8d2c59f32e77ae0">llvm::NoOpFunctionPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/nooploopnestpass/#af81517f704a2597a770a891160cb4e7d">llvm::NoOpLoopNestPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/nooplooppass/#a6a626ab781872fa960b1eb4f627a785a">llvm::NoOpLoopPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/noopmachinefunctionpass/#a9dc0f2386bb66e777b6591e36de7e284">llvm::NoOpMachineFunctionPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/noopmodulepass/#af747ee5d58536bac3e4c102dbcdeba25">llvm::NoOpModulePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/nvptxcopybyvalargspass/#adaee1fbeeb30f3f025c55c5f2d5e5ac9">llvm::NVPTXCopyByValArgsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxctordtorloweringpass/#a86b98247d644f6dd257de453f3802561">llvm::NVPTXCtorDtorLoweringPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/nvvmintrrangepass/#ac9fd2e59a5ad190662e1b0167fa2f2fc">llvm::NVVMIntrRangePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/nvvmreflectpass/#a5362d88cc699f98ddfbc4b004926c80d">llvm::NVVMReflectPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarcapelimpass/#ae4e95bbaf8d3c3a8b8df38c406a73030">llvm::ObjCARCAPElimPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarccontractpass/#a37aa96fbe116641ca7204a785341c962">llvm::ObjCARCContractPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarcexpandpass/#afec00b95aa5fccab1101e69496207a4a">llvm::ObjCARCExpandPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarcoptpass/#a02b31ca54388bfecbdd6593b7563d146">llvm::ObjCARCOptPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpoptcgsccpass/#a9d4366d9c2f6de53d6f2edce548577ab">llvm::OpenMPOptCGSCCPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpoptpass/#ad0812a5ba88f8645505134a108f639b2">llvm::OpenMPOptPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/paevalpass/#a7f0dda30879f62ea4eefdc53cfbb0e1d">llvm::PAEvalPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/partialinlinerpass/#a022b0aa595cef197b5b0c655cd18ad9c">llvm::PartialInlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/partiallyinlinelibcallspass/#a0e2ff100989ce66c294cfe38904c6cf1">llvm::PartiallyInlineLibCallsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#aef5d9142acafceffd14c76b8ddd0fd4e">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a6d74effaad77f6ecb91e1806993cda8f">llvm::PassManager&lt; LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp; &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/peepholeoptimizerpass/#a80af47b78e07ddb33af6e7d86af034df">llvm::PeepholeOptimizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoctxprofloweringpass/#a7ad703c2051de4321f9ef0d082a9c906">llvm::PGOCtxProfLoweringPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/pgoforcefunctionattrspass/#a5a7425ff46058c5adf7da1d9a58c4000">llvm::PGOForceFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoindirectcallpromotion/#a5017234dfda3310cbcae123e5a4de31a">llvm::PGOIndirectCallPromotion::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoinstrumentationgen/#a9cff4300652b1ae7f59c26011099ac65">llvm::PGOInstrumentationGen::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoinstrumentationuse/#a11847c7e88a21b5076fb1cb5e2f7f5e1">llvm::PGOInstrumentationUse::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgomemopsizeopt/#a01227f37509d10916de26411ab363d6b">llvm::PGOMemOPSizeOpt::run</a>, <a href="/web-llvm/docs/api/classes/llvm/phieliminationpass/#a950967d5a5e1ca4937a5e5c37ed466b4">llvm::PHIEliminationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/phivaluesprinterpass/#a21d9889708699714c41846b90164e285">llvm::PhiValuesPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/physicalregisterusageinfoprinterpass/#ac906046b0d9451273e8073b46cdfa74c">llvm::PhysicalRegisterUsageInfoPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/placesafepointspass/#a4c1a6d3206d9f1278836bdc314e56141">llvm::PlaceSafepointsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/postdominatortreeprinterpass/#a5a8a80e5f89a52ac0fb8e2ee24c3960b">llvm::PostDominatorTreePrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/postorderfunctionattrspass/#a8312d250d0f7b4407b4bad97293e5865">llvm::PostOrderFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/predicateinfoprinterpass/#a3d2162a259a40a3c7fecd27694e24a8d">llvm::PredicateInfoPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/predicateinfoverifierpass/#aa6365590a30ab595458b49c30b231661">llvm::PredicateInfoVerifierPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/preiselintrinsicloweringpass/#a6c4bdf5cd38f45ec8052f395f32f63ee">llvm::PreISelIntrinsicLoweringPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/printfunctionpass/#a5d4b836698202124122a0ee03d37b3e8">llvm::PrintFunctionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/printlooppass/#adbcefe621f9a4ceda788c648c59581cf">llvm::PrintLoopPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/printmirpass/#a354177020e92f5ab2dd0433a47123270">llvm::PrintMIRPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/printmirpreparepass/#a4215094f939e79bd1cb4ac7b26d3e185">llvm::PrintMIRPreparePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/printmodulepass/#abb1b61a3833aedd2fa62272bfd6740f3">llvm::PrintModulePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryprinterpass/#aff1db3108eff5862498fecfa0d419d72">llvm::ProfileSummaryPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/promotepass/#aca8a105910e7bb81285435f553e71872">llvm::PromotePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/reassociatepass/#aadf6b90fc920d89751c191799ff3e6ea">llvm::ReassociatePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/recomputeglobalsaapass/#abd209c0e2c06b211cbd147ad96b70890">llvm::RecomputeGlobalsAAPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/redundantdbginsteliminationpass/#aae0280e54f28cf0e183b7a6f64a0f2fa">llvm::RedundantDbgInstEliminationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocfastpass/#a8e1ca8e01852af346174b94ad5d8630c">llvm::RegAllocFastPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/regioninfoprinterpass/#a226463c4c73a0f1fc36d8d3256911f72">llvm::RegionInfoPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/regioninfoverifierpass/#a9e4421b3ea5f943378bff6877592acf2">llvm::RegionInfoVerifierPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/regtomempass/#a0a8fbb23329369eafe88acc194f6336d">llvm::RegToMemPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/regusageinfocollectorpass/#a387db9c3806e18b7691b075381d0ac09">llvm::RegUsageInfoCollectorPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/regusageinfopropagationpass/#ab365c22ad0becb1f9a4f0fc2d85f088f">llvm::RegUsageInfoPropagationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/rellookuptableconverterpass/#a3b1519f165c877970b589c9f53db69eb">llvm::RelLookupTableConverterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/replacewithveclib/#ac03e0f62c8cbbdd055546686f847183c">llvm::ReplaceWithVeclib::run</a>, <a href="/web-llvm/docs/api/structs/llvm/requireanalysispass/#ab43e4aa43606bb4fd7ce7575f2c075f5">llvm::RequireAnalysisPass&lt; AnalysisT, IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::run</a>, <a href="/web-llvm/docs/api/structs/llvm/requireanalysispass-498ca4f351a1bdb57b4c30b5c00bae4c/#a43a2aa154e25aa344a01ca757898b787">llvm::RequireAnalysisPass&lt; AnalysisT, LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp; &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/reversepostorderfunctionattrspass/#a711463cdc12e518aaca8c394a0f82139">llvm::ReversePostOrderFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/rewritestatepointsforgc/#af56b6dd2da7f65fa682eaf6a16cdb36a">llvm::RewriteStatepointsForGC::run</a>, <a href="/web-llvm/docs/api/classes/llvm/rewritesymbolpass/#a3a676b28a8e2daaf300ad9c5e3776c33">llvm::RewriteSymbolPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/safepointirverifierpass/#af94bb71714afbf2f143e6535c8264e56">llvm::SafepointIRVerifierPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/safestackpass/#a7a84d5b29faf6a5ce458e61ac1f79cab">llvm::SafeStackPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderpass/#a324d3696b255beea7cfd1e8b901b2363">llvm::SampleProfileLoaderPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxvectorizerpass/#a551ef06f642e5ab4d0e22806eb5bb4ac">llvm::SandboxVectorizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sanitizerbinarymetadatapass/#a4c4b3aea1ab9cc4a61033672c29e3c69">llvm::SanitizerBinaryMetadataPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sanitizercoveragepass/#a93d554aebdab8ad87f41ba8e07f73cad">llvm::SanitizerCoveragePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolutionprinterpass/#a5701836bcbb5fc1663cbaf72ea475bc0">llvm::ScalarEvolutionPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolutionverifierpass/#a922e2e00f7528f19fdece7de80099fc2">llvm::ScalarEvolutionVerifierPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/scalarizemaskedmemintrinpass/#ab805176ab5d08e2a34fadbc760bca5a6">llvm::ScalarizeMaskedMemIntrinPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarizerpass/#a250da10ea723b93bcd9f52cd0bca4d7e">llvm::ScalarizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sccppass/#ad9201f5b1be7f1b9cbff7b2b631b2256">llvm::SCCPPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagiselpass/#afbe031a5b54a7910faf25270aeeac0dc">llvm::SelectionDAGISelPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/separateconstoffsetfromgeppass/#a949e76f284f0977c83f729850a8b8a8b">llvm::SeparateConstOffsetFromGEPPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/shadowstackgcloweringpass/#a2053b340bf34047264af3190e9473953">llvm::ShadowStackGCLoweringPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/siannotatecontrolflowpass/#a84e9204f8b261089c66706e2941ee6da">llvm::SIAnnotateControlFlowPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sifixsgprcopiespass/#aa09db25356e6c1389f8c477c5555e298">llvm::SIFixSGPRCopiesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sifixvgprcopiespass/#af53c1d1201cca2f07c319251fb5bd8c8">llvm::SIFixVGPRCopiesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sifoldoperandspass/#a4a67d4ac73489afb2251111f326fbfba">llvm::SIFoldOperandsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/siloadstoreoptimizerpass/#a73bd665c6e03c1dc196c107a450e228a">llvm::SILoadStoreOptimizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/silowercontrolflowpass/#a8b4643be70785c8f090659b3ab19d73e">llvm::SILowerControlFlowPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/siloweri1copiespass/#a0af1fadc28e71aac6e7e74c59686a02b">llvm::SILowerI1CopiesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/silowersgprspillspass/#acc251fdad2ff98bf8f116ecbd8e93b14">llvm::SILowerSGPRSpillsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/silowerwwmcopiespass/#a8190b1c16b87f7d2ff20607bc4efb554">llvm::SILowerWWMCopiesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleloopunswitchpass/#ae7088b7b5c8bd069497f13e3e1990eff">llvm::SimpleLoopUnswitchPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/simplifycfgpass/#a1196be608a7f568e9cb19fe11f80ebe2">llvm::SimplifyCFGPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sinkingpass/#a07a25f4cfc32581da84eea1e0ced7f2e">llvm::SinkingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sioptimizeexecmaskingpass/#a75a5c4fad6c8da9f5925c9d0751a7b13">llvm::SIOptimizeExecMaskingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sioptimizevgprliverangepass/#a7bf8baafeef111584b003c06f997080a">llvm::SIOptimizeVGPRLiveRangePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sipeepholesdwapass/#af333339d4156056152073cbe27eb1887">llvm::SIPeepholeSDWAPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sipreallocatewwmregspass/#ae0b2123e3a8afffcdfc0e364d088f39a">llvm::SIPreAllocateWWMRegsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sishrinkinstructionspass/#aef43f9ae6fbd079affe6f0f2a07d034e">llvm::SIShrinkInstructionsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sjljehpreparepass/#a495925d0983e66d028a72e6b6748f072">llvm::SjLjEHPreparePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexesprinterpass/#afedda4628bf652e8255f1e6a6378d744">llvm::SlotIndexesPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/slpvectorizerpass/#aaec443311cb572adf0e2db9db82279ef">llvm::SLPVectorizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/speculativeexecutionpass/#a75693e29732ce9935478d5fdc533c67d">llvm::SpeculativeExecutionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvstructurizerwrapper/#abd2d6184a5dcf12b75b70b9f315e8389">llvm::SPIRVStructurizerWrapper::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sroapass/#a6cca3e145c2eb9050c6b4b94e2f760a0">llvm::SROAPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/stackcoloringpass/#a693535db98527be92419386a4baba10a">llvm::StackColoringPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/stacklifetimeprinterpass/#a7d1ec1183162820291a3dcc9a0e81d45">llvm::StackLifetimePrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/stackprotectorpass/#af99d23fe1a6d3d9ebfdf9fa3a101830a">llvm::StackProtectorPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/stacksafetyglobalprinterpass/#ac43f3f00ee89cc0fd16d5ba5323eef37">llvm::StackSafetyGlobalPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/stacksafetyprinterpass/#a418ed81d84497654db26995150b7c57a">llvm::StackSafetyPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/straightlinestrengthreducepass/#a40a452b8f3a3f5538eed5201e5bfdcc4">llvm::StraightLineStrengthReducePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/stripdeadprototypespass/#a5e06b34c5e5ae5f1fe88b71b05d0dfda">llvm::StripDeadPrototypesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/stripgcrelocates/#aaa7527b13944005e12d9f2ebf6a2c8a3">llvm::StripGCRelocates::run</a>, <a href="/web-llvm/docs/api/classes/llvm/structuralhashprinterpass/#afe15599f186ed0311708ffe7f629d374">llvm::StructuralHashPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/structurizecfgpass/#aeb3e7a1f92ba7129a43fdfe85ea9c000">llvm::StructurizeCFGPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/tailcallelimpass/#ab754a2815f5333ff5f443593896814dc">llvm::TailCallElimPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicatepassbase/#a0780ac5d6a2962adf46e1c611e6ca6fa">llvm::TailDuplicatePassBase&lt; DerivedT, PreRegAlloc &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/thinltobitcodewriterpass/#a407be825a5084267d383681109e30df9">llvm::ThinLTOBitcodeWriterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/threadsanitizerpass/#a554dea073d38539bd97dbb495225a24b">llvm::ThreadSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/twoaddressinstructionpass/#ab9a6f420b6121320d58d159773b8d92a">llvm::TwoAddressInstructionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/typepromotionpass/#addcc6ab5729a0a8e495cdc585f02234c">llvm::TypePromotionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/uniformityinfoprinterpass/#a60f393028e23ebd547f6b141ccb51c43">llvm::UniformityInfoPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/unifyfunctionexitnodespass/#adaf7a178b197e2db5058103a6cb525fb">llvm::UnifyFunctionExitNodesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/unifyloopexitspass/#afa18953dc3062e2c68866c9065b12bcb">llvm::UnifyLoopExitsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/unreachableblockelimpass/#a9941546788895103d10cdd0cfabe968c">llvm::UnreachableBlockElimPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/vectorcombinepass/#a6a1e4cac923bd64f58cb782f1a5ba91a">llvm::VectorCombinePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/verifierpass/#a27b98c15f4931023c6e5f739d9df2a02">llvm::VerifierPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/verifierpass/#a6112c8ef2aa7acf00aa9b0ce02eb3711">llvm::VerifierPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmapprinterpass/#a101be45b1a9d89ebbd7df78a0f9ffa85">llvm::VirtRegMapPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/warnmissedtransformationspass/#aa622d589f82389844d93eca02d865d4c">llvm::WarnMissedTransformationsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtpass/#af94d9399906155205bf6afa17427d5c7">llvm::WholeProgramDevirtPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/winehpreparepass/#a6e2da040c0d9056bb599c15b61a4a379">llvm::WinEHPreparePass::run</a>, <a href="/web-llvm/docs/api/classes/newpmcheckdebugifypass/#adb7be1f4b6e4efe53465ff24bc980b5a">NewPMCheckDebugifyPass::run</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-expandmemcmp-cpp-/#a1ed6e9933878fa5790bdacff6d5a907b">anonymous{ExpandMemCmp.cpp}::runImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#ab31c9b14b5bd6245b789fb6ed28a7aeb">updateNewSCCFunctionAnalyses</a>.</p>

</div>
</div>

### allInSet() {#aea87afbe4520fdc60652c554501f5cdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisSetT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses llvm::PreservedAnalyses::allInSet ()</td>
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

<p>Construct a preserved analyses object with a single preserved set.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>


<p>Reference <a href="#a937c42f77e161349ce0f999e448c7027">preserveSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#aa64f6bcd5ace031369edc14aa406d745">incorporateNewSCCRange</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#a490117b63072462d035a6933fdb94c1f">updateCGAndAnalysisManagerForPass</a>.</p>

</div>
</div>

### none() {#a03797a73044a81cbc6a3409d6c72ee8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses llvm::PreservedAnalyses::none ()</td>
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

<p>Convenience factory function for the empty preserved set.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-alwaysinliner-cpp-/#af5bb12426b6361914b816365eee4b4fd">anonymous{AlwaysInliner.cpp}::AlwaysInlineImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-passbuilder-cpp-/requireallmachinefunctionpropertiespass/#ab20042dac1f44de9b970b8c05fc0bc8d">anonymous{PassBuilder.cpp}::RequireAllMachineFunctionPropertiesPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-passbuilder-cpp-/triggerverifiererrorpass/#aa6e4c71c550683bb7d117491b717e2d1">anonymous{PassBuilder.cpp}::TriggerVerifierErrorPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-passbuilder-cpp-/triggerverifiererrorpass/#ada1d133949e3d808f4e13f5cadf21495">anonymous{PassBuilder.cpp}::TriggerVerifierErrorPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectoptimize-cpp-/selectoptimizeimpl/#ae454ad67b6e4fa9846a5395dc76759d6">anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::run</a>, <a href="/web-llvm/docs/api/classes/llvm/adddiscriminatorspass/#a7c89dac3d04b8cda0fe7586df5429d28">llvm::AddDiscriminatorsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/addresssanitizerpass/#a987afb1c68c5891e0b9a67cdac48147d">llvm::AddressSanitizerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpualwaysinlinepass/#aae20ee2a6a4ad198fc7b74d1a5a726c0">llvm::AMDGPUAlwaysInlinePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuannotateuniformvaluespass/#ad40e073c46402aba328eb57891116b74">llvm::AMDGPUAnnotateUniformValuesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuattributorpass/#a6b853868668b480de1fb9a5638185bbf">llvm::AMDGPUAttributorPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucodegenpreparepass/#a09ffc2a128b37269498bbcabc7f145d4">llvm::AMDGPUCodeGenPreparePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuctordtorloweringpass/#ad4e5fca7d7b0ff779714b3827d0b5ae9">llvm::AMDGPUCtorDtorLoweringPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuimageintrinsicoptimizerpass/#a11860dd752695b8560ec59e4459f1417">llvm::AMDGPUImageIntrinsicOptimizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulatecodegenpreparepass/#a5a4ff24504b852091b900d036f556885">llvm::AMDGPULateCodeGenPreparePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpulowerbufferfatpointerspass/#a629f4e8b3eddebb7df9b92172a9025b1">llvm::AMDGPULowerBufferFatPointersPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpulowermoduleldspass/#a76be940af9a6ce8a688affa5368cd3cb">llvm::AMDGPULowerModuleLDSPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuopenclenqueuedblockloweringpass/#ae8399e5456f80b9b739058cc30df10f3">llvm::AMDGPUOpenCLEnqueuedBlockLoweringPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupreloadkernargprologpass/#a0f5aef9a9f098c2144b9ac4e62675666">llvm::AMDGPUPreloadKernArgPrologPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuprintfruntimebindingpass/#a04bc7056720bebea77cc9fcab42aecc3">llvm::AMDGPUPrintfRuntimeBindingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuremoveincompatiblefunctionspass/#ac67b2b8b03c9e7cecf703fd30abb485e">llvm::AMDGPURemoveIncompatibleFunctionsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpusimplifylibcallspass/#ae83c4c6a3cf049dbac4ce40c2fa476dd">llvm::AMDGPUSimplifyLibCallsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusplitmodulepass/#a5fdf4ead69288861f3151e0f035a9877">llvm::AMDGPUSplitModulePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuunifydivergentexitnodespass/#a3e73b9a5c7212271285ef6c38d1cd26d">llvm::AMDGPUUnifyDivergentExitNodesPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuunifymetadatapass/#a538284b7129994222827deed13f792cc">llvm::AMDGPUUnifyMetadataPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuusenativecallspass/#a153430907ef218b9118d28f077a5dd78">llvm::AMDGPUUseNativeCallsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/annotation2metadatapass/#aa7680281613fde3b2326fc67b34dbcd9">llvm::Annotation2MetadataPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/assignguidpass/#aa89d9261590d9a6a45bb5a02e907c32c">llvm::AssignGUIDPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicexpandpass/#ae932e2c8ae7317381567ef80224874d5">llvm::AtomicExpandPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorpass/#aba65d47dce0a15a90eb4e519ffc4929c">llvm::AttributorPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/blockextractorpass/#a9be62d1c1fc68905037c91b681e7a329">llvm::BlockExtractorPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/boundscheckingpass/#aaeef3ef960131b08e172917320b9507d">llvm::BoundsCheckingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfabstractmemberaccesspass/#a6dc0d5add9dd3e49bf053ce9eed7a998">llvm::BPFAbstractMemberAccessPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfadjustoptpass/#a24d58eb05b954d419e136f326ec3b8cd">llvm::BPFAdjustOptPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfaspacecastsimplifypass/#a76364c57022d89ac618f1b1e22bef6e2">llvm::BPFASpaceCastSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfirpeepholepass/#abf9fca0eab24cbc96c2d0c2c2a1438a4">llvm::BPFIRPeepholePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfpreserveditypepass/#ae1e68a4457f7157f360590db8094edc4">llvm::BPFPreserveDITypePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfpreservestaticoffsetpass/#aef25d4cdefd91999a61e1854ea64b148">llvm::BPFPreserveStaticOffsetPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalizealiasespass/#adbebb133afffe58930e8681d47c2b071">llvm::CanonicalizeAliasesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cfguardpass/#a0d01e5f89b3ff7eb3f081f3ec59d27bb">llvm::CFGuardPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cgscctofunctionpassadaptor/#a44a083f826f2f2a189d3979eb43dd5ed">llvm::CGSCCToFunctionPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/constantmergepass/#aea5f79617ea5595171a5ce5d3deac6b4">llvm::ConstantMergePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/controlheightreductionpass/#aa07878663a309c8f4a4537b971c6d3b0">llvm::ControlHeightReductionPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/coroannotationelidepass/#a411202dc502ac666302ba81c40e94b10">llvm::CoroAnnotationElidePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/corocleanuppass/#ad94b3bcb5dea38b6b7d891fa9344322c">llvm::CoroCleanupPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/coroelidepass/#a6dfdc223099c4ca952c8b0369027e34d">llvm::CoroElidePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/corosplitpass/#a47f6589634ad33a13369ace133b9f4b2">llvm::CoroSplitPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/crossdsocfipass/#a4dfd6efbe42e2fe46955cce4d9bbc8ef">llvm::CrossDSOCFIPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dataflowsanitizerpass/#a763709e61e42f6df707528b509adf8de">llvm::DataFlowSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/deadargumenteliminationpass/#a29ba94ac3af7390af4fa3209e6647732">llvm::DeadArgumentEliminationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilfinalizelinkage/#af624c56c0240734e52623e85d262ba7d">llvm::DXILFinalizeLinkage::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilintrinsicexpansion/#a8c44e930b068104f227b3c1b0f4f3151">llvm::DXILIntrinsicExpansion::run</a>, <a href="/web-llvm/docs/api/classes/llvm/eliminateavailableexternallypass/#acb30ee5db432a603141e0f783643f5d1">llvm::EliminateAvailableExternallyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/expandlargedivrempass/#ab3c55956a41284798a17daed1f2d3de2">llvm::ExpandLargeDivRemPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/expandlargefpconvertpass/#ac98aeadd0bb290c908220397e777c556">llvm::ExpandLargeFpConvertPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/expandvariadicspass/#a2be438827ecb51c62941f87fbd3c0b79">llvm::ExpandVariadicsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/extractgvpass/#aa8ccdb19bbe28d226592a236b93311e8">llvm::ExtractGVPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/flattencfgpass/#ac48dd5c80bc3b98f2e2f5aa65117456f">llvm::FlattenCFGPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/forcefunctionattrspass/#a87517a35ede072d09d6c9889584780d5">llvm::ForceFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimportpass/#a4eb08e2a18ca18c8e8ee7d1a8d3de7f2">llvm::FunctionImportPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovprofilerpass/#abe3a54029a1d4094373deb485452f033">llvm::GCOVProfilerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/generictonvvmpass/#a0c8c7750ef98d7c7d7efdd45cdcf5775">llvm::GenericToNVVMPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/globaldcepass/#ae98558816f50b4a9f6f7244b2deadd53">llvm::GlobalDCEPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/globalmergefuncpass/#a51a440937b3f08b15f896d0c11777a78">llvm::GlobalMergeFuncPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/globaloptpass/#a0be1afba37502be6858f2a1c38955be8">llvm::GlobalOptPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/globalsplitpass/#add1bf1b7eb3fab7b1e542411688c208d">llvm::GlobalSplitPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/gvnsinkpass/#ae98a89808429d79b6d50dffe2109a2d6">llvm::GVNSinkPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/hipstdparacceleratorcodeselectionpass/#a3c59b50e60a44b5fa3871d0449aa4744">llvm::HipStdParAcceleratorCodeSelectionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/hipstdparallocationinterpositionpass/#afd2b9166ec33a01dbc79faa6b1b095b1">llvm::HipStdParAllocationInterpositionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/hotcoldsplittingpass/#a1428bc0c1945db2bcb0bc0b17447c18c">llvm::HotColdSplittingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/hwaddresssanitizerpass/#a0ab6bbfe1dc498f2c9a8603d672fbb1b">llvm::HWAddressSanitizerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/inferfunctionattrspass/#a43509c520610b43c4b366bee12dc1f4b">llvm::InferFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instrorderfilepass/#a30a949f855bc23cc82f5e0d503131095">llvm::InstrOrderFilePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofilingloweringpass/#a610148cfab0328ada1642b17b9a9e71c">llvm::InstrProfilingLoweringPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavedloadcombinepass/#abd04f9ee840b4323bdb0bffe6a02a5f6">llvm::InterleavedLoadCombinePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/internalizepass/#ac372346dd14c9889c13a849269751d8b">llvm::InternalizePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/invalidateallanalysespass/#a26d46f86f73f5ec55ce9e332c1969e14">llvm::InvalidateAllAnalysesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/iroutlinerpass/#a5b9a8fe2c3b6834817b2c12b08441cff">llvm::IROutlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/jmcinstrumenterpass/#a5d2aeb7f2893f237f1662e2f9cc19eb5">llvm::JMCInstrumenterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/kcfipass/#a19dcb564cb3c8a4de327c6f9cabed5b3">llvm::KCFIPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopidiomvectorizepass/#a0b63cb3362045110398f3faf3ddbee74">llvm::LoopIdiomVectorizePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopversioningpass/#ab85aee23551eb41e8d1d7e01e1fd3f98">llvm::LoopVersioningPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lowerallowcheckpass/#a0333cadd9ec11ea319d1fd3d3e0e6f05">llvm::LowerAllowCheckPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loweratomicpass/#aa6367f2b0be097467a383973068b444e">llvm::LowerAtomicPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/lowerexpectintrinsicpass/#afb59e74c5181b5a9fa8d58780be0699a">llvm::LowerExpectIntrinsicPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/lowerguardintrinsicpass/#a4ba7c788e41caef18b1c9c8f7fbfcdcc">llvm::LowerGuardIntrinsicPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lowerifuncpass/#afa57ad3cdcdc6ae559bb8444e407665a">llvm::LowerIFuncPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lowerinvokepass/#a13431158a9ef331dddfb0484b37f7bee">llvm::LowerInvokePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/lowerswitchpass/#a7ed296f67da3966a7e2c0dd6f4fbcf9e">llvm::LowerSwitchPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lowertypetestspass/#af14b972caecee35ee8e3a66b85ea3842">llvm::LowerTypeTestsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/lowerwidenableconditionpass/#af8574e7bcb8abe98879ae5a8cbf1f0c5">llvm::LowerWidenableConditionPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/makeguardsexplicitpass/#a025fe5043bbaa6412a601f3f8f9bbf17">llvm::MakeGuardsExplicitPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/memorysanitizerpass/#adfd94cfcef9d896734905bd5a18a05df">llvm::MemorySanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memprofcontextdisambiguation/#ac43814024a542d89728f88411b553e6d">llvm::MemProfContextDisambiguation::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memprofilerpass/#a9da61a3f33d95e94a03f2b2431100492">llvm::MemProfilerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memprofusepass/#a301e9c18f7576c32229ca4c2a06fb8e4">llvm::MemProfUsePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/mergefunctionspass/#ad0198e9945bcf4a17c56e124e7e804ed">llvm::MergeFunctionsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#ab7155781c9a6aafef322de28d9bc4c86">llvm::ModuleInlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/modulememprofilerpass/#a1f56cd341951380da3dc0a019a5b4a3e">llvm::ModuleMemProfilerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/modulethreadsanitizerpass/#adf10c75c773504153d27d41a73ad2223">llvm::ModuleThreadSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/nameanonglobalpass/#a182eb1220b11d52d74537fada176af97">llvm::NameAnonGlobalPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/numericalstabilitysanitizerpass/#aa05e97761e23096ba7621f0ad28c05ed">llvm::NumericalStabilitySanitizerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/nvptxcopybyvalargspass/#adaee1fbeeb30f3f025c55c5f2d5e5ac9">llvm::NVPTXCopyByValArgsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxctordtorloweringpass/#a86b98247d644f6dd257de453f3802561">llvm::NVPTXCtorDtorLoweringPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/nvvmintrrangepass/#ac9fd2e59a5ad190662e1b0167fa2f2fc">llvm::NVVMIntrRangePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/nvvmreflectpass/#a5362d88cc699f98ddfbc4b004926c80d">llvm::NVVMReflectPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpoptcgsccpass/#a9d4366d9c2f6de53d6f2edce548577ab">llvm::OpenMPOptCGSCCPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpoptpass/#ad0812a5ba88f8645505134a108f639b2">llvm::OpenMPOptPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/partialinlinerpass/#a022b0aa595cef197b5b0c655cd18ad9c">llvm::PartialInlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoctxprofflatteningpass/#a13390fcce3ec8b52ef55488e967081c5">llvm::PGOCtxProfFlatteningPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoctxprofloweringpass/#a7ad703c2051de4321f9ef0d082a9c906">llvm::PGOCtxProfLoweringPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/pgoforcefunctionattrspass/#a5a7425ff46058c5adf7da1d9a58c4000">llvm::PGOForceFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoindirectcallpromotion/#a5017234dfda3310cbcae123e5a4de31a">llvm::PGOIndirectCallPromotion::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoinstrumentationgen/#a9cff4300652b1ae7f59c26011099ac65">llvm::PGOInstrumentationGen::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoinstrumentationuse/#a11847c7e88a21b5076fb1cb5e2f7f5e1">llvm::PGOInstrumentationUse::run</a>, <a href="/web-llvm/docs/api/classes/llvm/placesafepointspass/#a4c1a6d3206d9f1278836bdc314e56141">llvm::PlaceSafepointsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/preiselintrinsicloweringpass/#a6c4bdf5cd38f45ec8052f395f32f63ee">llvm::PreISelIntrinsicLoweringPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobeupdatepass/#a1eef7e13ba8f6964ddd2f64c8a85d8b8">llvm::PseudoProbeUpdatePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/realtimesanitizerpass/#a6ef2f34cb129c3b7d3a996e88f3e2c9e">llvm::RealtimeSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/rewritesymbolpass/#a3a676b28a8e2daaf300ad9c5e3776c33">llvm::RewriteSymbolPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderpass/#a324d3696b255beea7cfd1e8b901b2363">llvm::SampleProfileLoaderPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileprobepass/#a8c1accd469872b7673c9c8a033e30a0c">llvm::SampleProfileProbePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sanitizerbinarymetadatapass/#a4c4b3aea1ab9cc4a61033672c29e3c69">llvm::SanitizerBinaryMetadataPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sanitizercoveragepass/#a93d554aebdab8ad87f41ba8e07f73cad">llvm::SanitizerCoveragePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/siannotatecontrolflowpass/#a84e9204f8b261089c66706e2941ee6da">llvm::SIAnnotateControlFlowPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sjljehpreparepass/#a495925d0983e66d028a72e6b6748f072">llvm::SjLjEHPreparePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/stackcoloringpass/#a693535db98527be92419386a4baba10a">llvm::StackColoringPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/stripdeadprototypespass/#a5e06b34c5e5ae5f1fe88b71b05d0dfda">llvm::StripDeadPrototypesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/thinltobitcodewriterpass/#a407be825a5084267d383681109e30df9">llvm::ThinLTOBitcodeWriterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/threadsanitizerpass/#a554dea073d38539bd97dbb495225a24b">llvm::ThreadSanitizerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/typesanitizerpass/#a2ffe7ab99b08300315a7ebb6e94ebbe4">llvm::TypeSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/wasmehpreparepass/#a2cbdc4bc7c2c1dc4c48d00376ab271a1">llvm::WasmEHPreparePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtpass/#af94d9399906155205bf6afa17427d5c7">llvm::WholeProgramDevirtPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/winehpreparepass/#a6e2da040c0d9056bb599c15b61a4a379">llvm::WinEHPreparePass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#a29648f060d2dd1e126ed17733813cf0a">llvm::AnalysisManager&lt; LazyCallGraph::SCC, LazyCallGraph &amp; &gt;::verifyNotInvalidated</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### AllAnalysesKey {#adff624f8bb356741634ae566379c463f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisSetKey PreservedAnalyses::AllAnalysesKey</td>
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

<p>A special key used to indicate all analyses.</p>

<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/analysis-h">Analysis.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
