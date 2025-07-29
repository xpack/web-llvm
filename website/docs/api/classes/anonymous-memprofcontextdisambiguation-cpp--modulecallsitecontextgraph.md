---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-memprofcontextdisambiguation-cpp-/modulecallsitecontextgraph
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ModuleCallsiteContextGraph` Class

<p>CRTP derived class for graphs built from IR (regular LTO). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{MemProfContextDisambiguation.cpp}::ModuleCallsiteContextGraph { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeefc570485efea4da856d33ef3d16f2a">ModuleCallsiteContextGraph</a> (Module &amp;M, llvm::function_ref&lt; OptimizationRemarkEmitter &amp;(Function *)&gt; OREGetter)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e3cd6adee641a128d26fdae5d48791e">getStackId</a> (uint64_t IdOrIndex) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5e3a27ec9ef6ade99fa0234c662aae1">getCalleeFunc</a> (Instruction *Call)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a466aa9e9151f0af6c4fb7bab264cdd52">calleeMatchesFunc</a> (Instruction *Call, const Function *Func, const Function *CallerFunc, std::vector&lt; std::pair&lt; Instruction *, Function * &gt; &gt; &amp;FoundCalleeChain)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1b117ebf7172812943e0e716bf71ea0">sameCallee</a> (Instruction *Call1, Instruction *Call2)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f8232f2aee9ff0e3386d4c0e690fc86">findProfiledCalleeThroughTailCalls</a> (const Function *ProfiledCallee, Value *CurCallee, unsigned Depth, std::vector&lt; std::pair&lt; Instruction *, Function * &gt; &gt; &amp;FoundCalleeChain, bool &amp;FoundMultipleCalleeChains)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88b184b0213019caa4171e6099d643a8">getLastStackId</a> (Instruction *Call)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa00df2308e0b6b2701c202073c8f02bc">getStackIdsWithContextNodesForCall</a> (Instruction *Call)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ea73858859e936fb1b3c4f03eb837b1">updateAllocationCall</a> (CallInfo &amp;Call, AllocationType AllocType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab60bcb1c8b6ed26e4d91964db8a0b71f">getAllocationCallType</a> (const CallInfo &amp;Call) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5c7868e2ae00277d2c2f914776335b9">updateCall</a> (CallInfo &amp;CallerCall, FuncInfo CalleeFunc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph">CallsiteContextGraph</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/modulecallsitecontextgraph">ModuleCallsiteContextGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;<a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#ab7b317804874313a6eaa944cc003698c">::FuncInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aead53f6a8d6f6d3b193483c5b1d2e73a">cloneFunctionForCallsite</a> (FuncInfo &amp;Func, CallInfo &amp;Call, std::map&lt; CallInfo, CallInfo &gt; &amp;CallMap, std::vector&lt; CallInfo &gt; &amp;CallsWithMetadataInFunc, unsigned CloneNo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bf6683c201f27821eab241463e39bd9">getLabel</a> (const Function *Func, const Instruction *Call, unsigned CloneNo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d6dc349ca3f98a9c056110f16f12508">CallsiteContextGraph&lt; ModuleCallsiteContextGraph, Function, Instruction * &gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4403459cc19dfaf669fad868192a8ada">Mod</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06e44e04a32456e624b0e4f5e27ec528">OREGetter</a></td>
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

<p>CRTP derived class for graphs built from IR (regular LTO).</p>

<p>Definition at line 768 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ModuleCallsiteContextGraph() {#aeefc570485efea4da856d33ef3d16f2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleCallsiteContextGraph::ModuleCallsiteContextGraph (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *)&gt; OREGetter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 772 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#adf8f8ad14c08099e793ca64a0768c96a">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; ModuleCallsiteContextGraph, Function, Instruction * &gt;::addAllocNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a3c04d483e66e81efc4812a2d38b93a8d">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; ModuleCallsiteContextGraph, Function, Instruction * &gt;::addStackNodesForMIB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#af4908b838f5705fa3d04d8884821a574">DumpCCG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad7ca5290dc5789cbeae763690e6edccf">llvm::mdconst::dyn_extract</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#a3f48d17e9412f965032b446536238a61">ExportToDot</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#ae120eda05be009e7e1124ac882412cad">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; ModuleCallsiteContextGraph, Function, Instruction * &gt;::exportToDot</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a19492f5e9a4b13d1b78b56c75b1f58a8">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; ModuleCallsiteContextGraph, Function, Instruction * &gt;::FuncToCallsWithMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a6adf5ed44d664399d019ab3727dc5bd9">llvm::memprof::getMIBAllocType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ab5636c9dedf3853480a075cefc7cc1fa">llvm::memprof::getMIBStackNode</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a9f3bc3cacc5c440fc83d37726a3af8aa">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; ModuleCallsiteContextGraph, Function, Instruction * &gt;::handleCallsitesWithMultipleTargets</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/#a6e0e5a23aea2cd0d2bc271342e6e5c34">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; ModuleCallsiteContextGraph, Function, Instruction * &gt;::updateStackNodes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### calleeMatchesFunc() {#a466aa9e9151f0af6c4fb7bab264cdd52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ModuleCallsiteContextGraph::calleeMatchesFunc (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Call, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Func, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * CallerFunc, std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &gt; &amp; FoundCalleeChain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 782 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### cloneFunctionForCallsite() {#aead53f6a8d6f6d3b193483c5b1d2e73a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallsiteContextGraph&lt; ModuleCallsiteContextGraph, Function, Instruction * &gt;::FuncInfo ModuleCallsiteContextGraph::cloneFunctionForCallsite (<a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#ab7b317804874313a6eaa944cc003698c">FuncInfo</a> &amp; Func, <a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#a8b8d198163dffec6d0db6c9b73917bce">CallInfo</a> &amp; Call, std::map&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#a8b8d198163dffec6d0db6c9b73917bce">CallInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#a8b8d198163dffec6d0db6c9b73917bce">CallInfo</a> &gt; &amp; CallMap, std::vector&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#a8b8d198163dffec6d0db6c9b73917bce">CallInfo</a> &gt; &amp; CallsWithMetadataInFunc, unsigned CloneNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### findProfiledCalleeThroughTailCalls() {#a6f8232f2aee9ff0e3386d4c0e690fc86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ModuleCallsiteContextGraph::findProfiledCalleeThroughTailCalls (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * ProfiledCallee, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * CurCallee, unsigned Depth, std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &gt; &amp; FoundCalleeChain, bool &amp; FoundMultipleCalleeChains)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 786 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getAllocationCallType() {#ab60bcb1c8b6ed26e4d91964db8a0b71f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocationType ModuleCallsiteContextGraph::getAllocationCallType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#a8b8d198163dffec6d0db6c9b73917bce">CallInfo</a> &amp; Call)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getCalleeFunc() {#ab5e3a27ec9ef6ade99fa0234c662aae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function * ModuleCallsiteContextGraph::getCalleeFunc (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Call)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getLabel() {#a5bf6683c201f27821eab241463e39bd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string ModuleCallsiteContextGraph::getLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Func, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Call, unsigned CloneNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getLastStackId() {#a88b184b0213019caa4171e6099d643a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ModuleCallsiteContextGraph::getLastStackId (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Call)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 790 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getStackId() {#a0e3cd6adee641a128d26fdae5d48791e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ModuleCallsiteContextGraph::getStackId (uint64_t IdOrIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 780 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### getStackIdsWithContextNodesForCall() {#aa00df2308e0b6b2701c202073c8f02bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; uint64_t &gt; ModuleCallsiteContextGraph::getStackIdsWithContextNodesForCall (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Call)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 791 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### sameCallee() {#ae1b117ebf7172812943e0e716bf71ea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ModuleCallsiteContextGraph::sameCallee (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Call1, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Call2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 785 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### updateAllocationCall() {#a7ea73858859e936fb1b3c4f03eb837b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleCallsiteContextGraph::updateAllocationCall (<a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#a8b8d198163dffec6d0db6c9b73917bce">CallInfo</a> &amp; Call, <a href="/web-llvm/docs/api/namespaces/llvm/#a230980cf62b697d22ffdda32f6118e27">AllocationType</a> AllocType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 792 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### updateCall() {#ae5c7868e2ae00277d2c2f914776335b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleCallsiteContextGraph::updateCall (<a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#a8b8d198163dffec6d0db6c9b73917bce">CallInfo</a> &amp; CallerCall, <a href="/web-llvm/docs/api/namespaces/anonymous-memprofcontextdisambiguation-cpp-/#ab7b317804874313a6eaa944cc003698c">FuncInfo</a> CalleeFunc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 794 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CallsiteContextGraph&lt; ModuleCallsiteContextGraph, Function, Instruction \* &gt; {#a7d6dc349ca3f98a9c056110f16f12508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend anonymous{MemProfContextDisambiguation.cpp}::ModuleCallsiteContextGraph::CallsiteContextGraph&lt; ModuleCallsiteContextGraph, Function, Instruction * &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 777 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### Mod {#a4403459cc19dfaf669fad868192a8ada}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Module&amp; anonymous{MemProfContextDisambiguation.cpp}::ModuleCallsiteContextGraph::Mod</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 804 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

### OREGetter {#a06e44e04a32456e624b0e4f5e27ec528}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::function_ref&lt;OptimizationRemarkEmitter &amp;(Function *)&gt; anonymous{MemProfContextDisambiguation.cpp}::ModuleCallsiteContextGraph::OREGetter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp">MemProfContextDisambiguation.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
