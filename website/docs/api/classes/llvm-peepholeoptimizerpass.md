---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/peepholeoptimizerpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PeepholeOptimizerPass` Class



## Declaration

<div class="doxyDeclaration">
class llvm::PeepholeOptimizerPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/peepholeoptimizer-h">llvm/CodeGen/PeepholeOptimizer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/passinfomixin">PassInfoMixin&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP mix-in to automatically provide informational APIs needed for passes. <a href="/web-llvm/docs/api/structs/llvm/passinfomixin/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">PreservedAnalyses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80af47b78e07ddb33af6e7d86af034df">run</a> (MachineFunction &amp;MF, MachineFunctionAnalysisManager &amp;MFAM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee6cbae8ff342084325d1ade32999846">getRequiredProperties</a> () const</td>
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


<p>Definition at line 16 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/peepholeoptimizer-h">PeepholeOptimizer.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getRequiredProperties() {#aee6cbae8ff342084325d1ade32999846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties llvm::PeepholeOptimizerPass::getRequiredProperties ()</td>
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



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/peepholeoptimizer-h">PeepholeOptimizer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a4fc3b812627e58da17a703f73013db96">llvm::MachineFunctionProperties::IsSSA</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a>.</p>

</div>
</div>

### run() {#a80af47b78e07ddb33af6e7d86af034df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses PeepholeOptimizerPass::run (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/namespaces/llvm/#a064825a8817522ca733ac413a7122d36">MachineFunctionAnalysisManager</a> &amp; MFAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 18 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/peepholeoptimizer-h">PeepholeOptimizer.h</a>, definition at line 1647 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a596ca6eb2e24883789eb3b1596974d83">llvm::getMachineFunctionPassPreservedAnalyses</a> and <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#aaab1fad63e4f3b8679469720a873fedd">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getResult</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/peepholeoptimizer-h">PeepholeOptimizer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp">PeepholeOptimizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
