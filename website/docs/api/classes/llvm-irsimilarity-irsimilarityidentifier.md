---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/irsimilarity/irsimilarityidentifier
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `IRSimilarityIdentifier` Class

<p>This class puts all the pieces of the <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper">IRInstructionMapper</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> together. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::IRSimilarity::IRSimilarityIdentifier { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">llvm/Analysis/IRSimilarityIdentifier.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c4131532750c5351e0baa4adfd59011">IRSimilarityIdentifier</a> (bool MatchBranches=true, bool MatchIndirectCalls=true, bool MatchCallsWithName=false, bool MatchIntrinsics=true, bool MatchMustTailCalls=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#a1e2d2e59b2467bacdc6db54dcc9bc4a1">SimilarityGroupList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab34199cfd6edb325744b61816910c1a">findSimilarity</a> (ArrayRef&lt; std::unique_ptr&lt; Module &gt; &gt; Modules)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#a1e2d2e59b2467bacdc6db54dcc9bc4a1">SimilarityGroupList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fe9caa9c99e1cdbc21e56f9f82417f0">findSimilarity</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d29ff1a4c56ed95827f1fc696fd1803">resetSimilarityCandidates</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#a1e2d2e59b2467bacdc6db54dcc9bc4a1">SimilarityGroupList</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa901661115f1c6c739c4d06f9094f78">getSimilarity</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a180833592f337b5a63ba76736941d0e6">populateMapper</a> (Module &amp;M, std::vector&lt; IRInstructionData * &gt; &amp;InstrList, std::vector&lt; unsigned &gt; &amp;IntegerMapping)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map the instructions in the module to unsigned integers, using mapping already present in the Mapper if possible. <a href="#a180833592f337b5a63ba76736941d0e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c25e2cf444910788d72624560fbe336">populateMapper</a> (ArrayRef&lt; std::unique_ptr&lt; Module &gt; &gt; &amp;Modules, std::vector&lt; IRInstructionData * &gt; &amp;InstrList, std::vector&lt; unsigned &gt; &amp;IntegerMapping)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map the instructions in the modules vector to unsigned integers, using mapping already present in the mapper if possible. <a href="#a1c25e2cf444910788d72624560fbe336">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53286cc1d5552f47be4b5127a6d30386">findCandidates</a> (std::vector&lt; IRInstructionData * &gt; &amp;InstrList, std::vector&lt; unsigned &gt; &amp;IntegerMapping)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the similarity candidates in <span class="doxyComputerOutput">InstrList</span> and corresponding <span class="doxyComputerOutput">UnsignedVec</span>. <a href="#a53286cc1d5552f47be4b5127a6d30386">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29f254901475076f46ef20de408e2bcd">InstDataAllocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The allocator for <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>. <a href="#a29f254901475076f46ef20de408e2bcd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondatalist">IRInstructionDataList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a176a3245ca3ef19d32ffdca4fd73f3f7">InstDataListAllocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The allocator for IRInstructionDataLists. <a href="#a176a3245ca3ef19d32ffdca4fd73f3f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper">IRInstructionMapper</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea0f78cbdd47f5f602541e21cbbbd4c7">Mapper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map Instructions to unsigned integers and wraps the <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> in an instance of <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>. <a href="#aea0f78cbdd47f5f602541e21cbbbd4c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71adf4465e2b0f139180f0290246bf56">EnableBranches</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The flag variable that marks whether we should check branches for similarity, or only look within basic blocks. <a href="#a71adf4465e2b0f139180f0290246bf56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab56e9a0bc42bc1a39688064c858abf0d">EnableIndirectCalls</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The flag variable that marks whether we allow indirect calls to be checked for similarity, or exclude them as a legal instruction. <a href="#ab56e9a0bc42bc1a39688064c858abf0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae35f73e96c5f1d86db6cc1de1d008ba5">EnableMatchingCallsByName</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The flag variable that marks whether we allow calls to be marked as similar if they do not have the same name, only the same calling convention, attributes and type signature. <a href="#ae35f73e96c5f1d86db6cc1de1d008ba5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91d25a35efb7454182bbe5229c83a3fb">EnableIntrinsics</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The flag variable that marks whether we should check intrinsics for similarity. <a href="#a91d25a35efb7454182bbe5229c83a3fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af276b17583d21f6f822e4c949228b2f7">EnableMustTailCalls</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#a1e2d2e59b2467bacdc6db54dcc9bc4a1">SimilarityGroupList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a017f7e88b856001e08549bb27c07b977">SimilarityCandidates</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The SimilarityGroups found with the most recent run of <a href="#aab34199cfd6edb325744b61816910c1a">findSimilarity</a>. <a href="#a017f7e88b856001e08549bb27c07b977">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class puts all the pieces of the <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper">IRInstructionMapper</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> together.</p>


<p>It first feeds the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> or vector of Modules into the <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper">IRInstructionMapper</a>, and puts all the mapped instructions into a single long list of <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>.</p>


<p>The list of unsigned integers is given to the Suffix Tree or similar data structure to find repeated subsequences. We construct an <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> for each instance of the subsequence. We compare them against one another since These repeated subsequences can have different structure. For each different kind of structure found, we create a similarity group.</p>


<p>If we had four IRSimilarityCandidates A, B, C, and D where A, B and D are structurally similar to one another, while C is different we would have two SimilarityGroups:</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#a2198f86ce16da838bdeea4de7e59ef31">SimilarityGroup</a> 1: <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#a2198f86ce16da838bdeea4de7e59ef31">SimilarityGroup</a> 2 A, B, D C</p>


<p>A list of the different similarity groups is then returned after analyzing the module.</p>


<p>Definition at line 1044 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IRSimilarityIdentifier() {#a3c4131532750c5351e0baa4adfd59011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IRSimilarity::IRSimilarityIdentifier::IRSimilarityIdentifier (bool MatchBranches=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool MatchIndirectCalls=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool MatchCallsWithName=false, bool MatchIntrinsics=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool MatchMustTailCalls=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 1046 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### findSimilarity() {#aab34199cfd6edb325744b61816910c1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SimilarityGroupList &amp; IRSimilarityIdentifier::findSimilarity (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; &gt; Modules)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1094 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 1438 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>Reference <a href="#a8d29ff1a4c56ed95827f1fc696fd1803">resetSimilarityCandidates</a>.</p>

</div>
</div>

### findSimilarity() {#a9fe9caa9c99e1cdbc21e56f9f82417f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SimilarityGroupList &amp; IRSimilarityIdentifier::findSimilarity (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 1456 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>Reference <a href="#a8d29ff1a4c56ed95827f1fc696fd1803">resetSimilarityCandidates</a>.</p>

</div>
</div>

### getSimilarity() {#afa901661115f1c6c739c4d06f9094f78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; SimilarityGroupList &gt; &amp; llvm::IRSimilarity::IRSimilarityIdentifier::getSimilarity ()</td>
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



<p>Definition at line 1116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/irsimilarityanalysisprinterpass/#a8dde7acadd30b1860704841855a1a07d">llvm::IRSimilarityAnalysisPrinterPass::run</a>.</p>

</div>
</div>

### resetSimilarityCandidates() {#a8d29ff1a4c56ed95827f1fc696fd1803}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IRSimilarity::IRSimilarityIdentifier::resetSimilarityCandidates ()</td>
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



<p>Definition at line 1104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#aab34199cfd6edb325744b61816910c1a">findSimilarity</a> and <a href="#a9fe9caa9c99e1cdbc21e56f9f82417f0">findSimilarity</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### findCandidates() {#a53286cc1d5552f47be4b5127a6d30386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRSimilarityIdentifier::findCandidates (std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> * &gt; &amp; InstrList, std::vector&lt; unsigned &gt; &amp; IntegerMapping)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the similarity candidates in <span class="doxyComputerOutput">InstrList</span> and corresponding <span class="doxyComputerOutput">UnsignedVec</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] InstrList</td>
<td class="doxyParamItemDescription"><p>- The vector to append <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] IntegerMapping</td>
<td class="doxyParamItemDescription"><p>- The vector to append integers to. candidates found in the program.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1083 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 1378 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>

</div>
</div>

### populateMapper() {#a180833592f337b5a63ba76736941d0e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRSimilarityIdentifier::populateMapper (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> * &gt; &amp; InstrList, std::vector&lt; unsigned &gt; &amp; IntegerMapping)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map the instructions in the module to unsigned integers, using mapping already present in the Mapper if possible.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] M</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> - To map to integers.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] InstrList</td>
<td class="doxyParamItemDescription"><p>- The vector to append <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] IntegerMapping</td>
<td class="doxyParamItemDescription"><p>- The vector to append integers to.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1064 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 908 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>

</div>
</div>

### populateMapper() {#a1c25e2cf444910788d72624560fbe336}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRSimilarityIdentifier::populateMapper (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; &gt; &amp; Modules, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> * &gt; &amp; InstrList, std::vector&lt; unsigned &gt; &amp; IntegerMapping)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map the instructions in the modules vector to unsigned integers, using mapping already present in the mapper if possible.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] Modules</td>
<td class="doxyParamItemDescription"><p>- The list of modules to use to populate the mapper</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] InstrList</td>
<td class="doxyParamItemDescription"><p>- The vector to append <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] IntegerMapping</td>
<td class="doxyParamItemDescription"><p>- The vector to append integers to.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1073 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 946 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EnableBranches {#a71adf4465e2b0f139180f0290246bf56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRSimilarity::IRSimilarityIdentifier::EnableBranches = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The flag variable that marks whether we should check branches for similarity, or only look within basic blocks.</p>

<p>Definition at line 1133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

### EnableIndirectCalls {#ab56e9a0bc42bc1a39688064c858abf0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRSimilarity::IRSimilarityIdentifier::EnableIndirectCalls = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The flag variable that marks whether we allow indirect calls to be checked for similarity, or exclude them as a legal instruction.</p>

<p>Definition at line 1137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

### EnableIntrinsics {#a91d25a35efb7454182bbe5229c83a3fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRSimilarity::IRSimilarityIdentifier::EnableIntrinsics = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The flag variable that marks whether we should check intrinsics for similarity.</p>

<p>Definition at line 1146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

### EnableMatchingCallsByName {#ae35f73e96c5f1d86db6cc1de1d008ba5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRSimilarity::IRSimilarityIdentifier::EnableMatchingCallsByName = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The flag variable that marks whether we allow calls to be marked as similar if they do not have the same name, only the same calling convention, attributes and type signature.</p>

<p>Definition at line 1142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

### EnableMustTailCalls {#af276b17583d21f6f822e4c949228b2f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRSimilarity::IRSimilarityIdentifier::EnableMustTailCalls = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

### InstDataAllocator {#a29f254901475076f46ef20de408e2bcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;IRInstructionData&gt; llvm::IRSimilarity::IRSimilarityIdentifier::InstDataAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The allocator for <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>.</p>

<p>Definition at line 1122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

### InstDataListAllocator {#a176a3245ca3ef19d32ffdca4fd73f3f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;IRInstructionDataList&gt; llvm::IRSimilarity::IRSimilarityIdentifier::InstDataListAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The allocator for IRInstructionDataLists.</p>

<p>Definition at line 1125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

### Mapper {#aea0f78cbdd47f5f602541e21cbbbd4c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRInstructionMapper llvm::IRSimilarity::IRSimilarityIdentifier::Mapper</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map Instructions to unsigned integers and wraps the <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> in an instance of <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>.</p>

<p>Definition at line 1129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

### SimilarityCandidates {#a017f7e88b856001e08549bb27c07b977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;SimilarityGroupList&gt; llvm::IRSimilarity::IRSimilarityIdentifier::SimilarityCandidates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The SimilarityGroups found with the most recent run of <a href="#aab34199cfd6edb325744b61816910c1a">findSimilarity</a>.</p>


<p>std::nullopt if there is no recent run.</p>


<p>Definition at line 1154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
