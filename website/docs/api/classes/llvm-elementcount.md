---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/elementcount
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ElementCount` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::ElementCount { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">llvm/Support/TypeSize.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity">FixedOrScalableQuantity&lt;LeafTy, ValueTy&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1662d2464a3ae04b13933a2ac948a2b6">ElementCount</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7b2380b93e4190f3c05c42846440f3c">ElementCount</a> (ScalarTy MinVal, bool Scalable)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5df7a0866c0cbc7cd343ec43621d4da">ElementCount</a> (const FixedOrScalableQuantity&lt; ElementCount, unsigned &gt; &amp;V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a991f269cde2e7fbcb254ef371efc8d1a">isScalar</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Exactly one element. <a href="#a991f269cde2e7fbcb254ef371efc8d1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a098a514da47d00e1176aa2e16eacfb70">isVector</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>One or more elements. <a href="#a098a514da47d00e1176aa2e16eacfb70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a584cb8dfa0090b33a969c4dda27337f6">getFixed</a> (ScalarTy MinVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bddc4949ab247dd1474f79b9bc6e34e">getScalable</a> (ScalarTy MinVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79ea372f9aa69492fccfafc0e5a1589c">get</a> (ScalarTy MinVal, bool Scalable)</td>
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


<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ElementCount() {#a1662d2464a3ae04b13933a2ac948a2b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ElementCount::ElementCount ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a57beba2321012fb9cb702573f26fefff">llvm::details::FixedOrScalableQuantity&lt; ElementCount, unsigned &gt;::FixedOrScalableQuantity</a>.</p>


<p>Referenced by <a href="#a79ea372f9aa69492fccfafc0e5a1589c">get</a>, <a href="#a584cb8dfa0090b33a969c4dda27337f6">getFixed</a> and <a href="#a1bddc4949ab247dd1474f79b9bc6e34e">getScalable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ElementCount() {#aa7b2380b93e4190f3c05c42846440f3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ElementCount::ElementCount (<a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#acedfd762498bd93768c82e145023a2e9">ScalarTy</a> MinVal, bool Scalable)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>

</div>
</div>

### ElementCount() {#ad5df7a0866c0cbc7cd343ec43621d4da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ElementCount::ElementCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a57beba2321012fb9cb702573f26fefff">FixedOrScalableQuantity</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a>, unsigned &gt; &amp; V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isScalar() {#a991f269cde2e7fbcb254ef371efc8d1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ElementCount::isScalar ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Exactly one element.</p>

<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; ElementCount, unsigned &gt;::getKnownMinValue</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; ElementCount, unsigned &gt;::isScalable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a362f793f3254317c698e3560548788a5">areRuntimeChecksProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#afcbf4a19be078644e784b539379d59b7">llvm::LoopVectorizationCostModel::collectInstsToScalarize</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ab4a3f06ac8f2aff57b864c2d8ace97d8">llvm::LoopVectorizationCostModel::collectUniformsAndScalars</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a4adc69fc8f74164e990cce6afc1e061b">llvm::LoopVectorizationPlanner::computeBestVF</a>, <a href="/web-llvm/docs/api/structs/llvm/vpfirstorderrecurrencephirecipe/#a465d0006e51f34ba35fccf2cb3f72f89">llvm::VPFirstOrderRecurrencePHIRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#ac2e757808f897dbb866fac9b8ad2f045">llvm::VPWidenCastRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#aa948ba905ff37c533b3c85068f94fd24">llvm::VPRegionBlock::cost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencanonicalivrecipe/#a06435ca2ee49b05bd4d93bdbb3b7d8e6">llvm::VPWidenCanonicalIVRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ae4c50e6300599d50ba706c0d2b780502">llvm::LoopVectorizationCostModel::expectedCost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#aa29e19b06aa800d1289048b54c58e8c6">llvm::LoopVectorizationCostModel::getCallWideningDecision</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a7e79d5a868530c399fc615b99b3f02ab">getCopyToPartsVector</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a644495365c2a3cd22d5b308ba96f41da">llvm::GCNTTIImpl::getMaxInterleaveFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/r600ttiimpl/#a8bfce9237a4882c6862de27708677f5c">llvm::R600TTIImpl::getMaxInterleaveFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a6fc00f70e954c5d710caf7dbe7c231ce">llvm::RISCVTTIImpl::getMaxInterleaveFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a7ecff78284bb90e68510b954c3487ab6">llvm::X86TTIImpl::getMaxInterleaveFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a3f4445d350e1253b4c05ab25011d766d">llvm::AArch64TargetLowering::getNumRegistersForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a59ae7f93fccb0ae431e82f8d74ba443c">llvm::TargetLoweringBase::getPreferredVectorAction</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a4e307866e6d65e87d1e6884b0d13306c">llvm::LoopVectorizationCostModel::getReductionPatternCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a0f1ad23af20c2a0b3e3f5c0a995c1969">llvm::AArch64TargetLowering::getRegisterTypeForCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acde9dba6a8593e7236d548082d3e39e5">llvm::TargetLoweringBase::getTypeConversion</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ad1f0755693a05c2b008e9a576c3b162b">llvm::LoopVectorizationCostModel::getVectorCallCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#afd413c038500ff13a7a888e65d8777ce">llvm::TargetLoweringBase::getVectorTypeBreakdown</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a5f5d6f7a1f29874d1e77a889510c879c">llvm::LoopVectorizationCostModel::isScalarAfterVectorization</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ac864682b9dcdc0ce83df845bf6cfb2e8">llvm::LoopVectorizationCostModel::isScalarWithPredication</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#a86e581cb8e98cb0649e8b524eed5c9c0">llvm::LoopVectorizationLegality::isUniform</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a20d7c96738b8f59692aec029895f8eb9">llvm::LoopVectorizationCostModel::isUniformAfterVectorization</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a83114915b4f7fec94a20efa3834a8250">maybeVectorizeType</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a2206e77c573f4947146faa681ea8855e">llvm::LoopVectorizationPlanner::planInVPlanNativePath</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#af9f62350ccdebd24858be552f3fc051c">llvm::LoopVectorizationCostModel::selectInterleaveCount</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ab8e5bf6d340d3b3f704b6398996ae51c">llvm::LoopVectorizationCostModel::setCallWideningDecision</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ae8d11752355845a0e271111de7be7d3a">llvm::LoopVectorizationCostModel::setCostBasedWideningDecision</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a8178cc5e49d5251d7ca3413b8a434f8f">llvm::LoopVectorizationCostModel::setVectorizedCallDecision</a> and <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a760fb390c24b907500c0a181fada9590">llvm::VPRecipeBuilder::tryToCreateWidenRecipe</a>.</p>

</div>
</div>

### isVector() {#a098a514da47d00e1176aa2e16eacfb70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ElementCount::isVector ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>One or more elements.</p>

<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#ac4ab9dd9440c55bee1aa4a1195cee759">llvm::details::FixedOrScalableQuantity&lt; ElementCount, unsigned &gt;::getKnownMinValue</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; ElementCount, unsigned &gt;::isScalable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a91466f7a82e967ed765e6d876415a3b7">llvm::LoopVectorizationCostModel::calculateRegisterUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#aa8c00664c6be2042407f13e4fcad950b">llvm::LoopVectorizationCostModel::canTruncateToMinimalBitwidth</a>, <a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe/#a6def10381cc09d92342a6846fe1174e0">llvm::VPHistogramRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebase/#ac84a2bc6b484c5d3a03e80ce40f0a14c">llvm::VPRecipeBase::cost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencanonicalivrecipe/#a06435ca2ee49b05bd4d93bdbb3b7d8e6">llvm::VPWidenCanonicalIVRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ae4c50e6300599d50ba706c0d2b780502">llvm::LoopVectorizationCostModel::expectedCost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#acec08d690b0cd43dfa708f6dd754712d">getStepVector</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#af7844564539b9f0f917e8f2380a064b3">llvm::LoopVectorizationCostModel::getWideningCost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#af01e065313d5fcaba9570458faf32429">llvm::LoopVectorizationCostModel::getWideningDecision</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#aa650124eefba1fd45866d05306385129">llvm::LoopVectorizationCostModel::isLegalGatherOrScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a9a6fbca8c965adeb8016a03ca3de2cac">llvm::LoopVectorizationCostModel::isProfitableToScalarize</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ac864682b9dcdc0ce83df845bf6cfb2e8">llvm::LoopVectorizationCostModel::isScalarWithPredication</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#aca6160bb3d669e9ce01f91b124e7e0a1">llvm::LoopVectorizationPlanner::plan</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#af9f62350ccdebd24858be552f3fc051c">llvm::LoopVectorizationCostModel::selectInterleaveCount</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a8178cc5e49d5251d7ca3413b8a434f8f">llvm::LoopVectorizationCostModel::setVectorizedCallDecision</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a9c44a42299ed9e7e97200271b00e0c7a">llvm::LoopVectorizationCostModel::setWideningDecision</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#abc1b952dd1661ccba4f999610bf9732e">llvm::LoopVectorizationCostModel::setWideningDecision</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#af378bb1e037306d9cfd4bb0b49ba55f9">willGenerateVectors</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#a79ea372f9aa69492fccfafc0e5a1589c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr ElementCount llvm::ElementCount::get (<a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#acedfd762498bd93768c82e145023a2e9">ScalarTy</a> MinVal, bool Scalable)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>References <a href="#a1662d2464a3ae04b13933a2ac948a2b6">ElementCount</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#aea2efb72b66f0b71d52898a155f20ab0">llvm::details::FixedOrScalableQuantity&lt; ElementCount, unsigned &gt;::Scalable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#addd1c6bc523b9a0eb56167da95dc5156">llvm::ConstantFoldShuffleVectorInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a0b91e092434338369b2e1995b87f0c5b">determineVPlanVF</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/#a2cea2a552183ce91c9617c732d395ee0">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::emitStackSlotRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/vectortype/#a417f5824a665662b7c3ca5439d257b4d">llvm::sandboxir::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#af2bc88fa949977374572b32de0224b03">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a59632c5deb0423a518ad984bdd04d41f">llvm::VectorType::getElementCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb74ac5c2f2a45c7247a785f898d4833">llvm::getGCDType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55a2f0d67720407fe032276991d5111b">llvm::getLCMType</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#afe8782d2d7b943ba08f9b93173d1a7ab">llvm::TargetTransformInfoImplBase::getMinimumVF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a03fe0007df15a56e14d2403acfff1af7">llvm::getOptionalElementCountLoopAttribute</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a15f3027fdcad3b33960402d9739afe4b">llvm::EVT::getPow2VectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#af5d482532f3f9df9fed007e78e983dcd">llvm::MVT::getPow2VectorType</a>, <a href="/web-llvm/docs/api/structs/llvm/intrinsic/iitdescriptor/#a2939c2224325c678cad4d045e7f8d791">llvm::Intrinsic::IITDescriptor::getVector</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#aa1abe2e0d36a43d780ce54ea3b197217">llvm::MVT::getVectorElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#a50cae5c2df432357d50f182d310ce7b7">llvm::LoopVectorizeHints::getWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2ffccbb574e8a2cf63b8ede89f53090b">llvm::LegalizerHelper::moreElementsVector</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a1119c30ad17d23efa29bf5593774867d">anonymous{MIParser.cpp}::MIParser::parseLowLevelType</a>.</p>

</div>
</div>

### getFixed() {#a584cb8dfa0090b33a969c4dda27337f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr ElementCount llvm::ElementCount::getFixed (<a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#acedfd762498bd93768c82e145023a2e9">ScalarTy</a> MinVal)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Reference <a href="#a1662d2464a3ae04b13933a2ac948a2b6">ElementCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#a8bde7bea5a6d6a50fd5b6d03d746e05b">addMappingsFromTLI</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a362f793f3254317c698e3560548788a5">areRuntimeChecksProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ac50dd9fe6220347f8306e3694a8129cb">llvm::LegalizerHelper::bitcastExtractVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a0aab1c76215e1773caa058744d6ae6af">bitcastToVectorElement32</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a91466f7a82e967ed765e6d876415a3b7">llvm::LoopVectorizationCostModel::calculateRegisterUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#af0e9f16b79d49af44209f202b31290a1">llvm::CastInst::castIsValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#a4fff4e593b92ebdfd3e0e394d52fa817">llvm::LegalizeMutations::changeElementCountTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#a0ac1646365dca61b7727ec5291144c38">llvm::LegalizeMutations::changeElementCountTo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a3b9d49f459b9596f73c60edab6e92673">llvm::LegalizeRuleSet::clampMaxNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a4adc69fc8f74164e990cce6afc1e061b">llvm::LoopVectorizationPlanner::computeBestVF</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a65ab4267c6c132d06451b5d97bc9ee83">llvm::LoopVectorizationCostModel::computeMaxVF</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a40ed7274ff11f079e5b5eae34c818c51">llvm::IRBuilderBase::CreateVectorSplat</a>, <a href="/web-llvm/docs/api/structs/llvm/vectorizationfactor/#acd24dfdad4f887e1f7b10c9039a05930">llvm::VectorizationFactor::Disabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#ae2198d73f3c2de2cee53f3d15db39abe">expandAbs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#adc12bf3c911b1e25c4a14ce8f4ad7634">expandAnyOrAllIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#ab26ebd710695202964347075355c501d">expandExpIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a8be283da675a1b678e17fd283f14945c">expandLogIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a7b29eea052e72ee9e9d598d992aa82e2">expandStepIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a3b5805e73f162bbb84584fbc2091806e">fewerEltsToSize64Vector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aac9e947d00e373eba50e79fd0da66792">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/#a7d3b40cff3ff8c00007cf9a3f0d785f1">llvm::slpvectorizer::BoUpSLP::ShuffleCostEstimator::gather</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a639711ef50cb300db9e9ade1445ccf07">getBitcastRegisterType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a7e79d5a868530c399fc615b99b3f02ab">getCopyToPartsVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa47ab206f485fe45e4d8a882ff00fd42">llvm::getCoverTy</a>, <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero/#a36b782c6eb416c7d3b1086d5f50b2e54">llvm::ConstantAggregateZero::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#aa0e2f7f2755f0a5cb30f1cc35957cb27">llvm::ConstantExpr::getGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#ad36adfb48960b5f9ae2e61aefad72e70">llvm::HexagonTTIImpl::getMinimumVF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aabc73c20ee69fa5d4e1cb3318c074963">getNarrowTypeBreakDown</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#ae6dc00935578ac3d7b43326b5f02b2bc">getPow2VectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a074d013c7183283d9aaa8d7127057242">llvm::ConstantDataVector::getRaw</a>, <a href="/web-llvm/docs/api/structs/llvm/vfshape/#ac7db4cdbe016c25c229740fceb0bd2a1">llvm::VFShape::getScalarShape</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/lookaheadheuristics/#a266c328585c72cd84dc48ef488acef49">llvm::slpvectorizer::BoUpSLP::LookAheadHeuristics::getShallowScore</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ac16a7b224b20beeecf5f1665b4bcc65f">llvm::AArch64TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a44124e702dc442346bd6202bb03e593b">llvm::ConstantDataVector::getSplat</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-d1a24269cf97e06932cf3d8a482d2077/#af17c126a5f1075975952d1bf898b08d3">llvm::DenseMapInfo&lt; ElementCount, void &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a8a8b818a539c2cbbe1a954a875c5fcec">getVectorCallCosts</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#afd413c038500ff13a7a888e65d8777ce">llvm::TargetLoweringBase::getVectorTypeBreakdown</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac477f229337de92be9c48dae99bf5546">llvm::AArch64TargetLowering::getVectorTypeBreakdownForCallingConv</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp/#a6c8fb06bafca9d7d42e44c4f22669947">getVectorTypeBreakdownMVT</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a15113486c66611b76318afc2c37352c3">llvm::TargetLibraryInfoImpl::getWidestVF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae641260d79a9242ccf378d9a7949fdc3">llvm::isTLIScalarize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6bc9d4e47e8a41e60f4bedae712f0c03">legalizeAndOptimizeInductions</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af4667ecbc4447b41863430fb572d8f82">llvm::AMDGPULegalizerInfo::legalizeLaneOp</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#af5a8919ec199949c9c5241e6c59872b5">llvm::LLT::LLT</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#aa68245d8ed8fafd80a06d5092f434093">llvm::LoopVectorizeHints::LoopVectorizeHints</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp/#ace2b635ecd7fc6de3eb1f8a95530d08d">mutationIsSane</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a52b55ad3935a5bf9e80c9c2f9bb501af">numVectorEltsOrZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abc2faab09dd74a706e426de046a3f4a0">performVSelectCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#aca6160bb3d669e9ce01f91b124e7e0a1">llvm::LoopVectorizationPlanner::plan</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a2206e77c573f4947146faa681ea8855e">llvm::LoopVectorizationPlanner::planInVPlanNativePath</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a27cad9bebff39ed9ba603074dda1335e">replaceWithCallToVeclib</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a0d3ab70393b799b3be4875c3334a4f42">llvm::LoopVectorizePass::runImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a0b6b1ae088cb8ca3aa4f26c4098daa3d">llvm::LoopVectorizationPlanner::selectEpilogueVectorizationFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ae8d11752355845a0e271111de7be7d3a">llvm::LoopVectorizationCostModel::setCostBasedWideningDecision</a>, <a href="/web-llvm/docs/api/classes/llvm/vectorbuilder/#a4e4d4ef05ee67389f699fbc2ec8fa864">llvm::VectorBuilder::setStaticVL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#ab4c2bc39e4119d3c2098986cfd7be179">splitUnequalType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ad2c874bad47bf92187afb13eb2840643">llvm::LLT::token</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a998af925aaf7778f8971a7ac616faefd">llvm::toVectorTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a46c9ccb087f925d00317f16577410a13">llvm::VFABI::tryDemangleForVFABI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a1bc5915736e0e4317a049e55fa502667">llvm::LegalizationArtifactCombiner::tryFoldUnmergeCast</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#abcf8c2b35316773f1ab0ba70aeb2a6de">llvm::LoopVectorizeHints::vectorizeAnalysisPassName</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#acbd3ab3957032feb181df036bb6a8d27">widenToNextPowerOf2</a>.</p>

</div>
</div>

### getScalable() {#a1bddc4949ab247dd1474f79b9bc6e34e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr ElementCount llvm::ElementCount::getScalable (<a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#acedfd762498bd93768c82e145023a2e9">ScalarTy</a> MinVal)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Reference <a href="#a1662d2464a3ae04b13933a2ac948a2b6">ElementCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#a8bde7bea5a6d6a50fd5b6d03d746e05b">addMappingsFromTLI</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#aae70ddddbfd05ed5831918fa1836b947">llvm::AArch64TTIImpl::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24fb14e02fa8e4a261838b46074e42fa">llvm::AArch64TTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a2d97ecc1d468027ddd95cb7399aaceb0">anonymous{VFABIDemangler.cpp}::getElementCountForTy</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-d1a24269cf97e06932cf3d8a482d2077/#aa1933320bd488c430561180d187bc10c">llvm::DenseMapInfo&lt; ElementCount, void &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#aa47f57320f9f28895b6df6b5eb0f9dfa">llvm::AArch64TTIImpl::getGatherScatterOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a0ed0459656c8a2378156bf244c7e2087">llvm::AArch64TTIImpl::getMaskedMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a6c8d73add4e552328f931ce1681c494f">llvm::AArch64TTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#adb7e05c95393c231260785fc1ce4700b">llvm::AArch64TTIImpl::getMinMaxReductionCost</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a0a09a1144b3dbb1ddc00f0ced5030522">anonymous{VFABIDemangler.cpp}::getScalableECFromSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a005211a6c7f26317af98d088c06f0f64">llvm::AArch64TTIImpl::getSpliceCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acde9dba6a8593e7236d548082d3e39e5">llvm::TargetLoweringBase::getTypeConversion</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a15113486c66611b76318afc2c37352c3">llvm::TargetLibraryInfoImpl::getWidestVF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae641260d79a9242ccf378d9a7949fdc3">llvm::isTLIScalarize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4eaae576935c3d68f63d9207bd5da494">LowerSVEIntrinsicEXT</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#aca6160bb3d669e9ce01f91b124e7e0a1">llvm::LoopVectorizationPlanner::plan</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae614d7a67bd01700a068c8e4eb6e2ef9">llvm::LLT::scalable_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3c8d482078435a16e34c2cc13caa6f75">llvm::LLT::scalable_vector</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad4340bab6e118d0614449e74a779b30c">tryCombineWhileLo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
