---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/blockfrequencyinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `BlockFrequencyInfo.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">llvm/Analysis/BlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/iterator-h">llvm/ADT/iterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">llvm/Analysis/BlockFrequencyInfoImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">llvm/Analysis/BranchProbabilityInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cfg-h">llvm/IR/CFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/graphwriter-h">llvm/Support/GraphWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;optional&gt;
#include &lt;string&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/graphtraits-41d1cb9c371ec31b99ac20773a2bc6fb">GraphTraits&lt;BlockFrequencyInfo *&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-41d1cb9c371ec31b99ac20773a2bc6fb">DOTGraphTraits&lt;BlockFrequencyInfo *&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a016177254de2446a59c8933b3ce3a085">INITIALIZE_PASS_BEGIN</a> (BlockFrequencyInfoWrapperPass, "block-freq", "Block Frequency Analysis", true, true) INITIALIZE_PASS_END(BlockFrequencyInfoWrapperPass</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#af0bf055834b973decc2477a8061624ff">GVDAGType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d6116a6ffd9acfeb0f3975c7317646d">ViewBlockFreqPropagationDAG</a>("view-block-freq-propagation-dags", cl::Hidden, cl::desc("Pop up a window to show a dag displaying how block " "frequencies propagation through the CFG."), cl::values(clEnumValN(GVDT_None, "none", "do not display graphs."), clEnumValN(GVDT_Fraction, "fraction", "display a graph using the " "fractional block frequency representation."), clEnumValN(GVDT_Integer, "integer", "display a graph using the raw " "integer fractional block frequency representation."), clEnumValN(GVDT_Count, "count", "display a graph using the real " "profile count if available.")))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6228da6ce1f2cdae97b17637c061011e">freq</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a> Block Frequency</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a> Block Frequency</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58dc96c9185c2ff09668719dc542f24b">true</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"block-freq"</td>
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

### INITIALIZE\_PASS\_BEGIN() {#a016177254de2446a59c8933b3ce3a085}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (<a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfowrapperpass">BlockFrequencyInfoWrapperPass</a>, "block-freq", "Block Frequency Analysis", <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### Analysis {#a882e33145fd2a17174b47d3f964a6b2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">print machine Print Machine Uniformity Info Analysis</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ae917d897ff4613b4cfdc9cd4dadade41">llvm::TargetLowering::computeKnownAlignForTargetInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#af7b6795985b3405f69339661de5d860c">llvm::TargetLowering::computeKnownBitsForTargetInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aa8d26126af786ae0383671d0ebab6fd1">llvm::AMDGPUTargetLowering::computeNumSignBitsForTargetInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a9b359fbfa123fbf333095817e902cf0c">llvm::TargetLowering::computeNumSignBitsForTargetInstr</a>, <a href="/web-llvm/docs/api/structs/llvm/analysisgetter/#a6802bcb402f1a4988ea97a4ce214e7ac">llvm::AnalysisGetter::getAnalysis</a>, <a href="/web-llvm/docs/api/structs/llvm/analysisgetter/#ac92ff546620b4d4197bd2e5b489b9480">llvm::AnalysisGetter::HasLegacyWrapper</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a4713251cc0d94764b3bafeff64a26c79">llvm::AMDGPUTargetLowering::PostISelFolding</a>, <a href="/web-llvm/docs/api/classes/llvm/dotgraphtraitsprinterwrapperpass/#abd6ce36a525dd5022e194577db9ad826">llvm::DOTGraphTraitsPrinterWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::processFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/dotgraphtraitsviewerwrapperpass/#a422f62bcc704728c67556e878a55aa1f">llvm::DOTGraphTraitsViewerWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::processFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation/#adda8476ef0007c61013ba8e5c46c6693">llvm::PassInstrumentation::runAfterAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation/#a698253acb40299131fecdb9489f88fcd">llvm::PassInstrumentation::runAnalysisInvalidated</a>, <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation/#a5a2cc6fe0017dd7067b103118a7bc914">llvm::PassInstrumentation::runBeforeAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/dotgraphtraitsprinterwrapperpass/#a13f01c501d30959accca2ddeec59fe10">llvm::DOTGraphTraitsPrinterWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/dotgraphtraitsviewerwrapperpass/#a2d6db797796df0405b03c47a31340cc9">llvm::DOTGraphTraitsViewerWrapperPass&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::runOnFunction</a>.</p>

</div>
</div>

### freq {#a6228da6ce1f2cdae97b17637c061011e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">block freq</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/spillplacement/node/#a03bf04c760f4e0dc8f8673a6dbbc1f37">llvm::SpillPlacement::Node::addBias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0c5885bd9e495730dc56baa6e5bdcf">llvm::getHeatColor</a> and <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-02fb7f36a5622815e386262c1f910406/#a18c5d3cf4cf688e934da2909ce3d3b9f">llvm::DOTGraphTraits&lt; CallGraphDOTInfo * &gt;::getNodeAttributes</a>.</p>

</div>
</div>

### true {#a58dc96c9185c2ff09668719dc542f24b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">block Block Frequency true</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>

</div>
</div>

### ViewBlockFreqPropagationDAG {#a2d6116a6ffd9acfeb0f3975c7317646d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; GVDAGType &gt; ViewBlockFreqPropagationDAG("view-block-freq-propagation-dags", cl::Hidden, cl::desc("Pop up a window to show a dag displaying how block " "frequencies propagation through the CFG."), cl::values(clEnumValN(GVDT_None, "none", "do not display graphs."), clEnumValN(GVDT_Fraction, "fraction", "display a graph using the " "fractional block frequency representation."), clEnumValN(GVDT_Integer, "integer", "display a graph using the raw " "integer fractional block frequency representation."), clEnumValN(GVDT_Count, "count", "display a graph using the real " "profile count if available.")))</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo/#a028fa7f559c340968f4faefbd899e69b">llvm::BlockFrequencyInfo::calculate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10bea33dd12f792987bcd7a4252a7446">llvm::getGVDT</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"block-freq"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
