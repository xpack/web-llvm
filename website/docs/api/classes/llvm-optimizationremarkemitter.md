---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/optimizationremarkemitter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `OptimizationRemarkEmitter` Class

<p>The optimization diagnostic interface. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::OptimizationRemarkEmitter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">llvm/Analysis/OptimizationRemarkEmitter.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a4e71371e852c7925451278d257c408">OptimizationRemarkEmitter</a> (const Function *F, BlockFrequencyInfo *BFI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97b6c307b527c1b857c01ac9a318ff28">OptimizationRemarkEmitter</a> (const Function *F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This variant can be used to generate ORE on demand (without the analysis pass). <a href="#a97b6c307b527c1b857c01ac9a318ff28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee09ddf733b1708fa14df6b39369647b">OptimizationRemarkEmitter</a> (OptimizationRemarkEmitter &amp;&amp;Arg)</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4890181e92c1f0d03e828016bcd1a7fd">OptimizationRemarkEmitter</a> (const OptimizationRemarkEmitter &amp;)=delete</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab45f4f184ef3863a7e639037dc6bf128">operator=</a> (OptimizationRemarkEmitter &amp;&amp;RHS)</td>
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

## Private Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0255bb6f938cb58172fcb5b274cfbba3">operator=</a> (const OptimizationRemarkEmitter &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18f7d23f2e90a7ab59eda27fb77ec7d8">invalidate</a> (Function &amp;F, const PreservedAnalyses &amp;PA, FunctionAnalysisManager::Invalidator &amp;Inv)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle invalidation events in the new pass manager. <a href="#a18f7d23f2e90a7ab59eda27fb77ec7d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bce56db93bffc6af600a967c61c5d3e">enabled</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true iff at least <em>some</em> remarks are enabled. <a href="#a3bce56db93bffc6af600a967c61c5d3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae6a98aea85aa3af87357cc5448db499">emit</a> (DiagnosticInfoOptimizationBase &amp;OptDiag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Output the remark via the diagnostic handler and to the optimization record file. <a href="#aae6a98aea85aa3af87357cc5448db499">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae8f91b309992d6d1c1b43bf7d888c811">emit</a> (T RemarkBuilder, decltype(RemarkBuilder()) *=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Take a lambda that returns a remark which will be emitted. <a href="#ae8f91b309992d6d1c1b43bf7d888c811">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74b26949a0dd7a5fab2ba1b0da204e50">allowExtraAnalysis</a> (StringRef PassName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether we allow for extra compile-time budget to perform more analysis to produce fewer false positives. <a href="#a74b26949a0dd7a5fab2ba1b0da204e50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67b757c2d9cd94a3692e8d094dd5b914">computeHotness</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute hotness from IR value (currently assumed to be a block) if PGO is available. <a href="#a67b757c2d9cd94a3692e8d094dd5b914">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af13b9892a91342b04ae620a40948024b">computeHotness</a> (DiagnosticInfoIROptimization &amp;OptDiag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar but use value from <span class="doxyComputerOutput">OptDiag</span> and update hotness there. <a href="#af13b9892a91342b04ae620a40948024b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afee79e13f19ff1df4103059a2abfc07c">shouldEmitVerbose</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only allow verbose messages if we know we're filtering by hotness (BFI is only set in this case). <a href="#afee79e13f19ff1df4103059a2abfc07c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40ba1ebabffad398c5a3c6d0643a175b">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b7ee2182195c5d3f369fc54fe6ea037">BFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83a6e292d262b1cc03c7f484df9ec961">OwnedBFI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we generate BFI on demand, we need to free it when ORE is freed. <a href="#a83a6e292d262b1cc03c7f484df9ec961">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19c3c3d0ac78d71ea5d4c759c8c8db9d">allowExtraAnalysis</a> (const Function &amp;F, StringRef PassName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6dacb86673ab0eec1cbbcdc1a031c77">allowExtraAnalysis</a> (LLVMContext &amp;Ctx, StringRef PassName)</td>
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

<p>The optimization diagnostic interface.</p>


<p>It allows reporting when optimizations are performed and when they are not along with the reasons for it. Hotness information of the corresponding code region can be included in the remark if DiagnosticsHotnessRequested is enabled in the LLVM context.</p>


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OptimizationRemarkEmitter() {#a9a4e71371e852c7925451278d257c408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OptimizationRemarkEmitter::OptimizationRemarkEmitter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>.</p>


<p>Referenced by <a href="#ab45f4f184ef3863a7e639037dc6bf128">operator=</a> and <a href="#aee09ddf733b1708fa14df6b39369647b">OptimizationRemarkEmitter</a>.</p>

</div>
</div>

### OptimizationRemarkEmitter() {#a97b6c307b527c1b857c01ac9a318ff28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter::OptimizationRemarkEmitter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This variant can be used to generate ORE on demand (without the analysis pass).</p>


<p>Note that this ctor has a very different cost depending on whether F-&gt;getContext().getDiagnosticsHotnessRequested() is on or not. If it's off the operation is free.</p>


<p>Whereas if DiagnosticsHotnessRequested is on, it is fairly expensive operation since BFI and all its required analyses are computed. This is for example useful for CGSCC passes that can't use function analyses passes in the old PM.</p>


<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/optimizationremarkemitter-cpp">OptimizationRemarkEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a280d02be3ec3eb6527c1ea944d902775">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::analyze</a> and <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#aa0641ae965656ff9988d67a35140e4d9">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::recalculate</a>.</p>

</div>
</div>

### OptimizationRemarkEmitter() {#aee09ddf733b1708fa14df6b39369647b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OptimizationRemarkEmitter::OptimizationRemarkEmitter (<a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;&amp; Arg)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>.</p>


<p>Reference <a href="#a9a4e71371e852c7925451278d257c408">OptimizationRemarkEmitter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### OptimizationRemarkEmitter() {#a4890181e92c1f0d03e828016bcd1a7fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OptimizationRemarkEmitter::OptimizationRemarkEmitter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ab45f4f184ef3863a7e639037dc6bf128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter &amp; llvm::OptimizationRemarkEmitter::operator= (<a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;&amp; RHS)</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>.</p>


<p>References <a href="#a9a4e71371e852c7925451278d257c408">OptimizationRemarkEmitter</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Operators

### operator=() {#a0255bb6f938cb58172fcb5b274cfbba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::OptimizationRemarkEmitter::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allowExtraAnalysis() {#a74b26949a0dd7a5fab2ba1b0da204e50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OptimizationRemarkEmitter::allowExtraAnalysis (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassName)</td>
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

<p>Whether we allow for extra compile-time budget to perform more analysis to produce fewer false positives.</p>


<p>This is useful when reporting missed optimizations. In this case we can use the extra analysis (1) to filter trivial false positives or (2) to provide more context so that non-trivial false positives can be quickly detected by the user.</p>


<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>.</p>


<p>References <a href="#a74b26949a0dd7a5fab2ba1b0da204e50">allowExtraAnalysis</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>.</p>


<p>Referenced by <a href="#a19c3c3d0ac78d71ea5d4c759c8c8db9d">allowExtraAnalysis</a>, <a href="#a74b26949a0dd7a5fab2ba1b0da204e50">allowExtraAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/annotation2metadata-cpp/#ae04cce04aef5dad8bb4c7b8d0a07f145">convertAnnotation2Metadata</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/annotationremarks-cpp/#ae33ca40f926442c4264c507f4d32c85e">runImpl</a>.</p>

</div>
</div>

### emit() {#aae6a98aea85aa3af87357cc5448db499}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OptimizationRemarkEmitter::emit (<a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase">DiagnosticInfoOptimizationBase</a> &amp; OptDiag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Output the remark via the diagnostic handler and to the optimization record file.</p>

<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/optimizationremarkemitter-cpp">OptimizationRemarkEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfooptimizationbase/#affaf002fae858d6fabe51a135b30e8be">llvm::DiagnosticInfoOptimizationBase::getHotness</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-alwaysinliner-cpp-/#af5bb12426b6361914b816365eee4b4fd">anonymous{AlwaysInliner.cpp}::AlwaysInlineImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a158e2caed73e4b5d2ad70c1b2a0e0cc8">llvm::canSinkOrHoistInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#af1fba45879c49d4839b11ec30afd7532">checkMixedPrecision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a921421142b15c9fb9196fc4b0d7b77cb">llvm::computeUnrollCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#a0282ad8b650e02a78742f8a718f888f4">createFunctionClones</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a49a9acd58935033c9716f1b45d7df68a">deleteLoopIfDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a5e53eb62d81882a5586764e2a9378a49">DoFlattenLoopPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="#ae8f91b309992d6d1c1b43bf7d888c811">emit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp/#ae02f5a84142c2d7909ce301489a6adef">EmitAndPrintRemark</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0ce71d047dc00014a965d0907a0aabde">llvm::emitInlinedInto</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-misexpect-cpp-/#a2aa415fe106b04cb1941236bbca23edb">anonymous{MisExpect.cpp}::emitMisexpectDiagnostic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/hwaddresssanitizer-cpp/#af9c57b6a103aa3fdadcb6948dedcf255">emitRemark</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/lowerallowcheckpass-cpp/#a828a09e2cee6726e7ce806bfe21408a7">emitRemark</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ab930da454be280eb307c612727543eb6">expandToSwitch</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a1017f6873c8e5d75aa472aa3f06b48e3">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a4cda46bdec29ace64dfd3dff3e55bbf3">hasSupportedLoopDepth</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a3a3a3183a327e1186dbe900032390ec6">hoist</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#ab63d5eb7a9919d4e5f2c8d614e9bda97">isSafeToExecuteUnconditionally</a>, <a href="/web-llvm/docs/api/structs/anonymous-dfajumpthreading-cpp-/mainswitch/#a44c0d4c6651981ee2416dda63f93e0b7">anonymous{DFAJumpThreading.cpp}::MainSwitch::MainSwitch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/tailrecursionelimination-cpp/#af31ca6130fc1fdac86bfb75b1acac4ac">markTails</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#adcd261211472362965c5b1bc5a3efebe">populateDependencyMatrix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pgo/#ac3ab1f99a5d99ba23fcfec6044ebc805">llvm::pgo::promoteIndirectCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a292edc681e4846f695d627a99cb1560d">reportFastISelFailure</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuremoveincompatiblefunctions-cpp-/#a87374a870efdb5320c2019accfd96e75">anonymous{AMDGPURemoveIncompatibleFunctions.cpp}::reportFunctionRemoved</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hardwareloops-cpp-/#aae269bc7f800ec24fb92133d830f4764">anonymous{HardwareLoops.cpp}::reportHWLoopFailure</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#a3048c1b015753173fe58163dc4ad6bf6">reportLoadElim</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#a160dacda9f89b4c190ff303c6f4ed15e">reportMayClobberedLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c19b37908311872f655348755e8d003">llvm::reportVectorization</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab425bb10a0f4af749bbb29aa07fc6854">llvm::reportVectorizationFailure</a>, <a href="/web-llvm/docs/api/classes/llvm/ssplayoutanalysis/#a9263d83965e9f3c52e94ff91bc96eb9c">llvm::SSPLayoutAnalysis::requiresStackProtector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/annotationremarks-cpp/#ae33ca40f926442c4264c507f4d32c85e">runImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad272ce4631595e235e560baf59dc1ffd">llvm::setProfMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a874edeab85418837bb65d4d2ec4c5d0b">llvm::SITargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25e327ae759c3362067beb2aad1dbfdd">llvm::shouldInline</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a52b8b307321627e612e77041260ece84">sink</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a6c13c3a269c58cac403ad567c29d679e">verifyFuncBFI</a>, <a href="/web-llvm/docs/api/classes/llvm/memtag/stackinfobuilder/#a2a198373b43abedb70ae454c1111cdc8">llvm::memtag::StackInfoBuilder::visit</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/warnmissedtransforms-cpp/#ad8b755c8c24b50c227014d64af258cd1">warnAboutLeftoverTransformations</a>.</p>

</div>
</div>

### emit() {#ae8f91b309992d6d1c1b43bf7d888c811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::OptimizationRemarkEmitter::emit (T RemarkBuilder, decltype(RemarkBuilder()) *)</td>
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

<p>Take a lambda that returns a remark which will be emitted.</p>


<p>Second argument is only used to restrict this to functions.</p>


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>.</p>


<p>References <a href="#aae6a98aea85aa3af87357cc5448db499">emit</a>, <a href="#a3bce56db93bffc6af600a967c61c5d3e">enabled</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### enabled() {#a3bce56db93bffc6af600a967c61c5d3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OptimizationRemarkEmitter::enabled ()</td>
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

<p>Return true iff at least <em>some</em> remarks are enabled.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>.</p>


<p>Referenced by <a href="#ae8f91b309992d6d1c1b43bf7d888c811">emit</a>.</p>

</div>
</div>

### invalidate() {#a18f7d23f2e90a7ab59eda27fb77ec7d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool OptimizationRemarkEmitter::invalidate (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp; PA, FunctionAnalysisManager::Invalidator &amp; Inv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle invalidation events in the new pass manager.</p>

<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/optimizationremarkemitter-cpp">OptimizationRemarkEmitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeHotness() {#a67b757c2d9cd94a3692e8d094dd5b914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; OptimizationRemarkEmitter::computeHotness (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute hotness from IR value (currently assumed to be a block) if PGO is available.</p>

<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/optimizationremarkemitter-cpp">OptimizationRemarkEmitter.cpp</a>.</p>

</div>
</div>

### computeHotness() {#af13b9892a91342b04ae620a40948024b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OptimizationRemarkEmitter::computeHotness (<a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoiroptimization">DiagnosticInfoIROptimization</a> &amp; OptDiag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similar but use value from <span class="doxyComputerOutput">OptDiag</span> and update hotness there.</p>

<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/optimizationremarkemitter-cpp">OptimizationRemarkEmitter.cpp</a>.</p>

</div>
</div>

### shouldEmitVerbose() {#afee79e13f19ff1df4103059a2abfc07c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OptimizationRemarkEmitter::shouldEmitVerbose ()</td>
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

<p>Only allow verbose messages if we know we're filtering by hotness (BFI is only set in this case).</p>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BFI {#a4b7ee2182195c5d3f369fc54fe6ea037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfo* llvm::OptimizationRemarkEmitter::BFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>.</p>

</div>
</div>

### F {#a40ba1ebabffad398c5a3c6d0643a175b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function* llvm::OptimizationRemarkEmitter::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>.</p>

</div>
</div>

### OwnedBFI {#a83a6e292d262b1cc03c7f484df9ec961}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;BlockFrequencyInfo&gt; llvm::OptimizationRemarkEmitter::OwnedBFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If we generate BFI on demand, we need to free it when ORE is freed.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### allowExtraAnalysis() {#a19c3c3d0ac78d71ea5d4c759c8c8db9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OptimizationRemarkEmitter::allowExtraAnalysis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassName)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>.</p>


<p>References <a href="#a74b26949a0dd7a5fab2ba1b0da204e50">allowExtraAnalysis</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>.</p>

</div>
</div>

### allowExtraAnalysis() {#af6dacb86673ab0eec1cbbcdc1a031c77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OptimizationRemarkEmitter::allowExtraAnalysis (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PassName)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">OptimizationRemarkEmitter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/optimizationremarkemitter-cpp">OptimizationRemarkEmitter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
