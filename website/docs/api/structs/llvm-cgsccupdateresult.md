---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/cgsccupdateresult
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CGSCCUpdateResult` Struct Reference

<p>Support structure for SCC passes to communicate updates the call graph back to the CGSCC pass manager infrastructure. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::CGSCCUpdateResult { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">llvm/Analysis/CGSCCPassManager.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallpriorityworklist">SmallPriorityWorklist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">LazyCallGraph::SCC</a> *, 1 &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a277c9d45b3b20308e166249fd56598ed">CWorklist</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Worklist of the SCCs queued for processing. <a href="#a277c9d45b3b20308e166249fd56598ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">LazyCallGraph::SCC</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6822f3e4bf1d3a55c967bf74b7419704">InvalidatedSCCs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of invalidated SCCs which should be skipped if they are found in <span class="doxyComputerOutput">CWorklist</span>. <a href="#a6822f3e4bf1d3a55c967bf74b7419704">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">LazyCallGraph::SCC</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4eb37646445da693553b9728143f31c">UpdatedC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If non-null, the updated current <span class="doxyComputerOutput">SCC</span> being processed. <a href="#ab4eb37646445da693553b9728143f31c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac113dcaae09e52d6da7235e0757757f0">CrossSCCPA</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Preserved analyses across SCCs. <a href="#ac113dcaae09e52d6da7235e0757757f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">LazyCallGraph::Node</a> *, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">LazyCallGraph::SCC</a> * &gt;, 4 &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a500c2477bf6251954e52d6d9ef808e39">InlinedInternalEdges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A hacky area where the inliner can retain history about inlining decisions that mutated the call graph's SCC structure in order to avoid infinite inlining. <a href="#a500c2477bf6251954e52d6d9ef808e39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, 4 &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53676888f06cf2212c0126db2e9cf9dd">DeadFunctions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Functions that a pass has considered to be dead to be removed at the end of the call graph walk in batch. <a href="#a53676888f06cf2212c0126db2e9cf9dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/smallmapvector">SmallMapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a>, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a4386bac07827eaf6916d7da69a1cd4">IndirectVHs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Weak VHs to keep track of indirect calls for the purposes of detecting devirtualization. <a href="#a0a4386bac07827eaf6916d7da69a1cd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Support structure for SCC passes to communicate updates the call graph back to the CGSCC pass manager infrastructure.</p>


<p>The CGSCC pass manager runs SCC passes which are allowed to update the call graph and SCC structures. This means the structure the pass manager works on is mutating underneath it. In order to support that, there needs to be careful communication about the precise nature and ramifications of these updates to the pass management infrastructure.</p>


<p>All SCC passes will have to accept a reference to the management layer's update result struct and use it to reflect the results of any CG updates performed.</p>


<p>Passes which do not change the call graph structure in any way can just ignore this argument to their run method.</p>


<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">CGSCCPassManager.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### CrossSCCPA {#ac113dcaae09e52d6da7235e0757757f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses llvm::CGSCCUpdateResult::CrossSCCPA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Preserved analyses across SCCs.</p>


<p>We specifically want to allow CGSCC passes to mutate ancestor IR (changing both the CG structure and the function IR itself). However, this means we need to take special care to correctly mark what analyses are preserved <em>across</em> SCCs. We have to track this out-of-band here because within the main <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/passmanager">PassManager</a></span> infrastructure we need to mark everything within an SCC as preserved in order to avoid repeatedly invalidating the same analyses as we unnest pass managers and adaptors. So we track the cross-SCC version of the preserved analyses here from any code that does direct invalidation of SCC analyses, and then use it whenever we move forward in the post-order walk of SCCs before running passes over the new SCC.</p>


<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">CGSCCPassManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#a0ff99def687659818bdb4a25afd82c94">llvm::ModuleToPostOrderCGSCCPassAdaptor::run</a> and <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a6d74effaad77f6ecb91e1806993cda8f">llvm::PassManager&lt; LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp; &gt;::run</a>.</p>

</div>
</div>

### CWorklist {#a277c9d45b3b20308e166249fd56598ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPriorityWorklist&lt;LazyCallGraph::SCC *, 1&gt;&amp; llvm::CGSCCUpdateResult::CWorklist</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Worklist of the SCCs queued for processing.</p>


<p>When a pass refines the graph and creates new SCCs or causes them to have a different shape or set of component functions it should add the SCCs to this worklist so that we visit them in the refined form.</p>


<p>Note that if the SCCs are part of a RefSCC that is added to the <span class="doxyComputerOutput">RCWorklist</span>, they don't need to be added here as visiting the RefSCC will be sufficient to re-visit the SCCs within it.</p>


<p>This worklist is in reverse post-order, as we pop off the back in order to observe SCCs in post-order. When adding SCCs, clients should add them in reverse post-order.</p>


<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">CGSCCPassManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#aa64f6bcd5ace031369edc14aa406d745">incorporateNewSCCRange</a>, <a href="/web-llvm/docs/api/structs/llvm/corosplitpass/#a47f6589634ad33a13369ace133b9f4b2">llvm::CoroSplitPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#a490117b63072462d035a6933fdb94c1f">updateCGAndAnalysisManagerForPass</a>.</p>

</div>
</div>

### DeadFunctions {#a53676888f06cf2212c0126db2e9cf9dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Function *, 4&gt;&amp; llvm::CGSCCUpdateResult::DeadFunctions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Functions that a pass has considered to be dead to be removed at the end of the call graph walk in batch.</p>

<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">CGSCCPassManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>.</p>

</div>
</div>

### IndirectVHs {#a0a4386bac07827eaf6916d7da69a1cd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallMapVector&lt;Value *, WeakTrackingVH, 16&gt; llvm::CGSCCUpdateResult::IndirectVHs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Weak VHs to keep track of indirect calls for the purposes of detecting devirtualization.</p>


<p>This is a map to avoid having duplicate entries. If a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is deallocated, its corresponding <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> will be nulled out. When checking if a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is in the map or not, also check if the corresponding <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> is null to avoid issues with a new <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> sharing the same address as a deallocated one.</p>


<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">CGSCCPassManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/devirtsccrepeatedpass/#a11597e1847c3156c4866aa0a43a1b71b">llvm::DevirtSCCRepeatedPass::run</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#a490117b63072462d035a6933fdb94c1f">updateCGAndAnalysisManagerForPass</a>.</p>

</div>
</div>

### InlinedInternalEdges {#a500c2477bf6251954e52d6d9ef808e39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseSet&lt;std::pair&lt;LazyCallGraph::Node *, LazyCallGraph::SCC *&gt;, 4&gt;&amp; llvm::CGSCCUpdateResult::InlinedInternalEdges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A hacky area where the inliner can retain history about inlining decisions that mutated the call graph's SCC structure in order to avoid infinite inlining.</p>


<p>See the comments in the inliner's CG update logic.</p>


<p>FIXME: Keeping this here seems like a big layering issue, we should look for a better technique.</p>


<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">CGSCCPassManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>.</p>

</div>
</div>

### InvalidatedSCCs {#a6822f3e4bf1d3a55c967bf74b7419704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSetImpl&lt;LazyCallGraph::SCC *&gt;&amp; llvm::CGSCCUpdateResult::InvalidatedSCCs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of invalidated SCCs which should be skipped if they are found in <span class="doxyComputerOutput">CWorklist</span>.</p>


<p>This is used to quickly prune out SCCs when they get deleted and happen to already be on the worklist. We use this primarily to avoid scanning the list and removing entries from it.</p>


<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">CGSCCPassManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/devirtsccrepeatedpass/#a11597e1847c3156c4866aa0a43a1b71b">llvm::DevirtSCCRepeatedPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#a0ff99def687659818bdb4a25afd82c94">llvm::ModuleToPostOrderCGSCCPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a6d74effaad77f6ecb91e1806993cda8f">llvm::PassManager&lt; LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp; &gt;::run</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#a490117b63072462d035a6933fdb94c1f">updateCGAndAnalysisManagerForPass</a>.</p>

</div>
</div>

### UpdatedC {#ab4eb37646445da693553b9728143f31c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallGraph::SCC* llvm::CGSCCUpdateResult::UpdatedC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If non-null, the updated current <span class="doxyComputerOutput">SCC</span> being processed.</p>


<p>This is set when a graph refinement takes place and the "current" point in the graph moves "down" or earlier in the post-order walk. This will often cause the "current" SCC to be a newly created SCC object and the old one to be added to the above worklist. When that happens, this pointer is non-null and can be used to continue processing the "top" of the post-order walk.</p>


<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">CGSCCPassManager.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/devirtsccrepeatedpass/#a11597e1847c3156c4866aa0a43a1b71b">llvm::DevirtSCCRepeatedPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#a0ff99def687659818bdb4a25afd82c94">llvm::ModuleToPostOrderCGSCCPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a6d74effaad77f6ecb91e1806993cda8f">llvm::PassManager&lt; LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp; &gt;::run</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#a490117b63072462d035a6933fdb94c1f">updateCGAndAnalysisManagerForPass</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">CGSCCPassManager.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
