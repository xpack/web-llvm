---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `CGSCCPassManager.h` File

<p>This header provides classes for managing passes over SCCs of the call graph. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">llvm/ADT/MapVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">llvm/Analysis/LazyCallGraph.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">llvm/IR/ValueHandle.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;utility&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/requireanalysispass-498ca4f351a1bdb57b4c30b5c00bae4c">RequireAnalysisPass&lt;AnalysisT, LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An explicit specialization of the require analysis template pass. <a href="/web-llvm/docs/api/structs/llvm/requireanalysispass-498ca4f351a1bdb57b4c30b5c00bae4c/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cgsccanalysismanagermoduleproxy/result">Result</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We need a specialized result for the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab279be449a12f8ba5f83dceba257d796">CGSCCAnalysisManagerModuleProxy</a></span> so it can have access to the call graph in order to walk all the SCCs when invalidating things. <a href="/web-llvm/docs/api/classes/llvm/cgsccanalysismanagermoduleproxy/result/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/cgsccupdateresult">CGSCCUpdateResult</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Support structure for SCC passes to communicate updates the call graph back to the CGSCC pass manager infrastructure. <a href="/web-llvm/docs/api/structs/llvm/cgsccupdateresult/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor">ModuleToPostOrderCGSCCPassAdaptor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The core module pass which does a post-order walk of the SCCs and runs a CGSCC pass over each one. <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionanalysismanagercgsccproxy">FunctionAnalysisManagerCGSCCProxy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A proxy from a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a></span> to an <span class="doxyComputerOutput">SCC</span>. <a href="/web-llvm/docs/api/classes/llvm/functionanalysismanagercgsccproxy/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functionanalysismanagercgsccproxy/result">Result</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cgscctofunctionpassadaptor">CGSCCToFunctionPassAdaptor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adaptor that maps from a SCC to its functions. <a href="/web-llvm/docs/api/classes/llvm/cgscctofunctionpassadaptor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/shouldnotrunfunctionpassesanalysis">ShouldNotRunFunctionPassesAnalysis</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/shouldnotrunfunctionpassesanalysis/result">Result</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/devirtsccrepeatedpass">DevirtSCCRepeatedPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper that repeats an SCC pass each time an indirect call is refined to a direct call by that pass. <a href="/web-llvm/docs/api/classes/llvm/devirtsccrepeatedpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"cgscc"</td>
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

<p>This header provides classes for managing passes over SCCs of the call graph.</p>


<p>These passes form an important component of LLVM's interprocedural optimizations. Because they operate on the SCCs of the call graph, and they traverse the graph in post-order, they can effectively do pair-wise interprocedural optimizations for all call edges in the program while incrementally refining it and improving the context of these pair-wise optimizations. At each call site edge, the callee has already been optimized as much as is possible. This in turn allows very accurate analysis of it for IPO.</p>


<p>A secondary more general goal is to be able to isolate optimization on unrelated parts of the IR module. This is useful to ensure our optimizations are principled and don't miss oportunities where refinement of one part of the module influences transformations in another part of the module. But this is also useful if we want to parallelize the optimizations across common large module graph shapes which tend to be very wide and have large regions of unrelated cliques.</p>


<p>To satisfy these goals, we use the LazyCallGraph which provides two graphs nested inside each other (and built lazily from the bottom-up): the call graph proper, and a reference graph. The reference graph is super set of the call graph and is a conservative approximation of what could through scalar or CGSCC transforms <em>become</em> the call graph. Using this allows us to ensure we optimize functions prior to them being introduced into the call graph by devirtualization or other technique, and thus ensures that subsequent pair-wise interprocedural optimizations observe the optimized form of these functions. The (potentially transitive) reference reachability used by the reference graph is a conservative approximation that still allows us to have independent regions of the graph.</p>


<p>FIXME: There is one major drawback of the reference graph: in its naive form it is quadratic because it contains a distinct edge for each (potentially indirect) reference, even if are all through some common global table of function pointers. This can be fixed in a number of ways that essentially preserve enough of the normalization. While it isn't expected to completely preclude the usability of this, it will need to be addressed.</p>


<p>All of these issues are made substantially more complex in the face of mutations to the call graph while optimization passes are being run. When mutations to the call graph occur we want to achieve two different things:</p>


<ul class="doxyList ">
<li>We need to update the call graph in-flight and invalidate analyses cached on entities in the graph. Because of the cache-based analysis design of the pass manager, it is essential to have stable identities for the elements of the IR that passes traverse, and to invalidate any analyses cached on these elements as the mutations take place.</li>
<li>We want to preserve the incremental and post-order traversal of the graph even as it is refined and mutated. This means we want optimization to observe the most refined form of the call graph and to do so in post-order.</li>
</ul>

<p>To address this, the CGSCC manager uses both worklists that can be expanded by passes which transform the IR, and provides invalidation tests to skip entries that become dead. This extra data is provided to every SCC pass so that it can carefully update the manager's traversal as the call graph mutates.</p>


<p>We also provide support for running function passes within the CGSCC walk, and there we provide automatic update of the call graph including of the pass manager to reflect call graph changes that fall out naturally as part of scalar transformations.</p>


<p>The patterns used to ensure the goals of post-order visitation of the fully refined graph:</p>


<p>1) Sink toward the "bottom" as the graph is refined. This means that any iteration continues in some valid post-order sequence after the mutation has altered the structure.</p>


<p>2) Enqueue in post-order, including the current entity. If the current entity's shape changes, it and everything after it in post-order needs to be visited to observe that shape.</p>


<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"cgscc"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">CGSCCPassManager.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
