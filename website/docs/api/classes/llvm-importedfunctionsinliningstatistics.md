---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/importedfunctionsinliningstatistics
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ImportedFunctionsInliningStatistics` Class Reference

<p>Calculate and dump ThinLTO specific inliner stats. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ImportedFunctionsInliningStatistics { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">llvm/Analysis/Utils/ImportedFunctionsInliningStatistics.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e0ebace9ffec1f8c233fb1c3138dbff">NodesMapTy</a> = <a href="/web-llvm/docs/api/classes/llvm/stringmap">llvm::StringMap</a>&lt; std::unique_ptr&lt; InlineGraphNode &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75cd65629ce3d058d760bbd05b8db344">SortedNodesTy</a> = std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringmap/#ae4367476b57e62bd12547515281177e8">NodesMapTy::MapEntryTy</a> * &gt;</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41874db064d638d7527a03f896dad428">ImportedFunctionsInliningStatistics</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d4d289221223b75026383a674d2ea66">ImportedFunctionsInliningStatistics</a> (const ImportedFunctionsInliningStatistics &amp;)=delete</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00fe0b2043a8218ede17ada91d286272">setModuleInfo</a> (const Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set information like AllFunctions, ImportedFunctions, <a href="/web-llvm/docs/api/structs/modulename">ModuleName</a>. <a href="#a00fe0b2043a8218ede17ada91d286272">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a869c36ec45c584dfa6f3d914d230b15f">recordInline</a> (const Function &amp;Caller, const Function &amp;Callee)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> inline of. <a href="#a869c36ec45c584dfa6f3d914d230b15f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a776e5ef304e07acc5bbbf585443459a4">dump</a> (bool Verbose)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump stats computed with InlinerStatistics class. <a href="#a776e5ef304e07acc5bbbf585443459a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">InlineGraphNode &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbf0cc45464890076496116b49a3d221">createInlineGraphNode</a> (const Function &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates new <a href="/web-llvm/docs/api/classes/node">Node</a> in NodeMap and sets attributes, or returns existed one. <a href="#abbf0cc45464890076496116b49a3d221">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c2a21a9626621a86b9acb220152c083">calculateRealInlines</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b73db1b13de3201bdd4cce9cd3a10cc">dfs</a> (InlineGraphNode &amp;GraphNode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">SortedNodesTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a356b49d03dec901f6f40d9b016fa5716">getSortedNodes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns vector of elements sorted by (-NumberOfInlines, -NumberOfRealInlines, FunctionName). <a href="#a356b49d03dec901f6f40d9b016fa5716">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">NodesMapTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12853e2eaa02c9a68a93994e058d36b6">NodesMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This map manage life of all InlineGraphNodes. <a href="#a12853e2eaa02c9a68a93994e058d36b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a213b28d3482cab59a4dae1f8f646c1de">NonImportedCallers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Non external functions that have some other function inlined inside. <a href="#a213b28d3482cab59a4dae1f8f646c1de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed26b62e0c2593499506847bede5ad83">AllFunctions</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e542745d90c059ab46aff1c37540e1d">ImportedFunctions</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad14ba258aaf4c55b3cc15f50f14a5ba5">ModuleName</a></td>
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

<p>Calculate and dump ThinLTO specific inliner stats.</p>


<p>The main statistics are: (1) Number of inlined imported functions, (2) Number of imported functions inlined into importing module (indirect), (3) Number of non imported functions inlined into importing module (indirect). The difference between first and the second is that first stat counts all performed inlines on imported functions, but the second one only the functions that have been eventually inlined to a function in the importing module (by a chain of inlines). Because llvm uses bottom-up inliner, it is possible to e.g. import function <span class="doxyComputerOutput">A</span>, <span class="doxyComputerOutput">B</span> and then inline <span class="doxyComputerOutput">B</span> to <span class="doxyComputerOutput">A</span>, and after this <span class="doxyComputerOutput">A</span> might be too big to be inlined into some other function that calls it. It calculates this statistic by building graph, where the nodes are functions, and edges are performed inlines and then by marking the edges starting from not imported function.</p>


<p>If <span class="doxyComputerOutput">Verbose</span> is set to true, then it also dumps statistics per each inlined function, sorted by the greatest inlines count like</p>


<ul class="doxyList ">
<li>number of performed inlines</li>
<li>number of performed inlines to importing module</li>
</ul>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">ImportedFunctionsInliningStatistics.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### NodesMapTy {#a8e0ebace9ffec1f8c233fb1c3138dbff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImportedFunctionsInliningStatistics::NodesMapTy = 
      llvm::StringMap&lt;std::unique_ptr&lt;InlineGraphNode&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">ImportedFunctionsInliningStatistics.h</a>.</p>

</div>
</div>

### SortedNodesTy {#a75cd65629ce3d058d760bbd05b8db344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ImportedFunctionsInliningStatistics::SortedNodesTy = 
      std::vector&lt;const NodesMapTy::MapEntryTy*&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">ImportedFunctionsInliningStatistics.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ImportedFunctionsInliningStatistics() {#a41874db064d638d7527a03f896dad428}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImportedFunctionsInliningStatistics::ImportedFunctionsInliningStatistics ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">ImportedFunctionsInliningStatistics.h</a>.</p>


<p>Referenced by <a href="#a7d4d289221223b75026383a674d2ea66">ImportedFunctionsInliningStatistics</a>.</p>

</div>
</div>

### ImportedFunctionsInliningStatistics() {#a7d4d289221223b75026383a674d2ea66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ImportedFunctionsInliningStatistics::ImportedFunctionsInliningStatistics (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/importedfunctionsinliningstatistics">ImportedFunctionsInliningStatistics</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">ImportedFunctionsInliningStatistics.h</a>.</p>


<p>References <a href="#a41874db064d638d7527a03f896dad428">ImportedFunctionsInliningStatistics</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adacba4cb06d1dd9232ee3d2d49a44d8fad4a9fa383ab700c5bdd6f31cf7df0faf">llvm::Verbose</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a776e5ef304e07acc5bbbf585443459a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ImportedFunctionsInliningStatistics::dump (bool Verbose)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump stats computed with InlinerStatistics class.</p>


<p>If</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Verbose</td>
<td class="doxyParamItemDescription"><p>is true then separate statistics for every inlined function will be printed.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">ImportedFunctionsInliningStatistics.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/importedfunctionsinliningstatistics-cpp">ImportedFunctionsInliningStatistics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/importedfunctionsinliningstatistics-cpp/#a3fadf39a420def06338f8c70f3c236ea">getStatString</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adacba4cb06d1dd9232ee3d2d49a44d8fad4a9fa383ab700c5bdd6f31cf7df0faf">llvm::Verbose</a>.</p>

</div>
</div>

### recordInline() {#a869c36ec45c584dfa6f3d914d230b15f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ImportedFunctionsInliningStatistics::recordInline (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Callee)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> inline of.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Callee</td>
<td class="doxyParamItemDescription"><p>to</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Caller</td>
<td class="doxyParamItemDescription"><p>for statistis.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">ImportedFunctionsInliningStatistics.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/importedfunctionsinliningstatistics-cpp">ImportedFunctionsInliningStatistics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### setModuleInfo() {#a00fe0b2043a8218ede17ada91d286272}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ImportedFunctionsInliningStatistics::setModuleInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set information like AllFunctions, ImportedFunctions, <a href="/web-llvm/docs/api/structs/modulename">ModuleName</a>.</p>

<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">ImportedFunctionsInliningStatistics.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/importedfunctionsinliningstatistics-cpp">ImportedFunctionsInliningStatistics.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### calculateRealInlines() {#a0c2a21a9626621a86b9acb220152c083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ImportedFunctionsInliningStatistics::calculateRealInlines ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">ImportedFunctionsInliningStatistics.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/importedfunctionsinliningstatistics-cpp">ImportedFunctionsInliningStatistics.cpp</a>.</p>

</div>
</div>

### createInlineGraphNode() {#abbf0cc45464890076496116b49a3d221}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImportedFunctionsInliningStatistics::InlineGraphNode &amp; ImportedFunctionsInliningStatistics::createInlineGraphNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates new <a href="/web-llvm/docs/api/classes/node">Node</a> in NodeMap and sets attributes, or returns existed one.</p>

<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">ImportedFunctionsInliningStatistics.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/importedfunctionsinliningstatistics-cpp">ImportedFunctionsInliningStatistics.cpp</a>.</p>

</div>
</div>

### dfs() {#a5b73db1b13de3201bdd4cce9cd3a10cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ImportedFunctionsInliningStatistics::dfs (InlineGraphNode &amp; GraphNode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">ImportedFunctionsInliningStatistics.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/importedfunctionsinliningstatistics-cpp">ImportedFunctionsInliningStatistics.cpp</a>.</p>

</div>
</div>

### getSortedNodes() {#a356b49d03dec901f6f40d9b016fa5716}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImportedFunctionsInliningStatistics::SortedNodesTy ImportedFunctionsInliningStatistics::getSortedNodes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns vector of elements sorted by (-NumberOfInlines, -NumberOfRealInlines, FunctionName).</p>

<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">ImportedFunctionsInliningStatistics.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/importedfunctionsinliningstatistics-cpp">ImportedFunctionsInliningStatistics.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllFunctions {#aed26b62e0c2593499506847bede5ad83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ImportedFunctionsInliningStatistics::AllFunctions = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">ImportedFunctionsInliningStatistics.h</a>.</p>

</div>
</div>

### ImportedFunctions {#a4e542745d90c059ab46aff1c37540e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ImportedFunctionsInliningStatistics::ImportedFunctions = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">ImportedFunctionsInliningStatistics.h</a>.</p>

</div>
</div>

### ModuleName {#ad14ba258aaf4c55b3cc15f50f14a5ba5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::ImportedFunctionsInliningStatistics::ModuleName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">ImportedFunctionsInliningStatistics.h</a>.</p>

</div>
</div>

### NodesMap {#a12853e2eaa02c9a68a93994e058d36b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodesMapTy llvm::ImportedFunctionsInliningStatistics::NodesMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This map manage life of all InlineGraphNodes.</p>


<p>Unique pointer to InlineGraphNode used since the node pointers are also saved in the InlinedCallees vector. If it would store InlineGraphNode instead then the address of the node would not be invariant.</p>


<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">ImportedFunctionsInliningStatistics.h</a>.</p>

</div>
</div>

### NonImportedCallers {#a213b28d3482cab59a4dae1f8f646c1de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;StringRef&gt; llvm::ImportedFunctionsInliningStatistics::NonImportedCallers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Non external functions that have some other function inlined inside.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">ImportedFunctionsInliningStatistics.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">ImportedFunctionsInliningStatistics.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/importedfunctionsinliningstatistics-cpp">ImportedFunctionsInliningStatistics.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
