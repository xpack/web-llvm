---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-sampleprofileinference-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{SampleProfileInference.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{SampleProfileInference.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-sampleprofileinference-cpp-/mincostmaxflow">MinCostMaxFlow</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The minimum-cost maximum flow algorithm. <a href="/web-llvm/docs/api/classes/anonymous-sampleprofileinference-cpp-/mincostmaxflow/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-sampleprofileinference-cpp-/flowadjuster">FlowAdjuster</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A post-processing adjustment of the control flow. <a href="/web-llvm/docs/api/classes/anonymous-sampleprofileinference-cpp-/flowadjuster/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; int64_t, int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad129e295efcd7c789b6c5d67124adef8">assignBlockCosts</a> (const ProfiParams &amp;Params, const FlowBlock &amp;Block)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign costs for increasing/decreasing the block counts. <a href="#ad129e295efcd7c789b6c5d67124adef8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; int64_t, int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ce5cbe1af8289db9c7121774c7ea192">assignJumpCosts</a> (const ProfiParams &amp;Params, const FlowJump &amp;Jump)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign costs for increasing/decreasing the jump counts. <a href="#a1ce5cbe1af8289db9c7121774c7ea192">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46dd2e73fdb4a5c9bf2af4a8fa968bd1">initializeNetwork</a> (const ProfiParams &amp;Params, MinCostMaxFlow &amp;Network, FlowFunction &amp;Func)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initializing flow network for a given function. <a href="#a46dd2e73fdb4a5c9bf2af4a8fa968bd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9165b166eac58ea95367c58bf55795e">extractWeights</a> (const ProfiParams &amp;Params, MinCostMaxFlow &amp;Network, FlowFunction &amp;Func)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract resulting block and edge counts from the flow network. <a href="#ae9165b166eac58ea95367c58bf55795e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b9100215c2494cda0d4aa638c2fff7b">verifyInput</a> (const FlowFunction &amp;Func)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that the provided block/jump weights are as expected. <a href="#a0b9100215c2494cda0d4aa638c2fff7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a320367d9f3ed81fea8f6979ae8e5a4ad">verifyOutput</a> (const FlowFunction &amp;Func)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that the computed flow values satisfy flow conservation rules. <a href="#a320367d9f3ed81fea8f6979ae8e5a4ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07e5cfb92cea09f102ecaedd7ea92c91">SampleProfileEvenFlowDistribution</a>("sample-profile-even-flow-distribution", cl::init(true), cl::Hidden, cl::desc("Try to evenly distribute flow when there are multiple equally " "likely options."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a7f269a0b70abd2de3b0eed910e6700">SampleProfileRebalanceUnknown</a>("sample-profile-rebalance-unknown", cl::init(true), cl::Hidden, cl::desc("Evenly re-distribute flow among unknown subgraphs."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a784ae48daf46ae5fb3d1048eca6be863">SampleProfileJoinIslands</a>("sample-profile-join-islands", cl::init(true), cl::Hidden, cl::desc("Join isolated components having positive flow."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ec1d2e0ad02412bb766e4acb4bdaa52">SampleProfileProfiCostBlockInc</a>("sample-profile-profi-cost-block-inc", cl::init(10), cl::Hidden, cl::desc("The cost of increasing a block's count by one."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c7aae207c92cebb2be99521effc819f">SampleProfileProfiCostBlockDec</a>("sample-profile-profi-cost-block-dec", cl::init(20), cl::Hidden, cl::desc("The cost of decreasing a block's count by one."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b1234b90aa075e5376b0ef03b70d232">SampleProfileProfiCostBlockEntryInc</a>("sample-profile-profi-cost-block-entry-inc", cl::init(40), cl::Hidden, cl::desc("The cost of increasing the entry block's count by one."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8daa8b900c16c315bf7a0b15f3429ab7">SampleProfileProfiCostBlockEntryDec</a>("sample-profile-profi-cost-block-entry-dec", cl::init(10), cl::Hidden, cl::desc("The cost of decreasing the entry block's count by one."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abafb27a8a17e325175e59ead3aea984c">SampleProfileProfiCostBlockZeroInc</a>("sample-profile-profi-cost-block-zero-inc", cl::init(11), cl::Hidden, cl::desc("The cost of increasing a count of zero-weight block by one."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a82ef3696e3ff3cd61283e5049b23df">SampleProfileProfiCostBlockUnknownInc</a>("sample-profile-profi-cost-block-unknown-inc", cl::init(0), cl::Hidden, cl::desc("The cost of increasing an unknown block's count by one."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a001dbf74fedb2ab9b6f541f6943dea14">INF</a> = ((int64_t)1) &lt;&lt; 50</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A value indicating an infinite flow/capacity/weight of a block/edge. <a href="#a001dbf74fedb2ab9b6f541f6943dea14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### assignBlockCosts() {#ad129e295efcd7c789b6c5d67124adef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; int64_t, int64_t &gt; anonymous{SampleProfileInference.cpp}::assignBlockCosts (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/profiparams">ProfiParams</a> &amp; Params, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/flowblock">FlowBlock</a> &amp; Block)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assign costs for increasing/decreasing the block counts.</p>

<p>Definition at line 1127 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/structs/llvm/profiparams/#adcd8b45086bba7f4515e3e3d8fef41dc">llvm::ProfiParams::CostBlockDec</a>, <a href="/web-llvm/docs/api/structs/llvm/profiparams/#aaa7f2d292f152d77537be66c67cd2008">llvm::ProfiParams::CostBlockEntryDec</a>, <a href="/web-llvm/docs/api/structs/llvm/profiparams/#af820f5e80ca4cd2a823d4dbd16714bc1">llvm::ProfiParams::CostBlockEntryInc</a>, <a href="/web-llvm/docs/api/structs/llvm/profiparams/#a39401e9ddaa84e388f7114f9f3b77c7e">llvm::ProfiParams::CostBlockInc</a>, <a href="/web-llvm/docs/api/structs/llvm/profiparams/#ad0fab235dca463ec9d48c5b6bfe9ccde">llvm::ProfiParams::CostBlockUnknownInc</a>, <a href="/web-llvm/docs/api/structs/llvm/profiparams/#a9e351546ca08436a0e7a7ccfa08f5495">llvm::ProfiParams::CostBlockZeroInc</a> and <a href="/web-llvm/docs/api/structs/llvm/profiparams/#a8c360b59499f427030ac3969086b5cb8">llvm::ProfiParams::CostUnlikely</a>.</p>


<p>Referenced by <a href="#a46dd2e73fdb4a5c9bf2af4a8fa968bd1">initializeNetwork</a>.</p>

</div>
</div>

### assignJumpCosts() {#a1ce5cbe1af8289db9c7121774c7ea192}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; int64_t, int64_t &gt; anonymous{SampleProfileInference.cpp}::assignJumpCosts (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/profiparams">ProfiParams</a> &amp; Params, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/flowjump">FlowJump</a> &amp; Jump)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assign costs for increasing/decreasing the jump counts.</p>

<p>Definition at line 1155 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/profiparams/#a94bec6d7c1e0827854d72091aacf81f7">llvm::ProfiParams::CostJumpDec</a>, <a href="/web-llvm/docs/api/structs/llvm/profiparams/#adb1dd7977642b5222b9fac44305f562e">llvm::ProfiParams::CostJumpFTDec</a>, <a href="/web-llvm/docs/api/structs/llvm/profiparams/#a55e432c2b9b6e25f5a83f1d5ac7655b7">llvm::ProfiParams::CostJumpFTInc</a>, <a href="/web-llvm/docs/api/structs/llvm/profiparams/#ac04da42f4440b9ea85d4ae6400b4e8ce">llvm::ProfiParams::CostJumpInc</a>, <a href="/web-llvm/docs/api/structs/llvm/profiparams/#a2aa4f0b714c6b54a55b97af255f6f62c">llvm::ProfiParams::CostJumpUnknownFTInc</a>, <a href="/web-llvm/docs/api/structs/llvm/profiparams/#acecc0d05ec41075cc30e0c9bbb0c20b9">llvm::ProfiParams::CostJumpUnknownInc</a>, <a href="/web-llvm/docs/api/structs/llvm/profiparams/#a8c360b59499f427030ac3969086b5cb8">llvm::ProfiParams::CostUnlikely</a>, <a href="/web-llvm/docs/api/structs/llvm/flowjump/#a491b58e7abf9b59f256a3c66443a1ad5">llvm::FlowJump::HasUnknownWeight</a>, <a href="/web-llvm/docs/api/structs/llvm/flowjump/#a061ed8974c636291de7f7cf5c76e4660">llvm::FlowJump::IsUnlikely</a>, <a href="/web-llvm/docs/api/structs/llvm/flowjump/#ae9c91a5ea45940cfaa166511aadd2eb2">llvm::FlowJump::Source</a>, <a href="/web-llvm/docs/api/structs/llvm/flowjump/#aa017ffa5be8016e6feb941ceae7c89cc">llvm::FlowJump::Target</a> and <a href="/web-llvm/docs/api/structs/llvm/flowjump/#acdd34566a25bab9890d87c9de6e7e8b0">llvm::FlowJump::Weight</a>.</p>


<p>Referenced by <a href="#a46dd2e73fdb4a5c9bf2af4a8fa968bd1">initializeNetwork</a>.</p>

</div>
</div>

### extractWeights() {#ae9165b166eac58ea95367c58bf55795e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SampleProfileInference.cpp}::extractWeights (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/profiparams">ProfiParams</a> &amp; Params, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofileinference-cpp-/mincostmaxflow">MinCostMaxFlow</a> &amp; Network, <a href="/web-llvm/docs/api/structs/llvm/flowfunction">FlowFunction</a> &amp; Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract resulting block and edge counts from the flow network.</p>

<p>Definition at line 1184 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siannotatecontrolflow-cpp/#acf797fa91d5b7065dfb68a2492df28c1">Flow</a>, <a href="/web-llvm/docs/api/structs/llvm/flowjump/#aba9bc6e5c52dfa0898860eeadbbef59b">llvm::FlowJump::Flow</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofileinference-cpp-/mincostmaxflow/#aca1fc02088c9f278b02f219d2d64c82c">anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::getFlow</a>, <a href="/web-llvm/docs/api/structs/llvm/flowjump/#ae9c91a5ea45940cfaa166511aadd2eb2">llvm::FlowJump::Source</a>, <a href="/web-llvm/docs/api/structs/llvm/flowjump/#aa017ffa5be8016e6feb941ceae7c89cc">llvm::FlowJump::Target</a> and <a href="/web-llvm/docs/api/structs/llvm/flowjump/#acdd34566a25bab9890d87c9de6e7e8b0">llvm::FlowJump::Weight</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af962cc3b6565966cbc3d5c1289f31a11">llvm::applyFlowInference</a>.</p>

</div>
</div>

### initializeNetwork() {#a46dd2e73fdb4a5c9bf2af4a8fa968bd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SampleProfileInference.cpp}::initializeNetwork (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/profiparams">ProfiParams</a> &amp; Params, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofileinference-cpp-/mincostmaxflow">MinCostMaxFlow</a> &amp; Network, <a href="/web-llvm/docs/api/structs/llvm/flowfunction">FlowFunction</a> &amp; Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initializing flow network for a given function.</p>


<p>Every block is split into two nodes that are responsible for (i) an incoming flow, (ii) an outgoing flow; they penalize an increase or a reduction of the block weight.</p>


<p>Definition at line 1056 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-sampleprofileinference-cpp-/mincostmaxflow/#a2945517bec92f190ee791baa19050289">anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::addEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad129e295efcd7c789b6c5d67124adef8">assignBlockCosts</a>, <a href="#a1ce5cbe1af8289db9c7121774c7ea192">assignJumpCosts</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a372f87e2cac1c83389c98554dc44806da807dbe7d1c25a633894d4a231b1c76d3">llvm::Bin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofileinference-cpp-/mincostmaxflow/#acbf43214acfd3c95a6e28d1db4989d91">anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::initialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="/web-llvm/docs/api/structs/llvm/flowjump/#ae9c91a5ea45940cfaa166511aadd2eb2">llvm::FlowJump::Source</a>, <a href="/web-llvm/docs/api/structs/llvm/flowjump/#aa017ffa5be8016e6feb941ceae7c89cc">llvm::FlowJump::Target</a> and <a href="/web-llvm/docs/api/structs/llvm/flowjump/#acdd34566a25bab9890d87c9de6e7e8b0">llvm::FlowJump::Weight</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af962cc3b6565966cbc3d5c1289f31a11">llvm::applyFlowInference</a>.</p>

</div>
</div>

### verifyInput() {#a0b9100215c2494cda0d4aa638c2fff7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SampleProfileInference.cpp}::verifyInput (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/flowfunction">FlowFunction</a> &amp; Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify that the provided block/jump weights are as expected.</p>

<p>Definition at line 1221 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/structs/llvm/flowjump/#a491b58e7abf9b59f256a3c66443a1ad5">llvm::FlowJump::HasUnknownWeight</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/flowjump/#aa017ffa5be8016e6feb941ceae7c89cc">llvm::FlowJump::Target</a> and <a href="/web-llvm/docs/api/structs/llvm/flowjump/#acdd34566a25bab9890d87c9de6e7e8b0">llvm::FlowJump::Weight</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af962cc3b6565966cbc3d5c1289f31a11">llvm::applyFlowInference</a>.</p>

</div>
</div>

### verifyOutput() {#a320367d9f3ed81fea8f6979ae8e5a4ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SampleProfileInference.cpp}::verifyOutput (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/flowfunction">FlowFunction</a> &amp; Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify that the computed flow values satisfy flow conservation rules.</p>

<p>Definition at line 1258 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/structs/llvm/flowjump/#aba9bc6e5c52dfa0898860eeadbbef59b">llvm::FlowJump::Flow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/flowjump/#ae9c91a5ea45940cfaa166511aadd2eb2">llvm::FlowJump::Source</a> and <a href="/web-llvm/docs/api/structs/llvm/flowjump/#aa017ffa5be8016e6feb941ceae7c89cc">llvm::FlowJump::Target</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af962cc3b6565966cbc3d5c1289f31a11">llvm::applyFlowInference</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### INF {#a001dbf74fedb2ab9b6f541f6943dea14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{SampleProfileInference.cpp}::INF = ((int64_t)1) &lt;&lt; 50</td>
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

<p>A value indicating an infinite flow/capacity/weight of a block/edge.</p>


<p>Not using numeric_limits&lt;int64_t&gt;::max(), as the values can be summed up during the execution.</p>


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofileinference-cpp-/mincostmaxflow/#af5911bffb6d89dea9124aec1644932c4">anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::addEdge</a>.</p>

</div>
</div>

### SampleProfileEvenFlowDistribution {#a07e5cfb92cea09f102ecaedd7ea92c91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{SampleProfileInference.cpp}::SampleProfileEvenFlowDistribution("sample-profile-even-flow-distribution", cl::init(true), cl::Hidden, cl::desc("Try to evenly distribute flow when there are multiple equally " "likely options."))</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97df254bc8c63986dc57817f0f553de9">llvm::applyFlowInference</a>.</p>

</div>
</div>

### SampleProfileJoinIslands {#a784ae48daf46ae5fb3d1048eca6be863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{SampleProfileInference.cpp}::SampleProfileJoinIslands("sample-profile-join-islands", cl::init(true), cl::Hidden, cl::desc("Join isolated components having positive flow."))</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97df254bc8c63986dc57817f0f553de9">llvm::applyFlowInference</a>.</p>

</div>
</div>

### SampleProfileProfiCostBlockDec {#a6c7aae207c92cebb2be99521effc819f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; anonymous{SampleProfileInference.cpp}::SampleProfileProfiCostBlockDec("sample-profile-profi-cost-block-dec", cl::init(20), cl::Hidden, cl::desc("The cost of decreasing a block's count by one."))</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97df254bc8c63986dc57817f0f553de9">llvm::applyFlowInference</a>.</p>

</div>
</div>

### SampleProfileProfiCostBlockEntryDec {#a8daa8b900c16c315bf7a0b15f3429ab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; anonymous{SampleProfileInference.cpp}::SampleProfileProfiCostBlockEntryDec("sample-profile-profi-cost-block-entry-dec", cl::init(10), cl::Hidden, cl::desc("The cost of decreasing the entry block's count by one."))</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97df254bc8c63986dc57817f0f553de9">llvm::applyFlowInference</a>.</p>

</div>
</div>

### SampleProfileProfiCostBlockEntryInc {#a1b1234b90aa075e5376b0ef03b70d232}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; anonymous{SampleProfileInference.cpp}::SampleProfileProfiCostBlockEntryInc("sample-profile-profi-cost-block-entry-inc", cl::init(40), cl::Hidden, cl::desc("The cost of increasing the entry block's count by one."))</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97df254bc8c63986dc57817f0f553de9">llvm::applyFlowInference</a>.</p>

</div>
</div>

### SampleProfileProfiCostBlockInc {#a0ec1d2e0ad02412bb766e4acb4bdaa52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; anonymous{SampleProfileInference.cpp}::SampleProfileProfiCostBlockInc("sample-profile-profi-cost-block-inc", cl::init(10), cl::Hidden, cl::desc("The cost of increasing a block's count by one."))</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97df254bc8c63986dc57817f0f553de9">llvm::applyFlowInference</a>.</p>

</div>
</div>

### SampleProfileProfiCostBlockUnknownInc {#a9a82ef3696e3ff3cd61283e5049b23df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; anonymous{SampleProfileInference.cpp}::SampleProfileProfiCostBlockUnknownInc("sample-profile-profi-cost-block-unknown-inc", cl::init(0), cl::Hidden, cl::desc("The cost of increasing an unknown block's count by one."))</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97df254bc8c63986dc57817f0f553de9">llvm::applyFlowInference</a>.</p>

</div>
</div>

### SampleProfileProfiCostBlockZeroInc {#abafb27a8a17e325175e59ead3aea984c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; anonymous{SampleProfileInference.cpp}::SampleProfileProfiCostBlockZeroInc("sample-profile-profi-cost-block-zero-inc", cl::init(11), cl::Hidden, cl::desc("The cost of increasing a count of zero-weight block by one."))</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97df254bc8c63986dc57817f0f553de9">llvm::applyFlowInference</a>.</p>

</div>
</div>

### SampleProfileRebalanceUnknown {#a0a7f269a0b70abd2de3b0eed910e6700}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{SampleProfileInference.cpp}::SampleProfileRebalanceUnknown("sample-profile-rebalance-unknown", cl::init(true), cl::Hidden, cl::desc("Evenly re-distribute flow among unknown subgraphs."))</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97df254bc8c63986dc57817f0f553de9">llvm::applyFlowInference</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileinference-cpp">SampleProfileInference.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
