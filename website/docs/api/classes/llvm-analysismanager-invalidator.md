---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/analysismanager/invalidator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Invalidator` Class Reference

<p>API to communicate dependencies between analyses during invalidation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AnalysisManager::Invalidator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affedfb8108f90597f24e166b7a36953b">AnalysisManager</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71bd98f8460b2e94048665a664dbbe1f">Invalidator</a> (SmallDenseMap&lt; AnalysisKey *, bool, 8 &gt; &amp;IsResultInvalidated, const AnalysisResultMapT &amp;Results)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PassT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5e8e9230fa677542877d1f3c6ff95ae2">invalidate</a> (IRUnitT &amp;IR, const PreservedAnalyses &amp;PA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Trigger the invalidation of some other analysis pass if not already handled and return whether it was in fact invalidated. <a href="#a5e8e9230fa677542877d1f3c6ff95ae2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a323b36498775645d82d4193998ed74">invalidate</a> (AnalysisKey *ID, IRUnitT &amp;IR, const PreservedAnalyses &amp;PA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A type-erased variant of the above invalidate method with the same core API other than passing an analysis <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> rather than an analysis type parameter. <a href="#a1a323b36498775645d82d4193998ed74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ResultT = ResultConceptT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8ee07d24cf65b35a8fbd59e1aabf16b1">invalidateImpl</a> (AnalysisKey *ID, IRUnitT &amp;IR, const PreservedAnalyses &amp;PA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a> *, bool, 8 &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a512ef78aed59b026630fff96548bd819">IsResultInvalidated</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">AnalysisResultMapT</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ef3234a0c0932ef94cafcc22895a82a">Results</a></td>
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

<p>API to communicate dependencies between analyses during invalidation.</p>


<p>When an analysis result embeds handles to other analysis results, it needs to be invalidated both when its own information isn't preserved and when any of its embedded analysis results end up invalidated. We pass an <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/analysismanager/invalidator">Invalidator</a></span> object as an argument to <span class="doxyComputerOutput"><a href="#a5e8e9230fa677542877d1f3c6ff95ae2">invalidate()</a></span> in order to let the analysis results themselves define the dependency graph on the fly. This lets us avoid building an explicit representation of the dependencies between analysis results.</p>


<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>


<div class="doxySectionDef">

## Friends

### AnalysisManager {#affedfb8108f90597f24e166b7a36953b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/analysismanager">AnalysisManager</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>


<p>References <a href="#affedfb8108f90597f24e166b7a36953b">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::Invalidator::AnalysisManager</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>


<p>Referenced by <a href="#affedfb8108f90597f24e166b7a36953b">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::Invalidator::AnalysisManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### Invalidator() {#a71bd98f8460b2e94048665a664dbbe1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::Invalidator::Invalidator (<a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a> *, bool, 8 &gt; &amp; IsResultInvalidated, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">AnalysisResultMapT</a> &amp; Results)</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### invalidate() {#a5e8e9230fa677542877d1f3c6ff95ae2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::Invalidator::invalidate (IRUnitT &amp; IR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a> &amp; PA)</td>
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

<p>Trigger the invalidation of some other analysis pass if not already handled and return whether it was in fact invalidated.</p>


<p>This is expected to be called from within a given analysis result's <span class="doxyComputerOutput">invalidate</span> method to trigger a depth-first walk of all inter-analysis dependencies. The same <span class="doxyComputerOutput">IR</span> unit and <span class="doxyComputerOutput">PA</span> passed to that result's <span class="doxyComputerOutput">invalidate</span> method should in turn be provided to this routine.</p>


<p>The first time this is called for a given analysis pass, it will call the corresponding result's <span class="doxyComputerOutput">invalidate</span> method. Subsequent calls will use a cache of the results of that initial call. It is an error to form cyclic dependencies between analysis results.</p>


<p>This returns true if the given analysis's result is invalid. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> dependecies on it will become invalid as a result.</p>


<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/outeranalysismanagerproxy/result/#a139e8b7a2de6d6c79a532567dfd2f9ed">llvm::OuterAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs &gt;::Result::invalidate</a>.</p>

</div>
</div>

### invalidate() {#a1a323b36498775645d82d4193998ed74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::Invalidator::invalidate (<a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a> * ID, IRUnitT &amp; IR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a> &amp; PA)</td>
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

<p>A type-erased variant of the above invalidate method with the same core API other than passing an analysis <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> rather than an analysis type parameter.</p>


<p>This is sadly less efficient than the above routine, which leverages the type parameter to avoid the type erasure overhead.</p>


<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### invalidateImpl() {#a8ee07d24cf65b35a8fbd59e1aabf16b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ResultT = ResultConceptT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::Invalidator::invalidateImpl (<a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a> * ID, IRUnitT &amp; IR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a> &amp; PA)</td>
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



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IsResultInvalidated {#a512ef78aed59b026630fff96548bd819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;AnalysisKey *, bool, 8&gt;&amp; llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::Invalidator::IsResultInvalidated</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

### Results {#a1ef3234a0c0932ef94cafcc22895a82a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AnalysisResultMapT&amp; llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::Invalidator::Results</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
