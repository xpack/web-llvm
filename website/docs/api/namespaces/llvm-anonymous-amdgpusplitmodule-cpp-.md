---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{AMDGPUSplitModule.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::anonymous{AMDGPUSplitModule.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/anonymous-amdgpusplitmodule-cpp-/splitmoduletimer">SplitModuleTimer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph">SplitGraph</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AMDGPUSplitModule's view of the source <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>, as a graph of all components that can be split into different modules. <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitproposal">SplitProposal</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a module splitting proposal. <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitproposal/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/recursivesearchsplitting">RecursiveSearchSplitting</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Partitioning algorithm. <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/recursivesearchsplitting/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c86b2852d6e78ed3aaaf412ed290186">CostType</a> = <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a5dbf65370a0656ea05a0aa97380c15cc">InstructionCost::CostType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa50f69d065e9d9f68b780be7495ec72c">FunctionsCostMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="#a0c86b2852d6e78ed3aaaf412ed290186">CostType</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea0eeab0d3382511b47dc3ae11736484">GetTTIFn</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37d07b3d937c118303cb6668c9605093">SplitGraphEdgeDstIterator</a> = <a href="/web-llvm/docs/api/classes/llvm/mapped-iterator">mapped_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a4678598cfb6250c999f0aeb17565ed42">SplitGraph::edges_iterator</a>, decltype(&amp;<a href="#aa45ff7fccb3b682c54c9051e2c74705d">mapEdgeToDst</a>)&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ffb58efadf5885f67a4ecd791d2b218">formatRatioOf</a> (CostType Num, CostType Dem)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab8baf5cac98f374fa37771b1491d59a">isNonCopyable</a> (const Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks whether a given function is non-copyable. <a href="#aab8baf5cac98f374fa37771b1491d59a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d232c3c6e60c94891fffed1f9277e8a">externalize</a> (GlobalValue &amp;GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">GV</span> has local linkage, make it external + hidden. <a href="#a6d232c3c6e60c94891fffed1f9277e8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a0c86b2852d6e78ed3aaaf412ed290186">CostType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3884c27912d0714a0f475680f6324b3d">calculateFunctionCosts</a> (GetTTIFn GetTTI, Module &amp;M, FunctionsCostMap &amp;CostMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a> analysis function. <a href="#a3884c27912d0714a0f475680f6324b3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af19f187ada651861964b8c5f77e2e6e7">canBeIndirectlyCalled</a> (const Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f04c6f908fc9d132e025f31d40fc976">handleCalleesMD</a> (const Instruction &amp;I, SetVector&lt; Function * &gt; &amp;Callees)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if <span class="doxyComputerOutput">I</span> has MD_callees and if it does, parse it and put the function in <span class="doxyComputerOutput">Callees</span>. <a href="#a4f04c6f908fc9d132e025f31d40fc976">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/node">SplitGraph::Node</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa45ff7fccb3b682c54c9051e2c74705d">mapEdgeToDst</a> (const SplitGraph::Edge *E)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3826bdde6c7b4e85b4b484ead3c2c0b7">needsConservativeImport</a> (const GlobalValue *GV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6e8eb04697a9174b65bf56d1a480310">printPartitionSummary</a> (raw_ostream &amp;OS, unsigned N, const Module &amp;M, unsigned PartCost, unsigned ModuleCost)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prints a summary of the partition <span class="doxyComputerOutput">N</span>, represented by module <span class="doxyComputerOutput">M</span>, to <span class="doxyComputerOutput">OS</span>. <a href="#ab6e8eb04697a9174b65bf56d1a480310">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa718ad43704d8324301fe03964cdc7c3">evaluateProposal</a> (SplitProposal &amp;Best, SplitProposal New)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6239eff86084387afa955637045370bb">cloneAll</a> (const Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Trivial helper to create an identical copy of <span class="doxyComputerOutput">M</span>. <a href="#a6239eff86084387afa955637045370bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97973584f850e83ab0c845def98d9587">writeDOTGraph</a> (const SplitGraph &amp;SG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Writes <span class="doxyComputerOutput">SG</span> as a DOTGraph to ModuleDotCfgDir if requested. <a href="#a97973584f850e83ab0c845def98d9587">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0706966ac4f391854346bebfcda816fa">splitAMDGPUModule</a> (GetTTIFn GetTTI, Module &amp;M, unsigned NumParts, function_ref&lt; void(std::unique_ptr&lt; Module &gt; MPart)&gt; ModuleCallback)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02273768ec41f48168b8b464f639bcd3">MaxDepth</a>("amdgpu-module-splitting-max-depth", cl::desc("maximum search depth. 0 forces a greedy approach. " "warning: the algorithm is up to O(2^N), where N is the max depth."), cl::init(8))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; float &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa109a30d0599119589438ed40cf7c7b">LargeFnFactor</a>("amdgpu-module-splitting-large-threshold", cl::init(2.0f), cl::Hidden, cl::desc("when max depth is reached and we can no longer branch out, this " "value determines if a function is worth merging into an already " "existing partition to reduce code duplication. This is a factor " "of the ideal partition size, e.g. 2.0 means we consider the " "function for merging if its cost (including its callees) is 2x the " "size of an ideal partition."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; float &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48d50e56a2dbc8c6f77083f912605294">LargeFnOverlapForMerge</a>("amdgpu-module-splitting-merge-threshold", cl::init(0.7f), cl::Hidden, cl::desc("when a function is considered for merging into a partition that " "already contains some of its callees, do the merge if at least " "n% of the code it can reach is already present inside the " "partition; e.g. 0.7 means only merge >70%"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49e00f99e0c57b7f9e62bc578fa85bf4">NoExternalizeGlobals</a>("amdgpu-module-splitting-no-externalize-globals", cl::Hidden, cl::desc("disables externalization of global variable with local linkage; " "may cause globals to be duplicated which increases binary size"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa08ecbf5df71f6c94b76cf8d745df92d">NoExternalizeOnAddrTaken</a>("amdgpu-module-splitting-no-externalize-address-taken", cl::Hidden, cl::desc("disables externalization of functions whose addresses are taken"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf53892dc2a4464e4b6a535195772d86">ModuleDotCfgOutput</a>("amdgpu-module-splitting-print-module-dotcfg", cl::Hidden, cl::desc("output file to write out the dotgraph " "representation of the input module"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84426ac86be4408aeeb7b9d3364648cd">PartitionSummariesOutput</a>("amdgpu-module-splitting-print-partition-summaries", cl::Hidden, cl::desc("output file to write out a summary of " "the partitions created for each module"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e9d93a9c62f28bebeefb524a30f1d93">UseLockFile</a>("amdgpu-module-splitting-serial-execution", cl::Hidden, cl::desc("use a lock file so only one process in the system " "can run this pass at once. useful to avoid mangled " "debug output in multithreaded environments."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a660c994791147eb5577de9c7bc68b937">DebugProposalSearch</a>("amdgpu-module-splitting-debug-proposal-search", cl::Hidden, cl::desc("print all proposals received and whether " "they were rejected or accepted"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a286dd4db76f60ca092a2a00292b5638d">InvalidPID</a> = -1</td>
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

## Typedefs

### CostType {#a0c86b2852d6e78ed3aaaf412ed290186}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::anonymous{AMDGPUSplitModule.cpp}::CostType =  InstructionCost::CostType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

### FunctionsCostMap {#aa50f69d065e9d9f68b780be7495ec72c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::anonymous{AMDGPUSplitModule.cpp}::FunctionsCostMap =  DenseMap&lt;const Function *, CostType&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

### GetTTIFn {#aea0eeab0d3382511b47dc3ae11736484}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::anonymous{AMDGPUSplitModule.cpp}::GetTTIFn =  function_ref&lt;const TargetTransformInfo &amp;(Function &amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

### SplitGraphEdgeDstIterator {#a37d07b3d937c118303cb6668c9605093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraphEdgeDstIterator = 
    mapped_iterator&lt;SplitGraph::edges_iterator, decltype(&amp;mapEdgeToDst)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### calculateFunctionCosts() {#a3884c27912d0714a0f475680f6324b3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CostType llvm::anonymous{AMDGPUSplitModule.cpp}::calculateFunctionCosts (<a href="#aea0eeab0d3382511b47dc3ae11736484">GetTTIFn</a> GetTTI, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="#aa50f69d065e9d9f68b780be7495ec72c">FunctionsCostMap</a> &amp; CostMap)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a> analysis function.</p>


<p>Calculates the cost of each function in <span class="doxyComputerOutput">M</span></p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">GetTTI</td>
<td class="doxyParamItemDescription"><p>Abstract getter for <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">M</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> to analyze.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CostMap[out]</td>
<td class="doxyParamItemDescription"><p>Resulting <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> -&gt; <a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a> map.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The module's total cost.</p></dd>
</dl>


<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3884c27912d0714a0f475680f6324b3d">calculateFunctionCosts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a49c487a9395a6c384be8544cfb2cfccf">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a6de26b938774385a0a4fb0d0b2a32d48">llvm::InstructionCost::getMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3c65c76a817d60e322ff750366674a92">llvm::AMDGPU::isEntryFunctionCC</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272ca022565d444ccf496c0414bccefbcd9c8">llvm::TargetTransformInfo::TCC_Expensive</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba737cfc93e5a2ff961677d57186167e7c">llvm::TargetTransformInfo::TCK_CodeSize</a>.</p>


<p>Referenced by <a href="#a3884c27912d0714a0f475680f6324b3d">calculateFunctionCosts</a> and <a href="#a0706966ac4f391854346bebfcda816fa">splitAMDGPUModule</a>.</p>

</div>
</div>

### canBeIndirectlyCalled() {#af19f187ada651861964b8c5f77e2e6e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{AMDGPUSplitModule.cpp}::canBeIndirectlyCalled (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">F</span> can be indirectly called</p></dd>
</dl>


<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>References <a href="#af19f187ada651861964b8c5f77e2e6e7">canBeIndirectlyCalled</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3c65c76a817d60e322ff750366674a92">llvm::AMDGPU::isEntryFunctionCC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a85511f1d0a02c18e6c6dd590344664a4">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::buildGraph</a> and <a href="#af19f187ada651861964b8c5f77e2e6e7">canBeIndirectlyCalled</a>.</p>

</div>
</div>

### cloneAll() {#a6239eff86084387afa955637045370bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Module &gt; llvm::anonymous{AMDGPUSplitModule.cpp}::cloneAll (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>Trivial helper to create an identical copy of <span class="doxyComputerOutput">M</span>.</p>

<p>Definition at line 1354 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ae13b67a51d9f8061d598e82272b79b80">llvm::CloneModule</a>.</p>


<p>Referenced by <a href="#a0706966ac4f391854346bebfcda816fa">splitAMDGPUModule</a>.</p>

</div>
</div>

### evaluateProposal() {#aa718ad43704d8324301fe03964cdc7c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::anonymous{AMDGPUSplitModule.cpp}::evaluateProposal (<a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitproposal">SplitProposal</a> &amp; Best, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitproposal">SplitProposal</a> New)</td>
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



<p>Definition at line 1312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a660c994791147eb5577de9c7bc68b937">DebugProposalSearch</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitproposal/#a8b7f24ee69de158b68769c29464e6b1c">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::getBottleneckScore</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitproposal/#a2b814b24fd11bbfc3ffc4f289c8cd36b">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::getCodeSizeScore</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="#a0706966ac4f391854346bebfcda816fa">splitAMDGPUModule</a>.</p>

</div>
</div>

### externalize() {#a6d232c3c6e60c94891fffed1f9277e8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::anonymous{AMDGPUSplitModule.cpp}::externalize (<a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV)</td>
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

<p>If <span class="doxyComputerOutput">GV</span> has local linkage, make it external + hidden.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3ba1af4b9d9faa4a33729bbbecee83d1">llvm::GlobalValue::hasLocalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ad9d88ae321b98d8a3b7f394977ae6d7f">llvm::Value::hasName</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a7eade123587a08e674f2ca72e2443771">llvm::GlobalValue::HiddenVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a687973de03d041e04b50a76d19d4fd36">llvm::GlobalValue::setLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aa242d8ab89216c14beab812e07009b2a">llvm::GlobalValue::setVisibility</a>.</p>


<p>Referenced by <a href="#a0706966ac4f391854346bebfcda816fa">splitAMDGPUModule</a>.</p>

</div>
</div>

### formatRatioOf() {#a2ffb58efadf5885f67a4ecd791d2b218}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto llvm::anonymous{AMDGPUSplitModule.cpp}::formatRatioOf (<a href="#a0c86b2852d6e78ed3aaaf412ed290186">CostType</a> Num, <a href="#a0c86b2852d6e78ed3aaaf412ed290186">CostType</a> Dem)</td>
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




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Num</td>
<td class="doxyParamItemDescription"><p>numerator</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Dem</td>
<td class="doxyParamItemDescription"><p>denominator</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a printable object to print (Num/Dem) using "%0.2f".</p></dd>
</dl>


<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a> and <a href="#a2ffb58efadf5885f67a4ecd791d2b218">formatRatioOf</a>.</p>


<p>Referenced by <a href="#a2ffb58efadf5885f67a4ecd791d2b218">formatRatioOf</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitproposal/#a0215de52344b43a21c90bb5e2293a5fb">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::print</a> and <a href="#ab6e8eb04697a9174b65bf56d1a480310">printPartitionSummary</a>.</p>

</div>
</div>

### handleCalleesMD() {#a4f04c6f908fc9d132e025f31d40fc976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{AMDGPUSplitModule.cpp}::handleCalleesMD (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &amp; Callees)</td>
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

<p>Checks if <span class="doxyComputerOutput">I</span> has MD_callees and if it does, parse it and put the function in <span class="doxyComputerOutput">Callees</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if there was metadata and it was parsed correctly. false if there was no MD or if it contained unknown entries and parsing failed. If this returns false, <span class="doxyComputerOutput">Callees</span> will contain incomplete information and must not be used.</p></dd>
</dl>


<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#a86397deb1d9d25f7a17ce22c4d66482f">llvm::mdconst::extract_or_null</a>, <a href="#a4f04c6f908fc9d132e025f31d40fc976">handleCalleesMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a85511f1d0a02c18e6c6dd590344664a4">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::buildGraph</a> and <a href="#a4f04c6f908fc9d132e025f31d40fc976">handleCalleesMD</a>.</p>

</div>
</div>

### isNonCopyable() {#aab8baf5cac98f374fa37771b1491d59a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{AMDGPUSplitModule.cpp}::isNonCopyable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>Checks whether a given function is non-copyable.</p>


<p>Non-copyable functions cannot be cloned into multiple partitions, and only one copy of the function can be present across all partitions.</p>


<p>Kernel functions and external functions fall into this category. If we were to clone them, we would end up with multiple symbol definitions and a very unhappy linker.</p>


<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a3c65c76a817d60e322ff750366674a92">llvm::AMDGPU::isEntryFunctionCC</a> and <a href="#aab8baf5cac98f374fa37771b1491d59a">isNonCopyable</a>.</p>


<p>Referenced by <a href="#aab8baf5cac98f374fa37771b1491d59a">isNonCopyable</a>.</p>

</div>
</div>

### mapEdgeToDst() {#aa45ff7fccb3b682c54c9051e2c74705d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SplitGraph::Node * llvm::anonymous{AMDGPUSplitModule.cpp}::mapEdgeToDst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/edge">SplitGraph::Edge</a> * E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>.</p>

</div>
</div>

### needsConservativeImport() {#a3826bdde6c7b4e85b4b484ead3c2c0b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{AMDGPUSplitModule.cpp}::needsConservativeImport (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
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



<p>Definition at line 1286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a0706966ac4f391854346bebfcda816fa">splitAMDGPUModule</a>.</p>

</div>
</div>

### printPartitionSummary() {#ab6e8eb04697a9174b65bf56d1a480310}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::anonymous{AMDGPUSplitModule.cpp}::printPartitionSummary (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, unsigned N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, unsigned PartCost, unsigned ModuleCost)</td>
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

<p>Prints a summary of the partition <span class="doxyComputerOutput">N</span>, represented by module <span class="doxyComputerOutput">M</span>, to <span class="doxyComputerOutput">OS</span>.</p>

<p>Definition at line 1294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>References <a href="#a2ffb58efadf5885f67a4ecd791d2b218">formatRatioOf</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a0706966ac4f391854346bebfcda816fa">splitAMDGPUModule</a>.</p>

</div>
</div>

### splitAMDGPUModule() {#a0706966ac4f391854346bebfcda816fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::anonymous{AMDGPUSplitModule.cpp}::splitAMDGPUModule (<a href="#aea0eeab0d3382511b47dc3ae11736484">GetTTIFn</a> GetTTI, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, unsigned NumParts, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; MPart)&gt; ModuleCallback)</td>
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



<p>Definition at line 1374 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a85511f1d0a02c18e6c6dd590344664a4">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::buildGraph</a>, <a href="#a3884c27912d0714a0f475680f6324b3d">calculateFunctionCosts</a>, <a href="#a6239eff86084387afa955637045370bb">cloneAll</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae13b67a51d9f8061d598e82272b79b80">llvm::CloneModule</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a12eeeae240f15fc205e117fadd684fca">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a7c733400ba8d113fd2976d4fea0db981">llvm::GlobalValue::eraseFromParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#aa718ad43704d8324301fe03964cdc7c3">evaluateProposal</a>, <a href="#a6d232c3c6e60c94891fffed1f9277e8a">externalize</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#ae1b150071ca45fe3f6771a884df8d78e">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::getCost</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/node/#ae0937c73accb6f2bcba8a14df4f7842b">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::Node::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a9d6e20f416d5fa4033e3a57b09e1555d">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3ba1af4b9d9faa4a33729bbbecee83d1">llvm::GlobalValue::hasLocalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a3826bdde6c7b4e85b4b484ead3c2c0b7">needsConservativeImport</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a8fcde5bd7cc93492f3b81908846cff7b">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::nodes</a>, <a href="#a49e00f99e0c57b7f9e62bc578fa85bf4">NoExternalizeGlobals</a>, <a href="#aa08ecbf5df71f6c94b76cf8d745df92d">NoExternalizeOnAddrTaken</a>, <a href="#a84426ac86be4408aeeb7b9d3364648cd">PartitionSummariesOutput</a>, <a href="#ab6e8eb04697a9174b65bf56d1a480310">printPartitionSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/recursivesearchsplitting/#a38bc18e3b30c87e344d2b70e51815d1e">llvm::anonymous{AMDGPUSplitModule.cpp}::RecursiveSearchSplitting::run</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a> and <a href="#a97973584f850e83ab0c845def98d9587">writeDOTGraph</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpusplitmodulepass/#a5fdf4ead69288861f3151e0f035a9877">llvm::AMDGPUSplitModulePass::run</a>.</p>

</div>
</div>

### writeDOTGraph() {#a97973584f850e83ab0c845def98d9587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::anonymous{AMDGPUSplitModule.cpp}::writeDOTGraph (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph">SplitGraph</a> &amp; SG)</td>
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

<p>Writes <span class="doxyComputerOutput">SG</span> as a DOTGraph to ModuleDotCfgDir if requested.</p>

<p>Definition at line 1360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a402393e451bd4231310cd8e80d62c7de">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::getModule</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a4b3648156c20e8cf63c5eb07c56ab2fe">llvm::Module::getName</a>, <a href="#acf53892dc2a4464e4b6a535195772d86">ModuleDotCfgOutput</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a45fc498e695e5b2061ab5e6ec8e604a1">llvm::WriteGraph</a>.</p>


<p>Referenced by <a href="#a0706966ac4f391854346bebfcda816fa">splitAMDGPUModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DebugProposalSearch {#a660c994791147eb5577de9c7bc68b937}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; llvm::anonymous{AMDGPUSplitModule.cpp}::DebugProposalSearch("amdgpu-module-splitting-debug-proposal-search", cl::Hidden, cl::desc("print all proposals received and whether " "they were rejected or accepted"))</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>Referenced by <a href="#aa718ad43704d8324301fe03964cdc7c3">evaluateProposal</a>.</p>

</div>
</div>

### InvalidPID {#a286dd4db76f60ca092a2a00292b5638d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::anonymous{AMDGPUSplitModule.cpp}::InvalidPID = -1</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitproposal/#a2c57a3c3b97578adb6ee510485e6eb47">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::findCheapestPartition</a>.</p>

</div>
</div>

### LargeFnFactor {#afa109a30d0599119589438ed40cf7c7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; float &gt; llvm::anonymous{AMDGPUSplitModule.cpp}::LargeFnFactor("amdgpu-module-splitting-large-threshold", cl::init(2.0f), cl::Hidden, cl::desc( "when max depth is reached and we can no longer branch out, this " "value determines if a function is worth merging into an already " "existing partition to reduce code duplication. This is a factor " "of the ideal partition size, e.g. 2.0 means we consider the " "function for merging if its cost (including its callees) is 2x the " "size of an ideal partition."))</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/recursivesearchsplitting/#a7730964440282e892cf5d22604f49507">llvm::anonymous{AMDGPUSplitModule.cpp}::RecursiveSearchSplitting::RecursiveSearchSplitting</a>.</p>

</div>
</div>

### LargeFnOverlapForMerge {#a48d50e56a2dbc8c6f77083f912605294}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; float &gt; llvm::anonymous{AMDGPUSplitModule.cpp}::LargeFnOverlapForMerge("amdgpu-module-splitting-merge-threshold", cl::init(0.7f), cl::Hidden, cl::desc("when a function is considered for merging into a partition that " "already contains some of its callees, do the merge if at least " "n% of the code it can reach is already present inside the " "partition; e.g. 0.7 means only merge &gt;70%"))</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>

</div>
</div>

### MaxDepth {#a02273768ec41f48168b8b464f639bcd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; llvm::anonymous{AMDGPUSplitModule.cpp}::MaxDepth("amdgpu-module-splitting-max-depth", cl::desc( "maximum search depth. 0 forces a greedy approach. " "warning: the algorithm is up to O(2^N), where N is the max depth."), cl::init(8))</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/recursivesearchsplitting/#a7730964440282e892cf5d22604f49507">llvm::anonymous{AMDGPUSplitModule.cpp}::RecursiveSearchSplitting::RecursiveSearchSplitting</a>.</p>

</div>
</div>

### ModuleDotCfgOutput {#acf53892dc2a4464e4b6a535195772d86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; llvm::anonymous{AMDGPUSplitModule.cpp}::ModuleDotCfgOutput("amdgpu-module-splitting-print-module-dotcfg", cl::Hidden, cl::desc("output file to write out the dotgraph " "representation of the input module"))</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>Referenced by <a href="#a97973584f850e83ab0c845def98d9587">writeDOTGraph</a>.</p>

</div>
</div>

### NoExternalizeGlobals {#a49e00f99e0c57b7f9e62bc578fa85bf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; llvm::anonymous{AMDGPUSplitModule.cpp}::NoExternalizeGlobals("amdgpu-module-splitting-no-externalize-globals", cl::Hidden, cl::desc("disables externalization of global variable with local linkage; " "may cause globals to be duplicated which increases binary size"))</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>Referenced by <a href="#a0706966ac4f391854346bebfcda816fa">splitAMDGPUModule</a>.</p>

</div>
</div>

### NoExternalizeOnAddrTaken {#aa08ecbf5df71f6c94b76cf8d745df92d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; llvm::anonymous{AMDGPUSplitModule.cpp}::NoExternalizeOnAddrTaken("amdgpu-module-splitting-no-externalize-address-taken", cl::Hidden, cl::desc( "disables externalization of functions whose addresses are taken"))</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>Referenced by <a href="#a0706966ac4f391854346bebfcda816fa">splitAMDGPUModule</a>.</p>

</div>
</div>

### PartitionSummariesOutput {#a84426ac86be4408aeeb7b9d3364648cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; llvm::anonymous{AMDGPUSplitModule.cpp}::PartitionSummariesOutput("amdgpu-module-splitting-print-partition-summaries", cl::Hidden, cl::desc("output file to write out a summary of " "the partitions created for each module"))</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>Referenced by <a href="#a0706966ac4f391854346bebfcda816fa">splitAMDGPUModule</a>.</p>

</div>
</div>

### UseLockFile {#a9e9d93a9c62f28bebeefb524a30f1d93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; llvm::anonymous{AMDGPUSplitModule.cpp}::UseLockFile("amdgpu-module-splitting-serial-execution", cl::Hidden, cl::desc("use a lock file so only one process in the system " "can run this pass at once. useful to avoid mangled " "debug output in multithreaded environments."))</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpusplitmodulepass/#a5fdf4ead69288861f3151e0f035a9877">llvm::AMDGPUSplitModulePass::run</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
