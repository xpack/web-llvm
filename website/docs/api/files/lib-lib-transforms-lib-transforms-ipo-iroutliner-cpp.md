---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `IROutliner.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">llvm/Transforms/IPO/IROutliner.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/irsimilarityidentifier-h">llvm/Analysis/IRSimilarityIdentifier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">llvm/Analysis/OptimizationRemarkEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">llvm/IR/DIBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">llvm/IR/DebugInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mangler-h">llvm/IR/Mangler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/ipo-h">llvm/Transforms/IPO.h</a>"
#include &lt;optional&gt;
#include &lt;vector&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/outlinablegroup">OutlinableGroup</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/structs/outlinablegroup">OutlinableGroup</a> holds all the overarching information for outlining a set of regions that are structurally similar to one another, such as the types of the overall function, the output blocks, the sets of stores needed and a list of the different regions. <a href="/web-llvm/docs/api/structs/outlinablegroup/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0fabe111fc0db047a04c21481fa6aab">ArgLocWithBBCanon</a> = std::pair&lt; unsigned, unsigned &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69893e3a4e9fbee5b5aa9ac4b036dc5c">CanonList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 2 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0389cc3001a985e14dcff4067684ad70">PHINodeData</a> = std::pair&lt; <a href="#ad0fabe111fc0db047a04c21481fa6aab">ArgLocWithBBCanon</a>, <a href="#a69893e3a4e9fbee5b5aa9ac4b036dc5c">CanonList</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3afc8c0c69b0c55edce3be13d5b7cc32">moveBBContents</a> (BasicBlock &amp;SourceBB, BasicBlock &amp;TargetBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move the contents of <span class="doxyComputerOutput">SourceBB</span> to before the last instruction of <span class="doxyComputerOutput">TargetBB</span>. <a href="#a3afc8c0c69b0c55edce3be13d5b7cc32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ad786f21829d9e92d31cc0b80c53dbb">getSortedConstantKeys</a> (std::vector&lt; Value * &gt; &amp;SortedKeys, DenseMap&lt; Value *, BasicBlock * &gt; &amp;Map)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A function to sort the keys of <span class="doxyComputerOutput">Map</span>, which must be a mapping of constant values to basic blocks and return it in <span class="doxyComputerOutput">SortedKeys</span>. <a href="#a8ad786f21829d9e92d31cc0b80c53dbb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e5c4577c64728c435eca5f4f7e163ab">replaceTargetsFromPHINode</a> (BasicBlock *PHIBlock, BasicBlock *Find, BasicBlock *Replace, DenseSet&lt; BasicBlock * &gt; &amp;Included)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite the BranchInsts in the incoming blocks to <span class="doxyComputerOutput">PHIBlock</span> that are found in <span class="doxyComputerOutput">Included</span> to branch to <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> <span class="doxyComputerOutput">Replace</span> if they currently branch to the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> <span class="doxyComputerOutput">Find</span>. <a href="#a8e5c4577c64728c435eca5f4f7e163ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac77f2569521257316a0f374b9a2682c5">constantMatches</a> (Value *V, unsigned GVN, DenseMap&lt; unsigned, Constant * &gt; &amp;GVNToConstant)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find whether <span class="doxyComputerOutput">V</span> matches the Constants previously found for the <span class="doxyComputerOutput">GVN</span>. <a href="#ac77f2569521257316a0f374b9a2682c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0d72084e637eaecbbadd192d547ef8e">findOutputMapping</a> (const DenseMap&lt; Value *, Value * &gt; OutputMappings, Value *Input)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> the <span class="doxyComputerOutput">OutputMappings</span> structure for value <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/input">Input</a></span>, if it exists it has been used as an output for outlining, and has been renamed, and we return the new value, otherwise, we return the same value. <a href="#ab0d72084e637eaecbbadd192d547ef8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52a09c04ddc4ec6d039f1f11f01d019e">collectRegionsConstants</a> (OutlinableRegion &amp;Region, DenseMap&lt; unsigned, Constant * &gt; &amp;GVNToConstant, DenseSet&lt; unsigned &gt; &amp;NotSame)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find whether <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span> matches the global value numbering to <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> mapping found so far. <a href="#a52a09c04ddc4ec6d039f1f11f01d019e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac5cfc936b6963f4e848982328d39e8e">getSubprogramOrNull</a> (OutlinableGroup &amp;Group)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the subprogram if it exists for one of the outlined regions. <a href="#aac5cfc936b6963f4e848982328d39e8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4047976de351f78967fba27df7a6361f">moveFunctionData</a> (Function &amp;Old, Function &amp;New, DenseMap&lt; Value *, BasicBlock * &gt; &amp;NewEnds)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move each <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> in <span class="doxyComputerOutput">Old</span> to <span class="doxyComputerOutput">New</span>. <a href="#a4047976de351f78967fba27df7a6361f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acda959f961048eba09125aba48d1142e">findConstants</a> (IRSimilarityCandidate &amp;C, DenseSet&lt; unsigned &gt; &amp;NotSame, std::vector&lt; unsigned &gt; &amp;Inputs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the constants that will need to be lifted into arguments as they are not the same in each instance of the region. <a href="#acda959f961048eba09125aba48d1142e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9165dd298666d75ed2e5be7d5d8b50e5">mapInputsToGVNs</a> (IRSimilarityCandidate &amp;C, SetVector&lt; Value * &gt; &amp;CurrentInputs, const DenseMap&lt; Value *, Value * &gt; &amp;OutputMappings, std::vector&lt; unsigned &gt; &amp;EndInputNumbers)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the GVN for the inputs that have been found by the <a href="/web-llvm/docs/api/classes/llvm/codeextractor">CodeExtractor</a>. <a href="#a9165dd298666d75ed2e5be7d5d8b50e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09e9f16b4a1aaf539000b95bf5442155">remapExtractedInputs</a> (const ArrayRef&lt; Value * &gt; ArgInputs, const DenseMap&lt; Value *, Value * &gt; &amp;OutputMappings, SetVector&lt; Value * &gt; &amp;RemappedArgInputs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the original value for the <span class="doxyComputerOutput">ArgInput</span> values if any one of them was replaced during a previous extraction. <a href="#a09e9f16b4a1aaf539000b95bf5442155">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48d81e3f58b8db143bc85763d25dbc7a">getCodeExtractorArguments</a> (OutlinableRegion &amp;Region, std::vector&lt; unsigned &gt; &amp;InputGVNs, DenseSet&lt; unsigned &gt; &amp;NotSame, DenseMap&lt; Value *, Value * &gt; &amp;OutputMappings, SetVector&lt; Value * &gt; &amp;ArgInputs, SetVector&lt; Value * &gt; &amp;Outputs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the input GVNs and the output values for a region of Instructions. <a href="#a48d81e3f58b8db143bc85763d25dbc7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9148948069532c9a5e1b59e3668b8cc3">findExtractedInputToOverallInputMapping</a> (OutlinableRegion &amp;Region, std::vector&lt; unsigned &gt; &amp;InputGVNs, SetVector&lt; Value * &gt; &amp;ArgInputs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look over the inputs and map each input argument to an argument in the overall function for the OutlinableRegions. <a href="#a9148948069532c9a5e1b59e3668b8cc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84e785627d5ab55370b5fa402ad7193f">outputHasNonPHI</a> (Value *V, unsigned PHILoc, PHINode &amp;PN, SmallPtrSet&lt; BasicBlock *, 1 &gt; &amp;Exits, DenseSet&lt; BasicBlock * &gt; &amp;BlocksInRegion)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the <span class="doxyComputerOutput">V</span> has any uses outside of the region other than <span class="doxyComputerOutput">PN</span>. <a href="#a84e785627d5ab55370b5fa402ad7193f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a882dcfc2455d525e78a8bbf46863ace2">analyzeExitPHIsForOutputUses</a> (BasicBlock *CurrentExitFromRegion, SmallPtrSet&lt; BasicBlock *, 1 &gt; &amp;PotentialExitsFromRegion, DenseSet&lt; BasicBlock * &gt; &amp;RegionBlocks, SetVector&lt; Value * &gt; &amp;Outputs, DenseSet&lt; Value * &gt; &amp;OutputsReplacedByPHINode, DenseSet&lt; Value * &gt; &amp;OutputsWithNonPhiUses)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether <span class="doxyComputerOutput">CurrentExitFromRegion</span> contains any PhiNodes that should be considered outputs. <a href="#a882dcfc2455d525e78a8bbf46863ace2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a652d50395284a0dec463c533709bc231">encodePHINodeData</a> (PHINodeData &amp;PND)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode <span class="doxyComputerOutput">PND</span> as an integer for easy lookup based on the argument location, the parent <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> canonical numbering, and the canonical numbering of the values stored in the <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>. <a href="#a652d50395284a0dec463c533709bc231">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c7b2c4c8824cfb8d35c97f6923c3fe2">getGVNForPHINode</a> (OutlinableRegion &amp;Region, PHINode *PN, DenseSet&lt; BasicBlock * &gt; &amp;Blocks, unsigned AggArgIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a special GVN for PHINodes that will be used outside of the region. <a href="#a1c7b2c4c8824cfb8d35c97f6923c3fe2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eb66b98a828331ed6cb79ae82c0336f">findExtractedOutputToOverallOutputMapping</a> (Module &amp;M, OutlinableRegion &amp;Region, SetVector&lt; Value * &gt; &amp;Outputs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a mapping of the output arguments for the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span> to the output arguments of the overall outlined function. <a href="#a4eb66b98a828331ed6cb79ae82c0336f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e2cad7ab18db9a3c940afc609c223dc">replaceCalledFunction</a> (Module &amp;M, OutlinableRegion &amp;Region)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace the extracted function in the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> with a call to the overall function constructed from the deduplicated similar regions, replacing and remapping the values passed to the extracted function as arguments to the new arguments of the overall function. <a href="#a7e2cad7ab18db9a3c940afc609c223dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af30ff2458bb283e423c1fc242a468579">findOrCreatePHIBlock</a> (OutlinableGroup &amp;Group, Value *RetVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find or create a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> in the outlined function containing PhiBlocks for <span class="doxyComputerOutput">RetVal</span>. <a href="#af30ff2458bb283e423c1fc242a468579">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad69884d9bf751011f8f9049542bbbd01">getPassedArgumentInAlreadyOutlinedFunction</a> (const Argument *A, const OutlinableRegion &amp;Region)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the function call now representing the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span>, find the passed value to that call that represents <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> <span class="doxyComputerOutput">A</span> at the call location if the call has already been replaced with a call to the overall, aggregate function. <a href="#ad69884d9bf751011f8f9049542bbbd01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a202f8ebe30581a7e75bcedc9dee531af">getPassedArgumentAndAdjustArgumentLocation</a> (const Argument *A, const OutlinableRegion &amp;Region)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the function call now representing the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span>, find the passed value to that call that represents <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> <span class="doxyComputerOutput">A</span> at the call location if the call has only been replaced by the call to the aggregate function. <a href="#a202f8ebe30581a7e75bcedc9dee531af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26b0639ceb3f28de2e6a283098c525b2">findCanonNumsForPHI</a> (PHINode *PN, OutlinableRegion &amp;Region, const DenseMap&lt; Value *, Value * &gt; &amp;OutputMappings, SmallVector&lt; std::pair&lt; unsigned, BasicBlock * &gt; &gt; &amp;CanonNums, bool ReplacedWithOutlinedCall=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the canonical numbering for the incoming Values into the <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> <span class="doxyComputerOutput">PN</span>. <a href="#a26b0639ceb3f28de2e6a283098c525b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a556a77d9b9acf322358b2c4131986b13">findOrCreatePHIInBlock</a> (PHINode &amp;PN, OutlinableRegion &amp;Region, BasicBlock *OverallPhiBlock, const DenseMap&lt; Value *, Value * &gt; &amp;OutputMappings, DenseSet&lt; PHINode * &gt; &amp;UsedPHIs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find, or add <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> <span class="doxyComputerOutput">PN</span> to the combined <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> Block <span class="doxyComputerOutput">OverallPHIBlock</span> in order to condense the number of instructions added to the outlined function. <a href="#a556a77d9b9acf322358b2c4131986b13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96b5bd50d8e96b4c76ffc26508ce774d">replaceArgumentUses</a> (OutlinableRegion &amp;Region, DenseMap&lt; Value *, BasicBlock * &gt; &amp;OutputBBs, const DenseMap&lt; Value *, Value * &gt; &amp;OutputMappings, bool FirstFunction=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace02ac07a3f704ffd345301bff92e5a8">replaceConstants</a> (OutlinableRegion &amp;Region)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Within an extracted function, replace the constants that need to be lifted into arguments with the actual argument. <a href="#ace02ac07a3f704ffd345301bff92e5a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af714eb55aced0ac27294c881d8be6ecb">findDuplicateOutputBlock</a> (DenseMap&lt; Value *, BasicBlock * &gt; &amp;OutputBBs, std::vector&lt; DenseMap&lt; Value *, BasicBlock * &gt; &gt; &amp;OutputStoreBBs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>It is possible that there is a basic block that already performs the same stores. <a href="#af714eb55aced0ac27294c881d8be6ecb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57d54880afa1fb74833cc7c43ad33377">analyzeAndPruneOutputBlocks</a> (DenseMap&lt; Value *, BasicBlock * &gt; &amp;BlocksToPrune, OutlinableRegion &amp;Region)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove empty output blocks from the outlined region. <a href="#a57d54880afa1fb74833cc7c43ad33377">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fcb90c9c38b3381765a891d0a61c1ea">alignOutputBlockWithAggFunc</a> (OutlinableGroup &amp;OG, OutlinableRegion &amp;Region, DenseMap&lt; Value *, BasicBlock * &gt; &amp;OutputBBs, DenseMap&lt; Value *, BasicBlock * &gt; &amp;EndBBs, const DenseMap&lt; Value *, Value * &gt; &amp;OutputMappings, std::vector&lt; DenseMap&lt; Value *, BasicBlock * &gt; &gt; &amp;OutputStoreBBs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the outlined section, move needed the StoreInsts for the output registers into their own block. <a href="#a4fcb90c9c38b3381765a891d0a61c1ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8120984c169f2ea17e785e7c6887702a">createAndInsertBasicBlocks</a> (DenseMap&lt; Value *, BasicBlock * &gt; &amp;OldMap, DenseMap&lt; Value *, BasicBlock * &gt; &amp;NewMap, Function *ParentFunc, Twine BaseName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Takes in a mapping, <span class="doxyComputerOutput">OldMap</span> of ConstantValues to BasicBlocks, sorts keys, before creating a basic block for each <span class="doxyComputerOutput">NewMap</span>, and inserting into the new block. <a href="#a8120984c169f2ea17e785e7c6887702a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae86fef7fc5831c2514bff95bdf784d09">createSwitchStatement</a> (Module &amp;M, OutlinableGroup &amp;OG, DenseMap&lt; Value *, BasicBlock * &gt; &amp;EndBBs, std::vector&lt; DenseMap&lt; Value *, BasicBlock * &gt; &gt; &amp;OutputStoreBBs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the switch statement for outlined function to differentiate between all the output blocks. <a href="#ae86fef7fc5831c2514bff95bdf784d09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e06ebf129ddfb3b33a64f1a456cfc24">fillOverallFunction</a> (Module &amp;M, OutlinableGroup &amp;CurrentGroup, std::vector&lt; DenseMap&lt; Value *, BasicBlock * &gt; &gt; &amp;OutputStoreBBs, std::vector&lt; Function * &gt; &amp;FuncsToRemove, const DenseMap&lt; Value *, Value * &gt; &amp;OutputMappings)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fill the new function that will serve as the replacement function for all of the extracted regions of a certain structure from the first region in the list of regions. <a href="#a4e06ebf129ddfb3b33a64f1a456cfc24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bc949e06e148a6d2879eb45ca164146">nextIRInstructionDataMatchesNextInst</a> (IRInstructionData &amp;ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks that the next instruction in the InstructionDataList matches the next instruction in the module. <a href="#a3bc949e06e148a6d2879eb45ca164146">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4b0641c5ffeeb3249b4ce9bb98c1a2d">findOutputValueInRegion</a> (OutlinableRegion &amp;Region, unsigned OutputCanon)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the <span class="doxyComputerOutput">OutputCanon</span> number passed in find the value represented by this canonical number. <a href="#ab4b0641c5ffeeb3249b4ce9bb98c1a2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b12ae89227758cb5684cc7cf25a7f43">findCostForOutputBlocks</a> (Module &amp;M, OutlinableGroup &amp;CurrentGroup, TargetTransformInfo &amp;TTI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the extra instructions needed to handle any output values for the region. <a href="#a8b12ae89227758cb5684cc7cf25a7f43">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a415af6f4421aa68820b3279b48acd928">EnableLinkOnceODRIROutlining</a>("enable-linkonceodr-ir-outlining", cl::Hidden, cl::desc("Enable the IR outliner on linkonceodr functions"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dfbf70cabc04c37f6f46b2c312b2506">NoCostModel</a>("ir-outlining-no-cost", cl::init(false), cl::ReallyHidden, cl::desc("Debug option to outline greedily, without restriction that " "calculated benefit outweighs cost"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"iroutliner"</td>
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

### ArgLocWithBBCanon {#ad0fabe111fc0db047a04c21481fa6aab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using ArgLocWithBBCanon =  std::pair&lt;unsigned, unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1141 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>

</div>
</div>

### CanonList {#a69893e3a4e9fbee5b5aa9ac4b036dc5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using CanonList =  SmallVector&lt;unsigned, 2&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1143 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>

</div>
</div>

### PHINodeData {#a0389cc3001a985e14dcff4067684ad70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using PHINodeData =  std::pair&lt;ArgLocWithBBCanon, CanonList&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1146 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### alignOutputBlockWithAggFunc() {#a4fcb90c9c38b3381765a891d0a61c1ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void alignOutputBlockWithAggFunc (<a href="/web-llvm/docs/api/structs/outlinablegroup">OutlinableGroup</a> &amp; OG, <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Region, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; OutputBBs, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; EndBBs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; OutputMappings, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &gt; &amp; OutputStoreBBs)</td>
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

<p>For the outlined section, move needed the StoreInsts for the output registers into their own block.</p>


<p>Then, determine if there is a duplicate output block already created.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] OG</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/structs/outlinablegroup">OutlinableGroup</a> of regions to be outlined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/region"&gt;Region&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> that is being analyzed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] OutputBBs</td>
<td class="doxyParamItemDescription"><p>- the blocks that stores for this region will be placed in.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] EndBBs</td>
<td class="doxyParamItemDescription"><p>- the final blocks of the extracted function.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] OutputMappings</td>
<td class="doxyParamItemDescription"><p>- OutputMappings the mapping of values that have been replaced by a new output value.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] OutputStoreBBs</td>
<td class="doxyParamItemDescription"><p>- The existing output blocks.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 2069 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="#a57d54880afa1fb74833cc7c43ad33377">analyzeAndPruneOutputBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a9f40e42226cee617c16cb1c447b115c5">llvm::BranchInst::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="#af714eb55aced0ac27294c881d8be6ecb">findDuplicateOutputBlock</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### analyzeAndPruneOutputBlocks() {#a57d54880afa1fb74833cc7c43ad33377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool analyzeAndPruneOutputBlocks (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; BlocksToPrune, <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Region)</td>
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

<p>Remove empty output blocks from the outlined region.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BlocksToPrune</td>
<td class="doxyParamItemDescription"><p>- Mapping of return values output blocks for the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/region"&gt;Region&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> we are analyzing.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 2022 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a1eb8504bab5f794778d82db6ac829923">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a8dd327a937563afdb08250abc43820b0">llvm::BasicBlock::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#ab9f68be0e2bcdf14f503f45edea63023">llvm::BasicBlock::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a3bf42baf773b375802538951c88d8e12">ToRemove</a>.</p>


<p>Referenced by <a href="#a4fcb90c9c38b3381765a891d0a61c1ea">alignOutputBlockWithAggFunc</a> and <a href="#a4e06ebf129ddfb3b33a64f1a456cfc24">fillOverallFunction</a>.</p>

</div>
</div>

### analyzeExitPHIsForOutputUses() {#a882dcfc2455d525e78a8bbf46863ace2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void analyzeExitPHIsForOutputUses (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * CurrentExitFromRegion, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 1 &gt; &amp; PotentialExitsFromRegion, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; RegionBlocks, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; Outputs, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; OutputsReplacedByPHINode, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; OutputsWithNonPhiUses)</td>
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

<p>Test whether <span class="doxyComputerOutput">CurrentExitFromRegion</span> contains any PhiNodes that should be considered outputs.</p>


<p>A PHINodes is an output when more than one incoming value has been marked by the <a href="/web-llvm/docs/api/classes/llvm/codeextractor">CodeExtractor</a> as an output.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CurrentExitFromRegion</td>
<td class="doxyParamItemDescription"><p>[in] - The block to analyze.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PotentialExitsFromRegion</td>
<td class="doxyParamItemDescription"><p>[in] - The potential exit blocks from the region.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RegionBlocks</td>
<td class="doxyParamItemDescription"><p>[in] - The basic blocks in the region.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Outputs</td>
<td class="doxyParamItemDescription"><p>[in, out] - The existing outputs for the region, we may add PHINodes to this as we find that they replace output values.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OutputsReplacedByPHINode</td>
<td class="doxyParamItemDescription"><p>[out] - A set containing outputs that are totally replaced by a <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OutputsWithNonPhiUses</td>
<td class="doxyParamItemDescription"><p>[out] - A set containing outputs that are used in PHINodes, but have other uses, and should still be considered outputs.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1093 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#af972d87e15b5f6ed61bd5c3956c5213d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::erase</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="#a84e785627d5ab55370b5fa402ad7193f">outputHasNonPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a13da92d2694197fbcb5b95fd94e7570d">llvm::BasicBlock::phis</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a4eb66b98a828331ed6cb79ae82c0336f">findExtractedOutputToOverallOutputMapping</a>.</p>

</div>
</div>

### collectRegionsConstants() {#a52a09c04ddc4ec6d039f1f11f01d019e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool collectRegionsConstants (<a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Region, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; &amp; GVNToConstant, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt; &amp; NotSame)</td>
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

<p>Find whether <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span> matches the global value numbering to <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> mapping found so far.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/region"&gt;Region&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> we are checking for constants</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GVNToConstant</td>
<td class="doxyParamItemDescription"><p>- The mapping of global value number to Constants.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NotSame</td>
<td class="doxyParamItemDescription"><p>- The set of global value numbers that do not have the same constant in each region.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if all Constants are the same in every use of a <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> in <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span> and false if not</p></dd>
</dl>


<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#ac77f2569521257316a0f374b9a2682c5">constantMatches</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a836d9cba6deced0bb1fa7333ce5afd3a">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/outlinablegroup/#a61915f6a6a382f51fd1a8bf3dd188c0c">OutlinableGroup::findSameConstants</a>.</p>

</div>
</div>

### constantMatches() {#ac77f2569521257316a0f374b9a2682c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; constantMatches (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, unsigned GVN, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; &amp; GVNToConstant)</td>
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

<p>Find whether <span class="doxyComputerOutput">V</span> matches the Constants previously found for the <span class="doxyComputerOutput">GVN</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">V</td>
<td class="doxyParamItemDescription"><p>- The value to check for consistency.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GVN</td>
<td class="doxyParamItemDescription"><p>- The global value number assigned to <span class="doxyComputerOutput">V</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GVNToConstant</td>
<td class="doxyParamItemDescription"><p>- The mapping of global value number to Constants.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> matches the <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> mapped to by V and false if it <span class="doxyComputerOutput">V</span> is a <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> but does not match.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>std::nullopt if <span class="doxyComputerOutput">V</span> is not a <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a>.</p></dd>
</dl>


<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>.</p>


<p>Referenced by <a href="#a52a09c04ddc4ec6d039f1f11f01d019e">collectRegionsConstants</a>.</p>

</div>
</div>

### createAndInsertBasicBlocks() {#a8120984c169f2ea17e785e7c6887702a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void createAndInsertBasicBlocks (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; OldMap, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; NewMap, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * ParentFunc, <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> BaseName)</td>
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

<p>Takes in a mapping, <span class="doxyComputerOutput">OldMap</span> of ConstantValues to BasicBlocks, sorts keys, before creating a basic block for each <span class="doxyComputerOutput">NewMap</span>, and inserting into the new block.</p>


<p>Each <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> is named with the scheme "&lt;basename&gt;_&lt;key_idx&gt;".</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OldMap</td>
<td class="doxyParamItemDescription"><p>[in] - The mapping to base the new mapping off of.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NewMap</td>
<td class="doxyParamItemDescription"><p>[out] - The output mapping using the keys of <span class="doxyComputerOutput">OldMap</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ParentFunc</td>
<td class="doxyParamItemDescription"><p>[in] - The function to put the new basic block in.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BaseName</td>
<td class="doxyParamItemDescription"><p>[in] - The start of the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> names to be appended to by an index value.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 2124 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="#a8ad786f21829d9e92d31cc0b80c53dbb">getSortedConstantKeys</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>.</p>


<p>Referenced by <a href="#ae86fef7fc5831c2514bff95bdf784d09">createSwitchStatement</a> and <a href="#a4e06ebf129ddfb3b33a64f1a456cfc24">fillOverallFunction</a>.</p>

</div>
</div>

### createSwitchStatement() {#ae86fef7fc5831c2514bff95bdf784d09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void createSwitchStatement (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/structs/outlinablegroup">OutlinableGroup</a> &amp; OG, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; EndBBs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &gt; &amp; OutputStoreBBs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create the switch statement for outlined function to differentiate between all the output blocks.</p>


<p>For the outlined section, determine if an outlined block already exists that matches the needed stores for the extracted section.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] M</td>
<td class="doxyParamItemDescription"><p>- The module we are outlining from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] OG</td>
<td class="doxyParamItemDescription"><p>- The group of regions to be outlined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] EndBBs</td>
<td class="doxyParamItemDescription"><p>- The final blocks of the extracted function.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] OutputStoreBBs</td>
<td class="doxyParamItemDescription"><p>- The existing output blocks.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 2150 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a62abc2475d09c01d583ba24a487898fd">llvm::SwitchInst::addCase</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#ac6baa801e4aea800984e760d5460662f">llvm::Function::arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a3c1416226bed5e92acb74aebe8e20f5a">llvm::SwitchInst::Create</a>, <a href="#a8120984c169f2ea17e785e7c6887702a">createAndInsertBasicBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a8a8e100a9a4c618756cbfc6286ae0e71">OutlinableGroup::EndBBs</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a8dd327a937563afdb08250abc43820b0">llvm::BasicBlock::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aecf2b6d6f052a378dd8f69fd1bb700b1">llvm::Function::getArg</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a3afc8c0c69b0c55edce3be13d5b7cc32">moveBBContents</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a95133d99b799f98e5c92dacc3028c621">OutlinableGroup::OutlinedFunction</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a53e3a8f28cb8e7a01334b7560467d9ea">OutlinableGroup::OutputGVNCombinations</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#ab9f68be0e2bcdf14f503f45edea63023">llvm::BasicBlock::size</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#a969eb757b1e43b455d4a8d0f603e695b">llvm::Function::size</a>.</p>

</div>
</div>

### encodePHINodeData() {#a652d50395284a0dec463c533709bc231}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">hash_code encodePHINodeData (<a href="#a0389cc3001a985e14dcff4067684ad70">PHINodeData</a> &amp; PND)</td>
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

<p>Encode <span class="doxyComputerOutput">PND</span> as an integer for easy lookup based on the argument location, the parent <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> canonical numbering, and the canonical numbering of the values stored in the <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">PND</td>
<td class="doxyParamItemDescription"><p>- The data to hash.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The hash code of <span class="doxyComputerOutput">PND</span>.</p></dd>
</dl>


<p>Definition at line 1154 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#add71474638430694c84640146383fc44">llvm::hash_combine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af80edfc5e42059e045aa7bf7fe42bee3">llvm::hash_combine_range</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0e2e479cf4860dc8a00614e36ee3d5e9">llvm::hash_value</a>.</p>


<p>Referenced by <a href="#a1c7b2c4c8824cfb8d35c97f6923c3fe2">getGVNForPHINode</a>.</p>

</div>
</div>

### fillOverallFunction() {#a4e06ebf129ddfb3b33a64f1a456cfc24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void fillOverallFunction (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/structs/outlinablegroup">OutlinableGroup</a> &amp; CurrentGroup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &gt; &amp; OutputStoreBBs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &amp; FuncsToRemove, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; OutputMappings)</td>
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

<p>Fill the new function that will serve as the replacement function for all of the extracted regions of a certain structure from the first region in the list of regions.</p>


<p>Replace this first region's extracted function with the new overall function.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] M</td>
<td class="doxyParamItemDescription"><p>- The module we are outlining from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] CurrentGroup</td>
<td class="doxyParamItemDescription"><p>- The group of regions to be outlined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] OutputStoreBBs</td>
<td class="doxyParamItemDescription"><p>- The output blocks for each different set of stores needed for the different functions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] FuncsToRemove</td>
<td class="doxyParamItemDescription"><p>- Extracted functions to erase from module once outlining is complete.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] OutputMappings</td>
<td class="doxyParamItemDescription"><p>- Extracted functions to erase from module once outlining is complete.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 2243 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a01875e4204852069dd4b7938cab4140b">llvm::Function::addFnAttr</a>, <a href="#a57d54880afa1fb74833cc7c43ad33377">analyzeAndPruneOutputBlocks</a>, <a href="/web-llvm/docs/api/structs/llvm/outlinableregion/#a018669f7b1d6a21106f47398a087c30a">llvm::OutlinableRegion::Call</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a9f40e42226cee617c16cb1c447b115c5">llvm::BranchInst::Create</a>, <a href="#a8120984c169f2ea17e785e7c6887702a">createAndInsertBasicBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a8a8e100a9a4c618756cbfc6286ae0e71">OutlinableGroup::EndBBs</a>, <a href="/web-llvm/docs/api/structs/llvm/outlinableregion/#ad5dce467e0d3954ba812f2e9611810b4">llvm::OutlinableRegion::ExtractedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a7477aafbbe989ad35b96fac186d8e9fd">llvm::Function::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a1cf553641e8527095ae4c8ec88a2cd92">llvm::AttributeList::getFnAttrs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a4047976de351f78967fba27df7a6361f">moveFunctionData</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a95133d99b799f98e5c92dacc3028c621">OutlinableGroup::OutlinedFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/outlinableregion/#a262d2672038afdeba85e23a30ea4c22d">llvm::OutlinableRegion::OutputBlockNum</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a75bbc3b17e5b70e0e1fac394f26b5c11">OutlinableGroup::Regions</a>, <a href="#a96b5bd50d8e96b4c76ffc26508ce774d">replaceArgumentUses</a>, <a href="#a7e2cad7ab18db9a3c940afc609c223dc">replaceCalledFunction</a> and <a href="#ace02ac07a3f704ffd345301bff92e5a8">replaceConstants</a>.</p>

</div>
</div>

### findCanonNumsForPHI() {#a26b0639ceb3f28de2e6a283098c525b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void findCanonNumsForPHI (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN, <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Region, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; OutputMappings, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &gt; &amp; CanonNums, bool ReplacedWithOutlinedCall=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Find the canonical numbering for the incoming Values into the <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> <span class="doxyComputerOutput">PN</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">PN</td>
<td class="doxyParamItemDescription"><p>[in] - The <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> that we are finding the canonical numbers for.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/region"&gt;Region&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>[in] - The <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> containing <span class="doxyComputerOutput">PN</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OutputMappings</td>
<td class="doxyParamItemDescription"><p>[in] - The mapping of output values from outlined region to their original values.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CanonNums</td>
<td class="doxyParamItemDescription"><p>[out] - The canonical numbering for the incoming values to <span class="doxyComputerOutput">PN</span> paired with their incoming block.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReplacedWithOutlinedCall</td>
<td class="doxyParamItemDescription"><p>- A flag to use the extracted function call of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span> rather than the overall function's call.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1634 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ab0d72084e637eaecbbadd192d547ef8e">findOutputMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ac53e1aabdf64e91b8b325bcac250d8a9">llvm::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aca1fd00f3ab63ec8f0f1ccc2093a9f6d">llvm::PHINode::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aef51af4b490af6b3bf2dfbc8737a8f9f">llvm::PHINode::getNumIncomingValues</a>, <a href="#a202f8ebe30581a7e75bcedc9dee531af">getPassedArgumentAndAdjustArgumentLocation</a> and <a href="#ad69884d9bf751011f8f9049542bbbd01">getPassedArgumentInAlreadyOutlinedFunction</a>.</p>


<p>Referenced by <a href="#a556a77d9b9acf322358b2c4131986b13">findOrCreatePHIInBlock</a>.</p>

</div>
</div>

### findConstants() {#acda959f961048eba09125aba48d1142e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void findConstants (<a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt; &amp; NotSame, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; unsigned &gt; &amp; Inputs)</td>
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

<p>Find the constants that will need to be lifted into arguments as they are not the same in each instance of the region.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] C</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> containing the region we are analyzing.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] NotSame</td>
<td class="doxyParamItemDescription"><p>- The set of global value numbers that do not have a single <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> across all OutlinableRegions similar to <span class="doxyComputerOutput">C</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] Inputs</td>
<td class="doxyParamItemDescription"><p>- The list containing the global value numbers of the arguments needed for the region of code.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 778 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a48d81e3f58b8db143bc85763d25dbc7a">getCodeExtractorArguments</a>.</p>

</div>
</div>

### findCostForOutputBlocks() {#a8b12ae89227758cb5684cc7cf25a7f43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost findCostForOutputBlocks (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/structs/outlinablegroup">OutlinableGroup</a> &amp; CurrentGroup, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI)</td>
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

<p>Find the extra instructions needed to handle any output values for the region.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] M</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> to outline from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] CurrentGroup</td>
<td class="doxyParamItemDescription"><p>- The collection of OutlinableRegions to analyze.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068"&gt;TTI&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> used to collect information for new instruction costs.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the additional cost to handle the outputs.</p></dd>
</dl>


<p>Definition at line 2556 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba07aee43ffb66908a25c55c77ce4c0d05">llvm::CmpInst::BAD_ICMP_PREDICATE</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a8ef219d66e525d2c9fbb7f54e5869ad3">OutlinableGroup::BranchesToOutside</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ab4b0641c5ffeeb3249b4ce9bb98c1a2d">findOutputValueInRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#a93f165686cbc3ed0554ec8431f9c9b21">llvm::IRSimilarity::IRSimilarityCandidate::getBasicBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a53e3a8f28cb8e7a01334b7560467d9ea">OutlinableGroup::OutputGVNCombinations</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a75bbc3b17e5b70e0e1fac394f26b5c11">OutlinableGroup::Regions</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba737cfc93e5a2ff961677d57186167e7c">llvm::TargetTransformInfo::TCK_CodeSize</a>.</p>

</div>
</div>

### findDuplicateOutputBlock() {#af714eb55aced0ac27294c881d8be6ecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; findDuplicateOutputBlock (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; OutputBBs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &gt; &amp; OutputStoreBBs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>It is possible that there is a basic block that already performs the same stores.</p>


<p>This returns a duplicate block, if it exists</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OutputBBs</td>
<td class="doxyParamItemDescription"><p>[in] the blocks we are looking for a duplicate of.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OutputStoreBBs</td>
<td class="doxyParamItemDescription"><p>[in] The existing output blocks.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an optional value with the number output block if there is a match.</p></dd>
</dl>


<p>Definition at line 1967 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#ab9f68be0e2bcdf14f503f45edea63023">llvm::BasicBlock::size</a>.</p>


<p>Referenced by <a href="#a4fcb90c9c38b3381765a891d0a61c1ea">alignOutputBlockWithAggFunc</a>.</p>

</div>
</div>

### findExtractedInputToOverallInputMapping() {#a9148948069532c9a5e1b59e3668b8cc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void findExtractedInputToOverallInputMapping (<a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Region, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; unsigned &gt; &amp; InputGVNs, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; ArgInputs)</td>
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

<p>Look over the inputs and map each input argument to an argument in the overall function for the OutlinableRegions.</p>


<p>This creates a way to replace the arguments of the extracted function with the arguments of the new overall function.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/region"&gt;Region&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The region of code to be analyzed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] InputGVNs</td>
<td class="doxyParamItemDescription"><p>- The global value numbering of the input values collected.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] ArgInputs</td>
<td class="doxyParamItemDescription"><p>- The values of the arguments to the extracted function.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 934 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/outlinablegroup/#a25b29490419d6ea97ce7d79dc58f306d">OutlinableGroup::ArgumentTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#ac3c1798aada6da8b72185545e4944c25">OutlinableGroup::CanonicalNumberToAggArg</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#abb03e3b6c4fd937936a13afe4f60d291">llvm::SetVector&lt; T, Vector, Set, N &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a9fabb6e6f74e4ef23575f45ea098b827">OutlinableGroup::InputTypesSet</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#aeab6020692f93361cff45734711204fc">OutlinableGroup::NumAggregateInputs</a> and <a href="/web-llvm/docs/api/structs/outlinablegroup/#a0d093de2575838ee30b3fbce09a020ff">OutlinableGroup::SwiftErrorArgument</a>.</p>

</div>
</div>

### findExtractedOutputToOverallOutputMapping() {#a4eb66b98a828331ed6cb79ae82c0336f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void findExtractedOutputToOverallOutputMapping (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Region, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; Outputs)</td>
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

<p>Create a mapping of the output arguments for the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span> to the output arguments of the overall outlined function.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/region"&gt;Region&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The region of code to be analyzed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] Outputs</td>
<td class="doxyParamItemDescription"><p>- The values found by the code extractor.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1276 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="#a882dcfc2455d525e78a8bbf46863ace2">analyzeExitPHIsForOutputUses</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a25b29490419d6ea97ce7d79dc58f306d">OutlinableGroup::ArgumentTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>, <a href="#a1c7b2c4c8824cfb8d35c97f6923c3fe2">getGVNForPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#aeab6020692f93361cff45734711204fc">OutlinableGroup::NumAggregateInputs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>

</div>
</div>

### findOrCreatePHIBlock() {#af30ff2458bb283e423c1fc242a468579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * findOrCreatePHIBlock (<a href="/web-llvm/docs/api/structs/outlinablegroup">OutlinableGroup</a> &amp; Group, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RetVal)</td>
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

<p>Find or create a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> in the outlined function containing PhiBlocks for <span class="doxyComputerOutput">RetVal</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Group</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/structs/outlinablegroup">OutlinableGroup</a> containing the information about the overall outlined function.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RetVal</td>
<td class="doxyParamItemDescription"><p>- The return value or exit option that we are currently evaluating.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The found or newly created <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> to contain the needed PHINodes to be used as outputs.</p></dd>
</dl>


<p>Definition at line 1540 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a9f40e42226cee617c16cb1c447b115c5">llvm::BranchInst::Create</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a8a8e100a9a4c618756cbfc6286ae0e71">OutlinableGroup::EndBBs</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aa286a0f7f5d38488d593bb7ef0ba183e">llvm::BasicBlock::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#aa4ad3c4db3597f25f2fba7a690a68bc6">OutlinableGroup::PHIBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a96b5bd50d8e96b4c76ffc26508ce774d">replaceArgumentUses</a>.</p>

</div>
</div>

### findOrCreatePHIInBlock() {#a556a77d9b9acf322358b2c4131986b13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode * findOrCreatePHIInBlock (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> &amp; PN, <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Region, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * OverallPhiBlock, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; OutputMappings, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * &gt; &amp; UsedPHIs)</td>
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

<p>Find, or add <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> <span class="doxyComputerOutput">PN</span> to the combined <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> Block <span class="doxyComputerOutput">OverallPHIBlock</span> in order to condense the number of instructions added to the outlined function.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">PN</td>
<td class="doxyParamItemDescription"><p>[in] - The <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> that we are finding the canonical numbers for.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/region"&gt;Region&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>[in] - The <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> containing <span class="doxyComputerOutput">PN</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OverallPhiBlock</td>
<td class="doxyParamItemDescription"><p>[in] - The overall PHIBlock we are trying to find <span class="doxyComputerOutput">PN</span> in.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OutputMappings</td>
<td class="doxyParamItemDescription"><p>[in] - The mapping of output values from outlined region to their original values.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UsedPHIs</td>
<td class="doxyParamItemDescription"><p>[in, out] - The PHINodes in the block that have already been matched.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the newly found or created <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> in <span class="doxyComputerOutput">OverallPhiBlock</span>.</p></dd>
</dl>


<p>Definition at line 1678 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0a4d51e372293abe5e5f6dac133e80a6">llvm::Instruction::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="#a26b0639ceb3f28de2e6a283098c525b2">findCanonNumsForPHI</a>, <a href="#ab0d72084e637eaecbbadd192d547ef8e">findOutputMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aecf2b6d6f052a378dd8f69fd1bb700b1">llvm::Function::getArg</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ac53e1aabdf64e91b8b325bcac250d8a9">llvm::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aca1fd00f3ab63ec8f0f1ccc2093a9f6d">llvm::PHINode::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aef51af4b490af6b3bf2dfbc8737a8f9f">llvm::PHINode::getNumIncomingValues</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a95133d99b799f98e5c92dacc3028c621">OutlinableGroup::OutlinedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a13da92d2694197fbcb5b95fd94e7570d">llvm::BasicBlock::phis</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a75bbc3b17e5b70e0e1fac394f26b5c11">OutlinableGroup::Regions</a>, <a href="/web-llvm/docs/api/structs/llvm/outlinableregion/#aa6e8e852e322a0a5383c6f0fce17daa2">llvm::OutlinableRegion::RemappedArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a5ba57877c55dfdbe6e3bbfdacd9ef8c1">llvm::PHINode::setIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a88cdefb709309eddc6e5daca0be6a7b4">llvm::PHINode::setIncomingValue</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a96b5bd50d8e96b4c76ffc26508ce774d">replaceArgumentUses</a>.</p>

</div>
</div>

### findOutputMapping() {#ab0d72084e637eaecbbadd192d547ef8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * findOutputMapping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; OutputMappings, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Input)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> the <span class="doxyComputerOutput">OutputMappings</span> structure for value <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/input">Input</a></span>, if it exists it has been used as an output for outlining, and has been renamed, and we return the new value, otherwise, we return the same value.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OutputMappings</td>
<td class="doxyParamItemDescription"><p>[in] - The mapping of values to their renamed value after being used as an output for an outlined region.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/input"&gt;Input&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>[in] - The value to find the remapped value of, if it exists.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The remapped value if it has been renamed, and the same value if has not.</p></dd>
</dl>


<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>.</p>


<p>Referenced by <a href="#a26b0639ceb3f28de2e6a283098c525b2">findCanonNumsForPHI</a> and <a href="#a556a77d9b9acf322358b2c4131986b13">findOrCreatePHIInBlock</a>.</p>

</div>
</div>

### findOutputValueInRegion() {#ab4b0641c5ffeeb3249b4ce9bb98c1a2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * findOutputValueInRegion (<a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Region, unsigned OutputCanon)</td>
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

<p>For the <span class="doxyComputerOutput">OutputCanon</span> number passed in find the value represented by this canonical number.</p>


<p>If it is from a <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>, we pick the first incoming value and return that <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> instead.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/region"&gt;Region&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> to get the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OutputCanon</td>
<td class="doxyParamItemDescription"><p>- The canonical number to find the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> from.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> represented by a canonical number <span class="doxyComputerOutput">OutputCanon</span> in <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span>.</p></dd>
</dl>


<p>Definition at line 2504 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a704926b49e550b25585651aea32b389b">OutlinableGroup::PHINodeGVNToGVNs</a> and <a href="/web-llvm/docs/api/structs/outlinablegroup/#a72b89466c3b2fd45331e2c315e2c33e5">OutlinableGroup::PHINodeGVNTracker</a>.</p>


<p>Referenced by <a href="#a8b12ae89227758cb5684cc7cf25a7f43">findCostForOutputBlocks</a>.</p>

</div>
</div>

### getCodeExtractorArguments() {#a48d81e3f58b8db143bc85763d25dbc7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void getCodeExtractorArguments (<a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Region, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; unsigned &gt; &amp; InputGVNs, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt; &amp; NotSame, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; OutputMappings, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; ArgInputs, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; Outputs)</td>
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

<p>Find the input GVNs and the output values for a region of Instructions.</p>


<p>Using the code extractor, we collect the inputs to the extracted function.</p>


<p>The <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span> can be identified as needing to be ignored in this function. It should be checked whether it should be ignored after a call to this function.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/region"&gt;Region&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The region of code to be analyzed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] InputGVNs</td>
<td class="doxyParamItemDescription"><p>- The global value numbers for the extracted arguments.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] NotSame</td>
<td class="doxyParamItemDescription"><p>- The global value numbers in the region that do not have the same constant value in the regions structurally similar to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] OutputMappings</td>
<td class="doxyParamItemDescription"><p>- The mapping of values that have been replaced by a new output value after extraction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] ArgInputs</td>
<td class="doxyParamItemDescription"><p>- The values of the inputs to the extracted function.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] Outputs</td>
<td class="doxyParamItemDescription"><p>- The set of values extracted by the <a href="/web-llvm/docs/api/classes/llvm/codeextractor">CodeExtractor</a> as outputs.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 863 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#acda959f961048eba09125aba48d1142e">findConstants</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a0c7d0dae14eb8a5916fff9f72d8b46d2">llvm::SetVector&lt; T, Vector, Set, N &gt;::getArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#a7ed9c79ac80ed5996c7e241814302eab">llvm::RegionBase&lt; Tr &gt;::getParent</a>, <a href="#a9165dd298666d75ed2e5be7d5d8b50e5">mapInputsToGVNs</a>, <a href="#a09e9f16b4a1aaf539000b95bf5442155">remapExtractedInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>.</p>

</div>
</div>

### getGVNForPHINode() {#a1c7b2c4c8824cfb8d35c97f6923c3fe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; getGVNForPHINode (<a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Region, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; Blocks, unsigned AggArgIdx)</td>
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

<p>Create a special GVN for PHINodes that will be used outside of the region.</p>


<p>We create a hash code based on the Canonical number of the parent <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>, the canonical numbering of the values stored in the <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> and the aggregate argument location. This is used to find whether this <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> type has been given a canonical numbering already. If not, we assign it a value and store it for later use. The value is returned to identify different output schemes for the set of regions.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/region"&gt;Region&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The region that <span class="doxyComputerOutput">PN</span> is an output for.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PN</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> we are analyzing.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Blocks</td>
<td class="doxyParamItemDescription"><p>- The blocks for the region we are analyzing.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AggArgIdx</td>
<td class="doxyParamItemDescription"><p>- The argument <span class="doxyComputerOutput">PN</span> will be stored into.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An optional holding the assigned canonical number, or std::nullopt if there is some attribute of the <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> blocking it from being used.</p></dd>
</dl>


<p>Definition at line 1174 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="#a652d50395284a0dec463c533709bc231">encodePHINodeData</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#ae6b404a6e77e0349378afa8ae7ce0e4a">llvm::IRSimilarity::IRSimilarityCandidate::getCanonicalNum</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#a3ffe65f27fa3355ffd96fbcd0bb1cbb9">llvm::IRSimilarity::IRSimilarityCandidate::getGVN</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ac53e1aabdf64e91b8b325bcac250d8a9">llvm::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aca1fd00f3ab63ec8f0f1ccc2093a9f6d">llvm::PHINode::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aef51af4b490af6b3bf2dfbc8737a8f9f">llvm::PHINode::getNumIncomingValues</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#ae22d915fa9ab51e40345773c663ebdeb">llvm::IRSimilarity::IRSimilarityCandidate::getStartBB</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a78f1513d0fadc0e72c1c7373c2003666">OutlinableGroup::GVNsToPHINodeGVN</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a704926b49e550b25585651aea32b389b">OutlinableGroup::PHINodeGVNToGVNs</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a72b89466c3b2fd45331e2c315e2c33e5">OutlinableGroup::PHINodeGVNTracker</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a4eb66b98a828331ed6cb79ae82c0336f">findExtractedOutputToOverallOutputMapping</a>.</p>

</div>
</div>

### getPassedArgumentAndAdjustArgumentLocation() {#a202f8ebe30581a7e75bcedc9dee531af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * getPassedArgumentAndAdjustArgumentLocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Region)</td>
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

<p>For the function call now representing the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span>, find the passed value to that call that represents <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> <span class="doxyComputerOutput">A</span> at the call location if the call has only been replaced by the call to the aggregate function.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">A</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> to get the passed value for.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/region"&gt;Region&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The extracted <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> corresponding to the outlined function.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> representing <span class="doxyComputerOutput">A</span> at the call site.</p></dd>
</dl>


<p>Definition at line 1609 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>


<p>Referenced by <a href="#a26b0639ceb3f28de2e6a283098c525b2">findCanonNumsForPHI</a>.</p>

</div>
</div>

### getPassedArgumentInAlreadyOutlinedFunction() {#ad69884d9bf751011f8f9049542bbbd01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * getPassedArgumentInAlreadyOutlinedFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Region)</td>
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

<p>For the function call now representing the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span>, find the passed value to that call that represents <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> <span class="doxyComputerOutput">A</span> at the call location if the call has already been replaced with a call to the overall, aggregate function.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">A</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> to get the passed value for.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/region"&gt;Region&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The extracted <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> corresponding to the outlined function.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> representing <span class="doxyComputerOutput">A</span> at the call site.</p></dd>
</dl>


<p>Definition at line 1593 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>


<p>Referenced by <a href="#a26b0639ceb3f28de2e6a283098c525b2">findCanonNumsForPHI</a>.</p>

</div>
</div>

### getSortedConstantKeys() {#a8ad786f21829d9e92d31cc0b80c53dbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void getSortedConstantKeys (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; SortedKeys, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; Map)</td>
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

<p>A function to sort the keys of <span class="doxyComputerOutput">Map</span>, which must be a mapping of constant values to basic blocks and return it in <span class="doxyComputerOutput">SortedKeys</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">SortedKeys</td>
<td class="doxyParamItemDescription"><p>- The vector the keys will be return in and sorted.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Map</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> containing keys to sort.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a31e8da5adf63afd38b4ab94bca823150">llvm::ConstantInt::getLimitedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>.</p>


<p>Referenced by <a href="#a8120984c169f2ea17e785e7c6887702a">createAndInsertBasicBlocks</a>.</p>

</div>
</div>

### getSubprogramOrNull() {#aac5cfc936b6963f4e848982328d39e8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DISubprogram * getSubprogramOrNull (<a href="/web-llvm/docs/api/structs/outlinablegroup">OutlinableGroup</a> &amp; Group)</td>
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

<p>Get the subprogram if it exists for one of the outlined regions.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] Group</td>
<td class="doxyParamItemDescription"><p>- The set of regions to find a subprogram for.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the subprogram if it exists, or nullptr.</p></dd>
</dl>


<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/outlinableregion/#a018669f7b1d6a21106f47398a087c30a">llvm::OutlinableRegion::Call</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a> and <a href="/web-llvm/docs/api/structs/outlinablegroup/#a75bbc3b17e5b70e0e1fac394f26b5c11">OutlinableGroup::Regions</a>.</p>

</div>
</div>

### mapInputsToGVNs() {#a9165dd298666d75ed2e5be7d5d8b50e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void mapInputsToGVNs (<a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; CurrentInputs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; OutputMappings, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; unsigned &gt; &amp; EndInputNumbers)</td>
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

<p>Find the GVN for the inputs that have been found by the <a href="/web-llvm/docs/api/classes/llvm/codeextractor">CodeExtractor</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] C</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> containing the region we are analyzing.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] CurrentInputs</td>
<td class="doxyParamItemDescription"><p>- The set of inputs found by the <a href="/web-llvm/docs/api/classes/llvm/codeextractor">CodeExtractor</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] OutputMappings</td>
<td class="doxyParamItemDescription"><p>- The mapping of values that have been replaced by a new output value.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] EndInputNumbers</td>
<td class="doxyParamItemDescription"><p>- The global value numbers for the extracted arguments.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 806 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>.</p>


<p>Referenced by <a href="#a48d81e3f58b8db143bc85763d25dbc7a">getCodeExtractorArguments</a>.</p>

</div>
</div>

### moveBBContents() {#a3afc8c0c69b0c55edce3be13d5b7cc32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void moveBBContents (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; SourceBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; TargetBB)</td>
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

<p>Move the contents of <span class="doxyComputerOutput">SourceBB</span> to before the last instruction of <span class="doxyComputerOutput">TargetBB</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">SourceBB</td>
<td class="doxyParamItemDescription"><p>- the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> to pull Instructions from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TargetBB</td>
<td class="doxyParamItemDescription"><p>- the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> to put <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> into.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#af29f89e91dfd0ae90950f0b1bf49798d">llvm::BasicBlock::splice</a>.</p>


<p>Referenced by <a href="#ae86fef7fc5831c2514bff95bdf784d09">createSwitchStatement</a> and <a href="/web-llvm/docs/api/structs/llvm/outlinableregion/#af5d7aa7988108e9377f154cf6a22f02b">llvm::OutlinableRegion::reattachCandidate</a>.</p>

</div>
</div>

### moveFunctionData() {#a4047976de351f78967fba27df7a6361f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void moveFunctionData (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Old, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; New, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; NewEnds)</td>
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

<p>Move each <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> in <span class="doxyComputerOutput">Old</span> to <span class="doxyComputerOutput">New</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] Old</td>
<td class="doxyParamItemDescription"><p>- The function to move the basic blocks from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] New</td>
<td class="doxyParamItemDescription"><p>- The function to move the basic blocks to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] NewEnds</td>
<td class="doxyParamItemDescription"><p>- The return blocks of the new overall function.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 706 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aecd4ed57fa6a20d048310d43f5c96da9">llvm::updateLoopMetadataDebugLocations</a>.</p>


<p>Referenced by <a href="#a4e06ebf129ddfb3b33a64f1a456cfc24">fillOverallFunction</a>.</p>

</div>
</div>

### nextIRInstructionDataMatchesNextInst() {#a3bc949e06e148a6d2879eb45ca164146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool nextIRInstructionDataMatchesNextInst (<a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> &amp; ID)</td>
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

<p>Checks that the next instruction in the InstructionDataList matches the next instruction in the module.</p>


<p>If they do not, there could be the possibility that extra code has been inserted, and we must ignore it.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed"&gt;ID&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> to check the next instruction of.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the InstructionDataList and actual instruction match.</p></dd>
</dl>


<p>Definition at line 2337 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>.</p>

</div>
</div>

### outputHasNonPHI() {#a84e785627d5ab55370b5fa402ad7193f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool outputHasNonPHI (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, unsigned PHILoc, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> &amp; PN, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 1 &gt; &amp; Exits, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; BlocksInRegion)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the <span class="doxyComputerOutput">V</span> has any uses outside of the region other than <span class="doxyComputerOutput">PN</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">V</td>
<td class="doxyParamItemDescription"><p>[in] - The value to check.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PHILoc</td>
<td class="doxyParamItemDescription"><p>[in] - The location in the <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> of <span class="doxyComputerOutput">V</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PN</td>
<td class="doxyParamItemDescription"><p>[in] - The <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> using <span class="doxyComputerOutput">V</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Exits</td>
<td class="doxyParamItemDescription"><p>[in] - The potential blocks we exit to from the outlined region.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BlocksInRegion</td>
<td class="doxyParamItemDescription"><p>[in] - The basic blocks contained in the region.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">V</span> has any use soutside its region other than <span class="doxyComputerOutput">PN</span>.</p></dd>
</dl>


<p>Definition at line 1036 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aef51af4b490af6b3bf2dfbc8737a8f9f">llvm::PHINode::getNumIncomingValues</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>.</p>


<p>Referenced by <a href="#a882dcfc2455d525e78a8bbf46863ace2">analyzeExitPHIsForOutputUses</a>.</p>

</div>
</div>

### remapExtractedInputs() {#a09e9f16b4a1aaf539000b95bf5442155}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void remapExtractedInputs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; ArgInputs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; OutputMappings, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; RemappedArgInputs)</td>
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

<p>Find the original value for the <span class="doxyComputerOutput">ArgInput</span> values if any one of them was replaced during a previous extraction.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] ArgInputs</td>
<td class="doxyParamItemDescription"><p>- The inputs to be extracted by the code extractor.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] OutputMappings</td>
<td class="doxyParamItemDescription"><p>- The mapping of values that have been replaced by a new output value.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] RemappedArgInputs</td>
<td class="doxyParamItemDescription"><p>- The remapped values according to <span class="doxyComputerOutput">OutputMappings</span> that will be extracted.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 832 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a> and <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>.</p>


<p>Referenced by <a href="#a48d81e3f58b8db143bc85763d25dbc7a">getCodeExtractorArguments</a>.</p>

</div>
</div>

### replaceArgumentUses() {#a96b5bd50d8e96b4c76ffc26508ce774d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void replaceArgumentUses (<a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Region, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; OutputBBs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; OutputMappings, bool FirstFunction=false)</td>
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
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/region"&gt;Region&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The region of extracted code to be changed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] OutputBBs</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> for the output stores for this region.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] FirstFunction</td>
<td class="doxyParamItemDescription"><p>- A flag to indicate whether we are using this function to define the overall outlined function for all the regions, or if we are operating on one of the following regions.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1800 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#a75479f44e7157d1a8592231addb67c9c">llvm::RegionBase&lt; Tr &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#ab0f09aefdf088f84a0bff7cba86454b4">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::deleteEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="#af30ff2458bb283e423c1fc242a468579">findOrCreatePHIBlock</a>, <a href="#a556a77d9b9acf322358b2c4131986b13">findOrCreatePHIInBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aecf2b6d6f052a378dd8f69fd1bb700b1">llvm::Function::getArg</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a406e4a6b7277aab7efd423ae30a9fb12">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::getDescendants</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a169f0c26ef46161741fdd120a806f853">llvm::Function::getEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/returninst/#a6c2dee0852138a5cb8a4fef5883db9ec">llvm::ReturnInst::getReturnValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a51145a3ae24ea73b3692a17088edea7b">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::insertEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#afcd9d2ea284c4d90541291ff9c47d332">llvm::Instruction::insertInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a95133d99b799f98e5c92dacc3028c621">OutlinableGroup::OutlinedFunction</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#aa4ad3c4db3597f25f2fba7a690a68bc6">OutlinableGroup::PHIBlocks</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a75bbc3b17e5b70e0e1fac394f26b5c11">OutlinableGroup::Regions</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a5fa9b8e1842b354f64c1ba6be0a4a17f">llvm::User::setOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a46db903db2484e1ef5062d094d6b0854">llvm::Value::user_back</a>.</p>


<p>Referenced by <a href="#a4e06ebf129ddfb3b33a64f1a456cfc24">fillOverallFunction</a>.</p>

</div>
</div>

### replaceCalledFunction() {#a7e2cad7ab18db9a3c940afc609c223dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * replaceCalledFunction (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Region)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace the extracted function in the <a href="/web-llvm/docs/api/classes/llvm/region">Region</a> with a call to the overall function constructed from the deduplicated similar regions, replacing and remapping the values passed to the extracted function as arguments to the new arguments of the overall function.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] M</td>
<td class="doxyParamItemDescription"><p>- The module to outline from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/region"&gt;Region&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The regions of extracted code to be replaced with a new function.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a call instruction with the replaced function.</p></dd>
</dl>


<p>Definition at line 1429 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#ac6baa801e4aea800984e760d5460662f">llvm::Function::arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#a75479f44e7157d1a8592231addb67c9c">llvm::RegionBase&lt; Tr &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#aa04721251be00370fbde6d21f47fed1a">llvm::CallInst::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#a9b0ebfeb3f47f1ad763e5b184dcb4e03">llvm::RegionBase&lt; Tr &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpointernull/#a96f5c85e4022e369266541b2db3fda69">llvm::ConstantPointerNull::get</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aecf2b6d6f052a378dd8f69fd1bb700b1">llvm::Function::getArg</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a21075305f0e463b24aafc2fb99514ace">llvm::Function::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a95133d99b799f98e5c92dacc3028c621">OutlinableGroup::OutlinedFunction</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a53e3a8f28cb8e7a01334b7560467d9ea">OutlinableGroup::OutputGVNCombinations</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a> and <a href="/web-llvm/docs/api/structs/outlinablegroup/#a0d093de2575838ee30b3fbce09a020ff">OutlinableGroup::SwiftErrorArgument</a>.</p>


<p>Referenced by <a href="#a4e06ebf129ddfb3b33a64f1a456cfc24">fillOverallFunction</a>.</p>

</div>
</div>

### replaceConstants() {#ace02ac07a3f704ffd345301bff92e5a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void replaceConstants (<a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Region)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Within an extracted function, replace the constants that need to be lifted into arguments with the actual argument.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/region"&gt;Region&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>[in] - The region of extracted code to be changed.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1934 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aecf2b6d6f052a378dd8f69fd1bb700b1">llvm::Function::getArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/outlinablegroup/#a95133d99b799f98e5c92dacc3028c621">OutlinableGroup::OutlinedFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a7e8dad1701aa6445be4a29f654b0473c">llvm::Value::replaceUsesWithIf</a>.</p>


<p>Referenced by <a href="#a4e06ebf129ddfb3b33a64f1a456cfc24">fillOverallFunction</a>.</p>

</div>
</div>

### replaceTargetsFromPHINode() {#a8e5c4577c64728c435eca5f4f7e163ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void replaceTargetsFromPHINode (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * PHIBlock, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Find, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Replace, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; Included)</td>
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

<p>Rewrite the BranchInsts in the incoming blocks to <span class="doxyComputerOutput">PHIBlock</span> that are found in <span class="doxyComputerOutput">Included</span> to branch to <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> <span class="doxyComputerOutput">Replace</span> if they currently branch to the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> <span class="doxyComputerOutput">Find</span>.</p>


<p>This is used to fix up the incoming basic blocks when PHINodes are included in outlined regions.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">PHIBlock</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> containing the PHINodes that need to be checked.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Find</td>
<td class="doxyParamItemDescription"><p>- The successor block to be replaced.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Replace</td>
<td class="doxyParamItemDescription"><p>- The new succesor block to branch to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Included</td>
<td class="doxyParamItemDescription"><p>- The set of blocks about to be outlined.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#a08e140d603b53c440c54cffc85131c8f">Find</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a96b8f11f6f21ca0321294669dab83b35">llvm::BranchInst::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aa05da2b94b366573d1651d5b163c521e">llvm::BranchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a13da92d2694197fbcb5b95fd94e7570d">llvm::BasicBlock::phis</a> and <a href="/web-llvm/docs/api/classes/llvm/branchinst/#adc5e7f9c460c68455e826783d77f9a99">llvm::BranchInst::setSuccessor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/outlinableregion/#af5d7aa7988108e9377f154cf6a22f02b">llvm::OutlinableRegion::reattachCandidate</a> and <a href="/web-llvm/docs/api/structs/llvm/outlinableregion/#a761b3c02cd196cb5f6fb019bcd86866e">llvm::OutlinableRegion::splitCandidate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### EnableLinkOnceODRIROutlining {#a415af6f4421aa68820b3279b48acd928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableLinkOnceODRIROutlining("enable-linkonceodr-ir-outlining", cl::Hidden, cl::desc("Enable the IR outliner on linkonceodr functions"), cl::init(false))</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/iroutliner/#adc7588dad82317423eb5949ca4bac107">llvm::IROutliner::run</a>.</p>

</div>
</div>

### NoCostModel {#a2dfbf70cabc04c37f6f46b2c312b2506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; NoCostModel("ir-outlining-no-cost", cl::init(false), cl::ReallyHidden, cl::desc("Debug option to outline greedily, without restriction that " "calculated benefit outweighs cost"))</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/iroutliner/#adc7588dad82317423eb5949ca4bac107">llvm::IROutliner::run</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"iroutliner"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
