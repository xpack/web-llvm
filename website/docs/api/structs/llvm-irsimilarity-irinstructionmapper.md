---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/irsimilarity/irinstructionmapper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `IRInstructionMapper` Struct Reference

<p>Helper struct for converting the Instructions in a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> into a vector of unsigned integers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::IRSimilarity::IRInstructionMapper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">llvm/Analysis/IRSimilarityIdentifier.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab074cefd064d3c9f84f7207dbee71724">IRInstructionMapper</a> (SpecificBumpPtrAllocator&lt; IRInstructionData &gt; *IDA, SpecificBumpPtrAllocator&lt; IRInstructionDataList &gt; *IDLA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac95ccee9d5cbc582a1bab1d1e9e854d">allocateIRInstructionData</a> (Instruction &amp;I, bool Legality, IRInstructionDataList &amp;IDL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an allocated <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> struct using the InstDataAllocator. <a href="#aac95ccee9d5cbc582a1bab1d1e9e854d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a81ca571e91f33e3a9e433e8bb075b3">allocateIRInstructionData</a> (IRInstructionDataList &amp;IDL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an empty allocated <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> struct using the InstDataAllocator. <a href="#a0a81ca571e91f33e3a9e433e8bb075b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondatalist">IRInstructionDataList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accaaf76a12845e506563d51d9617773d">allocateIRInstructionDataList</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an allocated <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondatalist">IRInstructionDataList</a> object using the IDLAllocator. <a href="#accaaf76a12845e506563d51d9617773d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c35c00b1125706d72f31c37b442fdc2">initializeForBBs</a> (Function &amp;F, unsigned &amp;BBNumber)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assigns values to all the basic blocks in function <span class="doxyComputerOutput">F</span> starting from integer <span class="doxyComputerOutput">BBNumber</span>. <a href="#a7c35c00b1125706d72f31c37b442fdc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac04bc0ac4b1620a9c9aa65c761b3344">initializeForBBs</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assigns values to all the basic blocks in <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> <span class="doxyComputerOutput">M</span>. <a href="#aac04bc0ac4b1620a9c9aa65c761b3344">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3af188e096e8a1152a33285a1c83c33">convertToUnsignedVec</a> (BasicBlock &amp;BB, std::vector&lt; IRInstructionData * &gt; &amp;InstrList, std::vector&lt; unsigned &gt; &amp;IntegerMapping)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps the Instructions in a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> <span class="doxyComputerOutput">BB</span> to legal or illegal integers determined by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bd">InstrType</a></span>. <a href="#ae3af188e096e8a1152a33285a1c83c33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae392ae2bd47b6a65a6d70f61ad7225a3">mapToLegalUnsigned</a> (BasicBlock::iterator &amp;It, std::vector&lt; unsigned &gt; &amp;IntegerMappingForBB, std::vector&lt; IRInstructionData * &gt; &amp;InstrListForBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to a legal integer. <a href="#ae392ae2bd47b6a65a6d70f61ad7225a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee2e5f8ff22ce6063643fea5c5b282d5">mapToIllegalUnsigned</a> (BasicBlock::iterator &amp;It, std::vector&lt; unsigned &gt; &amp;IntegerMappingForBB, std::vector&lt; IRInstructionData * &gt; &amp;InstrListForBB, bool End=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to an illegal integer. <a href="#aee2e5f8ff22ce6063643fea5c5b282d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60e5af3b7e239b6fdad88efbe1e861bd">IllegalInstrNumber</a> = static_cast&lt;unsigned&gt;(-3)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The starting illegal instruction number to map to. <a href="#a60e5af3b7e239b6fdad88efbe1e861bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a586d66c347a83ddac2d4552c720d3511">LegalInstrNumber</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The next available integer to assign to a legal <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to. <a href="#a586d66c347a83ddac2d4552c720d3511">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> *, unsigned, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondatatraits">IRInstructionDataTraits</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f22f1cd41d211cd1c0f3ada0f43d576">InstructionIntegerMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Correspondence from <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> to unsigned integers. <a href="#a0f22f1cd41d211cd1c0f3ada0f43d576">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac340be8c899d6572628a6944b17110bc">BasicBlockToInteger</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A mapping for a basic block in a module to its assigned number/location in the module. <a href="#ac340be8c899d6572628a6944b17110bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed7023ae0be840bc273712a9905e3c06">AddedIllegalLastTime</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set if we added an illegal number in the previous step. <a href="#aed7023ae0be840bc273712a9905e3c06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab943fd711b08ed084ecf2ed90abf1832">CanCombineWithPrevInstr</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Marks whether we found a illegal instruction in the previous step. <a href="#ab943fd711b08ed084ecf2ed90abf1832">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa21c1493313104ffa2d57c0379c4d145">HaveLegalRange</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Marks whether we have found a set of instructions that is long enough to be considered for similarity. <a href="#aa21c1493313104ffa2d57c0379c4d145">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ab651a0029c43f8639d98cbe3a4bc0c">EnableMatchCallsByName</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Marks whether we should use exact function names, as well as types to find similarity between calls. <a href="#a3ab651a0029c43f8639d98cbe3a4bc0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a300223e253d8cc149948becb9ef98378">InstDataAllocator</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This allocator pointer is in charge of holding on to the <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> so it is not deallocated until whatever external tool is using it is done with the information. <a href="#a300223e253d8cc149948becb9ef98378">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondatalist">IRInstructionDataList</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fdad6185139f685b846369c634a04cf">IDLAllocator</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This allocator pointer is in charge of creating the <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondatalist">IRInstructionDataList</a> so it is not deallocated until whatever external tool is using it is done with the information. <a href="#a2fdad6185139f685b846369c634a04cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondatalist">IRInstructionDataList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba61492b976936c3faf96a7713e175d9">IDL</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper/instructionclassification">InstructionClassification</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a0011906a29aacd3db06d94b41193e2">InstClassifier</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to a member of <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bd">InstrType</a>. <a href="#a7a0011906a29aacd3db06d94b41193e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper struct for converting the Instructions in a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> into a vector of unsigned integers.</p>


<p>This vector of unsigned integers can be thought of as a "numeric string". This numeric string can then be queried by, for example, data structures that find repeated substrings.</p>


<p>This hashing is done per <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> in the module. To hash Instructions based off of their operations, each <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> is wrapped in an <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> struct. The unsigned integer for an <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> depends on:</p>


<ul class="doxyList ">
<li>The hash provided by the <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>.</li>
<li>Which member of <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bd">InstrType</a> the <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> is classified as. The numeric string for an individual <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> is terminated by an unique unsigned integer. This prevents data structures which rely on repetition from matching across BasicBlocks. (For example, the <a href="/web-llvm/docs/api/classes/llvm/suffixtree">SuffixTree</a>.) As a concrete example, if we have the following two BasicBlocks:

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">bb0:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%add1 = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> i32 %a, %<a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea92eb5ffee6ae2fec3ad71c777531578f">b</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%add2 = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> i32 %c, %d</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%add3 = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> i64 %<a href="/web-llvm/docs/api/namespaces/llvm/numbers/#a92f4283d4e0e2ea1776894b3ae93640f">e</a>, %<a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea8fa14cdd754f91cc6554c9e71929cce7">f</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">bb1:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%<a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">sub</a> = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">sub</a> i32 %c, %d</span></span></div>

</div>


We may hash the Instructions like this (via <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>):

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">bb0:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%add1 = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> i32 %a, %<a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea92eb5ffee6ae2fec3ad71c777531578f">b</a> ; Hash: 1</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%add2 = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> i32 %c, %d; Hash: 1</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%add3 = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> i64 %<a href="/web-llvm/docs/api/namespaces/llvm/numbers/#a92f4283d4e0e2ea1776894b3ae93640f">e</a>, %<a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea8fa14cdd754f91cc6554c9e71929cce7">f</a>; Hash: 2</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">bb1:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%<a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">sub</a> = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">sub</a> i32 %c, %d; Hash: 3</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%add4 = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> i32 %c, %d ; Hash: 1</span></span></div>

</div>


And produce a "numeric string representation" like so: 1, 1, 2, unique_integer_1, 3, 1, unique_integer_2</li>
</ul>

<p>TODO: This is very similar to the MachineOutliner, and should be consolidated into the same interface.</p>


<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IRInstructionMapper() {#ab074cefd064d3c9f84f7207dbee71724}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IRSimilarity::IRInstructionMapper::IRInstructionMapper (<a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> &gt; * IDA, <a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondatalist">IRInstructionDataList</a> &gt; * IDLA)</td>
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



<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a1423601a8e4ec304e0756df4e761ebbb">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a9571e26b946751eaf015a9b8dc508be9">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getTombstoneKey</a>, <a href="#aba61492b976936c3faf96a7713e175d9">IDL</a>, <a href="#a2fdad6185139f685b846369c634a04cf">IDLAllocator</a> and <a href="#a300223e253d8cc149948becb9ef98378">InstDataAllocator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allocateIRInstructionData() {#aac95ccee9d5cbc582a1bab1d1e9e854d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRInstructionData * IRInstructionMapper::allocateIRInstructionData (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, bool Legality, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondatalist">IRInstructionDataList</a> &amp; IDL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get an allocated <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> struct using the InstDataAllocator.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">I</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to wrap with <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Legality</td>
<td class="doxyParamItemDescription"><p>- A boolean value that is true if the instruction is to be considered for similarity, and false if not.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IDL</td>
<td class="doxyParamItemDescription"><p>- The InstructionDataList that the <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> is inserted into.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An allocated <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> struct.</p></dd>
</dl>


<p>Declaration at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aba61492b976936c3faf96a7713e175d9">IDL</a> and <a href="#a300223e253d8cc149948becb9ef98378">InstDataAllocator</a>.</p>


<p>Referenced by <a href="#aee2e5f8ff22ce6063643fea5c5b282d5">mapToIllegalUnsigned</a> and <a href="#ae392ae2bd47b6a65a6d70f61ad7225a3">mapToLegalUnsigned</a>.</p>

</div>
</div>

### allocateIRInstructionData() {#a0a81ca571e91f33e3a9e433e8bb075b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRInstructionData * IRInstructionMapper::allocateIRInstructionData (<a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondatalist">IRInstructionDataList</a> &amp; IDL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get an empty allocated <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> struct using the InstDataAllocator.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">IDL</td>
<td class="doxyParamItemDescription"><p>- The InstructionDataList that the <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> is inserted into.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An allocated <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> struct.</p></dd>
</dl>


<p>Declaration at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="#aba61492b976936c3faf96a7713e175d9">IDL</a> and <a href="#a300223e253d8cc149948becb9ef98378">InstDataAllocator</a>.</p>

</div>
</div>

### allocateIRInstructionDataList() {#accaaf76a12845e506563d51d9617773d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRInstructionDataList * IRInstructionMapper::allocateIRInstructionDataList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get an allocated <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondatalist">IRInstructionDataList</a> object using the IDLAllocator.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An allocated <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondatalist">IRInstructionDataList</a> object.</p></dd>
</dl>


<p>Declaration at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>Reference <a href="#a2fdad6185139f685b846369c634a04cf">IDLAllocator</a>.</p>

</div>
</div>

### convertToUnsignedVec() {#ae3af188e096e8a1152a33285a1c83c33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRInstructionMapper::convertToUnsignedVec (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> * &gt; &amp; InstrList, std::vector&lt; unsigned &gt; &amp; IntegerMapping)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps the Instructions in a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> <span class="doxyComputerOutput">BB</span> to legal or illegal integers determined by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bd">InstrType</a></span>.</p>


<p>Two Instructions are mapped to the same value if they are close as defined by the InstructionData class above.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] BB</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> to be mapped to integers.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] InstrList</td>
<td class="doxyParamItemDescription"><p>- Vector of <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> to append to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] IntegerMapping</td>
<td class="doxyParamItemDescription"><p>- Vector of unsigned integers to append to.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="#aed7023ae0be840bc273712a9905e3c06">AddedIllegalLastTime</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="#aba61492b976936c3faf96a7713e175d9">IDL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bda16a84ba67d52e1c64fb48ce437b569ab">llvm::IRSimilarity::Illegal</a>, <a href="#a7a0011906a29aacd3db06d94b41193e2">InstClassifier</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bda47b7bba75c0c242b40fece427c2bfefa">llvm::IRSimilarity::Invisible</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bda8f7357506e00d8cd0694f948f909865d">llvm::IRSimilarity::Legal</a>, <a href="#aee2e5f8ff22ce6063643fea5c5b282d5">mapToIllegalUnsigned</a> and <a href="#ae392ae2bd47b6a65a6d70f61ad7225a3">mapToLegalUnsigned</a>.</p>

</div>
</div>

### initializeForBBs() {#a7c35c00b1125706d72f31c37b442fdc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IRSimilarity::IRInstructionMapper::initializeForBBs (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, unsigned &amp; BBNumber)</td>
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

<p>Assigns values to all the basic blocks in function <span class="doxyComputerOutput">F</span> starting from integer <span class="doxyComputerOutput">BBNumber</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">F</td>
<td class="doxyParamItemDescription"><p>- The function containing the basic blocks to assign numbers to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BBNumber</td>
<td class="doxyParamItemDescription"><p>- The number to start from.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>References <a href="#ac340be8c899d6572628a6944b17110bc">BasicBlockToInteger</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#aac04bc0ac4b1620a9c9aa65c761b3344">initializeForBBs</a>.</p>

</div>
</div>

### initializeForBBs() {#aac04bc0ac4b1620a9c9aa65c761b3344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IRSimilarity::IRInstructionMapper::initializeForBBs (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>Assigns values to all the basic blocks in <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> <span class="doxyComputerOutput">M</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">M</td>
<td class="doxyParamItemDescription"><p>- The module containing the basic blocks to assign numbers to.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a7c35c00b1125706d72f31c37b442fdc2">initializeForBBs</a>.</p>

</div>
</div>

### mapToIllegalUnsigned() {#aee2e5f8ff22ce6063643fea5c5b282d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned IRInstructionMapper::mapToIllegalUnsigned (<a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> &amp; It, std::vector&lt; unsigned &gt; &amp; IntegerMappingForBB, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> * &gt; &amp; InstrListForBB, bool End=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to an illegal integer.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] It</td>
<td class="doxyParamItemDescription"><p>- The <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></span> to be mapped to an integer.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] IntegerMappingForBB</td>
<td class="doxyParamItemDescription"><p>- Vector of unsigned integers to append to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] InstrListForBB</td>
<td class="doxyParamItemDescription"><p>- Vector of <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> to append to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">End</td>
<td class="doxyParamItemDescription"><p>- true if creating a dummy <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> at the end of a basic block.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The integer <span class="doxyComputerOutput">It</span> was mapped to.</p></dd>
</dl>


<p>Declaration at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="#aed7023ae0be840bc273712a9905e3c06">AddedIllegalLastTime</a>, <a href="#aac95ccee9d5cbc582a1bab1d1e9e854d">allocateIRInstructionData</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab943fd711b08ed084ecf2ed90abf1832">CanCombineWithPrevInstr</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a1423601a8e4ec304e0756df4e761ebbb">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a9571e26b946751eaf015a9b8dc508be9">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getTombstoneKey</a>, <a href="#aba61492b976936c3faf96a7713e175d9">IDL</a>, <a href="#a60e5af3b7e239b6fdad88efbe1e861bd">IllegalInstrNumber</a> and <a href="#a586d66c347a83ddac2d4552c720d3511">LegalInstrNumber</a>.</p>


<p>Referenced by <a href="#ae3af188e096e8a1152a33285a1c83c33">convertToUnsignedVec</a>.</p>

</div>
</div>

### mapToLegalUnsigned() {#ae392ae2bd47b6a65a6d70f61ad7225a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned IRInstructionMapper::mapToLegalUnsigned (<a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> &amp; It, std::vector&lt; unsigned &gt; &amp; IntegerMappingForBB, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> * &gt; &amp; InstrListForBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to a legal integer.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] It</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to be mapped to an integer.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] IntegerMappingForBB</td>
<td class="doxyParamItemDescription"><p>- Vector of unsigned integers to append to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] InstrListForBB</td>
<td class="doxyParamItemDescription"><p>- Vector of InstructionData to append to.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The integer <span class="doxyComputerOutput">It</span> was mapped to.</p></dd>
</dl>


<p>Declaration at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>, definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a>.</p>


<p>References <a href="#aed7023ae0be840bc273712a9905e3c06">AddedIllegalLastTime</a>, <a href="#aac95ccee9d5cbc582a1bab1d1e9e854d">allocateIRInstructionData</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac340be8c899d6572628a6944b17110bc">BasicBlockToInteger</a>, <a href="#ab943fd711b08ed084ecf2ed90abf1832">CanCombineWithPrevInstr</a>, <a href="#a3ab651a0029c43f8639d98cbe3a4bc0c">EnableMatchCallsByName</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a1423601a8e4ec304e0756df4e761ebbb">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a9571e26b946751eaf015a9b8dc508be9">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getTombstoneKey</a>, <a href="#aa21c1493313104ffa2d57c0379c4d145">HaveLegalRange</a>, <a href="#aba61492b976936c3faf96a7713e175d9">IDL</a>, <a href="#a60e5af3b7e239b6fdad88efbe1e861bd">IllegalInstrNumber</a>, <a href="#a0f22f1cd41d211cd1c0f3ada0f43d576">InstructionIntegerMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a586d66c347a83ddac2d4552c720d3511">LegalInstrNumber</a>.</p>


<p>Referenced by <a href="#ae3af188e096e8a1152a33285a1c83c33">convertToUnsignedVec</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AddedIllegalLastTime {#aed7023ae0be840bc273712a9905e3c06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRSimilarity::IRInstructionMapper::AddedIllegalLastTime = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set if we added an illegal number in the previous step.</p>


<p>Since each illegal number is unique, we only need one of them between each range of legal numbers. This lets us make sure we don't add more than one illegal number per range.</p>


<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#ae3af188e096e8a1152a33285a1c83c33">convertToUnsignedVec</a>, <a href="#aee2e5f8ff22ce6063643fea5c5b282d5">mapToIllegalUnsigned</a> and <a href="#ae392ae2bd47b6a65a6d70f61ad7225a3">mapToLegalUnsigned</a>.</p>

</div>
</div>

### BasicBlockToInteger {#ac340be8c899d6572628a6944b17110bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;BasicBlock *, unsigned&gt; llvm::IRSimilarity::IRInstructionMapper::BasicBlockToInteger</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A mapping for a basic block in a module to its assigned number/location in the module.</p>

<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#a7c35c00b1125706d72f31c37b442fdc2">initializeForBBs</a> and <a href="#ae392ae2bd47b6a65a6d70f61ad7225a3">mapToLegalUnsigned</a>.</p>

</div>
</div>

### CanCombineWithPrevInstr {#ab943fd711b08ed084ecf2ed90abf1832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRSimilarity::IRInstructionMapper::CanCombineWithPrevInstr = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Marks whether we found a illegal instruction in the previous step.</p>

<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#aee2e5f8ff22ce6063643fea5c5b282d5">mapToIllegalUnsigned</a> and <a href="#ae392ae2bd47b6a65a6d70f61ad7225a3">mapToLegalUnsigned</a>.</p>

</div>
</div>

### EnableMatchCallsByName {#a3ab651a0029c43f8639d98cbe3a4bc0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRSimilarity::IRInstructionMapper::EnableMatchCallsByName = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Marks whether we should use exact function names, as well as types to find similarity between calls.</p>

<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#ae392ae2bd47b6a65a6d70f61ad7225a3">mapToLegalUnsigned</a>.</p>

</div>
</div>

### HaveLegalRange {#aa21c1493313104ffa2d57c0379c4d145}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRSimilarity::IRInstructionMapper::HaveLegalRange = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Marks whether we have found a set of instructions that is long enough to be considered for similarity.</p>

<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#ae392ae2bd47b6a65a6d70f61ad7225a3">mapToLegalUnsigned</a>.</p>

</div>
</div>

### IDL {#aba61492b976936c3faf96a7713e175d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRInstructionDataList* llvm::IRSimilarity::IRInstructionMapper::IDL = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#aac95ccee9d5cbc582a1bab1d1e9e854d">allocateIRInstructionData</a>, <a href="#a0a81ca571e91f33e3a9e433e8bb075b3">allocateIRInstructionData</a>, <a href="#ae3af188e096e8a1152a33285a1c83c33">convertToUnsignedVec</a>, <a href="#ab074cefd064d3c9f84f7207dbee71724">IRInstructionMapper</a>, <a href="#aee2e5f8ff22ce6063643fea5c5b282d5">mapToIllegalUnsigned</a> and <a href="#ae392ae2bd47b6a65a6d70f61ad7225a3">mapToLegalUnsigned</a>.</p>

</div>
</div>

### IDLAllocator {#a2fdad6185139f685b846369c634a04cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;IRInstructionDataList&gt;* llvm::IRSimilarity::IRInstructionMapper::IDLAllocator = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This allocator pointer is in charge of creating the <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondatalist">IRInstructionDataList</a> so it is not deallocated until whatever external tool is using it is done with the information.</p>

<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#accaaf76a12845e506563d51d9617773d">allocateIRInstructionDataList</a> and <a href="#ab074cefd064d3c9f84f7207dbee71724">IRInstructionMapper</a>.</p>

</div>
</div>

### IllegalInstrNumber {#a60e5af3b7e239b6fdad88efbe1e861bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IRSimilarity::IRInstructionMapper::IllegalInstrNumber = static_cast&lt;unsigned&gt;(-3)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The starting illegal instruction number to map to.</p>


<p>Set to -3 for compatibility with <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo&lt;unsigned&gt;</a>.</p>


<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp/#adb57434f498dac697cfa36cd1cb9394c">createCandidatesFromSuffixTree</a>, <a href="#aee2e5f8ff22ce6063643fea5c5b282d5">mapToIllegalUnsigned</a> and <a href="#ae392ae2bd47b6a65a6d70f61ad7225a3">mapToLegalUnsigned</a>.</p>

</div>
</div>

### InstClassifier {#a7a0011906a29aacd3db06d94b41193e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionClassification llvm::IRSimilarity::IRInstructionMapper::InstClassifier</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to a member of <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bd">InstrType</a>.</p>

<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#ae3af188e096e8a1152a33285a1c83c33">convertToUnsignedVec</a>.</p>

</div>
</div>

### InstDataAllocator {#a300223e253d8cc149948becb9ef98378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;IRInstructionData&gt;* llvm::IRSimilarity::IRInstructionMapper::InstDataAllocator = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This allocator pointer is in charge of holding on to the <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> so it is not deallocated until whatever external tool is using it is done with the information.</p>

<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#aac95ccee9d5cbc582a1bab1d1e9e854d">allocateIRInstructionData</a>, <a href="#a0a81ca571e91f33e3a9e433e8bb075b3">allocateIRInstructionData</a> and <a href="#ab074cefd064d3c9f84f7207dbee71724">IRInstructionMapper</a>.</p>

</div>
</div>

### InstructionIntegerMap {#a0f22f1cd41d211cd1c0f3ada0f43d576}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;IRInstructionData *, unsigned, IRInstructionDataTraits&gt; llvm::IRSimilarity::IRInstructionMapper::InstructionIntegerMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Correspondence from <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> to unsigned integers.</p>

<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#ae392ae2bd47b6a65a6d70f61ad7225a3">mapToLegalUnsigned</a>.</p>

</div>
</div>

### LegalInstrNumber {#a586d66c347a83ddac2d4552c720d3511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IRSimilarity::IRInstructionMapper::LegalInstrNumber = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The next available integer to assign to a legal <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to.</p>

<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a>.</p>


<p>Referenced by <a href="#aee2e5f8ff22ce6063643fea5c5b282d5">mapToIllegalUnsigned</a> and <a href="#ae392ae2bd47b6a65a6d70f61ad7225a3">mapToLegalUnsigned</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">IRSimilarityIdentifier.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp">IRSimilarityIdentifier.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
