---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loopvectorizationcostmodel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LoopVectorizationCostModel` Class

<p><a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel">LoopVectorizationCostModel</a> - estimates the expected speedups due to vectorization. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LoopVectorizationCostModel { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4e6b85f2d6082de289fc378a71d746b">ScalarCostsTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A type representing the costs for instructions if they were to be scalarized rather than vectorized. <a href="#ae4e6b85f2d6082de289fc378a71d746b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7edd59261e6980464433a84e406f7cc">DecisionList</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> &gt;, std::pair&lt; <a href="#abd75237965fb9548c506a19549c4a260">InstWidening</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps cost model vectorization decision and cost for instructions. <a href="#ab7edd59261e6980464433a84e406f7cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a843b8abbd9585f013ac47eebe7065af8">CallDecisionList</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> &gt;, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizationcostmodel/callwideningdecision">CallWideningDecision</a> &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">InstWidening { <a href="#abd75237965fb9548c506a19549c4a260">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decision that was taken during cost calculation for memory instruction. <a href="#abd75237965fb9548c506a19549c4a260">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a409249e01d3e65716e4c76fa3369a4e0">LoopVectorizationPlanner</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a405e73f32c9044b8b14648b62cb2ef30">LoopVectorizationCostModel</a> (ScalarEpilogueLowering SEL, Loop *L, PredicatedScalarEvolution &amp;PSE, LoopInfo *LI, LoopVectorizationLegality *Legal, const TargetTransformInfo &amp;TTI, const TargetLibraryInfo *TLI, DemandedBits *DB, AssumptionCache *AC, OptimizationRemarkEmitter *ORE, const Function *F, const LoopVectorizeHints *Hints, InterleavedAccessInfo &amp;IAI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fixedscalablevfpair">FixedScalableVFPair</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65ab4267c6c132d06451b5d97bc9ee83">computeMaxVF</a> (ElementCount UserVF, unsigned UserIC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad6239ca8b51657f5ebdbd6e51e6ea90">runtimeChecksRequired</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a885ad9ea73b97e3154433e5c37fefa99">selectUserVectorizationFactor</a> (ElementCount UserVF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Setup cost-based decisions for user vectorization factor. <a href="#a885ad9ea73b97e3154433e5c37fefa99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fa63b37ad2ac06f289e9962a3703e9e">getSmallestAndWidestTypes</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9f62350ccdebd24858be552f3fc051c">selectInterleaveCount</a> (ElementCount VF, InstructionCost LoopCost)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8d11752355845a0e271111de7be7d3a">setCostBasedWideningDecision</a> (ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> access instruction may be vectorized in more than one way. <a href="#ae8d11752355845a0e271111de7be7d3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8178cc5e49d5251d7ca3413b8a434f8f">setVectorizedCallDecision</a> (ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A call may be vectorized in different ways depending on whether we have vectorized variants available and whether the target supports masking. <a href="#a8178cc5e49d5251d7ca3413b8a434f8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/loopvectorizationcostmodel/registerusage">RegisterUsage</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91466f7a82e967ed765e6d876415a3b7">calculateRegisterUsage</a> (ArrayRef&lt; ElementCount &gt; VFs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ac5df8f0304981180d602dacb13512c">collectValuesToIgnore</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect values we want to ignore in the cost model. <a href="#a0ac5df8f0304981180d602dacb13512c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06f5d9725a2b1f7b06e8bf51f7d31417">collectElementTypesForWidening</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect all element types in the loop for which widening is needed. <a href="#a06f5d9725a2b1f7b06e8bf51f7d31417">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12d2850f420726c4acb262b626e95b7d">collectInLoopReductions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split reductions into those that happen in the loop, and those that happen outside. <a href="#a12d2850f420726c4acb262b626e95b7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad508b8cfa31c0e7a1ac8f9d733bb8eed">useOrderedReductions</a> (const RecurrenceDescriptor &amp;RdxDesc) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we should use strict in-order reductions for the given RdxDesc. <a href="#ad508b8cfa31c0e7a1ac8f9d733bb8eed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, uint64_t &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fe7595d60ab8e1f3ee1da0846838113">getMinimalBitwidths</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a6fbca8c965adeb8016a03ca3de2cac">isProfitableToScalarize</a> (Instruction *I, ElementCount VF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20d7c96738b8f59692aec029895f8eb9">isUniformAfterVectorization</a> (Instruction *I, ElementCount VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">I</span> is known to be uniform after vectorization. <a href="#a20d7c96738b8f59692aec029895f8eb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f5d6f7a1f29874d1e77a889510c879c">isScalarAfterVectorization</a> (Instruction *I, ElementCount VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">I</span> is known to be scalar after vectorization. <a href="#a5f5d6f7a1f29874d1e77a889510c879c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8c00664c6be2042407f13e4fcad950b">canTruncateToMinimalBitwidth</a> (Instruction *I, ElementCount VF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc1b952dd1661ccba4f999610bf9732e">setWideningDecision</a> (Instruction *I, ElementCount VF, InstWidening W, InstructionCost Cost)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Save vectorization decision <span class="doxyComputerOutput">W</span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a></span> taken by the cost model for instruction <span class="doxyComputerOutput">I</span> and vector width <span class="doxyComputerOutput">VF</span>. <a href="#abc1b952dd1661ccba4f999610bf9732e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c44a42299ed9e7e97200271b00e0c7a">setWideningDecision</a> (const InterleaveGroup&lt; Instruction &gt; *Grp, ElementCount VF, InstWidening W, InstructionCost Cost)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Save vectorization decision <span class="doxyComputerOutput">W</span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a></span> taken by the cost model for interleaving group <span class="doxyComputerOutput">Grp</span> and vector width <span class="doxyComputerOutput">VF</span>. <a href="#a9c44a42299ed9e7e97200271b00e0c7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abd75237965fb9548c506a19549c4a260">InstWidening</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af01e065313d5fcaba9570458faf32429">getWideningDecision</a> (Instruction *I, ElementCount VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cost model decision for the given instruction <span class="doxyComputerOutput">I</span> and vector width <span class="doxyComputerOutput">VF</span>. <a href="#af01e065313d5fcaba9570458faf32429">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7844564539b9f0f917e8f2380a064b3">getWideningCost</a> (Instruction *I, ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the vectorization cost for the given instruction <span class="doxyComputerOutput">I</span> and vector width <span class="doxyComputerOutput">VF</span>. <a href="#af7844564539b9f0f917e8f2380a064b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8e5bf6d340d3b3f704b6398996ae51c">setCallWideningDecision</a> (CallInst *CI, ElementCount VF, InstWidening Kind, Function *Variant, Intrinsic::ID IID, std::optional&lt; unsigned &gt; MaskPos, InstructionCost Cost)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loopvectorizationcostmodel/callwideningdecision">CallWideningDecision</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa29e19b06aa800d1289048b54c58e8c6">getCallWideningDecision</a> (CallInst *CI, ElementCount VF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61375f5189558cc261186f388d31fe92">isOptimizableIVTruncate</a> (Instruction *I, ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return True if instruction <span class="doxyComputerOutput">I</span> is an optimizable truncate whose operand is an induction variable. <a href="#a61375f5189558cc261186f388d31fe92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcbf4a19be078644e784b539379d59b7">collectInstsToScalarize</a> (ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collects the instructions to scalarize for each predicated instruction in the loop. <a href="#afcbf4a19be078644e784b539379d59b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4a3f06ac8f2aff57b864c2d8ace97d8">collectUniformsAndScalars</a> (ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect Uniform and Scalar values for the given <span class="doxyComputerOutput">VF</span>. <a href="#ab4a3f06ac8f2aff57b864c2d8ace97d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c25146329f69e026508656cfb1280fa">isLegalMaskedStore</a> (Type *DataType, Value *Ptr, Align Alignment) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target machine supports masked store operation for the given <span class="doxyComputerOutput">DataType</span> and kind of access to <span class="doxyComputerOutput">Ptr</span>. <a href="#a8c25146329f69e026508656cfb1280fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a472c49074b0d81970f8eea07de4d7ad4">isLegalMaskedLoad</a> (Type *DataType, Value *Ptr, Align Alignment) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target machine supports masked load operation for the given <span class="doxyComputerOutput">DataType</span> and kind of access to <span class="doxyComputerOutput">Ptr</span>. <a href="#a472c49074b0d81970f8eea07de4d7ad4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa650124eefba1fd45866d05306385129">isLegalGatherOrScatter</a> (Value *V, ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target machine can represent <span class="doxyComputerOutput">V</span> as a masked gather or scatter operation. <a href="#aa650124eefba1fd45866d05306385129">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07515d0542b797be2d1c87d4359ff8f6">canVectorizeReductions</a> (ElementCount VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the target machine supports all of the reduction variables found for the given VF. <a href="#a07515d0542b797be2d1c87d4359ff8f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add43c346a11ae1deb49142ba968eb07e">isDivRemScalarWithPredication</a> (InstructionCost ScalarCost, InstructionCost SafeDivisorCost) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given costs for both strategies, return true if the scalar predication lowering should be used for div/rem. <a href="#add43c346a11ae1deb49142ba968eb07e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac864682b9dcdc0ce83df845bf6cfb2e8">isScalarWithPredication</a> (Instruction *I, ElementCount VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">I</span> is an instruction which requires predication and for which our chosen predication strategy is scalarization (i.e. <a href="#ac864682b9dcdc0ce83df845bf6cfb2e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a96f040b7fc3eae004aa6dc2af8f522">isPredicatedInst</a> (Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">I</span> is an instruction that needs to be predicated at runtime. <a href="#a0a96f040b7fc3eae004aa6dc2af8f522">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8398a35cd187d6a75b460fcf54b5236">getDivRemSpeculationCost</a> (Instruction *I, ElementCount VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the costs for our two available strategies for lowering a div/rem operation which requires speculating at least one lane. <a href="#ad8398a35cd187d6a75b460fcf54b5236">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59a6dd7531c8683174f886ff7698cc63">memoryInstructionCanBeWidened</a> (Instruction *I, ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">I</span> is a memory instruction with consecutive memory access that can be widened. <a href="#a59a6dd7531c8683174f886ff7698cc63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5964ce9ba38fe5a4d372242ac39e3f1d">interleavedAccessCanBeWidened</a> (Instruction *I, ElementCount VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">I</span> is a memory instruction in an interleaved-group of memory accesses that can be vectorized with wide vector loads/stores and shuffles. <a href="#a5964ce9ba38fe5a4d372242ac39e3f1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85e3110b9fe54caf00fe4297d1b4f0b6">isAccessInterleaved</a> (Instruction *Instr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">Instr</span> belongs to any interleaved access group. <a href="#a85e3110b9fe54caf00fe4297d1b4f0b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/interleavegroup">InterleaveGroup</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a1e4ba873eb1b26dd3649a530a3e36c">getInterleavedAccessGroup</a> (Instruction *Instr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the interleaved access group that <span class="doxyComputerOutput">Instr</span> belongs to. <a href="#a5a1e4ba873eb1b26dd3649a530a3e36c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a913ab9c8291000dd3a1c3739194b03e4">requiresScalarEpilogue</a> (bool IsVectorizing) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we're required to use a scalar epilogue for at least the final iteration of the original loop. <a href="#a913ab9c8291000dd3a1c3739194b03e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08599d322c8160c0412192455bbfb3c2">requiresScalarEpilogue</a> (VFRange Range) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we're required to use a scalar epilogue for at least the final iteration of the original loop for all VFs in <span class="doxyComputerOutput">Range</span>. <a href="#a08599d322c8160c0412192455bbfb3c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af67062c22dbf5e0ab35164a778768476">isScalarEpilogueAllowed</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if a scalar epilogue is not allowed due to optsize or a loop hint annotation. <a href="#af67062c22dbf5e0ab35164a778768476">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdd">TailFoldingStyle</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a738b994c87e0e816cf5f323e0e2b6c07">getTailFoldingStyle</a> (bool IVUpdateMayOverflow=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdd">TailFoldingStyle</a> that is best for the current loop. <a href="#a738b994c87e0e816cf5f323e0e2b6c07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8eb89837d2853e4853ea14379ae3972">setTailFoldingStyles</a> (bool IsScalableVF, unsigned UserIC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Selects and saves <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdd">TailFoldingStyle</a> for 2 options - if IV update may overflow or not. <a href="#ab8eb89837d2853e4853ea14379ae3972">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf371382a45e4756dbc1753d162324ba">foldTailByMasking</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if all loop blocks should be masked to fold tail loop. <a href="#aaf371382a45e4756dbc1753d162324ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36ed7dfdcdc1bca9eea99fc741511590">getMaxSafeElements</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return maximum safe number of elements to be processed per vector iteration, which do not prevent store-load forwarding and are safe with regard to the memory dependencies. <a href="#a36ed7dfdcdc1bca9eea99fc741511590">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8c8de8f62b5d2b27c4878d3effd7273">blockNeedsPredicationForAnyReason</a> (BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the instructions in this block requires predication for any reason, e.g. <a href="#ab8c8de8f62b5d2b27c4878d3effd7273">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0c7e793ca1b6b8a4f8c00a1bc1cb32f">foldTailWithEVL</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if VP intrinsics with explicit vector length support should be generated in the tail folded loop. <a href="#ab0c7e793ca1b6b8a4f8c00a1bc1cb32f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9819226a3ff242635fd99bf22b50bd97">isInLoopReduction</a> (PHINode *Phi) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the Phi is part of an inloop reduction. <a href="#a9819226a3ff242635fd99bf22b50bd97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23c31233960bfc62d1cc93bb4a5f5148">usePredicatedReductionSelect</a> (unsigned Opcode, Type *PhiTy) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the predicated reduction select should be used to set the incoming value for the reduction phi. <a href="#a23c31233960bfc62d1cc93bb4a5f5148">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5abced3ab870d7abf57f2b35a02cd041">getVectorIntrinsicCost</a> (CallInst *CI, ElementCount VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Estimate cost of an intrinsic call instruction CI if it were vectorized with factor VF. <a href="#a5abced3ab870d7abf57f2b35a02cd041">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1f0755693a05c2b008e9a576c3b162b">getVectorCallCost</a> (CallInst *CI, ElementCount VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Estimate cost of a call instruction CI if it were vectorized with factor VF. <a href="#ad1f0755693a05c2b008e9a576c3b162b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85afe07533e500a31222b17f80b540fe">invalidateCostModelingDecisions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Invalidates decisions already taken by the cost model. <a href="#a85afe07533e500a31222b17f80b540fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4c50e6300599d50ba706c0d2b780502">expectedCost</a> (ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the expected execution cost. <a href="#ae4c50e6300599d50ba706c0d2b780502">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aa9aa5d09f2f30c5a62a4692e5a21e3">hasPredStores</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07db8a5919c9879e3327549f20cda2f9">isEpilogueVectorizationProfitable</a> (const ElementCount VF, const unsigned IC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if epilogue vectorization is considered profitable, and false otherwise. <a href="#a07db8a5919c9879e3327549f20cda2f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a> (Instruction *I, ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the execution time cost of an instruction for a given vector width. <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e307866e6d65e87d1e6884b0d13306c">getReductionPatternCost</a> (Instruction *I, ElementCount VF, Type *VectorTy) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cost of instructions in an inloop reduction pattern, if I is part of that pattern. <a href="#a4e307866e6d65e87d1e6884b0d13306c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadd9a9d699ede62468422c7cfab66e99">shouldConsiderInvariant</a> (Value *Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> should be considered invariant and if it is trivially hoistable. <a href="#aadd9a9d699ede62468422c7cfab66e99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fixedscalablevfpair">FixedScalableVFPair</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9956319d31294a80a256a76b4228b4b2">computeFeasibleMaxVF</a> (unsigned MaxTripCount, ElementCount UserVF, bool FoldTailByMasking)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11b8d73e606d42d9c0d5287b49d5b1da">getMaximizedVFForTarget</a> (unsigned MaxTripCount, unsigned SmallestType, unsigned WidestType, ElementCount MaxSafeVF, bool FoldTailByMasking)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ae934ae181e40f3a0b7e7658ddb5cae">isScalableVectorizationAllowed</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if scalable vectorization is supported and enabled. <a href="#a8ae934ae181e40f3a0b7e7658ddb5cae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09c45adebc2c4fa82cce2d0df576c9be">getMaxLegalScalableVF</a> (unsigned MaxSafeElements)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cc23e9a1f8dd15e9d17c608fb90814a">getMemoryInstructionCost</a> (Instruction *I, ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate vectorization cost of memory instruction <span class="doxyComputerOutput">I</span>. <a href="#a2cc23e9a1f8dd15e9d17c608fb90814a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad13565f2d563b87570fa74576b116b4b">getMemInstScalarizationCost</a> (Instruction *I, ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost computation for scalarized memory instruction. <a href="#ad13565f2d563b87570fa74576b116b4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a00ba77387558dbf2dc3ed28b944b34">getInterleaveGroupCost</a> (Instruction *I, ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost computation for interleaving group of memory instructions. <a href="#a0a00ba77387558dbf2dc3ed28b944b34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc8952751e71e49709fc1144d1e0e92f">getGatherScatterCost</a> (Instruction *I, ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost computation for Gather/Scatter instruction. <a href="#afc8952751e71e49709fc1144d1e0e92f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef7540a23106bdfe677828ff5085f250">getConsecutiveMemOpCost</a> (Instruction *I, ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost computation for widening instruction <span class="doxyComputerOutput">I</span> with consecutive memory access. <a href="#aef7540a23106bdfe677828ff5085f250">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7749fffb38d72b07b8a3625e720c0de5">getUniformMemOpCost</a> (Instruction *I, ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The cost calculation for Load/Store instruction <span class="doxyComputerOutput">I</span> with uniform pointer - Load: scalar load + broadcast. <a href="#a7749fffb38d72b07b8a3625e720c0de5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcf975438d3e87e38b4f0ae8438cd092">getScalarizationOverhead</a> (Instruction *I, ElementCount VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Estimate the overhead of scalarizing an instruction. <a href="#abcf975438d3e87e38b4f0ae8438cd092">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27101a97ecd70055be42f41c52cd5f69">useEmulatedMaskMemRefHack</a> (Instruction *I, ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if an artificially high cost for emulated masked memrefs should be used. <a href="#a27101a97ecd70055be42f41c52cd5f69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92dbc62025bcd5ac5d0f4219e6e970d9">computePredInstDiscount</a> (Instruction *PredInst, ScalarCostsTy &amp;ScalarCosts, ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the expected difference in cost from scalarizing the expression feeding a predicated instruction <span class="doxyComputerOutput">PredInst</span>. <a href="#a92dbc62025bcd5ac5d0f4219e6e970d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d4a948b9b7deacfddf01d2d6e3a7a7d">collectLoopUniforms</a> (ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect the instructions that are uniform after vectorization. <a href="#a1d4a948b9b7deacfddf01d2d6e3a7a7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8c30022b972dbde1cb1f5cfee7a5864">collectLoopScalars</a> (ElementCount VF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect the instructions that are scalar after vectorization. <a href="#ae8c30022b972dbde1cb1f5cfee7a5864">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60e07d5fe91e94f05d201cb4e285c4ad">needsExtract</a> (Value *V, ElementCount VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">V</span> is expected to be vectorized and it needs to be extracted. <a href="#a60e07d5fe91e94f05d201cb4e285c4ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e9dd76b56349c25f0d718e50b9f6efd">filterExtractingOperands</a> (Instruction::op_range Ops, ElementCount VF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a range containing only operands needing to be extracted. <a href="#a2e9dd76b56349c25f0d718e50b9f6efd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The loop that we evaluate. <a href="#a664dc60e31d9203d66c9d7a49787b63f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35372cc43a297f286fc6c679b14c61d2">PSE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Predicated scalar evolution analysis. <a href="#a35372cc43a297f286fc6c679b14c61d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c62d3e36a2d815cbfac5a1579ccbb01">LI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> Info analysis. <a href="#a8c62d3e36a2d815cbfac5a1579ccbb01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality">LoopVectorizationLegality</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4714bf2e30b65997d553264e047245f1">Legal</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vectorization legality. <a href="#a4714bf2e30b65997d553264e047245f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector target information. <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a598f8ca344de1cfac7a7985b212bb66b">TLI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Library Info. <a href="#a598f8ca344de1cfac7a7985b212bb66b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/demandedbits">DemandedBits</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58fd764accfd06df487cc6ec43d4f5fc">DB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Demanded bits analysis. <a href="#a58fd764accfd06df487cc6ec43d4f5fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba357162dc28acb3a399731e1e397614">AC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assumption cache. <a href="#aba357162dc28acb3a399731e1e397614">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b0171a0d29e72189ffad26b9770c464">ORE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface to emit optimization remarks. <a href="#a8b0171a0d29e72189ffad26b9770c464">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4384debcd154f44445005e6866afba4a">TheFunction</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints">LoopVectorizeHints</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35e67974daa692cfd961904c151ad33d">Hints</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> Vectorize Hint. <a href="#a35e67974daa692cfd961904c151ad33d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/interleavedaccessinfo">InterleavedAccessInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a98f0c17229446d76997f158d896aad">InterleaveInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The interleave access information contains groups of interleaved accesses with the same stride and close to each other. <a href="#a7a98f0c17229446d76997f158d896aad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e207263ca75f2bfc5eb562a213bc575">ValuesToIgnore</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Values to ignore in the cost model. <a href="#a7e207263ca75f2bfc5eb562a213bc575">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91945cb39ed4c6676d991a9528dcd2d0">VecValuesToIgnore</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Values to ignore in the cost model when VF &gt; 1. <a href="#a91945cb39ed4c6676d991a9528dcd2d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00a28a503636abdbedf080f3896b937c">ElementTypesInLoop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All element types found in the loop. <a href="#a00a28a503636abdbedf080f3896b937c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a686506cbb75808c52247608065bc6596">CostKind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The kind of cost that we are calculating. <a href="#a686506cbb75808c52247608065bc6596">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8156223056c7fbdd5c8150d2fe4b7dc3">NumPredStores</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f50fc0d0512a2412fff5a6a1132c3b3">MinBWs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map of scalar integer values to the smallest bitwidth they can be legally represented as. <a href="#a2f50fc0d0512a2412fff5a6a1132c3b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 4 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd39f031902ddbca84a441ce108fee1f">PredicatedBBsAfterVectorization</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A set containing all BasicBlocks that are known to present after vectorization as a predicated block. <a href="#afd39f031902ddbca84a441ce108fee1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ab5d4f35a197e7b0f2320bdbbf518bd9d">ScalarEpilogueLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbb186bdec9b34efe2c9398f1963aef1">ScalarEpilogueStatus</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#ab5d4f35a197e7b0f2320bdbbf518bd9da65f7ef37c3a0cd826b5e361e8cf32cf7">CM_ScalarEpilogueAllowed</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Records whether it is allowed to have the original scalar loop execute at least once. <a href="#afbb186bdec9b34efe2c9398f1963aef1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdd">TailFoldingStyle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdd">TailFoldingStyle</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb4943fb908288e581908a0fc56153a5">ChosenTailFoldingStyle</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Control finally chosen tail folding style. <a href="#abb4943fb908288e581908a0fc56153a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3640d157cd9cb23ed37933475b0a20f5">IsScalableVectorizationAllowed</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>true if scalable vectorization is supported and enabled. <a href="#a3640d157cd9cb23ed37933475b0a20f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ab7e76bb8a0d205cfa13351b0dfae32">MaxSafeElements</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maximum safe number of elements to be processed per vector iteration, which do not prevent store-load forwarding and are safe with regard to the memory dependencies. <a href="#a4ab7e76bb8a0d205cfa13351b0dfae32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/densemap">ScalarCostsTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3713624a2daa27a85f4b79153394398a">InstsToScalarize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A map holding scalar costs for different vectorization factors. <a href="#a3713624a2daa27a85f4b79153394398a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0152151c757d7aa0c4cee9c919666ddc">Uniforms</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds the instructions known to be uniform after vectorization. <a href="#a0152151c757d7aa0c4cee9c919666ddc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e5401d78114cb93b8784701c3051a72">Scalars</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds the instructions known to be scalar after vectorization. <a href="#a3e5401d78114cb93b8784701c3051a72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade5f41ac1ba74cbc8c1adc4c46e29812">ForcedScalars</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds the instructions (address computations) that are forced to be scalarized. <a href="#ade5f41ac1ba74cbc8c1adc4c46e29812">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac025f929ec31e3c10c997a2e82c6b034">InLoopReductions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PHINodes of the reductions that should be expanded in-loop. <a href="#ac025f929ec31e3c10c997a2e82c6b034">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cb052e45c60c073f4e6e05e79e68c0a">InLoopReductionImmediateChains</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A Map of inloop reduction operations and their immediate chain operand. <a href="#a5cb052e45c60c073f4e6e05e79e68c0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DecisionList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad49214633145ca13a71c8c9a91fdfab9">WideningDecisions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">CallDecisionList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9761802e2f0c3bb684179023d0ff711">CallWideningDecisions</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel">LoopVectorizationCostModel</a> - estimates the expected speedups due to vectorization.</p>


<p>In many cases vectorization is not profitable. This can happen because of a number of reasons. In this class we mainly attempt to predict the expected speedup/slowdowns due to the supported instruction set. We use the <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> to query the different backends for the cost of different operations.</p>


<p>Definition at line 966 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### CallDecisionList {#a843b8abbd9585f013ac47eebe7065af8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LoopVectorizationCostModel::CallDecisionList = 
      DenseMap&lt;std::pair&lt;CallInst *, ElementCount&gt;, CallWideningDecision&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1717 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### DecisionList {#ab7edd59261e6980464433a84e406f7cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LoopVectorizationCostModel::DecisionList =  DenseMap&lt;std::pair&lt;Instruction *, ElementCount&gt;,
                                std::pair&lt;InstWidening, InstructionCost&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keeps cost model vectorization decision and cost for instructions.</p>


<p>Right now it is used for memory instructions only.</p>


<p>Definition at line 1712 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### ScalarCostsTy {#ae4e6b85f2d6082de289fc378a71d746b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LoopVectorizationCostModel::ScalarCostsTy =  DenseMap&lt;Instruction *, InstructionCost&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A type representing the costs for instructions if they were to be scalarized rather than vectorized.</p>


<p>The entries are Instruction-Cost pairs.</p>


<p>Definition at line 1625 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### InstWidening {#abd75237965fb9548c506a19549c4a260}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LoopVectorizationCostModel::InstWidening </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decision that was taken during cost calculation for memory instruction.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CM_Unknown<a id="abd75237965fb9548c506a19549c4a260af974de6a8aba0481a82335fb93471a39"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CM_Widen<a id="abd75237965fb9548c506a19549c4a260adc468760c02910f77bad7525bc66c334"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CM_Widen_Reverse<a id="abd75237965fb9548c506a19549c4a260a058eacbd3c28e2ecec2af7db726ce527"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CM_Interleave<a id="abd75237965fb9548c506a19549c4a260a3a2a7904b0c4a7f4c55939e457bcc971"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CM_GatherScatter<a id="abd75237965fb9548c506a19549c4a260ae849d400780f51424bc4e4c26ddf3000"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CM_Scalarize<a id="abd75237965fb9548c506a19549c4a260a03c0934d38787b1773c050deee484126"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CM_VectorCall<a id="abd75237965fb9548c506a19549c4a260ab6fd5f45ab6e363de6c3f42472d439ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CM_IntrinsicCall<a id="abd75237965fb9548c506a19549c4a260a679b46cebdf2f87b9efd0413c960314a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1126 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### LoopVectorizationPlanner {#a409249e01d3e65716e4c76fa3369a4e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner">LoopVectorizationPlanner</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 967 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Reference <a href="#a409249e01d3e65716e4c76fa3369a4e0">LoopVectorizationPlanner</a>.</p>


<p>Referenced by <a href="#a409249e01d3e65716e4c76fa3369a4e0">LoopVectorizationPlanner</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LoopVectorizationCostModel() {#a405e73f32c9044b8b14648b62cb2ef30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoopVectorizationCostModel::LoopVectorizationCostModel (<a href="/web-llvm/docs/api/namespaces/llvm/#ab5d4f35a197e7b0f2320bdbbf518bd9d">ScalarEpilogueLowering</a> SEL, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality">LoopVectorizationLegality</a> * Legal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/classes/llvm/demandedbits">DemandedBits</a> * DB, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints">LoopVectorizeHints</a> * Hints, <a href="/web-llvm/docs/api/classes/llvm/interleavedaccessinfo">InterleavedAccessInfo</a> &amp; IAI)</td>
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



<p>Definition at line 970 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="#aba357162dc28acb3a399731e1e397614">AC</a>, <a href="#a686506cbb75808c52247608065bc6596">CostKind</a>, <a href="#a58fd764accfd06df487cc6ec43d4f5fc">DB</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a35e67974daa692cfd961904c151ad33d">Hints</a>, <a href="#a7a98f0c17229446d76997f158d896aad">InterleaveInfo</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="#a8c62d3e36a2d815cbfac5a1579ccbb01">LI</a>, <a href="#a8b0171a0d29e72189ffad26b9770c464">ORE</a>, <a href="#a35372cc43a297f286fc6c679b14c61d2">PSE</a>, <a href="#a4384debcd154f44445005e6866afba4a">TheFunction</a>, <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a>, <a href="#a598f8ca344de1cfac7a7985b212bb66b">TLI</a> and <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### blockNeedsPredicationForAnyReason() {#ab8c8de8f62b5d2b27c4878d3effd7273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::blockNeedsPredicationForAnyReason (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Returns true if the instructions in this block requires predication for any reason, e.g.</p>


<p>because tail folding now requires a predicate or because the block in the original loop was predicated.</p>


<p>Definition at line 1482 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="#aaf371382a45e4756dbc1753d162324ba">foldTailByMasking</a> and <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>.</p>


<p>Referenced by <a href="#afcbf4a19be078644e784b539379d59b7">collectInstsToScalarize</a>, <a href="#a5964ce9ba38fe5a4d372242ac39e3f1d">interleavedAccessCanBeWidened</a> and <a href="#a0a96f040b7fc3eae004aa6dc2af8f522">isPredicatedInst</a>.</p>

</div>
</div>

### calculateRegisterUsage() {#a91466f7a82e967ed765e6d876415a3b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; LoopVectorizationCostModel::RegisterUsage, 8 &gt; LoopVectorizationCostModel::calculateRegisterUsage (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> &gt; VFs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Returns information about the register usages of the loop for the given vectorization factors.</p></dd>
</dl>


<p>Definition at line 1041 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/loopblocksdfs/#a003fe6215d300fc9720b1b056cdf4c23">llvm::LoopBlocksDFS::beginRPO</a>, <a href="#a12d2850f420726c4acb262b626e95b7d">collectInLoopReductions</a>, <a href="#ab4a3f06ac8f2aff57b864c2d8ace97d8">collectUniformsAndScalars</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/loopblocksdfs/#aeebda6b0288bea7cd706111624ca73f6">llvm::LoopBlocksDFS::endRPO</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a11045c7973ab24a8d6315b61fa337d4e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="#a5f5d6f7a1f29874d1e77a889510c879c">isScalarAfterVectorization</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#aa6a2194fc011669faabe43322d7c6c5f">llvm::VectorType::isValidElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a098a514da47d00e1176aa2e16eacfb70">llvm::ElementCount::isVector</a>, <a href="#a8c62d3e36a2d815cbfac5a1579ccbb01">LI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizationcostmodel/registerusage/#a12f1d225b87b9cb583e78478d9ef3b9c">llvm::LoopVectorizationCostModel::RegisterUsage::LoopInvariantRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizationcostmodel/registerusage/#a0ae3b197ca92417681a2865b605e56a9">llvm::LoopVectorizationCostModel::RegisterUsage::MaxLocalUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/loopblocksdfs/#adc85a5f08fb0f5dc3e053975995c9d29">llvm::LoopBlocksDFS::perform</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06aefdc051657574f00e43b0fa1f87e7336">llvm::RegUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#acf4c09e1f30cdd4e0b5b1b8a236ead34">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a0e1c3175b0ac22fe3853651c28e1ecb8">llvm::SmallPtrSetImplBase::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a3bf42baf773b375802538951c88d8e12">ToRemove</a>, <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a>, <a href="#a7e207263ca75f2bfc5eb562a213bc575">ValuesToIgnore</a> and <a href="#a91945cb39ed4c6676d991a9528dcd2d0">VecValuesToIgnore</a>.</p>


<p>Referenced by <a href="#af9f62350ccdebd24858be552f3fc051c">selectInterleaveCount</a>.</p>

</div>
</div>

### canTruncateToMinimalBitwidth() {#aa8c00664c6be2042407f13e4fcad950b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::canTruncateToMinimalBitwidth (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if instruction <span class="doxyComputerOutput">I</span> can be truncated to a smaller bitwidth for vectorization factor <span class="doxyComputerOutput">VF</span>.</p></dd>
</dl>


<p>Definition at line 1119 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a9a6fbca8c965adeb8016a03ca3de2cac">isProfitableToScalarize</a>, <a href="#a5f5d6f7a1f29874d1e77a889510c879c">isScalarAfterVectorization</a> and <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a098a514da47d00e1176aa2e16eacfb70">llvm::ElementCount::isVector</a>.</p>


<p>Referenced by <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>.</p>

</div>
</div>

### canVectorizeReductions() {#a07515d0542b797be2d1c87d4359ff8f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::canVectorizeReductions (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
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

<p>Returns true if the target machine supports all of the reduction variables found for the given VF.</p>

<p>Definition at line 1299 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a175f1f53cc9c3619505ffbd13aca087f">Reduction</a>.</p>

</div>
</div>

### collectElementTypesForWidening() {#a06f5d9725a2b1f7b06e8bf51f7d31417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVectorizationCostModel::collectElementTypesForWidening ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect all element types in the loop for which widening is needed.</p>

<p>Definition at line 1047 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a00a28a503636abdbedf080f3896b937c">ElementTypesInLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a30ee597b72598bc7939d3a40d2a5ba20">llvm::RecurrenceDescriptor::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a4f29fefacd6bdd966f6ba021cc656a2f">llvm::RecurrenceDescriptor::getRecurrenceType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a96ef6bd4742763bf1b85aaf1a4150620">PreferInLoopReductions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a>, <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a>, <a href="#ad508b8cfa31c0e7a1ac8f9d733bb8eed">useOrderedReductions</a> and <a href="#a7e207263ca75f2bfc5eb562a213bc575">ValuesToIgnore</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#adeb41c907ebde15846bc643325909f95">processLoopInVPlanNativePath</a>.</p>

</div>
</div>

### collectInLoopReductions() {#a12d2850f420726c4acb262b626e95b7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVectorizationCostModel::collectInLoopReductions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Split reductions into those that happen in the loop, and those that happen outside.</p>


<p>In loop reductions are collected into InLoopReductions.</p>


<p>Definition at line 1051 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a30ee597b72598bc7939d3a40d2a5ba20">llvm::RecurrenceDescriptor::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a4f29fefacd6bdd966f6ba021cc656a2f">llvm::RecurrenceDescriptor::getRecurrenceType</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a6415fb68bc55f3a316aa414a5c2c0ab2">llvm::RecurrenceDescriptor::getReductionOpChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a96ef6bd4742763bf1b85aaf1a4150620">PreferInLoopReductions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a175f1f53cc9c3619505ffbd13aca087f">Reduction</a>, <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a>, <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a> and <a href="#ad508b8cfa31c0e7a1ac8f9d733bb8eed">useOrderedReductions</a>.</p>


<p>Referenced by <a href="#a91466f7a82e967ed765e6d876415a3b7">calculateRegisterUsage</a>.</p>

</div>
</div>

### collectInstsToScalarize() {#afcbf4a19be078644e784b539379d59b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVectorizationCostModel::collectInstsToScalarize (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collects the instructions to scalarize for each predicated instruction in the loop.</p>

<p>Definition at line 1250 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a50d461a887e200e704e5157d3b21514d">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::begin</a>, <a href="#ab8c8de8f62b5d2b27c4878d3effd7273">blockNeedsPredicationForAnyReason</a>, <a href="#abd75237965fb9548c506a19549c4a260a03c0934d38787b1773c050deee484126">CM_Scalarize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>, <a href="#a5f5d6f7a1f29874d1e77a889510c879c">isScalarAfterVectorization</a>, <a href="#ac864682b9dcdc0ce83df845bf6cfb2e8">isScalarWithPredication</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ad96fee81c3174ef427bf779d73fb1ef2">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a> and <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a>.</p>


<p>Referenced by <a href="#a885ad9ea73b97e3154433e5c37fefa99">selectUserVectorizationFactor</a>.</p>

</div>
</div>

### collectUniformsAndScalars() {#ab4a3f06ac8f2aff57b864c2d8ace97d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopVectorizationCostModel::collectUniformsAndScalars (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
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

<p>Collect Uniform and Scalar values for the given <span class="doxyComputerOutput">VF</span>.</p>


<p>The sets depend on CM decision for Load/Store instructions that may be vectorized as interleave, gather-scatter or scalarized. Also make a decision on what to do about call instructions in the loop at that VF – scalarize, call a known vector routine, or call a vector intrinsic.</p>


<p>Definition at line 1258 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>, <a href="#ae8d11752355845a0e271111de7be7d3a">setCostBasedWideningDecision</a> and <a href="#a8178cc5e49d5251d7ca3413b8a434f8f">setVectorizedCallDecision</a>.</p>


<p>Referenced by <a href="#a91466f7a82e967ed765e6d876415a3b7">calculateRegisterUsage</a> and <a href="#a885ad9ea73b97e3154433e5c37fefa99">selectUserVectorizationFactor</a>.</p>

</div>
</div>

### collectValuesToIgnore() {#a0ac5df8f0304981180d602dacb13512c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVectorizationCostModel::collectValuesToIgnore ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect values we want to ignore in the cost model.</p>

<p>Definition at line 1044 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#aba357162dc28acb3a399731e1e397614">AC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#abf73a826b5d6f739eb4af48ddf14c5b4">llvm::SmallPtrSetImpl&lt; PtrType &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/loopblocksdfs/#a003fe6215d300fc9720b1b056cdf4c23">llvm::LoopBlocksDFS::beginRPO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/codemetrics/#a7e174506b52ad46ea1f746a7f727d999">llvm::CodeMetrics::collectEphemeralValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a7004354fbee1c8cd74ed9001915e1db5">llvm::SmallPtrSetImpl&lt; PtrType &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/loopblocksdfs/#aeebda6b0288bea7cd706111624ca73f6">llvm::LoopBlocksDFS::endRPO</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#ae7e8084b6da14960ba7c5b2cb7bd5f66">llvm::InductionDescriptor::getCastInsts</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a5691507e6742c90b796d82fb8cb2d70d">llvm::RecurrenceDescriptor::getCastInsts</a>, <a href="#a5a1e4ba873eb1b26dd3649a530a3e36c">getInterleavedAccessGroup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2922c0c507ccec5bea4642aff9e2e328">llvm::getLoadStorePointerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a79c007dcf9fff57e1569e778d7885b5e">llvm::BasicBlock::getSingleSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a85e3110b9fe54caf00fe4297d1b4f0b6">isAccessInterleaved</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#a87d0fbdabd17122a3febe35d7fbefb60">IsEmptyBlock</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="#a8c62d3e36a2d815cbfac5a1579ccbb01">LI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/classes/llvm/loopblocksdfs/#adc85a5f08fb0f5dc3e053975995c9d29">llvm::LoopBlocksDFS::perform</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a13da92d2694197fbcb5b95fd94e7570d">llvm::BasicBlock::phis</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a175f1f53cc9c3619505ffbd13aca087f">Reduction</a>, <a href="#a913ab9c8291000dd3a1c3739194b03e4">requiresScalarEpilogue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a>, <a href="#a598f8ca344de1cfac7a7985b212bb66b">TLI</a>, <a href="#a7e207263ca75f2bfc5eb562a213bc575">ValuesToIgnore</a>, <a href="#a91945cb39ed4c6676d991a9528dcd2d0">VecValuesToIgnore</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a845142f96a84f067cb6bf639e37980d0">llvm::wouldInstructionBeTriviallyDead</a>.</p>

</div>
</div>

### computeMaxVF() {#a65ab4267c6c132d06451b5d97bc9ee83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedScalableVFPair LoopVectorizationCostModel::computeMaxVF (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> UserVF, unsigned UserIC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An upper bound for the vectorization factors (both fixed and scalable). If the factors are 0, vectorization and interleaving should be avoided up front.</p></dd>
</dl>


<p>Definition at line 986 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad146072469181af4ccb7ef03c28999ba">llvm::ScalarEvolution::applyLoopGuards</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5d4f35a197e7b0f2320bdbbf518bd9da65f7ef37c3a0cd826b5e361e8cf32cf7">llvm::CM_ScalarEpilogueAllowed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5d4f35a197e7b0f2320bdbbf518bd9da0a5c3a3ea2de39aa77f3e6da8de4d5bd">llvm::CM_ScalarEpilogueNotAllowedLowTripLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5d4f35a197e7b0f2320bdbbf518bd9da4f61afe29426363c5cf62d4ee93199b7">llvm::CM_ScalarEpilogueNotAllowedOptSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5d4f35a197e7b0f2320bdbbf518bd9dab8edd8f39c728bd8b0045b64768ef206">llvm::CM_ScalarEpilogueNotAllowedUsePredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5d4f35a197e7b0f2320bdbbf518bd9da34c20b2dbd2edddfd1b013f073a32354">llvm::CM_ScalarEpilogueNotNeededUsePredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdda6ae67872a709ea2e3175802518fc4e71">llvm::DataWithEVL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/fixedscalablevfpair/#a25a62c28e80eac3b4cc08470ae0770bd">llvm::FixedScalableVFPair::FixedVF</a>, <a href="#aaf371382a45e4756dbc1753d162324ba">foldTailByMasking</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a22d9bcbd44563106d7217f3bd9a4039e">llvm::ScalarEvolution::getBackedgeTakenCount</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a2eb94d079d8416118f4aaed865ab05d7">llvm::ScalarEvolution::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a604c96744d2e46447f11e2d3aab9a9b2">getMaxVScale</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a8d5202095ab1b8b726dd1e9db728b997">llvm::ScalarEvolution::getMinusOne</a>, <a href="/web-llvm/docs/api/structs/llvm/fixedscalablevfpair/#aa2acd0d0943f4e488516ad21848f9be3">llvm::FixedScalableVFPair::getNone</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a3fbe8f529d36d76730550905d730a2a7">llvm::ScalarEvolution::getOne</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#abec0c616087c002528fcf80c6583eadd">llvm::ScalarEvolution::getSmallConstantTripCount</a>, <a href="#a738b994c87e0e816cf5f323e0e2b6c07">getTailFoldingStyle</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a13b9eb961d35ad9ecb3b633f5703253a">llvm::ScalarEvolution::getURemExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="#a7a98f0c17229446d76997f158d896aad">InterleaveInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#af74112dae88db73eb5484821b6f0fccd">llvm::ScalarEvolution::isKnownPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a5cafb166cf7c4937f5647a084c4eaee2">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isNonZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#a4541962f9c18aacceb7243520eb15e1f">llvm::SCEV::isZero</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a8b0171a0d29e72189ffad26b9770c464">ORE</a>, <a href="#a35372cc43a297f286fc6c679b14c61d2">PSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab425bb10a0f4af749bbb29aa07fc6854">llvm::reportVectorizationFailure</a>, <a href="#aad6239ca8b51657f5ebdbd6e51e6ea90">runtimeChecksRequired</a>, <a href="/web-llvm/docs/api/structs/llvm/fixedscalablevfpair/#a25f82f8ef3355c335a7ddae4ad0b6965">llvm::FixedScalableVFPair::ScalableVF</a>, <a href="#ab8eb89837d2853e4853ea14379ae3972">setTailFoldingStyles</a>, <a href="#a4384debcd154f44445005e6866afba4a">TheFunction</a>, <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a>, <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#adf8d8fb6f39b9c0cf21d55b7229d35e2">useMaskedInterleavedAccesses</a>.</p>

</div>
</div>

### expectedCost() {#ae4c50e6300599d50ba706c0d2b780502}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost LoopVectorizationCostModel::expectedCost (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the expected execution cost.</p>


<p>The unit of the cost does not matter because we use the 'cost' units to compare different vector widths. The cost that is returned is <em>not</em> normalized by the factor width.</p>


<p>Definition at line 1531 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#ababcaf6e2e00fc3fc8791ea2c3acbda5">addFullyUnrolledInstructionsToIgnore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#aaf371382a45e4756dbc1753d162324ba">foldTailByMasking</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a5eae6074e6a1bb62e365ef65f3e26196">ForceTargetInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb5d7cdf62c5d24e421899cd74c4550d">llvm::getReciprocalPredBlockProb</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#aab9a9b0568c1c524f01499c7930b3bf9">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a098a514da47d00e1176aa2e16eacfb70">llvm::ElementCount::isVector</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a35372cc43a297f286fc6c679b14c61d2">PSE</a>, <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a>, <a href="#a7e207263ca75f2bfc5eb562a213bc575">ValuesToIgnore</a> and <a href="#a91945cb39ed4c6676d991a9528dcd2d0">VecValuesToIgnore</a>.</p>


<p>Referenced by <a href="#af9f62350ccdebd24858be552f3fc051c">selectInterleaveCount</a> and <a href="#a885ad9ea73b97e3154433e5c37fefa99">selectUserVectorizationFactor</a>.</p>

</div>
</div>

### foldTailByMasking() {#aaf371382a45e4756dbc1753d162324ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::foldTailByMasking ()</td>
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

<p>Returns true if all loop blocks should be masked to fold tail loop.</p>

<p>Definition at line 1464 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="#a738b994c87e0e816cf5f323e0e2b6c07">getTailFoldingStyle</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdda6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>


<p>Referenced by <a href="#ab8c8de8f62b5d2b27c4878d3effd7273">blockNeedsPredicationForAnyReason</a>, <a href="#a65ab4267c6c132d06451b5d97bc9ee83">computeMaxVF</a>, <a href="#ae4c50e6300599d50ba706c0d2b780502">expectedCost</a> and <a href="#ae8d11752355845a0e271111de7be7d3a">setCostBasedWideningDecision</a>.</p>

</div>
</div>

### foldTailWithEVL() {#ab0c7e793ca1b6b8a4f8c00a1bc1cb32f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::foldTailWithEVL ()</td>
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

<p>Returns true if VP intrinsics with explicit vector length support should be generated in the tail folded loop.</p>

<p>Definition at line 1488 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdda6ae67872a709ea2e3175802518fc4e71">llvm::DataWithEVL</a> and <a href="#a738b994c87e0e816cf5f323e0e2b6c07">getTailFoldingStyle</a>.</p>


<p>Referenced by <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>, <a href="#af9f62350ccdebd24858be552f3fc051c">selectInterleaveCount</a> and <a href="#a23c31233960bfc62d1cc93bb4a5f5148">usePredicatedReductionSelect</a>.</p>

</div>
</div>

### getCallWideningDecision() {#aa29e19b06aa800d1289048b54c58e8c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallWideningDecision llvm::LoopVectorizationCostModel::getCallWideningDecision (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
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



<p>Definition at line 1216 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>.</p>

</div>
</div>

### getDivRemSpeculationCost() {#ad8398a35cd187d6a75b460fcf54b5236}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; InstructionCost, InstructionCost &gt; LoopVectorizationCostModel::getDivRemSpeculationCost (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the costs for our two available strategies for lowering a div/rem operation which requires speculating at least one lane.</p>


<p>First result is for scalarization (will be invalid for scalable vectors); second is for the safe-divisor strategy.</p>


<p>Definition at line 1338 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba07aee43ffb66908a25c55c77ce4c0d05">llvm::CmpInst::BAD_ICMP_PREDICATE</a>, <a href="#a686506cbb75808c52247608065bc6596">CostKind</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a57207993e2fe6ec98912e8072e4600bc">llvm::InstructionCost::getInvalid</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb5d7cdf62c5d24e421899cd74c4550d">llvm::getReciprocalPredBlockProb</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8601ff0320b6e29a13a2194200853425">llvm::isSafeToSpeculativelyExecute</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#afa38851d75434d1476444ac93f94cb4ca9c0eecea29e9fa58e4dac7ee32b9b2ac">llvm::TargetTransformInfo::OK_AnyValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#afa38851d75434d1476444ac93f94cb4ca7aa61d9e9d33bdf28478754c69c59640">llvm::TargetTransformInfo::OK_UniformValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae5262cc0e3a55bc74891cb8751d3b188">llvm::toVectorTy</a> and <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a>.</p>


<p>Referenced by <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a> and <a href="#ac864682b9dcdc0ce83df845bf6cfb2e8">isScalarWithPredication</a>.</p>

</div>
</div>

### getInstructionCost() {#a556ec90a0fa1e168a9f22db1deb1fee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost LoopVectorizationCostModel::getInstructionCost (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the execution time cost of an instruction for a given vector width.</p>


<p>Vector width of one means scalar.</p>


<p>Definition at line 1545 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba07aee43ffb66908a25c55c77ce4c0d05">llvm::CmpInst::BAD_ICMP_PREDICATE</a>, <a href="#aa8c00664c6be2042407f13e4fcad950b">canTruncateToMinimalBitwidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a07be078de4a2c223bd6a76e24e1c02db">llvm::cast_if_present</a>, <a href="#abd75237965fb9548c506a19549c4a260ae849d400780f51424bc4e4c26ddf3000">CM_GatherScatter</a>, <a href="#abd75237965fb9548c506a19549c4a260a3a2a7904b0c4a7f4c55939e457bcc971">CM_Interleave</a>, <a href="#abd75237965fb9548c506a19549c4a260a679b46cebdf2f87b9efd0413c960314a">CM_IntrinsicCall</a>, <a href="#abd75237965fb9548c506a19549c4a260a03c0934d38787b1773c050deee484126">CM_Scalarize</a>, <a href="#abd75237965fb9548c506a19549c4a260af974de6a8aba0481a82335fb93471a39">CM_Unknown</a>, <a href="#abd75237965fb9548c506a19549c4a260ab6fd5f45ab6e363de6c3f42472d439ac">CM_VectorCall</a>, <a href="#abd75237965fb9548c506a19549c4a260adc468760c02910f77bad7525bc66c334">CM_Widen</a>, <a href="#abd75237965fb9548c506a19549c4a260a058eacbd3c28e2ecec2af7db726ce527">CM_Widen_Reverse</a>, <a href="#a686506cbb75808c52247608065bc6596">CostKind</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f6975e193997c4e0183e96774a7cb39">llvm::find_singleton</a>, <a href="#ab0c7e793ca1b6b8a4f8c00a1bc1cb32f">foldTailWithEVL</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af84cce349a77262269fd3f6756f37a64afc2e3edeec59afcdc10f55205713f14b">llvm::TargetTransformInfo::GatherScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a>, <a href="#ad8398a35cd187d6a75b460fcf54b5236">getDivRemSpeculationCost</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a57207993e2fe6ec98912e8072e4600bc">llvm::InstructionCost::getInvalid</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12126a4bea94833696dc67e0431e829">llvm::getLoadStoreType</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a5fecba95c1ba20950ea8e2139127e621">llvm::TargetTransformInfo::getOperandInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a945c21ff70f310de538153db17e7b857">llvm::LoadInst::getPointerOperandType</a>, <a href="#a4e307866e6d65e87d1e6884b0d13306c">getReductionPatternCost</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aa05da2b94b366573d1651d5b163c521e">llvm::BranchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#ad1f0755693a05c2b008e9a576c3b162b">getVectorCallCost</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>, <a href="#af7844564539b9f0f917e8f2380a064b3">getWideningCost</a>, <a href="#af01e065313d5fcaba9570458faf32429">getWideningDecision</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af84cce349a77262269fd3f6756f37a64ad392556b3674a98332cc2938ba0bfeb7">llvm::TargetTransformInfo::Interleave</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a69df67c7d92481ae63a5d8017e96c716">llvm::RecurrenceDescriptor::isAnyOfRecurrenceKind</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a7e4be8b16fbd68c9045a388904044e01">llvm::BranchInst::isConditional</a>, <a href="#add43c346a11ae1deb49142ba968eb07e">isDivRemScalarWithPredication</a>, <a href="#a9819226a3ff242635fd99bf22b50bd97">isInLoopReduction</a>, <a href="#a61375f5189558cc261186f388d31fe92">isOptimizableIVTruncate</a>, <a href="#a0a96f040b7fc3eae004aa6dc2af8f522">isPredicatedInst</a>, <a href="#a9a6fbca8c965adeb8016a03ca3de2cac">isProfitableToScalarize</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>, <a href="#a5f5d6f7a1f29874d1e77a889510c879c">isScalarAfterVectorization</a>, <a href="#a20d7c96738b8f59692aec029895f8eb9">isUniformAfterVectorization</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a098a514da47d00e1176aa2e16eacfb70">llvm::ElementCount::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8cb1f2bd469f8a823857a1cf1447a0e3">llvm::llvm_unreachable_internal</a>, <a href="/web-llvm/docs/api/structs/llvm/histograminfo/#a18ad617fc2ebb0c359d7a7364a226926">llvm::HistogramInfo::Load</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#acf8c16eed89e5ee1a10b6dfc08a33b3a">llvm::PatternMatch::m_LogicalAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5cce7a41c7581ff15a23ab90eb3b403a">llvm::PatternMatch::m_LogicalOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af84cce349a77262269fd3f6756f37a64a6864311f985d160ad4bd46a9fbe4a4d4">llvm::TargetTransformInfo::Masked</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af84cce349a77262269fd3f6756f37a64a6adf97f83acf6453d4a6a4b1070f3754">llvm::TargetTransformInfo::None</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af84cce349a77262269fd3f6756f37a64a960b44c579bc2f6818d2daaf9e4c16f0">llvm::TargetTransformInfo::Normal</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#afa38851d75434d1476444ac93f94cb4ca9c0eecea29e9fa58e4dac7ee32b9b2ac">llvm::TargetTransformInfo::OK_AnyValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#afa38851d75434d1476444ac93f94cb4ca7aa61d9e9d33bdf28478754c69c59640">llvm::TargetTransformInfo::OK_UniformValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#a35372cc43a297f286fc6c679b14c61d2">PSE</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af84cce349a77262269fd3f6756f37a64a030aa94015bd11d183b897ddb541e4e3">llvm::TargetTransformInfo::Reversed</a>, <a href="#aadd9a9d699ede62468422c7cfab66e99">shouldConsiderInvariant</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ecaa9e18b2636661e341804da24971997df">llvm::TargetTransformInfo::SK_Splice</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272ca89f768b1267e3083b4eb05b4ab77e717">llvm::TargetTransformInfo::TCC_Free</a>, <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a>, <a href="#a598f8ca344de1cfac7a7985b212bb66b">TLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae5262cc0e3a55bc74891cb8751d3b188">llvm::toVectorTy</a> and <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a>.</p>


<p>Referenced by <a href="#ae4c50e6300599d50ba706c0d2b780502">expectedCost</a> and <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>.</p>

</div>
</div>

### getInterleavedAccessGroup() {#a5a1e4ba873eb1b26dd3649a530a3e36c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InterleaveGroup&lt; Instruction &gt; * llvm::LoopVectorizationCostModel::getInterleavedAccessGroup (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Instr)</td>
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

<p>Get the interleaved access group that <span class="doxyComputerOutput">Instr</span> belongs to.</p>

<p>Definition at line 1357 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Reference <a href="#a7a98f0c17229446d76997f158d896aad">InterleaveInfo</a>.</p>


<p>Referenced by <a href="#a0ac5df8f0304981180d602dacb13512c">collectValuesToIgnore</a>, <a href="#a5964ce9ba38fe5a4d372242ac39e3f1d">interleavedAccessCanBeWidened</a> and <a href="#ae8d11752355845a0e271111de7be7d3a">setCostBasedWideningDecision</a>.</p>

</div>
</div>

### getMaxSafeElements() {#a36ed7dfdcdc1bca9eea99fc741511590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; llvm::LoopVectorizationCostModel::getMaxSafeElements ()</td>
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

<p>Return maximum safe number of elements to be processed per vector iteration, which do not prevent store-load forwarding and are safe with regard to the memory dependencies.</p>


<p>Required for EVL-based VPlans to correctly calculate AVL (application vector length) as min(remaining AVL,
MaxSafeElements). TODO: need to consider adjusting cost model to use this value as a vectorization factor for EVL-based vectorization.</p>


<p>Definition at line 1477 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### getMinimalBitwidths() {#a9fe7595d60ab8e1f3ee1da0846838113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MapVector&lt; Instruction *, uint64_t &gt; &amp; llvm::LoopVectorizationCostModel::getMinimalBitwidths ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The smallest bitwidth each instruction can be represented with. The vector equivalents of these instructions should be truncated to this type.</p></dd>
</dl>


<p>Definition at line 1064 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### getReductionPatternCost() {#a4e307866e6d65e87d1e6884b0d13306c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; InstructionCost &gt; LoopVectorizationCostModel::getReductionPatternCost (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * VectorTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the cost of instructions in an inloop reduction pattern, if I is part of that pattern.</p>

<p>Definition at line 1549 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a686506cbb75808c52247608065bc6596">CostKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaa7dad289ea38506fb1c9b5b148405d0c">llvm::FMulAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a0d5c759e770c1c6032d077a1b9cf7172">llvm::RecurrenceDescriptor::getFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a13e877ef779ba7a0688081079f4f9b03">llvm::Type::getIntegerBitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e4b6546560e7fb6d37f6318d3236bb9">llvm::getMinMaxReductionIntrinsicOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a30ee597b72598bc7939d3a40d2a5ba20">llvm::RecurrenceDescriptor::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a89e9d5a5838c63159df1aed56f600ef1">llvm::RecurrenceDescriptor::getRecurrenceKind</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a4f29fefacd6bdd966f6ba021cc656a2f">llvm::RecurrenceDescriptor::getRecurrenceType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a2e987c6af902aad6baa39bd5b7ef322c">llvm::Value::hasOneUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#af08d243545b64f4b77161992d0e2366e">llvm::RecurrenceDescriptor::isMinMaxRecurrenceKind</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#ae01c5ced9fe2fe50f421ae121483ef04">llvm::InstructionCost::isValid</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2adca0e23c974dbb32019dccb22547bc">llvm::PatternMatch::m_Instruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a532515120d78196926b68c48460087ab">llvm::PatternMatch::m_Mul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab9dc78a306f2befc7dc7f1da8c9eaca2">llvm::PatternMatch::m_ZExtOrSExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af84cce349a77262269fd3f6756f37a64a6adf97f83acf6453d4a6a4b1070f3754">llvm::TargetTransformInfo::None</a>, <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a>, <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a>, <a href="#ad508b8cfa31c0e7a1ac8f9d733bb8eed">useOrderedReductions</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6609528bd67d5506a9bf9a2cce2d6f58">llvm::Instruction::user_back</a>.</p>


<p>Referenced by <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>, <a href="#ad1f0755693a05c2b008e9a576c3b162b">getVectorCallCost</a> and <a href="#a8178cc5e49d5251d7ca3413b8a434f8f">setVectorizedCallDecision</a>.</p>

</div>
</div>

### getSmallestAndWidestTypes() {#a1fa63b37ad2ac06f289e9962a3703e9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, unsigned &gt; LoopVectorizationCostModel::getSmallestAndWidestTypes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The size (in bits) of the smallest and widest types in the code that needs to be vectorized. We ignore values that remain scalar such as 64 bit loop indices.</p></dd>
</dl>


<p>Definition at line 1003 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a00a28a503636abdbedf080f3896b937c">ElementTypesInLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a5f64b98dd7b1371ddda6c24bf2163be6">llvm::RecurrenceDescriptor::getMinWidthCastToRecurrenceTypeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a4f29fefacd6bdd966f6ba021cc656a2f">llvm::RecurrenceDescriptor::getRecurrenceType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#a4384debcd154f44445005e6866afba4a">TheFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a0b91e092434338369b2e1995b87f0c5b">determineVPlanVF</a>.</p>

</div>
</div>

### getTailFoldingStyle() {#a738b994c87e0e816cf5f323e0e2b6c07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TailFoldingStyle llvm::LoopVectorizationCostModel::getTailFoldingStyle (bool IVUpdateMayOverflow=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Returns the <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdd">TailFoldingStyle</a> that is best for the current loop.</p>

<p>Definition at line 1407 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdda6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>


<p>Referenced by <a href="#a65ab4267c6c132d06451b5d97bc9ee83">computeMaxVF</a>, <a href="#aaf371382a45e4756dbc1753d162324ba">foldTailByMasking</a> and <a href="#ab0c7e793ca1b6b8a4f8c00a1bc1cb32f">foldTailWithEVL</a>.</p>

</div>
</div>

### getVectorCallCost() {#ad1f0755693a05c2b008e9a576c3b162b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost LoopVectorizationCostModel::getVectorCallCost (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Estimate cost of a call instruction CI if it were vectorized with factor VF.</p>


<p>Return the cost of the instruction, including scalarization overhead if it's needed.</p>


<p>Definition at line 1517 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ad027ea8803d83ee19b9a2e13aec6d655">llvm::CallBase::args</a>, <a href="#a686506cbb75808c52247608065bc6596">CostKind</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="#a4e307866e6d65e87d1e6884b0d13306c">getReductionPatternCost</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a5abced3ab870d7abf57f2b35a02cd041">getVectorIntrinsicCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11c66d01880f53332fc7ad53f565b039">llvm::getVectorIntrinsicIDForCall</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a08416fb970e8c177c7d78452d927c606">llvm::RecurrenceDescriptor::isFMulAddIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>, <a href="#a598f8ca344de1cfac7a7985b212bb66b">TLI</a> and <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a>.</p>


<p>Referenced by <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>.</p>

</div>
</div>

### getVectorIntrinsicCost() {#a5abced3ab870d7abf57f2b35a02cd041}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost LoopVectorizationCostModel::getVectorIntrinsicCost (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Estimate cost of an intrinsic call instruction CI if it were vectorized with factor VF.</p>


<p>Return the cost of the instruction, including scalarization overhead if it's needed.</p>


<p>Definition at line 1512 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ad027ea8803d83ee19b9a2e13aec6d655">llvm::CallBase::args</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a1161e5a4e753384aaba3a8e4533c4261">Arguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a686506cbb75808c52247608065bc6596">CostKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a21075305f0e463b24aafc2fb99514ace">llvm::Function::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11c66d01880f53332fc7ad53f565b039">llvm::getVectorIntrinsicIDForCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a83114915b4f7fec94a20efa3834a8250">maybeVectorizeType</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a05d5616e1422394b4d350c008b0cc5e0">llvm::FunctionType::param_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#aeae69a459419ec0bb738cdc73f4fc2a1">llvm::FunctionType::param_end</a>, <a href="#a598f8ca344de1cfac7a7985b212bb66b">TLI</a> and <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a>.</p>


<p>Referenced by <a href="#ad1f0755693a05c2b008e9a576c3b162b">getVectorCallCost</a> and <a href="#a8178cc5e49d5251d7ca3413b8a434f8f">setVectorizedCallDecision</a>.</p>

</div>
</div>

### getWideningCost() {#af7844564539b9f0f917e8f2380a064b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::LoopVectorizationCostModel::getWideningCost (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
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

<p>Return the vectorization cost for the given instruction <span class="doxyComputerOutput">I</span> and vector width <span class="doxyComputerOutput">VF</span>.</p>

<p>Definition at line 1191 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a098a514da47d00e1176aa2e16eacfb70">llvm::ElementCount::isVector</a>.</p>


<p>Referenced by <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>.</p>

</div>
</div>

### getWideningDecision() {#af01e065313d5fcaba9570458faf32429}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstWidening llvm::LoopVectorizationCostModel::getWideningDecision (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
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

<p>Return the cost model decision for the given instruction <span class="doxyComputerOutput">I</span> and vector width <span class="doxyComputerOutput">VF</span>.</p>


<p>Return CM_Unknown if this instruction did not pass through the cost modeling.</p>


<p>Definition at line 1176 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abd75237965fb9548c506a19549c4a260af974de6a8aba0481a82335fb93471a39">CM_Unknown</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a098a514da47d00e1176aa2e16eacfb70">llvm::ElementCount::isVector</a> and <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a>.</p>


<p>Referenced by <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>, <a href="#a5964ce9ba38fe5a4d372242ac39e3f1d">interleavedAccessCanBeWidened</a> and <a href="#ae8d11752355845a0e271111de7be7d3a">setCostBasedWideningDecision</a>.</p>

</div>
</div>

### hasPredStores() {#a0aa9aa5d09f2f30c5a62a4692e5a21e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::hasPredStores ()</td>
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



<p>Definition at line 1533 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### interleavedAccessCanBeWidened() {#a5964ce9ba38fe5a4d372242ac39e3f1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVectorizationCostModel::interleavedAccessCanBeWidened (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">I</span> is a memory instruction in an interleaved-group of memory accesses that can be vectorized with wide vector loads/stores and shuffles.</p>

<p>Definition at line 1348 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab8c8de8f62b5d2b27c4878d3effd7273">blockNeedsPredicationForAnyReason</a>, <a href="#abd75237965fb9548c506a19549c4a260af974de6a8aba0481a82335fb93471a39">CM_Unknown</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a5a1e4ba873eb1b26dd3649a530a3e36c">getInterleavedAccessGroup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4370c1523db2ede8d9791b76da2ab798">llvm::getLoadStoreAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12126a4bea94833696dc67e0431e829">llvm::getLoadStoreType</a>, <a href="#af01e065313d5fcaba9570458faf32429">getWideningDecision</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aa407c2e7d895ed29af8cc68563c03065">hasIrregularType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a85e3110b9fe54caf00fe4297d1b4f0b6">isAccessInterleaved</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="#af67062c22dbf5e0ab35164a778768476">isScalarEpilogueAllowed</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#adf8d8fb6f39b9c0cf21d55b7229d35e2">useMaskedInterleavedAccesses</a>.</p>


<p>Referenced by <a href="#ae8d11752355845a0e271111de7be7d3a">setCostBasedWideningDecision</a>.</p>

</div>
</div>

### invalidateCostModelingDecisions() {#a85afe07533e500a31222b17f80b540fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopVectorizationCostModel::invalidateCostModelingDecisions ()</td>
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

<p>Invalidates decisions already taken by the cost model.</p>

<p>Definition at line 1520 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### isAccessInterleaved() {#a85e3110b9fe54caf00fe4297d1b4f0b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::isAccessInterleaved (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Instr)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">Instr</span> belongs to any interleaved access group.</p>

<p>Definition at line 1351 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Reference <a href="#a7a98f0c17229446d76997f158d896aad">InterleaveInfo</a>.</p>


<p>Referenced by <a href="#a0ac5df8f0304981180d602dacb13512c">collectValuesToIgnore</a>, <a href="#a5964ce9ba38fe5a4d372242ac39e3f1d">interleavedAccessCanBeWidened</a> and <a href="#ae8d11752355845a0e271111de7be7d3a">setCostBasedWideningDecision</a>.</p>

</div>
</div>

### isDivRemScalarWithPredication() {#add43c346a11ae1deb49142ba968eb07e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::isDivRemScalarWithPredication (<a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> ScalarCost, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> SafeDivisorCost)</td>
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

<p>Given costs for both strategies, return true if the scalar predication lowering should be used for div/rem.</p>


<p>This incorporates an override option so it is not simply a cost comparison.</p>


<p>Definition at line 1309 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44a4e55599a5b5277382b14e6e8eb1f63ef">llvm::cl::BOU_FALSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44ad7c4bd83c337c86d34f6c2d8eba1e736">llvm::cl::BOU_TRUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44aa5bd521ebe67ddf0e90f1a9e540a6d43">llvm::cl::BOU_UNSET</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#ad69cf8bf5c6b79c5642327ecb6be38cd">ForceSafeDivisor</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a> and <a href="#ac864682b9dcdc0ce83df845bf6cfb2e8">isScalarWithPredication</a>.</p>

</div>
</div>

### isEpilogueVectorizationProfitable() {#a07db8a5919c9879e3327549f20cda2f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVectorizationCostModel::isEpilogueVectorizationProfitable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned IC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if epilogue vectorization is considered profitable, and false otherwise.</p>


<p><span class="doxyComputerOutput">VF</span> is the vectorization factor chosen for the original loop. <span class="doxyComputerOutput">Multiplier</span> is an aditional scaling factor applied to VF before comparing to EpilogueVectorizationMinVF.</p>


<p>Definition at line 1540 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a01070590fdc156c181654c2db7b9ddcc">EpilogueVectorizationMinVF</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#ab3df41ae1ed3978e3b825bc4dd50ae8d">getEstimatedRuntimeVF</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#aab9a9b0568c1c524f01499c7930b3bf9">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isFixed</a>, <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a> and <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a>.</p>

</div>
</div>

### isInLoopReduction() {#a9819226a3ff242635fd99bf22b50bd97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::isInLoopReduction (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi)</td>
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

<p>Returns true if the Phi is part of an inloop reduction.</p>

<p>Definition at line 1493 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>.</p>

</div>
</div>

### isLegalGatherOrScatter() {#aa650124eefba1fd45866d05306385129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::isLegalGatherOrScatter (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
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

<p>Returns true if the target machine can represent <span class="doxyComputerOutput">V</span> as a masked gather or scatter operation.</p>

<p>Definition at line 1284 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4370c1523db2ede8d9791b76da2ab798">llvm::getLoadStoreAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12126a4bea94833696dc67e0431e829">llvm::getLoadStoreType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a098a514da47d00e1176aa2e16eacfb70">llvm::ElementCount::isVector</a>, <a href="#a8c62d3e36a2d815cbfac5a1579ccbb01">LI</a> and <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a>.</p>


<p>Referenced by <a href="#ae8d11752355845a0e271111de7be7d3a">setCostBasedWideningDecision</a>.</p>

</div>
</div>

### isLegalMaskedLoad() {#a472c49074b0d81970f8eea07de4d7ad4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::isLegalMaskedLoad (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DataType, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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

<p>Returns true if the target machine supports masked load operation for the given <span class="doxyComputerOutput">DataType</span> and kind of access to <span class="doxyComputerOutput">Ptr</span>.</p>

<p>Definition at line 1277 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a>.</p>


<p>Referenced by <a href="#ac864682b9dcdc0ce83df845bf6cfb2e8">isScalarWithPredication</a>.</p>

</div>
</div>

### isLegalMaskedStore() {#a8c25146329f69e026508656cfb1280fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::isLegalMaskedStore (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * DataType, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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

<p>Returns true if the target machine supports masked store operation for the given <span class="doxyComputerOutput">DataType</span> and kind of access to <span class="doxyComputerOutput">Ptr</span>.</p>

<p>Definition at line 1270 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a>.</p>


<p>Referenced by <a href="#ac864682b9dcdc0ce83df845bf6cfb2e8">isScalarWithPredication</a>.</p>

</div>
</div>

### isOptimizableIVTruncate() {#a61375f5189558cc261186f388d31fe92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::isOptimizableIVTruncate (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
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

<p>Return True if instruction <span class="doxyComputerOutput">I</span> is an optimizable truncate whose operand is an induction variable.</p>


<p>Such a truncate will be removed by adding a new induction variable with the destination type.</p>


<p>Definition at line 1225 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae5262cc0e3a55bc74891cb8751d3b188">llvm::toVectorTy</a> and <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a>.</p>


<p>Referenced by <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>.</p>

</div>
</div>

### isPredicatedInst() {#a0a96f040b7fc3eae004aa6dc2af8f522}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVectorizationCostModel::isPredicatedInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">I</span> is an instruction that needs to be predicated at runtime.</p>


<p>The result is independent of the predication mechanism. Superset of instructions that return true for isScalarWithPredication.</p>


<p>Definition at line 1331 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab8c8de8f62b5d2b27c4878d3effd7273">blockNeedsPredicationForAnyReason</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2922c0c507ccec5bea4642aff9e2e328">llvm::getLoadStorePointerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8601ff0320b6e29a13a2194200853425">llvm::isSafeToSpeculativelyExecute</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a>.</p>


<p>Referenced by <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>, <a href="#ac864682b9dcdc0ce83df845bf6cfb2e8">isScalarWithPredication</a> and <a href="#aadd9a9d699ede62468422c7cfab66e99">shouldConsiderInvariant</a>.</p>

</div>
</div>

### isProfitableToScalarize() {#a9a6fbca8c965adeb8016a03ca3de2cac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::isProfitableToScalarize (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if it is more profitable to scalarize instruction <span class="doxyComputerOutput">I</span> for vectorization factor <span class="doxyComputerOutput">VF</span>.</p></dd>
</dl>


<p>Definition at line 1070 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a098a514da47d00e1176aa2e16eacfb70">llvm::ElementCount::isVector</a> and <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a>.</p>


<p>Referenced by <a href="#aa8c00664c6be2042407f13e4fcad950b">canTruncateToMinimalBitwidth</a> and <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>.</p>

</div>
</div>

### isScalarAfterVectorization() {#a5f5d6f7a1f29874d1e77a889510c879c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::isScalarAfterVectorization (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
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

<p>Returns true if <span class="doxyComputerOutput">I</span> is known to be scalar after vectorization.</p>

<p>Definition at line 1104 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a> and <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a>.</p>


<p>Referenced by <a href="#a91466f7a82e967ed765e6d876415a3b7">calculateRegisterUsage</a>, <a href="#aa8c00664c6be2042407f13e4fcad950b">canTruncateToMinimalBitwidth</a>, <a href="#afcbf4a19be078644e784b539379d59b7">collectInstsToScalarize</a> and <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>.</p>

</div>
</div>

### isScalarEpilogueAllowed() {#af67062c22dbf5e0ab35164a778768476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::isScalarEpilogueAllowed ()</td>
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

<p>Returns true if a scalar epilogue is not allowed due to optsize or a loop hint annotation.</p>

<p>Definition at line 1402 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab5d4f35a197e7b0f2320bdbbf518bd9da65f7ef37c3a0cd826b5e361e8cf32cf7">llvm::CM_ScalarEpilogueAllowed</a>.</p>


<p>Referenced by <a href="#a5964ce9ba38fe5a4d372242ac39e3f1d">interleavedAccessCanBeWidened</a>, <a href="#a913ab9c8291000dd3a1c3739194b03e4">requiresScalarEpilogue</a> and <a href="#af9f62350ccdebd24858be552f3fc051c">selectInterleaveCount</a>.</p>

</div>
</div>

### isScalarWithPredication() {#ac864682b9dcdc0ce83df845bf6cfb2e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVectorizationCostModel::isScalarWithPredication (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">I</span> is an instruction which requires predication and for which our chosen predication strategy is scalarization (i.e.</p>


<p>we don't have an alternate strategy such as masking available). <span class="doxyComputerOutput">VF</span> is the vectorization factor that will be used to vectorize <span class="doxyComputerOutput">I</span>.</p>


<p>Definition at line 1326 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#abd75237965fb9548c506a19549c4a260a03c0934d38787b1773c050deee484126">CM_Scalarize</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="#ad8398a35cd187d6a75b460fcf54b5236">getDivRemSpeculationCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4370c1523db2ede8d9791b76da2ab798">llvm::getLoadStoreAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2922c0c507ccec5bea4642aff9e2e328">llvm::getLoadStorePointerOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12126a4bea94833696dc67e0431e829">llvm::getLoadStoreType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#add43c346a11ae1deb49142ba968eb07e">isDivRemScalarWithPredication</a>, <a href="#a472c49074b0d81970f8eea07de4d7ad4">isLegalMaskedLoad</a>, <a href="#a8c25146329f69e026508656cfb1280fa">isLegalMaskedStore</a>, <a href="#a0a96f040b7fc3eae004aa6dc2af8f522">isPredicatedInst</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a098a514da47d00e1176aa2e16eacfb70">llvm::ElementCount::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a>.</p>


<p>Referenced by <a href="#afcbf4a19be078644e784b539379d59b7">collectInstsToScalarize</a>, <a href="#a59a6dd7531c8683174f886ff7698cc63">memoryInstructionCanBeWidened</a> and <a href="#ae8d11752355845a0e271111de7be7d3a">setCostBasedWideningDecision</a>.</p>

</div>
</div>

### isUniformAfterVectorization() {#a20d7c96738b8f59692aec029895f8eb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::isUniformAfterVectorization (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
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

<p>Returns true if <span class="doxyComputerOutput">I</span> is known to be uniform after vectorization.</p>

<p>Definition at line 1084 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a> and <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a>.</p>


<p>Referenced by <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a> and <a href="#a8178cc5e49d5251d7ca3413b8a434f8f">setVectorizedCallDecision</a>.</p>

</div>
</div>

### memoryInstructionCanBeWidened() {#a59a6dd7531c8683174f886ff7698cc63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVectorizationCostModel::memoryInstructionCanBeWidened (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">I</span> is a memory instruction with consecutive memory access that can be widened.</p>

<p>Definition at line 1343 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2922c0c507ccec5bea4642aff9e2e328">llvm::getLoadStorePointerOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12126a4bea94833696dc67e0431e829">llvm::getLoadStoreType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aa407c2e7d895ed29af8cc68563c03065">hasIrregularType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#ac864682b9dcdc0ce83df845bf6cfb2e8">isScalarWithPredication</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="#ae8d11752355845a0e271111de7be7d3a">setCostBasedWideningDecision</a>.</p>

</div>
</div>

### requiresScalarEpilogue() {#a913ab9c8291000dd3a1c3739194b03e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::requiresScalarEpilogue (bool IsVectorizing)</td>
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

<p>Returns true if we're required to use a scalar epilogue for at least the final iteration of the original loop.</p>

<p>Definition at line 1363 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#af7af1b4bf03205c80dcba0a6324c4f21">EnableEarlyExitVectorization</a>, <a href="#a7a98f0c17229446d76997f158d896aad">InterleaveInfo</a>, <a href="#af67062c22dbf5e0ab35164a778768476">isScalarEpilogueAllowed</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a>.</p>


<p>Referenced by <a href="#a0ac5df8f0304981180d602dacb13512c">collectValuesToIgnore</a>, <a href="#a08599d322c8160c0412192455bbfb3c2">requiresScalarEpilogue</a> and <a href="#af9f62350ccdebd24858be552f3fc051c">selectInterleaveCount</a>.</p>

</div>
</div>

### requiresScalarEpilogue() {#a08599d322c8160c0412192455bbfb3c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::requiresScalarEpilogue (<a href="/web-llvm/docs/api/structs/llvm/vfrange">VFRange</a> Range)</td>
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

<p>Returns true if we're required to use a scalar epilogue for at least the final iteration of the original loop for all VFs in <span class="doxyComputerOutput">Range</span>.</p>


<p>A scalar epilogue must either be required for all VFs in <span class="doxyComputerOutput">Range</span> or for none.</p>


<p>Definition at line 1389 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="#a913ab9c8291000dd3a1c3739194b03e4">requiresScalarEpilogue</a>.</p>

</div>
</div>

### runtimeChecksRequired() {#aad6239ca8b51657f5ebdbd6e51e6ea90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVectorizationCostModel::runtimeChecksRequired ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if runtime checks are required for vectorization, and false otherwise.</p></dd>
</dl>


<p>Definition at line 990 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a8b0171a0d29e72189ffad26b9770c464">ORE</a>, <a href="#a35372cc43a297f286fc6c679b14c61d2">PSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab425bb10a0f4af749bbb29aa07fc6854">llvm::reportVectorizationFailure</a> and <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a>.</p>


<p>Referenced by <a href="#a65ab4267c6c132d06451b5d97bc9ee83">computeMaxVF</a>.</p>

</div>
</div>

### selectInterleaveCount() {#af9f62350ccdebd24858be552f3fc051c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LoopVectorizationCostModel::selectInterleaveCount (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> LoopCost)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The desired interleave count. If interleave count has been specified by metadata it will be returned. Otherwise, the interleave count is computed and returned. VF and LoopCost are the selected vectorization factor and the cost of the selected VF.</p></dd>
</dl>


<p>Definition at line 1009 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae22967d11b695d268992470debfae4b2">llvm::bit_floor</a>, <a href="#a91466f7a82e967ed765e6d876415a3b7">calculateRegisterUsage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a8122656ed2c776067b43d9ae34ccecb6">EnableIndVarRegisterHeur</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a99a396adb2c0f9fb93b7ff8ea8b2e2ef">EnableLoadStoreRuntimeInterleave</a>, <a href="#ae4c50e6300599d50ba706c0d2b780502">expectedCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ab0c7e793ca1b6b8a4f8c00a1bc1cb32f">foldTailWithEVL</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aee1082071c43958a6ef5e6e9f665ae4a">ForceTargetMaxScalarInterleaveFactor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#ade5aad46b91dc51c831acf1e69ee9863">ForceTargetMaxVectorInterleaveFactor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a62baadf3a5bf03eddf58bf048724acb1">ForceTargetNumScalarRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a7d952aa72676eecd8065aa2c29ea458c">ForceTargetNumVectorRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#ab3df41ae1ed3978e3b825bc4dd50ae8d">getEstimatedRuntimeVF</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a84375e6536d9214c7895013078055aff">getSmallBestKnownTC</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a9b642067999075ba996ecdee40b52b68">llvm::InstructionCost::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>, <a href="#af67062c22dbf5e0ab35164a778768476">isScalarEpilogueAllowed</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#ae01c5ced9fe2fe50f421ae121483ef04">llvm::InstructionCost::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a098a514da47d00e1176aa2e16eacfb70">llvm::ElementCount::isVector</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#ae75965df4671fa34c6ffc5a6e404843a">MaxNestedScalarReductionIC</a>, <a href="#a35372cc43a297f286fc6c679b14c61d2">PSE</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a175f1f53cc9c3619505ffbd13aca087f">Reduction</a>, <a href="#a913ab9c8291000dd3a1c3739194b03e4">requiresScalarEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a71899f6c73fcc8e2fc977dadc1fb1520">SmallLoopCost</a>, <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a> and <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### selectUserVectorizationFactor() {#a885ad9ea73b97e3154433e5c37fefa99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::selectUserVectorizationFactor (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> UserVF)</td>
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

<p>Setup cost-based decisions for user vectorization factor.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the UserVF is a feasible VF to be chosen.</p></dd>
</dl>


<p>Definition at line 994 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="#afcbf4a19be078644e784b539379d59b7">collectInstsToScalarize</a>, <a href="#ab4a3f06ac8f2aff57b864c2d8ace97d8">collectUniformsAndScalars</a>, <a href="#ae4c50e6300599d50ba706c0d2b780502">expectedCost</a> and <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#ae01c5ced9fe2fe50f421ae121483ef04">llvm::InstructionCost::isValid</a>.</p>

</div>
</div>

### setCallWideningDecision() {#ab8e5bf6d340d3b3f704b6398996ae51c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopVectorizationCostModel::setCallWideningDecision (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="#abd75237965fb9548c506a19549c4a260">InstWidening</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Variant, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IID, std::optional&lt; unsigned &gt; MaskPos, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> Cost)</td>
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



<p>Definition at line 1207 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>.</p>


<p>Referenced by <a href="#a8178cc5e49d5251d7ca3413b8a434f8f">setVectorizedCallDecision</a>.</p>

</div>
</div>

### setCostBasedWideningDecision() {#ae8d11752355845a0e271111de7be7d3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVectorizationCostModel::setCostBasedWideningDecision (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> access instruction may be vectorized in more than one way.</p>


<p>Form of instruction after vectorization depends on cost. This function takes cost-based decisions for Load/Store instructions and collects them in a map. This decisions map is used for building the lists of loop-uniform and loop-scalar instructions. The calculated cost is saved with widening decision in order to avoid redundant calculations.</p>


<p>Definition at line 1018 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#abd75237965fb9548c506a19549c4a260ae849d400780f51424bc4e4c26ddf3000">CM_GatherScatter</a>, <a href="#abd75237965fb9548c506a19549c4a260a3a2a7904b0c4a7f4c55939e457bcc971">CM_Interleave</a>, <a href="#abd75237965fb9548c506a19549c4a260a03c0934d38787b1773c050deee484126">CM_Scalarize</a>, <a href="#abd75237965fb9548c506a19549c4a260af974de6a8aba0481a82335fb93471a39">CM_Unknown</a>, <a href="#abd75237965fb9548c506a19549c4a260adc468760c02910f77bad7525bc66c334">CM_Widen</a>, <a href="#abd75237965fb9548c506a19549c4a260a058eacbd3c28e2ecec2af7db726ce527">CM_Widen_Reverse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#aaf371382a45e4756dbc1753d162324ba">foldTailByMasking</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="#a5a1e4ba873eb1b26dd3649a530a3e36c">getInterleavedAccessGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a57207993e2fe6ec98912e8072e4600bc">llvm::InstructionCost::getInvalid</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2922c0c507ccec5bea4642aff9e2e328">llvm::getLoadStorePointerOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12126a4bea94833696dc67e0431e829">llvm::getLoadStoreType</a>, <a href="#af01e065313d5fcaba9570458faf32429">getWideningDecision</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#a5964ce9ba38fe5a4d372242ac39e3f1d">interleavedAccessCanBeWidened</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a85e3110b9fe54caf00fe4297d1b4f0b6">isAccessInterleaved</a>, <a href="#aa650124eefba1fd45866d05306385129">isLegalGatherOrScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>, <a href="#ac864682b9dcdc0ce83df845bf6cfb2e8">isScalarWithPredication</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="#a59a6dd7531c8683174f886ff7698cc63">memoryInstructionCanBeWidened</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#abc1b952dd1661ccba4f999610bf9732e">setWideningDecision</a>, <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a> and <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a>.</p>


<p>Referenced by <a href="#ab4a3f06ac8f2aff57b864c2d8ace97d8">collectUniformsAndScalars</a>.</p>

</div>
</div>

### setTailFoldingStyles() {#ab8eb89837d2853e4853ea14379ae3972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopVectorizationCostModel::setTailFoldingStyles (bool IsScalableVF, unsigned UserIC)</td>
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

<p>Selects and saves <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdd">TailFoldingStyle</a> for 2 options - if IV update may overflow or not.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsScalableVF</td>
<td class="doxyParamItemDescription"><p>true if scalable vector factors enabled.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UserIC</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/user">User</a> specific interleave count.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1418 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdda6ae67872a709ea2e3175802518fc4e71">llvm::DataWithEVL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bddadfca60932ecfe430f86d4ecde04e13ab">llvm::DataWithoutLaneMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ef0a19ea2267182eb0da4f6e191b59b">llvm::EnableVPlanNativePath</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a8959791a22c7d3cfb4136777fd244535">ForceTailFoldingStyle</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada31142763d41520644d228c139a4bdda6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a>.</p>


<p>Referenced by <a href="#a65ab4267c6c132d06451b5d97bc9ee83">computeMaxVF</a>.</p>

</div>
</div>

### setVectorizedCallDecision() {#a8178cc5e49d5251d7ca3413b8a434f8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVectorizationCostModel::setVectorizedCallDecision (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A call may be vectorized in different ways depending on whether we have vectorized variants available and whether the target supports masking.</p>


<p>This function analyzes all calls in the function at the supplied VF, makes a decision based on the costs of available options, and stores that decision in a map for use in planning and plan execution.</p>


<p>Definition at line 1025 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ad027ea8803d83ee19b9a2e13aec6d655">llvm::CallBase::args</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abd75237965fb9548c506a19549c4a260a679b46cebdf2f87b9efd0413c960314a">CM_IntrinsicCall</a>, <a href="#abd75237965fb9548c506a19549c4a260a03c0934d38787b1773c050deee484126">CM_Scalarize</a>, <a href="#abd75237965fb9548c506a19549c4a260ab6fd5f45ab6e363de6c3f42472d439ac">CM_VectorCall</a>, <a href="#a686506cbb75808c52247608065bc6596">CostKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scevconstant/#a6caf7f3a0a4303e4c0bc06ed8e205126">llvm::SCEVConstant::getAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a209a615a3a32241323420cca24b5520a">llvm::Module::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a57207993e2fe6ec98912e8072e4600bc">llvm::InstructionCost::getInvalid</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getKnownMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vfdatabase/#ab3e99bee894f145998d620d3d2a2f900">llvm::VFDatabase::getMappings</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4ba3a5be6c0e9b9e8a525de055836733">llvm::Instruction::getModule</a>, <a href="#a4e307866e6d65e87d1e6884b0d13306c">getReductionPatternCost</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a30bd18ac905eacf3601bc6a553a9ff49">llvm::ScalarEvolution::getSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a5abced3ab870d7abf57f2b35a02cd041">getVectorIntrinsicCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11c66d01880f53332fc7ad53f565b039">llvm::getVectorIntrinsicIDForCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39adf3e3249ad10ccf5bf901eb83c105cc3">llvm::GlobalPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a08416fb970e8c177c7d78452d927c606">llvm::RecurrenceDescriptor::isFMulAddIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a1fb374eb65dcf7cd3d1671efb2616f76">llvm::CallBase::isNoBuiltin</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a991f269cde2e7fbcb254ef371efc8d1a">llvm::ElementCount::isScalar</a>, <a href="#a20d7c96738b8f59692aec029895f8eb9">isUniformAfterVectorization</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a098a514da47d00e1176aa2e16eacfb70">llvm::ElementCount::isVector</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a35fedf4db6d756bd82501607f93c1e79aab5fb650050f184fa7c19c26abde5226">llvm::Intrinsic::not_intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a16454c62ab71c641dedda0971980c9d5">llvm::OMP_Linear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39acbf35bbdad5d09f9072d0e83e78e90e4">llvm::OMP_Uniform</a>, <a href="#a35372cc43a297f286fc6c679b14c61d2">PSE</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#ab8e5bf6d340d3b3f704b6398996ae51c">setCallWideningDecision</a>, <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a>, <a href="#a598f8ca344de1cfac7a7985b212bb66b">TLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae5262cc0e3a55bc74891cb8751d3b188">llvm::toVectorTy</a>, <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">llvm::Vector</a>.</p>


<p>Referenced by <a href="#ab4a3f06ac8f2aff57b864c2d8ace97d8">collectUniformsAndScalars</a>.</p>

</div>
</div>

### setWideningDecision() {#abc1b952dd1661ccba4f999610bf9732e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopVectorizationCostModel::setWideningDecision (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="#abd75237965fb9548c506a19549c4a260">InstWidening</a> W, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> Cost)</td>
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

<p>Save vectorization decision <span class="doxyComputerOutput">W</span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a></span> taken by the cost model for instruction <span class="doxyComputerOutput">I</span> and vector width <span class="doxyComputerOutput">VF</span>.</p>

<p>Definition at line 1139 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a098a514da47d00e1176aa2e16eacfb70">llvm::ElementCount::isVector</a>.</p>


<p>Referenced by <a href="#ae8d11752355845a0e271111de7be7d3a">setCostBasedWideningDecision</a>.</p>

</div>
</div>

### setWideningDecision() {#a9c44a42299ed9e7e97200271b00e0c7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoopVectorizationCostModel::setWideningDecision (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/interleavegroup">InterleaveGroup</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &gt; * Grp, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="#abd75237965fb9548c506a19549c4a260">InstWidening</a> W, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> Cost)</td>
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

<p>Save vectorization decision <span class="doxyComputerOutput">W</span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a19921a3ceb99548f498d3df118eda9ed">Cost</a></span> taken by the cost model for interleaving group <span class="doxyComputerOutput">Grp</span> and vector width <span class="doxyComputerOutput">VF</span>.</p>

<p>Definition at line 1147 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abd75237965fb9548c506a19549c4a260a3a2a7904b0c4a7f4c55939e457bcc971">CM_Interleave</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavegroup/#a46f3b431a3121fdf53608a283bf4efec">llvm::InterleaveGroup&lt; InstTy &gt;::getFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavegroup/#a8ceaf9f0ed35c1a277261b29c97e4c95">llvm::InterleaveGroup&lt; InstTy &gt;::getInsertPos</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavegroup/#a5085afe1fa721f3ef5bf09ca7fc7537c">llvm::InterleaveGroup&lt; InstTy &gt;::getMember</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavegroup/#af81c826ee51addc3321e4ef1c1934696">llvm::InterleaveGroup&lt; InstTy &gt;::getNumMembers</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a098a514da47d00e1176aa2e16eacfb70">llvm::ElementCount::isVector</a>.</p>

</div>
</div>

### shouldConsiderInvariant() {#aadd9a9d699ede62468422c7cfab66e99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVectorizationCostModel::shouldConsiderInvariant (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> should be considered invariant and if it is trivially hoistable.</p>

<p>Definition at line 1555 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a0a96f040b7fc3eae004aa6dc2af8f522">isPredicatedInst</a>, <a href="#a4714bf2e30b65997d553264e047245f1">Legal</a> and <a href="#a664dc60e31d9203d66c9d7a49787b63f">TheLoop</a>.</p>


<p>Referenced by <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>.</p>

</div>
</div>

### useOrderedReductions() {#ad508b8cfa31c0e7a1ac8f9d733bb8eed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::useOrderedReductions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor">RecurrenceDescriptor</a> &amp; RdxDesc)</td>
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

<p>Returns true if we should use strict in-order reductions for the given RdxDesc.</p>


<p>This is true if the -enable-strict-reductions flag is passed, the IsOrdered flag of RdxDesc is set and we do not allow reordering of FP operations.</p>


<p>Definition at line 1057 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="#a35e67974daa692cfd961904c151ad33d">Hints</a> and <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a8dad5abc2bd929acd8391643b2dbe4c5">llvm::RecurrenceDescriptor::isOrdered</a>.</p>


<p>Referenced by <a href="#a06f5d9725a2b1f7b06e8bf51f7d31417">collectElementTypesForWidening</a>, <a href="#a12d2850f420726c4acb262b626e95b7d">collectInLoopReductions</a> and <a href="#a4e307866e6d65e87d1e6884b0d13306c">getReductionPatternCost</a>.</p>

</div>
</div>

### usePredicatedReductionSelect() {#a23c31233960bfc62d1cc93bb4a5f5148}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::usePredicatedReductionSelect (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * PhiTy)</td>
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

<p>Returns true if the predicated reduction select should be used to set the incoming value for the reduction phi.</p>

<p>Definition at line 1499 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>References <a href="#ab0c7e793ca1b6b8a4f8c00a1bc1cb32f">foldTailWithEVL</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a927ef1cfd7c981c5b9b9e8c67b1d13c3">PreferPredicatedReductionSelect</a> and <a href="#a3dfa67eb67a32ca048b4af8fae5c898d">TTI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### collectLoopScalars() {#ae8c30022b972dbde1cb1f5cfee7a5864}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVectorizationCostModel::collectLoopScalars (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect the instructions that are scalar after vectorization.</p>


<p>An instruction is scalar if it is known to be uniform or will be scalarized during vectorization. collectLoopScalars should only add non-uniform nodes to the list if they are used by a load/store instruction that is marked as CM_Scalarize. Non-uniform scalarized instructions will be represented by VF values in the vectorized loop, each corresponding to an iteration of the original scalar loop.</p>


<p>Definition at line 1708 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### collectLoopUniforms() {#a1d4a948b9b7deacfddf01d2d6e3a7a7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopVectorizationCostModel::collectLoopUniforms (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect the instructions that are uniform after vectorization.</p>


<p>An instruction is uniform if we represent it with a single scalar value in the vectorized loop corresponding to each vector iteration. Examples of uniform instructions include pointer operands of consecutive or interleaved memory accesses. Note that although uniformity implies an instruction will be scalar, the reverse is not true. In general, a scalarized instruction will be represented by VF scalar values in the vectorized loop, each corresponding to an iteration of the original scalar loop.</p>


<p>Definition at line 1699 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### computeFeasibleMaxVF() {#a9956319d31294a80a256a76b4228b4b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedScalableVFPair LoopVectorizationCostModel::computeFeasibleMaxVF (unsigned MaxTripCount, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> UserVF, bool FoldTailByMasking)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An upper bound for the vectorization factors for both fixed and scalable vectorization, where the minimum-known number of elements is a power-of-2 larger than zero. If scalable vectorization is disabled or unsupported, then the scalable part will be equal to ElementCount::getScalable(0).</p></dd>
</dl>


<p>Definition at line 1565 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### computePredInstDiscount() {#a92dbc62025bcd5ac5d0f4219e6e970d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost LoopVectorizationCostModel::computePredInstDiscount (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * PredInst, <a href="/web-llvm/docs/api/classes/llvm/densemap">ScalarCostsTy</a> &amp; ScalarCosts, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the expected difference in cost from scalarizing the expression feeding a predicated instruction <span class="doxyComputerOutput">PredInst</span>.</p>


<p>The instructions to scalarize and their scalar costs are collected in <span class="doxyComputerOutput">ScalarCosts</span>. A non-negative return value implies the expression will be scalarized. Currently, only single-use chains are considered for scalarization.</p>


<p>Definition at line 1686 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### filterExtractingOperands() {#a2e9dd76b56349c25f0d718e50b9f6efd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; Value *, 4 &gt; llvm::LoopVectorizationCostModel::filterExtractingOperands (<a href="/web-llvm/docs/api/classes/llvm/user/#a917548288129e24325af275795e4622f">Instruction::op_range</a> Ops, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
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

<p>Returns a range containing only operands needing to be extracted.</p>

<p>Definition at line 1741 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### getConsecutiveMemOpCost() {#aef7540a23106bdfe677828ff5085f250}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost LoopVectorizationCostModel::getConsecutiveMemOpCost (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost computation for widening instruction <span class="doxyComputerOutput">I</span> with consecutive memory access.</p>

<p>Definition at line 1600 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### getGatherScatterCost() {#afc8952751e71e49709fc1144d1e0e92f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost LoopVectorizationCostModel::getGatherScatterCost (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost computation for Gather/Scatter instruction.</p>

<p>Definition at line 1596 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### getInterleaveGroupCost() {#a0a00ba77387558dbf2dc3ed28b944b34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost LoopVectorizationCostModel::getInterleaveGroupCost (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost computation for interleaving group of memory instructions.</p>

<p>Definition at line 1593 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### getMaximizedVFForTarget() {#a11b8d73e606d42d9c0d5287b49d5b1da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElementCount LoopVectorizationCostModel::getMaximizedVFForTarget (unsigned MaxTripCount, unsigned SmallestType, unsigned WidestType, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> MaxSafeVF, bool FoldTailByMasking)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the maximized element count based on the targets vector registers and the loop trip-count, but limited to a maximum safe VF. This is a helper function of computeFeasibleMaxVF.</p></dd>
</dl>


<p>Definition at line 1572 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### getMaxLegalScalableVF() {#a09c45adebc2c4fa82cce2d0df576c9be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElementCount LoopVectorizationCostModel::getMaxLegalScalableVF (unsigned MaxSafeElements)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the maximum legal scalable VF, based on the safe max number of elements.</p></dd>
</dl>


<p>Definition at line 1584 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### getMemInstScalarizationCost() {#ad13565f2d563b87570fa74576b116b4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost LoopVectorizationCostModel::getMemInstScalarizationCost (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost computation for scalarized memory instruction.</p>

<p>Definition at line 1590 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### getMemoryInstructionCost() {#a2cc23e9a1f8dd15e9d17c608fb90814a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost LoopVectorizationCostModel::getMemoryInstructionCost (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate vectorization cost of memory instruction <span class="doxyComputerOutput">I</span>.</p>

<p>Definition at line 1587 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### getScalarizationOverhead() {#abcf975438d3e87e38b4f0ae8438cd092}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost LoopVectorizationCostModel::getScalarizationOverhead (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Estimate the overhead of scalarizing an instruction.</p>


<p>This is a convenience wrapper for the type-based getScalarizationOverhead API.</p>


<p>Definition at line 1610 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### getUniformMemOpCost() {#a7749fffb38d72b07b8a3625e720c0de5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost LoopVectorizationCostModel::getUniformMemOpCost (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The cost calculation for Load/Store instruction <span class="doxyComputerOutput">I</span> with uniform pointer - Load: scalar load + broadcast.</p>


<p>Store: scalar store + (loop invariant value stored? 0 : extract of last element)</p>


<p>Definition at line 1606 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### isScalableVectorizationAllowed() {#a8ae934ae181e40f3a0b7e7658ddb5cae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVectorizationCostModel::isScalableVectorizationAllowed ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if scalable vectorization is supported and enabled.</p>


<p>Caches the result to avoid repeated debug dumps for repeated queries.</p>


<p>Definition at line 1580 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### needsExtract() {#a60e07d5fe91e94f05d201cb4e285c4ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizationCostModel::needsExtract (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
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

<p>Returns true if <span class="doxyComputerOutput">V</span> is expected to be vectorized and it needs to be extracted.</p>

<p>Definition at line 1724 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### useEmulatedMaskMemRefHack() {#a27101a97ecd70055be42f41c52cd5f69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LoopVectorizationCostModel::useEmulatedMaskMemRefHack (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if an artificially high cost for emulated masked memrefs should be used.</p>

<p>Definition at line 1615 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AC {#aba357162dc28acb3a399731e1e397614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache* llvm::LoopVectorizationCostModel::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assumption cache.</p>

<p>Definition at line 1770 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a0ac5df8f0304981180d602dacb13512c">collectValuesToIgnore</a> and <a href="#a405e73f32c9044b8b14648b62cb2ef30">LoopVectorizationCostModel</a>.</p>

</div>
</div>

### CostKind {#a686506cbb75808c52247608065bc6596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TTI::TargetCostKind llvm::LoopVectorizationCostModel::CostKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The kind of cost that we are calculating.</p>

<p>Definition at line 1794 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#ad8398a35cd187d6a75b460fcf54b5236">getDivRemSpeculationCost</a>, <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>, <a href="#a4e307866e6d65e87d1e6884b0d13306c">getReductionPatternCost</a>, <a href="#ad1f0755693a05c2b008e9a576c3b162b">getVectorCallCost</a>, <a href="#a5abced3ab870d7abf57f2b35a02cd041">getVectorIntrinsicCost</a>, <a href="#a405e73f32c9044b8b14648b62cb2ef30">LoopVectorizationCostModel</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#adeb41c907ebde15846bc643325909f95">processLoopInVPlanNativePath</a> and <a href="#a8178cc5e49d5251d7ca3413b8a434f8f">setVectorizedCallDecision</a>.</p>

</div>
</div>

### DB {#a58fd764accfd06df487cc6ec43d4f5fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DemandedBits* llvm::LoopVectorizationCostModel::DB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Demanded bits analysis.</p>

<p>Definition at line 1767 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a405e73f32c9044b8b14648b62cb2ef30">LoopVectorizationCostModel</a>.</p>

</div>
</div>

### ElementTypesInLoop {#a00a28a503636abdbedf080f3896b937c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Type *, 16&gt; llvm::LoopVectorizationCostModel::ElementTypesInLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All element types found in the loop.</p>

<p>Definition at line 1791 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a06f5d9725a2b1f7b06e8bf51f7d31417">collectElementTypesForWidening</a> and <a href="#a1fa63b37ad2ac06f289e9962a3703e9e">getSmallestAndWidestTypes</a>.</p>

</div>
</div>

### Hints {#a35e67974daa692cfd961904c151ad33d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopVectorizeHints* llvm::LoopVectorizationCostModel::Hints</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> Vectorize Hint.</p>

<p>Definition at line 1778 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a405e73f32c9044b8b14648b62cb2ef30">LoopVectorizationCostModel</a> and <a href="#ad508b8cfa31c0e7a1ac8f9d733bb8eed">useOrderedReductions</a>.</p>

</div>
</div>

### InterleaveInfo {#a7a98f0c17229446d76997f158d896aad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InterleavedAccessInfo&amp; llvm::LoopVectorizationCostModel::InterleaveInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The interleave access information contains groups of interleaved accesses with the same stride and close to each other.</p>

<p>Definition at line 1782 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a65ab4267c6c132d06451b5d97bc9ee83">computeMaxVF</a>, <a href="#a5a1e4ba873eb1b26dd3649a530a3e36c">getInterleavedAccessGroup</a>, <a href="#a85e3110b9fe54caf00fe4297d1b4f0b6">isAccessInterleaved</a>, <a href="#a405e73f32c9044b8b14648b62cb2ef30">LoopVectorizationCostModel</a> and <a href="#a913ab9c8291000dd3a1c3739194b03e4">requiresScalarEpilogue</a>.</p>

</div>
</div>

### Legal {#a4714bf2e30b65997d553264e047245f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopVectorizationLegality* llvm::LoopVectorizationCostModel::Legal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vectorization legality.</p>

<p>Definition at line 1758 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#ab8c8de8f62b5d2b27c4878d3effd7273">blockNeedsPredicationForAnyReason</a>, <a href="#a07515d0542b797be2d1c87d4359ff8f6">canVectorizeReductions</a>, <a href="#a06f5d9725a2b1f7b06e8bf51f7d31417">collectElementTypesForWidening</a>, <a href="#a12d2850f420726c4acb262b626e95b7d">collectInLoopReductions</a>, <a href="#a0ac5df8f0304981180d602dacb13512c">collectValuesToIgnore</a>, <a href="#a65ab4267c6c132d06451b5d97bc9ee83">computeMaxVF</a>, <a href="#ae4c50e6300599d50ba706c0d2b780502">expectedCost</a>, <a href="#ad8398a35cd187d6a75b460fcf54b5236">getDivRemSpeculationCost</a>, <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>, <a href="#a4e307866e6d65e87d1e6884b0d13306c">getReductionPatternCost</a>, <a href="#a1fa63b37ad2ac06f289e9962a3703e9e">getSmallestAndWidestTypes</a>, <a href="#a5964ce9ba38fe5a4d372242ac39e3f1d">interleavedAccessCanBeWidened</a>, <a href="#a472c49074b0d81970f8eea07de4d7ad4">isLegalMaskedLoad</a>, <a href="#a8c25146329f69e026508656cfb1280fa">isLegalMaskedStore</a>, <a href="#a61375f5189558cc261186f388d31fe92">isOptimizableIVTruncate</a>, <a href="#a0a96f040b7fc3eae004aa6dc2af8f522">isPredicatedInst</a>, <a href="#a405e73f32c9044b8b14648b62cb2ef30">LoopVectorizationCostModel</a>, <a href="#a59a6dd7531c8683174f886ff7698cc63">memoryInstructionCanBeWidened</a>, <a href="#a913ab9c8291000dd3a1c3739194b03e4">requiresScalarEpilogue</a>, <a href="#aad6239ca8b51657f5ebdbd6e51e6ea90">runtimeChecksRequired</a>, <a href="#af9f62350ccdebd24858be552f3fc051c">selectInterleaveCount</a>, <a href="#ae8d11752355845a0e271111de7be7d3a">setCostBasedWideningDecision</a>, <a href="#ab8eb89837d2853e4853ea14379ae3972">setTailFoldingStyles</a>, <a href="#a8178cc5e49d5251d7ca3413b8a434f8f">setVectorizedCallDecision</a> and <a href="#aadd9a9d699ede62468422c7cfab66e99">shouldConsiderInvariant</a>.</p>

</div>
</div>

### LI {#a8c62d3e36a2d815cbfac5a1579ccbb01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* llvm::LoopVectorizationCostModel::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> Info analysis.</p>

<p>Definition at line 1755 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a91466f7a82e967ed765e6d876415a3b7">calculateRegisterUsage</a>, <a href="#a0ac5df8f0304981180d602dacb13512c">collectValuesToIgnore</a>, <a href="#aa650124eefba1fd45866d05306385129">isLegalGatherOrScatter</a> and <a href="#a405e73f32c9044b8b14648b62cb2ef30">LoopVectorizationCostModel</a>.</p>

</div>
</div>

### ORE {#a8b0171a0d29e72189ffad26b9770c464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter* llvm::LoopVectorizationCostModel::ORE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Interface to emit optimization remarks.</p>

<p>Definition at line 1773 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a65ab4267c6c132d06451b5d97bc9ee83">computeMaxVF</a>, <a href="#a405e73f32c9044b8b14648b62cb2ef30">LoopVectorizationCostModel</a> and <a href="#aad6239ca8b51657f5ebdbd6e51e6ea90">runtimeChecksRequired</a>.</p>

</div>
</div>

### PSE {#a35372cc43a297f286fc6c679b14c61d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredicatedScalarEvolution&amp; llvm::LoopVectorizationCostModel::PSE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Predicated scalar evolution analysis.</p>

<p>Definition at line 1752 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a65ab4267c6c132d06451b5d97bc9ee83">computeMaxVF</a>, <a href="#ae4c50e6300599d50ba706c0d2b780502">expectedCost</a>, <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>, <a href="#a405e73f32c9044b8b14648b62cb2ef30">LoopVectorizationCostModel</a>, <a href="#aad6239ca8b51657f5ebdbd6e51e6ea90">runtimeChecksRequired</a>, <a href="#af9f62350ccdebd24858be552f3fc051c">selectInterleaveCount</a> and <a href="#a8178cc5e49d5251d7ca3413b8a434f8f">setVectorizedCallDecision</a>.</p>

</div>
</div>

### TheFunction {#a4384debcd154f44445005e6866afba4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function* llvm::LoopVectorizationCostModel::TheFunction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1775 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a65ab4267c6c132d06451b5d97bc9ee83">computeMaxVF</a>, <a href="#a1fa63b37ad2ac06f289e9962a3703e9e">getSmallestAndWidestTypes</a> and <a href="#a405e73f32c9044b8b14648b62cb2ef30">LoopVectorizationCostModel</a>.</p>

</div>
</div>

### TheLoop {#a664dc60e31d9203d66c9d7a49787b63f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* llvm::LoopVectorizationCostModel::TheLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The loop that we evaluate.</p>

<p>Definition at line 1749 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a91466f7a82e967ed765e6d876415a3b7">calculateRegisterUsage</a>, <a href="#a06f5d9725a2b1f7b06e8bf51f7d31417">collectElementTypesForWidening</a>, <a href="#a12d2850f420726c4acb262b626e95b7d">collectInLoopReductions</a>, <a href="#afcbf4a19be078644e784b539379d59b7">collectInstsToScalarize</a>, <a href="#a0ac5df8f0304981180d602dacb13512c">collectValuesToIgnore</a>, <a href="#a65ab4267c6c132d06451b5d97bc9ee83">computeMaxVF</a>, <a href="#ae4c50e6300599d50ba706c0d2b780502">expectedCost</a>, <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>, <a href="#a4e307866e6d65e87d1e6884b0d13306c">getReductionPatternCost</a>, <a href="#af01e065313d5fcaba9570458faf32429">getWideningDecision</a>, <a href="#a07db8a5919c9879e3327549f20cda2f9">isEpilogueVectorizationProfitable</a>, <a href="#a0a96f040b7fc3eae004aa6dc2af8f522">isPredicatedInst</a>, <a href="#a9a6fbca8c965adeb8016a03ca3de2cac">isProfitableToScalarize</a>, <a href="#a5f5d6f7a1f29874d1e77a889510c879c">isScalarAfterVectorization</a>, <a href="#a20d7c96738b8f59692aec029895f8eb9">isUniformAfterVectorization</a>, <a href="#a405e73f32c9044b8b14648b62cb2ef30">LoopVectorizationCostModel</a>, <a href="#a913ab9c8291000dd3a1c3739194b03e4">requiresScalarEpilogue</a>, <a href="#aad6239ca8b51657f5ebdbd6e51e6ea90">runtimeChecksRequired</a>, <a href="#af9f62350ccdebd24858be552f3fc051c">selectInterleaveCount</a>, <a href="#ae8d11752355845a0e271111de7be7d3a">setCostBasedWideningDecision</a>, <a href="#a8178cc5e49d5251d7ca3413b8a434f8f">setVectorizedCallDecision</a> and <a href="#aadd9a9d699ede62468422c7cfab66e99">shouldConsiderInvariant</a>.</p>

</div>
</div>

### TLI {#a598f8ca344de1cfac7a7985b212bb66b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo* llvm::LoopVectorizationCostModel::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Library Info.</p>

<p>Definition at line 1764 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a0ac5df8f0304981180d602dacb13512c">collectValuesToIgnore</a>, <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>, <a href="#ad1f0755693a05c2b008e9a576c3b162b">getVectorCallCost</a>, <a href="#a5abced3ab870d7abf57f2b35a02cd041">getVectorIntrinsicCost</a>, <a href="#a405e73f32c9044b8b14648b62cb2ef30">LoopVectorizationCostModel</a> and <a href="#a8178cc5e49d5251d7ca3413b8a434f8f">setVectorizedCallDecision</a>.</p>

</div>
</div>

### TTI {#a3dfa67eb67a32ca048b4af8fae5c898d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetTransformInfo&amp; llvm::LoopVectorizationCostModel::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector target information.</p>

<p>Definition at line 1761 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a91466f7a82e967ed765e6d876415a3b7">calculateRegisterUsage</a>, <a href="#a06f5d9725a2b1f7b06e8bf51f7d31417">collectElementTypesForWidening</a>, <a href="#a12d2850f420726c4acb262b626e95b7d">collectInLoopReductions</a>, <a href="#a65ab4267c6c132d06451b5d97bc9ee83">computeMaxVF</a>, <a href="#ad8398a35cd187d6a75b460fcf54b5236">getDivRemSpeculationCost</a>, <a href="#a556ec90a0fa1e168a9f22db1deb1fee6">getInstructionCost</a>, <a href="#a4e307866e6d65e87d1e6884b0d13306c">getReductionPatternCost</a>, <a href="#ad1f0755693a05c2b008e9a576c3b162b">getVectorCallCost</a>, <a href="#a5abced3ab870d7abf57f2b35a02cd041">getVectorIntrinsicCost</a>, <a href="#a5964ce9ba38fe5a4d372242ac39e3f1d">interleavedAccessCanBeWidened</a>, <a href="#a07db8a5919c9879e3327549f20cda2f9">isEpilogueVectorizationProfitable</a>, <a href="#aa650124eefba1fd45866d05306385129">isLegalGatherOrScatter</a>, <a href="#a472c49074b0d81970f8eea07de4d7ad4">isLegalMaskedLoad</a>, <a href="#a8c25146329f69e026508656cfb1280fa">isLegalMaskedStore</a>, <a href="#a61375f5189558cc261186f388d31fe92">isOptimizableIVTruncate</a>, <a href="#ac864682b9dcdc0ce83df845bf6cfb2e8">isScalarWithPredication</a>, <a href="#a405e73f32c9044b8b14648b62cb2ef30">LoopVectorizationCostModel</a>, <a href="#af9f62350ccdebd24858be552f3fc051c">selectInterleaveCount</a>, <a href="#ae8d11752355845a0e271111de7be7d3a">setCostBasedWideningDecision</a>, <a href="#ab8eb89837d2853e4853ea14379ae3972">setTailFoldingStyles</a>, <a href="#a8178cc5e49d5251d7ca3413b8a434f8f">setVectorizedCallDecision</a> and <a href="#a23c31233960bfc62d1cc93bb4a5f5148">usePredicatedReductionSelect</a>.</p>

</div>
</div>

### ValuesToIgnore {#a7e207263ca75f2bfc5eb562a213bc575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const Value *, 16&gt; llvm::LoopVectorizationCostModel::ValuesToIgnore</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Values to ignore in the cost model.</p>

<p>Definition at line 1785 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a91466f7a82e967ed765e6d876415a3b7">calculateRegisterUsage</a>, <a href="#a06f5d9725a2b1f7b06e8bf51f7d31417">collectElementTypesForWidening</a>, <a href="#a0ac5df8f0304981180d602dacb13512c">collectValuesToIgnore</a> and <a href="#ae4c50e6300599d50ba706c0d2b780502">expectedCost</a>.</p>

</div>
</div>

### VecValuesToIgnore {#a91945cb39ed4c6676d991a9528dcd2d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const Value *, 16&gt; llvm::LoopVectorizationCostModel::VecValuesToIgnore</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Values to ignore in the cost model when VF &gt; 1.</p>

<p>Definition at line 1788 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>


<p>Referenced by <a href="#a91466f7a82e967ed765e6d876415a3b7">calculateRegisterUsage</a>, <a href="#a0ac5df8f0304981180d602dacb13512c">collectValuesToIgnore</a> and <a href="#ae4c50e6300599d50ba706c0d2b780502">expectedCost</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CallWideningDecisions {#aa9761802e2f0c3bb684179023d0ff711}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallDecisionList llvm::LoopVectorizationCostModel::CallWideningDecisions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1720 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### ChosenTailFoldingStyle {#abb4943fb908288e581908a0fc56153a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;std::pair&lt;TailFoldingStyle, TailFoldingStyle&gt; &gt; llvm::LoopVectorizationCostModel::ChosenTailFoldingStyle</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Control finally chosen tail folding style.</p>


<p>The first element is used if the IV update may overflow, the second element - if it does not.</p>


<p>Definition at line 1644 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### ForcedScalars {#ade5f41ac1ba74cbc8c1adc4c46e29812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ElementCount, SmallPtrSet&lt;Instruction *, 4&gt; &gt; llvm::LoopVectorizationCostModel::ForcedScalars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds the instructions (address computations) that are forced to be scalarized.</p>

<p>Definition at line 1671 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### InLoopReductionImmediateChains {#a5cb052e45c60c073f4e6e05e79e68c0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Instruction *, Instruction *&gt; llvm::LoopVectorizationCostModel::InLoopReductionImmediateChains</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A Map of inloop reduction operations and their immediate chain operand.</p>


<p>FIXME: This can be removed once reductions can be costed correctly in <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>. This was added to allow quick lookup of the inloop operations.</p>


<p>Definition at line 1679 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### InLoopReductions {#ac025f929ec31e3c10c997a2e82c6b034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;PHINode *, 4&gt; llvm::LoopVectorizationCostModel::InLoopReductions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PHINodes of the reductions that should be expanded in-loop.</p>

<p>Definition at line 1674 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### InstsToScalarize {#a3713624a2daa27a85f4b79153394398a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ElementCount, ScalarCostsTy&gt; llvm::LoopVectorizationCostModel::InstsToScalarize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A map holding scalar costs for different vectorization factors.</p>


<p>The presence of a cost for an instruction in the mapping indicates that the instruction will be scalarized when vectorizing with the associated vectorization factor. The entries are VF-ScalarCostTy pairs.</p>


<p>Definition at line 1659 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### IsScalableVectorizationAllowed {#a3640d157cd9cb23ed37933475b0a20f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::LoopVectorizationCostModel::IsScalableVectorizationAllowed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>true if scalable vectorization is supported and enabled.</p>

<p>Definition at line 1647 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### MaxSafeElements {#a4ab7e76bb8a0d205cfa13351b0dfae32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;unsigned&gt; llvm::LoopVectorizationCostModel::MaxSafeElements</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maximum safe number of elements to be processed per vector iteration, which do not prevent store-load forwarding and are safe with regard to the memory dependencies.</p>


<p>Required for EVL-based veectorization, where this value is used as the upper bound of the safe AVL.</p>


<p>Definition at line 1653 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### MinBWs {#a2f50fc0d0512a2412fff5a6a1132c3b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;Instruction *, uint64_t&gt; llvm::LoopVectorizationCostModel::MinBWs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map of scalar integer values to the smallest bitwidth they can be legally represented as.</p>


<p>The vector equivalents of these values should be truncated to this type.</p>


<p>Definition at line 1620 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### NumPredStores {#a8156223056c7fbdd5c8150d2fe4b7dc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoopVectorizationCostModel::NumPredStores = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1558 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### PredicatedBBsAfterVectorization {#afd39f031902ddbca84a441ce108fee1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ElementCount, SmallPtrSet&lt;BasicBlock *, 4&gt; &gt; llvm::LoopVectorizationCostModel::PredicatedBBsAfterVectorization</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A set containing all BasicBlocks that are known to present after vectorization as a predicated block.</p>

<p>Definition at line 1630 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### ScalarEpilogueStatus {#afbb186bdec9b34efe2c9398f1963aef1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEpilogueLowering llvm::LoopVectorizationCostModel::ScalarEpilogueStatus = <a href="/web-llvm/docs/api/namespaces/llvm/#ab5d4f35a197e7b0f2320bdbbf518bd9da65f7ef37c3a0cd826b5e361e8cf32cf7">CM_ScalarEpilogueAllowed</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Records whether it is allowed to have the original scalar loop execute at least once.</p>


<p>This may be needed as a fallback loop in case runtime aliasing/dependence checks fail, or to handle the tail/remainder iterations when the trip count is unknown or doesn't divide by the VF, or as a peel-loop to handle gaps in interleave-groups. Under optsize and when the trip count is very small we don't allow any iterations to execute in the scalar loop.</p>


<p>Definition at line 1639 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### Scalars {#a3e5401d78114cb93b8784701c3051a72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ElementCount, SmallPtrSet&lt;Instruction *, 4&gt; &gt; llvm::LoopVectorizationCostModel::Scalars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds the instructions known to be scalar after vectorization.</p>


<p>The data is collected per VF.</p>


<p>Definition at line 1667 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### Uniforms {#a0152151c757d7aa0c4cee9c919666ddc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ElementCount, SmallPtrSet&lt;Instruction *, 4&gt; &gt; llvm::LoopVectorizationCostModel::Uniforms</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds the instructions known to be uniform after vectorization.</p>


<p>The data is collected per VF.</p>


<p>Definition at line 1663 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

### WideningDecisions {#ad49214633145ca13a71c8c9a91fdfab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecisionList llvm::LoopVectorizationCostModel::WideningDecisions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1715 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp">LoopVectorize.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
