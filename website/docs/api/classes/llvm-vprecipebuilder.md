---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vprecipebuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VPRecipeBuilder` Class Reference

<p>Helper class to create VPRecipies from IR instructions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPRecipeBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">Transforms/Vectorize/VPRecipeBuilder.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd211a51adf7aef33cfa49ee55d62a41">EdgeMaskCacheTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt;, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When we if-convert we need to create edge masks. <a href="#acd211a51adf7aef33cfa49ee55d62a41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af471aecea0d388416897d4986f36fcf9">BlockMaskCacheTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt;</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc4659f1aee78e49f4e81af4eacaad23">VPRecipeBuilder</a> (VPlan &amp;Plan, Loop *OrigLoop, const TargetLibraryInfo *TLI, const TargetTransformInfo *TTI, LoopVectorizationLegality *Legal, LoopVectorizationCostModel &amp;CM, PredicatedScalarEvolution &amp;PSE, VPBuilder &amp;Builder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a830fac639095604081943918ff84f703">getScalingForReduction</a> (const Instruction *ExitInst)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dc41af84f49f4b418bddf15547755af">collectScaledReductions</a> (VFRange &amp;Range)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find all possible partial reductions in the loop and track all of those that are valid so recipes can be formed later. <a href="#a8dc41af84f49f4b418bddf15547755af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a760fb390c24b907500c0a181fada9590">tryToCreateWidenRecipe</a> (Instruction *Instr, ArrayRef&lt; VPValue * &gt; Operands, VFRange &amp;Range, VPBasicBlock *VPBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create and return a widened recipe for <span class="doxyComputerOutput">I</span> if one can be created within the given VF <span class="doxyComputerOutput">Range</span>. <a href="#a760fb390c24b907500c0a181fada9590">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06a097fb3e3b640d70709b4770408024">tryToCreatePartialReduction</a> (Instruction *Reduction, ArrayRef&lt; VPValue * &gt; Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create and return a partial reduction recipe for a reduction instruction along with binary operation and reduction phi operands. <a href="#a06a097fb3e3b640d70709b4770408024">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a919404e870cee5ce3eea6e0cfb4238d4">setRecipe</a> (Instruction *I, VPRecipeBase *R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the recipe created for given ingredient. <a href="#a919404e870cee5ce3eea6e0cfb4238d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a826173bded23a3839e30074a98ad34a1">createHeaderMask</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the mask for the vector loop header block. <a href="#a826173bded23a3839e30074a98ad34a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a4bd8661b898e837b18df553e937311">createBlockInMask</a> (BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper function that computes the predicate of the block BB, assuming that the header block of the loop is set to True or the loop mask when tail folding. <a href="#a8a4bd8661b898e837b18df553e937311">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38a607d72d35cad5060b4cd7b5934bb5">getBlockInMask</a> (BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <em>entry</em> mask for the block <span class="doxyComputerOutput">BB</span>. <a href="#a38a607d72d35cad5060b4cd7b5934bb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e7e2adb0e2bd1c35df6aee471fc1db7">createSwitchEdgeMasks</a> (SwitchInst *SI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an edge mask for every destination of cases and/or default. <a href="#a2e7e2adb0e2bd1c35df6aee471fc1db7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0775987674a0fc922481db1966a5fdf5">createEdgeMask</a> (BasicBlock *Src, BasicBlock *Dst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper function that computes the predicate of the edge between SRC and DST. <a href="#a0775987674a0fc922481db1966a5fdf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a24061cba79c1c33396b71076a7379e">getEdgeMask</a> (BasicBlock *Src, BasicBlock *Dst) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper that returns the previously computed predicate of the edge between SRC and DST. <a href="#a4a24061cba79c1c33396b71076a7379e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5f874dc688e86699e648825bfcbf495">getRecipe</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the recipe created for given ingredient. <a href="#af5f874dc688e86699e648825bfcbf495">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe">VPReplicateRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c36c7d44a38145e7c72340d1b0e34d8">handleReplication</a> (Instruction *I, VFRange &amp;Range)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a VPReplicationRecipe for <span class="doxyComputerOutput">I</span>. <a href="#a2c36c7d44a38145e7c72340d1b0e34d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d8fbabf45554d7d598dc8eb4eca41cf">fixHeaderPhis</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the incoming values from the backedge to reduction &amp; first-order recurrence cross-iteration phis. <a href="#a6d8fbabf45554d7d598dc8eb4eca41cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mapped-iterator">mapped_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *, std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *(<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *)&gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a537d8b3b5160caeb94b20a21a9f6dcff">mapToVPValues</a> (User::op_range Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a range mapping the values of the range <span class="doxyComputerOutput">Operands</span> to their corresponding VPValues. <a href="#a537d8b3b5160caeb94b20a21a9f6dcff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7951985b28c0786b4ca50f061172ff22">getVPValueOrAddLiveIn</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea89a3a2a84acc89687e9538fea93436">shouldWiden</a> (Instruction *I, VFRange &amp;Range) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">I</span> can be widened at the start of <span class="doxyComputerOutput">Range</span> and possibly decrease the range such that the returned value holds for the entire <span class="doxyComputerOutput">Range</span>. <a href="#aea89a3a2a84acc89687e9538fea93436">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe">VPWidenMemoryRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae81657b7392dfe7784c06e6d19d8aeb0">tryToWidenMemory</a> (Instruction *I, ArrayRef&lt; VPValue * &gt; Operands, VFRange &amp;Range)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the load or store instruction <span class="doxyComputerOutput">I</span> should widened for <span class="doxyComputerOutput">Range.Start</span> and potentially masked. <a href="#ae81657b7392dfe7784c06e6d19d8aeb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpheaderphirecipe">VPHeaderPHIRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0a173d4291530cbbf7756fc10d17570">tryToOptimizeInductionPHI</a> (PHINode *Phi, ArrayRef&lt; VPValue * &gt; Operands, VFRange &amp;Range)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if an induction recipe should be constructed for <span class="doxyComputerOutput">Phi</span>. <a href="#ac0a173d4291530cbbf7756fc10d17570">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe">VPWidenIntOrFpInductionRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5604ea1499455510762c5132ba979515">tryToOptimizeInductionTruncate</a> (TruncInst *I, ArrayRef&lt; VPValue * &gt; Operands, VFRange &amp;Range)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize the special case where the operand of <span class="doxyComputerOutput">I</span> is a constant integer induction variable. <a href="#a5604ea1499455510762c5132ba979515">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpblendrecipe">VPBlendRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a2d4313651e2bd8795377b7bfed74d9">tryToBlend</a> (PHINode *Phi, ArrayRef&lt; VPValue * &gt; Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle non-loop phi nodes. <a href="#a9a2d4313651e2bd8795377b7bfed74d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpsingledefrecipe">VPSingleDefRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48d8b59c620cdc640d6ead4681386042">tryToWidenCall</a> (CallInst *CI, ArrayRef&lt; VPValue * &gt; Operands, VFRange &amp;Range)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle call instructions. <a href="#a48d8b59c620cdc640d6ead4681386042">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe">VPWidenRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a2c0611ceeca50ba03f8a0b69e6a489">tryToWiden</a> (Instruction *I, ArrayRef&lt; VPValue * &gt; Operands, VPBasicBlock *VPBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">I</span> has an opcode that can be widened and return a <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe">VPWidenRecipe</a> if it can. <a href="#a1a2c0611ceeca50ba03f8a0b69e6a489">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe">VPHistogramRecipe</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a496f0ec22c8acf89cd2a76c569625716">tryToWidenHistogram</a> (const HistogramInfo *HI, ArrayRef&lt; VPValue * &gt; Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Makes Histogram count operations safe for vectorization, by emitting a llvm.experimental.vector.histogram.add intrinsic in place of the Load + Add|Sub + Store operations that perform the histogram in the original scalar loop. <a href="#a496f0ec22c8acf89cd2a76c569625716">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eb3573da98ef0f60a92872c0d4ea578">getScaledReductions</a> (Instruction *PHI, Instruction *RdxExitInstr, VFRange &amp;Range, SmallVectorImpl&lt; std::pair&lt; PartialReductionChain, unsigned &gt; &gt; &amp;Chains)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examines reduction operations to see if the target can use a cheaper operation with a wider per-iteration input VF and narrower PHI VF. <a href="#a9eb3573da98ef0f60a92872c0d4ea578">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a838aff225f3387d5114d02f1abe6572e">Plan</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> new recipes are added to. <a href="#a838aff225f3387d5114d02f1abe6572e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac241dea3c4680ba644d04ca9e70819e5">OrigLoop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The loop that we evaluate. <a href="#ac241dea3c4680ba644d04ca9e70819e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3af8bcea18d89c9c14df6dea75f957ca">TLI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Library Info. <a href="#a3af8bcea18d89c9c14df6dea75f957ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace71e7cb485479d694e3d73ff93301e1">TTI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality">LoopVectorizationLegality</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac87f0430d9c153ab92c2a257b665614e">Legal</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The legality analysis. <a href="#ac87f0430d9c153ab92c2a257b665614e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel">LoopVectorizationCostModel</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34d121710314af4c0efa458406d22cc2">CM</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The profitablity analysis. <a href="#a34d121710314af4c0efa458406d22cc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae939f954b2016e9d62df4f2440a477d7">PSE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbuilder">VPBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad727e271392ae366439e1818994fe688">Builder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">EdgeMaskCacheTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f147aaa8c5afa2b18247658215e502f">EdgeMaskCache</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">BlockMaskCacheTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af63b932ee669cd63f00ef3c08f4da7d1">BlockMaskCache</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8bae54b55bc54c0c645495e64d81393">Ingredient2Recipe</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpheaderphirecipe">VPHeaderPHIRecipe</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a281254c3022de84d28191f7474089baa">PhisToFix</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cross-iteration reduction &amp; first-order recurrence phis for which we need to add the incoming value from the backedge after all recipes have been created. <a href="#a281254c3022de84d28191f7474089baa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec506f08e07913840094222ce898bdd">ScaledReductionMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A mapping of partial reduction exit instructions to their scaling factor. <a href="#a1ec506f08e07913840094222ce898bdd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper class to create VPRecipies from IR instructions.</p>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BlockMaskCacheTy {#af471aecea0d388416897d4986f36fcf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::VPRecipeBuilder::BlockMaskCacheTy =  DenseMap&lt;BasicBlock *, VPValue *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>

</div>
</div>

### EdgeMaskCacheTy {#acd211a51adf7aef33cfa49ee55d62a41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::VPRecipeBuilder::EdgeMaskCacheTy = 
      DenseMap&lt;std::pair&lt;BasicBlock *, BasicBlock *&gt;, VPValue *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When we if-convert we need to create edge masks.</p>


<p>We have to cache values so that we don't end up with exponential recursion/IR. Note that if-conversion currently takes place during VPlan-construction, so these caches are only used at that stage.</p>


<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VPRecipeBuilder() {#afc4659f1aee78e49f4e81af4eacaad23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPRecipeBuilder::VPRecipeBuilder (<a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> &amp; Plan, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * OrigLoop, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality">LoopVectorizationLegality</a> * Legal, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel">LoopVectorizationCostModel</a> &amp; CM, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder">VPBuilder</a> &amp; Builder)</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### collectScaledReductions() {#a8dc41af84f49f4b418bddf15547755af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPRecipeBuilder::collectScaledReductions (<a href="/web-llvm/docs/api/structs/llvm/vfrange">VFRange</a> &amp; Range)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find all possible partial reductions in the loop and track all of those that are valid so recipes can be formed later.</p>

<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8687 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a94d23373106467003722f7d6c17b1528">llvm::SmallVectorImpl&lt; T &gt;::insert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

### createBlockInMask() {#a8a4bd8661b898e837b18df553e937311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPRecipeBuilder::createBlockInMask (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A helper function that computes the predicate of the block BB, assuming that the header block of the loop is set to True or the loop mask when tail folding.</p>

<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8218 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0775987674a0fc922481db1966a5fdf5">createEdgeMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3e549d97549636a7f08779d5cd98540">llvm::pred_begin</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2103c335fa6ab933312c3871c82b0106">llvm::pred_end</a>.</p>

</div>
</div>

### createEdgeMask() {#a0775987674a0fc922481db1966a5fdf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * VPRecipeBuilder::createEdgeMask (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Src, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A helper function that computes the predicate of the edge between SRC and DST.</p>

<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8124 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2e7e2adb0e2bd1c35df6aee471fc1db7">createSwitchEdgeMasks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a38a607d72d35cad5060b4cd7b5934bb5">getBlockInMask</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aebd4af5642453ce3169094f08dd3d7b8">llvm::BranchInst::getCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aa05da2b94b366573d1651d5b163c521e">llvm::BranchInst::getSuccessor</a>, <a href="#a7951985b28c0786b4ca50f061172ff22">getVPValueOrAddLiveIn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a7e4be8b16fbd68c9045a388904044e01">llvm::BranchInst::isConditional</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>.</p>


<p>Referenced by <a href="#a8a4bd8661b898e837b18df553e937311">createBlockInMask</a>.</p>

</div>
</div>

### createHeaderMask() {#a826173bded23a3839e30074a98ad34a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPRecipeBuilder::createHeaderMask ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create the mask for the vector loop header block.</p>

<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8183 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad928235da3a32b50ba65140da09daf5d">llvm::VPBlockBase::getEntryBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a72533c6b54501809628b9daee79b9d18">llvm::VPBasicBlock::getFirstNonPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#adfdd504b078cce3b90e7c5cf1f5164db">llvm::VPBasicBlock::insert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>.</p>

</div>
</div>

### createSwitchEdgeMasks() {#a2e7e2adb0e2bd1c35df6aee471fc1db7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPRecipeBuilder::createSwitchEdgeMasks (<a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> * SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an edge mask for every destination of cases and/or default.</p>

<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8068 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="#a38a607d72d35cad5060b4cd7b5934bb5">getBlockInMask</a>, <a href="#a7951985b28c0786b4ca50f061172ff22">getVPValueOrAddLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="#a0775987674a0fc922481db1966a5fdf5">createEdgeMask</a>.</p>

</div>
</div>

### fixHeaderPhis() {#a6d8fbabf45554d7d598dc8eb4eca41cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPRecipeBuilder::fixHeaderPhis ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the incoming values from the backedge to reduction &amp; first-order recurrence cross-iteration phis.</p>

<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8613 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#af5f874dc688e86699e648825bfcbf495">getRecipe</a> and <a href="/web-llvm/docs/api/classes/llvm/vpdef/#a76a983b694720483a3dd9fe57314e39b">llvm::VPDef::getVPSingleValue</a>.</p>

</div>
</div>

### getBlockInMask() {#a38a607d72d35cad5060b4cd7b5934bb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * VPRecipeBuilder::getBlockInMask (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the <em>entry</em> mask for the block <span class="doxyComputerOutput">BB</span>.</p>

<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8210 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a0775987674a0fc922481db1966a5fdf5">createEdgeMask</a>, <a href="#a2e7e2adb0e2bd1c35df6aee471fc1db7">createSwitchEdgeMasks</a>, <a href="#a2c36c7d44a38145e7c72340d1b0e34d8">handleReplication</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ac2fcd61c17c94d7e9d10b24b718c812e">llvm::VPlanTransforms::handleUncountableEarlyExit</a>.</p>

</div>
</div>

### getEdgeMask() {#a4a24061cba79c1c33396b71076a7379e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * VPRecipeBuilder::getEdgeMask (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Src, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A helper that returns the previously computed predicate of the edge between SRC and DST.</p>

<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8172 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>.</p>

</div>
</div>

### getRecipe() {#af5f874dc688e86699e648825bfcbf495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPRecipeBase * llvm::VPRecipeBuilder::getRecipe (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Return the recipe created for given ingredient.</p>

<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a02106664ead4e0c4e755457dbac7f7b3">addScalarResumePhis</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aa88371693bc18186386b04e8c45a30e4">llvm::VPlanTransforms::createInterleaveGroups</a> and <a href="#a6d8fbabf45554d7d598dc8eb4eca41cf">fixHeaderPhis</a>.</p>

</div>
</div>

### getScalingForReduction() {#a830fac639095604081943918ff84f703}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; llvm::VPRecipeBuilder::getScalingForReduction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ExitInst)</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>


<p>Referenced by <a href="#a760fb390c24b907500c0a181fada9590">tryToCreateWidenRecipe</a>.</p>

</div>
</div>

### getVPValueOrAddLiveIn() {#a7951985b28c0786b4ca50f061172ff22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPValue * llvm::VPRecipeBuilder::getVPValueOrAddLiveIn (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a435b95efad7ea03299bd527b55b4708a">collectUsersInExitBlocks</a>, <a href="#a0775987674a0fc922481db1966a5fdf5">createEdgeMask</a>, <a href="#a2e7e2adb0e2bd1c35df6aee471fc1db7">createSwitchEdgeMasks</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ac2fcd61c17c94d7e9d10b24b718c812e">llvm::VPlanTransforms::handleUncountableEarlyExit</a> and <a href="#a537d8b3b5160caeb94b20a21a9f6dcff">mapToVPValues</a>.</p>

</div>
</div>

### handleReplication() {#a2c36c7d44a38145e7c72340d1b0e34d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPReplicateRecipe * VPRecipeBuilder::handleReplication (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/structs/llvm/vfrange">VFRange</a> &amp; Range)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build a VPReplicationRecipe for <span class="doxyComputerOutput">I</span>.</p>


<p>If it is predicated, add the mask as last operand. Range.End may be decreased to ensure same recipe behavior from <span class="doxyComputerOutput">Range.Start</span> to <span class="doxyComputerOutput">Range.End</span>.</p>


<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8623 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a38a607d72d35cad5060b4cd7b5934bb5">getBlockInMask</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#abe3531f2a6e2a86c1d35958794805785">llvm::LoopVectorizationPlanner::getDecisionAndClampRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a62766c75f88612ffa652342472e755f6">getIntrinsicID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a537d8b3b5160caeb94b20a21a9f6dcff">mapToVPValues</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

### mapToVPValues() {#a537d8b3b5160caeb94b20a21a9f6dcff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; mapped_iterator&lt; Use *, std::function&lt; VPValue *(Value *)&gt; &gt; &gt; VPRecipeBuilder::mapToVPValues (<a href="/web-llvm/docs/api/classes/llvm/user/#a917548288129e24325af275795e4622f">User::op_range</a> Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a range mapping the values of the range <span class="doxyComputerOutput">Operands</span> to their corresponding VPValues.</p>

<p>Declaration at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8061 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="#a7951985b28c0786b4ca50f061172ff22">getVPValueOrAddLiveIn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51c7cbd21e1104ee6841c18d7daa6edb">llvm::map_range</a>, <a href="#a537d8b3b5160caeb94b20a21a9f6dcff">mapToVPValues</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>


<p>Referenced by <a href="#a2c36c7d44a38145e7c72340d1b0e34d8">handleReplication</a> and <a href="#a537d8b3b5160caeb94b20a21a9f6dcff">mapToVPValues</a>.</p>

</div>
</div>

### setRecipe() {#a919404e870cee5ce3eea6e0cfb4238d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VPRecipeBuilder::setRecipe (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> * R)</td>
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

<p>Set the recipe created for given ingredient.</p>

<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### tryToCreatePartialReduction() {#a06a097fb3e3b640d70709b4770408024}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPRecipeBase * VPRecipeBuilder::tryToCreatePartialReduction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Reduction, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create and return a partial reduction recipe for a reduction instruction along with binary operation and reduction phi operands.</p>

<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8887 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#abb0a82cf9ab3cf0c256918c17512f987aa66d3974b6f2e3a542f896da144cd297">Accumulator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a175f1f53cc9c3619505ffbd13aca087f">Reduction</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#a760fb390c24b907500c0a181fada9590">tryToCreateWidenRecipe</a>.</p>

</div>
</div>

### tryToCreateWidenRecipe() {#a760fb390c24b907500c0a181fada9590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPRecipeBase * VPRecipeBuilder::tryToCreateWidenRecipe (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Instr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands, <a href="/web-llvm/docs/api/structs/llvm/vfrange">VFRange</a> &amp; Range, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> * VPBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create and return a widened recipe for <span class="doxyComputerOutput">I</span> if one can be created within the given VF <span class="doxyComputerOutput">Range</span>.</p>

<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8802 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#abe3531f2a6e2a86c1d35958794805785">llvm::LoopVectorizationPlanner::getDecisionAndClampRange</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a2b34d6e86d376d6857ccf7dd75d7dcf2">llvm::RecurrenceDescriptor::getLoopExitInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a61351428b7eb226cbad866ccf2382817">llvm::RecurrenceDescriptor::getRecurrenceStartValue</a>, <a href="#a830fac639095604081943918ff84f703">getScalingForReduction</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="#a06a097fb3e3b640d70709b4770408024">tryToCreatePartialReduction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getScaledReductions() {#a9eb3573da98ef0f60a92872c0d4ea578}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPRecipeBuilder::getScaledReductions (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * PHI, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * RdxExitInstr, <a href="/web-llvm/docs/api/structs/llvm/vfrange">VFRange</a> &amp; Range, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/structs/llvm/partialreductionchain">PartialReductionChain</a>, unsigned &gt; &gt; &amp; Chains)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Examines reduction operations to see if the target can use a cheaper operation with a wider per-iteration input VF and narrower PHI VF.</p>


<p>Each element within Chains is a pair with a struct containing reduction information and the scaling factor between the number of elements in the input and output. Recursively calls itself to identify chained scaled reductions. Returns true if this invocation added an entry to Chains, otherwise false. i.e. returns false in the case that a subcall adds an entry to Chains, but the top-level call does not.</p>


<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8722 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### shouldWiden() {#aea89a3a2a84acc89687e9538fea93436}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPRecipeBuilder::shouldWiden (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/structs/llvm/vfrange">VFRange</a> &amp; Range)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">I</span> can be widened at the start of <span class="doxyComputerOutput">Range</span> and possibly decrease the range such that the returned value holds for the entire <span class="doxyComputerOutput">Range</span>.</p>


<p>The function should not be called for memory instructions or calls.</p>


<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8506 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### tryToBlend() {#a9a2d4313651e2bd8795377b7bfed74d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBlendRecipe * VPRecipeBuilder::tryToBlend (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle non-loop phi nodes.</p>


<p>Return a new <a href="/web-llvm/docs/api/classes/llvm/vpblendrecipe">VPBlendRecipe</a> otherwise. Currently all such phi nodes are turned into a sequence of select instructions as the vectorizer currently performs full if-conversion.</p>


<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8390 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### tryToOptimizeInductionPHI() {#ac0a173d4291530cbbf7756fc10d17570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPHeaderPHIRecipe * VPRecipeBuilder::tryToOptimizeInductionPHI (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands, <a href="/web-llvm/docs/api/structs/llvm/vfrange">VFRange</a> &amp; Range)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if an induction recipe should be constructed for <span class="doxyComputerOutput">Phi</span>.</p>


<p>If so build and return it. If not, return null.</p>


<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8337 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### tryToOptimizeInductionTruncate() {#a5604ea1499455510762c5132ba979515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPWidenIntOrFpInductionRecipe * VPRecipeBuilder::tryToOptimizeInductionTruncate (<a href="/web-llvm/docs/api/classes/llvm/truncinst">TruncInst</a> * I, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands, <a href="/web-llvm/docs/api/structs/llvm/vfrange">VFRange</a> &amp; Range)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optimize the special case where the operand of <span class="doxyComputerOutput">I</span> is a constant integer induction variable.</p>

<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8362 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### tryToWiden() {#a1a2c0611ceeca50ba03f8a0b69e6a489}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPWidenRecipe * VPRecipeBuilder::tryToWiden (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> * VPBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">I</span> has an opcode that can be widened and return a <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe">VPWidenRecipe</a> if it can.</p>


<p>The function should only be called if the cost-model indicates that widening should be performed.</p>


<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8520 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### tryToWidenCall() {#a48d8b59c620cdc640d6ead4681386042}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPSingleDefRecipe * VPRecipeBuilder::tryToWidenCall (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands, <a href="/web-llvm/docs/api/structs/llvm/vfrange">VFRange</a> &amp; Range)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle call instructions.</p>


<p>If <span class="doxyComputerOutput">CI</span> can be widened for <span class="doxyComputerOutput">Range.Start</span>, return a new <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe">VPWidenCallRecipe</a> or <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe">VPWidenIntrinsicRecipe</a>. Range.End may be decreased to ensure same decision from <span class="doxyComputerOutput">Range.Start</span> to <span class="doxyComputerOutput">Range.End</span>.</p>


<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8416 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### tryToWidenHistogram() {#a496f0ec22c8acf89cd2a76c569625716}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPHistogramRecipe * VPRecipeBuilder::tryToWidenHistogram (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/histograminfo">HistogramInfo</a> * HI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Makes Histogram count operations safe for vectorization, by emitting a llvm.experimental.vector.histogram.add intrinsic in place of the Load + Add|Sub + Store operations that perform the histogram in the original scalar loop.</p>

<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8590 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### tryToWidenMemory() {#ae81657b7392dfe7784c06e6d19d8aeb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPWidenMemoryRecipe * VPRecipeBuilder::tryToWidenMemory (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands, <a href="/web-llvm/docs/api/structs/llvm/vfrange">VFRange</a> &amp; Range)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the load or store instruction <span class="doxyComputerOutput">I</span> should widened for <span class="doxyComputerOutput">Range.Start</span> and potentially masked.</p>


<p>Such instructions are handled by a recipe that takes an additional <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> for the mask.</p>


<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>, definition at line 8248 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BlockMaskCache {#af63b932ee669cd63f00ef3c08f4da7d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockMaskCacheTy llvm::VPRecipeBuilder::BlockMaskCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>

</div>
</div>

### Builder {#ad727e271392ae366439e1818994fe688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBuilder&amp; llvm::VPRecipeBuilder::Builder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>

</div>
</div>

### CM {#a34d121710314af4c0efa458406d22cc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopVectorizationCostModel&amp; llvm::VPRecipeBuilder::CM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The profitablity analysis.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>

</div>
</div>

### EdgeMaskCache {#a9f147aaa8c5afa2b18247658215e502f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeMaskCacheTy llvm::VPRecipeBuilder::EdgeMaskCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>

</div>
</div>

### Ingredient2Recipe {#af8bae54b55bc54c0c645495e64d81393}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Instruction *, VPRecipeBase *&gt; llvm::VPRecipeBuilder::Ingredient2Recipe</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>

</div>
</div>

### Legal {#ac87f0430d9c153ab92c2a257b665614e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopVectorizationLegality* llvm::VPRecipeBuilder::Legal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The legality analysis.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>

</div>
</div>

### OrigLoop {#ac241dea3c4680ba644d04ca9e70819e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* llvm::VPRecipeBuilder::OrigLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The loop that we evaluate.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>

</div>
</div>

### PhisToFix {#a281254c3022de84d28191f7474089baa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;VPHeaderPHIRecipe *, 4&gt; llvm::VPRecipeBuilder::PhisToFix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cross-iteration reduction &amp; first-order recurrence phis for which we need to add the incoming value from the backedge after all recipes have been created.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>

</div>
</div>

### Plan {#a838aff225f3387d5114d02f1abe6572e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPlan&amp; llvm::VPRecipeBuilder::Plan</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a> new recipes are added to.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>

</div>
</div>

### PSE {#ae939f954b2016e9d62df4f2440a477d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredicatedScalarEvolution&amp; llvm::VPRecipeBuilder::PSE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>

</div>
</div>

### ScaledReductionMap {#a1ec506f08e07913840094222ce898bdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Instruction *, unsigned&gt; llvm::VPRecipeBuilder::ScaledReductionMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A mapping of partial reduction exit instructions to their scaling factor.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>

</div>
</div>

### TLI {#a3af8bcea18d89c9c14df6dea75f957ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo* llvm::VPRecipeBuilder::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Library Info.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>

</div>
</div>

### TTI {#ace71e7cb485479d694e3d73ff93301e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetTransformInfo* llvm::VPRecipeBuilder::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vprecipebuilder-h">VPRecipeBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
