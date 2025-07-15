---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-memprofcontextdisambiguation-cpp-/indexcallsitecontextgraph
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IndexCallsiteContextGraph` Class Reference

<p>CRTP derived class for graphs built from summary index (ThinLTO). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{MemProfContextDisambiguation.cpp}::IndexCallsiteContextGraph { ... }
</div>

## Base class

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

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4f54d80f1f0152753a9b60e3f5aea61">IndexCallsiteContextGraph</a> (ModuleSummaryIndex &amp;Index, llvm::function_ref&lt; bool(GlobalValue::GUID, const GlobalValueSummary *)&gt; isPrevailing)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8bd957a75b45aa78942c4cceab29725">~IndexCallsiteContextGraph</a> ()</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ff2908eb339445dccaaa621f2196cfe">getStackId</a> (uint64_t IdOrIndex) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c15cf4adb402623a666aac9877b987d">getCalleeFunc</a> (IndexCall &amp;Call)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ca3f1f1099ca3dcfb268acedfc1de73">calleeMatchesFunc</a> (IndexCall &amp;Call, const FunctionSummary *Func, const FunctionSummary *CallerFunc, std::vector&lt; std::pair&lt; IndexCall, FunctionSummary * &gt; &gt; &amp;FoundCalleeChain)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab71ec014e0304a8125ff0938be1d3c1">sameCallee</a> (IndexCall &amp;Call1, IndexCall &amp;Call2)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03f1bfa63e21c3a7201bb2e7f6d23db0">findProfiledCalleeThroughTailCalls</a> (ValueInfo ProfiledCallee, ValueInfo CurCallee, unsigned Depth, std::vector&lt; std::pair&lt; IndexCall, FunctionSummary * &gt; &gt; &amp;FoundCalleeChain, bool &amp;FoundMultipleCalleeChains)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af120586d3fbe5b845f50e640f7b20c1b">getLastStackId</a> (IndexCall &amp;Call)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1315552c9ad48061fdce810480761710">getStackIdsWithContextNodesForCall</a> (IndexCall &amp;Call)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46788dc62b9eafd99c92d54dda076868">updateAllocationCall</a> (CallInfo &amp;Call, AllocationType AllocType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27">AllocationType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6c26087c766a44b0ce10d50a338d11b">getAllocationCallType</a> (const CallInfo &amp;Call) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5851cd211f18cbe6b23f3c80b4329f0">updateCall</a> (CallInfo &amp;CallerCall, FuncInfo CalleeFunc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph">CallsiteContextGraph</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/indexcallsitecontextgraph">IndexCallsiteContextGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/indexcall">IndexCall</a> &gt;<a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#ab7b317804874313a6eaa944cc003698c">::FuncInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade92e58c355691f3c0b05fba5168e664">cloneFunctionForCallsite</a> (FuncInfo &amp;Func, CallInfo &amp;Call, std::map&lt; CallInfo, CallInfo &gt; &amp;CallMap, std::vector&lt; CallInfo &gt; &amp;CallsWithMetadataInFunc, unsigned CloneNo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a620da4b8f722dfe539f2e3b8b28ef280">getLabel</a> (const FunctionSummary *Func, const IndexCall &amp;Call, unsigned CloneNo) const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d62c4d23e59c69c455df078abcdc505">CallsiteContextGraph&lt; IndexCallsiteContextGraph, FunctionSummary, IndexCall &gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> *, <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad09943c94948738707f6000306d31e49">FSToVIMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2fd0c5158584901d9e0bede7510d8c9">Index</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> *)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbf4d70fbba9706ec4052ec663af1785">isPrevailing</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> *, std::map&lt; <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a>, std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/callsiteinfo">CallsiteInfo</a> &gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d950912557f1c0f1d9859117ec76641">FunctionCalleesToSynthesizedCallsiteInfos</a></td>
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

<p>CRTP derived class for graphs built from summary index (ThinLTO).</p>

<p>Definition at line 846 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IndexCallsiteContextGraph() {#aa4f54d80f1f0152753a9b60e3f5aea61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexCallsiteContextGraph::IndexCallsiteContextGraph (<a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> *)&gt; isPrevailing)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 850 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#adf8f8ad14c08099e793ca64a0768c96a">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; IndexCallsiteContextGraph, FunctionSummary, IndexCall &gt;::addAllocNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a3c04d483e66e81efc4812a2d38b93a8d">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; IndexCallsiteContextGraph, FunctionSummary, IndexCall &gt;::addStackNodesForMIB</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#a20c00c2a87e53869acc65017497e9fe2">anonymous{MemProfContextDisambiguation.cpp}::allocTypeToUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#af4908b838f5705fa3d04d8884821a574">DumpCCG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#a3f48d17e9412f965032b446536238a61">ExportToDot</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#ae120eda05be009e7e1124ac882412cad">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; IndexCallsiteContextGraph, FunctionSummary, IndexCall &gt;::exportToDot</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a19492f5e9a4b13d1b78b56c75b1f58a8">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; IndexCallsiteContextGraph, FunctionSummary, IndexCall &gt;::FuncToCallsWithMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a9f3bc3cacc5c440fc83d37726a3af8aa">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; IndexCallsiteContextGraph, FunctionSummary, IndexCall &gt;::handleCallsitesWithMultipleTargets</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a308b65a044b4f53e31a2026a81c991d2">llvm::GlobalValue::isLocalLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp/#a696467f077d0e94dc6b3f171acc6be25">MemProfReportHintedSizes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#af7e93a7f4bbea37887b3fc9be720b8d0">MinClonedColdBytePercent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a6e0e5a23aea2cd0d2bc271342e6e5c34">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; IndexCallsiteContextGraph, FunctionSummary, IndexCall &gt;::updateStackNodes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~IndexCallsiteContextGraph() {#ac8bd957a75b45aa78942c4cceab29725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MemProfContextDisambiguation.cpp}::IndexCallsiteContextGraph::~IndexCallsiteContextGraph ()</td>
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



<p>Definition at line 855 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### calleeMatchesFunc() {#a3ca3f1f1099ca3dcfb268acedfc1de73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IndexCallsiteContextGraph::calleeMatchesFunc (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/indexcall">IndexCall</a> &amp; Call, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> * Func, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> * CallerFunc, std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/indexcall">IndexCall</a>, <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> * &gt; &gt; &amp; FoundCalleeChain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 873 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### cloneFunctionForCallsite() {#ade92e58c355691f3c0b05fba5168e664}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallsiteContextGraph&lt; IndexCallsiteContextGraph, FunctionSummary, IndexCall &gt;::FuncInfo IndexCallsiteContextGraph::cloneFunctionForCallsite (<a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#ab7b317804874313a6eaa944cc003698c">FuncInfo</a> &amp; Func, <a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#a8b8d198163dffec6d0db6c9b73917bce">CallInfo</a> &amp; Call, std::map&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#a8b8d198163dffec6d0db6c9b73917bce">CallInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#a8b8d198163dffec6d0db6c9b73917bce">CallInfo</a> &gt; &amp; CallMap, std::vector&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#a8b8d198163dffec6d0db6c9b73917bce">CallInfo</a> &gt; &amp; CallsWithMetadataInFunc, unsigned CloneNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 889 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### findProfiledCalleeThroughTailCalls() {#a03f1bfa63e21c3a7201bb2e7f6d23db0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IndexCallsiteContextGraph::findProfiledCalleeThroughTailCalls (<a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> ProfiledCallee, <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> CurCallee, unsigned Depth, std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/indexcall">IndexCall</a>, <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> * &gt; &gt; &amp; FoundCalleeChain, bool &amp; FoundMultipleCalleeChains)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 878 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getAllocationCallType() {#aa6c26087c766a44b0ce10d50a338d11b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocationType IndexCallsiteContextGraph::getAllocationCallType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#a8b8d198163dffec6d0db6c9b73917bce">CallInfo</a> &amp; Call)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 885 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getCalleeFunc() {#a4c15cf4adb402623a666aac9877b987d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FunctionSummary * IndexCallsiteContextGraph::getCalleeFunc (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/indexcall">IndexCall</a> &amp; Call)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 872 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getLabel() {#a620da4b8f722dfe539f2e3b8b28ef280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string IndexCallsiteContextGraph::getLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> * Func, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/indexcall">IndexCall</a> &amp; Call, unsigned CloneNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 893 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getLastStackId() {#af120586d3fbe5b845f50e640f7b20c1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t IndexCallsiteContextGraph::getLastStackId (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/indexcall">IndexCall</a> &amp; Call)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 882 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getStackId() {#a0ff2908eb339445dccaaa621f2196cfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t IndexCallsiteContextGraph::getStackId (uint64_t IdOrIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 871 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getStackIdsWithContextNodesForCall() {#a1315552c9ad48061fdce810480761710}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; uint64_t &gt; IndexCallsiteContextGraph::getStackIdsWithContextNodesForCall (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/indexcall">IndexCall</a> &amp; Call)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 883 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### sameCallee() {#aab71ec014e0304a8125ff0938be1d3c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IndexCallsiteContextGraph::sameCallee (<a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/indexcall">IndexCall</a> &amp; Call1, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/indexcall">IndexCall</a> &amp; Call2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 877 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### updateAllocationCall() {#a46788dc62b9eafd99c92d54dda076868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndexCallsiteContextGraph::updateAllocationCall (<a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#a8b8d198163dffec6d0db6c9b73917bce">CallInfo</a> &amp; Call, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27">AllocationType</a> AllocType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 884 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### updateCall() {#ae5851cd211f18cbe6b23f3c80b4329f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndexCallsiteContextGraph::updateCall (<a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#a8b8d198163dffec6d0db6c9b73917bce">CallInfo</a> &amp; CallerCall, <a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#ab7b317804874313a6eaa944cc003698c">FuncInfo</a> CalleeFunc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 886 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CallsiteContextGraph&lt; IndexCallsiteContextGraph, FunctionSummary, IndexCall &gt; {#a4d62c4d23e59c69c455df078abcdc505}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend anonymous{MemProfContextDisambiguation.cpp}::IndexCallsiteContextGraph::CallsiteContextGraph&lt; IndexCallsiteContextGraph, FunctionSummary, IndexCall &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 868 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### FSToVIMap {#ad09943c94948738707f6000306d31e49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;const FunctionSummary *, ValueInfo&gt; anonymous{MemProfContextDisambiguation.cpp}::IndexCallsiteContextGraph::FSToVIMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 898 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### FunctionCalleesToSynthesizedCallsiteInfos {#a1d950912557f1c0f1d9859117ec76641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;FunctionSummary *, std::map&lt;ValueInfo, std::unique_ptr&lt;CallsiteInfo&gt; &gt; &gt; anonymous{MemProfContextDisambiguation.cpp}::IndexCallsiteContextGraph::FunctionCalleesToSynthesizedCallsiteInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 910 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### Index {#ab2fd0c5158584901d9e0bede7510d8c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ModuleSummaryIndex&amp; anonymous{MemProfContextDisambiguation.cpp}::IndexCallsiteContextGraph::Index</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 900 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### isPrevailing {#afbf4d70fbba9706ec4052ec663af1785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::function_ref&lt;bool(GlobalValue::GUID, const GlobalValueSummary *)&gt; anonymous{MemProfContextDisambiguation.cpp}::IndexCallsiteContextGraph::isPrevailing</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 902 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
