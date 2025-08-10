---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/detail/analysisresultconcept
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `AnalysisResultConcept` Struct Template

<p>Abstract concept of an analysis result. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename IRUnitT, typename InvalidatorT&gt;
struct llvm::detail::AnalysisResultConcept&lt;IRUnitT, InvalidatorT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">llvm/IR/PassManagerInternal.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultmodel-75f8f241f73e3efeb1c36c7a3a5bec6a">AnalysisResultModel&lt;IRUnitT, PassT, ResultT, InvalidatorT, false&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialization of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultmodel">AnalysisResultModel</a></span> which provides the default invalidate functionality. <a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultmodel-75f8f241f73e3efeb1c36c7a3a5bec6a/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultmodel-e14ac5d3d3a9272adbd262bf85f25321">AnalysisResultModel&lt;IRUnitT, PassT, ResultT, InvalidatorT, true&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialization of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultmodel">AnalysisResultModel</a></span> which delegates invalidate handling to <span class="doxyComputerOutput">ResultT</span>. <a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultmodel-e14ac5d3d3a9272adbd262bf85f25321/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename InvalidatorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a70a62a9653fe05eed33dc9fcba57b83a">~AnalysisResultConcept</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename InvalidatorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aed810e47a1f277849f34ba839bd8a587">invalidate</a> (IRUnitT &amp;IR, const PreservedAnalyses &amp;PA, InvalidatorT &amp;Inv)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Method to try and mark a result as invalid. <a href="#aed810e47a1f277849f34ba839bd8a587">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Abstract concept of an analysis result.</p>


<p>This concept is parameterized over the IR unit that this result pertains to.</p>


<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~AnalysisResultConcept() {#a70a62a9653fe05eed33dc9fcba57b83a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename InvalidatorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::detail::AnalysisResultConcept&lt; IRUnitT, InvalidatorT &gt;::~AnalysisResultConcept ()</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### invalidate() {#aed810e47a1f277849f34ba839bd8a587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename InvalidatorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::detail::AnalysisResultConcept&lt; IRUnitT, InvalidatorT &gt;::invalidate (IRUnitT &amp; IR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp; PA, InvalidatorT &amp; Inv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Method to try and mark a result as invalid.</p>


<p>When the outer analysis manager detects a change in some underlying unit of the IR, it will call this method on all of the results cached.</p>


<p><span class="doxyComputerOutput">PA</span> is a set of preserved analyses which can be used to avoid invalidation because the pass which changed the underlying IR took care to update or preserve the analysis result in some way.</p>


<p><span class="doxyComputerOutput">Inv</span> is typically a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/analysismanager/invalidator">AnalysisManager::Invalidator</a></span> object that can be used by a particular analysis result to discover if other analyses results are also invalidated in the event that this result depends on them. See the documentation in the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/analysismanager">AnalysisManager</a></span> for more details.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the result is indeed invalid (the default).</p></dd>
</dl>


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
