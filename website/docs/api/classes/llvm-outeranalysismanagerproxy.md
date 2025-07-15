---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/outeranalysismanagerproxy
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `OuterAnalysisManagerProxy` Class Template Reference

<p>An analysis over an "inner" IR unit that provides access to an analysis manager over a "outer" IR unit. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename AnalysisManagerT, typename IRUnitT, typename... ExtraArgTs&gt;
class llvm::OuterAnalysisManagerProxy&lt;AnalysisManagerT, IRUnitT, ExtraArgTs&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/analysisinfomixin">AnalysisInfoMixin&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP mix-in that provides informational APIs needed for analysis passes. <a href="/web-llvm/docs/api/structs/llvm/analysisinfomixin/#details">More...</a></p>
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
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ac45b2069285adb1d482b5bd80b2b281c">OuterAnalysisManagerProxy</a> (const AnalysisManagerT &amp;OuterAM)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/outeranalysismanagerproxy/result">Result</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab5b413ed02f38146175d4d3ec11540bc">run</a> (IRUnitT &amp;, AnalysisManager&lt; IRUnitT, ExtraArgTs... &gt; &amp;, ExtraArgTs...)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run the analysis pass and create our proxy result object. <a href="#ab5b413ed02f38146175d4d3ec11540bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab36191daaf4cfd6f33f7655587430f2b">AnalysisInfoMixin&lt; OuterAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt; &gt;</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> AnalysisManagerT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac4cb329debaa1e7d9b92e6bd4ad884a4">OuterAM</a></td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8ca5331f8970e41c978f2f360100b9b5">Key</a></td>
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

<p>An analysis over an "inner" IR unit that provides access to an analysis manager over a "outer" IR unit.</p>


<p>The inner unit must be contained in the outer unit.</p>


<p>For example <a href="/web-llvm/docs/api/classes/llvm/outeranalysismanagerproxy">OuterAnalysisManagerProxy&lt;ModuleAnalysisManager, Function&gt;</a> is an analysis over Functions (the "inner" unit) which provides access to a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> analysis manager. The <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> is the "outer" manager being proxied, and Modules are the "outer" IR unit. The inner/outer relationship is valid because each <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> is contained in one <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>.</p>


<p>This proxy only exposes the const interface of the outer analysis manager, to indicate that you cannot cause an outer analysis to run from within an inner pass. Instead, you must rely on the <span class="doxyComputerOutput">getCachedResult</span> API. This is due to keeping potential future concurrency in mind. To give an example, running a module analysis before any function passes may give a different result than running it in a function pass. Both may be valid, but it would produce non-deterministic results. <a href="/web-llvm/docs/api/classes/llvm/globalsaa">GlobalsAA</a> is a good analysis example, because the cached information has the mod/ref info for all memory for each function at the time the analysis was computed. The information is still valid after a function transformation, but it may be <em>different</em> if recomputed after that transform. <a href="/web-llvm/docs/api/classes/llvm/globalsaa">GlobalsAA</a> is never invalidated. This proxy doesn't manage invalidation in any way – that is handled by the recursive return path of each layer of the pass manager. A consequence of this is the outer analyses may be stale. We invalidate the outer analyses only when we're done running passes over the inner IR units.</p>


<p>Definition at line 690 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OuterAnalysisManagerProxy() {#ac45b2069285adb1d482b5bd80b2b281c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisManagerT, typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OuterAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs &gt;::OuterAnalysisManagerProxy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> AnalysisManagerT &amp; OuterAM)</td>
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



<p>Definition at line 774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#ab5b413ed02f38146175d4d3ec11540bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisManagerT, typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Result llvm::OuterAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs &gt;::run (IRUnitT &amp;, <a href="/web-llvm/docs/api/classes/llvm/analysismanager">AnalysisManager</a>&lt; IRUnitT, ExtraArgTs... &gt; &amp;, ExtraArgTs...)</td>
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

<p>Run the analysis pass and create our proxy result object.</p>


<p>Nothing to see here, it just forwards the <span class="doxyComputerOutput">OuterAM</span> reference into the result.</p>


<p>Definition at line 780 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AnalysisInfoMixin&lt; OuterAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt; &gt; {#ab36191daaf4cfd6f33f7655587430f2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisManagerT, typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::OuterAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs &gt;::AnalysisInfoMixin&lt; OuterAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt; &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 786 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

### OuterAM {#ac4cb329debaa1e7d9b92e6bd4ad884a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisManagerT, typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AnalysisManagerT* llvm::OuterAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs &gt;::OuterAM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### Key {#a8ca5331f8970e41c978f2f360100b9b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AnalysisManagerT, typename IRUnitT, typename... ExtraArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisKey llvm::OuterAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs &gt;::Key</td>
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



<p>Definition at line 789 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">PassManager.h</a>.</p>

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
