---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/detail/analysispassmodel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `AnalysisPassModel` Struct Template

<p>Wrapper to model the analysis pass concept. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename IRUnitT, typename PassT, typename InvalidatorT, typename... ExtraArgTs&gt;
struct llvm::detail::AnalysisPassModel&lt;IRUnitT, PassT, InvalidatorT, ExtraArgTs&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">llvm/IR/PassManagerInternal.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/detail/analysispassconcept">AnalysisPassConcept&lt;IRUnitT, InvalidatorT, ExtraArgTs&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract concept of an analysis pass. <a href="/web-llvm/docs/api/structs/llvm/detail/analysispassconcept/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab4f605982b83a3e36c2093f5522b5a30">ResultModelT</a> = <a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultmodel">AnalysisResultModel</a>&lt; IRUnitT, PassT, typename PassT::Result, InvalidatorT &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abeb36910e941e044cf7bb71d76767f4f">swap</a></td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a3cc5a6c66e433e139a608fb2c37191a4">AnalysisPassModel</a> (PassT Pass)</td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a2e74303752215d7c6e30787cc210432d">AnalysisPassModel</a> (const AnalysisPassModel &amp;Arg)</td>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#af5000427d629ba9bea70e0eba14f0eb9">AnalysisPassModel</a> (AnalysisPassModel &amp;&amp;Arg)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/detail/analysispassmodel">AnalysisPassModel</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad0c29602405373c28d19123771394d11">operator=</a> (AnalysisPassModel RHS)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab7cb7eff46888a5b3c8b4d3d6578b13d">run</a> (IRUnitT &amp;IR, AnalysisManager&lt; IRUnitT, ExtraArgTs... &gt; &amp;AM, ExtraArgTs... ExtraArgs) override -&gt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultconcept">AnalysisResultConcept</a>&lt; IRUnitT, InvalidatorT &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The model delegates to the <span class="doxyComputerOutput">PassT::run</span> method. <a href="#ab7cb7eff46888a5b3c8b4d3d6578b13d">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a39849dba8f55d3050df4bbded264f4b2">name</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The model delegates to a static <span class="doxyComputerOutput">PassT::name</span> method. <a href="#a39849dba8f55d3050df4bbded264f4b2">More...</a></p>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">PassT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aefa0ae6daaedbff961122c05141961b2">Pass</a></td>
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

<p>Wrapper to model the analysis pass concept.</p>


<p>Can wrap any type which implements a suitable <span class="doxyComputerOutput">run</span> method. The method must accept an <span class="doxyComputerOutput">IRUnitT&amp;</span> and an <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/analysismanager">AnalysisManager&lt;IRUnitT&gt;</a>&amp;</span> as arguments and produce an object which can be wrapped in a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultmodel">AnalysisResultModel</a></span>.</p>


<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ResultModelT {#ab4f605982b83a3e36c2093f5522b5a30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename InvalidatorT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::ResultModelT = 
      AnalysisResultModel&lt;IRUnitT, PassT, typename PassT::Result, InvalidatorT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### swap {#abeb36910e941e044cf7bb71d76767f4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend void <a href="/web-llvm/docs/api/structs/llvm/detail/analysispassmodel">AnalysisPassModel</a> &amp; LHS, <a href="/web-llvm/docs/api/structs/llvm/detail/analysispassmodel">AnalysisPassModel</a> &amp; RHS</td>
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


<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>References <a href="#a3cc5a6c66e433e139a608fb2c37191a4">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::AnalysisPassModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#abeb36910e941e044cf7bb71d76767f4f">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::swap</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#ad0c29602405373c28d19123771394d11">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::operator=</a> and <a href="#abeb36910e941e044cf7bb71d76767f4f">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::swap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AnalysisPassModel() {#a3cc5a6c66e433e139a608fb2c37191a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename InvalidatorT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::AnalysisPassModel (PassT Pass)</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#aefa0ae6daaedbff961122c05141961b2">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::Pass</a>.</p>


<p>Referenced by <a href="#af5000427d629ba9bea70e0eba14f0eb9">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::AnalysisPassModel</a>, <a href="#a2e74303752215d7c6e30787cc210432d">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::AnalysisPassModel</a>, <a href="#ad0c29602405373c28d19123771394d11">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::operator=</a> and <a href="#abeb36910e941e044cf7bb71d76767f4f">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::swap</a>.</p>

</div>
</div>

### AnalysisPassModel() {#a2e74303752215d7c6e30787cc210432d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename InvalidatorT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::AnalysisPassModel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/detail/analysispassmodel">AnalysisPassModel</a> &amp; Arg)</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>References <a href="#a3cc5a6c66e433e139a608fb2c37191a4">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::AnalysisPassModel</a> and <a href="#aefa0ae6daaedbff961122c05141961b2">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::Pass</a>.</p>

</div>
</div>

### AnalysisPassModel() {#af5000427d629ba9bea70e0eba14f0eb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename InvalidatorT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::AnalysisPassModel (<a href="/web-llvm/docs/api/structs/llvm/detail/analysispassmodel">AnalysisPassModel</a> &amp;&amp; Arg)</td>
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



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>References <a href="#a3cc5a6c66e433e139a608fb2c37191a4">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::AnalysisPassModel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#aefa0ae6daaedbff961122c05141961b2">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::Pass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ad0c29602405373c28d19123771394d11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename InvalidatorT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisPassModel &amp; llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::operator= (<a href="/web-llvm/docs/api/structs/llvm/detail/analysispassmodel">AnalysisPassModel</a> RHS)</td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>References <a href="#a3cc5a6c66e433e139a608fb2c37191a4">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::AnalysisPassModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#abeb36910e941e044cf7bb71d76767f4f">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::swap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### name() {#a39849dba8f55d3050df4bbded264f4b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename InvalidatorT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::name ()</td>
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

<p>The model delegates to a static <span class="doxyComputerOutput">PassT::name</span> method.</p>


<p>The returned string ref must point to constant immutable data!</p>


<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>

</div>
</div>

### run() {#ab7cb7eff46888a5b3c8b4d3d6578b13d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename InvalidatorT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AnalysisResultConcept&lt; IRUnitT, InvalidatorT &gt; &gt; llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::run (IRUnitT &amp; IR, <a href="/web-llvm/docs/api/classes/llvm/analysismanager">AnalysisManager</a>&lt; IRUnitT, ExtraArgTs... &gt; &amp; AM, ExtraArgTs... ExtraArgs)</td>
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

<p>The model delegates to the <span class="doxyComputerOutput">PassT::run</span> method.</p>


<p>The return is wrapped in an <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultmodel">AnalysisResultModel</a></span>.</p>


<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a> and <a href="#aefa0ae6daaedbff961122c05141961b2">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::Pass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Pass {#aefa0ae6daaedbff961122c05141961b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT, typename InvalidatorT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassT llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::Pass</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerinternal-h">PassManagerInternal.h</a>.</p>


<p>Referenced by <a href="#af5000427d629ba9bea70e0eba14f0eb9">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::AnalysisPassModel</a>, <a href="#a2e74303752215d7c6e30787cc210432d">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::AnalysisPassModel</a>, <a href="#a3cc5a6c66e433e139a608fb2c37191a4">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::AnalysisPassModel</a> and <a href="#ab7cb7eff46888a5b3c8b4d3d6578b13d">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::run</a>.</p>

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
