---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dotgraphtraits-55c8cb82503f51812ad190e425a6fd3d
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DOTGraphTraits` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::DOTGraphTraits&lt;DOTFuncInfo *&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgprinter-h">llvm/Analysis/CFGPrinter.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits">DefaultDOTGraphTraits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits">DefaultDOTGraphTraits</a> - This class provides the default implementations of all of the <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits">DOTGraphTraits</a> methods. <a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6977cab958e56c12f632f9b1cea6b7fa">DOTGraphTraits</a> (bool isSimple=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a965cbc8ca7a71e0b6b41e4b82c5beab1">getNodeLabel</a> (const BasicBlock *Node, DOTFuncInfo *CFGInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02f466eae018c75689a0189cb5f29524">getEdgeAttributes</a> (const BasicBlock *Node, const_succ_iterator I, DOTFuncInfo *CFGInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Display the raw branch weights from PGO. <a href="#a02f466eae018c75689a0189cb5f29524">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69a2252b0ac0a2ce93c024ee5750cff7">getNodeAttributes</a> (const BasicBlock *Node, DOTFuncInfo *CFGInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d2303181b25afdeddcba74d8da287a9">isNodeHidden</a> (const BasicBlock *Node, const DOTFuncInfo *CFGInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c7952a137a05f691e2b5cb7df2a6200">computeDeoptOrUnreachablePaths</a> (const Function *F)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a386c80dd91d59dce98f090b6e11a2d5a">isOnDeoptOrUnreachablePath</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a805a9f868fdddb951a04aa511a12cfd5">eraseComment</a> (std::string &amp;OutStr, unsigned &amp;I, unsigned Idx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33c6f6eb06efcdf1daf21bc77c4b1a6f">getGraphName</a> (DOTFuncInfo *CFGInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30fd63967b80599471009b6eb15c8fe3">getSimpleNodeLabel</a> (const BasicBlock *Node, DOTFuncInfo *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac945ed3e9df97e271d68f9e1af8b737d">printBasicBlock</a> (raw_string_ostream &amp;OS, const BasicBlock &amp;Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8fdb1fa52848beb3739bf34cf6a5753">getCompleteNodeLabel</a> (const BasicBlock *Node, DOTFuncInfo *, function_ref&lt; void(raw_string_ostream &amp;, const BasicBlock &amp;)&gt; HandleBasicBlock=printBasicBlock, function_ref&lt; void(std::string &amp;, unsigned &amp;, unsigned)&gt; HandleComment=eraseComment)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a803b22c256d8b43894d71021c743501c">getEdgeSourceLabel</a> (const BasicBlock *Node, const_succ_iterator I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5433443eafbdb00b6673eae4ce08b1f">getBBName</a> (const BasicBlock *Node)</td>
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


<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgprinter-h">CFGPrinter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DOTGraphTraits() {#a6977cab958e56c12f632f9b1cea6b7fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::DOTGraphTraits (bool isSimple=false)</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgprinter-h">CFGPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits/#a8a0585a182245d87b224f4a26a41cf16">llvm::DefaultDOTGraphTraits::DefaultDOTGraphTraits</a> and <a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits/#ae8629cdc360910256304238ca5db1a45">llvm::DefaultDOTGraphTraits::isSimple</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### computeDeoptOrUnreachablePaths() {#a0c7952a137a05f691e2b5cb7df2a6200}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::computeDeoptOrUnreachablePaths (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgprinter-h">CFGPrinter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### getEdgeAttributes() {#a02f466eae018c75689a0189cb5f29524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::getEdgeAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Node, <a href="/web-llvm/docs/api/namespaces/llvm/#ae21e08e18fe951a73ef0942064ef841c">const_succ_iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo">DOTFuncInfo</a> * CFGInfo)</td>
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

<p>Display the raw branch weights from PGO.</p>

<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgprinter-h">CFGPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad7ca5290dc5789cbeae763690e6edccf">llvm::mdconst::dyn_extract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="#aa5433443eafbdb00b6673eae4ce08b1f">getBBName</a>, <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo/#a6ec434a232fa535d8a7742f996335c7c">llvm::DOTFuncInfo::getBPI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3475c6d4bdcc4da34ea01a05f01becf2">llvm::getBranchWeightMDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo/#a46502d648608aa13cb485ed4af447d88">llvm::BranchProbabilityInfo::getEdgeProbability</a>, <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo/#a371d6f2c316aa7f48f477a3d3d9fa878">llvm::DOTFuncInfo::getFreq</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a3287172f2d13af086e6d66364e8c6de3">llvm::Instruction::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6e5d2e18c81baaeec7dadc81a0dea993">llvm::Instruction::getSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo/#a6ee6a45f7ecb4f52bef20c87b41e599d">llvm::DOTFuncInfo::showEdgeWeights</a> and <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo/#ab274e40835dd61f68d1dfb3223627543">llvm::DOTFuncInfo::useRawEdgeWeights</a>.</p>

</div>
</div>

### getNodeAttributes() {#a69a2252b0ac0a2ce93c024ee5750cff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::getNodeAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo">DOTFuncInfo</a> * CFGInfo)</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgprinter-h">CFGPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo/#a371d6f2c316aa7f48f477a3d3d9fa878">llvm::DOTFuncInfo::getFreq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0c5885bd9e495730dc56baa6e5bdcf">llvm::getHeatColor</a>, <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo/#a1fa569be4ec01a302a7955b487811685">llvm::DOTFuncInfo::getMaxFreq</a> and <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo/#a7f87ca50f46c29e9e9db5dd3a1177815">llvm::DOTFuncInfo::showHeatColors</a>.</p>

</div>
</div>

### getNodeLabel() {#a965cbc8ca7a71e0b6b41e4b82c5beab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::getNodeLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo">DOTFuncInfo</a> * CFGInfo)</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgprinter-h">CFGPrinter.h</a>.</p>


<p>References <a href="#ad8fdb1fa52848beb3739bf34cf6a5753">getCompleteNodeLabel</a>, <a href="#a30fd63967b80599471009b6eb15c8fe3">getSimpleNodeLabel</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a3ca9742688618517cc4690fb947fb609">isSimple</a>.</p>

</div>
</div>

### isNodeHidden() {#a4d2303181b25afdeddcba74d8da287a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::isNodeHidden (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Node, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo">DOTFuncInfo</a> * CFGInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgprinter-h">CFGPrinter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### isOnDeoptOrUnreachablePath {#a386c80dd91d59dce98f090b6e11a2d5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const BasicBlock *, bool&gt; llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::isOnDeoptOrUnreachablePath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgprinter-h">CFGPrinter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### eraseComment() {#a805a9f868fdddb951a04aa511a12cfd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::eraseComment (std::string &amp; OutStr, unsigned &amp; I, unsigned Idx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgprinter-h">CFGPrinter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#ad8fdb1fa52848beb3739bf34cf6a5753">getCompleteNodeLabel</a>.</p>

</div>
</div>

### getBBName() {#aa5433443eafbdb00b6673eae4ce08b1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::getBBName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Node)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgprinter-h">CFGPrinter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/node/#a2479457ae2ca9ae65654ebfb7cb5acaa">Node::printAsOperand</a>.</p>


<p>Referenced by <a href="#a02f466eae018c75689a0189cb5f29524">getEdgeAttributes</a>.</p>

</div>
</div>

### getCompleteNodeLabel() {#ad8fdb1fa52848beb3739bf34cf6a5753}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::getCompleteNodeLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo">DOTFuncInfo</a> *, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream">raw_string_ostream</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp;)&gt; HandleBasicBlock=<a href="#ac945ed3e9df97e271d68f9e1af8b737d">printBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(std::string &amp;, unsigned &amp;, unsigned)&gt; HandleComment=<a href="#a805a9f868fdddb951a04aa511a12cfd5">eraseComment</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgprinter-h">CFGPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aef388dd4679a63426b91a9059b2380cd">llvm::CompleteNodeLabelString</a>, <a href="#a805a9f868fdddb951a04aa511a12cfd5">eraseComment</a> and <a href="#ac945ed3e9df97e271d68f9e1af8b737d">printBasicBlock</a>.</p>


<p>Referenced by <a href="#a965cbc8ca7a71e0b6b41e4b82c5beab1">getNodeLabel</a>.</p>

</div>
</div>

### getEdgeSourceLabel() {#a803b22c256d8b43894d71021c743501c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::getEdgeSourceLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Node, <a href="/web-llvm/docs/api/namespaces/llvm/#ae21e08e18fe951a73ef0942064ef841c">const_succ_iterator</a> I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgprinter-h">CFGPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/caseiteratorimpl/#ae5a39d260adc65f8646df2830a66e262">llvm::SwitchInst::CaseIteratorImpl&lt; ConstCaseHandle &gt;::fromSuccessorIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa408bc83db2292cc1a57a3e6b206c2">llvm::succ_begin</a>.</p>

</div>
</div>

### getGraphName() {#a33c6f6eb06efcdf1daf21bc77c4b1a6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::getGraphName (<a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo">DOTFuncInfo</a> * CFGInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgprinter-h">CFGPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo/#ab29244479559a63048450afda5f9e631">llvm::DOTFuncInfo::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>.</p>

</div>
</div>

### getSimpleNodeLabel() {#a30fd63967b80599471009b6eb15c8fe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::getSimpleNodeLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/dotfuncinfo">DOTFuncInfo</a> *)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgprinter-h">CFGPrinter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a6aa83be387fc77549be8e650c009d12a">llvm::SimpleNodeLabelString</a>.</p>


<p>Referenced by <a href="#a965cbc8ca7a71e0b6b41e4b82c5beab1">getNodeLabel</a>.</p>

</div>
</div>

### printBasicBlock() {#ac945ed3e9df97e271d68f9e1af8b737d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::printBasicBlock (<a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream">raw_string_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; Node)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgprinter-h">CFGPrinter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/node/#a2479457ae2ca9ae65654ebfb7cb5acaa">Node::printAsOperand</a>.</p>


<p>Referenced by <a href="#ad8fdb1fa52848beb3739bf34cf6a5753">getCompleteNodeLabel</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfgprinter-h">CFGPrinter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
