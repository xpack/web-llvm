---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/detail/analysisresultmodel-75f8f241f73e3efeb1c36c7a3a5bec6a
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AnalysisResultModel` Struct Template Reference

<p>Specialization of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultmodel">AnalysisResultModel</a></span> which provides the default invalidate functionality. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename IRUnitT, typename PassT, typename ResultT, typename InvalidatorT&gt;
struct llvm::detail::AnalysisResultModel&lt;IRUnitT, PassT, ResultT, InvalidatorT, false&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">llvm/IR/PassManagerInternal.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultconcept">AnalysisResultConcept&lt;IRUnitT, InvalidatorT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract concept of an analysis result. <a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultconcept/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afa8e895973acea9d338bd063e43ae682">swap</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a8e075754b01600ac246499b86b35728c">AnalysisResultModel</a> (ResultT Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a5cb77717a54ba8f476e0a79d0329559d">AnalysisResultModel</a> (const AnalysisResultModel &amp;Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aeb14693ce2d6d18089bbdf43b6bb4eb0">AnalysisResultModel</a> (AnalysisResultModel &amp;&amp;Arg)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultmodel">AnalysisResultModel</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a44df49d0ca5295a56a766c5e8e21f96a">operator=</a> (AnalysisResultModel RHS)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adf6d574cd1bf37ff3fc04014eb6d2365">invalidate</a> (IRUnitT &amp;, const PreservedAnalyses &amp;PA, InvalidatorT &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The model bases invalidation solely on being in the preserved set. <a href="#adf6d574cd1bf37ff3fc04014eb6d2365">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ResultT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a149a3464c1f9ac07931a729481867bb2">Result</a></td>
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

<p>Specialization of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultmodel">AnalysisResultModel</a></span> which provides the default invalidate functionality.</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<div class="doxySectionDef">

## Friends

### swap {#afa8e895973acea9d338bd063e43ae682}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend void <a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultmodel">AnalysisResultModel</a> &amp; LHS, <a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultmodel">AnalysisResultModel</a> &amp; RHS</td>
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


<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>References <a href="#a8e075754b01600ac246499b86b35728c">AnalysisResultModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#afa8e895973acea9d338bd063e43ae682">swap</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#a44df49d0ca5295a56a766c5e8e21f96a">operator=</a> and <a href="#afa8e895973acea9d338bd063e43ae682">swap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AnalysisResultModel() {#a8e075754b01600ac246499b86b35728c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename ResultT, typename InvalidatorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::AnalysisResultModel&lt; IRUnitT, PassT, ResultT, InvalidatorT, false &gt;::AnalysisResultModel (ResultT Result)</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a149a3464c1f9ac07931a729481867bb2">Result</a>.</p>


<p>Referenced by <a href="#aeb14693ce2d6d18089bbdf43b6bb4eb0">AnalysisResultModel</a>, <a href="#a5cb77717a54ba8f476e0a79d0329559d">AnalysisResultModel</a>, <a href="#a44df49d0ca5295a56a766c5e8e21f96a">operator=</a> and <a href="#afa8e895973acea9d338bd063e43ae682">swap</a>.</p>

</div>
</div>

### AnalysisResultModel() {#a5cb77717a54ba8f476e0a79d0329559d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename ResultT, typename InvalidatorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::AnalysisResultModel&lt; IRUnitT, PassT, ResultT, InvalidatorT, false &gt;::AnalysisResultModel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultmodel">AnalysisResultModel</a> &amp; Arg)</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>References <a href="#a8e075754b01600ac246499b86b35728c">AnalysisResultModel</a> and <a href="#a149a3464c1f9ac07931a729481867bb2">Result</a>.</p>

</div>
</div>

### AnalysisResultModel() {#aeb14693ce2d6d18089bbdf43b6bb4eb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename ResultT, typename InvalidatorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::AnalysisResultModel&lt; IRUnitT, PassT, ResultT, InvalidatorT, false &gt;::AnalysisResultModel (<a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultmodel">AnalysisResultModel</a> &amp;&amp; Arg)</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>References <a href="#a8e075754b01600ac246499b86b35728c">AnalysisResultModel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a149a3464c1f9ac07931a729481867bb2">Result</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a44df49d0ca5295a56a766c5e8e21f96a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename ResultT, typename InvalidatorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisResultModel &amp; llvm::detail::AnalysisResultModel&lt; IRUnitT, PassT, ResultT, InvalidatorT, false &gt;::operator= (<a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultmodel">AnalysisResultModel</a> RHS)</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>References <a href="#a8e075754b01600ac246499b86b35728c">AnalysisResultModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#afa8e895973acea9d338bd063e43ae682">swap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### invalidate() {#adf6d574cd1bf37ff3fc04014eb6d2365}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename ResultT, typename InvalidatorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::AnalysisResultModel&lt; IRUnitT, PassT, ResultT, InvalidatorT, false &gt;::invalidate (IRUnitT &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/preservedanalyses">PreservedAnalyses</a> &amp; PA, InvalidatorT &amp;)</td>
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

<p>The model bases invalidation solely on being in the preserved set.</p>

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Result {#a149a3464c1f9ac07931a729481867bb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename ResultT, typename InvalidatorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResultT llvm::detail::AnalysisResultModel&lt; IRUnitT, PassT, ResultT, InvalidatorT, false &gt;::Result</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>Referenced by <a href="#aeb14693ce2d6d18089bbdf43b6bb4eb0">AnalysisResultModel</a>, <a href="#a5cb77717a54ba8f476e0a79d0329559d">AnalysisResultModel</a> and <a href="#a8e075754b01600ac246499b86b35728c">AnalysisResultModel</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
