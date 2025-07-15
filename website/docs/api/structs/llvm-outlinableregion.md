---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/outlinableregion
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `OutlinableRegion` Struct Reference

<p>The <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> holds all the information for a specific region, or sequence of instructions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::OutlinableRegion { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">llvm/Transforms/IPO/IROutliner.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3f327e6f6a42e9b7729a16fbba4bc58">OutlinableRegion</a> (IRSimilarityCandidate &amp;C, OutlinableGroup &amp;Group)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a761b3c02cd196cb5f6fb019bcd86866e">splitCandidate</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the contained region, split the parent <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> at the starting and ending instructions of the contained <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>. <a href="#a761b3c02cd196cb5f6fb019bcd86866e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5d7aa7988108e9377f154cf6a22f02b">reattachCandidate</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the contained region, reattach the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> at the starting and ending instructions of the contained <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>, or if the function has been extracted, the start and end of the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> containing the called function. <a href="#af5d7aa7988108e9377f154cf6a22f02b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e03ba3e02776435b130c487f13289be">findCorrespondingValueIn</a> (const OutlinableRegion &amp;Other, Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find a corresponding value for <span class="doxyComputerOutput">V</span> in similar <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> <span class="doxyComputerOutput">Other</span>. <a href="#a7e03ba3e02776435b130c487f13289be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84b80673b9748e75da40fa84cca3a630">findCorrespondingBlockIn</a> (const OutlinableRegion &amp;Other, BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find a corresponding <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> for <span class="doxyComputerOutput">BB</span> in similar <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> <span class="doxyComputerOutput">Other</span>. <a href="#a84b80673b9748e75da40fa84cca3a630">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a086b69a5012fff81b179e92d137aae33">getBenefit</a> (TargetTransformInfo &amp;TTI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the size of the code removed from the region. <a href="#a086b69a5012fff81b179e92d137aae33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9db9e67d9d8c8f5c0cd2b8a64915f884">Candidate</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Describes the region of code. <a href="#a9db9e67d9d8c8f5c0cd2b8a64915f884">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a11fa118fe02011d314e8c435ab430e">NewFront</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this region is outlined, the front and back <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> could potentially become invalidated if the only new instruction is a call. <a href="#a3a11fa118fe02011d314e8c435ab430e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3864a66e1f77cc31e2b1acbdc12bf89">NewBack</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0bef07845f31f2c494f8e0565741dc9">NumExtractedInputs</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of extracted inputs from the <a href="/web-llvm/docs/api/classes/llvm/codeextractor">CodeExtractor</a>. <a href="#aa0bef07845f31f2c494f8e0565741dc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a262d2672038afdeba85e23a30ea4c22d">OutputBlockNum</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The corresponding <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> with the appropriate stores for this <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> in the overall function. <a href="#a262d2672038afdeba85e23a30ea4c22d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fd87f1e5fd502c0726451f97e8badf1">ExtractedArgToAgg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping the extracted argument number to the argument number in the overall function. <a href="#a7fd87f1e5fd502c0726451f97e8badf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e3fe29ac364265774e50fc0cecbda5c">AggArgToExtracted</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6e8e852e322a0a5383c6f0fce17daa2">RemappedArguments</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Values in the outlined functions will often be replaced by arguments. <a href="#aa6e8e852e322a0a5383c6f0fce17daa2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73d359ff9ba96a1a4576533dbb8d91b9">ChangedArgOrder</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Marks whether we need to change the order of the arguments when mapping the old extracted function call to the new aggregate outlined function call. <a href="#a73d359ff9ba96a1a4576533dbb8d91b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9bf08399ff5638f26f2f4eac57e03b2">EndsInBranch</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Marks whether this region ends in a branch, there is special handling required for the following basic blocks in this case. <a href="#ad9bf08399ff5638f26f2f4eac57e03b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6c689b51914b57c17eac0a2dbbacda6">PHIBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The PHIBlocks with their corresponding return block based on the return value as the key. <a href="#aa6c689b51914b57c17eac0a2dbbacda6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b119747211b5b2e6b4dbe6c50eb84fb">AggArgToConstant</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping of the argument number in the deduplicated function to a given constant, which is used when creating the arguments to the call to the newly created deduplicated function. <a href="#a0b119747211b5b2e6b4dbe6c50eb84fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c92ed5a8ec132b80f7737cba8bad0e8">GVNStores</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The global value numbers that are used as outputs for this section. <a href="#a3c92ed5a8ec132b80f7737cba8bad0e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeextractor">CodeExtractor</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06ee910ecb16eaaab4f069fa05c2a95a">CE</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to create an outlined function. <a href="#a06ee910ecb16eaaab4f069fa05c2a95a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a018669f7b1d6a21106f47398a087c30a">Call</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The call site of the extracted region. <a href="#a018669f7b1d6a21106f47398a087c30a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5dce467e0d3954ba812f2e9611810b4">ExtractedFunction</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The function for the extracted region. <a href="#ad5dce467e0d3954ba812f2e9611810b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a1b95a7f7c90784102fd63ffaa0ea00">CandidateSplit</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag for whether we have split out the IRSimilarityCanidate. <a href="#a6a1b95a7f7c90784102fd63ffaa0ea00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a737734321cd2dd3896e64015cab7ab95">IgnoreRegion</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag for whether we should not consider this region for extraction. <a href="#a737734321cd2dd3896e64015cab7ab95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f2224bfd6ac276c27b61578415e67df">PrevBB</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> that is before the start of the region <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>, only defined when the region has been split. <a href="#a8f2224bfd6ac276c27b61578415e67df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeea36f22dc87339b7be65179d3f249b6">StartBB</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> that contains the starting instruction of the region. <a href="#aeea36f22dc87339b7be65179d3f249b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92e2737e736f30a9984ccd08bbb902c7">EndBB</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> that contains the ending instruction of the region. <a href="#a92e2737e736f30a9984ccd08bbb902c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23d6f80b1fe2abb20b13b3c30864f423">FollowBB</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> that is after the start of the region <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>, only defined when the region has been split. <a href="#a23d6f80b1fe2abb20b13b3c30864f423">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/outlinablegroup">OutlinableGroup</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd706032a3800a5ee7c3ee8f83390996">Parent</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The Outlinable Group that contains this region and structurally similar regions to this region. <a href="#acd706032a3800a5ee7c3ee8f83390996">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> holds all the information for a specific region, or sequence of instructions.</p>


<p>This includes what values need to be hoisted to arguments from the extracted function, inputs and outputs to the region, and mapping from the extracted function arguments to overall function arguments.</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OutlinableRegion() {#ad3f327e6f6a42e9b7729a16fbba4bc58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OutlinableRegion::OutlinableRegion (<a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; C, <a href="/web-llvm/docs/api/structs/outlinablegroup">OutlinableGroup</a> &amp; Group)</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a9db9e67d9d8c8f5c0cd2b8a64915f884">Candidate</a>, <a href="#a92e2737e736f30a9984ccd08bbb902c7">EndBB</a>, <a href="#acd706032a3800a5ee7c3ee8f83390996">Parent</a> and <a href="#aeea36f22dc87339b7be65179d3f249b6">StartBB</a>.</p>


<p>Referenced by <a href="#a84b80673b9748e75da40fa84cca3a630">findCorrespondingBlockIn</a> and <a href="#a7e03ba3e02776435b130c487f13289be">findCorrespondingValueIn</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### findCorrespondingBlockIn() {#a84b80673b9748e75da40fa84cca3a630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * OutlinableRegion::findCorrespondingBlockIn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Other, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find a corresponding <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> for <span class="doxyComputerOutput">BB</span> in similar <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> <span class="doxyComputerOutput">Other</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Other</td>
<td class="doxyParamItemDescription"><p>[in] - The <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> to find the corresponding <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> in.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BB</td>
<td class="doxyParamItemDescription"><p>[in] - The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> to look for in the other region.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The corresponding <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to <span class="doxyComputerOutput">V</span> if it exists, otherwise nullptr.</p></dd>
</dl>


<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a7e03ba3e02776435b130c487f13289be">findCorrespondingValueIn</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a50909227135ef69932bff39b8ea3f572">llvm::BasicBlock::getFirstNonPHIOrDbg</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a1b4bf7c97cdc8159fd73d48063f0b250">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#ad3f327e6f6a42e9b7729a16fbba4bc58">OutlinableRegion</a>.</p>

</div>
</div>

### findCorrespondingValueIn() {#a7e03ba3e02776435b130c487f13289be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * OutlinableRegion::findCorrespondingValueIn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Other, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find a corresponding value for <span class="doxyComputerOutput">V</span> in similar <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> <span class="doxyComputerOutput">Other</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Other</td>
<td class="doxyParamItemDescription"><p>[in] - The <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> to find the corresponding <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> in.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">V</td>
<td class="doxyParamItemDescription"><p>[in] - The <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to look for in the other region.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The corresponding <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to <span class="doxyComputerOutput">V</span> if it exists, otherwise nullptr.</p></dd>
</dl>


<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>, definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9db9e67d9d8c8f5c0cd2b8a64915f884">Candidate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#ad3f327e6f6a42e9b7729a16fbba4bc58">OutlinableRegion</a>.</p>


<p>Referenced by <a href="#a84b80673b9748e75da40fa84cca3a630">findCorrespondingBlockIn</a>.</p>

</div>
</div>

### getBenefit() {#a086b69a5012fff81b179e92d137aae33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost OutlinableRegion::getBenefit (<a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the size of the code removed from the region.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068"&gt;TTI&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> for the parent function.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the code size of the region</p></dd>
</dl>


<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>, definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="#a9db9e67d9d8c8f5c0cd2b8a64915f884">Candidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba737cfc93e5a2ff961677d57186167e7c">llvm::TargetTransformInfo::TCK_CodeSize</a>.</p>

</div>
</div>

### reattachCandidate() {#af5d7aa7988108e9377f154cf6a22f02b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutlinableRegion::reattachCandidate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For the contained region, reattach the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> at the starting and ending instructions of the contained <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>, or if the function has been extracted, the start and end of the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> containing the called function.</p>

<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>, definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9db9e67d9d8c8f5c0cd2b8a64915f884">Candidate</a>, <a href="#a6a1b95a7f7c90784102fd63ffaa0ea00">CandidateSplit</a>, <a href="#a92e2737e736f30a9984ccd08bbb902c7">EndBB</a>, <a href="#ad9bf08399ff5638f26f2f4eac57e03b2">EndsInBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="#ad5dce467e0d3954ba812f2e9611810b4">ExtractedFunction</a>, <a href="#a23d6f80b1fe2abb20b13b3c30864f423">FollowBB</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aef9e9fcf4c5dfce90276ca16d91b8e46">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a57f1945911ca1e95d0f51d7c3516b529">llvm::BasicBlock::getUniqueSuccessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a3afc8c0c69b0c55edce3be13d5b7cc32">moveBBContents</a>, <a href="#a8f2224bfd6ac276c27b61578415e67df">PrevBB</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a089e003bb688e55b9a91ed4e7fed3678">llvm::BasicBlock::replaceSuccessorsPhiUsesWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a8e5c4577c64728c435eca5f4f7e163ab">replaceTargetsFromPHINode</a> and <a href="#aeea36f22dc87339b7be65179d3f249b6">StartBB</a>.</p>

</div>
</div>

### splitCandidate() {#a761b3c02cd196cb5f6fb019bcd86866e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutlinableRegion::splitCandidate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For the contained region, split the parent <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> at the starting and ending instructions of the contained <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a>.</p>

<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a43b79a254fba6ce00adf5b963382a0a4">llvm::Function::back</a>, <a href="#a9db9e67d9d8c8f5c0cd2b8a64915f884">Candidate</a>, <a href="#a6a1b95a7f7c90784102fd63ffaa0ea00">CandidateSplit</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a16413f1a88d8baca228d0a1b4cc0bfc6">llvm::SmallPtrSetImplBase::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#af74676a3c7447be34bd2c1da76ec0c48">llvm::SmallPtrSetImpl&lt; PtrType &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a92e2737e736f30a9984ccd08bbb902c7">EndBB</a>, <a href="#ad9bf08399ff5638f26f2f4eac57e03b2">EndsInBranch</a>, <a href="#a23d6f80b1fe2abb20b13b3c30864f423">FollowBB</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a91bd28adea418a08cec78b72413d9d45">llvm::Instruction::getNextNonDebugInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a7653277511df1034148a37520a585bb5">llvm::Instruction::isTerminator</a>, <a href="#a8f2224bfd6ac276c27b61578415e67df">PrevBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a8e5c4577c64728c435eca5f4f7e163ab">replaceTargetsFromPHINode</a> and <a href="#aeea36f22dc87339b7be65179d3f249b6">StartBB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AggArgToConstant {#a0b119747211b5b2e6b4dbe6c50eb84fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, Constant *&gt; llvm::OutlinableRegion::AggArgToConstant</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping of the argument number in the deduplicated function to a given constant, which is used when creating the arguments to the call to the newly created deduplicated function.</p>


<p>This is handled separately since the <a href="/web-llvm/docs/api/classes/llvm/codeextractor">CodeExtractor</a> does not recognize constants.</p>


<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### AggArgToExtracted {#a1e3fe29ac364265774e50fc0cecbda5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, unsigned&gt; llvm::OutlinableRegion::AggArgToExtracted</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### Call {#a018669f7b1d6a21106f47398a087c30a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst* llvm::OutlinableRegion::Call = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The call site of the extracted region.</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a4e06ebf129ddfb3b33a64f1a456cfc24">fillOverallFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#aac5cfc936b6963f4e848982328d39e8e">getSubprogramOrNull</a>.</p>

</div>
</div>

### Candidate {#a9db9e67d9d8c8f5c0cd2b8a64915f884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRSimilarityCandidate* llvm::OutlinableRegion::Candidate = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Describes the region of code.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>


<p>Referenced by <a href="#a7e03ba3e02776435b130c487f13289be">findCorrespondingValueIn</a>, <a href="#a086b69a5012fff81b179e92d137aae33">getBenefit</a>, <a href="#ad3f327e6f6a42e9b7729a16fbba4bc58">OutlinableRegion</a>, <a href="#af5d7aa7988108e9377f154cf6a22f02b">reattachCandidate</a> and <a href="#a761b3c02cd196cb5f6fb019bcd86866e">splitCandidate</a>.</p>

</div>
</div>

### CandidateSplit {#a6a1b95a7f7c90784102fd63ffaa0ea00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OutlinableRegion::CandidateSplit = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag for whether we have split out the IRSimilarityCanidate.</p>


<p>That is, make the region contained the <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> its own <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>.</p>


<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>


<p>Referenced by <a href="#af5d7aa7988108e9377f154cf6a22f02b">reattachCandidate</a> and <a href="#a761b3c02cd196cb5f6fb019bcd86866e">splitCandidate</a>.</p>

</div>
</div>

### CE {#a06ee910ecb16eaaab4f069fa05c2a95a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeExtractor* llvm::OutlinableRegion::CE = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to create an outlined function.</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### ChangedArgOrder {#a73d359ff9ba96a1a4576533dbb8d91b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OutlinableRegion::ChangedArgOrder = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Marks whether we need to change the order of the arguments when mapping the old extracted function call to the new aggregate outlined function call.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### EndBB {#a92e2737e736f30a9984ccd08bbb902c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* llvm::OutlinableRegion::EndBB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> that contains the ending instruction of the region.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>


<p>Referenced by <a href="#ad3f327e6f6a42e9b7729a16fbba4bc58">OutlinableRegion</a>, <a href="#af5d7aa7988108e9377f154cf6a22f02b">reattachCandidate</a> and <a href="#a761b3c02cd196cb5f6fb019bcd86866e">splitCandidate</a>.</p>

</div>
</div>

### EndsInBranch {#ad9bf08399ff5638f26f2f4eac57e03b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OutlinableRegion::EndsInBranch = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Marks whether this region ends in a branch, there is special handling required for the following basic blocks in this case.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>


<p>Referenced by <a href="#af5d7aa7988108e9377f154cf6a22f02b">reattachCandidate</a> and <a href="#a761b3c02cd196cb5f6fb019bcd86866e">splitCandidate</a>.</p>

</div>
</div>

### ExtractedArgToAgg {#a7fd87f1e5fd502c0726451f97e8badf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, unsigned&gt; llvm::OutlinableRegion::ExtractedArgToAgg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping the extracted argument number to the argument number in the overall function.</p>


<p>Since there will be inputs, such as elevated constants that are not the same in each region in a <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#a2198f86ce16da838bdeea4de7e59ef31">SimilarityGroup</a>, or values that cannot be sunk into the extracted section in every region, we must keep track of which extracted argument maps to which overall argument.</p>


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### ExtractedFunction {#ad5dce467e0d3954ba812f2e9611810b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::OutlinableRegion::ExtractedFunction = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The function for the extracted region.</p>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a4e06ebf129ddfb3b33a64f1a456cfc24">fillOverallFunction</a> and <a href="#af5d7aa7988108e9377f154cf6a22f02b">reattachCandidate</a>.</p>

</div>
</div>

### FollowBB {#a23d6f80b1fe2abb20b13b3c30864f423}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* llvm::OutlinableRegion::FollowBB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> that is after the start of the region <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>, only defined when the region has been split.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>


<p>Referenced by <a href="#af5d7aa7988108e9377f154cf6a22f02b">reattachCandidate</a> and <a href="#a761b3c02cd196cb5f6fb019bcd86866e">splitCandidate</a>.</p>

</div>
</div>

### GVNStores {#a3c92ed5a8ec132b80f7737cba8bad0e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 4&gt; llvm::OutlinableRegion::GVNStores</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The global value numbers that are used as outputs for this section.</p>


<p>Once extracted, each output will be stored to an output register. This documents the global value numbers that are used in this pattern.</p>


<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### IgnoreRegion {#a737734321cd2dd3896e64015cab7ab95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::OutlinableRegion::IgnoreRegion = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag for whether we should not consider this region for extraction.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### NewBack {#af3864a66e1f77cc31e2b1acbdc12bf89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRInstructionData* llvm::OutlinableRegion::NewBack = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### NewFront {#a3a11fa118fe02011d314e8c435ab430e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRInstructionData* llvm::OutlinableRegion::NewFront = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this region is outlined, the front and back <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> could potentially become invalidated if the only new instruction is a call.</p>


<p>This ensures that we replace in the instruction in the <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>.</p>


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### NumExtractedInputs {#aa0bef07845f31f2c494f8e0565741dc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::OutlinableRegion::NumExtractedInputs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of extracted inputs from the <a href="/web-llvm/docs/api/classes/llvm/codeextractor">CodeExtractor</a>.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### OutputBlockNum {#a262d2672038afdeba85e23a30ea4c22d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::OutlinableRegion::OutputBlockNum = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The corresponding <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> with the appropriate stores for this <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> in the overall function.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a4e06ebf129ddfb3b33a64f1a456cfc24">fillOverallFunction</a>.</p>

</div>
</div>

### Parent {#acd706032a3800a5ee7c3ee8f83390996}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutlinableGroup* llvm::OutlinableRegion::Parent = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The Outlinable Group that contains this region and structurally similar regions to this region.</p>

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>


<p>Referenced by <a href="#ad3f327e6f6a42e9b7729a16fbba4bc58">OutlinableRegion</a>.</p>

</div>
</div>

### PHIBlocks {#aa6c689b51914b57c17eac0a2dbbacda6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, BasicBlock *&gt; llvm::OutlinableRegion::PHIBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The PHIBlocks with their corresponding return block based on the return value as the key.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### PrevBB {#a8f2224bfd6ac276c27b61578415e67df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* llvm::OutlinableRegion::PrevBB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> that is before the start of the region <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>, only defined when the region has been split.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>


<p>Referenced by <a href="#af5d7aa7988108e9377f154cf6a22f02b">reattachCandidate</a> and <a href="#a761b3c02cd196cb5f6fb019bcd86866e">splitCandidate</a>.</p>

</div>
</div>

### RemappedArguments {#aa6e8e852e322a0a5383c6f0fce17daa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, Value *&gt; llvm::OutlinableRegion::RemappedArguments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Values in the outlined functions will often be replaced by arguments.</p>


<p>When finding corresponding values from one region to another, the found value will be the value the argument previously replaced. This structure maps any replaced values for the region to the aggregate aggregate argument in the overall function.</p>


<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a556a77d9b9acf322358b2c4131986b13">findOrCreatePHIInBlock</a>.</p>

</div>
</div>

### StartBB {#aeea36f22dc87339b7be65179d3f249b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* llvm::OutlinableRegion::StartBB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> that contains the starting instruction of the region.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>


<p>Referenced by <a href="#ad3f327e6f6a42e9b7729a16fbba4bc58">OutlinableRegion</a>, <a href="#af5d7aa7988108e9377f154cf6a22f02b">reattachCandidate</a> and <a href="#a761b3c02cd196cb5f6fb019bcd86866e">splitCandidate</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
