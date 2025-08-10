---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeextractor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CodeExtractor` Class

<p>Utility class for extracting code into a new function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CodeExtractor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">llvm/Transforms/Utils/CodeExtractor.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6271464228e166c13033f277a43493e">ValueSet</a> = <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a152c260d40a85ed5b0ef5f11f86ac3b4">CodeExtractor</a> (ArrayRef&lt; BasicBlock * &gt; BBs, DominatorTree *DT=nullptr, bool AggregateArgs=false, BlockFrequencyInfo *BFI=nullptr, BranchProbabilityInfo *BPI=nullptr, AssumptionCache *AC=nullptr, bool AllowVarArgs=false, bool AllowAlloca=false, BasicBlock *AllocationBlock=nullptr, std::string Suffix="", bool ArgsInZeroAddressSpace=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a code extractor for a sequence of blocks. <a href="#a152c260d40a85ed5b0ef5f11f86ac3b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8561c48aa0b397c37f9e071dad7df392">extractCodeRegion</a> (const CodeExtractorAnalysisCache &amp;CEAC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform the extraction, returning the new function. <a href="#a8561c48aa0b397c37f9e071dad7df392">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0645a37d60eb4946b1b73c517a96544">extractCodeRegion</a> (const CodeExtractorAnalysisCache &amp;CEAC, ValueSet &amp;Inputs, ValueSet &amp;Outputs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform the extraction, returning the new function and providing an interface to see what was categorized as inputs and outputs. <a href="#ac0645a37d60eb4946b1b73c517a96544">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3a4770e725305d3529cba8c6562c85a">isEligible</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether this code extractor is eligible. <a href="#ad3a4770e725305d3529cba8c6562c85a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4d4236fd0a481a0d93e159a9882fc53">findInputsOutputs</a> (ValueSet &amp;Inputs, ValueSet &amp;Outputs, const ValueSet &amp;Allocas, bool CollectGlobalInputs=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the set of input values and output values for the code. <a href="#ab4d4236fd0a481a0d93e159a9882fc53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9ce92095ff18cb2c607d5a3591703ca">isLegalToShrinkwrapLifetimeMarkers</a> (const CodeExtractorAnalysisCache &amp;CEAC, Instruction *AllocaAddr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if life time marker nodes can be hoisted/sunk into the outline region. <a href="#ae9ce92095ff18cb2c607d5a3591703ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a537993928c8af5b0d064fcd5ce1dec2f">findAllocas</a> (const CodeExtractorAnalysisCache &amp;CEAC, ValueSet &amp;SinkCands, ValueSet &amp;HoistCands, BasicBlock *&amp;ExitBlock) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the set of allocas whose life ranges are contained within the outlined region. <a href="#a537993928c8af5b0d064fcd5ce1dec2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19ce83f3f1fef433e2ba91a0b2a196a0">findOrCreateBlockForHoisting</a> (BasicBlock *CommonExitBlock)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find or create a block within the outline region for placing hoisted code. <a href="#a19ce83f3f1fef433e2ba91a0b2a196a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4d03968d09741d23f5b83e7a538f04f">excludeArgFromAggregate</a> (Value *Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Exclude a value from aggregate argument passing when extracting a code region, passing it instead as a scalar. <a href="#ad4d03968d09741d23f5b83e7a538f04f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">LifetimeMarkerInfo</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeb52d50b07b579d70ab4ec53afa368e">getLifetimeMarkers</a> (const CodeExtractorAnalysisCache &amp;CEAC, Instruction *Addr, BasicBlock *ExitBlock) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a350e0e6280f2dc10d5351df669b4da">computeExtractedFuncRetVals</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Updates the list of SwitchCases (corresponding to exit blocks) after changes of the control flow or the Blocks list. <a href="#a5a350e0e6280f2dc10d5351df669b4da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93d1fa599f74cec9c70aeb7c729b5d96">getSwitchType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type used for the return code of the extracted function to indicate which exit block to jump to. <a href="#a93d1fa599f74cec9c70aeb7c729b5d96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a088347482819a60fe80edbb565a64576">severSplitPHINodesOfEntry</a> (BasicBlock *&amp;Header)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>severSplitPHINodesOfEntry - If a PHI node has multiple inputs from outside of the region, we need to split the entry block of the region so that the PHI node is easier to deal with. <a href="#a088347482819a60fe80edbb565a64576">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bf7ad0e20b2a13d447806bd8a53a9d1">severSplitPHINodesOfExits</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>severSplitPHINodesOfExits - if PHI nodes in exit blocks have inputs from outlined region, we split these PHIs on two: one with inputs from region and other with remaining incoming blocks; then first PHIs are placed in outlined region. <a href="#a5bf7ad0e20b2a13d447806bd8a53a9d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50a00b19a935f0caee2d2780a657bf54">splitReturnBlocks</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5bbc2212ffdea8b5117834d6c0e36e8">moveCodeToFunction</a> (Function *newFunction)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78ead07dc9be9cd16a79317303faf46d">calculateNewCallTerminatorWeights</a> (BasicBlock *CodeReplacer, const DenseMap&lt; BasicBlock *, BlockFrequency &gt; &amp;ExitWeights, BranchProbabilityInfo *BPI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c08536df2601eaef5d6ea02e1cb1457">normalizeCFGForExtraction</a> (BasicBlock *&amp;header)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Normalizes the control flow of the extracted regions, such as ensuring that the extracted region does not contain a return instruction. <a href="#a1c08536df2601eaef5d6ea02e1cb1457">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79eb5c4fb0d6136e56f5936208291ed0">constructFunctionDeclaration</a> (const ValueSet &amp;inputs, const ValueSet &amp;outputs, BlockFrequency EntryFreq, const Twine &amp;Name, ValueSet &amp;StructValues, StructType *&amp;StructTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generates the function declaration for the function containing the extracted code. <a href="#a79eb5c4fb0d6136e56f5936208291ed0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe0a9415158260ff490f6e74da695fde">emitFunctionBody</a> (const ValueSet &amp;inputs, const ValueSet &amp;outputs, const ValueSet &amp;StructValues, Function *newFunction, StructType *StructArgTy, BasicBlock *header, const ValueSet &amp;SinkingCands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generates the code for the extracted function. <a href="#abe0a9415158260ff490f6e74da695fde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e494a515f6c5ab54dfb67e2043f0f91">emitReplacerCall</a> (const ValueSet &amp;inputs, const ValueSet &amp;outputs, const ValueSet &amp;StructValues, Function *newFunction, StructType *StructArgTy, Function *oldFunction, BasicBlock *ReplIP, BlockFrequency EntryFreq, ArrayRef&lt; Value * &gt; LifetimesStart, std::vector&lt; Value * &gt; &amp;Reloads)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generates a Basic Block that calls the extracted function. <a href="#a3e494a515f6c5ab54dfb67e2043f0f91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f6b5ff66dc35723796354a00fc478bf">insertReplacerCall</a> (Function *oldFunction, BasicBlock *header, BasicBlock *codeReplacer, const ValueSet &amp;outputs, ArrayRef&lt; Value * &gt; Reloads, const DenseMap&lt; BasicBlock *, BlockFrequency &gt; &amp;ExitWeights)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Connects the basic block containing the call to the extracted function into the original function's control flow. <a href="#a4f6b5ff66dc35723796354a00fc478bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78d11c3a06b2deb9ca067d4ee9e99591">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ce8741a067c95c562937385a08c5ce9">AggregateArgs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a572c77244af879aa55fcda67edfe8408">BFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0835502a4ef2f33dfc6eed41a6a9f2d7">BPI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae34677a041d16250bbc787140f2a9ca0">AC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12bc301c1f504ee465cf8ff10fb77821">AllocationBlock</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8518df90911c53ff0da21533b874b5c">AllowVarArgs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d997119eca29c5f7743cb625b45d791">Blocks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a383f32110209230c9ace193dd97ec1a1">ExtractedFuncRetVals</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lists of blocks that are branched from the code region to be extracted, also called the exit blocks. <a href="#a383f32110209230c9ace193dd97ec1a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b02a08a96a4345c3d740bb3b689da43">Suffix</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e027485b8b10f5d9f0a3b6517a32b0a">ArgsInZeroAddressSpace</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">ValueSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab48f25d4f0c09a0d963a9744a14727d8">ExcludeArgsFromAggregate</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a995ee70f3e9a0cb350322bb1e058a707">verifyAssumptionCache</a> (const Function &amp;OldFunc, const Function &amp;NewFunc, AssumptionCache *AC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify that assumption cache isn't stale after a region is extracted. <a href="#a995ee70f3e9a0cb350322bb1e058a707">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Utility class for extracting code into a new function.</p>


<p>This utility provides a simple interface for extracting some sequence of code into its own function, replacing it with a call to that function. It also provides various methods to query about the nature and result of such a transformation.</p>


<p>The rough algorithm used is: 1) Find both the inputs and outputs for the extracted region. 2) <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> the inputs as arguments, remapping them within the extracted function to arguments. 3) Add allocas for any scalar outputs, adding all of the outputs' allocas as arguments, and inserting stores to the arguments for any scalars.</p>


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ValueSet {#ab6271464228e166c13033f277a43493e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CodeExtractor::ValueSet =  SetVector&lt;Value *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CodeExtractor() {#a152c260d40a85ed5b0ef5f11f86ac3b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeExtractor::CodeExtractor (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; BBs, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT=nullptr, bool AggregateArgs=false, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI=nullptr, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> * BPI=nullptr, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC=nullptr, bool AllowVarArgs=false, bool AllowAlloca=false, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * AllocationBlock=nullptr, std::string Suffix="", bool ArgsInZeroAddressSpace=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a code extractor for a sequence of blocks.</p>


<p>Given a sequence of basic blocks where the first block in the sequence dominates the rest, prepare a code extractor object for pulling this sequence out into its new function. When a <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> is also given, extra checking and transformations are enabled. If AllowVarArgs is true, vararg functions can be extracted. This is safe, if all vararg handling code is extracted, including vastart. If AllowAlloca is true, then extraction of blocks containing alloca instructions would be possible, however code extractor won't validate whether extraction is legal. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> new allocations will be placed in the AllocationBlock, unless it is null, in which case it will be placed in the entry block of the function from which the code is being extracted. If ArgsInZeroAddressSpace param is set to true, then the aggregate param pointer of the outlined function is declared in zero address space.</p>


<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#ab04f4c20d718420071af11662817dbd4">AggregateArgsOpt</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#a10e1b14fd1da88aad682e5d70ab224bb">buildExtractionBlockSet</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### excludeArgFromAggregate() {#ad4d03968d09741d23f5b83e7a538f04f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeExtractor::excludeArgFromAggregate (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Arg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Exclude a value from aggregate argument passing when extracting a code region, passing it instead as a scalar.</p>

<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 2051 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>

</div>
</div>

### extractCodeRegion() {#a8561c48aa0b397c37f9e071dad7df392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * CodeExtractor::extractCodeRegion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeextractoranalysiscache">CodeExtractorAnalysisCache</a> &amp; CEAC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform the extraction, returning the new function.</p>


<p>Returns zero when called on a <a href="/web-llvm/docs/api/classes/llvm/codeextractor">CodeExtractor</a> instance where isEligible returns false.</p>


<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 1395 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>


<p>Reference <a href="#a8561c48aa0b397c37f9e071dad7df392">extractCodeRegion</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#aa06ef927da6dbc2b989bb4df7d1f5c6a">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::doSingleRegionFunctionOutlining</a>, <a href="#a8561c48aa0b397c37f9e071dad7df392">extractCodeRegion</a> and <a href="/web-llvm/docs/api/classes/anonymous-blockextractor-cpp-/blockextractor/#ab929be069dc417044c41ddeca9bec3b7">anonymous{BlockExtractor.cpp}::BlockExtractor::runOnModule</a>.</p>

</div>
</div>

### extractCodeRegion() {#ac0645a37d60eb4946b1b73c517a96544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * CodeExtractor::extractCodeRegion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeextractoranalysiscache">CodeExtractorAnalysisCache</a> &amp; CEAC, <a href="/web-llvm/docs/api/classes/llvm/setvector">ValueSet</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/llvm/setvector">ValueSet</a> &amp; Outputs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform the extraction, returning the new function and providing an interface to see what was categorized as inputs and outputs.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CEAC</td>
<td class="doxyParamItemDescription"><p>- Cache to speed up operations for the <a href="/web-llvm/docs/api/classes/llvm/codeextractor">CodeExtractor</a> when hoisting, and extracting lifetime values and assumes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Inputs</td>
<td class="doxyParamItemDescription"><p>[out] - filled with values marked as inputs to the newly outlined function.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Outputs</td>
<td class="doxyParamItemDescription"><p>[out] - filled with values marked as outputs to the newly outlined function.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>zero when called on a <a href="/web-llvm/docs/api/classes/llvm/codeextractor">CodeExtractor</a> instance where isEligible returns false.</p></dd>
</dl>


<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 1401 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#af7dca9a9e816ef69fd9e9467f64f72b4">llvm::Value::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a266367eb01c634406b32f816d2d9c6bf">llvm::BasicBlock::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ac178f4fc4e4a0642610c374256b9fb27">llvm::SetVector&lt; T, Vector, Set, N &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#a93144a1eb23283cfa213d7dccb12d683">eraseLifetimeMarkersOnInputs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#a537993928c8af5b0d064fcd5ce1dec2f">findAllocas</a>, <a href="#ab4d4236fd0a481a0d93e159a9882fc53">findInputsOutputs</a>, <a href="#a19ce83f3f1fef433e2ba91a0b2a196a0">findOrCreateBlockForHoisting</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a0c7d0dae14eb8a5916fff9f72d8b46d2">llvm::SetVector&lt; T, Vector, Set, N &gt;::getArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a62ee7ece4986606d41363bc1f70d5ab2">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNextNode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#ad3a4770e725305d3529cba8c6562c85a">isEligible</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f470380211ecb6cee767f1ef0f16ed0">llvm::Function::IsNewDbgInfoFormat</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af67d1f3a518964d80a109bb3d9d5cf1e">llvm::Instruction::moveBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>, <a href="#a995ee70f3e9a0cb350322bb1e058a707">verifyAssumptionCache</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26389c546573f058ad8ecbdc5c1933cf">llvm::verifyFunction</a>.</p>

</div>
</div>

### findAllocas() {#a537993928c8af5b0d064fcd5ce1dec2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeExtractor::findAllocas (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeextractoranalysiscache">CodeExtractorAnalysisCache</a> &amp; CEAC, <a href="/web-llvm/docs/api/classes/llvm/setvector">ValueSet</a> &amp; SinkCands, <a href="/web-llvm/docs/api/classes/llvm/setvector">ValueSet</a> &amp; HoistCands, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *&amp; ExitBlock)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the set of allocas whose life ranges are contained within the outlined region.</p>


<p>Allocas which have life_time markers contained in the outlined region should be pushed to the outlined function. The address bitcasts that are used by the lifetime markers are also candidates for shrink- wrapping. The instructions that need to be sunk are collected in 'Allocas'.</p>


<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#ac120250caf531b58acce9d8cc34c7032">llvm::CastInst::CreatePointerCast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#a2b5ed2fba3b0aa877b82ba5d6f4131bf">definedInRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractoranalysiscache/#a35fd9ad0c2debb7b171f4c61ce7bdac6">llvm::CodeExtractorAnalysisCache::getAllocas</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#a8289e5f6e7e557759efb2b1b785c9196">getCommonExitBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a185bafe1e8f07def76a3bac154a23e7a">llvm::Instruction::isLifetimeStartOrEnd</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="#ac0645a37d60eb4946b1b73c517a96544">extractCodeRegion</a>.</p>

</div>
</div>

### findInputsOutputs() {#ab4d4236fd0a481a0d93e159a9882fc53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeExtractor::findInputsOutputs (<a href="/web-llvm/docs/api/classes/llvm/setvector">ValueSet</a> &amp; Inputs, <a href="/web-llvm/docs/api/classes/llvm/setvector">ValueSet</a> &amp; Outputs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/setvector">ValueSet</a> &amp; Allocas, bool CollectGlobalInputs=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the set of input values and output values for the code.</p>


<p>These can be used either when performing the extraction or to evaluate the expected size of a call to the extracted function. Note that this work cannot be cached between the two as once we decide to extract a code sequence, that sequence is modified, including changing these sets, before extraction occurs. These modifications won't have any significant impact on the cost however.</p>


<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/setvector/#abb03e3b6c4fd937936a13afe4f60d291">llvm::SetVector&lt; T, Vector, Set, N &gt;::count</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#a4dde4d426caa9831108c7520128292e0">definedInCaller</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#a2b5ed2fba3b0aa877b82ba5d6f4131bf">definedInRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#ac0645a37d60eb4946b1b73c517a96544">extractCodeRegion</a>.</p>

</div>
</div>

### findOrCreateBlockForHoisting() {#a19ce83f3f1fef433e2ba91a0b2a196a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * CodeExtractor::findOrCreateBlockForHoisting (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * CommonExitBlock)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find or create a block within the outline region for placing hoisted code.</p>


<p>CommonExitBlock is block outside the outline region. It is the common successor of blocks inside the region. If there exists a single block inside the region that is the predecessor of CommonExitBlock, that block will be returned. Otherwise CommonExitBlock will be split and the original block will be added to the outline region.</p>


<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a362b5e6097732cbc0d2fb555a1f73400">llvm::BasicBlock::getFirstNonPHIIt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a52c990590792c91dd20b6d45acebe359">llvm::BasicBlock::splitBasicBlock</a>.</p>


<p>Referenced by <a href="#ac0645a37d60eb4946b1b73c517a96544">extractCodeRegion</a>.</p>

</div>
</div>

### isEligible() {#ad3a4770e725305d3529cba8c6562c85a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeExtractor::isEligible ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether this code extractor is eligible.</p>


<p>Based on the blocks used when constructing the code extractor, determine whether it is eligible for extraction.</p>


<p>Checks that varargs handling (with vastart and vaend) is only done in the outlined blocks.</p>


<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#a2b5ed2fba3b0aa877b82ba5d6f4131bf">definedInRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>


<p>Referenced by <a href="#ac0645a37d60eb4946b1b73c517a96544">extractCodeRegion</a>.</p>

</div>
</div>

### isLegalToShrinkwrapLifetimeMarkers() {#ae9ce92095ff18cb2c607d5a3591703ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeExtractor::isLegalToShrinkwrapLifetimeMarkers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeextractoranalysiscache">CodeExtractorAnalysisCache</a> &amp; CEAC, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * AllocaAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if life time marker nodes can be hoisted/sunk into the outline region.</p>


<p>Returns true if it is safe to do the code motion.</p>


<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractoranalysiscache/#af0ee5fce396f816a21443799205fbedd">llvm::CodeExtractorAnalysisCache::doesBlockContainClobberOfAddr</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a3711f4a2446d9e9302ebfa2fb1180883">llvm::Value::stripInBoundsConstantOffsets</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### calculateNewCallTerminatorWeights() {#a78ead07dc9be9cd16a79317303faf46d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeExtractor::calculateNewCallTerminatorWeights (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * CodeReplacer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> &gt; &amp; ExitWeights, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> * BPI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 1159 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>

</div>
</div>

### computeExtractedFuncRetVals() {#a5a350e0e6280f2dc10d5351df669b4da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeExtractor::computeExtractedFuncRetVals ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Updates the list of SwitchCases (corresponding to exit blocks) after changes of the control flow or the Blocks list.</p>

<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 1534 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>

</div>
</div>

### constructFunctionDeclaration() {#a79eb5c4fb0d6136e56f5936208291ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * CodeExtractor::constructFunctionDeclaration (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/setvector">ValueSet</a> &amp; inputs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/setvector">ValueSet</a> &amp; outputs, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> EntryFreq, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, <a href="/web-llvm/docs/api/classes/llvm/setvector">ValueSet</a> &amp; StructValues, <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *&amp; StructTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generates the function declaration for the function containing the extracted code.</p>

<p>Declaration at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 820 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>

</div>
</div>

### emitFunctionBody() {#abe0a9415158260ff490f6e74da695fde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeExtractor::emitFunctionBody (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/setvector">ValueSet</a> &amp; inputs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/setvector">ValueSet</a> &amp; outputs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/setvector">ValueSet</a> &amp; StructValues, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * newFunction, <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> * StructArgTy, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * header, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/setvector">ValueSet</a> &amp; SinkingCands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generates the code for the extracted function.</p>


<p>That is: a prolog, the moved or copied code from the original function, and epilogs for each exit.</p>


<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 1567 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>

</div>
</div>

### emitReplacerCall() {#a3e494a515f6c5ab54dfb67e2043f0f91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * CodeExtractor::emitReplacerCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/setvector">ValueSet</a> &amp; inputs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/setvector">ValueSet</a> &amp; outputs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/setvector">ValueSet</a> &amp; StructValues, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * newFunction, <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> * StructArgTy, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * oldFunction, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * ReplIP, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> EntryFreq, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; LifetimesStart, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; Reloads)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generates a Basic Block that calls the extracted function.</p>

<p>Declaration at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 1766 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>

</div>
</div>

### getLifetimeMarkers() {#aaeb52d50b07b579d70ab4ec53afa368e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeExtractor::LifetimeMarkerInfo CodeExtractor::getLifetimeMarkers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeextractoranalysiscache">CodeExtractorAnalysisCache</a> &amp; CEAC, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * ExitBlock)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>

</div>
</div>

### getSwitchType() {#a93d1fa599f74cec9c70aeb7c729b5d96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * CodeExtractor::getSwitchType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the type used for the return code of the extracted function to indicate which exit block to jump to.</p>

<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 1550 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>

</div>
</div>

### insertReplacerCall() {#a4f6b5ff66dc35723796354a00fc478bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeExtractor::insertReplacerCall (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * oldFunction, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * header, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * codeReplacer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/setvector">ValueSet</a> &amp; outputs, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Reloads, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> &gt; &amp; ExitWeights)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Connects the basic block containing the call to the extracted function into the original function's control flow.</p>

<p>Declaration at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 1968 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>

</div>
</div>

### moveCodeToFunction() {#ad5bbc2212ffdea8b5117834d6c0e36e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeExtractor::moveCodeToFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * newFunction)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 1144 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>

</div>
</div>

### normalizeCFGForExtraction() {#a1c08536df2601eaef5d6ea02e1cb1457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeExtractor::normalizeCFGForExtraction (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *&amp; header)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Normalizes the control flow of the extracted regions, such as ensuring that the extracted region does not contain a return instruction.</p>

<p>Declaration at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 1518 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>

</div>
</div>

### severSplitPHINodesOfEntry() {#a088347482819a60fe80edbb565a64576}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeExtractor::severSplitPHINodesOfEntry (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *&amp; Header)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>severSplitPHINodesOfEntry - If a PHI node has multiple inputs from outside of the region, we need to split the entry block of the region so that the PHI node is easier to deal with.</p>

<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 678 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>

</div>
</div>

### severSplitPHINodesOfExits() {#a5bf7ad0e20b2a13d447806bd8a53a9d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeExtractor::severSplitPHINodesOfExits ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>severSplitPHINodesOfExits - if PHI nodes in exit blocks have inputs from outlined region, we split these PHIs on two: one with inputs from region and other with remaining incoming blocks; then first PHIs are placed in outlined region.</p>

<p>Declaration at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 755 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>

</div>
</div>

### splitReturnBlocks() {#a50a00b19a935f0caee2d2780a657bf54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeExtractor::splitReturnBlocks ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 800 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AC {#ae34677a041d16250bbc787140f2a9ca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache* llvm::CodeExtractor::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>.</p>

</div>
</div>

### AggregateArgs {#a4ce8741a067c95c562937385a08c5ce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::CodeExtractor::AggregateArgs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>.</p>

</div>
</div>

### AllocationBlock {#a12bc301c1f504ee465cf8ff10fb77821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* llvm::CodeExtractor::AllocationBlock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>.</p>

</div>
</div>

### AllowVarArgs {#ae8518df90911c53ff0da21533b874b5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeExtractor::AllowVarArgs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>.</p>

</div>
</div>

### ArgsInZeroAddressSpace {#a6e027485b8b10f5d9f0a3b6517a32b0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeExtractor::ArgsInZeroAddressSpace</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>.</p>

</div>
</div>

### BFI {#a572c77244af879aa55fcda67edfe8408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfo* llvm::CodeExtractor::BFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>.</p>

</div>
</div>

### Blocks {#a3d997119eca29c5f7743cb625b45d791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt;BasicBlock *&gt; llvm::CodeExtractor::Blocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>.</p>

</div>
</div>

### BPI {#a0835502a4ef2f33dfc6eed41a6a9f2d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbabilityInfo* llvm::CodeExtractor::BPI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>.</p>

</div>
</div>

### DT {#a78d11c3a06b2deb9ca067d4ee9e99591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* const llvm::CodeExtractor::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>.</p>

</div>
</div>

### ExcludeArgsFromAggregate {#ab48f25d4f0c09a0d963a9744a14727d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueSet llvm::CodeExtractor::ExcludeArgsFromAggregate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>.</p>

</div>
</div>

### ExtractedFuncRetVals {#a383f32110209230c9ace193dd97ec1a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;BasicBlock *&gt; llvm::CodeExtractor::ExtractedFuncRetVals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lists of blocks that are branched from the code region to be extracted, also called the exit blocks.</p>


<p>Each block is contained at most once. Its order defines the return value of the extracted function.</p>


<p>When there is just one (or no) exit block, the return value is irrelevant.</p>


<p>When there are exactly two exit blocks, the extracted function returns a boolean. For ExtractedFuncRetVals[0], it returns 'true'. For ExtractedFuncRetVals[1] it returns 'false'. NOTE: Since a boolean is represented by i1, ExtractedFuncRetVals[0] returns 1 and ExtractedFuncRetVals[1] returns 0, which opposite of the regular pattern below.</p>


<p>When there are 3 or more exit blocks, leaving the extracted function via the first block it returns 0. When leaving via the second entry it returns 1, etc.</p>


<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>.</p>

</div>
</div>

### Suffix {#a1b02a08a96a4345c3d740bb3b689da43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::CodeExtractor::Suffix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### verifyAssumptionCache() {#a995ee70f3e9a0cb350322bb1e058a707}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeExtractor::verifyAssumptionCache (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; OldFunc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; NewFunc, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC)</td>
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

<p>Verify that assumption cache isn't stale after a region is extracted.</p>


<p>Returns true when verifier finds errors. <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> is passed as parameter to make this function stateless.</p>


<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a>, definition at line 2022 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#ac0645a37d60eb4946b1b73c517a96544">extractCodeRegion</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/codeextractor-h">CodeExtractor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp">CodeExtractor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
