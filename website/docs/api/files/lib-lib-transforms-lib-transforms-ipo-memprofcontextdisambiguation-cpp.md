---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MemProfContextDisambiguation.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/memprofcontextdisambiguation-h">llvm/Transforms/IPO/MemProfContextDisambiguation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/denseset-h">llvm/ADT/DenseSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">llvm/ADT/MapVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setoperations-h">llvm/ADT/SetOperations.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">llvm/ADT/SmallSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">llvm/Analysis/MemoryProfileInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/modulesummaryanalysis-h">llvm/Analysis/ModuleSummaryAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">llvm/Analysis/OptimizationRemarkEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">llvm/Bitcode/BitcodeReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">llvm/IR/ModuleSummaryIndex.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/graphwriter-h">llvm/Support/GraphWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/ipo-h">llvm/Transforms/IPO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callpromotionutils-h">llvm/Transforms/Utils/CallPromotionUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/cloning-h">llvm/Transforms/Utils/Cloning.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/instrumentation-h">llvm/Transforms/Utils/Instrumentation.h</a>"
#include &lt;deque&gt;
#include &lt;sstream&gt;
#include &lt;unordered_map&gt;
#include &lt;vector&gt;
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-">anonymous{MemProfContextDisambiguation.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph">CallsiteContextGraph&lt;DerivedCCG, FuncTy, CallTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CRTP base for graphs built from either IR or ThinLTO summary index. <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/funcinfo">FuncInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a function clone via FuncTy pointer and clone number pair. <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/funcinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo">CallInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a callsite clone via CallTy and clone number pair. <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/node">Node</a> in the Callsite Context Graph. <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge">ContextEdge</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Edge in the Callsite Context Graph from a <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode">ContextNode</a> N to a caller or callee. <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callcontextinfo">CallContextInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/modulecallsitecontextgraph">ModuleCallsiteContextGraph</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CRTP derived class for graphs built from IR (regular LTO). <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/modulecallsitecontextgraph/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/indexcall">IndexCall</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a call in the summary index graph, which can either be an allocation or an interior callsite node in an allocation's context. <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/indexcall/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/simplify-type-6b407870b2ccd45f63adc0df9ac9fd55">simplify_type&lt;IndexCall&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/simplify-type-78c41d1bd2798cf9ecb1e07f520879d0">simplify_type&lt;const IndexCall&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/indexcallsitecontextgraph">IndexCallsiteContextGraph</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CRTP derived class for graphs built from summary index (ThinLTO). <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/indexcallsitecontextgraph/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/densemapinfo-a0bd662518daa47d6945fbfbf3d14c2c">DenseMapInfo&lt;typename CallsiteContextGraph&lt; ModuleCallsiteContextGraph, Function, Instruction * &gt;::CallInfo&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/densemapinfo-20e59342efe220375a2b0d2a0c0492aa">DenseMapInfo&lt;typename CallsiteContextGraph&lt; IndexCallsiteContextGraph, FunctionSummary, IndexCall &gt;::CallInfo&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/densemapinfo-6b407870b2ccd45f63adc0df9ac9fd55">DenseMapInfo&lt;IndexCall&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/graphtraits-d346cb7ec23912bbca82c15ec6af2116">GraphTraits&lt;const CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt; *&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/dotgraphtraits-d346cb7ec23912bbca82c15ec6af2116">DOTGraphTraits&lt;const CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt; *&gt;</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad47dddcde435db9e161df5bdf088e70c">STATISTIC</a> (FunctionClonesAnalysis, "Number of function clones created during whole program analysis")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c78b660ad5ab906ae843c1638898c6b">STATISTIC</a> (FunctionClonesThinBackend, "Number of function clones created during ThinLTO backend")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09ad38bd07c10331492fe65117181b18">STATISTIC</a> (FunctionsClonedThinBackend, "Number of functions that had clones created during ThinLTO backend")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4994d926f59df7009a792f00c91626c1">STATISTIC</a> (AllocTypeNotCold, "Number of not cold static allocations (possibly " "cloned) during whole program analysis")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9c26cefd4c54ad4e678cb4789c8cb11">STATISTIC</a> (AllocTypeCold, "Number of cold static allocations (possibly cloned) " "during whole program analysis")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff83a010d2df004834900547713eccfc">STATISTIC</a> (AllocTypeNotColdThinBackend, "Number of not cold static allocations (possibly cloned) during " "ThinLTO backend")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3883e908bf17bd2d087523786af4647">STATISTIC</a> (AllocTypeColdThinBackend, "Number of cold static allocations " "(possibly cloned) during ThinLTO backend")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70a1f6e2179e9ac59c6e6a73f1a5b066">STATISTIC</a> (OrigAllocsThinBackend, "Number of original (not cloned) allocations with memprof profiles " "during ThinLTO backend")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3725747a218585e6f0e5f4aac824ddd1">STATISTIC</a> (AllocVersionsThinBackend, "Number of allocation versions (including clones) during ThinLTO backend")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa57efed199d74148c767cea8fae99133">STATISTIC</a> (MaxAllocVersionsThinBackend, "Maximum number of allocation versions created for an original " "allocation during ThinLTO backend")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fee1be27954ff1963e706aef4da23a5">STATISTIC</a> (UnclonableAllocsThinBackend, "Number of unclonable ambigous allocations during ThinLTO backend")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ca631bb6c211840827e2e9b354c5ab1">STATISTIC</a> (RemovedEdgesWithMismatchedCallees, "Number of edges removed due to mismatched callees (profiled vs IR)")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dc14829593c94420d28cf48a900711d">STATISTIC</a> (FoundProfiledCalleeCount, "Number of profiled callees found via tail calls")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2db88e308d8826b31d584284120c167f">STATISTIC</a> (FoundProfiledCalleeDepth, "Aggregate depth of profiled callees found via tail calls")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46bd8a6922f6a9bbadd32b39dbac87e5">STATISTIC</a> (FoundProfiledCalleeMaxDepth, "Maximum depth of profiled callees found via tail calls")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72e49b6415eb5ddf74001dceec5f0e90">STATISTIC</a> (FoundProfiledCalleeNonUniquelyCount, "Number of profiled callees found via multiple tail call chains")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78e5652d529e02da75e8087017930e28">getAllocTypeString</a> (uint8_t AllocTypes)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a496375cb9cab49305ab8298d46481c9e">checkEdge</a> (const std::shared_ptr&lt; ContextEdge&lt; DerivedCCG, FuncTy, CallTy &gt; &gt; &amp;Edge)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab6a774bfe473897840683fe5c52e200f">checkNode</a> (const ContextNode&lt; DerivedCCG, FuncTy, CallTy &gt; *Node, bool CheckEdges=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf5139fde11ca45c9c419e1989ebf553">getMemProfFuncName</a> (Twine Base, unsigned CloneNo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29b56ebd4926238fd5e5022b7f80458f">isMemProfClone</a> (const Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54060e46cd65144dd5c15d157b188593">checkColdOrNotCold</a> (uint8_t AllocType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &gt;, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0282ad8b650e02a78742f8a718f888f4">createFunctionClones</a> (Function &amp;F, unsigned NumClones, Module &amp;M, OptimizationRemarkEmitter &amp;ORE, std::map&lt; const Function *, SmallPtrSet&lt; const GlobalAlias *, 1 &gt; &gt; &amp;FuncToAliasMap)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59c4cec2de3101c3788db6c4d84872dd">findValueInfoForFunc</a> (const Function &amp;F, const Module &amp;M, const ModuleSummaryIndex *ImportSummary)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3aebd4fa3b5e0d3a952fd4543bde380">DotFilePathPrefix</a>("memprof-dot-file-path-prefix", cl::init(""), cl::Hidden, cl::value_desc("filename"), cl::desc("Specify the path prefix of the MemProf dot files."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f48d17e9412f965032b446536238a61">ExportToDot</a>("memprof-export-to-dot", cl::init(false), cl::Hidden, cl::desc("Export graph to dot files."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4908b838f5705fa3d04d8884821a574">DumpCCG</a>("memprof-dump-ccg", cl::init(false), cl::Hidden, cl::desc("Dump CallingContextGraph to stdout after each stage."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadb6dc3c4ec78048014fdbb22a247ee7">VerifyCCG</a>("memprof-verify-ccg", cl::init(false), cl::Hidden, cl::desc("Perform verification checks on CallingContextGraph."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3a6c5634d5eb4b762f53497d495c4b2">VerifyNodes</a>("memprof-verify-nodes", cl::init(false), cl::Hidden, cl::desc("Perform frequent verification checks on nodes."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac577f50d4870e58f3716e9f06eca5491">MemProfImportSummary</a>("memprof-import-summary", cl::desc("Import summary to use for testing the ThinLTO backend via opt"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a125b93089af5c0962f1368f1e56c4176">TailCallSearchDepth</a>("memprof-tail-call-search-depth", cl::init(5), cl::Hidden, cl::desc("Max depth to recursively search for missing " "frames through tail calls."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86661d08b47f066260c5c37497e391b8">AllowRecursiveCallsites</a>("memprof-allow-recursive-callsites", cl::init(false), cl::Hidden, cl::desc("Allow cloning of callsites involved in recursive cycles"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae03c74ab306d2efe0b44d4c71d58256a">AllowRecursiveContexts</a>("memprof-allow-recursive-contexts", cl::init(true), cl::Hidden, cl::desc("Allow cloning of contexts through recursive cycles"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7af832ec142a036af0c6439583d7785d">MemProfReportHintedSizes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d202769d4373260d2e9158487a94986">MinClonedColdBytePercent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad87209e87867681064f37e6f66b2ae05">MemProfCloneSuffix</a> = ".memprof."</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"memprof-context-disambiguation"</td>
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


<div class="doxySectionDef">

## Functions

### checkColdOrNotCold() {#a54060e46cd65144dd5c15d157b188593}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool checkColdOrNotCold (uint8_t AllocType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3297 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27a1a3c2e99e572ec71d3820d0363d90742">llvm::Cold</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27ad814aa38fbac7f6d03b30741366aae56">llvm::NotCold</a>.</p>

</div>
</div>

### checkEdge() {#a496375cb9cab49305ab8298d46481c9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void checkEdge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::shared_ptr&lt; ContextEdge&lt; DerivedCCG, FuncTy, CallTy &gt; &gt; &amp; Edge)</td>
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



<p>Definition at line 1376 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>


<p>Referenced by <a href="#ab6a774bfe473897840683fe5c52e200f">checkNode</a>.</p>

</div>
</div>

### checkNode() {#ab6a774bfe473897840683fe5c52e200f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedCCG, typename FuncTy, typename CallTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void checkNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ContextNode&lt; DerivedCCG, FuncTy, CallTy &gt; * Node, bool CheckEdges=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 1385 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="#a86661d08b47f066260c5c37497e391b8">AllowRecursiveCallsites</a>, <a href="#ae03c74ab306d2efe0b44d4c71d58256a">AllowRecursiveContexts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a496375cb9cab49305ab8298d46481c9e">checkEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/nodeset/#aba49350c71f099c58053900c4250b417">llvm::NodeSet::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38740a7e3fde66312240ec2cbf003fc2">llvm::set_is_subset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8b4f88b1fadc8f51a643e5faaa13afa6">llvm::set_union</a> and <a href="/web-llvm/docs/api/classes/llvm/nodeset/#a9ea1466950ca6ed26b74695ac58aa954">llvm::NodeSet::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#af222e51d6efae0aeb9ea76cac1b46300">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::assignFunctions</a>.</p>

</div>
</div>

### createFunctionClones() {#a0282ad8b650e02a78742f8a718f888f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; std::unique_ptr&lt; ValueToValueMapTy &gt;, 4 &gt; createFunctionClones (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, unsigned NumClones, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE, std::map&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> *, 1 &gt; &gt; &amp; FuncToAliasMap)</td>
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



<p>Definition at line 4144 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aedeb89fa4ceb608d9d49bcd53ddcd2c1">llvm::CloneFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a8a638534b520f72ab7f2c886da739a6c">llvm::GlobalAlias::create</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter/#aae6a98aea85aa3af87357cc5448db499">llvm::OptimizationRemarkEmitter::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#abf5139fde11ca45c9c419e1989ebf553">getMemProfFuncName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>.</p>

</div>
</div>

### findValueInfoForFunc() {#a59c4cec2de3101c3788db6c4d84872dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueInfo findValueInfoForFunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * ImportSummary)</td>
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



<p>Definition at line 4205 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aed99d84162082a52cd08efb7dfe017e4">llvm::GlobalValue::getGlobalIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6811428caf500217f319c74e80900c14">llvm::GlobalValue::getGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#ada483380be076b95fdf85a6db51c4931">llvm::ModuleSummaryIndex::getGUIDFromOriginalID</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#a352678c0e0c1d28bf963d1d96090733c">llvm::ModuleSummaryIndex::getOriginalNameBeforePromote</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#a62fac0638e2f98e3a85a13fd8deefdc5">llvm::ModuleSummaryIndex::getValueInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>.</p>

</div>
</div>

### getAllocTypeString() {#a78e5652d529e02da75e8087017930e28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string getAllocTypeString (uint8_t AllocTypes)</td>
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



<p>Definition at line 1211 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27a1a3c2e99e572ec71d3820d0363d90742">llvm::Cold</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27ad814aa38fbac7f6d03b30741366aae56">llvm::NotCold</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextedge/#ab6c023223ec2c5481dd82c860deed2f8">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextEdge::print</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/contextnode/#a4f9c9934b56d5f01f4e5057f021022c9">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::ContextNode::print</a> and <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#aaa295e87dfe1eb5dff19dbbe08e8f464">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::printTotalSizes</a>.</p>

</div>
</div>

### getMemProfFuncName() {#abf5139fde11ca45c9c419e1989ebf553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string getMemProfFuncName (<a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> Base, unsigned CloneNo)</td>
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



<p>Definition at line 1897 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a> and <a href="#ad87209e87867681064f37e6f66b2ae05">MemProfCloneSuffix</a>.</p>


<p>Referenced by <a href="#a0282ad8b650e02a78742f8a718f888f4">createFunctionClones</a>.</p>

</div>
</div>

### isMemProfClone() {#a29b56ebd4926238fd5e5022b7f80458f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isMemProfClone (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 1905 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#ad87209e87867681064f37e6f66b2ae05">MemProfCloneSuffix</a>.</p>

</div>
</div>

### STATISTIC() {#ad47dddcde435db9e161df5bdf088e70c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (FunctionClonesAnalysis, "Number of <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> clones created during whole program analysis")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a1c78b660ad5ab906ae843c1638898c6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (FunctionClonesThinBackend, "Number of <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> clones created during ThinLTO backend")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a09ad38bd07c10331492fe65117181b18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (FunctionsClonedThinBackend, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> that had clones created during ThinLTO backend")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a4994d926f59df7009a792f00c91626c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (AllocTypeNotCold, "Number of not cold static allocations (possibly " "cloned) during whole program analysis")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#aa9c26cefd4c54ad4e678cb4789c8cb11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (AllocTypeCold, "Number of cold static allocations (possibly cloned) " "during whole program analysis")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#aff83a010d2df004834900547713eccfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (AllocTypeNotColdThinBackend, "Number of not cold static allocations (possibly cloned) during " "ThinLTO backend")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ac3883e908bf17bd2d087523786af4647}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (AllocTypeColdThinBackend, "Number of cold static allocations " "(possibly cloned) during ThinLTO backend")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a70a1f6e2179e9ac59c6e6a73f1a5b066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (OrigAllocsThinBackend, "Number of original (not cloned) allocations with memprof profiles " "during ThinLTO backend")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a3725747a218585e6f0e5f4aac824ddd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (AllocVersionsThinBackend, "Number of <a href="/web-llvm/docs/api/files/lib/lib/codegen/phielimination-cpp/#a6058ea3bdb60defe0ccd652f1a08131c">allocation</a> versions (including clones) during ThinLTO backend")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#aa57efed199d74148c767cea8fae99133}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (MaxAllocVersionsThinBackend, "Maximum number of <a href="/web-llvm/docs/api/files/lib/lib/codegen/phielimination-cpp/#a6058ea3bdb60defe0ccd652f1a08131c">allocation</a> versions created <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> an original " "<a href="/web-llvm/docs/api/files/lib/lib/codegen/phielimination-cpp/#a6058ea3bdb60defe0ccd652f1a08131c">allocation</a> during ThinLTO backend")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a0fee1be27954ff1963e706aef4da23a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (UnclonableAllocsThinBackend, "Number of unclonable ambigous allocations during ThinLTO backend")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a3ca631bb6c211840827e2e9b354c5ab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (RemovedEdgesWithMismatchedCallees, "Number of edges removed due to mismatched callees (profiled vs <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>)")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a2dc14829593c94420d28cf48a900711d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (FoundProfiledCalleeCount, "Number of profiled callees found via tail calls")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a2db88e308d8826b31d584284120c167f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (FoundProfiledCalleeDepth, "Aggregate depth of profiled callees found via tail calls")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a46bd8a6922f6a9bbadd32b39dbac87e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (FoundProfiledCalleeMaxDepth, "Maximum depth of profiled callees found via tail calls")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a72e49b6415eb5ddf74001dceec5f0e90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (FoundProfiledCalleeNonUniquelyCount, "Number of profiled callees found via multiple tail call chains")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AllowRecursiveCallsites {#a86661d08b47f066260c5c37497e391b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; AllowRecursiveCallsites("memprof-allow-recursive-callsites", cl::init(false), cl::Hidden, cl::desc("Allow cloning of callsites involved in recursive cycles"))</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a3c04d483e66e81efc4812a2d38b93a8d">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; IndexCallsiteContextGraph, FunctionSummary, IndexCall &gt;::addStackNodesForMIB</a> and <a href="#ab6a774bfe473897840683fe5c52e200f">checkNode</a>.</p>

</div>
</div>

### AllowRecursiveContexts {#ae03c74ab306d2efe0b44d4c71d58256a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; AllowRecursiveContexts("memprof-allow-recursive-contexts", cl::init(true), cl::Hidden, cl::desc("Allow cloning of contexts through recursive cycles"))</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="#ab6a774bfe473897840683fe5c52e200f">checkNode</a>.</p>

</div>
</div>

### DotFilePathPrefix {#ae3aebd4fa3b5e0d3a952fd4543bde380}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; DotFilePathPrefix("memprof-dot-file-path-prefix", cl::init(""), cl::Hidden, cl::value_desc("filename"), cl::desc("Specify the path prefix of the MemProf dot files."))</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#ae120eda05be009e7e1124ac882412cad">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::exportToDot</a>.</p>

</div>
</div>

### DumpCCG {#af4908b838f5705fa3d04d8884821a574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DumpCCG("memprof-dump-ccg", cl::init(false), cl::Hidden, cl::desc("Dump CallingContextGraph to stdout after each stage."))</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/indexcallsitecontextgraph/#aa4f54d80f1f0152753a9b60e3f5aea61">anonymous{MemProfContextDisambiguation.cpp}::IndexCallsiteContextGraph::IndexCallsiteContextGraph</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/modulecallsitecontextgraph/#aeefc570485efea4da856d33ef3d16f2a">anonymous{MemProfContextDisambiguation.cpp}::ModuleCallsiteContextGraph::ModuleCallsiteContextGraph</a> and <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a4652a942c3bcd94d6540e3fb0238d356">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::process</a>.</p>

</div>
</div>

### ExportToDot {#a3f48d17e9412f965032b446536238a61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ExportToDot("memprof-export-to-dot", cl::init(false), cl::Hidden, cl::desc("Export graph to dot files."))</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/indexcallsitecontextgraph/#aa4f54d80f1f0152753a9b60e3f5aea61">anonymous{MemProfContextDisambiguation.cpp}::IndexCallsiteContextGraph::IndexCallsiteContextGraph</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/modulecallsitecontextgraph/#aeefc570485efea4da856d33ef3d16f2a">anonymous{MemProfContextDisambiguation.cpp}::ModuleCallsiteContextGraph::ModuleCallsiteContextGraph</a> and <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a4652a942c3bcd94d6540e3fb0238d356">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::process</a>.</p>

</div>
</div>

### MemProfCloneSuffix {#ad87209e87867681064f37e6f66b2ae05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string MemProfCloneSuffix = ".memprof."</td>
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



<p>Definition at line 1895 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="#abf5139fde11ca45c9c419e1989ebf553">getMemProfFuncName</a> and <a href="#a29b56ebd4926238fd5e5022b7f80458f">isMemProfClone</a>.</p>

</div>
</div>

### MemProfImportSummary {#ac577f50d4870e58f3716e9f06eca5491}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; MemProfImportSummary("memprof-import-summary", cl::desc("Import summary to use for testing the ThinLTO backend via opt"), cl::Hidden)</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memprofcontextdisambiguation/#abfc69efe5e1b61e475c294e22e3601d5">llvm::MemProfContextDisambiguation::MemProfContextDisambiguation</a>.</p>

</div>
</div>

### MemProfReportHintedSizes {#a7af832ec142a036af0c6439583d7785d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt;bool&gt; MemProfReportHintedSizes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### MinClonedColdBytePercent {#a5d202769d4373260d2e9158487a94986}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt;unsigned&gt; MinClonedColdBytePercent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### TailCallSearchDepth {#a125b93089af5c0962f1368f1e56c4176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; TailCallSearchDepth("memprof-tail-call-search-depth", cl::init(5), cl::Hidden, cl::desc("Max depth to recursively search for missing " "frames through tail calls."))</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### VerifyCCG {#aadb6dc3c4ec78048014fdbb22a247ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; VerifyCCG("memprof-verify-ccg", cl::init(false), cl::Hidden, cl::desc("Perform verification checks on CallingContextGraph."))</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#af222e51d6efae0aeb9ea76cac1b46300">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::assignFunctions</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a35fd3a36d7623912363f7bc2550aef0b">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::identifyClones</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a4652a942c3bcd94d6540e3fb0238d356">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::process</a> and <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a6e0e5a23aea2cd0d2bc271342e6e5c34">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::updateStackNodes</a>.</p>

</div>
</div>

### VerifyNodes {#af3a6c5634d5eb4b762f53497d495c4b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; VerifyNodes("memprof-verify-nodes", cl::init(false), cl::Hidden, cl::desc("Perform frequent verification checks on nodes."))</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#af222e51d6efae0aeb9ea76cac1b46300">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::assignFunctions</a>.</p>

</div>
</div>

</div>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"memprof-context-disambiguation"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
