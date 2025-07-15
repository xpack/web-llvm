---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/iroutliner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IROutliner` Class Reference

<p>This class is a pass that identifies similarity in a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>, extracts instances of the similarity, and then consolidating the similar regions in an effort to reduce code size. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::IROutliner { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">llvm/Transforms/IPO/IROutliner.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dfb1b9b4add772840b18038df972d59">IROutliner</a> (function_ref&lt; TargetTransformInfo &amp;(Function &amp;)&gt; GTTI, function_ref&lt; IRSimilarityIdentifier &amp;(Module &amp;)&gt; GIRSI, function_ref&lt; OptimizationRemarkEmitter &amp;(Function &amp;)&gt; GORE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc7588dad82317423eb5949ca4bac107">run</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c8e647be2f0b5d2efe1241cc288e6fa">doOutline</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find repeated similar code sequences in <span class="doxyComputerOutput">M</span> and outline them into new Functions. <a href="#a2c8e647be2f0b5d2efe1241cc288e6fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac16fb7a3ce7c2dc2f6de30a354558937">isCompatibleWithAlreadyOutlinedCode</a> (const OutlinableRegion &amp;Region)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether an <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> is incompatible with code already outlined. <a href="#ac16fb7a3ce7c2dc2f6de30a354558937">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33eec4f23ed70e97a15aeab286c9a139">pruneIncompatibleRegions</a> (std::vector&lt; IRSimilarityCandidate &gt; &amp;CandidateVec, OutlinableGroup &amp;CurrentGroup)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove all the IRSimilarityCandidates from <span class="doxyComputerOutput">CandidateVec</span> that have instructions contained in a previously outlined region and put the remaining regions in <span class="doxyComputerOutput">CurrentGroup</span>. <a href="#a33eec4f23ed70e97a15aeab286c9a139">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabf3efc0bd728a533caeebeee17bff6b">createFunction</a> (Module &amp;M, OutlinableGroup &amp;CG, unsigned FunctionNameSuffix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the function based on the overall types found in the current regions being outlined. <a href="#aabf3efc0bd728a533caeebeee17bff6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7d3729a389ea80fc6da20686dc12049">findAddInputsOutputs</a> (Module &amp;M, OutlinableRegion &amp;Region, DenseSet&lt; unsigned &gt; &amp;NotSame)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify the needed extracted inputs in a section, and add to the overall function if needed. <a href="#ac7d3729a389ea80fc6da20686dc12049">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfe342420c2f533448508bf5c75a31c1">findBenefitFromAllRegions</a> (OutlinableGroup &amp;CurrentGroup)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the number of instructions that will be removed by extracting the OutlinableRegions in <span class="doxyComputerOutput">CurrentGroup</span>. <a href="#acfe342420c2f533448508bf5c75a31c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada668b50e24e19eb5489c84afd53c13c">findCostOutputReloads</a> (OutlinableGroup &amp;CurrentGroup)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the number of instructions that will be added by reloading arguments. <a href="#ada668b50e24e19eb5489c84afd53c13c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9667df89d348ad2b31d37699743fc694">findCostBenefit</a> (Module &amp;M, OutlinableGroup &amp;CurrentGroup)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the cost and the benefit of <span class="doxyComputerOutput">CurrentGroup</span> and save it back to <span class="doxyComputerOutput">CurrentGroup</span>. <a href="#a9667df89d348ad2b31d37699743fc694">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae72068274b82e22d746d4b039d2a842e">updateOutputMapping</a> (OutlinableRegion &amp;Region, ArrayRef&lt; Value * &gt; Outputs, LoadInst *LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the output mapping based on the load instruction, and the outputs of the extracted function. <a href="#ae72068274b82e22d746d4b039d2a842e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a364079371163c9d5daf4edad11f9357b">extractSection</a> (OutlinableRegion &amp;Region)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span> into its own function. <a href="#a364079371163c9d5daf4edad11f9357b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53a98d3c5abcb4f9ea22b1b688681da5">deduplicateExtractedSections</a> (Module &amp;M, OutlinableGroup &amp;CurrentGroup, std::vector&lt; Function * &gt; &amp;FuncsToRemove, unsigned &amp;OutlinedFunctionNum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the similarities found, and the extracted sections, create a single outlined function with appropriate output blocks as necessary. <a href="#a53a98d3c5abcb4f9ea22b1b688681da5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a717a443b3e21b0442a79b4677d2b0d5d">OutlineFromLinkODRs</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If true, enables us to outline from functions that have LinkOnceFromODR linkages. <a href="#a717a443b3e21b0442a79b4677d2b0d5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa875337f62c7fc51a5ec11eebf47f0df">CostModel</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If false, we do not worry if the cost is greater than the benefit. <a href="#aa875337f62c7fc51a5ec11eebf47f0df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af245aff2ce32c3502c60297f833938f8">Outlined</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of outlined Instructions, identified by their location in the sequential ordering of instructions in a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>. <a href="#af245aff2ce32c3502c60297f833938f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacb55c75e23073b0e5ca05a6d9addf2c">getTTI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> lambda for target specific information. <a href="#aacb55c75e23073b0e5ca05a6d9addf2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e197a45c8d9c6f5bcdf6b1bf8fef36c">OutputMappings</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A mapping from newly created reloaded output values to the original value. <a href="#a9e197a45c8d9c6f5bcdf6b1bf8fef36c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilarityidentifier">IRSimilarityIdentifier</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab85476e0fa1ff28fc071d308877a5569">getIRSI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilarityidentifier">IRSimilarityIdentifier</a> lambda to retrieve <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilarityidentifier">IRSimilarityIdentifier</a>. <a href="#ab85476e0fa1ff28fc071d308877a5569">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2681979717de9e17c318eb2b4ec30d7">getORE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The optimization remark emitter for the pass. <a href="#ae2681979717de9e17c318eb2b4ec30d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/codeextractor">CodeExtractor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d939a73571c6d16cb579c2f2d18331c">ExtractorAllocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The memory allocator used to allocate the CodeExtractors. <a href="#a7d939a73571c6d16cb579c2f2d18331c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a430ba6ec6814dc27841b18730191a783">RegionAllocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The memory allocator used to allocate the OutlinableRegions. <a href="#a430ba6ec6814dc27841b18730191a783">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabf5b8081c2017ad2aa57c333e256b1d">InstDataAllocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The memory allocator used to allocate new <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>. <a href="#aabf5b8081c2017ad2aa57c333e256b1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">InstructionAllowed</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a410fe16b0a243b46ba902cb9a5c9ad3e">InstructionClassifier</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/instvisitor">InstVisitor</a> used to exclude certain instructions from being outlined. <a href="#a410fe16b0a243b46ba902cb9a5c9ad3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class is a pass that identifies similarity in a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>, extracts instances of the similarity, and then consolidating the similar regions in an effort to reduce code size.</p>


<p>It uses the <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilarityidentifier">IRSimilarityIdentifier</a> pass to identify the similar regions of code, and then extracts the similar sections into a single function. See the above for an example as to how code is extracted and consolidated into a single function.</p>


<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IROutliner() {#a4dfb1b9b4add772840b18038df972d59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IROutliner::IROutliner (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GTTI, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilarityidentifier">IRSimilarityIdentifier</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;)&gt; GIRSI, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GORE)</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a1423601a8e4ec304e0756df4e761ebbb">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getEmptyKey</a> and <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a9571e26b946751eaf015a9b8dc508be9">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getTombstoneKey</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#adc7588dad82317423eb5949ca4bac107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IROutliner::run (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>, definition at line 3013 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a415af6f4421aa68820b3279b48acd928">EnableLinkOnceODRIROutlining</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a2dfbf70cabc04c37f6f46b2c312b2506">NoCostModel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createFunction() {#aabf3efc0bd728a533caeebeee17bff6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * IROutliner::createFunction (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/structs/outlinablegroup">OutlinableGroup</a> &amp; CG, unsigned FunctionNameSuffix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create the function based on the overall types found in the current regions being outlined.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">M</td>
<td class="doxyParamItemDescription"><p>- The module to outline from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] CG</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/structs/outlinablegroup">OutlinableGroup</a> for the regions to be outlined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] FunctionNameSuffix</td>
<td class="doxyParamItemDescription"><p>- How many functions have we previously created.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the newly created function.</p></dd>
</dl>


<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>, definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>

</div>
</div>

### deduplicateExtractedSections() {#a53a98d3c5abcb4f9ea22b1b688681da5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IROutliner::deduplicateExtractedSections (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/structs/outlinablegroup">OutlinableGroup</a> &amp; CurrentGroup, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &amp; FuncsToRemove, unsigned &amp; OutlinedFunctionNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For the similarities found, and the extracted sections, create a single outlined function with appropriate output blocks as necessary.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] M</td>
<td class="doxyParamItemDescription"><p>- The module to outline from</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] CurrentGroup</td>
<td class="doxyParamItemDescription"><p>- The set of extracted sections to consolidate.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] FuncsToRemove</td>
<td class="doxyParamItemDescription"><p>- List of functions to remove from the module after outlining is completed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] OutlinedFunctionNum</td>
<td class="doxyParamItemDescription"><p>- the number of new outlined functions.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>, definition at line 2292 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>

</div>
</div>

### doOutline() {#a2c8e647be2f0b5d2efe1241cc288e6fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned IROutliner::doOutline (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find repeated similar code sequences in <span class="doxyComputerOutput">M</span> and outline them into new Functions.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] M</td>
<td class="doxyParamItemDescription"><p>- The module to outline from.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The number of Functions created.</p></dd>
</dl>


<p>Declaration at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>, definition at line 2783 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>

</div>
</div>

### extractSection() {#a364079371163c9d5daf4edad11f9357b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IROutliner::extractSection (<a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Region)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a></span> into its own function.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/region"&gt;Region&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The region to be extracted into its own function.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if it was successfully outlined.</p></dd>
</dl>


<p>Declaration at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>, definition at line 2708 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>

</div>
</div>

### findAddInputsOutputs() {#ac7d3729a389ea80fc6da20686dc12049}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IROutliner::findAddInputsOutputs (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Region, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt; &amp; NotSame)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identify the needed extracted inputs in a section, and add to the overall function if needed.</p>


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
<td class="doxyParamItemDescription"><p>- The region to be extracted.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] NotSame</td>
<td class="doxyParamItemDescription"><p>- The global value numbers of the Values in the region that do not have the same <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> in each strucutrally similar region.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>, definition at line 1400 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>

</div>
</div>

### findBenefitFromAllRegions() {#acfe342420c2f533448508bf5c75a31c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost IROutliner::findBenefitFromAllRegions (<a href="/web-llvm/docs/api/structs/outlinablegroup">OutlinableGroup</a> &amp; CurrentGroup)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the number of instructions that will be removed by extracting the OutlinableRegions in <span class="doxyComputerOutput">CurrentGroup</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] CurrentGroup</td>
<td class="doxyParamItemDescription"><p>- The collection of OutlinableRegions to be analyzed.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the number of outlined instructions across all regions.</p></dd>
</dl>


<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>, definition at line 2482 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>

</div>
</div>

### findCostBenefit() {#a9667df89d348ad2b31d37699743fc694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IROutliner::findCostBenefit (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/structs/outlinablegroup">OutlinableGroup</a> &amp; CurrentGroup)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the cost and the benefit of <span class="doxyComputerOutput">CurrentGroup</span> and save it back to <span class="doxyComputerOutput">CurrentGroup</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] M</td>
<td class="doxyParamItemDescription"><p>- The module being analyzed</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] CurrentGroup</td>
<td class="doxyParamItemDescription"><p>- The overall outlined section</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>, definition at line 2629 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>

</div>
</div>

### findCostOutputReloads() {#ada668b50e24e19eb5489c84afd53c13c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost IROutliner::findCostOutputReloads (<a href="/web-llvm/docs/api/structs/outlinablegroup">OutlinableGroup</a> &amp; CurrentGroup)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the number of instructions that will be added by reloading arguments.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] CurrentGroup</td>
<td class="doxyParamItemDescription"><p>- The collection of OutlinableRegions to be analyzed.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the number of added reload instructions across all regions.</p></dd>
</dl>


<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>, definition at line 2526 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>

</div>
</div>

### isCompatibleWithAlreadyOutlinedCode() {#ac16fb7a3ce7c2dc2f6de30a354558937}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IROutliner::isCompatibleWithAlreadyOutlinedCode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Region)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether an <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> is incompatible with code already outlined.</p>


<p>OutlinableRegions are incomptaible when there are overlapping instructions, or code that has not been recorded has been added to the instructions.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/region"&gt;Region&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> to check for conflicts with already outlined code.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>whether the region can safely be outlined.</p></dd>
</dl>


<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>, definition at line 2360 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>

</div>
</div>

### pruneIncompatibleRegions() {#a33eec4f23ed70e97a15aeab286c9a139}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IROutliner::pruneIncompatibleRegions (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate">IRSimilarityCandidate</a> &gt; &amp; CandidateVec, <a href="/web-llvm/docs/api/structs/outlinablegroup">OutlinableGroup</a> &amp; CurrentGroup)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove all the IRSimilarityCandidates from <span class="doxyComputerOutput">CandidateVec</span> that have instructions contained in a previously outlined region and put the remaining regions in <span class="doxyComputerOutput">CurrentGroup</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] CandidateVec</td>
<td class="doxyParamItemDescription"><p>- List of similarity candidates for regions with the same similarity structure.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] CurrentGroup</td>
<td class="doxyParamItemDescription"><p>- Contains the potential sections to be outlined.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>, definition at line 2398 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>

</div>
</div>

### updateOutputMapping() {#ae72068274b82e22d746d4b039d2a842e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IROutliner::updateOutputMapping (<a href="/web-llvm/docs/api/structs/llvm/outlinableregion">OutlinableRegion</a> &amp; Region, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Outputs, <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the output mapping based on the load instruction, and the outputs of the extracted function.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/region"&gt;Region&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The region extracted</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Outputs</td>
<td class="doxyParamItemDescription"><p>- The outputs from the extracted function.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LI</td>
<td class="doxyParamItemDescription"><p>- The load instruction used to update the mapping.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>, definition at line 2676 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CostModel {#aa875337f62c7fc51a5ec11eebf47f0df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IROutliner::CostModel = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If false, we do not worry if the cost is greater than the benefit.</p>


<p>This is for debugging and testing, so that we can test small cases to ensure that the outlining is being done correctly.</p>


<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### ExtractorAllocator {#a7d939a73571c6d16cb579c2f2d18331c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;CodeExtractor&gt; llvm::IROutliner::ExtractorAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The memory allocator used to allocate the CodeExtractors.</p>

<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### getIRSI {#ab85476e0fa1ff28fc071d308877a5569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">function_ref&lt;IRSimilarityIdentifier &amp;(Module &amp;)&gt; llvm::IROutliner::getIRSI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilarityidentifier">IRSimilarityIdentifier</a> lambda to retrieve <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilarityidentifier">IRSimilarityIdentifier</a>.</p>

<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### getORE {#ae2681979717de9e17c318eb2b4ec30d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">function_ref&lt;OptimizationRemarkEmitter &amp;(Function &amp;)&gt; llvm::IROutliner::getORE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The optimization remark emitter for the pass.</p>

<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### getTTI {#aacb55c75e23073b0e5ca05a6d9addf2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">function_ref&lt;TargetTransformInfo &amp;(Function &amp;)&gt; llvm::IROutliner::getTTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> lambda for target specific information.</p>

<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### InstDataAllocator {#aabf5b8081c2017ad2aa57c333e256b1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;IRInstructionData&gt; llvm::IROutliner::InstDataAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The memory allocator used to allocate new <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata">IRInstructionData</a>.</p>

<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### InstructionClassifier {#a410fe16b0a243b46ba902cb9a5c9ad3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionAllowed llvm::IROutliner::InstructionClassifier</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A <a href="/web-llvm/docs/api/classes/llvm/instvisitor">InstVisitor</a> used to exclude certain instructions from being outlined.</p>

<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### Outlined {#af245aff2ce32c3502c60297f833938f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;unsigned&gt; llvm::IROutliner::Outlined</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of outlined Instructions, identified by their location in the sequential ordering of instructions in a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>.</p>

<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### OutlineFromLinkODRs {#a717a443b3e21b0442a79b4677d2b0d5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IROutliner::OutlineFromLinkODRs = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If true, enables us to outline from functions that have LinkOnceFromODR linkages.</p>

<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### OutputMappings {#a9e197a45c8d9c6f5bcdf6b1bf8fef36c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, Value *&gt; llvm::IROutliner::OutputMappings</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A mapping from newly created reloaded output values to the original value.</p>


<p>If an value is replace by an output from an outlined region, this maps that <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, back to its original <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>


<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

### RegionAllocator {#a430ba6ec6814dc27841b18730191a783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;OutlinableRegion&gt; llvm::IROutliner::RegionAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The memory allocator used to allocate the OutlinableRegions.</p>

<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/iroutliner-h">IROutliner.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp">IROutliner.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
