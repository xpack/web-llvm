---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machinebranchprobabilityinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachineBranchProbabilityInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MachineBranchProbabilityInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebranchprobabilityinfo-h">llvm/CodeGen/MachineBranchProbabilityInfo.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cdcc5c57bbaa51937e0eba3197be755">invalidate</a> (MachineFunction &amp;, const PreservedAnalyses &amp;PA, MachineFunctionAnalysisManager::Invalidator &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78fb9b4721b71aa297bd2bda44e7e39">getEdgeProbability</a> (const MachineBasicBlock *Src, const MachineBasicBlock *Dst) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af41c2e9c27e387f0dcd7be82afdfc347">getEdgeProbability</a> (const MachineBasicBlock *Src, MachineBasicBlock::const_succ_iterator Dst) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cd25f432a77253606cc6387d0057833">isEdgeHot</a> (const MachineBasicBlock *Src, const MachineBasicBlock *Dst) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22940e98d6895d17808a5b217d742b91">printEdgeProbability</a> (raw_ostream &amp;OS, const MachineBasicBlock *Src, const MachineBasicBlock *Dst) const</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b5407afc0edbbc0f4fb6bf264a7fd93">DEFAULT_WEIGHT</a> = 16</td>
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


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebranchprobabilityinfo-h">MachineBranchProbabilityInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getEdgeProbability() {#ad78fb9b4721b71aa297bd2bda44e7e39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability MachineBranchProbabilityInfo::getEdgeProbability (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebranchprobabilityinfo-h">MachineBranchProbabilityInfo.h</a>, definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebranchprobabilityinfo-cpp">MachineBranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a> and <a href="#ad78fb9b4721b71aa297bd2bda44e7e39">getEdgeProbability</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonloopalign-cpp-/hexagonloopalign/#a49530a2f7101146544b49c809bc2e035">anonymous{HexagonLoopAlign.cpp}::HexagonLoopAlign::attemptToBalignSmallLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a5f32c10b46f4e956f21552b0984ae68f">llvm::AsmPrinter::emitBBAddrMapSection</a>, <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#a1959523b897eac43ed99525fd9849be1">llvm::X86AsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#afa8ce195c40d446fbe801e412cbd4634">llvm::HexagonInstrInfo::getDotNewPredJumpOp</a>, <a href="#ad78fb9b4721b71aa297bd2bda44e7e39">getEdgeProbability</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonnewvaluejump-cpp/#afea8486b4f8f712c6fd71dbb0071f3a4">getNewValueJumpOpcode</a>, <a href="#a6cd25f432a77253606cc6387d0057833">isEdgeHot</a>, <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo/#a83b388502250fca34a5e23148e0d3bf2">llvm::MachineBlockFrequencyInfo::onEdgeSplit</a>, <a href="#a22940e98d6895d17808a5b217d742b91">printEdgeProbability</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>.</p>

</div>
</div>

### getEdgeProbability() {#af41c2e9c27e387f0dcd7be82afdfc347}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability MachineBranchProbabilityInfo::getEdgeProbability (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Src, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3f43e04d827b07cf1d5366554d03f748">MachineBasicBlock::const_succ_iterator</a> Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebranchprobabilityinfo-h">MachineBranchProbabilityInfo.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebranchprobabilityinfo-cpp">MachineBranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### invalidate() {#a3cdcc5c57bbaa51937e0eba3197be755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBranchProbabilityInfo::invalidate (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp; PA, MachineFunctionAnalysisManager::Invalidator &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebranchprobabilityinfo-h">MachineBranchProbabilityInfo.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebranchprobabilityinfo-cpp">MachineBranchProbabilityInfo.cpp</a>.</p>

</div>
</div>

### isEdgeHot() {#a6cd25f432a77253606cc6387d0057833}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBranchProbabilityInfo::isEdgeHot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebranchprobabilityinfo-h">MachineBranchProbabilityInfo.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebranchprobabilityinfo-cpp">MachineBranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="#ad78fb9b4721b71aa297bd2bda44e7e39">getEdgeProbability</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a75dea20875e2199efbf65662db1234d8">llvm::StaticLikelyProb</a>.</p>


<p>Referenced by <a href="#a22940e98d6895d17808a5b217d742b91">printEdgeProbability</a>.</p>

</div>
</div>

### printEdgeProbability() {#a22940e98d6895d17808a5b217d742b91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; MachineBranchProbabilityInfo::printEdgeProbability (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebranchprobabilityinfo-h">MachineBranchProbabilityInfo.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebranchprobabilityinfo-cpp">MachineBranchProbabilityInfo.cpp</a>.</p>


<p>References <a href="#ad78fb9b4721b71aa297bd2bda44e7e39">getEdgeProbability</a>, <a href="#a6cd25f432a77253606cc6387d0057833">isEdgeHot</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### DEFAULT\_WEIGHT {#a7b5407afc0edbbc0f4fb6bf264a7fd93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t llvm::MachineBranchProbabilityInfo::DEFAULT_WEIGHT = 16</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebranchprobabilityinfo-h">MachineBranchProbabilityInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebranchprobabilityinfo-h">MachineBranchProbabilityInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebranchprobabilityinfo-cpp">MachineBranchProbabilityInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
