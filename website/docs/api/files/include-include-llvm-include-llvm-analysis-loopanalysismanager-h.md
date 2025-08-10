---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/analysis/loopanalysismanager-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `LoopAnalysisManager.h` File

<p>This header provides classes for managing per-loop analyses. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults">LoopStandardAnalysisResults</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The adaptor from a function pass to a loop pass computes these analyses and makes them available to the loop passes "for free". <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopanalysismanagerfunctionproxy/result">Result</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A specialized result for the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a43d65ba07f09dd4c0c13d551848cdc88">LoopAnalysisManagerFunctionProxy</a></span> which retains a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a></span> reference. <a href="/web-llvm/docs/api/classes/llvm/loopanalysismanagerfunctionproxy/result/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This header provides classes for managing per-loop analyses.</p>


<p>These are typically used as part of a loop pass pipeline over the loop nests of a function.</p>


<p>Loop analyses are allowed to make some simplifying assumptions: 1) Loops are, where possible, in simplified form. 2) Loops are <em>always</em> in LCSSA form. 3) A collection of analysis results are available:</p>


<ul class="doxyList ">
<li>LoopInfo</li>
<li>DominatorTree</li>
<li>ScalarEvolution</li>
<li>AAManager</li>
</ul>

<p>The primary mechanism to provide these invariants is the loop pass manager, but they can also be manually provided in order to reason about a loop from outside of a dedicated pass manager.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
