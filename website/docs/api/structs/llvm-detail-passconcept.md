---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/detail/passconcept
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PassConcept` Struct Template Reference

<p>Template for the abstract base class used to dispatch polymorphically over pass objects. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename IRUnitT, typename AnalysisManagerT, typename... ExtraArgTs&gt;
struct llvm::detail::PassConcept&lt;IRUnitT, AnalysisManagerT, ExtraArgTs&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">llvm/IR/PassManagerInternal.h</a>"
</div>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#af7747f5ff9bd31bacb39b2d3a6b084f9">~PassConcept</a> ()=default</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">PreservedAnalyses</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af397f5b2bf1d7cdc52a6032047f8fbc4">run</a> (IRUnitT &amp;IR, AnalysisManagerT &amp;AM, ExtraArgTs... ExtraArgs)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The polymorphic API which runs the pass over a given IR entity. <a href="#af397f5b2bf1d7cdc52a6032047f8fbc4">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa633809a04e763eb3c0e13a6e1658181">printPipeline</a> (raw_ostream &amp;OS, function_ref&lt; StringRef(StringRef)&gt; MapClassName2PassName)=0</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a13ea20e381ecfadc5ad25ce6122aece8">name</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Polymorphic method to access the name of a pass. <a href="#a13ea20e381ecfadc5ad25ce6122aece8">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aab65a1248cdc6b5fbd15a60afa528fa8">isRequired</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Polymorphic method to let a pass optionally exempted from skipping by <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation">PassInstrumentation</a>. <a href="#aab65a1248cdc6b5fbd15a60afa528fa8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Template for the abstract base class used to dispatch polymorphically over pass objects.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~PassConcept() {#af7747f5ff9bd31bacb39b2d3a6b084f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename AnalysisManagerT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::detail::PassConcept&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::~PassConcept ()</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isRequired() {#aab65a1248cdc6b5fbd15a60afa528fa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename AnalysisManagerT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::detail::PassConcept&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::isRequired ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Polymorphic method to let a pass optionally exempted from skipping by <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation">PassInstrumentation</a>.</p>


<p>To opt-in, pass should implement <span class="doxyComputerOutput">static bool <a href="#aab65a1248cdc6b5fbd15a60afa528fa8">isRequired()</a></span>. It's no-op to have <span class="doxyComputerOutput">isRequired</span> always return false since that is the default.</p>


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>

</div>
</div>

### name() {#a13ea20e381ecfadc5ad25ce6122aece8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename AnalysisManagerT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual StringRef llvm::detail::PassConcept&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::name ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Polymorphic method to access the name of a pass.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>

</div>
</div>

### printPipeline() {#aa633809a04e763eb3c0e13a6e1658181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename AnalysisManagerT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::detail::PassConcept&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::printPipeline (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt; MapClassName2PassName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>

</div>
</div>

### run() {#af397f5b2bf1d7cdc52a6032047f8fbc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename AnalysisManagerT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual PreservedAnalyses llvm::detail::PassConcept&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::run (IRUnitT &amp; IR, AnalysisManagerT &amp; AM, ExtraArgTs... ExtraArgs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The polymorphic API which runs the pass over a given IR entity.</p>


<p>Note that actual pass object can omit the analysis manager argument if desired. Also that the analysis manager may be null if there is no analysis manager in the pass pipeline.</p>


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
